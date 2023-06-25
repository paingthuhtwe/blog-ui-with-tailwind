<template>
  <NavBar></NavBar>
  <MainPage></MainPage>
  <ChartPage></ChartPage>
  <ServicePage></ServicePage>
  <CategoryPage></CategoryPage>
  <CoursePage></CoursePage>
  <ExperiencePage></ExperiencePage>
  <ReviewPage></ReviewPage>
  <PartnerPage></PartnerPage>
  <FooterPage></FooterPage>
</template>

<script>
import FooterPage from "../components/FooterPage";
import PartnerPage from "../components/PartnerPage";
import ReviewPage from "../components/ReviewPage";
import ExperiencePage from "../components/ExperiencePage";
import CoursePage from "../components/CoursePage";
import CategoryPage from "../components/CategoryPage";
import ServicePage from "../components/ServicePage";
import ChartPage from "../components/ChartPage";
import MainPage from "../components/MainPage";
import NavBar from "../components/NavBar";
import ScrollReveal from "scrollreveal";
import { onMounted } from "vue";

// @ is an alias to /src

export default {
  name: "HomeView",
  components: {
    FooterPage,
    PartnerPage,
    ReviewPage,
    ExperiencePage,
    CoursePage,
    CategoryPage,
    ServicePage,
    ChartPage,
    MainPage,
    NavBar,
  },
  setup() {
    onMounted(() => {
      let sr = ScrollReveal();
      // for top
      sr.reveal(".scroll-top", {
        reset: true,
        mobile: false,
        duration: 1000,
        delay: 100,
        distance: "200px",
        easing: "ease-out",
        origin: "top",
      });
      // for bottom
      sr.reveal(".scroll-bottom", {
        reset: true,
        mobile: false,
        duration: 1000,
        delay: 100,
        distance: "200px",
        easing: "ease-out",
        origin: "bottom",
      });
      sr.reveal(".scroll-bottom-1", {
        reset: true,
        mobile: false,
        duration: 1400,
        delay: 100,
        distance: "200px",
        easing: "ease-out",
        origin: "bottom",
      });
      sr.reveal(".scroll-bottom-2", {
        reset: true,
        mobile: false,
        duration: 1800,
        delay: 100,
        distance: "200px",
        easing: "ease-out",
        origin: "bottom",
      });
      sr.reveal(".scroll-bottom-3", {
        reset: true,
        mobile: false,
        duration: 2200,
        delay: 100,
        distance: "200px",
        easing: "ease-out",
        origin: "bottom",
      });
      sr.reveal(".scroll-bottom-4", {
        reset: true,
        mobile: false,
        duration: 2600,
        delay: 100,
        distance: "200px",
        easing: "ease-out",
        origin: "bottom",
      });
      // for left
      sr.reveal(".scroll-left", {
        reset: true,
        mobile: false,
        duration: 1000,
        delay: 100,
        distance: "200px",
        easing: "ease-out",
        origin: "left",
      });
      // for right
      sr.reveal(".scroll-right", {
        reset: true,
        mobile: false,
        duration: 1000,
        delay: 100,
        distance: "200px",
        easing: "ease-out",
        origin: "right",
      });
    });
  },
};
</script>
