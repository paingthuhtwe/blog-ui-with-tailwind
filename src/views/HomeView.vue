<template>
  <NavBar></NavBar>
  <MainPage></MainPage>
</template>

<script>
import MainPage from "../components/MainPage";
import NavBar from "../components/NavBar";
// @ is an alias to /src

export default {
  name: "HomeView",
  components: {
    MainPage,
    NavBar,
  },
};
</script>
