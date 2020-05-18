<template>
  <div class="home">
        <img src="@/assets/herald.png" alt="Herald" />
        
        <weatherWidget />
  </div>
</template>

<script>
import weatherWidget from '@/components/weatherWidget.vue';

export default {
  name: "home",
  components: {
    weatherWidget
  }
}
</script>

<style lang="scss" scoped>
.home {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    flex-direction: column;
}

img {
    border-radius: 50%;
    margin-bottom: 40px;
}
</style>
