<template>
  <div class="p-container">
    <div class="p-title">

      <h2>Portfolio</h2>
      <p>What i made</p>
    </div>

    <div class="p-projects">
      <div class="p-card">
        <div class="p-card-img">
          <img src="../assets/img/p3.png" alt="ecommerce" />
        </div>
        <div class="p-card-desc">
          <h3>Vidal ecommerce website</h3>
          <p>
            powerful combination of Django, a robust Python framework, and
            Vue.js with Pinia state management library, With integration of
            Stripe and PayPal payment gateways.
          </p>
        </div>
        <div class="p-card-btn">
          <button><a href="https://www.youtube.com/watch?v=A-t4ZQFvUHc&t=144s" target="_blank" style="color: #253a41;">Visit</a><i class="fa-solid fa-eye"></i></button>
          
        </div>
      </div>

      <div class="p-card">
        <div class="p-card-img">
          <img src="../assets/img/blog.png" alt="learn" />
        </div>
        <div class="p-card-desc">
          <h3>VX7 Blogerr website</h3>
          <p>
            built with Django & and DRF with Nuxt 3 on the
            frontend with Pinia state management library, include many
            functionality like user auth (dj-rest-auth) and more.
          </p>
        </div>
        <div class="p-card-btn">
          <button><a href="https://www.youtube.com/watch?v=WqTUAnJxCEI" target="_blank" style="color: #253a41;">Visit</a><i class="fa-solid fa-eye"></i></button>
         
        </div>
      </div>

      <div class="p-card">
        <div class="p-card-img">
          <img src="../assets/img/p2.png" alt="ecommerce" />
        </div>
        <div class="p-card-desc">
          <h3>Mohamed Tk portfolio</h3>
          <p>
            Responsive portfolio for datascientist using CSS (grid & flex
            layout) and HTML and javscript (Dark/Light mode)
          </p>
        </div>
        <div class="p-card-btn">
          <button><a href="https://portfolio-chi-kohl-41.vercel.app/" target="_blank" style="color: #253a41;">Visit</a><i class="fa-solid fa-eye"></i></button>
          
        </div>
      </div>

      <div class="p-card">
        <div class="p-card-img">
          <img src="../assets/img/p1.png" alt="ecommerce" />
        </div>
        <div class="p-card-desc">
          <h3>Hundle landing page</h3>
          <p>
            This responsive web page chellenge from Frontendmentor platform, i
            used my skills to convert UI/UX design to real web page.
          </p>
        </div>
        <div class="p-card-btn">
          <button><a href="https://landing-page-chellenge-5idi.vercel.app/" target="_blank" style="color: #253a41;">Visit</a><i class="fa-solid fa-eye"></i></button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.p-container {
  padding: 20px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.p-title {
  width: 100%;
  text-align: center;
  padding: 50px 0;
}

.p-title h2 {
  font-size: 38px;
  margin: 0 5px;
  
}

/*projects */
.p-projects {
  display: flex;
  flex-flow: row wrap;
  flex-direction: row;
  align-items: center;
  justify-content: center;
}

.p-projects > div {
  width: 400px;
  margin: 20px;
  border-radius: 6px;
}
.p-card {
  background: #253a41;
  box-shadow: 0px 0px 12px 10px rgba(0,0,0,0.1);
}
.p-card h3{
  color: #fff;
}
/*context card*/

.p-card-desc {
  padding: 10px;
}

.p-card-desc p {
  color: #f1f1f1;
}
/*img */
.p-card img {
  width: 400px;
  height: 300px;
  border-radius: 6px 6px 0 0;
  object-fit: cover;
  object-position: top;
}

/*btn */

.p-card-btn {
  padding: 5px;
  display: flex;
  justify-content: flex-start;
  align-items: center;
  margin: 5px 0;
}
.p-card-btn button {
  padding: 5px;
  font-size: 17px;
  font-family: "Poppins", sans-serif;
  width: auto;
  margin-left: 5px;
  border: none;
  border-radius: 4px;
  /*background: #415a77;*/
  background: #fff;
  color: #000;
  cursor: pointer;
  vertical-align: middle;
}
i {
  display: inline;
  margin: 0 8px;
  vertical-align: middle;
}

@media screen and (max-width:460px){
  .p-projects > div {
  width: 300px;

}
.p-card img {
  width: 300px;

}

.p-card-desc {
  padding: 10px;
}

.p-card-desc p {
  font-size: 0.8em;
}

.p-card-btn button {
  font-size: 15px;
}
}
</style>