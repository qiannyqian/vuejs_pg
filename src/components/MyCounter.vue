<template>
  <div class="">
    <div class="counter">
      {{count}}
    </div>
    <button v-on:click="count++">Click to +1</button>
  </div>
</template>


<script>
export default {
  data () {
    return {
      count: 0,
    }
  }
}
</script>
