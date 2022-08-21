<template>
  <TheHero />
  <PreviewWNumbers />
  <VarientDisplay />
  <AQuote />
  <PricingPlan />
  <GetStartedForm />
</template>

<script>
import AQuote from "../components/layout/AQuote.vue";
import GetStartedForm from "../components/layout/GetStartedForm.vue";
import PreviewWNumbers from "../components/layout/PreviewWNumbers.vue";
import PricingPlan from "../components/layout/PricingPlan.vue";
import TheHero from "../components/layout/TheHero.vue";
import VarientDisplay from "../components/layout/VarientDisplay.vue";

export default {
  components: {
    TheHero,
    PreviewWNumbers,
    VarientDisplay,
    AQuote,
    PricingPlan,
    GetStartedForm,
  },
};
</script>
