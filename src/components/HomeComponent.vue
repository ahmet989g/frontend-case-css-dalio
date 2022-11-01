<template>
  <main class="z-10">
    <section class="absolute top-0 header-inner">
        <div class="ellipse-shadow-left"></div>
        <div class="table">
            <div class="star"></div>
            <div class="lines"></div>
        </div>
        <div class="ellipse-shadow-right">
            <div class="star"></div>
        </div>
    </section>
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
    <section class="what-we-do">
        <div class="content-dalio">
            <div class="grid grid-cols-2 gap-10 mx-20 mb-20">
                <div class="left-block">
                    <h2 class="mb-10 page-heading">We are a creative digital agency</h2>
                    <p class="mb-10">Dalio started with a vision for building an agency to solve the business problems of the future, and that requires a different model. We’re not a branding agency that dabbles in tech, and we’re not a development shop that leaves you hanging when it’s time 
to go to market.</p>
                    <p class="mb-10">We start with human experience and layer in technology and marketing to deliver truly integrated digital solutions. This unique set of capabilities sets us apart from other agencies and positions DIG to help you attack your goals.</p>
                    
                    <a href="/" target="_blank" class="btn btn-yellow flex justify-center items-center rounded-[30px] bg-dalio-yellow px-5 py-3">
                        <span>Contact us</span>
                        <svg class="icon icon--button:upright-arrow">
                            <use xlink:href="#icon-upright-arrow"></use>
                        </svg>
                    </a>
                </div>
                <div class="right-block">
                    <div class="image-content">
                        <img src="@/assets/images/page-image-3.png" alt="Page Image">
                    </div>
                </div>
            </div>
            <div class="counter-content">
                <div class="grid grid-cols-4 gap-20 mx-20 mb-20">
                    <div class="counter--item">
                        <h3>4.8k</h3>
                        <p>Job Completed</p>
                    </div>
                    <div class="counter--item">
                        <h3>12+</h3>
                        <p>Industry Experience</p>
                    </div>
                    <div class="counter--item">
                        <h3>2.5k</h3>
                        <p>World wide clients</p>
                    </div>
                    <div class="counter--item">
                        <h3>120+</h3>
                        <p>Won Awards</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="our-solition p-20">
        <div class="bg-solution"></div>
        <div class="content-dalio">
            <div class="flex justify-between items-center gap-10">
                <div class="left-block">
                    <div class="image-content">
                        <img src="@/assets/images/page-image-4.png" alt="Our Solution">
                        <svg class="icon icon--button:lines">
                            <use xlink:href="#icon-lines"></use>
                        </svg>
                    </div>
                </div>
                <div class="right-block">
                    <h2 class="mb-10 page-heading">Our Solution Approach</h2>
                    <ul>
                        <li class="mb-8">
                            <h5>Data Analysis with problem factor</h5>
                            <p>Delivering the spatial expertise of the largest, most sophisticated performance marketing agencies, while providing intimate, boutique-like support.</p>
                        </li>
                        <li class="mb-8">
                            <h5>Functionality solution for users</h5>
                            <p>Delivering the spatial expertise of the largest, most sophisticated performance marketing agencies.</p>
                        </li>
                        <li>
                            <h5>Latest technology enabled</h5>
                            <p>Technology the spatial expertise of the largest, most sophisticated performance marketing agencies, while providing intimate, boutique-like support.</p>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
    <section class="service my-20">
        <div class="content-dalio">
            <div class="flex items-center justify-between">
                <h2 class="mb-10 page-heading mx-20">Service we can<br/>help you</h2>
                <a href="javascript:;" class="btn btn-white flex justify-center items-center rounded-[30px] px-5 py-3 mx-20">
                    <span>See All</span>
                    <svg class="icon icon--button:upright-arrow">
                        <use xlink:href="#icon-upright-arrow"></use>
                    </svg>
                </a>
            </div>
            <div class="grid grid-cols-2 gap-10 mx-20">
                <div class="left-block">
                    <div class="service-item px-10 py-20 mb-10">
                        <svg class="icon icon--button:content-writing mb-5">
                            <use xlink:href="#icon-content-writing"></use>
                        </svg>
                        <h4 class="mb-3">Content Writing</h4>
                        <p class="mb-10">Lorem ipsum dolor sit amet, consectetur adipiscing elit. A consequat nunc id purus pretium sagittis. Nulla ridiculus nullam bibendum luctus viverra. Eu pellentesque sem sed platea diam dignissim duis purus.</p>
                        <a href="javascript:;" class="btn btn-white flex justify-center items-center rounded-[30px] px-5 py-3">
                            <span>Read More</span>
                            <svg class="icon icon--button:upright-arrow">
                                <use xlink:href="#icon-upright-arrow"></use>
                            </svg>
                        </a>
                    </div>
                    <div class="service-item px-10 py-20">
                        <svg class="icon icon--button:ux-research mb-5">
                            <use xlink:href="#icon-ux-research"></use>
                        </svg>
                        <h4 class="mb-3">Branding</h4>
                        <p class="mb-10">Lorem ipsum dolor sit amet, consectetur adipiscing elit. A consequat nunc id purus pretium sagittis diam quis massa. Nulla ridiculus nullam bibendum luctus viverra. Eu pellentesque sem sed platea diam dignissim duis purus.</p>
                        <a href="javascript:;" class="btn btn-white flex justify-center items-center rounded-[30px] px-5 py-3">
                            <span>Read More</span>
                            <svg class="icon icon--button:upright-arrow">
                                <use xlink:href="#icon-upright-arrow"></use>
                            </svg>
                        </a>
                    </div>
                </div>
                <div class="right-block mt-10">
                    <div class="service-item px-10 py-20 mb-10">
                        <svg class="icon icon--button:branding mb-5">
                            <use xlink:href="#icon-branding"></use>
                        </svg>
                        <h4 class="mb-3">UX Research</h4>
                        <p class="mb-10">Lorem ipsum dolor sit amet, consectetur adipiscing elit. A consequat nunc id purus pretium sagittis diam quis massa. Nulla ridiculus nullam bibendum luctus viverra. Eu pellentesque sem sed platea diam dignissim duis purus.</p>
                        <a href="javascript:;" class="btn btn-white flex justify-center items-center rounded-[30px] px-5 py-3">
                            <span>Read More</span>
                            <svg class="icon icon--button:upright-arrow">
                                <use xlink:href="#icon-upright-arrow"></use>
                            </svg>
                        </a>
                    </div>
                    <div class="service-item px-10 py-20">
                        <svg class="icon icon--button:web-design mb-5">
                            <use xlink:href="#icon-web-design"></use>
                        </svg>
                        <h4 class="mb-3">Web Design</h4>
                        <p class="mb-10">Lorem ipsum dolor sit amet, consectetur adipiscing elit. A consequat nunc id purus pretium sagittis diam quis massa. Nulla ridiculus nullam bibendum luctus viverra. Eu pellentesque sem sed platea diam dignissim duis purus.</p>
                        <a href="javascript:;" class="btn btn-white flex justify-center items-center rounded-[30px] px-5 py-3">
                            <span>Read More</span>
                            <svg class="icon icon--button:upright-arrow">
                                <use xlink:href="#icon-upright-arrow"></use>
                            </svg>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <OurLatestProjects/>
    <WhatSay/>
  </main>
</template>

<script>
import OurLatestProjects from './OurLatestProjects.vue'
import WhatSay from './WhatSay.vue'
export default {
  components: {
    OurLatestProjects,
    WhatSay
  }
}
</script>

<style>

</style>