<template>
  <div class="login-container">
    {{loginForm.username}}
  </div>
</template>

<script>

export default {
  name: 'login',
  data() {
    return {
      loginForm: {
        username: 'admin',
        password: '1111111'
      },
      passwordType: 'password',
      loading: false,
      showDialog: false
    }
  },
  methods: {

  },
  created() {
    // window.addEventListener('hashchange', this.afterQRScan)
  },
  destroyed() {
    // window.removeEventListener('hashchange', this.afterQRScan)
  }
}
</script>
