<template>
  <div class="">jokes</div>
</template>

<script>
import axios from 'axios'; 

export default {
    data(){
        return {
            jokes: []
        }
    },

    async created(){ //everything here runs on component load
        const config = {
            headers: {
                "Accept": "application/json"
            }
        }

        try {
            const response = await axios.get('https://icanhazdadjoke.com/search', config);
            this.jokes = response.data.results;
        } catch (error) {
            console.log(error)
        }

    },
    head() { //Shit to help with SEO
        return {
            title: 'Here\'s some Dad Jokes!',
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