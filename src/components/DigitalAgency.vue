<template>
  <section class="digital-agency mb-20">
        <div class="text">
            <img src="@/assets/images/svg/world-class.svg" alt="World Class">
            <img src="@/assets/images/svg/dashed-line.svg" alt="Lines" class="lines">
            <h1><span>Digital</span><span>Agency</span></h1>
            <p class="mt-10 mb-10">Full-service design support that growing B2B companies need. World leading agency.</p>
            <a href="/" target="_blank" class="btn btn-yellow flex justify-center items-center rounded-[30px] bg-dalio-yellow px-5 py-3">
                <span>Our Projects</span>
                <svg class="icon icon--button:upright-arrow">
                    <use xlink:href="#icon-upright-arrow"></use>
                </svg>
            </a>
            <div class="right-image">
                <img src="@/assets/images/page-image-1.png" alt="Digital Agency 1">
                <button type="button" class="btn btn-play">
                    <svg viewBox="0 0 100 100" width="100" height="100">
                        <defs>
                            <path id="circle"
                            d="
                                M 50, 50
                                m -37, 0
                                a 37,37 0 1,1 74,0
                                a 37,37 0 1,1 -74,0"/>
                        </defs>
                        <text font-size="16">
                            <textPath xlink:href="#circle">
                                Digital <tspan>*</tspan> agency dalio <tspan>*</tspan>
                            </textPath>
                        </text>
                    </svg>
                    <svg class="icon icon--button:play">
                        <use xlink:href="#icon-play"></use>
                    </svg>
                </button>
                <svg class="icon icon--button:star star">
                    <use xlink:href="#icon-star"></use>
                </svg>
                <svg class="icon icon--button:star star2">
                    <use xlink:href="#icon-star"></use>
                </svg>
                <div class="ellipse-shadow-right-bottom"></div>
            </div>
        </div>
        <div class="left-image">
            <img src="@/assets/images/page-image-2.png" alt="Digital Agency 2">
            <svg class="icon icon--button:lines">
                <use xlink:href="#icon-lines"></use>
            </svg>
        <div class="ellipse-shadow-left-bottom"></div>
        </div>
        <div class="scroll-down">
            <button type="button" class="btn btn-scroll-down">
                <span>Scroll Down</span>
                <svg class="icon icon--button:scroll-down">
                    <use xlink:href="#icon-scroll-down"></use>
                </svg>
            </button>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style>

</style>