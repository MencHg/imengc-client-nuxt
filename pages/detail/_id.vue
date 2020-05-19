<template>
  <section class="detail">
    <!-- {{$route.params.id}} -->
    <table>
      <thead>
        <tr>
          <td>操作</td>
          <td>项目</td>
          <td>备注</td>
          <td>条目</td>
          <td>小计</td>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td></td>
        </tr>
      </tbody>
    </table>
  </section>
</template>
<script>
export default {
  name: "home",
  components: {

  },
  data: () => ({

  }),
  watch: {

  },
  filters: {

  },
  created() {

  },
  methods: {

  },
  mounted(){

  },
};
</script>
<style scoped>
  table{
    display: block;
    height: 500px;
    background-color: #fff;
    color: #000;
  }
  thead{
    display: block;
    width: 100%;
    background-color: #eee;
  }
  tr{
    display: flex;
    justify-content: center;
  }
  td{
    width: 100%;
    border: 1px solid #aaa;
    text-align: center;
  }
</style>