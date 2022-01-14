<template>
 <!-- Header -->
 <NavbarMenu />
  <!-- Small sidebar -->
 <SmallSidebar />
  <!-- Sidebar -->
  <SideBar />
  <!-- Mobile sidebar -->
  <MobileSidebar />
  <!-- Categories -->
 <Categories />
  <!-- Videos -->
 <video-youtube />
  <!-- Footer -->
</template>
<script>
import NavbarMenu from "./components/header/TheNavbar-menu.vue";
import SmallSidebar from "./components/TheSmall-sidebar.vue";
import SideBar from "./components/TheSide-bar.vue";
import MobileSidebar from "./components/TheMobile-sidebar.vue";
import Categories from "./components/TheCategories.vue";
import VideoYoutube from './components/videos/TheVideo-youtube.vue';

export default {
  name: "App",
  components: { NavbarMenu, SmallSidebar, SideBar, MobileSidebar, Categories, VideoYoutube },
};
</script>

<style src="./assets/tailwind.css"></style>
