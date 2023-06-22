<template>
  <NavBar></NavBar>
  <MainPage></MainPage>
  <ChartPage></ChartPage>
  <ServicePage></ServicePage>
  <CategoryPage></CategoryPage>
</template>

<script>
import CategoryPage from "../components/CategoryPage";
import ServicePage from "../components/ServicePage";
import ChartPage from "../components/ChartPage";
import MainPage from "../components/MainPage";
import NavBar from "../components/NavBar";
// @ is an alias to /src

export default {
  name: "HomeView",
  components: {
    CategoryPage,
    ServicePage,
    ChartPage,
    MainPage,
    NavBar,
  },
};
</script>
