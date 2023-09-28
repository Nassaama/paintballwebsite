<template lang="">
  <main class="body">
    <div class="hero-frame">
      <h1 id="hero-header">Paintball-Arena Falkenau</h1>
    </div>
    <div class="welcome-widget">
      <img
        src="../assets//pics/scoping-player-behind-wood_auto_x2-transformed.jpeg"
        alt="scoping player behind wood"
        id="scoping-player"
      />
      <div id="gun-container-wrapper">
        <img
          src="../assets/icons/paintball.png"
          alt="paintpall Gun"
          id="paintball-gun"
        />
        <p id="paintball-gun-text">Ganzjährig, Montag - Sonntag</p>
      </div>
      <div id="hall-container-wrapper">
        <img
          id="hall-map"
          src="../assets/icons/hall-map.png"
          alt="Hall Map Image"
        />
        <p id="hall-map-text">Über 8000 Quadratmeter!</p>
      </div>
      <div id="crown-container-wrapper">
        <img
          id="crown-img"
          src="../assets/icons/krone1.png"
          alt="Krone Image"
        />
        <p id="crown-img-text">Größte Halle Deutschlands!</p>
      </div>
      <div id="mask-container-wrapper">
        <img id="mask-img" src="../assets/icons/maske.png" alt="Maske Image" />
        <p id="mask-img-text">Leihausrüst-ung vor Ort</p>
      </div>
    </div>
    <div id="filler-information">
      <div id="obstacle-wrapper">
        <img
          id="obstacle-img"
          src="../assets/icons/hürde1.png"
          alt="Hürde Image"
        />
        <p id="obstacle-text">
          Mit unzähligen Hindernissen, Ecken und verschiedenen Räumen spielen
          wir Paintball
        </p>
      </div>
      <div id="moon-wrapper">
        <img id="moon-image" src="../assets/icons/moon.png" alt="Mond Image" />
        <p id="moon-text">
          Nachtspielmöglichkeit. Nach Absprache ist Spielen bei Nacht möglich
        </p>
      </div>
      <div id="phone-wrapper">
        <img
          id="phone-image"
          src="../assets/icons/telefon.png"
          alt="Telefon Image"
        />
        <p id="phone-text">Termin / Buchung einfach über Telefon / Email</p>
      </div>
    </div>
    <div id="video-frame">
      <div id="video-icon-wrapper">
        <img
          src="../assets/icons/video.png"
          alt="Video Icon Image"
          id="video-icon"
        />
        <p id="video-icon-text">Trailer der Halle</p>
      </div>
      <video autoplay muted loop id="trailer">
        <source
          src="../assets/paintball-trailer.mp4"
          alt="Paintball trailer video"
          type="video/mp4"
        />
        Dein Browser unterstützt das Video-Tag nicht.
      </video>
    </div>
    <div id="social-media-wrap">
      <div id="social-media-wrapper">
        <h1 id="social-media-text">Social Medias:</h1>
        <a href="https://de-de.facebook.com/paintball.falkenau/"
          ><img id="facebook-icon" src="../assets/icons/facebook.png" alt=""
        /></a>
        <a href="https://www.instagram.com/paintballfalkenau/"
          ><img id="instagram-icon" src="../assets/icons/instagram.png" alt=""
        /></a>
        <a
          href="https://www.youtube.com/results?search_query=paintball+Falkenau"
          ><img id="youtube-icon" src="../assets/icons/youtube.png" alt=""
        /></a>
      </div>
    </div>
  </main>
</template>
<script>
export default {};
</script>
<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.body {
  overflow-y: scroll;
}

/* Galaxy Fold */
@media only screen and (min-width: 280px) {
  .hero-frame {
    height: 39px;
    width: 100%;
    padding-top: 11px;
    padding-bottom: 8px;
    padding-left: 34px;
    padding-right: 33px;
    background-color: #d5e6dd;
    justify-content: center;
    align-items: center;
    display: inline-flex;
  }
  #hero-header {
    width: 213px;
    height: 20px;
    color: #0d080d;
    background-color: #d5e6dd;
    font-size: 15px;
    font-family: "Black Han Sans", sans-serif;
    font-weight: 400;
    word-wrap: break-word;
  }
  .welcome-widget {
    width: 100%;
    height: 331px;
    position: relative;
    background: #294328;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  #scoping-player {
    height: 273px;
    width: 400px;
    opacity: 80%;
  }
  #gun-container-wrapper {
    width: 126px;
    height: 90px;
    left: 5px;
    top: 197px;
    position: absolute;
    opacity: 0.85;
    background: #d5e6dd;
    border-radius: 15px;
    overflow: hidden;
  }
  #paintball-gun {
    width: 31px;
    height: 31px;
    left: 45px;
    top: 4px;
    position: absolute;
    background-color: #d5e6dd;
  }
  #paintball-gun-text {
    width: 73px;
    height: 60px;
    left: 30px;
    top: 35px;
    position: absolute;
    color: black;
    font-size: 14px;
    font-family: "Merge One", sans-serif;
    font-weight: 500;
    word-wrap: break-word;
    background-color: #d5e6dd;
  }
  #hall-container-wrapper {
    width: 125px;
    height: 90px;
    left: 150px;
    top: 54px;
    position: absolute;
    opacity: 0.85;
    background: #d5e6dd;
    border-radius: 15px;
    overflow: hidden;
  }
  #hall-map {
    width: 31px;
    height: 31px;
    left: 47px;
    top: 5px;
    position: absolute;
    background-color: #d5e6dd;
  }
  #hall-map-text {
    width: 97px;
    height: 52px;
    left: 22px;
    top: 45px;
    position: absolute;
    color: black;
    font-size: 14px;
    font-family: Merge One;
    font-weight: 400;
    word-wrap: break-word;
    background-color: #d5e6dd;
  }
  #crown-container-wrapper {
    width: 125px;
    height: 90px;
    left: 6px;
    top: 54px;
    position: absolute;
    opacity: 0.85;
    background: #d5e6dd;
    border-radius: 15px;
    overflow: hidden;
  }
  #crown-img {
    width: 31px;
    height: 31px;
    left: 47px;
    top: 5px;
    position: absolute;
    background-color: #d5e6dd;
  }
  #crown-img-text {
    width: 90px;
    height: 44px;
    left: 20px;
    top: 40px;
    position: absolute;
    color: #0d080d;
    font-size: 14px;
    font-family: Merge One;
    font-weight: 400;
    word-wrap: break-word;
    background-color: #d5e6dd;
  }
  #mask-container-wrapper {
    width: 125px;
    height: 90px;
    left: 150px;
    top: 197px;
    position: absolute;
    opacity: 0.85;
    background: #d5e6dd;
    border-radius: 15px;
    overflow: hidden;
  }
  #mask-img {
    width: 31px;
    height: 33.14px;
    left: 45px;
    top: 5px;
    position: absolute;
    background-color: #d5e6dd;
  }
  #mask-img-text {
    width: 87px;
    height: 54px;
    left: 26px;
    top: 45px;
    position: absolute;
    color: black;
    font-size: 14px;
    font-family: Merge One;
    font-weight: 400;
    word-wrap: break-word;
    background-color: #d5e6dd;
  }
  #filler-information {
    width: 100%;
    height: 227px;
    position: relative;
    background-color: #d5e6dd;
  }
  #obstacle-wrapper {
    width: 100%;
    height: 50px;
    padding-top: 5px;
    padding-bottom: 5px;
    padding-left: 23px;
    padding-right: 18px;
    left: 0px;
    top: 20px;
    position: absolute;
    background: #7b9859;
    border-radius: 15px;
    overflow: hidden;
    justify-content: flex-end;
    align-items: center;
    gap: 35px;
    display: inline-flex;
  }
  #obstacle-img {
    position: absolute;
    left: 5%;
    width: 34px;
    height: 40px;
    background-color: #7b9859;
  }
  #obstacle-text {
    width: 170px;
    height: 36px;
    text-align: center;
    color: #0d080d;
    font-size: 10px;
    font-family: Merge One;
    font-weight: 400;
    word-wrap: break-word;
    background-color: #7b9859;
  }
  #moon-wrapper {
    padding-top: 6px;
    width: 100%;
    padding-bottom: 6px;
    padding-left: 24px;
    padding-right: 13px;
    left: 0px;
    top: 90px;
    position: absolute;
    background: #7b9859;
    border-radius: 15px;
    overflow: hidden;
    justify-content: flex-end;
    align-items: center;
    gap: 35px;
    display: inline-flex;
  }
  #moon-image {
    position: absolute;
    left: 5%;
    width: 34px;
    height: 34px;
    background: #7b9859;
  }
  #moon-text {
    width: 174px;
    height: 38px;
    text-align: center;
    color: #0d080d;
    font-size: 10px;
    font-family: Merge One;
    font-weight: 400;
    word-wrap: break-word;
    background: #7b9859;
  }
  #phone-wrapper {
    width: 100%;
    padding-top: 8px;
    height: 50px;
    padding-bottom: 8px;
    padding-left: 25px;
    padding-right: 15px;
    left: 0px;
    top: 160px;
    position: absolute;
    background: #7b9859;
    border-radius: 15px;
    overflow: hidden;
    justify-content: flex-end;
    align-items: center;
    gap: 34px;
    display: inline-flex;
  }
  #phone-image {
    position: absolute;
    left: 5%;
    width: 34px;
    height: 34px;
    background: #7b9859;
  }
  #phone-text {
    width: 172px;
    height: 25px;
    text-align: center;
    color: #0d080d;
    font-size: 10px;
    font-family: Merge One;
    font-weight: 400;
    word-wrap: break-word;
    background: #7b9859;
  }
  #video-frame {
    margin-top: 0;
    width: 100%;
    height: 239px;
    padding-top: 10px;
    padding-bottom: 18px;
    background: #294328;
    justify-content: flex-start;
    align-items: center;
    gap: 15px;
    display: inline-flex;
    flex-direction: column;
  }
  #video-icon-wrapper {
    align-self: stretch;
    height: 44px;
    padding-top: 6px;
    padding-bottom: 7px;
    padding-left: 10px;
    padding-right: 66px;
    opacity: 0.9;
    background: #d5e6dd;
    border-radius: 20px;
    overflow: hidden;
    justify-content: flex-start;
    align-items: center;
    gap: 50px;
    display: inline-flex;
  }
  #video-icon {
    width: 30px;
    height: 31px;
    background-color: #d5e6dd;
  }
  #video-icon-text {
    color: black;
    font-size: 14px;
    font-family: Merge One;
    font-weight: 400;
    word-wrap: break-word;
    background-color: #d5e6dd;
  }
  #trailer {
    width: 100%;
    height: 160px;
    border-radius: 5px;
  }
  #social-media-wrap {
    width: 100%;
    height: 100%;
    padding-top: 35px;
    padding-bottom: 35px;
    background: #d5e6dd;
    justify-content: center;
    align-items: center;
    display: inline-flex;
  }
  #social-media-wrapper {
    width: 100%;
    height: 40px;
    background-color: #d5e6dd;
    position: relative;
  }
  #social-media-text {
    width: 134px;
    height: 24px;
    left: 2px;
    top: 9px;
    position: absolute;
    color: black;
    font-size: 16px;
    font-family: Black Ops One;
    background-color: #d5e6dd;

    font-weight: 400;
    word-wrap: break-word;
  }
  #facebook-icon {
    width: 30px;
    height: 30px;
    background-color: #d5e6dd;
    left: 136px;
    top: 5px;
    position: absolute;
  }
  #instagram-icon {
    width: 32px;
    height: 32px;
    background-color: #d5e6dd;
    left: 185px;
    top: 4px;
    position: absolute;
  }
  #youtube-icon {
    width: 38px;
    height: 38px;
    left: 233px;
    background-color: #d5e6dd;
    top: 1px;
    position: absolute;
  }
}

/* PHONE  */
@media only screen and (min-width: 350px) {
  .hero-frame {
    padding: 0;
    height: 60px;
    width: 100%;
    background-color: #d5e6dd;
    display: inline-flex;
    justify-content: center;
    align-items: center;
  }
  #hero-header {
    width: 70%;
    align-items: center;
    height: 20px;
    color: #0d080d;
    background-color: #d5e6dd;
    font-size: 18px;
    font-family: "Black Han Sans", sans-serif;
    font-weight: 400;
  }
  .welcome-widget {
    width: 100%;
    height: 400px;
    position: relative;
    background: #294328;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  #scoping-player {
    height: 350px;
    width: 500px;
    opacity: 80%;
  }
  #gun-container-wrapper {
    width: 150px;
    height: 120px;
    left: 5%;
    top: 60%;
    position: absolute;
    opacity: 0.85;
    background: #d5e6dd;
    border-radius: 15px;
  }
  #paintball-gun {
    width: 45px;
    height: 45px;
    left: 35%;
    top: 2%;
    position: absolute;
    background-color: #d5e6dd;
  }
  #paintball-gun-text {
    width: 90px;
    height: 60px;
    left: 23%;
    top: 40%;
    position: absolute;
    color: black;
    font-size: 17px;
    font-family: "Merge One", sans-serif;
    font-weight: 500;
    word-wrap: break-word;
    background-color: #d5e6dd;
  }
  #hall-container-wrapper {
    width: 150px;
    height: 120px;
    left: 55%;
    top: 10%;
    position: absolute;
    opacity: 0.85;
    background: #d5e6dd;
    border-radius: 15px;
    overflow: hidden;
  }
  #hall-map {
    width: 45px;
    height: 45px;
    left: 35%;
    top: 5%;
    position: absolute;
    background-color: #d5e6dd;
  }
  #hall-map-text {
    width: 115px;
    height: 60px;
    left: 15%;
    top: 50%;
    position: absolute;
    color: black;
    font-size: 17px;
    font-family: Merge One;
    font-weight: 400;
    word-wrap: break-word;
    background-color: #d5e6dd;
  }
  #crown-container-wrapper {
    width: 150px;
    height: 120px;
    left: 5%;
    top: 10%;
    position: absolute;
    opacity: 0.85;
    background: #d5e6dd;
    border-radius: 15px;
    overflow: hidden;
  }
  #crown-img {
    width: 50px;
    height: 50px;
    left: 33%;
    top: 3%;
    position: absolute;
    background-color: #d5e6dd;
  }
  #crown-img-text {
    width: 115px;
    height: 44px;
    left: 14%;
    top: 50%;
    position: absolute;
    color: #0d080d;
    font-size: 110%;
    font-family: Merge One;
    font-weight: 400;
    word-wrap: break-word;
    background-color: #d5e6dd;
  }
  #mask-container-wrapper {
    width: 150px;
    height: 120px;
    left: 55%;
    top: 60%;
    position: absolute;
    opacity: 0.85;
    background: #d5e6dd;
    border-radius: 15px;
    overflow: hidden;
  }
  #mask-img {
    width: 52px;
    height: 52px;
    left: 30%;
    top: 2%;
    position: absolute;
    background-color: #d5e6dd;
  }
  #mask-img-text {
    width: 110px;
    height: 60px;
    left: 17%;
    top: 50%;
    position: absolute;
    color: black;
    font-size: 17px;
    font-family: Merge One;
    font-weight: 400;
    word-wrap: break-word;
    background-color: #d5e6dd;
  }
  #filler-information {
    width: 100%;
    height: 350px;
    position: relative;
    background-color: #d5e6dd;
  }
  #obstacle-wrapper {
    width: 100%;
    height: 20%;
    left: 0;
    top: 10%;
    position: absolute;
    background: #7b9859;
    border-radius: 15px;
    overflow: hidden;
    justify-content: flex-end;
    align-items: center;
    gap: 35px;
    display: inline-flex;
  }
  #obstacle-img {
    position: absolute;
    left: 5%;
    width: 52px;
    height: 58px;
    background-color: #7b9859;
  }
  #obstacle-text {
    width: 240px;
    height: 45px;
    text-align: center;
    color: #0d080d;
    font-size: 14px;
    font-family: Merge One;
    font-weight: 600;
    word-wrap: break-word;
    background-color: #7b9859;
  }
  #moon-wrapper {
    width: 100%;
    height: 20%;
    left: 0px;
    top: 40%;
    position: absolute;
    background: #7b9859;
    border-radius: 15px;
    overflow: hidden;
    justify-content: flex-end;
    align-items: center;
    gap: 35px;
    display: inline-flex;
  }
  #moon-image {
    position: absolute;
    left: 7%;
    width: 50px;
    height: 50px;
    background: #7b9859;
  }
  #moon-text {
    width: 240px;
    height: 45px;
    text-align: center;
    color: #0d080d;
    font-size: 14px;
    font-family: Merge One;
    font-weight: 600;
    word-wrap: break-word;
    background: #7b9859;
  }
  #phone-wrapper {
    width: 100%;
    height: 20%;
    left: 0px;
    top: 70%;
    position: absolute;
    background: #7b9859;
    border-radius: 15px;
    overflow: hidden;
    justify-content: flex-end;
    align-items: center;
    gap: 34px;
    display: inline-flex;
  }
  #phone-image {
    position: absolute;
    left: 6%;
    width: 50px;
    height: 50px;
    background: #7b9859;
  }
  #phone-text {
    width: 240px;
    height: 35px;
    text-align: center;
    color: #0d080d;
    font-size: 15px;
    font-family: Merge One;
    font-weight: 600;
    word-wrap: break-word;
    background: #7b9859;
  }
  #video-frame {
    width: 100%;
    height: 350px;
    background: #294328;
    justify-content: flex-start;
    align-items: center;
    gap: 15px;
    display: inline-flex;
    flex-direction: column;
    padding-top: 5%;
  }
  #video-icon-wrapper {
    align-self: stretch;
    height: 70px;
    opacity: 0.9;
    background: #d5e6dd;
    border-radius: 20px;
    overflow: hidden;
    justify-content: flex-start;
    align-items: center;
    gap: 50px;
    display: inline-flex;
  }
  #video-icon {
    width: 48px;
    height: 48px;
    background-color: #d5e6dd;
  }
  #video-icon-text {
    color: black;
    font-size: 20px;
    font-family: Merge One;
    font-weight: 500;
    word-wrap: break-word;
    background-color: #d5e6dd;
  }
  #trailer {
    width: 100%;
    height: 280px;
    border-radius: 5px;
    background-color: #294328;
  }
  #social-media-wrap {
    width: 100%;
    height: 100%;
    padding-top: 35px;
    padding-bottom: 35px;
    background: #d5e6dd;
    justify-content: center;
    align-items: center;
    display: inline-flex;
  }
  #social-media-wrapper {
    width: 100%;
    height: 60px;
    background-color: #d5e6dd;
    position: relative;
  }
  #social-media-text {
    width: 200px;
    height: 24px;
    left: 3%;
    top: 35%;
    position: absolute;
    color: black;
    font-size: 20px;
    font-family: Black Ops One;
    background-color: #d5e6dd;

    font-weight: 400;
    word-wrap: break-word;
  }
  #facebook-icon {
    width: 40px;
    height: 40px;
    background-color: #d5e6dd;
    left: 47%;
    top: 25%;
    position: absolute;
  }
  #instagram-icon {
    width: 40px;
    height: 40px;
    background-color: #d5e6dd;
    left: 65%;
    top: 25%;
    position: absolute;
  }
  #youtube-icon {
    width: 50px;
    height: 50px;
    left: 82%;
    top: 18%;
    background-color: #d5e6dd;
    position: absolute;
  }
}
@media only screen and (min-width: 750px) {
  .hero-frame {
    height: 100px;
    width: 100%;
    padding-top: 11px;
    padding-bottom: 8px;
    padding-left: 34px;
    padding-right: 33px;
    background-color: #d5e6dd;
    justify-content: center;
    align-items: center;
    display: inline-flex;
  }
  #hero-header {
    width: auto;
    height: 40px;
    color: #0d080d;
    background-color: #d5e6dd;
    font-size: 35px;
    font-family: "Black Han Sans", sans-serif;
    font-weight: 400;
    word-wrap: break-word;
  }
  .welcome-widget {
    width: 100%;
    height: 900px;
    position: relative;
    background: #294328;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  #scoping-player {
    height: 800px;
    width: 1000px;
    opacity: 80%;
  }
  #gun-container-wrapper {
    width: 320px;
    height: 180px;
    left: 50px;
    top: 625px;
    position: absolute;
    opacity: 0.85;
    background: #d5e6dd;
    border-radius: 15px;
    overflow: hidden;
  }
  #paintball-gun {
    width: 70px;
    height: 70px;
    left: 40%;
    top: 4px;
    position: absolute;
    background-color: #d5e6dd;
  }
  #paintball-gun-text {
    width: 200px;
    height: 55px;
    left: 30%;
    top: 42%;
    position: absolute;
    color: black;
    font-size: 25px;
    font-family: "Merge One", sans-serif;
    font-weight: 500;
    word-wrap: break-word;
    background-color: #d5e6dd;
  }
  #hall-container-wrapper {
    width: 320px;
    height: 180px;
    right: 50px;
    bottom: 625px;
    position: absolute;
    opacity: 0.85;
    background: #d5e6dd;
    border-radius: 15px;
    overflow: hidden;
  }
  #hall-map {
    width: 70px;
    height: 70px;
    left: 39%;
    top: 5px;
    position: absolute;
    background-color: #d5e6dd;
  }
  #hall-map-text {
    width: 200px;
    height: 55px;
    left: 25%;
    top: 50%;
    position: absolute;
    color: black;
    font-size: 25px;
    font-family: Merge One;
    font-weight: 400;
    word-wrap: break-word;
    background-color: #d5e6dd;
  }
  #crown-container-wrapper {
    width: 320px;
    height: 180px;
    left: 50px;
    bottom: 625px;
    position: absolute;
    opacity: 0.85;
    background: #d5e6dd;
    border-radius: 15px;
    overflow: hidden;
  }
  #crown-img {
    width: 74px;
    height: 74px;
    left: 40%;
    top: 5px;
    position: absolute;
    background-color: #d5e6dd;
  }
  #crown-img-text {
    width: 200px;
    height: 44px;
    left: 25%;
    top: 50%;
    position: absolute;
    color: #0d080d;
    font-size: 25px;
    font-family: Merge One;
    font-weight: 400;
    word-wrap: break-word;
    background-color: #d5e6dd;
  }
  #mask-container-wrapper {
    width: 320px;
    height: 180px;
    right: 50px;
    top: 625px;
    position: absolute;
    opacity: 0.85;
    background: #d5e6dd;
    border-radius: 15px;
    overflow: hidden;
  }
  #mask-img {
    width: 70px;
    height: 70px;
    left: 40%;
    top: 5px;
    position: absolute;
    background-color: #d5e6dd;
  }
  #mask-img-text {
    width: 150px;
    height: 55px;
    left: 30%;
    top: 50%;
    position: absolute;
    color: black;
    font-size: 25px;
    font-family: Merge One;
    font-weight: 400;
    word-wrap: break-word;
    background-color: #d5e6dd;
  }
  #filler-information {
    width: 100%;
    height: 600px;
    position: relative;
    background-color: #d5e6dd;
  }
  #obstacle-wrapper {
    width: 100%;
    height: 130px;
    padding-top: 5px;
    padding-bottom: 5px;
    padding-left: 23px;
    padding-right: 18px;
    left: 0px;
    top: 10%;
    position: absolute;
    background: #7b9859;
    border-radius: 15px;
    overflow: hidden;
    justify-content: flex-end;
    align-items: center;
    gap: 35px;
    display: inline-flex;
  }
  #obstacle-img {
    position: absolute;
    left: 7%;
    width: 95px;
    height: 100px;
    background-color: #7b9859;
  }
  #obstacle-text {
    width: 450px;
    height: 80px;
    text-align: center;
    color: #0d080d;
    font-size: 25px;
    padding-right: 5%;
    font-family: Merge One;
    font-weight: 600;
    word-wrap: break-word;
    background-color: #7b9859;
  }
  #moon-wrapper {
    padding-top: 6px;
    width: 100%;
    padding-bottom: 6px;
    padding-left: 24px;
    padding-right: 13px;
    height: 130px;
    left: 0px;
    top: 40%;
    position: absolute;
    background: #7b9859;
    border-radius: 15px;
    overflow: hidden;
    justify-content: flex-end;
    align-items: center;
    gap: 35px;
    display: inline-flex;
  }
  #moon-image {
    position: absolute;
    left: 8%;
    width: 90px;
    height: 90px;
    background: #7b9859;
  }
  #moon-text {
    width: 400px;
    height: 90px;
    text-align: center;
    color: #0d080d;
    font-size: 25px;
    padding-right: 12%;
    font-family: Merge One;
    font-weight: 600;
    word-wrap: break-word;
    background: #7b9859;
  }
  #phone-wrapper {
    width: 100%;
    padding-top: 8px;
    height: 130px;
    padding-bottom: 8px;
    padding-left: 25px;
    padding-right: 15px;
    left: 0px;
    top: 70%;
    position: absolute;
    background: #7b9859;
    border-radius: 15px;
    overflow: hidden;
    justify-content: flex-end;
    align-items: center;
    gap: 34px;
    display: inline-flex;
  }
  #phone-image {
    position: absolute;
    left: 8%;
    width: 90px;
    height: 90px;
    background: #7b9859;
  }
  #phone-text {
    width: 420px;
    height: 70px;
    text-align: center;
    color: #0d080d;
    font-size: 25px;
    padding-right: 12%;
    font-family: Merge One;
    font-weight: 600;
    word-wrap: break-word;
    background: #7b9859;
  }
  #video-frame {
    height: 700px;
    padding-top: 40px;
    background: #294328;
    justify-content: flex-start;
    align-items: center;
    gap: 15px;
    display: inline-flex;
    flex-direction: column;
  }
  #video-icon-wrapper {
    align-self: stretch;
    height: 120px;
    padding-top: 6px;
    padding-bottom: 7px;
    padding-left: 10px;
    padding-right: 66px;
    opacity: 0.9;
    background: #d5e6dd;
    border-radius: 20px;
    overflow: hidden;
    justify-content: flex-start;
    align-items: center;
    gap: 50px;
    display: inline-flex;
  }
  #video-icon {
    width: 100px;
    height: 100px;
    background-color: #d5e6dd;
  }
  #video-icon-text {
    color: black;
    font-size: 32px;
    font-family: Merge One;
    font-weight: 400;
    word-wrap: break-word;
    background-color: #d5e6dd;
    position: absolute;
    left: 35%;
  }
  #trailer {
    width: 100%;
    height: 500px;
  }
  #social-media-wrap {
    width: 100%;
    height: 100%;
    padding-top: 35px;
    padding-bottom: 35px;
    background: #d5e6dd;
    justify-content: center;
    align-items: center;
    display: inline-flex;
  }
  #social-media-wrapper {
    width: 100%;
    height: 200px;
    background-color: #d5e6dd;
    position: relative;
  }
  #social-media-text {
    width: 350px;
    height: 150px;
    left: 2%;
    top: 40%;
    position: absolute;
    color: black;
    font-size: 40px;
    font-family: Black Ops One;
    background-color: #d5e6dd;
    font-size: 400;
    word-wrap: break-word;
  }
  #facebook-icon {
    width: 105px;
    height: 105px;
    background-color: #d5e6dd;
    left: 45%;
    top: 30%;
    position: absolute;
  }
  #instagram-icon {
    width: 105px;
    height: 105px;
    background-color: #d5e6dd;
    left: 62%;
    top: 30%;
    position: absolute;
  }
  #youtube-icon {
    width: 130px;
    height: 130px;
    left: 80%;
    background-color: #d5e6dd;
    top: 25%;
    position: absolute;
  }
}
@media only screen and (min-width: 1000px) {
  .hero-frame {
    height: 150px;
    width: 100%;
    padding-top: 11px;
    padding-bottom: 8px;
    padding-left: 34px;
    padding-right: 33px;
    background-color: #d5e6dd;
    justify-content: center;
    align-items: center;
    display: inline-flex;
  }
  #hero-header {
    width: auto;
    height: 45px;
    color: #0d080d;
    background-color: #d5e6dd;
    font-size: 40px;
    font-family: "Black Han Sans", sans-serif;
    font-weight: 400;
    word-wrap: break-word;
  }
  .welcome-widget {
    width: 100%;
    height: 900px;
    position: relative;
    background: #294328;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  #scoping-player {
    height: 800px;
    width: 1200px;
    opacity: 80%;
  }
  #gun-container-wrapper {
    width: 320px;
    height: 180px;
    left: 50px;
    top: 625px;
    position: absolute;
    opacity: 0.85;
    background: #d5e6dd;
    border-radius: 15px;
    overflow: hidden;
  }
  #paintball-gun {
    width: 70px;
    height: 70px;
    left: 40%;
    top: 4px;
    position: absolute;
    background-color: #d5e6dd;
  }
  #paintball-gun-text {
    width: 200px;
    height: 55px;
    left: 30%;
    top: 42%;
    position: absolute;
    color: black;
    font-size: 25px;
    font-family: "Merge One", sans-serif;
    font-weight: 500;
    word-wrap: break-word;
    background-color: #d5e6dd;
  }
  #hall-container-wrapper {
    width: 320px;
    height: 180px;
    left: 65%;
    bottom: 625px;
    position: absolute;
    opacity: 0.85;
    background: #d5e6dd;
    border-radius: 15px;
    overflow: hidden;
  }
  #hall-map {
    width: 70px;
    height: 70px;
    left: 39%;
    top: 5px;
    position: absolute;
    background-color: #d5e6dd;
  }
  #hall-map-text {
    width: 200px;
    height: 55px;
    left: 25%;
    top: 50%;
    position: absolute;
    color: black;
    font-size: 25px;
    font-family: Merge One;
    font-weight: 400;
    word-wrap: break-word;
    background-color: #d5e6dd;
  }
  #crown-container-wrapper {
    width: 320px;
    height: 180px;
    left: 50px;
    bottom: 625px;
    position: absolute;
    opacity: 0.85;
    background: #d5e6dd;
    border-radius: 15px;
    overflow: hidden;
  }
  #crown-img {
    width: 74px;
    height: 74px;
    left: 40%;
    top: 5px;
    position: absolute;
    background-color: #d5e6dd;
  }
  #crown-img-text {
    width: 200px;
    height: 44px;
    left: 25%;
    top: 50%;
    position: absolute;
    color: #0d080d;
    font-size: 25px;
    font-family: Merge One;
    font-weight: 400;
    word-wrap: break-word;
    background-color: #d5e6dd;
  }
  #mask-container-wrapper {
    width: 320px;
    height: 180px;
    left: 65%;
    top: 625px;
    position: absolute;
    opacity: 0.85;
    background: #d5e6dd;
    border-radius: 15px;
    overflow: hidden;
  }
  #mask-img {
    width: 70px;
    height: 70px;
    left: 40%;
    top: 5px;
    position: absolute;
    background-color: #d5e6dd;
  }
  #mask-img-text {
    width: 150px;
    height: 55px;
    left: 30%;
    top: 50%;
    position: absolute;
    color: black;
    font-size: 25px;
    font-family: Merge One;
    font-weight: 400;
    word-wrap: break-word;
    background-color: #d5e6dd;
  }
  #filler-information {
    width: 100%;
    height: 600px;
    position: relative;
    background-color: #d5e6dd;
  }
  #obstacle-wrapper {
    width: 100%;
    height: 130px;
    padding-top: 5px;
    padding-bottom: 5px;
    padding-left: 23px;
    padding-right: 18px;
    left: 0px;
    top: 10%;
    position: absolute;
    background: #7b9859;
    border-radius: 15px;
    overflow: hidden;
    justify-content: flex-end;
    align-items: center;
    gap: 35px;
    display: inline-flex;
  }
  #obstacle-img {
    position: absolute;
    left: 7%;
    width: 95px;
    height: 100px;
    background-color: #7b9859;
  }
  #obstacle-text {
    width: 450px;
    height: 80px;
    text-align: center;
    color: #0d080d;
    font-size: 25px;
    padding-right: 5%;
    font-family: Merge One;
    font-weight: 600;
    word-wrap: break-word;
    background-color: #7b9859;
  }
  #moon-wrapper {
    padding-top: 6px;
    width: 100%;
    padding-bottom: 6px;
    padding-left: 24px;
    padding-right: 13px;
    height: 130px;
    left: 0px;
    top: 40%;
    position: absolute;
    background: #7b9859;
    border-radius: 15px;
    overflow: hidden;
    justify-content: flex-end;
    align-items: center;
    gap: 35px;
    display: inline-flex;
  }
  #moon-image {
    position: absolute;
    left: 8%;
    width: 90px;
    height: 90px;
    background: #7b9859;
  }
  #moon-text {
    width: 410px;
    height: 95%;
    text-align: center;
    color: #0d080d;
    font-size: 25px;
    padding-right: 12%;
    font-family: Merge One;
    font-weight: 600;
    word-wrap: break-word;
    background: #7b9859;
  }
  #phone-wrapper {
    width: 100%;
    padding-top: 8px;
    height: 130px;
    padding-bottom: 8px;
    padding-left: 25px;
    padding-right: 15px;
    left: 0px;
    top: 70%;
    position: absolute;
    background: #7b9859;
    border-radius: 15px;
    overflow: hidden;
    justify-content: flex-end;
    align-items: center;
    gap: 34px;
    display: inline-flex;
  }
  #phone-image {
    position: absolute;
    left: 8%;
    width: 90px;
    height: 90px;
    background: #7b9859;
  }
  #phone-text {
    width: 420px;
    height: 70px;
    text-align: center;
    color: #0d080d;
    font-size: 25px;
    padding-right: 12%;
    font-family: Merge One;
    font-weight: 600;
    word-wrap: break-word;
    background: #7b9859;
  }
  #video-frame {
    height: 700px;
    padding-top: 40px;
    background: #294328;
    justify-content: flex-start;
    align-items: center;
    gap: 15px;
    display: inline-flex;
    flex-direction: column;
  }
  #video-icon-wrapper {
    align-self: stretch;
    height: 120px;
    padding-top: 6px;
    padding-bottom: 7px;
    padding-left: 10px;
    padding-right: 66px;
    opacity: 0.9;
    background: #d5e6dd;
    border-radius: 20px;
    overflow: hidden;
    justify-content: flex-start;
    align-items: center;
    gap: 50px;
    display: inline-flex;
  }
  #video-icon {
    width: 100px;
    height: 100px;
    background-color: #d5e6dd;
  }
  #video-icon-text {
    color: black;
    font-size: 32px;
    font-family: Merge One;
    font-weight: 400;
    word-wrap: break-word;
    background-color: #d5e6dd;
    position: absolute;
    left: 35%;
  }
  #trailer {
    width: 100%;
    height: 500px;
  }
  #social-media-wrap {
    width: 100%;
    height: 100%;
    padding-top: 35px;
    padding-bottom: 35px;
    background: #d5e6dd;
    justify-content: center;
    align-items: center;
    display: inline-flex;
  }
  #social-media-wrapper {
    width: 100%;
    height: 200px;
    background-color: #d5e6dd;
    position: relative;
  }
  #social-media-text {
    width: 350px;
    height: 150px;
    left: 2%;
    top: 40%;
    position: absolute;
    color: black;
    font-size: 40px;
    font-family: Black Ops One;
    background-color: #d5e6dd;
    font-size: 400;
    word-wrap: break-word;
  }
  #facebook-icon {
    width: 105px;
    height: 105px;
    background-color: #d5e6dd;
    left: 45%;
    top: 30%;
    position: absolute;
  }
  #instagram-icon {
    width: 105px;
    height: 105px;
    background-color: #d5e6dd;
    left: 62%;
    top: 30%;
    position: absolute;
  }
  #youtube-icon {
    width: 130px;
    height: 130px;
    left: 80%;
    background-color: #d5e6dd;
    top: 25%;
    position: absolute;
  }
}
@media only screen and (min-width: 1200px) {
  .welcome-widget {
    width: 100%;
    height: 1100px;
    position: relative;
    background: #294328;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  #scoping-player {
    height: 1000px;
    width: 1350px;
    opacity: 80%;
  }
  #gun-container-wrapper {
    width: 320px;
    height: 180px;
    left: 50px;
    top: 75%;
    position: absolute;
    opacity: 0.85;
    background: #d5e6dd;
    border-radius: 15px;
    overflow: hidden;
  }
  #paintball-gun {
    width: 70px;
    height: 70px;
    left: 40%;
    top: 4px;
    position: absolute;
    background-color: #d5e6dd;
  }
  #paintball-gun-text {
    width: 200px;
    height: 55px;
    left: 30%;
    top: 42%;
    position: absolute;
    color: black;
    font-size: 25px;
    font-family: "Merge One", sans-serif;
    font-weight: 500;
    word-wrap: break-word;
    background-color: #d5e6dd;
  }
  #hall-container-wrapper {
    width: 320px;
    height: 180px;
    left: 70%;
    bottom: 625px;
    position: absolute;
    opacity: 0.85;
    background: #d5e6dd;
    border-radius: 15px;
    overflow: hidden;
  }
  #hall-map {
    width: 70px;
    height: 70px;
    left: 39%;
    top: 5px;
    position: absolute;
    background-color: #d5e6dd;
  }
  #hall-map-text {
    width: 200px;
    height: 55px;
    left: 25%;
    top: 50%;
    position: absolute;
    color: black;
    font-size: 25px;
    font-family: Merge One;
    font-weight: 400;
    word-wrap: break-word;
    background-color: #d5e6dd;
  }
  #crown-container-wrapper {
    width: 320px;
    height: 180px;
    left: 50px;
    bottom: 625px;
    position: absolute;
    opacity: 0.85;
    background: #d5e6dd;
    border-radius: 15px;
    overflow: hidden;
  }
  #crown-img {
    width: 74px;
    height: 74px;
    left: 40%;
    top: 5px;
    position: absolute;
    background-color: #d5e6dd;
  }
  #crown-img-text {
    width: 200px;
    height: 44px;
    left: 25%;
    top: 50%;
    position: absolute;
    color: #0d080d;
    font-size: 25px;
    font-family: Merge One;
    font-weight: 400;
    word-wrap: break-word;
    background-color: #d5e6dd;
  }
  #mask-container-wrapper {
    width: 320px;
    height: 180px;
    left: 70%;
    top: 75%;
    position: absolute;
    opacity: 0.85;
    background: #d5e6dd;
    border-radius: 15px;
    overflow: hidden;
  }
  #mask-img {
    width: 70px;
    height: 70px;
    left: 40%;
    top: 5px;
    position: absolute;
    background-color: #d5e6dd;
  }
  #mask-img-text {
    width: 150px;
    height: 55px;
    left: 30%;
    top: 50%;
    position: absolute;
    color: black;
    font-size: 25px;
    font-family: Merge One;
    font-weight: 400;
    word-wrap: break-word;
    background-color: #d5e6dd;
  }
}
@media only screen and (min-width: 1400px) {
}
</style>
