<template>
  <v-btn @click="clickbtn">this is test button</v-btn>
</template>

<script>
export default {
    data() {
        return {
            
        }
    },
    methods: {
        clickbtn: function () {
            alert('clicked me!')
        }
    },
}
</script>

<style>

</style>