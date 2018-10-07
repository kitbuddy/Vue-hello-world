<template>

  <section class="header-main">
    <div>
     this is headerMain vue component
    </div>
    <div name="animateMessage">
      <button id="show-modal" v-on:click="showMessage = !showMessage">show message</button>
        <transition name="actionFade">
        <div id="message" v-if="showMessage"> 
            <h3>this is modal Message</h3>
        </div>
  </transition>
</div>
  </section>

</template>

<script>
import Vue from "vue";

Vue.component("headerMain", {});
export default {
  name: "headerMain",
  props: [],
  mounted() {},
  data: function() {
    return {
      showMessage: false
    };
  },
  methods: {},
  computed: {}
};
</script>

<style scoped>
.header-main {
  height: 50px;
  background-color: gray;
  margin-top: 0%;
}

#message {
  position: absolute;
}
</style>
