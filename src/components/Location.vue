<template>
  <div class="container">
    <div class="header-wrapper">
      <h1>Interessiert? Hier findest du Uns:</h1>
      <p>Ernst-Thälmann-Straße39</p>
      <span></span>
      <p>09569 Falkenau</p>
    </div>
    <div class="map-wrapper">
      <iframe
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2518.6943904475224!2d13.118423577688539!3d50.85534329176594!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47a75b616232469f%3A0xe571452bba7f5d4f!2sPaint-Ball-Arena%20Falkenau!5e0!3m2!1sde!2sde!4v1695491428382!5m2!1sde!2sde"
        width="100%"
        style="border: 0"
        allowfullscreen=""
        loading="lazy"
        referrerpolicy="no-referrer-when-downgrade"
      ></iframe>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style>
* {
  margin: 0;
}

@media only screen and (min-width: 280px) {
  .container {
    display: flex;
    align-items: center;
    flex-direction: column;
  }
  .header-wrapper h1 {
    font-family: "Black Ops One", cursive;
    font-size: 20px;
    padding: 10%;
  }
  .header-wrapper p {
    padding-left: 5%;
    margin-top: 1%;
  }
  .map-wrapper {
    border-width: 5px;
    border-style: solid;
    border-color: #294328;
  }
}
</style>
