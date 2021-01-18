<template>
  <div>
    <main>
      <div class="search-box">
        <input type="text" class="search-bar" placeholder="Search..." />
      </div>
    </main>
  </div>
</template>

<script>

export default {
  name: 'App',
  data () {
    return {
      api_key: process.env.WEATHER_API
    }
  }
}
</script>

<style>

</style>
