<template>
  <div class="container">
    
      <h2>
        Learning nuxt nuances leveraging the power of dad jokes!
      </h2>
      
  </div>
</template>

<script>

export default {
  head() { //Shit to help with SEO
        return {
            title: 'Welcome to Dad Jokes!',
            meta: [
                {
                    hid: 'description',
                    name: 'description',
                    content: 'Best place for dadjokes, sunny!'
                }
            ]
        }
    }
}
</script>

<style scoped>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
