<template>
    <div class="binary-question">
        <p>{{ questionText }}</p>
        <input type="radio" name="yesno" value="yes">Ja<br>
        <input type="radio" name="yesno" value="nei">Nei<br>
        <button>Send</button>
    </div>
</template>

<script>
    export default {
        name: "BinaryQuestion",
        props: {
            questionText: String
        }
    }
</script>

<style scoped>

</style>