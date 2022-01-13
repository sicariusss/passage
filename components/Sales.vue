<template>
  <b-container fluid class="sales-block">
    <b-row class="justify-content-center pt-5 pb-5">
      <b-col cols="8">
        <b-row class="justify-content-center align-content-between pt-5 pb-5">
          <b-col xl="4" md="6" cols="12">
            <!--Заголовок-->
            <div class="sales-title">
              Выделись из толпы вместе с нами!
            </div>
            <!--Описание-->
            <p class="sales-desc">
              Приходите в ТЦ Александровский <br>
              Пассаж на шопинг, который больше <br>
              не найдете нигде в городе!
            </p>
            <b-row class="all-sales-button-block">
              <div class="all-sales-button">Все Акции</div>
            </b-row>
          </b-col>
          <!--1 акция-->
          <b-col xl="4" md="6" cols="12">
            <b-img style="width: 100%; cursor: pointer;" src="/sale1.png"></b-img>
            <!--Дата-->
            <div class="sales-date py-3">
              Только до 31 августа
            </div>
            <!--Заголовок акции-->
            <p class="sale-title">
              Суперакция в магазине Gloria Jeans 3=2!
            </p>
          </b-col>
          <!--2 акция-->
          <b-col xl="4" md="6" cols="12">
            <b-img style="width: 100%; cursor: pointer;" src="/sale2.png"></b-img>
            <!--Дата-->
            <div class="sales-date py-3">
              Только до 31 августа
            </div>
            <!--Заголовок акции-->
            <p class="sale-title">
              Акция в Gloria Jeans «Скидки на школьную форму»!
            </p>
          </b-col>
          <!--3 акция-->
          <b-col xl="4" md="6" cols="12">
            <b-img style="width: 100%; cursor: pointer;" src="/sale3.png"></b-img>
            <!--Дата-->
            <div class="sales-date py-3">
              Только до 31 августа
            </div>
            <!--Заголовок акции-->
            <p class="sale-title">
              Пришло время побаловать себя в магазине @watchman.russia
            </p>
          </b-col>
          <!--4 акция-->
          <b-col xl="4" md="6" cols="12">
            <b-img style="width: 100%; cursor: pointer;" src="/sale4.png"></b-img>
            <!--Дата-->
            <div class="sales-date py-3">
              Только до 31 августа
            </div>
            <!--Заголовок акции-->
            <p class="sale-title">
              Новый салона женской одежды @monaco_nt
            </p>
          </b-col>
          <!--5 акция-->
          <b-col xl="4" md="6" cols="12">
            <b-img style="width: 100%; cursor: pointer;" src="/sale5.png"></b-img>
            <!--Дата-->
            <div class="sales-date py-3">
              Только с 26 августа по 12 сентября 2021
            </div>
            <!--Заголовок акции-->
            <p class="sale-title">
              Маникюрный островок @printmanikyur
            </p>
          </b-col>
        </b-row>
        <!--Кнопка "Показать все"-->
        <b-row class="justify-content-center pb-5">
          <div class="sales-button">Показать все</div>
        </b-row>
        <!--Кнопка "Все акции" для мобильной версии-->
        <b-row class="all-sales-button-block-mobile">
          <div class="all-sales-button-mobile">Все Акции</div>
        </b-row>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {
  name: "Sales"
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Noto+Serif:ital,wght@0,400;0,700;1,400;1,700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;1,300;1,400;1,500;1,600;1,700;1,800&display=swap');

.sales-block {
  background: url("/sales-bg.svg") top center no-repeat;
  background-size: cover;
}

.sales-title {
  font-size: 50px;
  font-family: 'Noto Serif', serif;
  font-weight: 500;
  color: white;
  line-height: 1.2;
}

.sales-desc {
  font-size: 18px;
  font-family: 'Open Sans', sans-serif;
  font-weight: 400;
  color: white;
  padding-top: 1rem;
}

.all-sales-button {
  padding: 12px 33px;
  border: #1B3359 1px solid;
  color: #1B3359;
  font-family: 'Open Sans', sans-serif;
  font-weight: 600;
  font-size: 16px;
  cursor: pointer;
  background-color: white;
  margin-left: 15px;
}

.sales-button {
  padding: 12px 33px;
  border: white 1px solid;
  font-family: 'Open Sans', sans-serif;
  font-weight: 600;
  font-size: 16px;
  cursor: pointer;
  color: white;

}

.sales-button:hover {
  border: #1B3359 1px solid;
  background-color: white;
  color: #1B3359;
}

.all-sales-button:hover {
  border: white 1px solid;
  background-color: transparent;
  color: white;
}

.sales-date {
  font-family: 'Open Sans', sans-serif;
  font-weight: 400;
  font-size: 14px;
  color: white;
}

.sale-title {
  font-family: 'Open Sans', sans-serif;
  font-weight: 600;
  font-size: 22px;
  color: white;
  padding-bottom: 3rem;
  cursor: pointer;
}

.sale-title:hover {
  text-shadow: 1px 1px 2px black, 0 0 1em white, 0 0 0.2em white;
}

.all-sales-button-block {
  padding-top: 1rem;
}

@media (max-width: 1750px) {
  .sales-title {
    font-size: 40px;
  }
}

@media (max-width: 1400px) {
  .sales-title {
    font-size: 35px;
  }
}

@media (max-width: 1250px) {
  .sales-title {
    font-size: 30px;
  }
}

@media (max-width: 768px) {
  .sales-title {
    font-size: 40px;
  }

  .all-sales-button-block {
    padding-bottom: 3rem;
  }

  .all-sales-button, .sales-button {
    display: none;
  }

  .all-sales-button-mobile {
    padding: 12px 33px;
    border: #1B3359 1px solid;
    color: #1B3359;
    font-family: 'Open Sans', sans-serif;
    font-weight: 600;
    font-size: 16px;
    cursor: pointer;
    background-color: white;
    margin-left: 15px;
  }

  .all-sales-button-mobile:hover {
    border: white 1px solid;
    background-color: transparent;
    color: white;
  }

  .all-sales-button-block-mobile {
    margin-top: -5rem;
  }
}

@media (max-width: 360px) {
  .sales-title {
    font-size: 30px;
  }
  .sales-desc {
    font-size: 15px;
  }

  .sale-title {
    font-size: 18px;
  }
}

@media (min-width: 768px) {
  .all-sales-button-block-mobile {
    display: none;
  }
}
</style>
