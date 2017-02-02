<template>
  <div class="profile">
    {{ name }}
    <picture></picture>
  </div>
</template>

<script>
import picture from './picture.vue'
export default {
  data () {
    return {
      name: 'Jesse Test Wise'
    };
  },
  components:{ picture }
};
</script>

<style>
.profile {
    background: #eee;
    border: 1px solid #aaa;
    border-radius: 2em;
    margin: 2em auto;
    min-height: 150px;
    padding: 2em;
    width: 300px;
}
</style>