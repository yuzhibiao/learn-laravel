<template>
  <div class="container">
    <div class="content">
      <div class="title">{{ msg }}</div>
      <div class="links">
        <a href="#">Author: {{ author }}</a>
        <a href="#">Email: {{ email }}</a>
        <a href="#">GitHub</a>
      </div>
    </div>
  </div>
</template>

<script>
  export default{
    data () {
      return {
        msg: 'Vue - Laravel - Example',
        author: 'Bill',
        email: 'yuzhibiao@appgame.com'
      }
    }
  }
</script>

<style>
  html, body {
    height: 100%;
  }
  body {
    margin: 0;
    padding: 0;
    width: 100%;
    display: table;
    font-weight: 100;
    font-family: 'Lato';
  }
  .container {
    text-align: center;
    display: table-cell;
    vertical-align: middle;
  }
  .content {
    text-align: center;
    display: inline-block;
  }
  .title {
    font-size: 96px;
  }
  .links > a {
    color: #636b6f;
    padding: 0 25px;
    font-size: 12px;
    font-weight: 600;
    letter-spacing: .1rem;
    text-decoration: none;
    text-transform: uppercase;
  }
</style>
