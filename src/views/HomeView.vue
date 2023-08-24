<template>
  <el-table
  :data="tableData"
  stripe
  style="width: 100%">
  <el-table-column
    prop="skiresortName"
    label="スキーリゾート名"
    width="200">
  </el-table-column>
  <el-table-column
    prop="area"
    label="エリア"
    width="200">
  </el-table-column>
  <el-table-column
    prop="access"
    label="アクセス"
    width="200">
  </el-table-column>
  <el-table-column
    prop="numberOfStars"
    label="星の数"
    width="200">
  </el-table-column>
  <el-table-column
    prop="recommentedPoint"
    label="お勧めポイント">
  </el-table-column>

</el-table>
</template>

<script>
export default {
  data () {
    return {
      tableData: [{ // 項目が5つあるので、要素数（5回ループ又はmapする）
        skiresortName: 'わん',
        area: 'にゃん',
        access: 'がおー',
        numberOfStars: 'わんわん',
        recommentedPoint: 'ぱおーん'
      }, {
        skiresortName: 'わん',
        area: 'にゃん',
        access: 'がおー',
        numberOfStars: 'わんわん',
        recommentedPoint: 'ぱおーん'
      }, {
        skiresortName: '',
        area: '',
        access: '',
        numberOfStars: '',
        recommentedPoint: ''
      }]
    }
  }
}
</script>
