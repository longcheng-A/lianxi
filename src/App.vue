<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
};
import Vue from "vue";
import Vant from "vant";
import "vant/lib/index.css";

Vue.use(Vant);
</script>

<style>
</style>
