
<template>
    <div>
     <span>{{index}}</span> 
   <span>{{nickName}}</span> 
   <div>{{typeOfAnimal}}</div>
    </div>
</template>

<script>
    export default {
        props:["index", "nickName", "typeOfAnimal"], 
    }
</script>

<style scoped>

</style>