<template>
  <div>
    <header class="navbar py-12">
      <div class="container">
        <nav
          class="align flex flex-row gap-[1.8rem] items-center justify-around"
        >
          <div
            class="svg absolute left-[12%] flex items-center gap-[0.6rem] ml-[0.3rem]"
          >
            <svg
              class="w-auto h-6 text-indigo-600 fill-current"
              viewBox="0 0 194 116"
              xmlns="http://www.w3.org/2000/svg"
            >
              <g fill-rule="evenodd">
                <path
                  d="M96.869 0L30 116h104l-9.88-17.134H59.64l47.109-81.736zM0 116h19.831L77 17.135 67.088 0z"
                ></path>
                <path
                  d="M87 68.732l9.926 17.143 29.893-51.59L174.15 116H194L126.817 0z"
                ></path>
              </g>
            </svg>
            <h1 class="name font-black text-xl">
              Landmark
              <span
                class="dot inline-block w-[5px] h-[5px] rounded-full bg-red-400 -ml-[0.3rem]"
              ></span>
            </h1>
          </div>
          <div class="links mt-[-0.9rem]">
            <div class="setup-icons flex gap-[1rem]">
              <span
                class="menu-icon absolute text-[2rem] cursor-pointer top-[0.4%] right-[3%]"
                @click="toggleNavbar"
                v-if="windowWidth <= 1100"
                >{{ hidden ? "&#9776;" : "&#10005;" }}</span
              >
            </div>
            <ul
              :class="[
                'nav-links list-none flex gap-[1.8rem] p-0 m-0 absolute left-[38%]',
                { isVisible: !hidden && windowWidth <= 1100 },
              ]"
            >
              <li>
                <a
                  href="#Home"
                  class="nav-link no-underline text-black font-bold transition-all duration-200 hover:text-[#497bb1]"
                  >Home</a
                >
              </li>
              <li>
                <a
                  href="#Features"
                  class="nav-link no-underline text-black font-bold transition-all duration-200 hover:text-[#497bb1]"
                  >Features</a
                >
              </li>
              <li>
                <a
                  href="#Pricing"
                  class="nav-link no-underline text-black font-bold transition-all duration-200 hover:text-[#497bb1]"
                  >Pricing</a
                >
              </li>
              <li>
                <a
                  href="#Testimonials"
                  class="nav-link no-underline text-black font-bold transition-all duration-200 hover:text-[#497bb1]"
                  >Testimonials</a
                >
              </li>
            </ul>
          </div>
          <div class="links mt-[-0.9rem]">
            <ul
              :class="[
                'nav-links2 list-none flex gap-[1.8rem] p-0 m-0 absolute right-[14%] ',
                {
                  isVisible: !hidden && windowWidth <= 1100,
                  isAlign: !hidden && windowWidth <= 1100,
                },
              ]"
            >
              <li>
                <a
                  href="#"
                  class="login no-underline text-black font-bold transition-all duration-200"
                  >Login</a
                >
              </li>
              <li>
                <a
                  href="#"
                  class="start no-underline text-[#616ee7] py-[0.6rem] px-[0.9rem] rounded-[0.3rem] ml-[1.25rem] font-bold transition-all duration-200 bg-white"
                  >Get Started</a
                >
              </li>
            </ul>
            <div class="square-pos relative">
              <div class="square1"></div>
              <div class="square2"></div>
            </div>
          </div>
        </nav>
      </div>
    </header>
  </div>
</template>

<script setup lang="ts">
import { ref, onMounted, onUnmounted } from "vue";

const hidden = ref<boolean>(true);
const windowWidth = ref<number>(0);

function toggleNavbar(): void {
  hidden.value = !hidden.value;
}

function updateWindow(): void {
  windowWidth.value = window.innerWidth;
}

onMounted(() => {
  window.addEventListener("resize", updateWindow);
});

onUnmounted(() => {
  window.removeEventListener("resize", updateWindow);
});
</script>

<style scoped>
.svg svg {
  height: 25px;
  fill: #3b7cc1;
}

.start:hover {
  box-shadow: 2px 2px 5px skyblue;
}

.square1 {
  position: absolute;
  width: 500px;
  height: 600px;
  top: -10rem;
  right: -32.3rem;
  z-index: -1;
  background-color: #616ee7;
  transform: rotate(-60deg);
  transform-origin: center;
  overflow: hidden;
}

.square2 {
  position: absolute;
  width: 500px;
  height: 500px;
  top: -15.6rem;
  right: -30.25rem;
  z-index: -100;
  background-color: #f13aa4;
  transform: rotate(45deg);
  border-radius: 2.5rem;
}

@media screen and (max-width: 1279px) {
  .square1 {
    right: -39.3rem;
  }
  .square2 {
    right: -37.25rem;
  }
}

@media screen and (max-width: 1150px) {
  .square1,
  .square2 {
    display: none;
  }
  .login {
    color: #f13aa4;
  }
  .start {
    background-color: #616ee7;
    color: white;
    padding: 0.6rem 0.9rem;
    border-radius: 0.3rem;
    margin-left: 1.2rem;
  }
  .svg {
    left: 2%;
  }
  .nav-links {
    left: 35%;
  }
  .nav-links2 {
    right: 2%;
  }
}
@media screen and (max-width: 1024px) {
  .svg {
    left: 0;
  }
  .svg svg {
    height: 4rem;
  }
  .name {
    font-size: 3rem;
  }
  .dot {
    width: 12px;
    height: 12px;
  }
}

@media screen and (max-width: 1100px) {
  ul.nav-links,
  ul.nav-links2 {
    display: none;
    flex-direction: column;
    gap: 0.5rem;
  }
  ul.isVisible {
    display: flex;
    position: absolute;
    border-top: 1px solid #f2f5f9;
    padding-top: 2rem;
    left: 0%;
    width: 100%;
    top: 65px;
    z-index: 1;
    background-color: #ffffff;
    padding-bottom: 0.5rem;
    margin-top: 1rem;
  }
  ul.isVisible li {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  ul.isAlign {
    display: flex;
    gap: 1.3rem;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    position: absolute;
    width: 100%;
    top: 4.2%;
    border-top: 1px solid #f2f5f9;
    padding-top: 1rem;
    padding-bottom: 2.2rem;
    margin-top: 1rem;
    z-index: 1;
    background-color: #ffffff;
  }
  .svg {
    left: 2%;
    margin-top: 0.5rem;
  }
  .svg svg {
    height: 4rem;
  }
  .name {
    font-size: 3rem;
  }
  .dot {
    width: 12px;
    height: 12px;
  }
}

@media screen and (max-width: 900px) {
  .svg {
    left: 4%;
    margin-top: 0.4rem;
  }
  .svg svg {
    height: 2rem;
  }
  .name {
    font-size: 2rem;
  }
  .dot {
    width: 8px;
    height: 8px;
  }
  ul.isVisible {
    padding-bottom: 50px;
  }
  ul.isAlign {
    top: 4.5%;
  }
}
@media screen and (max-width: 800px) {
  ul.isAlign {
    top: 4%;
  }
}

@media screen and (max-width: 700px) {
  .svg {
    left: 30%;
    margin-top: 0.6rem;
  }
  .svg svg {
    height: 2rem;
  }
  .name {
    font-size: 2rem;
  }
  .dot {
    width: 6px;
    height: 6px;
  }
  ul li {
    font-size: 1.2rem;
  }
}

@media screen and (max-width: 500px) {
  .svg {
    left: 27%;
    margin-top: 0.4rem;
  }
  .svg svg {
    height: 1.5rem;
  }
  .name {
    font-size: 1.5rem;
  }
  .dot {
    width: 5px;
    height: 5px;
  }
  ul li {
    font-size: 1rem;
  }
}

@media screen and (max-width: 300px) {
  .svg {
    left: 20%;
    margin-top: 0.4rem;
  }
  .svg svg {
    height: 1.3rem;
  }
  .name {
    font-size: 1.3rem;
  }
  ul li {
    font-size: 0.7rem;
  }
  ul.isAlign {
    top: 3.5%;
    padding-bottom: 1.5rem;
  }
}
</style>
