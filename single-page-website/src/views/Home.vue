<template>
  <div class="home">
    <div class="container">
      <div  class="columns">
        <div class="column auto">
          <div class="text">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore ad, impedit et minima numquam dolorem obcaecati, deleniti nulla fuga ullam aperiam ea nam, sunt officia. Perspiciatis velit repudiandae ut, labore delectus reprehenderit accusantium, placeat, unde eaque ullam esse odio corrupti. Repudiandae veniam in dolor maxime rem optio repellendus maiores sint, quas quis ducimus architecto saepe reiciendis, doloremque sit vitae dolorem nemo dolore autem animi a cum perferendis ullam! Magni molestias earum minima! Molestiae quasi atque magni deleniti deserunt, cupiditate accusamus numquam quibusdam veritatis exercitationem sit fuga itaque nostrum cum voluptatem explicabo corporis, repellat cumque. Recusandae architecto quasi sequi fuga molestiae!</p>
          </div>  
          <div class="">
            <button type="button" class="button is-primary" name="button"><router-link :to="{ name:'About'}">Learn more</router-link></button>
          </div>
        </div>
        <div class="column is-three-fifths">
          <div class="">
            <img src="@/assets/music4.png" alt="image1">
          </div>  
        </div>  
        </div>
    </div>  
  </div>
</template>

<script>
</script>

<style scoped>
*  {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
  .text {
    margin-top: 45%;
  }
  img {
    margin-left: 20%;
  }
  p {
    margin-bottom: 25px;
  }
  a {
    color: black;
  }
</style>