<template>
    <div>{{title}}</div>
</template>

<script>
export default {
  data() {
    return { title: 'Check me' }
  },
  methods: {
    check() { this.checked = !this.checked; }
  }
};
</script>
