<template>
  <div class="">
      <h1>Hello</h1>
      <p>Im using this as a learnign experience to help spread the joy of dadjokes around the world.</p>
  </div>
</template>

<script>
export default {
    head() { //Shit to help with SEO
        return {
            title: 'About the app',
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

<style>

</style>