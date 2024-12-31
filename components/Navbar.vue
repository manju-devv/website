<template>
  <div>
    <header class="navbar">
      <div class="container">
        <nav class="align">
          <div class="svg">
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
            <h1 class="name">Landmark <span class="dot"></span></h1>
          </div>
          <div class="links">
            <ul class="nav-links">
              <li><a href="#Home" class="nav-link">Home</a></li>
              <li><a href="#Features" class="nav-link">Features</a></li>
              <li><a href="#Pricing" class="nav-link">Pricing</a></li>
              <li><a href="#Testimonials" class="nav-link">Testimonials</a></li>
            </ul>
          </div>
          <div class="links">
            <ul class="nav-links2">
              <li><a href="#" class="login">Login</a></li>
              <li><a href="#" class="start">Get Started</a></li>
            </ul>
            <div class="square-pos">
              <div class="square1"></div>
              <div class="square2"></div>
            </div>
          </div>
        </nav>
      </div>
    </header>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped>
.navbar {
  padding: 3rem 0;
}
.svg {
  position: absolute;
  left: 12%;
  display: flex;
  align-items: center;
  gap: 10px;
  margin-left: 5px;
}
.svg svg {
  height: 25px;
  fill: #3b7cc1;
}
.dot {
  display: inline-block;
  width: 5px;
  height: 5px;
  border-radius: 50%;
  background-color: rgb(246, 121, 121);
  margin-left: -5px;
}
.name {
  font-weight: 900;
  font-size: 1.25rem;
}

.align {
  display: flex;
  flex-direction: row;
  gap: 30px;
  align-items: center;
  justify-content: space-around;
}

.nav-links,
.nav-links2 {
  list-style: none;
  display: flex;
  gap: 30px;
  margin: 0;
  padding: 0;
}

.links {
  margin-top: -15px;
}
.nav-links {
  position: absolute;
  left: 38%;
}
.nav-links2 {
  position: absolute;
  display: flex;
  gap: 20px;
  right: 14%;
}

.nav-link,
.login,
.start {
  text-decoration: none;
  color: black;
  font-weight: 700;
  transition: 0.2s;
}

.nav-link:hover {
  color: #497bb1;
}

.start {
  background-color: white;
  color: #616ee7;
  padding: 10px 15px;
  border-radius: 5px;
  margin-left: 20px;
}
.start:hover {
  box-shadow: 2px 2px 5px skyblue;
}

.login {
  color: white;
}

.square-pos {
  position: relative;
}

.square1 {
  position: absolute;
  width: 500px;
  height: 600px;
  top: -160px;
  right: -550px;
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
  top: -250px;
  right: -500px;
  z-index: -100;
  background-color: #f13aa4;
  transform: rotate(45deg);
  border-radius: 40px;
}

@media (max-width: 1150px) {
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
    padding: 10px 15px;
    border-radius: 5px;
    margin-left: 20px;
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
@media (max-width: 1100px) {
  .nav-links {
    left: 30%;
    gap: 20px;
    font-size: 15px;
  }
}
</style>
