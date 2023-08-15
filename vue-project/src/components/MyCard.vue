<template lang="">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Phi Phi Islands" style="width:100%" />
      <div className="container">
        <h2>namecar : {{namecar}}</h2>
        <h2>price car : {{price}}</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. A sit natus alias modi ipsam labore est assumenda aperiam in nihil. Iusto hic quidem fugit itaque dolores delectus velit accusamus odit?</p>
      </div>
    </div>
  </template>
  <script>
  export default {
    data() {
      return {
        namecar:"xxx,xxx",
        price:"xxx,xxx"
      }
    },
  }
  </script>