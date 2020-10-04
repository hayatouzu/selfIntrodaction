<template>
  <div>
    <section class="works">
      <h2 class="heading">
        MY WORKS
      </h2>
      <div class="works-wrapper">
        <div class="work-box">
          <img class="work-image" src="images/pictweet.jpg" alt="制作事例">
          <div class="work-description">
            wasiseSaiying
            <a href="#" class="button button-ghost">READ MORE</a>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
  export default {

  }
</script>

<style lang="scss" scoped>
.works {
  height: 100vh;
  background-color: #383634;
  padding: 80px 0 10px;
}
.works-wrapper {
  display: flex;
  justify-content: center;
  margin: 60px auto 0;
}

.work-box {
  background-color: rgba(100, 100, 100, 0.3);
  border: 1px solid #333;
}

.work-image {
  display: block;
  width: 100%;
}

.work-description {
  margin: 20px 0;
}

.work-description .button {
  width: 60%;
  margin-top: 20px;
  padding: 3px;
}

.button-ghost {
  border: 2px solid #fff;
  background-color: rgba(255, 255, 255, 0.15);
}
</style>
