<template>
  <div id="app">
    <hello></hello>
  </div>
</template>

<script>
    import Hello from './components/Hello'

    export default {
        name: 'app',
        data() {
            return {
                parrilla: [
                    [1, 1, 1, 1],
                    [1, 1, 1, 1],
                    [1, 1, 1, 1],
                    [1, 1, 1, 1]
                ]
            }
        },
        components: {
            Hello
        }
    }

</script>

<style>


</style>
