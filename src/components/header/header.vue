<template>

  <section class="header">
    <span class='autoHeader'>
    <h1>My header Component</h1>
<span>
  </section>

</template>

<script lang="ts">
import Vue from "vue";

Vue.component("my-component-name", {
  // ... options ...
});
export default {
  name: "header",
  props: [],
  mounted() {},
  data() {
    return {};
  },
  methods: {},
  computed: {}
};
</script>

<style scoped lang="less">
.header {
  background-color: aqua
}

.autoHeader {
  background-color: blue height 200px;
}
</style>
