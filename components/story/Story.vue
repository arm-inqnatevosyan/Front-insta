<template>
    <div class="story">
        <div id="one-block">
        <img src="../story/insta8.jpg" />
        <div>
          <i id='add' class="fa-solid fa-circle-plus"></i>
        </div>
        <p>Your Story</p>
      </div>
      <div>
        <img src="../story/insta1.webp" />
        <p>axelbeyon</p>
      </div>
      <div>
        <img src="../story/insta2.jpg" />
        <p>simson</p>
      </div>
      <div>
        <img src="../story/insta3.jpg" />
        <p>ico.wooy</p>
      </div>
      <div>
        <img src="../story/insta4.webp" />
        <p>louwsers</p>
      </div>
      <div>
        <img src="../story/insta5.jpg" />
        <p>tinanakey</p>
      </div>
      <div>
        <img src="../story/insta6.jpg" />
        <p>robincield</p>
      </div>
      <div>
        <img src="../story/insta7.jpg" />
        <p>arnauld</p>
      </div>
    </div>
</template>

<script>
export default {
  name: 'StoryVue',
}
</script>
<style scoped>
.story{
    width: 78%;
    height: auto;
    display: flex;
    justify-content: space-evenly;
    margin: 0 auto;
    margin-top: 30px;
}
.story img{
    width: 60px;
    height: 60px;
    border-radius: 50% 50%;
}
.story p{
    font-size: 13px;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
#one-block{
    position: relative;
}
#add{
    position: absolute;
    bottom: 20%;
    color: rgb(52, 157, 228);
    right: -10%;
    font-size: 20px;
}
</style>