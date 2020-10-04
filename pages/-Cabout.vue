<template>
  <div>
    <section id="about" class="about">
      <h2 class="heading">
        PROFILE
      </h2>
      <p class="about-text">
        子どもの頃からモノづくりが好きで、いまはウェブアプリをつくることにハマっています。
        Railsは難しくて最初は使えるようになるのかな？と不安に感じましたが、いまは本当に便利なフレームワークだなと思っています。

        これから、共通の趣味を持った仲間がコミュニケーションを取れるようなオリジナルアプリをつくっていきます。来月リリース予定なので、興味のある方はぜひお試しください！
      </p>
    </section>
  </div>
</template>

<script>
  export default {
  }
</script>

<style lang="scss" scoped>
.about {
  height: 100vh;
  padding: 80px 30px;
  background-color: #fff;
  color: #333;
}

.about-text {
    width: 600px;
    margin: 30px auto;
    line-height: 2.5;
    text-align: left;
}

.heading {
    display: inline-block;
    margin: 30px 0 15px;
    padding-bottom: 15px;
    letter-spacing: 2px;
    font-size: 4rem;
    border-bottom: double 4px #999;
}
</style>
