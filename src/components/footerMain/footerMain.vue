<template>

  <section class="footerMain">
    <div>
     this is headerMain vue component
    </div>
  </section>

</template>

<script>
import Vue from "vue";

Vue.component("footerMain", {
  // ... options ...
});
export default {
  name: "footerMain",
  props: [],
  mounted() {},
  data() {
    return {};
  },
  methods: {},
  computed: {}
};
</script>

<style scoped>
.footerMain {
  height: 50px;
  background-color: black;
  margin-bottom: 0%
}
</style>
