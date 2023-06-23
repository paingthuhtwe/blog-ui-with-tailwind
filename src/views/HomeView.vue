<template>
  <NavBar></NavBar>
  <MainPage></MainPage>
  <ChartPage></ChartPage>
  <ServicePage></ServicePage>
  <CategoryPage></CategoryPage>
  <CoursePage></CoursePage>
  <ExperiencePage></ExperiencePage>
  <ReviewPage></ReviewPage>
</template>

<script>
import ReviewPage from "../components/ReviewPage";
import ExperiencePage from "../components/ExperiencePage";
import CoursePage from "../components/CoursePage";
import CategoryPage from "../components/CategoryPage";
import ServicePage from "../components/ServicePage";
import ChartPage from "../components/ChartPage";
import MainPage from "../components/MainPage";
import NavBar from "../components/NavBar";
// @ is an alias to /src

export default {
  name: "HomeView",
  components: {
    ReviewPage,
    ExperiencePage,
    CoursePage,
    CategoryPage,
    ServicePage,
    ChartPage,
    MainPage,
    NavBar,
  },
};
</script>
