<template lang="">
  <div class="card">
    <img :src="image" alt="name" style="width:100%">
    <div class="container">
      <h4><b>{{ name }}</b></h4>
      <p>{{ nickname }}</p>
      <p>{{ tel }}</p>
      <p>{{ email}}</p>
      </div>
    </div>
</template>
<script>
export default {
    props: ['id','name','nickname','tel','email','image']
}
</script>
<style scoped>
    .card {
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  width: 70%;
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

.container {
  padding: 2px 16px;
}
</style>