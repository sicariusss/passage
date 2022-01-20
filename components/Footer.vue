<template>
  <b-container fluid class="footer-block pb-5 pt-5">
    <b-row class="justify-content-center pt-5">
      <b-col cols="12" md="4" xl="3">
        <b-row class="footer-logo-row">
          <b-col cols="1">
            <b-img width="35px" height="43px" src="/logo.png"></b-img>
          </b-col>
          <div class="footer-title">
            <div class="footer-first">ПАССАЖ</div>
            <div class="footer-second">АЛЕКСАНДРОВСКИЙ</div>
          </div>
        </b-row>
        <b-row class="footer-info pt-5 pb-3">
          <div>
            <a href="tel:+73435378252">(3435) 37-82-52 (приёмная)</a>
          </div>
          <div class="py-3">
            г. Нижний Тагил, проспект Ленина д.22
          </div>
          <div>
            <a href="mailto:passage-nt@mail.ru">passage-nt@mail.ru</a>
          </div>
        </b-row>
      </b-col>
      <b-col cols="12" md="7" xl="5">
        <b-row class="footer-nav-block justify-content-end align-content-between">
          <b-col cols="auto" class="py-3"><a class="footer-nav-link" href="#">Новости</a>
          </b-col>
          <b-col cols="auto" class="py-3"><a class="footer-nav-link" href="#">Магазины</a>
          </b-col>
          <b-col cols="auto" class="py-3"><a class="footer-nav-link" href="#">Образы</a>
          </b-col>
          <b-col cols="auto" class="py-3"><a class="footer-nav-link" href="#">Места</a>
          </b-col>
          <b-col cols="auto" class="py-3"><a class="footer-nav-link" href="#">Арендатору</a>
          </b-col>
          <b-col cols="auto" class="py-3"><a class="footer-nav-link" href="#">Контакты</a>
          </b-col>
        </b-row>
        <b-row class="footer-media-links justify-content-end pt-3 pb-5">
          <b-col cols="auto">
            <a href="https://www.instagram.com/passagent/">
              <b-img style="cursor: pointer" src="/footer-ig.svg"></b-img>
            </a>
          </b-col>
          <b-col cols="auto">
            <a href="https://vk.com/passagent">
              <b-img style="cursor: pointer" src="/footer-vk.svg"></b-img>
            </a>
          </b-col>
        </b-row>
      </b-col>
    </b-row>
    <b-row class="justify-content-center">
      <div class="footer-c">
        © 2021
      </div>
    </b-row>
  </b-container>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style>
.footer-block {
  background: #1B3359 url("/footer-bg.svg") no-repeat;
  background-size: cover;
}

a.footer-nav-link {
  color: white !important;
  font-family: 'Open Sans', sans-serif;
  font-weight: 600;
  font-size: 16px;
  text-decoration: none;
}

a.footer-nav-link:hover {
  text-shadow: 1px 1px 2px black, 0 0 1em white, 0 0 0.2em white;
}

.footer-c {
  color: white;
  font-family: 'Roboto', sans-serif;
  font-size: 14px;
  font-weight: 400;
}

.footer-logo-row {
  flex-wrap: nowrap;
  align-items: end;
}

.footer-title {
  text-align: center;
  padding-left: 40px;
}

.footer-first {
  font-family: "Playfair Display", serif;
  color: white;
  font-size: 12px;
  font-weight: 900;
}

.footer-second {
  font-family: "Playfair Display", serif;
  color: white;
  font-size: 14px;
  font-weight: 900;
}

.footer-info {
  color: white;
  font-family: 'Roboto', sans-serif;
  font-size: 14px;
  font-weight: 400;
  flex-direction: column;
  padding-left: 1rem;
}

.footer-info a {
  color: white;
  font-family: 'Roboto', sans-serif;
  font-size: 14px;
  font-weight: 400;
  text-decoration: none;
}

@media (max-width: 768px) {
  .footer-c {
    display: none;
  }
  .footer-nav-block {
    display: none;
  }
  .footer-media-links {
    justify-content: center !important;
  }
  .footer-logo-row {
    justify-content: center !important;
  }
  .footer-info {
    text-align: center;
  }
  .footer-title {
    padding-left: 30px;
  }
  .footer-block {
    padding-left: 0;
  }
}
</style>
