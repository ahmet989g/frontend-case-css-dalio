<template>
    <section class="our-latest-projects mb-20">
        <div class="content-dalio">
            <div class="flex justify-center">
                <h2 class="mb-10 page-heading mx-20">Our latest Projects</h2>
            </div>
            <div class="tabs-content">
                <div class="flex flex-wrap mb-10">
                    <div class="w-full">
                        <ul class="flex mb-0 list-none flex-wrap pt-3 pb-4 flex-row tab-nav justify-center">
                            <li class="-mb-px mr-2 last:mr-0 text-center">
                                <a class="px-5 py-3 block leading-normal cursor-pointer" v-on:click="toggleTabs(1)" :class="{'text-white': openElement !== 1, 'text-dalio-yellow': openElement === 1}">
                                    All
                                </a>
                            </li>
                            <li class="-mb-px mr-2 last:mr-0 text-center">
                                <a class="px-5 py-3 block leading-normal cursor-pointer" v-on:click="toggleTabs(2)" :class="{'text-white': openElement !== 2, 'text-dalio-yellow': openElement === 2}">
                                    UI/UX
                                </a>
                            </li>
                            <li class="-mb-px mr-2 last:mr-0 text-center">
                                <a class="px-5 py-3 block leading-normal cursor-pointer" v-on:click="toggleTabs(3)" :class="{'text-white': openElement !== 3, 'text-dalio-yellow': openElement === 3}">
                                    Options
                                </a>
                            </li>
                            <li class="-mb-px mr-2 last:mr-0 text-center">
                                <a class="px-5 py-3 block leading-normal cursor-pointer" v-on:click="toggleTabs(4)" :class="{'text-white': openElement !== 4, 'text-dalio-yellow': openElement === 4}">
                                    Options
                                </a>
                            </li>
                            <li class="-mb-px mr-2 last:mr-0 text-center">
                                <a class="px-5 py-3 block leading-normal cursor-pointer" v-on:click="toggleTabs(5)" :class="{'text-white': openElement !== 5, 'text-dalio-yellow': openElement === 5}">
                                    Options
                                </a>
                            </li>
                        </ul>
                        <div class="relative flex flex-col min-w-0 break-words w-full mb-6">
                            <div class="px-4 py-5 flex-auto">
                                <div class="tab-content tab-space">
                                    <div class="grid grid-cols-2 gap-10">
                                        <div class="project-item" v-bind:class="{'hidden': openElement !== 1, 'block': openElement === 1}">
                                            <div class="image-content mb-5">
                                                <a href="javascript:;">
                                                    <img src="@/assets/images/page-image-5.png" alt="Project 1"/>
                                                </a>
                                            </div>
                                            <div class="info">
                                                <h4 class="mb-3"><a href="javascript:;">Talent.com - Logo, Full Redesign and Branding</a></h4>
                                                <p>Talent.com a new brand identity using their core values of optimism, transparency and approachability as inspiration. As a result, we were able to create the most streamlined</p>
                                            </div>
                                        </div>
                                        <div class="project-item" v-bind:class="{'hidden': openElement !== 1, 'block': openElement === 1}">
                                            <div class="image-content mb-5">
                                                <a href="javascript:;">
                                                    <img src="@/assets/images/page-image-6.png" alt="Project 1"/>
                                                </a>
                                            </div>
                                            <div class="info">
                                                <h4 class="mb-3"><a href="javascript:;">Bonfire - Landing Page Design Webby Awards Nomination</a></h4>
                                                <p>Pretty excited to announce that we just got nominated at the Webby Awards! easy to understand and to use should be essential for every business owner who uses their website.</p>
                                            </div>
                                        </div>
                                        
                                        <div class="project-item" v-bind:class="{'hidden': openElement !== 2, 'block': openElement === 2}">
                                            <div class="image-content mb-5">
                                                <a href="javascript:;">
                                                    <img src="@/assets/images/page-image-6.png" alt="Project 1"/>
                                                </a>
                                            </div>
                                            <div class="info">
                                                <h4 class="mb-3"><a href="javascript:;">Bonfire - Landing Page Design Webby Awards Nomination</a></h4>
                                                <p>Pretty excited to announce that we just got nominated at the Webby Awards! easy to understand and to use should be essential for every business owner who uses their website.</p>
                                            </div>
                                        </div>
                                        <div class="project-item" v-bind:class="{'hidden': openElement !== 2, 'block': openElement === 2}">
                                            <div class="image-content mb-5">
                                                <a href="javascript:;">
                                                    <img src="@/assets/images/page-image-5.png" alt="Project 1"/>
                                                </a>
                                            </div>
                                            <div class="info">
                                                <h4 class="mb-3"><a href="javascript:;">Talent.com - Logo, Full Redesign and Branding</a></h4>
                                                <p>Talent.com a new brand identity using their core values of optimism, transparency and approachability as inspiration. As a result, we were able to create the most streamlined</p>
                                            </div>
                                        </div>
                                        <div class="project-item" v-bind:class="{'hidden': openElement !== 3, 'block': openElement === 3}">
                                            <div class="image-content mb-5">
                                                <a href="javascript:;">
                                                    <img src="@/assets/images/page-image-5.png" alt="Project 1"/>
                                                </a>
                                            </div>
                                            <div class="info">
                                                <h4 class="mb-3"><a href="javascript:;">Talent.com - Logo, Full Redesign and Branding</a></h4>
                                                <p>Talent.com a new brand identity using their core values of optimism, transparency and approachability as inspiration. As a result, we were able to create the most streamlined</p>
                                            </div>
                                        </div>
                                        <div class="project-item" v-bind:class="{'hidden': openElement !== 4, 'block': openElement === 4}">
                                            <div class="image-content mb-5">
                                                <a href="javascript:;">
                                                    <img src="@/assets/images/page-image-6.png" alt="Project 1"/>
                                                </a>
                                            </div>
                                            <div class="info">
                                                <h4 class="mb-3"><a href="javascript:;">Bonfire - Landing Page Design Webby Awards Nomination</a></h4>
                                                <p>Pretty excited to announce that we just got nominated at the Webby Awards! easy to understand and to use should be essential for every business owner who uses their website.</p>
                                            </div>
                                        </div>
                                        <div class="project-item" v-bind:class="{'hidden': openElement !== 5, 'block': openElement === 5}">
                                            <div class="image-content mb-5">
                                                <a href="javascript:;">
                                                    <img src="@/assets/images/page-image-5.png" alt="Project 1"/>
                                                </a>
                                            </div>
                                            <div class="info">
                                                <h4 class="mb-3"><a href="javascript:;">Talent.com - Logo, Full Redesign and Branding</a></h4>
                                                <p>Talent.com a new brand identity using their core values of optimism, transparency and approachability as inspiration. As a result, we were able to create the most streamlined</p>
                                            </div>
                                        </div>
                                    </div>
                                    
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="flex justify-center">
                    <a href="/" target="_blank" class="btn btn-yellow flex justify-center items-center rounded-[30px] bg-dalio-yellow px-5 py-3">
                        <span>Load More</span>
                        <svg class="icon icon--button:upright-arrow">
                            <use xlink:href="#icon-upright-arrow"></use>
                        </svg>
                    </a>
                </div>
            </div>
        </div>
  </section>
</template>

<script>
export default {
  name: "pink-tabs",
  data() {
    return {
      openElement: 1
    }
  },
  methods: {
    toggleTabs: function(tabNumber){
      this.openElement = tabNumber
    }
  }
}
</script>

<style lang="scss" scoped>
.tabs-content{
    .tab-nav{
        a{
            font-size: 16px;
            font-weight: 500;
            line-height: 30px;
        }
    }

    .project-item{
        h4{
            max-width: 400px;
            a{
                color: #FFFFFF;
                font-size: 24px;
                font-weight: 700;
                line-height: 36px;
            }
            a:hover{
                color: #FFC93E;
            }
        }
        p{
            color: #E0E5F3;
            font-size: 16px;
            font-weight: 400;
            line-height: 30px;
        }
    }
}
</style>