<template>
  <div class="hello">
    <h1>{{ title }}</h1>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    title: String,
    message: String,
  }
}
</script>

<style>
  div {
    margin: 10px;
    padding: 0;
    text-align: left;
  }
  h1 {
    font-size: 72pt;
    font-weight: bold;
    text-align: right;
    letter-spacing: -8px;
    color: #f0f0f0;
    margin: 0;
  }
  p {
    margin: 0;
    color: #666;
    font-size: 16pt;
  }
</style>
