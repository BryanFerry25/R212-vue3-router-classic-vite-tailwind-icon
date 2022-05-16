<template>
  <div>
    <header1 />
  </div>
  <div class="p-2 grid grid-flow-row-dense grid-cols-[repeat(auto-fit,minmax(300px,1fr))]">

    <card price="2700" nom="Beverly Springfield"  image="/public/image/pexels-binyamin-mellish-106399 1.png" texte="2821 Lake Sevilla, Palm Harbor, TX" bathroom="2 Bathrooms" size="6x7.5 m²"/>

    <card price="2095" nom="Palm Harbor"  image="/public/image/pexels-binyamin-mellish-106399 4.png" texte="2699 Green Valley, Highland Lake" bathroom="2 Bathrooms" size="6x7 m²"/>

    <card price="4800" nom="Tarpon Bay"  image="/public/image/pexels-binyamin-mellish-106399_2.png" texte="103 Lake Shores, Michigan, IN" bathroom="2 Bathrooms" size="6x7.5 m²"/>

    <card price="4550" nom="Faulkner Ave"  image="/public/image/pexels-binyamin-mellish-106399 3.png" texte="909 Woodland St, Michigan, IN" bathroom="3 Bathrooms" size="8x10 m²"/>

    <card price="3100" nom="Cover Red" image="/public/image/pexels-binyamin-mellish-106399 6.png" texte="243 CurlewRoad, PalmHarbor, TX" bathroom="2 Bathrooms" size="6x7.5 m²"/>

    <card price="4650" nom="St. Christal" image="/public/image/pexels-binyamin-mellish-106399 5.png"  texte="210 US Highway, HighlandLake, FL" bathroom="2 Bathrooms" size="6x7.5 m²"/>

    
  </div>

  <div>
    <footer1 />
  </div>


</template>
<script>
import card from "./components/card.vue"
import { FilmIcon, MenuIcon, DownloadIcon  } from "@heroicons/vue/solid";
import { initCustomFormatter } from '@vue/runtime-core';
import header1 from './components/header.vue';
import footer1 from './components/footer.vue';
export default {
  name: "App",
  components:  { card, header1, footer1}
};
</script>