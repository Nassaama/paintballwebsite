<template>
  <NavbarPhone
    class="navbar-phone"
    @selected-tab="handleTabSelected"
  ></NavbarPhone>
  <Navbar @selected-tab="handleTabSelected" />
  <Welcome class="welcome" v-if="selectedTab === 'welcome'"></Welcome>
  <Location v-if="selectedTab === 'location'"></Location>
  <Prices v-if="selectedTab === 'prices'"></Prices>
  <Galery v-if="selectedTab === 'galery'"></Galery>
  <Footer style="width: 100%"></Footer>
</template>
<script>
import Navbar from "./components/Navbar.vue";
import Welcome from "./components/Welcome.vue";
import Location from "./components/Location.vue";
import Galery from "./components/Galery.vue";
import Prices from "./components/Prices.vue";
import Footer from "./components/Footer.vue";
import NavbarPhone from "./components/NavbarPhone.vue";
export default {
  components: {
    Navbar,
    Welcome,
    Location,
    Galery,
    Prices,
    Footer,
    NavbarPhone,
  },

  data() {
    return {
      selectedTab: "welcome",
    };
  },

  methods: {
    handleTabSelected(tab) {
      this.selectedTab = tab;
    },
  },
};
</script>
<style scoped>
.navbar-phone {
  position: relative;
  z-index: 2;
}
</style>
