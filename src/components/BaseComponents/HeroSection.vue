<template>
  <div id="Home" class="relative overflow-hidden hero-section-main">
    <div class="mx-auto max-w-[80%]">
      <TheNavbar></TheNavbar>
    </div>
    <div class="mx-auto max-w-[80%]">
      <main class="mt-56 px-4 sm:px-6 lg:px-8">
        <div class="lg:text-left sm:text-center md:text-left">
          <h1
            class="
              font-[600]
              leading-[7rem]
              text-neutral-100 text-[6.4rem]
              font-['Kanit-bold']
            "
          >
            Taking your business <br />
            to the web
          </h1>
          <p
            class="
              mt-8
              sm:mx-auto
              md:mx-0
              sm:max-w-[50rem]
              lg:mx-0
              text-[2rem]
              leading-[2.6rem]
              text-neutral-100
              font-[600] font-['Kanit-SemiBold']
            "
          >
            We Plan, Design & Develop Websites from start to finish, ensuring a
            high ROI for clients, Our Major concern is the Reliability of
            Website.
          </p>
          <div
            class="mt-20 flex justify-center md:justify-start lg:justify-start"
          >
            <div class="rounded-md shadow w-fit">
              <a
                href="#"
                class="
                  flex
                  w-100
                  items-center
                  justify-center
                  rounded-md
                  border border-transparent
                  bg-indigo-600
                  px-6
                  py-[0.6rem]
                  font-medium
                  text-[2rem] text-neutral-100
                  bg-[#00407C]
                  hover:bg-[#00407cc2]
                  cursor-pointer
                "
                >Let’s get to work</a
              >
            </div>
          </div>
        </div>
      </main>
    </div>
  </div>
</template>



<style scoped>
.hero-section-main {
  background-image: url("@/assets/images/Hero-background.png");
  background-size: cover;
  background-repeat: no-repeat;
  background-position-y: bottom;
  height: 80rem;
  background-position-x: left;
}
</style>

<script>
import TheNavbar from "./TheNavbar.vue"
export default {
  components: {
    TheNavbar,
  },
  
};
</script>