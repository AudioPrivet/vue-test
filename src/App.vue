<template>
  <div class="container">
    <div class="row justify-content-center">
      <div class="col-6 my-5">
        <form>
          <InputPassword v-model="password"/>
        </form>
        <code>
          {{ password }}
        </code>
      </div>
    </div>
  </div>
</template>

<script>
import InputPassword from './components/InputPassword.vue'

export default {
  name: 'App',
  components: {
    InputPassword
  },
  data () {
    return {
      password: 'test123'
    }
  }
}
</script>
