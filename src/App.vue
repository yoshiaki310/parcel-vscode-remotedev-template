<template>
  <div>
    {{ title }}
    <MyButton></MyButton>
  </div>
</template>

<style>
</style>

<script lang="ts">
    import { Component, Vue } from 'vue-property-decorator';
    import MyButton from "./MyButton.vue";
    @Component({
        components: {
            MyButton,
    },
    })
    export default class Home extends Vue {
    data() {
      return({
        title: 'Hello World!',
      });
    }
  }
</script>