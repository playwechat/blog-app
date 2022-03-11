<template>
  <el-card class="box-card" style="width:600px ;height:600px">
    <ChartBtCategory ></ChartBtCategory>
  </el-card>
</template>

<script>
  import ChartBtCategory from "./charts/ChartBtCategory";
  export default {
    name: "dataShow",
    components: {ChartBtCategory},
    // data(){
    //
    // },
    created() {

    },
  }
</script>

<style>
  .text {
    font-size: 14px;
  }

  .item {
    padding: 18px 0;
  }

  .box-card {
    width: 480px;
  }
</style>
