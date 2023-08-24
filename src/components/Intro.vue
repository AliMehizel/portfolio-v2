<template>
  <div class="intro-container">
    <!---intro-text--->
    <div class="intro-text">
      <div>
        <h1>Ali Mehizel</h1>
        <div class="fd">
          <hr />
          <strong>Fullstack developer</strong>
        </div>
        <p>
          Greetings! I'm a passionate and accomplished <strong>Full-stack Developer</strong> with
          a wealth of experience in Python (Django) and JavaScript (Vue.js and
          Reactjs), Currently pursuing a major in <strong>Statistics and Data Science</strong>
          at <strong>ENSSEA</strong>(High School of Statistics and Applied Economics).
        </p>
      </div>
    </div>
    <!--img-hero-->

    <div class="intro-hero">
      <img src="../assets/img/pic.jpg" alt="" />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
/*intro-container */
.intro-container {
  margin-top: 50px;
  padding: 0px 50px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.intro-container > div {
  flex: 1;
}

/*intro-txt */
.intro-text {
  padding: 30px;
}
.intro-text h1 {
  font-size: 50px;
  color: #253a41;
}
p{
  color: #253a41;
}
.fd {
  display: flex;
  align-items: center;
  padding: 5px;
}

.fd hr {
  width: 100px;
  margin: 5px;
}
/*intro img */

.intro-hero {
  text-align: center;
}
.intro-hero img {
  margin-top: 50px;
  width: 250px;
  height: 250px;
  object-fit: cover;
  object-position: bottom;
  border-radius: 50%;
}

@media screen and (max-width: 850px) {
  .intro-container {
    margin-top: 50px;
    padding: 0px 50px;
    flex-direction: column-reverse;
  }
  .intro-text > div {
    text-align: center;
  }
  .fd hr {
    width: 0px;
    margin: 5px;
  }
}

@media screen and (max-width: 470px) {
  .intro-container {
    padding: 0px 10px;
  }
}
</style>