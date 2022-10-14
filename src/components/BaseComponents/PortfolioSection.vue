<template>
  <div id="Portfolio" class="portfolio-section flex justify-center items-center">
    <section class="text-gray-600 body-font mx-auto max-w-[80%]">
      <div
        class="container mx-auto flex py-24 md:flex-row flex-col items-center"
      >
        <div
          class="
            lg:flex-grow
            md:w-1/2
            lg:pr-16
            md:pr-8
            xl:pr-42
            2xl:pr-42
            flex flex-col
            md:items-start md:text-left
            mb-16
            md:mb-0
            items-center
            text-center
          "
        >
          <p
            class="
              mb-4
              font-[600]
              text-neutral-100 text-[3.6rem]
              font-['Kanit-Semibold']
            "
          >
            Lorem Ipsum,
          </p>
          <h1
            class="
              font-[600]
              leading-[7.5rem]
              text-neutral-100 text-[6.4rem]
              font-['Kanit-bold']
            "
          >
            Website Design <br />
            & Build
          </h1>
          <p
            class="
              text-neutral-100 text-[2rem]
              font-['Kanit-Medium']
              leading-[3rem]
              mt-10
            "
          >
            Lorem ipsum dolor sit amet, consectetur adipiscing elit Aenean et
            ultrices ipsum. Sed bibendum metus sapien, nec porttitor metus
            commodo eu. Mauris mollis dolor at sem aliquet placerat.
            Pellentesque velit.
          </p>
        </div>
        <div class="md:w-1/2 w-5/6">
          <img
            class="object-cover object-center rounded w-full"
            alt="hero"
            src="@/assets/images/Project1.png"
          />
        </div>
      </div>
      <div class="flex justify-center items-center mt-24">
        <a
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
            mx-5
            cursor-pointer
          "
          ><img src="@/assets/icons/arrowleft.svg" alt=""></a
        >
        <a
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
            mx-5
            cursor-pointer
          "
          ><img src="@/assets/icons/arrowleft.svg" alt="" class="rotate-180"></a
        >
      </div>
    </section>
  </div>
</template>

<style scoped>
.portfolio-section {
  background-image: url("@/assets/images/portfoliobackground.svg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position-y: bottom;
  height: 115rem;
  background-position-x: left;
}
</style>