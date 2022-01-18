<template>
  <b-container fluid class="pb-5">
    <b-row class="justify-content-center pt-5 pb-5">
      <b-col cols="10" md="8">
        <b-row class="justify-content-center pt-5 pb-5">
          <div class="news-block-title">
            Новости Александровского Пассажа
          </div>
        </b-row>
        <!--Карусель для разрешения от 1200 и больше -->
        <div v-if="windowWidth >= 1200">
          <VueSlickCarousel v-bind="bigSettings" ref="carousel">
            <div>
              <div class="news-image-block">
                <b-img class="news-image" src="/news1.png"></b-img>
                <!--Дата-->
                <div class="news-date py-3">
                  12 апреля 2021 - 20 апреля 2012
                </div>
                <!--Заголовок новости-->
                <p class="news-title">
                  Друзья, ТЦ Александровский Пассаж обновляется для вас!
                </p>

              </div>
            </div>
            <div>
              <div class="news-image-block">
                <b-img class="news-image" src="/news1.png"></b-img>
                <!--Дата-->
                <div class="news-date py-3">
                  12 апреля 2021 - 20 апреля 2012
                </div>
                <!--Заголовок новости-->
                <p class="news-title">
                  Друзья, ТЦ Александровский Пассаж обновляется для вас!
                </p>

              </div>
            </div>
            <div>
              <div class="news-image-block">
                <b-img class="news-image" src="/news1.png"></b-img>
                <!--Дата-->
                <div class="news-date py-3">
                  12 апреля 2021 - 20 апреля 2012
                </div>
                <!--Заголовок новости-->
                <p class="news-title">
                  Друзья, ТЦ Александровский Пассаж обновляется для вас!
                </p>
              </div>
            </div>
            <div>
              <div class="news-image-block">
                <b-img class="news-image" src="/news1.png"></b-img>
                <!--Дата-->
                <div class="news-date py-3">
                  12 апреля 2021 - 20 апреля 2012
                </div>
                <!--Заголовок новости-->
                <p class="news-title">
                  Друзья, ТЦ Александровский Пассаж обновляется для вас!
                </p>
              </div>
            </div>
          </VueSlickCarousel>
        </div>
        <!--Карусель для разрешения от 800px до 1200px -->
        <div v-else-if="windowWidth < 1200 && windowWidth >= 800">
          <VueSlickCarousel v-bind="smallSettings" ref="carousel">
            <div>
              <div class="news-image-block">
                <b-img class="news-image" src="/news1.png"></b-img>
                <!--Дата-->
                <div class="news-date py-3">
                  12 апреля 2021 - 20 апреля 2012
                </div>
                <!--Заголовок новости-->
                <p class="news-title">
                  Друзья, ТЦ Александровский Пассаж обновляется для вас!
                </p>

              </div>
            </div>
            <div>
              <div class="news-image-block">
                <b-img class="news-image" src="/news1.png"></b-img>
                <!--Дата-->
                <div class="news-date py-3">
                  12 апреля 2021 - 20 апреля 2012
                </div>
                <!--Заголовок новости-->
                <p class="news-title">
                  Друзья, ТЦ Александровский Пассаж обновляется для вас!
                </p>

              </div>
            </div>
            <div>
              <div class="news-image-block">
                <b-img class="news-image" src="/news1.png"></b-img>
                <!--Дата-->
                <div class="news-date py-3">
                  12 апреля 2021 - 20 апреля 2012
                </div>
                <!--Заголовок новости-->
                <p class="news-title">
                  Друзья, ТЦ Александровский Пассаж обновляется для вас!
                </p>
              </div>
            </div>
            <div>
              <div class="news-image-block">
                <b-img class="news-image" src="/news1.png"></b-img>
                <!--Дата-->
                <div class="news-date py-3">
                  12 апреля 2021 - 20 апреля 2012
                </div>
                <!--Заголовок новости-->
                <p class="news-title">
                  Друзья, ТЦ Александровский Пассаж обновляется для вас!
                </p>
              </div>
            </div>
          </VueSlickCarousel>
        </div>
        <!--Карусель для разрешения до 800px-->
        <div v-else-if="windowWidth < 800">
          <VueSlickCarousel v-bind="smolSettings" ref="carousel">
            <div>
              <div class="news-image-block">
                <b-img class="news-image" src="/news1.png"></b-img>
                <!--Дата-->
                <div class="news-date py-3">
                  12 апреля 2021 - 20 апреля 2012
                </div>
                <!--Заголовок новости-->
                <p class="news-title">
                  Друзья, ТЦ Александровский Пассаж обновляется для вас!
                </p>

              </div>
            </div>
            <div>
              <div class="news-image-block">
                <b-img class="news-image" src="/news1.png"></b-img>
                <!--Дата-->
                <div class="news-date py-3">
                  12 апреля 2021 - 20 апреля 2012
                </div>
                <!--Заголовок новости-->
                <p class="news-title">
                  Друзья, ТЦ Александровский Пассаж обновляется для вас!
                </p>

              </div>
            </div>
            <div>
              <div class="news-image-block">
                <b-img class="news-image" src="/news1.png"></b-img>
                <!--Дата-->
                <div class="news-date py-3">
                  12 апреля 2021 - 20 апреля 2012
                </div>
                <!--Заголовок новости-->
                <p class="news-title">
                  Друзья, ТЦ Александровский Пассаж обновляется для вас!
                </p>
              </div>
            </div>
            <div>
              <div class="news-image-block">
                <b-img class="news-image" src="/news1.png"></b-img>
                <!--Дата-->
                <div class="news-date py-3">
                  12 апреля 2021 - 20 апреля 2012
                </div>
                <!--Заголовок новости-->
                <p class="news-title">
                  Друзья, ТЦ Александровский Пассаж обновляется для вас!
                </p>
              </div>
            </div>
          </VueSlickCarousel>
        </div>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'

export default {
  name: 'News',
  components: {VueSlickCarousel},
  data() {
    return {
      windowWidth: global.innerWidth,
      bigSettings: {
        "dots": true,
        "infinite": true,
        "initialSlide": 2,
        "speed": 500,
        "slidesToShow": 3,
        "slidesToScroll": 3,
        "swipeToSlide": true
      },
      smallSettings: {
        "dots": true,
        "infinite": true,
        "initialSlide": 2,
        "speed": 500,
        "slidesToShow": 2,
        "slidesToScroll": 2,
        "swipeToSlide": true
      },
      smolSettings: {
        "dots": true,
        "infinite": true,
        "initialSlide": 2,
        "speed": 500,
        "slidesToShow": 1,
        "slidesToScroll": 1,
        "swipeToSlide": true
      },
    }
  },
  mounted() {
    window.onresize = () => {
      this.windowWidth = window.innerWidth
    }
  }
}
</script>

<style>
.news-date {
  font-size: 14px;
  font-family: 'Open Sans', sans-serif;
  font-weight: 400;
  color: #525252;
}

.news-title {
  font-size: 22px;
  font-family: 'Open Sans', sans-serif;
  font-weight: 600;
  color: #191919;
}

.news-block-title {
  font-size: 50px;
  font-family: 'Noto Serif', serif;
  font-weight: 700;
  color: #191919;
  line-height: 1.2;
}

.news-image {
  width: 100%;
  cursor: pointer;
}

.news-image-block {
  padding: 10px;
}

.slick-dots li button:before {
  content: '○';
  color: #1B3359 !important;
  font-family: unset;
  font-size: 15px;
  opacity: 1;
}

.slick-dots li.slick-active button:before {
  content: '●';
  color: #1B3359 !important;
  font-family: unset;
  font-size: 25px;
  opacity: 1;
  margin-top: -3px;
}

.slick-next:before {
  content: url("/arrow-right.svg");
  opacity: 1;
  z-index: 2;
}

.slick-prev:before {
  content: url("/arrow-left.svg");
  opacity: 1;
  z-index: 2;
}

.slick-prev {
  left: -2rem;
  z-index: 2;
  top: 50%;
}

.slick-next {
  right: 2rem;
  z-index: 2;
  top: 50%;
}

@media (max-width: 2500px) {
  .slick-prev {
    top: 40%;
  }

  .slick-next {
    top: 40%;
  }
}

@media (max-width: 1600px) {
  .slick-prev {
    top: 30%;
    left: -2.5rem;
  }

  .slick-next {
    top: 30%;
    right: 1rem;
  }

  .news-block-title {
    margin-left: 10%;
  }
}

@media (max-width: 1200px) {
  .news-block-title {
    font-size: 40px;
  }
}

@media (max-width: 800px) {
  .news-image-block {
    padding: 0;
  }
}

@media (max-width: 600px) {
  .news-block-title {
    font-size: 35px;
    margin-left: 5%;
  }

  .news-date {
    font-size: 12px;
  }

  .news-title {
    font-size: 18px;
  }
}

@media (max-width: 450px) {
  .news-block-title {
    font-size: 30px;
  }
}

@media (max-width: 350px) {
  .news-block-title {
    font-size: 25px;
  }
}
</style>
