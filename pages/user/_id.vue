<template>
  <div>{{message}}</div>
</template>

<script>
export default {
  computed: {
    message: function() {
      let user_id = this.$route.params.id
      return "ユーザーID["+ user_id +"]のページです。"
    }
  }
}
</script>
