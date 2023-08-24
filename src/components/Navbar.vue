<template>
  <nav>
    <div class="nav-title">
      <h2>Alii</h2>
    </div>

    

    <div class="nav-icon">
      <a href="https://github.com/AliMehizel" target="_blank" style="color: #253a41;"><i class="fa-brands fa-github"></i></a>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
nav {
  padding: 30px 70px;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

nav > div {
  width: auto;
}

.nav-title h2{
  color: #253a41;
}



/*logo githubg */
.nav-icon i {
  font-size: 50px;
  cursor: pointer;
}

@media screen and (max-width:380px) {
    nav {
  padding: 20px;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
    .nav-links a {
  margin: 0 5px;
text-decoration: underline;
  color: #000;
  font-size: 15px;
}
}
</style>