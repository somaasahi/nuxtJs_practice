<template>
  <div>
    <div>{{message}}</div>
    <RouterLink to="/next">次ページへ</RouterLink>
    <div>数値:{{$store.state.count}}</div>
    <button v-on:click="increment">カウントアップ</button>
  </div>
</template>

<script>
export default {
  data: function() {
    return {
      message: 'Hello Nuxt!'
    }
  },
  methods: {
    increment: function() {
      this.$store.commit('increment')
    }
  }
}
</script>
