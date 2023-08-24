<template>
  <div class="about-container">
    <div class="about-title">
      <h2>About me</h2>
    </div>
    <div class="div">
      <div class="about-img">
        <img src="../assets/img/pic.jpg" alt="about-img" />
      </div>
      <div class="about-desc">
        <p>
          I am deeply committed to the art
          of problem-solving, and my proficiency in Python and Django allows me
          to construct powerful backends that ensure optimal performance and
          scalability for all my applications. Currently pursuing studies at
          ENSSEA , I am always seeking opportunities to expand my horizons and
          embrace the latest trends and technologies in the world of web
          development. Thank
          you for taking the time to explore my portfolio.Let's collaborate and
          build a brighter, tech-driven future!
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.about-container {
  padding: 50px 100px;
  width: 100%;
  display: flex;
  justify-content: center;
  align-content: center;
  flex-direction: column;
}
.about-container > div {
  display: flex;
  align-items: center;
  justify-content: center;
}

.about-title {
  width: 100%;
  text-align: center;
}

.about-title h2 {
  font-size: 38px;
  margin: 0 5px;
}

h2 {
  font-size: 38px;
  margin: 20px 0;
}
/*about desc */
.about-desc {
  text-align: start;
  padding: 15px;
}

.about-desc p {
  color: #333;
  letter-spacing: 0.5px;
}

/*about img */
.about-img {
  text-align: center;

  width: 300px;
  height: 300px;
  padding: 0 10px;
}
img {
  width: 300px;
  height: 300px;
  object-fit: cover;
  object-position: center;
  border-radius: 6px;
}

@media screen and (max-width: 1000px) {
  .about-container .div {
    flex-direction: column;
  }
  .about-desc {
    text-align: center;
    padding: 5px 100px;
  }
  .about-desc p {
    margin: 10px 0;
  }
}
@media screen and (max-width: 640px) {
  .about-title h2 {
    font-size: 30px;
  }
}
@media screen and (max-width: 520px) {
  .about-container .div {
    flex-direction: column;
  }
  .about-desc {
    text-align: center;
    padding: 5px 15px;
  }
  .about-desc p {
    margin: 10px 0;
  }
  .about-title {
    width: 100%;
    text-align: center;
  }
  .about-title h2 {
    font-size: 25px;
  }
  hr {
    width: 50%;
  }
}
</style>