<template>
    <b-container>
        <questions test-type="quiz"></questions>
    </b-container>
</template>

<script>
    import Questions from './questions.vue'

    export default {
        components: {
            Questions
        },
        name: "quizzes"
    }
</script>

<style scoped>

</style>