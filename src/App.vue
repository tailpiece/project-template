
<template>
  <div>
    <h1>{{name}}</h1>
  </div>
</template>

<script>
  import Vue from "vue";
  import "./styles.scss";
  import {Const} from "./modules/const";

  export default Vue.extend({
    data: function() {
      return {
        name: 'project template',
      }
    },
    mounted() {
      console.info('aaa', Const.ColorMaps[2]);
    }
  });
</script>

