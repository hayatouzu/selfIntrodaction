<template>
  <div>
    <header class="header">
      <p class="site-title-sub">
        ----- Web application portfolio -----
      </p>
      <h1 class="site-title">
        My WORKS
      </h1>
      <p class="site-description">
        Check out some of my works.
      </p>
      <div class="buttons">
        <a class="button" href="#about">Profile</a>
        <a class="button button-orange" href="#skill">My skill</a>
      </div>
    </header>
  </div>
</template>

<script>
  export default {}
</script>

<style lang="scss" scoped>
.header {
    padding: 170px 30px 80px;
    height: 100vh;
    background-color: rgba(25, 25, 120, 0.9);
}
.site-title-sub {
    margin: 0 0 30px;
    letter-spacing: 1px;
    font-size: 1.2rem;
}
.site-title {
    margin: 50px;
    font-size: 4.5rem;
}
.site-description {
    margin-bottom: 50px;
    color: #888;
}
.button {
    display: inline-block;
    width: 200px;
    padding: 20px;
    margin: 10px;
    border-radius: 4px;
    background-color: #afa58d;
    color: #fff;
    text-decoration: none;
    letter-spacing: 1px;
    font-size: 0.7rem;
}

.button:hover {
    opacity: 0.9;
}

.button-orange {
    background-color: #f1b400;
}
</style>
