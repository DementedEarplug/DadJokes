<template>
  <div class="joke">
      <p>
          {{joke}}
      </p>
  </div>
</template>

<script>
export default {
    name: 'Joke',
    props: [
        'joke',
        'id'
    ]
}
</script>

<style scoped>
    .joke {
        padding: 1rem;
        margin: 1rem 0;
        border: 1px dotted #ccc;
    }

</style>