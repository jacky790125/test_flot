<template>
  <div class="about">
    <h1>This is an about page</h1>
    <div id="msg"></div>
  </div>
</template>

<script>
import $ from 'jquery';

export default {
    name: 'about',
    mounted() {
      $('#msg').text('test jquery');
    },
}
</script>