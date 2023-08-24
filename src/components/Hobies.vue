<template>
  <div class="hobies-container">
    <div class="hobies-title">
      <h2>Favorite books</h2>

    </div>
    <div class="books">
      <div><img src="../assets/img/m1.jpg" alt="m1" /></div>
      <div><img src="../assets/img/ds.jpg" alt="ds" /></div>
      <div><img src="../assets/img/r.jpg" alt="m1" /></div>
      <div><img src="../assets/img/aibro.jpg" alt="ds" /></div>
      <div><img src="../assets/img/ali.jpg" alt="ds" /></div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.hobies-container {
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 0 30px;
}
.hobies-title {
width: 100%;
  text-align: center;
}
.books {
  margin-top: 20px;
  display: flex;
  flex-flow: row wrap;
  flex-direction: row;
  align-items: center;
  justify-content: center;
}
.books > div {
  margin: 20px;

  width: 200px;
  height: 200px;
}
.books img {
  width: 200px;
  height: 200px;
  border-radius: 8px;
}
</style>