<template>
    <div class="spinner"></div>
    <Spinner v-if="loading" />
  </template>
  
  <script>
  export default {
    name: 'Spinner'
  };
  </script>
  
  <style>
  .spinner {
    width: 40px;
    height: 40px;
    border-radius: 50%;
    border: 4px solid #f3f3f3;
    border-top: 4px solid #635531;
    animation: spin 1s linear infinite;
  }
  
  @keyframes spin {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
  }
  </style>