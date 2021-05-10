<template>
  <div> Hello World! My name is {{ userName }}.</div>
</template>
<script>

export default {
  setup(props) {
    // TODO
  },
  data() {
    return {
      name: 'Chong',
    };
  },
  computed: {
    userName() {
      return this.name ?? 'Charles'; // support by Babel 7
    },
  },
}
</script>

