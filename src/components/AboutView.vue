<template>
  <div class="about">
    <div class="header">
      <span class="header__title">About</span>
    </div>
    <img class="about__image circle" src="/static/jeroen.jpg" alt="Svitlana Murakhovska">
    <p>This website was build by <a href="https://www.instagram.com/leveny7/" target="_blank">Svitlana Murakhovska</a>
  </div>
</template>

<script>
  export default {}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>

  .about {

    display: block;
    margin-left: auto;
    margin-right: auto;
    max-width: 700px;

  p {
    text-align: center;
  }

  .about__image {
    width: 150px;
    height: 150px;
    display: block;
    margin-left: auto;
    margin-right: auto;
  }

  }

</style>
