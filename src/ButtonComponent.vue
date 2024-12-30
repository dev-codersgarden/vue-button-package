<template>
    <button @click="showAlert">Click Me!</button>
  </template>
  
  <script setup>
  const showAlert = () => {
    alert('Hello from your Vue component!');
  }
  </script>
  
  <style scoped>
  button {
    padding: 8px 16px;
    font-size: 16px;
    cursor: pointer;
  }
  </style>
  