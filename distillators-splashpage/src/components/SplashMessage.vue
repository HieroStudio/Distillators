<script setup>

</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <a class="input" href='mailto:benjamintbailey@icloud.com'>Email us
      <svg class="link-icon" version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 36.1 25.8" enable-background="new 0 0 36.1 25.8" xml:space="preserve"><g><polyline stroke-width="3" stroke-miterlimit="10" points="22.2,1.1 34,12.9 22.2,24.7   "></polyline></g></svg>
    </a>
    <h3 class="red-brown link">
      <a class="link" href="http://benjamintbailey.com/" target="_blank" rel="noopener">BENJAMIN T BAILEY PORTFOLIO
        <svg  class="icon" version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 36.1 25.8" enable-background="new 0 0 36.1 25.8" xml:space="preserve"><g><polyline stroke-width="3" stroke-miterlimit="10" points="22.2,1.1 34,12.9 22.2,24.7   "></polyline></g></svg>
      </a>
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
  font-weight: 500;
}

.greetings h1,
.greetings h3 {
  text-align: center;
  margin-top: 5rem;
}

.input {
  display: flex;
  align-items: center;
  margin: auto;
  width: 550px;
  max-width: 100%;
  height: 50px;
  margin-top: 2rem;
  color: #660025;
  font-family: inherit;
  padding: 0.35rem 0.5rem;
  background-color:#fFF0D7;
  border: 3px solid #660025;
  border-radius: 4px;
}

.link-icon {
  margin-left: 400px;
  width: 30px;
  height: 30px;
  fill: #660025;
  stroke: #660025;
}

.icon {
  width: 20px;
  height: 20px;
  fill: #660025;
  stroke: #660025;
}

.link {
  display: flex;
  justify-items: center;
  align-items: center;
  margin: auto;
  margin-top: 90px;
}

</style>
