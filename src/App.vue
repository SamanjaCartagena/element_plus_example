<template>
<div>
 <el-row :gutter="20">
    <el-col :span="6">
      <div class="grid-content ep-bg-purple-dark" >
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Est voluptate, iure rerum nulla nisi cupiditate iste eos minus nobis recusandae reiciendis? Facilis expedita quisquam eius dolorum quo culpa accusantium pariatur consequatur sed beatae quod vel voluptatem magni magnam, soluta eum repellendus id fuga quis quam assumenda? Eos, debitis?
      </div>
      </el-col>
        <el-col :span="6" :offset="6">
      <div class="grid-content ep-bg-purple-dark" >
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Est voluptate, iure rerum nulla nisi cupiditate iste eos minus nobis recusandae reiciendis? Facilis expedita quisquam eius dolorum quo culpa accusantium pariatur consequatur sed beatae quod vel voluptatem magni magnam, soluta eum repellendus id fuga quis quam assumenda? Eos, debitis?
      </div>
      </el-col>
      <el-col :span="6">
      <div class="grid-content ep-bg-purple-dark" >
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Est voluptate, iure rerum nulla nisi cupiditate iste eos minus nobis recusandae reiciendis? Facilis expedita quisquam eius dolorum quo culpa accusantium pariatur consequatur sed beatae quod vel voluptatem magni magnam, soluta eum repellendus id fuga quis quam assumenda? Eos, debitis?
      </div>
      </el-col>
  </el-row>
 <el-row :gutter="20">
    <el-col :span="6" :offset="8">
      <div class="grid-content ep-bg-purple-dark" >
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Est voluptate, iure rerum nulla nisi cupiditate iste eos minus nobis recusandae reiciendis? Facilis expedita quisquam eius dolorum quo culpa accusantium pariatur consequatur sed beatae quod vel voluptatem magni magnam, soluta eum repellendus id fuga quis quam assumenda? Eos, debitis?
      </div>
      </el-col>
        <el-col :span="6" :offset="8">
      <div class="grid-content ep-bg-purple-dark" >
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Est voluptate, iure rerum nulla nisi cupiditate iste eos minus nobis recusandae reiciendis? Facilis expedita quisquam eius dolorum quo culpa accusantium pariatur consequatur sed beatae quod vel voluptatem magni magnam, soluta eum repellendus id fuga quis quam assumenda? Eos, debitis?
      </div>
      </el-col>
      
  </el-row>
  <el-row :gutter="20" type="flex" justify="end">
    <el-col :md="8" :sm="12">
      <div class="grid-content ep-bg-purple-dark" >
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Est voluptate, iure rerum nulla nisi cupiditate iste eos minus nobis recusandae reiciendis? Facilis expedita quisquam eius dolorum quo culpa accusantium pariatur consequatur sed beatae quod vel voluptatem magni magnam, soluta eum repellendus id fuga quis quam assumenda? Eos, debitis?
      </div>
      </el-col>
        <el-col :md="8" :sm="12" >
      <div class="grid-content ep-bg-purple-dark" >
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Est voluptate, iure rerum nulla nisi cupiditate iste eos minus nobis recusandae reiciendis? Facilis expedita quisquam eius dolorum quo culpa accusantium pariatur consequatur sed beatae quod vel voluptatem magni magnam, soluta eum repellendus id fuga quis quam assumenda? Eos, debitis?
      </div>
      </el-col>
      <el-col :md="8" :sm="12">
      <div class="grid-content ep-bg-purple-dark" >
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Est voluptate, iure rerum nulla nisi cupiditate iste eos minus nobis recusandae reiciendis? Facilis expedita quisquam eius dolorum quo culpa accusantium pariatur consequatur sed beatae quod vel voluptatem magni magnam, soluta eum repellendus id fuga quis quam assumenda? Eos, debitis?
      </div>
      </el-col>
  </el-row>
  <el-container class="container">
    <el-aside>
     Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio quo excepturi praesentium doloremque aspernatur soluta asperiores similique voluptatem rem quibusdam laboriosam animi est atque sed, officia, eum facilis adipisci exercitationem iure quod temporibus. Iure eius itaque, alias labore ullam ea exercitationem consectetur aperiam modi perspiciatis beatae excepturi asperiores.
    </el-aside>
      <el-main>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Culpa eaque ad exercitationem aspernatur nesciunt, dolores atque, harum adipisci quia fugit temporibus distinctio iure aut nam perferendis, repellendus obcaecati libero corporis dolor laboriosam rerum ipsa? Iste maiores repellat quia perspiciatis earum eius. Tempore porro amet saepe facilis exercitationem natus?
      </el-main>
     <el-button type="primary" @click="handleClick">Primary</el-button>
  </el-container>
</div>
  
</template>

<script>

export default {
  name: 'App',
  components: {
  },
  methods:{
    handleClick(){
      console.log("Handling")
    }
  }
}
</script>

<style>
#app {
 
}
.el-row{
  margin-bottom: 100px;
  border:1px solid black;
}
.container{
  max-width:1200px;
  margin:auto;
}
</style>
