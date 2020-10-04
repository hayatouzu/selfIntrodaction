<script>
import { Doughnut } from 'vue-chartjs'
  export default ({
  extends: Doughnut,
  data() {
    return {
      datas: {
        // 凡例とツールチップに表示するラベル
        labels: ['Sun', 'Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat'],
        // 表示するデータ
        datasets: [
          {
            data: [10, 15, 6, 22, 11, 49, 32],
            backgroundColor: ['#f87979', '#aa4c8f', '#38b48b', '#006e54', '#c1e4e9', '#89c3eb', '#c3d825']
          }
        ]
      },
      options: {
        responsive: true
      }
    }
  },
  mounted() {
    this.renderChart(this.datas, this.options)
  }
})
</script>

<style lang="scss" scoped>
.skill {
  height: 100vh;
  background-color: rgba(25, 25, 120, 0.9);
}
.title {
    display: inline-block;
    margin: 30px 0 15px;
    padding-bottom: 15px;
    font-size: 4rem;
}
</style>
