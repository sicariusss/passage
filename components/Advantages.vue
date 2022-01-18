<template>
  <b-container fluid>
    <b-row class="advantages-row justify-content-center">
      <b-col cols="10" md="8">
        <b-row>
          <b-col xl="3" md="6" cols="12">
            <!--Первое преимущество-->
            <b-row class="first-advantage">
              <b-col cols="3">
                <b-img width="43px" height="45px" src="/t-shirt.png"></b-img>
              </b-col>
              <b-col cols="9">
                <div class="advantage-title">
                  Уникальные бренды
                </div>
                <div class="advantage-desc">
                  Описание приемущества
                  Описание приемущества
                </div>
              </b-col>
            </b-row>
          </b-col>
          <b-col xl="3" md="6" cols="12">
            <!--Второе преимущество-->
            <b-row class="second-advantage">
              <b-col cols="3">
                <b-img width="48px" height="40px" src="/booking.svg"></b-img>
              </b-col>
              <b-col cols="9">
                <div class="advantage-title">
                  ONLINE бронирование
                </div>
                <div class="advantage-desc">
                  Описание приемущества
                  Описание приемущества
                </div>
              </b-col>
            </b-row>
          </b-col>
          <b-col xl="3" md="6" cols="12">
            <!--Третье преимущество-->
            <b-row class="third-advantage">
              <b-col cols="3">
                <b-img width="41px" height="41px" src="/gift.svg"></b-img>
              </b-col>
              <b-col cols="9">
                <div class="advantage-title">
                  Акции и подарки
                </div>
                <div class="advantage-desc">
                  Описание приемущества
                  Описание приемущества
                </div>
              </b-col>
            </b-row>
          </b-col>
          <b-col xl="3" md="6" cols="12">
            <!--Четвертое преимущество-->
            <b-row class="fourth-advantage">
              <b-col cols="3">
                <b-img width="51px" height="43px" src="/parking.svg"></b-img>
              </b-col>
              <b-col cols="9">
                <div class="advantage-title">
                  Большая парковка
                </div>
                <div class="advantage-desc">
                  Описание приемущества
                  Описание приемущества
                </div>
              </b-col>
            </b-row>
          </b-col>
        </b-row>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {
  name: "Advantages"
}
</script>

<style>
.advantages-row {
  padding-top: 100px;
  padding-bottom: 100px;
  align-content: center;
}

.advantage-title {
  color: #191919;
  font-family: 'Open Sans', sans-serif;
  font-weight: 700;
  font-size: 16px;
}

.advantage-desc {
  color: #525252;
  font-family: 'Open Sans', sans-serif;
  font-weight: 400;
  font-size: 16px;
}

@media (max-width: 1200px) {
  .third-advantage, .fourth-advantage {
    padding-top: 30px;
  }
}

@media (max-width: 768px) {
  .second-advantage {
    padding-top: 30px;
  }
}
</style>
