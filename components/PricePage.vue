<template>
  <div>
    <section
      id="Pricing"
      class="border-b border-[#f2f5f9] mb-[3.7rem] pb-[10.6rem] mt-[3.7rem]"
    >
      <div class="Price-details flex flex-col items-center justify-center">
        <p class="text-[#667eea]">OUR PRICING</p>
        <h3 class="text-[3rem] font-extrabold max-w-[500px] mx-auto">
          Simple, Transparent Pricing for Everyone
        </h3>
      </div>
      <div
        class="price-cards flex flex-row items-center justify-center pt-[1.8rem]"
      >
        <div
          class="price-card1 border border-[#f2f5f9] shadow-[2px_2px_5px_#f2f5f9]"
        >
          <h4 class="text-center mt-[1.5rem] font-thin">
            <span class="plan-details font-bold">BASIC</span> PLAN
          </h4>
          <p class="dollar flex items-center justify-center my-[1rem]">
            $<span
              class="plan-price text-[2rem] font-bold ml-[0.3rem] items-center justify-center"
              >48</span
            >
          </p>
          <p
            class="price-description text-start max-w-[300px] text-[0.9rem] mb-[2rem] font-normal text-[#718096]"
          >
            In our basic plan you can take advantage of all these features
            below.
          </p>
          <div class="svg-tick flex items-center justify-start mt-2 gap-[15px]">
            <svg
              id="tick-icon"
              class="w-6 h-6 align-middle"
              viewBox="0 0 24 24"
              fill="none"
              stroke="#48BB78"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path>
              <polyline points="22 4 12 14.01 9 11.01"></polyline>
            </svg>
            <p class="text-[#4A5568] text-lg">Awesome Feature</p>
          </div>
          <div class="svg-tick flex items-center justify-start mt-2 gap-[15px]">
            <svg
              id="tick-icon"
              class="w-6 h-6 align-middle"
              viewBox="0 0 24 24"
              fill="none"
              stroke="#48BB78"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path>
              <polyline points="22 4 12 14.01 9 11.01"></polyline>
            </svg>
            <p class="text-[#4A5568] text-lg">And Another Cool Feature</p>
          </div>
          <div class="svg-tick flex items-center justify-start mt-2 gap-[15px]">
            <svg
              id="tick-icon"
              class="w-6 h-6 align-middle"
              viewBox="0 0 24 24"
              fill="none"
              stroke="#48BB78"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path>
              <polyline points="22 4 12 14.01 9 11.01"></polyline>
            </svg>
            <p class="text-[#4A5568] text-lg">One More Feature</p>
          </div>
          <div
            class="plan-container flex items-center justify-center mt-[2.5rem]"
          >
            <a
              class="select-plan no-underline bg-[rgb(42,42,42)] text-white py-[0.9rem] px-[2.5rem] rounded-[5px] w-[90%] text-center font-semibold"
              href="#"
              >SELECT THIS PLAN</a
            >
          </div>
        </div>
        <div class="price-card2 shadow-[4px_4px_8px_#a1a8b1] pt-0">
          <div
            class="popular-plan w-[116.5%] flex items-center justify-center p-[0.9rem] text-white bg-[#667eea] -ml-[25px] rounded-t-[5px] mt-[-1rem]"
          >
            MOST POPULAR
          </div>
          <h4 class="text-center mt-[1.5rem] font-thin">
            <span class="plan-details font-bold">PRO</span> PLAN
          </h4>
          <p class="dollar flex items-center justify-center my-[1rem]">
            $<span
              class="plan-price text-[2rem] font-bold ml-[0.3rem] items-center justify-center"
              >98</span
            >
          </p>
          <p
            class="price-description text-start max-w-[300px] text-[0.9rem] mb-[2rem] font-normal text-[#718096]"
          >
            Our most popular package is the Pro Plan which gives you access to
            the following:
          </p>
          <div class="svg-tick flex items-center justify-start mt-2 gap-[15px]">
            <svg
              id="tick-icon"
              class="w-6 h-6 align-middle"
              viewBox="0 0 24 24"
              fill="none"
              stroke="#48BB78"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path>
              <polyline points="22 4 12 14.01 9 11.01"></polyline>
            </svg>
            <p class="text-[#4A5568] text-lg">Really Cool Features</p>
          </div>
          <div class="svg-tick flex items-center justify-start mt-2 gap-[15px]">
            <svg
              id="tick-icon"
              class="w-6 h-6 align-middle"
              viewBox="0 0 24 24"
              fill="none"
              stroke="#48BB78"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path>
              <polyline points="22 4 12 14.01 9 11.01"></polyline>
            </svg>
            <p class="text-[#4A5568] text-lg">Another Cool Feature</p>
          </div>
          <div class="svg-tick flex items-center justify-start mt-2 gap-[15px]">
            <svg
              id="tick-icon"
              class="w-6 h-6 align-middle"
              viewBox="0 0 24 24"
              fill="none"
              stroke="#48BB78"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path>
              <polyline points="22 4 12 14.01 9 11.01"></polyline>
            </svg>
            <p class="text-[#4A5568] text-lg">And One More</p>
          </div>
          <div
            class="plan-container flex items-center justify-center mt-[2.5rem]"
          >
            <a
              id="user-selected"
              class="select-plan no-underline bg-[rgb(42,42,42)] text-white py-[0.9rem] px-[2.5rem] rounded-[5px] w-[90%] text-center font-semibold"
              href="#"
              >SELECT THIS PLAN</a
            >
          </div>
        </div>
        <div class="price-card3">
          <h4 class="text-center mt-[1.5rem] font-thin">
            <span class="plan-details font-bold">Premium</span> PLAN
          </h4>
          <p class="dollar flex items-center justify-center my-[1rem]">
            $<span
              class="plan-price text-[2rem] font-bold ml-[0.3rem] items-center justify-center"
              >78</span
            >
          </p>
          <p
            class="price-description text-start max-w-[300px] text-[0.9rem] mb-[2rem] font-normal text-[#718096]"
          >
            With our premium plan you can take advantage of all the following
            features:
          </p>
          <div class="svg-tick flex items-center justify-start mt-2 gap-[15px]">
            <svg
              id="tick-icon"
              class="w-6 h-6 align-middle"
              viewBox="0 0 24 24"
              fill="none"
              stroke="#48BB78"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path>
              <polyline points="22 4 12 14.01 9 11.01"></polyline>
            </svg>
            <p class="text-[#4A5568] text-lg">Totally Tubular Feature</p>
          </div>
          <div class="svg-tick flex items-center justify-start mt-2 gap-[15px]">
            <svg
              id="tick-icon"
              class="w-6 h-6 align-middle"
              viewBox="0 0 24 24"
              fill="none"
              stroke="#48BB78"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path>
              <polyline points="22 4 12 14.01 9 11.01"></polyline>
            </svg>
            <p class="text-[#4A5568] text-lg">Super Cool Feature</p>
          </div>
          <div class="svg-tick flex items-center justify-start mt-2 gap-[15px]">
            <svg
              id="tick-icon"
              class="w-6 h-6 align-middle"
              viewBox="0 0 24 24"
              fill="none"
              stroke="#48BB78"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path>
              <polyline points="22 4 12 14.01 9 11.01"></polyline>
            </svg>
            <p class="text-[#4A5568] text-lg">One More Feature</p>
          </div>
          <div
            class="plan-container flex items-center justify-center mt-[2.5rem]"
          >
            <a
              class="select-plan no-underline bg-[rgb(42,42,42)] text-white py-[0.9rem] px-[2.5rem] rounded-[5px] w-[90%] text-center font-semibold"
              href="#"
              >SELECT THIS PLAN</a
            >
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
#tick-icon {
  width: 1.2rem;
}

.price-card1,
.price-card2,
.price-card3 {
  padding: 0.9rem 1.5rem 1.5rem 1.5rem;
  border-radius: 5px;
}

.plan-container a:hover {
  background-color: #38a169;
}
div #user-selected:hover {
  background-color: #5a67d8;
}

.price-card3 {
  border: 1px solid #f2f5f9;
  box-shadow: 2px 2px 5px #f2f5f9;
}

.tick-icon {
  color: green;
}

@media screen and (max-width: 900px) {
  .price-cards {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding-top: 1.8rem;
  }
  .price-card2,
  .price-card3 {
    margin-top: 2.5rem;
  }
  .Price-details h3 {
    font-size: 2rem;
    text-align: center;
  }
  #Pricing {
    padding-bottom: 5rem;
    margin-top: 0.6rem;
  }
}

@media screen and (max-width: 500px) {
  .Price-details h3 {
    width: 90%;
  }
}

@media screen and (max-width: 300px) {
  .Price-details h3 {
    width: 80%;
    font-size: 1.3rem;
  }
  .price-cards {
    padding: 0.8rem;
  }
  div.plan-container {
    margin-top: 0.5rem;
  }
}
</style>
