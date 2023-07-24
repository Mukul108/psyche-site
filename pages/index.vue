<template>
  <div class="container">
    <div class="background-image"></div>
    <div class="glass-container">
      <link href="https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap" rel="stylesheet">
      <!-- Existing content -->
      <h3 class="subtitle0">TEAM</h3>
      <h1 class="title">Psyche</h1>
      <h2 class="subtitle">HUNGER OF BUILDING TECH</h2>
      <div class="social-buttons">
        <!-- Existing social buttons -->
      </div>
    </div>
    <div class="glassy-buttons">
      <div class="glassy-button">Story</div>
      <div class="glassy-button">Projects</div>
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
  background-color: rgba(255, 255, 255, 0.425);
  backdrop-filter: blur(5px);
  border-radius: 120px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
  margin: 20px; /* Instead of using margin-left and margin-right separately, use a single margin value */
}

.title {
  font-family: 'Dancing Script', cursive;
  font-size: 14.5rem;
  font-weight: bold;
  margin-bottom: 1rem;
}

.subtitle {
  font-size: 1.5rem;
  margin-bottom: 2rem;
}

.subtitle0 {
  font-size: 1rem;
  margin-top: 1rem;
}

.social-buttons {
  display: flex;
  justify-content: center; /* Center the social buttons horizontally */
}

.button {
  width: 100px;
  padding: 20px;
}

.button:last-child {
  margin-right: 0;
}

.glassy-buttons {
  display: flex;
  justify-content: center; /* Center the glassy buttons horizontally */
  margin: 20px auto; /* Use auto margin to center the buttons vertically */
  max-width: 500px;
  padding: 20px;
}

.glassy-button {
  display: flex;
  justify-content: center;
  align-items: center;
  flex: 1;
  background-color: rgba(255, 255, 255, 0.425);
  backdrop-filter: blur(5px);
  border-radius: 30px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
  font-size: 1.2rem;
  font-weight: bold;
  padding: 10px;
  margin: 10px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.glassy-button:hover {
  background-color: rgba(255, 255, 255, 0.6);
}

/* Media queries for responsiveness */

/* For screens smaller than 768px (e.g., smartphones) */
@media screen and (max-width: 767px) {
  .glass-container {
    margin: 10px;
  }

  .title {
    font-size: 6rem;
  }
}

/* For screens between 768px and 1023px (e.g., tablets) */
@media screen and (min-width: 768px) and (max-width: 1023px) {
  .glass-container {
    margin: 15px;
  }

  .title {
    font-size: 10rem;
  }
}

/* For screens larger than 1023px (e.g., desktops) */
@media screen and (min-width: 1024px) {
  .glass-container {
    margin: 30px;
  }

  .title {
    font-size: 14.5rem;
  }
}

</style>
