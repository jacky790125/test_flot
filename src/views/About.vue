<template>
  <div class="about">
    <h1>This is an about page</h1>
    <div id="msg"></div>
    <div id="chart"></div>
  </div>
</template>

<script>
import $ from 'jquery';

export default {
    name: 'about',
    mounted() {
      // jquery test
      $('#msg').text('test jquery');

      // flot test
      var d2 = [[0, 3], [4, 8], [8, 5], [9, 13]];
      $.plot("#chart", d2);
    },
}
</script>