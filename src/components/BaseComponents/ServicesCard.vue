<template>
  <div
    class="
      shadow-[0_4px_30px_rgba(0,0,0,0.1)]
      p-12
      rounded-[2rem]
      border-transparent border-2
      hover:border-[#288ddd]
      ease-in-out
      duration-300
      card
    "
    v-for="(service, index) in services"
    :key="index"
  >
    <div class="flex justify-start items-center h-[5rem]">
      <div
        class="
          flex
          rounded-full
          bg-[#BCDAF2]
          items-center
          justify-center
          w-[3rem]
          h-[3rem]
          mr-4
        "
      >
        <img :src="service.iconImg" alt="" class="w-[2rem]" />
      </div>
      <p
        class="
          text-[2rem]
          leading-[2.4rem]
          text-left text-[#288DDD]
          font-[600] font-['Kanit-Bold']
        "
      >
        {{ service.title }}
      </p>
    </div>
    <h4
      class="
        text-[1.5rem]
        leading-[2.2rem]
        text-left text-[#444444]
        font-[400]
        mt-6
        font-['Kanit-Medium']
      "
    >
      {{ service.description }}
    </h4>
  </div>
</template>



<script>
export default {
  data() {
    return {
      services: [
        {
          iconImg: require("@/assets/icons/appicon.svg"),
          title: "Application Developement",
          description:
            "We provide a variety of high-quality desktop applications to assist you in running your business more effectively and efficiently.",
        },
        {
          iconImg: require("@/assets/icons/cloud.svg"),
          title: "Cloud Computing",
          description:
            "We provide cloud services integration solutions that enable scalable computation for seamless connection with business intelligence, CRM, ERP, and identity management systems.",
        },
        {
          iconImg: require("@/assets/icons/uiux.svg"),
          title: "UI/UX",
          description:
            "We design responsive and attractive websites that meet all of your requirements while staying within your schedule and budget constraints.",
        },
        {
          iconImg: require("@/assets/icons/seo.svg"),
          title: "Seo",
          description:
            "We serve clients who demand a comprehensive, full-service search engine marketing strategy.",
        },
      ],
    };
  },
};
</script>