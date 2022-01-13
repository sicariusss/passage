<template>
  <b-container fluid class="header-block">
    <b-row>
      <b-row style="position: absolute; z-index: 1">
        <div>
          <b-navbar class="navbar-dark" toggleable="lg">
            <b-navbar>
              <b-navbar-brand href="#">
                <b-row class="nav-row">
                  <b-col cols="1">
                    <b-img width="35px" height="43px" src="/logo.png"></b-img>
                  </b-col>
                  <div class="nav-title">
                    <div class="title-first">ПАССАЖ</div>
                    <div class="title-second">АЛЕКСАНДРОВСКИЙ</div>
                  </div>
                </b-row>
              </b-navbar-brand>
            </b-navbar>
            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
            <b-collapse id="nav-collapse" is-nav>
              <b-navbar-nav style="margin-left: 10%; padding-top: 2.5rem;">
                <b-nav-item href="#">Магазины</b-nav-item>
                <b-nav-item href="#">Образы</b-nav-item>
                <b-nav-item href="#">Новости</b-nav-item>
                <b-nav-item href="#">Места</b-nav-item>
                <b-nav-item href="#">Арендатору</b-nav-item>
                <b-nav-item href="#">Контакты</b-nav-item>
              </b-navbar-nav>
            </b-collapse>
          </b-navbar>
        </div>
      </b-row>
      <b-col class="left-block" cols="12" lg="5">
        <b-row style="padding-top: 10rem; padding-right: 2rem">
          <b-col class="left-block-text" cols="12" xl="8">
            <p class="header-title">
              Стильный <br>
              Шоппинг <br>
              В Центре Города
            </p>
            <p
              style="font-size: 18px; font-family: 'Open Sans', sans-serif; font-weight: 400; color: white; line-height: 1.3; padding-top: 1rem">
              Приходите в ТЦ Александровский <br>
              Пассаж на шопинг, который больше <br>
              не найдете нигде в городе!
            </p>
            <b-row style="padding-top: 20px">
              <b-col cols="12" xl="6">
                <div>
                  <b-img width="30px" height="30px" src="/header-clock.svg"></b-img>
                  <div style="font-size: 22px; font-family: 'Open Sans', sans-serif; font-weight: 600; color: white;">
                    C 10:00 до 20:00
                  </div>
                  <div style="font-size: 14px; font-family: 'Open Sans', sans-serif; font-weight: 400; color: #BABABA;">
                    Без выходных
                  </div>
                </div>
              </b-col>
              <b-col class="header-pin" cols="12" xl="6">
                <div>
                  <b-img width="30px" height="30px" src="/header-pin.svg"></b-img>
                  <div style="font-size: 22px; font-family: 'Open Sans', sans-serif; font-weight: 600; color: white;">
                    пр-т Ленина д.22
                  </div>
                </div>
              </b-col>
            </b-row>
          </b-col>
        </b-row>
      </b-col>
      <b-col class="right-block" cols="12" lg="7"></b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;1,300;1,400;1,500;1,600;1,700;1,800&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Noto+Serif:ital,wght@0,400;0,700;1,400;1,700&display=swap');

.nav-row {
  padding-top: 2.5rem;
  flex-wrap: nowrap;
  align-items: end;
  padding-left: 15vw;
}

li.nav-item {
  padding-left: 5%;
}

.header-title {
  font-size: 50px;
  font-family: 'Noto Serif', serif;
  font-weight: 500;
  color: white;
  line-height: 1.2;
}

@media (max-width: 350px) {
  .header-title {
    font-size: 35px;
  }
}

@media (max-width: 1400px) {
  .nav-row {
    padding-left: 5vw;
  }

  li.nav-item {
    padding-left: 2%;
  }
}

@media (max-width: 1200px) {
  .header-pin {
    padding-top: 20px;
  }
}

@media (max-width: 370px) {
  .nav-row {
    padding-left: 1vw;
  }
}

.nav-title {
  text-align: center;
  padding-left: 40px;
}

.navbar-toggler {
  border: none;
  padding-top: 2rem;
  z-index: 2;
}

@media (max-width: 360px) {
  .nav-title {
    padding-left: 30px;
  }

  .navbar-toggler {
    margin-left: -2rem;
  }
}

@media (max-width: 320px) {
  .navbar-toggler {
    margin-left: -3rem;
  }
}

.left-block {
  background: url("/header-bg1.svg") top left no-repeat;
  height: 774px;
}

.right-block {
  background: url("/header-bg2.png") top center no-repeat;
}

@media (max-width: 991px) {
  .left-block {
    background-size: cover;
  }

  .right-block {
    height: 550px;
    background-size: cover;
  }
}

.title-first {
  font-family: "Playfair Display", serif;
  color: white;
  font-size: 12px;
  font-weight: 900;
}

.title-second {
  font-family: "Playfair Display", serif;
  color: white;
  font-size: 14px;
  font-weight: 900;
}

@media (max-width: 300px) {
  .title-first {
    font-size: 8px;
  }

  .title-second {
    font-size: 10px;
  }
}

a.nav-link {
  color: white !important;
  font-family: 'Open Sans', sans-serif;
  font-weight: 600;
  font-size: 16px;
}

a.nav-link:hover {
  text-shadow: 1px 1px 2px black, 0 0 1em white, 0 0 0.2em white;
}

.left-block-text {
  margin-left: 7%;
}

@media (min-width: 1400px) {
  .left-block-text {
    margin-left: 33.333333%;
  }
}
</style>
