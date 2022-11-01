<template>
    <section class="client-comment mb-20">
        <h2 class="mb-10 page-heading">What say happy clients</h2>
        <swiper
            :slides-per-view="1.8"
            :space-between="50"
            @swiper="onSwiper"
            @slideChange="onSlideChange">
            <swiper-slide>
                <div class="client-comment-item p-20">
                    <svg class="icon icon--button:quotation mb-7">
                        <use xlink:href="#icon-quotation"></use>
                    </svg>
                    <p class="mb-7">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sit semper consequat in dolor mattis pellentesque suspendisse vulputate nec. Scelerisque elementum, consequat pharetra lectus eget vivamus ut. Magna aliquam tellus at volutpat cras aliquet facilisi quis adipiscing. Proin egestas et pellentesque augue pretium, amet. Natoque blandit augue integer maecenas mattis amet, nec.</p>
                    <div class="client-info flex justify-between items-center">
                        <div class="client flex items-center">
                            <div class="image mr-3">
                                <img src="@/assets/images/user-image-1.png" alt="Brooklyn Simmons">
                            </div>
                            <div class="info">
                                <h6>Brooklyn Simmons</h6>
                                <p>Pendron.Inc, CEO</p>
                            </div>
                        </div>
                        <div class="stars flex">
                            <svg class="icon icon--button:comment-star">
                                <use xlink:href="#icon-comment-star"></use>
                            </svg>
                            <svg class="icon icon--button:comment-star">
                                <use xlink:href="#icon-comment-star"></use>
                            </svg>
                            <svg class="icon icon--button:comment-star">
                                <use xlink:href="#icon-comment-star"></use>
                            </svg>
                            <svg class="icon icon--button:comment-star">
                                <use xlink:href="#icon-comment-star"></use>
                            </svg>
                            <svg class="icon icon--button:comment-star">
                                <use xlink:href="#icon-comment-star"></use>
                            </svg>
                        </div>
                    </div>
                </div>
            </swiper-slide>
            <swiper-slide>
                <div class="client-comment-item p-20">
                    <svg class="icon icon--button:quotation mb-7">
                        <use xlink:href="#icon-quotation"></use>
                    </svg>
                    <p class="mb-7">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sit semper consequat in dolor mattis pellentesque suspendisse vulputate nec. Scelerisque elementum, consequat pharetra lectus eget vivamus ut. Magna aliquam tellus at volutpat cras aliquet facilisi quis adipiscing. Proin egestas et pellentesque augue pretium, amet. Natoque blandit augue integer maecenas mattis amet, nec.</p>
                    <div class="client-info flex justify-between items-center">
                        <div class="client flex items-center">
                            <div class="image mr-3">
                                <img src="@/assets/images/user-image-1.png" alt="Brooklyn Simmons">
                            </div>
                            <div class="info">
                                <h6>Brooklyn Simmons</h6>
                                <p>Pendron.Inc, CEO</p>
                            </div>
                        </div>
                        <div class="stars flex">
                            <svg class="icon icon--button:comment-star">
                                <use xlink:href="#icon-comment-star"></use>
                            </svg>
                            <svg class="icon icon--button:comment-star">
                                <use xlink:href="#icon-comment-star"></use>
                            </svg>
                            <svg class="icon icon--button:comment-star">
                                <use xlink:href="#icon-comment-star"></use>
                            </svg>
                            <svg class="icon icon--button:comment-star">
                                <use xlink:href="#icon-comment-star"></use>
                            </svg>
                            <svg class="icon icon--button:comment-star">
                                <use xlink:href="#icon-comment-star"></use>
                            </svg>
                        </div>
                    </div>
                </div>
            </swiper-slide>
            <swiper-slide>
                <div class="client-comment-item p-20">
                    <svg class="icon icon--button:quotation mb-7">
                        <use xlink:href="#icon-quotation"></use>
                    </svg>
                    <p class="mb-7">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sit semper consequat in dolor mattis pellentesque suspendisse vulputate nec. Scelerisque elementum, consequat pharetra lectus eget vivamus ut. Magna aliquam tellus at volutpat cras aliquet facilisi quis adipiscing. Proin egestas et pellentesque augue pretium, amet. Natoque blandit augue integer maecenas mattis amet, nec.</p>
                    <div class="client-info flex justify-between items-center">
                        <div class="client flex items-center">
                            <div class="image mr-3">
                                <img src="@/assets/images/user-image-1.png" alt="Brooklyn Simmons">
                            </div>
                            <div class="info">
                                <h6>Brooklyn Simmons</h6>
                                <p>Pendron.Inc, CEO</p>
                            </div>
                        </div>
                        <div class="stars flex">
                            <svg class="icon icon--button:comment-star">
                                <use xlink:href="#icon-comment-star"></use>
                            </svg>
                            <svg class="icon icon--button:comment-star">
                                <use xlink:href="#icon-comment-star"></use>
                            </svg>
                            <svg class="icon icon--button:comment-star">
                                <use xlink:href="#icon-comment-star"></use>
                            </svg>
                            <svg class="icon icon--button:comment-star">
                                <use xlink:href="#icon-comment-star"></use>
                            </svg>
                            <svg class="icon icon--button:comment-star">
                                <use xlink:href="#icon-comment-star"></use>
                            </svg>
                        </div>
                    </div>
                </div>
            </swiper-slide>
        </swiper>
    </section>
</template>
<script>
  import { Swiper, SwiperSlide } from 'swiper/vue';

  import 'swiper/css';

  export default {
    components: {
      Swiper,
      SwiperSlide,
    },
    setup() {
      const onSwiper = (swiper) => {
        console.log(swiper);
      };
      const onSlideChange = () => {
        console.log('slide change');
      };
      return {
        onSwiper,
        onSlideChange,
      };
    },
  };
</script>

<style lang="scss" scoped>
.client-comment{
    margin-left: 10%;
    .client-comment-item{
        background: #353F5B;
        border-radius: 50px;
        >svg{
            fill: #F3F5F6;
            width: 62px;
            height: 48px;
            opacity: .5;
        }
        >p{
            color: #E0E5F3;
            font-size: 16px;
            font-weight: 400;
            line-height: 30px;
        }
        .client-info{
            .info{
                h6{
                    color: #FFFFFF;
                    font-size: 18px;
                    font-weight: 500;
                    line-height: 30px;
                }
                p{
                    color: #FFC93E;
                    font-size: 16px;
                    font-weight: 400;
                    line-height: 30px;
                }
            }
            .stars{
                svg{
                    fill: #FFFFFF;
                    width: 16px;
                    height: 16px;
                }
                svg:not(:last-child){
                    margin-right: 8px;
                }
            }
        }
    }
}
@media (max-width:1450px) and (min-width:1024px) {
    .client-comment{
        margin-left: 5%;
    }
}
</style>