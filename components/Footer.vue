<template>
  <div>
    <section id="footer">
      <div class="end">
        <div class="end1">
          <div>
            <div class="svg-end">
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
            </div>
          </div>
          <div class="end-p">
            <p>Crafting the next-level of user experience and engagement.</p>
          </div>
        </div>
        <div class="part2">
          <div class="end2">
            <div><h5>PRODUCT</h5></div>
            <div>
              <ul class="first-ul">
                <li>Features</li>
                <li>Integrations</li>
                <li>Pricing</li>
                <li>FAQ</li>
              </ul>
            </div>
          </div>
          <div class="end3">
            <div><h5>PRIVACY</h5></div>
            <div>
              <ul class="first-ul second">
                <li>Privacy</li>
                <li>Terms of Service</li>
              </ul>
            </div>
          </div>
          <div class="end4">
            <div><h5>TailwindCSS</h5></div>
            <div class="a-links">
              <a href="https://devdojo.com/tailwindcss/components"
                >Tailwind Components</a
              >
              <a href="https://devdojo.com/tailwindcss/templates"
                >Tailwind Templates</a
              >
              <a href="https://devdojo.com/tails">Tails</a>
            </div>
          </div>
          <div class="end5">
            <div>FOLLOW US</div>
            <div class="social-iicons">
              <svg
                id="ic"
                viewBox="0 0 24 24"
                class="w-5 h-5 fill-current"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M23.998 12c0-6.628-5.372-12-11.999-12C5.372 0 0 5.372 0 12c0 5.988 4.388 10.952 10.124 11.852v-8.384H7.078v-3.469h3.046V9.356c0-3.008 1.792-4.669 4.532-4.669 1.313 0 2.686.234 2.686.234v2.953H15.83c-1.49 0-1.955.925-1.955 1.874V12h3.328l-.532 3.469h-2.796v8.384c5.736-.9 10.124-5.864 10.124-11.853z"
                ></path>
              </svg>
              <svg
                id="ic"
                viewBox="0 0 24 24"
                class="w-5 h-5 fill-current"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M23.954 4.569a10 10 0 01-2.825.775 4.958 4.958 0 002.163-2.723c-.951.555-2.005.959-3.127 1.184a4.92 4.92 0 00-8.384 4.482C7.691 8.094 4.066 6.13 1.64 3.161a4.822 4.822 0 00-.666 2.475c0 1.71.87 3.213 2.188 4.096a4.904 4.904 0 01-2.228-.616v.061a4.923 4.923 0 003.946 4.827 4.996 4.996 0 01-2.212.085 4.937 4.937 0 004.604 3.417 9.868 9.868 0 01-6.102 2.105c-.39 0-.779-.023-1.17-.067a13.995 13.995 0 007.557 2.209c9.054 0 13.999-7.496 13.999-13.986 0-.209 0-.42-.015-.63a9.936 9.936 0 002.46-2.548l-.047-.02z"
                ></path>
              </svg>
              <svg
                id="ic"
                viewBox="0 0 24 24"
                class="w-5 h-5 fill-current"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"
                ></path>
              </svg>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped>
.svg-end > svg {
  height: 25px;
}

#footer {
  margin-top: 70px;
}
.end {
  display: flex;
}
.end1 {
  display: flex;
  flex-direction: column;
  margin-left: 80px;
}
.end1 .end-p {
  max-width: 250px;
  margin-left: -20px;
  color: grey;
}
.part2 {
  display: flex;
  gap: 60px;
  margin-left: 40px;
}
li {
  list-style-type: none;
  color: grey;
  margin-top: 10px;
}

.end2,
.end3 {
  display: flex;
  flex-direction: column;
}
ul.first-ul {
  margin-top: -10px;
  margin-left: -35px;
}
ul.second {
  margin-left: -30px;
}
.end4 {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-left: -50px;
}
.end4 .a-links {
  display: flex;
  flex-direction: column;
}
.a-links a {
  margin-left: 75px;
  margin-top: 5px;
  text-decoration: none;
  color: grey;
}

#ic {
  width: 20px;
}

.end5 {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 20px;
  font-weight: 700;
}
.social-iicons #ic {
  gap: 30px;
}
</style>
