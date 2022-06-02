<template>
  <HeaderCont />
  <main id="main"></main>
  <FooterCont />
</template>

<script>
import HeaderCont from "@/components/HeaderCont.vue";
import FooterCont from "@/components/FooterCont.vue";

export default {
  components: {
    HeaderCont,
    FooterCont,
  },
};
</script>
