<script>
import MenuLateral from "@/components/MenuLateral.vue";
import BlocoFooter from "@/components/BlocoFooter.vue";
import BlocoHeader from "@/components/BlocoHeader.vue";
import BlocoMain from "@/components/BlocoMain.vue";
export default {
  components: { MenuLateral, BlocoFooter, BlocoHeader, BlocoMain },
};
</script>
<template>
  <MenuLateral />
  <BlocoHeader />
  <BlocoMain />
  <BlocoFooter />
</template>
<style></style>
