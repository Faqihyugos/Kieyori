<template>
 <div class="HomeView">
   <HeaderKieyori />
   <HeroKieyori />
   <ProductKieyori />
   <InstaKieyori />
   <PartnerKieyori />
   <FooterKieyori />
 </div>
</template>

<script>

import HeaderKieyori from "@/components/HeaderKieyori.vue";
import HeroKieyori from "@/components/HeroKieyori.vue";
import ProductKieyori from "@/components/ProductKieyori.vue";
import InstaKieyori from "@/components/InstaKieyori.vue";
import PartnerKieyori from "@/components/PartnerKieyori.vue";
import FooterKieyori from "@/components/FooterKieyori.vue";


export default {
  name: "HomeView",
  components: {
    HeaderKieyori,
    HeroKieyori,
    ProductKieyori,
    InstaKieyori,
    PartnerKieyori,
    FooterKieyori
  }
}
</script>