<template>
  <div>
    <Banner />
    <div class="main-container">
      <h1>Monte sua Pizza:</h1>
      <BurgerForm />
    </div>
  </div>
</template>

<script>
import Banner from '../components/Banner'


export default {
  name: 'Home',
  components: {
    Banner

  }
}
</script>