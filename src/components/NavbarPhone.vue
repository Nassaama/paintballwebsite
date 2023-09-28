<template>
  <div class="body">
    <header>
      <div class="header-horizontal">
        <img id="logo" src="../assets/FINAL.jpg" alt="Logo" />

        <img
          id="options-icon"
          src="../assets/icons/optionen.png"
          alt="Options lines"
          @click="showNavbarFunction"
          v-if="!showNavbar"
        />
      </div>
      <div class="header-vertical" v-if="showNavbar">
        <div>
          <img
            id="cross-icon"
            src="../assets/icons/kreuz.png"
            alt="Kreuz"
            @click="showNavbarFunction"
          />
        </div>
        <p class="navbar-text" @click="selectedTab('welcome')">Willkommen</p>
        <p class="navbar-text" @click="selectedTab('prices')">Preise</p>
        <p class="navbar-text" @click="selectedTab('location')">Location</p>
        <p class="navbar-text" @click="selectedTab('galery')">Galerie</p>
        <p class="navbar-text" @click="selectedTab('contact')">Kontakt</p>
      </div>
    </header>
  </div>
</template>
<script>
export default {
  data() {
    return {
      showNavbar: false,
    };
  },
  methods: {
    showNavbarFunction() {
      this.showNavbar = !this.showNavbar;
    },
    selectedTab(tab) {
      this.$emit("selected-tab", tab);
      this.showNavbarFunction();
    },
  },
};
</script>

<style scoped>
.body {
  margin: 0;
  padding: 0;
  display: inline-block;
}
.header-horizontal {
  background-color: #294328;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 5%;
  transition: 1s;
}
.icon-wrapper {
  display: inline-block;
}

#logo {
  width: 20%;
  border-radius: 100%;
}
#options-icon {
  width: 20%;
}

.header-vertical {
  position: fixed;
  top: 0;
  right: 0;
  background-color: #d5e6dd;
  display: flex;
  flex-direction: column;
  align-items: end;
  justify-content: space-evenly;
  padding: 5%;
  padding-bottom: 25%;
  width: 60%;
  height: 100%;
  transition: 1s;
  opacity: 0.9;
}

#cross-icon {
  position: fixed;
  top: 4%;
  right: 9%;
  width: 11%;
}
.navbar-text {
  font-family: "Black Ops One", sans-serif;
  font-size: 30px;
}

@media only screen and (max-width: 280px) {
  .navbar-text {
    font-family: "Black Ops One", sans-serif;
    font-size: 20px;
  }
}

@media only screen and (min-width: 750px) {
  .body {
    display: none;
  }
}
</style>
