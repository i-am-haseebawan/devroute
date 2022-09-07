<template>
  <section id="Contact" class="mt-32 pt-32">
    <h1
      class="
        font-[800]
        leading-[4.5rem]
        text-[#222222] text-[4.6rem]
        pb-10
        font-['Kanit-bold']
      "
    >
      Get a free quote !
    </h1>
    <p
      class="
        leading-[3.5rem]
        text-[#444444] text-[2.8rem]
        font-['Kanit-Medium']
      "
    >
      Reach out to us and we get back to you shortly !
    </p>
    <div class="contact-background flex justify-center items-flex-start">
      <div
        class="
          block
          p-12
          rounded-[2rem]
          bg-white
          w-[37.7rem]
          shadow-[0_14px_30px_rgba(0,0,0,0.25)]
          h-fit
          mt-52
        "
      >
        <form>
          <div class="form-group mb-8">
            <input
              type="text"
              class="
                form-control
                block
                w-full
                px-4
                py-1.5
                bg-white bg-clip-padding
                rounded-[0.6rem]
                transition
                ease-in-out
                m-0
                focus:text-gray-700
                focus:bg-white
                focus:border-blue-600
                focus:outline-none
                text-[#222222] text-[2rem]
                font-['Kanit-Semibold']
                leading-[2rem]
                shadow-[0_14px_30px_rgba(0,0,0,0.25)]
                italic
              "
              id="exampleInput90"
              placeholder="Your Name"
            />
          </div>
          <div class="form-group mb-8">
            <input
              type="text"
              class="
                form-control
                block
                w-full
                px-4
                py-1.5
                bg-white bg-clip-padding
                shadow-[0_14px_30px_rgba(0,0,0,0.25)]
                rounded-[0.6rem]
                transition
                ease-in-out
                m-0
                focus:text-gray-700
                focus:bg-white
                focus:border-blue-600
                focus:outline-none
                text-[#222222] text-[2rem]
                font-['Kanit-Semibold']
                leading-[2rem]
                italic
              "
              id="exampleInput90"
              placeholder="Email Address"
            />
          </div>
          <textarea
            class="
              resize-none
              rounded-[0.6rem]
              block
              w-full
              px-4
              h-[20rem]
              py-4
              bg-white bg-clip-padding
              shadow-[0_14px_30px_rgba(0,0,0,0.25)]
              transition
              ease-in-out
              m-0
              focus:text-gray-700
              focus:bg-white
              focus:border-blue-600
              focus:outline-none
              text-[#222222] text-[2rem]
              font-['Kanit-Semibold']
              leading-[2rem]
              italic
            "
            placeholder="Your Message"
          ></textarea>

          <button
            type="submit"
            class="
              w-[15rem]
              px-6
              rounded-[0.6rem]
              py-2.5
              bg-[#288DDD]
              text-white text-[2rem]
              font-['Kanit-Semibold']
              rounded
              shadow-md
              hover:bg-[#096dbd] hover:shadow-lg
              focus:bg-[#096dbd] focus:shadow-lg focus:outline-none focus:ring-0
              active:bg-[#096dbd] active:shadow-lg
              transition
              duration-150
              ease-in-out
              mt-10
            "
          >
            Submit
          </button>
        </form>
      </div>
    </div>
  </section>
</template>
<style scoped>
.contact-background {
  background-image: url("@/assets/images/ContactBackground.svg");
  background-size: cover;
  background-repeat: no-repeat;
  height: 108rem;
  background-position: center;
  width: 100%;
}
</style>