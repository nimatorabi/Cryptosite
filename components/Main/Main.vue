<template>
  <div>
    <div class="container mx-auto">
      <EarningWrapper></EarningWrapper>
      <AboutCrypto></AboutCrypto>
    </div>
    <pricingCharts></pricingCharts>
    <MultipleIncome></MultipleIncome>
    <ServiceSection></ServiceSection>
    <Team></Team>
    <News></News>
    <FAQ></FAQ>
  </div>
</template>

<script>
import EarningWrapper from "./EarningWrapper/EarningWrapper";

import AboutCrypto from "./AboutCrypto/AboutCrypto";
import pricingCharts from "./pricingCharts/pricingCharts";
import MultipleIncome from "./MultipleIncome/MultipleIncome";
import ServiceSection from "./ServiceSection/ServiceSection";
import Team from "./Team/Team";
import News from "./News/News";
import FAQ from "./FAQ/FAQ";
export default {
  components: {
    EarningWrapper,
    AboutCrypto,
    pricingCharts,
    MultipleIncome,
    ServiceSection,
    Team,
    News,
    FAQ
  }
};
</script>

<style></style>
