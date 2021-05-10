# Vue3 + TypeScript + webpack

## 步骤
1. ```npm install -D webpack webpack-cli@3.3.12 webpack-dev-server``` 这里遇到cli的坑，不安装这个低版本的话会报 
Cannot find module 'webpack-cli/bin/config-yargs'
2. ```npm install -D html-webpack-plugin```
3. ```npm install -D vue-loader@next @vue/compiler-sfc``` （这个编译器代替了
vue-template-compiler，需研究一下）
4. ```npm install -D css-loader style-loader```
5. ```npm install -D file-loader url-loader``` 图片处理
6. ```npm install -D @babel/core @babel/cli @babel/preset-env babel-loader```
7. ```npm install @babel/polyfill```
8. ```npm install vue@next @vue/cli@next vue-router vuex``` 未来尤雨溪会把Vue3作为主版本，届时无需再加'next'

## 参考文章：
https://www.cnblogs.com/xyzhanjiang/p/13272975.html

