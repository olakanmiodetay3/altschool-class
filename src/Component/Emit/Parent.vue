
<template>
    <div>
      <div></div>
  
         <Child :handleChangeMessage="handleChangeMessage" />
    </div>
  </template>
  
  <script>
  import Child from "./Child.vue";
  export default {
    Component: {Child},
    data() {
      return {
      };
    },
    methods: {
      handleChangeMessage() {
        this.message = "good afternoon";
      },
    },
  };
  </script>
  
  <style scoped></style>
  