<template>
  <main class="z-10">
    <HeaderBG/>
    <DigitalAgency/>
    <WhatWeDo/>
    <OurSolution/>
    <ServiceComponent/>
    <OurLatestProjects/>
    <WhatSay/>
  </main>
</template>

<script>
import HeaderBG from './HeaderBG.vue'
import DigitalAgency from './DigitalAgency.vue'
import WhatWeDo from './WhatWeDo.vue'
import OurSolution from './OurSolution.vue'
import ServiceComponent from './ServiceComponent.vue'
import OurLatestProjects from './OurLatestProjects.vue'
import WhatSay from './WhatSay.vue'
export default {
  components: {
    HeaderBG,
    DigitalAgency,
    WhatWeDo,
    OurSolution,
    ServiceComponent,
    OurLatestProjects,
    WhatSay
  }
}
</script>

<style>

</style>