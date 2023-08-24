<template>
  <div class="contact-container">
    <div>
      <div class="contact-title">
        <h2>Contact me</h2>
      </div>
      <form action="">
        <div>
          <label for="name">Name</label>
          <input type="text" id="name" placeholder="Enter your name.." />
        </div>
        <div>
          <label for="email">Email</label>
          <input type="email" id="email" placeholder="Enter your email.." />
        </div>
        <div>
          <label for="message">Message</label>
          <textarea
            id="message"
            cols="30"
            rows="7"
            placeholder="Message.."
          ></textarea>
        </div>
        <div class="div-btn">
          <input type="submit" value="Send" class="form-btn"/>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.contact-container{
    display: flex;
    justify-content: center;
    margin: 40px 0;
}
.contact-title{
    text-align: center;
    color: #000;
}
.contact-title h2{
    color: #000;
}
.contact-container > div{
    width: 70%;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    background: #fff;
    padding: 20px 0;
    border-radius: 6px;
}

.contact-container form{
    width: 80%;
}

form input{
    padding: 5px;
    font-family: 'Poppins', sans-serif;
    font-size: 18px;
    color: #000;
}
textarea{
    padding: 5px;
    font-family: 'Poppins', sans-serif;
    font-size: 16px;
    color: #000;
}
.div-btn{
    text-align: center;
}
.form-btn{
    border: none;
    border-radius: 4px;
    color: #fff;
    font-family: 'Poppins', sans-serif;
    font-size: 18px;
    padding: 5px 0;
    width: 50%;
    background: #253a41;
    cursor: pointer;
}

@media screen and (max-width:420px) {
    .contact-container > div{
    width: 90%;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    background: #fff;
    padding: 20px 0;
    border-radius: 6px;
}
}
</style>