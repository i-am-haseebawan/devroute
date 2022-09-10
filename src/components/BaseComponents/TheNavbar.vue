<template>
  <div class="relative px-4 pt-10 sm:px-6 lg:px-8">
    <nav
      class="relative flex items-center justify-between sm:h-10"
      aria-label="Global"
    >
      <div class="flex flex-shrink-0 flex-grow items-center lg:flex-grow-0">
        <div class="flex w-full items-center justify-between md:w-auto">
          <a href="#">
            <span class="sr-only">Your Company</span>
            <img
              alt="Your Company"
              class="h-8 w-auto sm:h-10"
              src="@/assets/images/navlogo.svg"
            />
          </a>
          <div class="-mr-2 flex items-center md:hidden">
            <button
              type="button"
              class="
                inline-flex
                items-center
                justify-center
                rounded-md
                bg-white
                p-2
                text-gray-400
                hover:bg-gray-100 hover:text-gray-500
                focus:outline-none
                focus:ring-2
                focus:ring-inset
                focus:ring-indigo-500
              "
              aria-expanded="false"
              @click="openMobNavbar"
            >
              <span class="sr-only">Open main menu</span>
              <!-- Heroicon name: outline/bars-3 -->
              <svg
                class="h-12 w-12"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                aria-hidden="true"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"
                />
              </svg>
            </button>
          </div>
        </div>
      </div>
      <div class="hidden md:ml-10 md:block md:space-x-8 md:pr-4">
        <a
          href="#Home"
          class="
            font-medium
            text-neutral-100
            hover:text-neutral-300
            text-[2rem]
            pr-8
          "
          >Home</a
        >

        <a
          href="#Services"
          class="
            font-medium
            text-neutral-100
            hover:text-neutral-300
            text-[2rem]
            pr-8
          "
          >Services</a
        >

        <a
          href="#Portfolio"
          class="
            font-medium
            text-neutral-100
            hover:text-neutral-300
            text-[2rem]
            pr-8
          "
          >Portfolio</a
        >

        <a
          href="#Technologies"
          class="
            font-medium
            text-neutral-100
            hover:text-neutral-300
            text-[2rem]
            pr-8
          "
          >Technologies</a
        >
        <a
          href="#Contact"
          class="
            font-medium
            text-neutral-100
            hover:text-neutral-300
            text-[2rem]
          "
          >Contact</a
        >
      </div>
    </nav>
    <div
      class="
        absolute
        inset-x-0
        top-2
        z-auto
        origin-top-right
        transform
        p-2
        transition
        md:hidden
      "
    >
      <div
        class="
          overflow-hidden
          rounded-lg
          bg-white
          shadow-md
          ring-1 ring-black ring-opacity-5
          pb-0
        "
        v-if="isVisible"
      >
        <div class="flex items-center justify-between px-5 pt-4">
          <div>
            <img class="h-8 w-auto" src="@/assets/images/navlogo.svg" alt="" />
          </div>
          <div class="-mr-2">
            <button
              type="button"
              class="
                inline-flex
                items-center
                justify-center
                rounded-md
                bg-white
                p-2
                text-gray-400
                hover:bg-gray-100 hover:text-gray-500
                focus:outline-none
                focus:ring-2
                focus:ring-inset
                focus:ring-indigo-500
              "
              @click="closeMobNavbar"
            >
              <span class="sr-only">Close main menu</span>
              <!-- Heroicon name: outline/x-mark -->
              <svg
                class="h-12 w-12"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                aria-hidden="true"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M6 18L18 6M6 6l12 12"
                />
              </svg>
            </button>
          </div>
        </div>
        <div class="space-y-1 pt-2 pb-0">
          <a
            href="#Home"
            class="
              block
              rounded-md
              px-3
              py-2
              font-medium
              text-gray-700
              hover:bg-gray-50 hover:text-gray-900
              text-[2rem]
              font-['Kanit-Medium']
              border-b-2 border-[#288DDD]
            "
            >Home</a
          >

          <a
            href="#Services"
            class="
              block
              rounded-md
              px-3
              py-2
              text-[2rem]
              font-medium
              text-gray-700
              hover:bg-gray-50 hover:text-gray-900
              font-['Kanit-Medium']
              border-b-2 border-[#288DDD]
            "
            >Services</a
          >

          <a
            href="#Portfolio"
            class="
              block
              rounded-md
              px-3
              py-2
              text-[2rem]
              font-medium
              text-gray-700
              hover:bg-gray-50 hover:text-gray-900
              font-['Kanit-Medium']
              border-b-2 border-[#288DDD]
            "
            >Portfolio</a
          >

          <a
            href="#Technologies"
            class="
              block
              rounded-md
              px-3
              py-2
              text-[2rem]
              font-medium
              text-gray-700
              hover:bg-gray-50 hover:text-gray-900
              font-['Kanit-Medium']
              border-b-2 border-[#288DDD]
            "
            >Technologies</a
          >

          <a
            href="#Contact"
            class="
              block
              rounded-md
              px-3
              py-2
              text-[2rem]
              font-medium
              text-gray-700
              hover:bg-gray-50 hover:text-gray-900
              font-['Kanit-Medium']
              border-b-2 border-[#288DDD]
            "
            >Contact</a
          >
        </div>
      </div>
    </div>
  </div>
</template>