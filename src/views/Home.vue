<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <el-input v-model="input" placeholder="请输入内容"></el-input>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloWorld from "../components/HelloWorld.vue";

export default defineComponent({
  name: "Home",
  data() {
    return {
      input: "",
    };
  },
  components: {
    HelloWorld,
  },
  setup() {
    return {};
  },
});
</script>

<style scoped></style>
