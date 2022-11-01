<template>
  <div>
    <div>{{message}}</div>
    <RouterLink to="/">トップページへ</RouterLink>
  </div>
</template>

<script>
export default {
  data: function() {
    return {
      message: 'Hello NextPage!'
    }
  }
}
</script>
