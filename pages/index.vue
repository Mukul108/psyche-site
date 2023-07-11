<template>
  <div class="container">
    <div class="background-image"></div>
    <div class="glass-container">
      <link href="https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap" rel="stylesheet">

      <h1 class="title">Psyche</h1>
      <h2 class="subtitle">HUNGER OF BUILDING TECH</h2>
      <div class="social-buttons">
        <a href="#" class="button">Facebook</a>
        <a href="#" class="button">Twitter</a>
        <a href="#" class="button">Instagram</a>
        <a href="#" class="button">LinkedIn</a>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  overflow-x: hidden;
  position: relative;
  min-height: 100vh;
}

.background-image {
  position: fixed;
  top: 0;
  left: 0;
  width: 100vw;
  height: 100vh;
  width: 100%;
  height: 100%;
  background-image: url('../public/bg/psyche6.jpg');
  background-size: cover;
  background-position: center;
  z-index: -1;
}

.glass-container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 2rem;
  background-color: rgba(255, 255, 255, 0.5);
  backdrop-filter: blur(10px);
  border-radius: 120px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
  margin-left: 90px;
  margin-right: 70px;
}

.title {
  font-family: 'Dancing Script', cursive;
  font-size: 15rem;
  font-weight: bold;
  margin-bottom: 1rem;
}

.subtitle {
  font-size: 1.5rem;
  margin-bottom: 2rem;
}

.social-buttons {
  display: flex;
}

.button {
  margin-right: 0.5rem;
  padding: 0.5rem 1rem;
  background-color: #3182ce;
  color: white;
  text-decoration: none;
  border-radius: 4px;
}

.button:last-child {
  margin-right: 0;
}
</style>