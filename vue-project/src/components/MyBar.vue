<template lang="">
    <div>
      <nav>
        <a href="#/">Home</a> |
        <a href="#/keng">keng</a> |
        <a href="#/non-existent-path">Broken Link</a>
        <component :is="currentView" />
      </nav>
    </div>
  </template>
  
<script>
export default {

}
</script>
  
  <!-- <style scoped>
  nav {
    position: fixed; /* ให้ Navbar อยู่ติดกับด้านบนของหน้าจอ */
    top: 0; /* กำหนดให้อยู่ด้านบนสุด */
    width: 100%; /* กำหนดให้ Navbar ครอบคลุมทั้งหน้าจอ */
    background-color: #333;
  }
  
  ul {
    display: flex;
    justify-content: center;
    align-items: center;
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #333;
  }
  
  li {
    margin: 0;
    padding: 0;
  }
  
  li a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
  }
  </style>
   -->