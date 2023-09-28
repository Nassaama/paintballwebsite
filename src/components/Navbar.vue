<template>
  <header class="navbar">
    <img src="../assets/FINAL.jpg" alt="Logo" id="logo" />
    <ul class="nav-links">
      <li class="nav-link">
        <a href="#" @click="selectedTab('welcome')">Willkommen</a>
      </li>
      <li class="nav-link">
        <a href="#" @click="selectedTab('prices')">Preise</a>
      </li>
      <li class="nav-link">
        <a href="#" @click="selectedTab('location')">Location</a>
      </li>
      <li class="nav-link">
        <a href="#" @click="selectedTab('galery')">Galerie</a>
      </li>
    </ul>
    <button class="button">Kontakt</button>
  </header>
</template>
<script>
export default {
  data() {
    return {
      logoImage: require("../assets/FINAL.jpg"),
    };
  },
  props: ["renderInfoWelcome"],
  methods: {
    selectedTab(tab) {
      this.$emit("selected-tab", tab);
    },
  },
};
</script>
<style scoped>
.navbar {
  display: none;
}
/* Pisser geräte */
@media only screen and (min-width: 750px) {
  * {
    margin: 0;
    text-decoration: none;
    list-style: none;
  }
  .navbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color: #294328;
    padding-bottom: 1%;
    padding-top: 1%;
  }
  .nav-links {
    display: inline-flex;
    justify-content: center;
    align-items: center;
  }
  .nav-link {
    display: inline-block;
    padding-left: 5%;
    padding-right: 5%;
  }
  .nav-link a {
    font-family: "Black Ops One", sans-serif;
    font-size: 17px;
    color: black;
  }
  .nav-link a:hover {
    color: #7b9859;
    transition: 0.3s;
  }
  .button {
    background-color: #7b9859;
    font-family: "Black Ops One", sans-serif;
    font-size: 20px;
    color: black;
    border: none;
    height: 55px;
    width: 120px;
    border-radius: 50px;
    margin-right: 1%;
  }
  .button:hover {
    background-color: #4e692f;
    transition: 0.3s;
  }
  #logo {
    width: 100px;
    border-radius: 35%;
    padding: 5px;
    margin-left: 1%;
  }
}
/* Desktop alike */
@media only screen and (min-width: 1200px) {
  * {
    margin: 0;
    text-decoration: none;
    list-style: none;
  }
  .navbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color: #294328;
    padding-bottom: 1%;
    padding-top: 1%;
  }
  .nav-links {
    display: inline-flex;
    justify-content: center;
    align-items: center;
  }
  .nav-link {
    display: inline-block;
    padding-left: 8%;
    padding-right: 8%;
  }
  .nav-link a {
    font-family: "Black Ops One", sans-serif;
    font-size: 30px;
    color: black;
  }
  .nav-link a:hover {
    color: #7b9859;
    transition: 0.3s;
  }
  .button {
    background-color: #7b9859;
    font-family: "Black Ops One", sans-serif;
    font-size: 30px;
    color: black;
    border: none;
    height: 90px;
    width: 200px;
    border-radius: 50px;
    margin-right: 1%;
  }
  .button:hover {
    background-color: #4e692f;
    transition: 0.3s;
  }
  #logo {
    width: 100px;
    border-radius: 35%;
    padding: 5px;
    margin-left: 1%;
  }
}
</style>
