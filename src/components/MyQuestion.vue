<template>
    <div class="myquestion">
        <p>{{ questionText }}</p>
        <button>{{ buttonText }}</button>
    </div>
</template>

<script>
    export default {
        name: "MyQuestion",
        props: {
            questionText: String,
            buttonText: String
        }
    }
</script>

<style scoped>

    myquestion {
        float: left;
    }
</style>