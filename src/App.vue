<template>
  <div>
    <Navbar />
    <el-container>
      <router-view />
    </el-container>
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";

export default {
  name: "app",
  components: {
    Navbar,
  },
};
</script>

<style>
*{
	margin: 0;
	padding: 0;
	list-style: none;
	text-decoration: none;
	border: none;
	outline: none;
}
</style>
