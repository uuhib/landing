<template>
  <div class="main">
        <div class="text">
            <p>
                In Orlando, plumbing problems are taken care of quickly and efficiently by the experts at Grace Plumbing Inc. When something goes wrong with your sink, toilet, bath, water heater or pipes, you want it fixed right away. We offer prompt and professional service that ensures everything will be working properly again often with same day service. Our goal is to take the time to get it right the first time.
            </p>
            <p>We are a full service company that employs background checked plumbers that have the experience to solve the problem quickly and professionally. Need a new sink or bathtub installed, or your pipes replaced? We can do that too, and we keep our prices affordable. Our full range of services includes:</p>
            <img src="contact-us.svg" alt="">
        </div>
        <div class="form"></div>
  </div>
</template>

<script>


export default {
  name: 'Main'
}
</script>

<style>

.form{
    width: 385px;
    min-height: 450px;
    background: #45969b;
    border-radius: 2px;
}
.text{
    width: 50%;
    padding: 10px;

}
.text p{
    padding-bottom: 20px;
}
.main{
    display: flex;
    justify-content: space-between;
    width: 80vw;
    margin: auto;
    margin-top: 30px;
}
</style>