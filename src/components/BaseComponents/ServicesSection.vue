<template>
  <section id="Services" class="mx-auto max-w-[80%] my-32 py-32">
    <h1 class="font-[800] leading-[4.5rem] text-[#222222] text-[4.6rem] pb-10 font-['Kanit-bold']">
      We advise organizations in value creation strategies
    </h1>
    <p class="leading-[3.5rem] text-[#444444] text-[2.8rem] font-['Kanit-Medium']">
      Devroute is a software development company that specializes <br />
      in web and mobile app design, development, integration, <br />
      and customization.
    </p>
    <div class="grid sm:grid-cols-2 md:grid-cols-2 lg:grid-cols-4 gap-12 mt-64 ">
      <ServicesCard></ServicesCard>
    </div>
  </section>
</template>
<script>
import ServicesCard from "./ServicesCard.vue";

export default {
  components: {
    ServicesCard,
  },
};
</script>
