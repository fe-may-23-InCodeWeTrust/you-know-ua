<script>
</script>

<template>
  <h1 class="logo">You know ua</h1>

  <div class="video">
    <video id="background-video" autoplay loop muted playsinline>
      <source src="../videos/video5280985082994111415.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>

  <div class="map">
    Map of Ukraine
    <router-link to="/city/lviv">
      Go to Lviv
    </router-link>
  </div>
</template>

<style>
.logo {
  font-weight: bold;
  font-size: 50px;
  text-align: center;
  margin-top: 40vh;
  color: #fff;
}
#background-video {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100vh;
  object-fit: cover; /* чтобы видео заполнило всю область */
  z-index: -1;
}
.map {
  margin-top: 45vh;
}
</style>
