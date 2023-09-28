<template>
  <main>
    <div class="footer">
      <div class="impress-wrapper">
        <p>Impressum</p>
      </div>
      <div class="hafti-wrapper">
        <p>Haftungsausschluss</p>
      </div>
    </div>
  </main>
</template>
<script>
export default {};
</script>
<style scoped>
* {
  display: inline-block;
  margin: 0;
  padding: 0;
}
@media only screen and (min-width: 280px) {
  .footer {
    width: 100%;
    height: 40px;
    background-color: #294328;
    display: flex;
    justify-content: space-evenly;
  }
  .impress-wrapper {
    background-color: #294328;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  .impress-wrapper p {
    background-color: #294328;
  }
  .hafti-wrapper {
    background-color: #294328;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  .hafti-wrapper p {
    background-color: #294328;
  }
}
</style>
