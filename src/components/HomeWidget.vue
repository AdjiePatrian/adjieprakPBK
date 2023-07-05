<template>
    <div class="widget">
      <h2>{{ title }}</h2>
      <p>{{ message }}</p>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        title: 'UAS Praktikum PBK : Widget ',
        message: 'Hola, Adjie Patrian Khalish (213510709)',
      };
    },
  };
  </script>
  
  <style scoped>
  .widget {
    border: 1px solid #ccc;
    padding: 20px;
    margin-bottom: 20px;
  }
  </style>