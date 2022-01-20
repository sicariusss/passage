<template>
  <b-container fluid class="pb-5">
    <div class="ig-block">
      <div class="ig-title">
        Узнавайте новости первыми
      </div>
      <div>
        <div class="ig-link-block">
          <b-img class="ig-logo" src="/ig.svg"></b-img>
          <div class="ig-link">
            <a href="https://www.instagram.com/passagent/">@passagent</a>
          </div>
        </div>
      </div>
    </div>
    <b-row class="justify-content-center pt-5">
      <b-col class="first-cols-block" cols="12">
        <b-img class="ig-image" src="/ig1.png"></b-img>
        <b-img class="ig-image" src="/ig2.png"></b-img>
        <b-img class="ig-image" src="/ig3.png"></b-img>
        <b-img class="ig-image" src="/ig4.png"></b-img>
        <b-img class="ig-image" src="/ig5.png"></b-img>
        <b-img class="ig-image" src="/ig6.png"></b-img>
      </b-col>
    </b-row>
    <b-row class="justify-content-center pb-5">
      <b-col class="second-cols-block" cols="12">
        <b-img class="ig-image" src="/ig7.png"></b-img>
        <b-img class="ig-image" src="/ig8.png"></b-img>
        <b-img class="ig-image" src="/ig9.png"></b-img>
        <b-img class="ig-image" src="/ig10.png"></b-img>
        <b-img class="ig-image" src="/ig11.png"></b-img>
        <b-img class="ig-image" src="/ig12.png"></b-img>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {
  name: "Photos"
}
</script>

<style>
.ig-image {
  padding: 5px;
}

.ig-title {
  font-size: 18px;
  font-family: 'Open Sans', sans-serif;
  font-weight: 400;
  color: #616161;
  text-align: right;
  width: 300px;
}

.ig-link {
  font-size: 40px;
  font-family: 'Noto Serif', serif;
  background: -webkit-linear-gradient(#EEA054, #D64763, #B62A99);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-weight: 700;
  color: #191919;
}

.ig-block {
  position: absolute;
  left: 20%;
  padding-top: 5rem;
  z-index: 2;
}

.ig-link-block {
  display: flex;
  justify-content: space-between;
  width: 300px;
}

.first-cols-block {
  display: flex;
  align-items: flex-end;
  justify-content: center;
}

.second-cols-block {
  display: flex;
  align-items: flex-start;
  justify-content: center;
}

@media (max-width: 1400px) {
  .first-cols-block {
    justify-content: start;
    margin-left: -40%;
  }
}

@media (max-width: 500px) {
  .first-cols-block {
    margin-left: -100%;
  }

  .ig-block {
    left: 10%;
    padding-top: 7rem;
  }
}

@media (max-width: 400px) {
  .ig-block {
    left: 3%;
    position: unset;
    margin-bottom: -13rem;
  }
}

@media (max-width: 340px) {
  .ig-title {
    text-align: left;
    font-size: 15px;
    padding-left: 3%;
  }

  .ig-logo {
    display: none;
  }
}

@media (min-width: 2000px) {
  .ig-block {
    left: 30%;
  }
}
</style>
