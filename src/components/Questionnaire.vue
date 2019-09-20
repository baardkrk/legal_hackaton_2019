<template>
    <div class="questionnaire">
        <h2>{{ header }}</h2>
        <Question questionText="myfirstquestion" buttonText="mybutton"/>
        <Question questionText="mysecondquestion" buttonText="mysecondbutton" />
        <BinaryQuestion questionText="My Binary Question"/>
        <BinaryQuestion question-text="Mye second binary querstion"/>
    </div>
</template>

<script>
    import Question from './MyQuestion.vue'
    import BinaryQuestion from './BinaryQuestion'

    export default {
        name: "Questionnaire",
        components: {
            BinaryQuestion,
            Question
        },
        props: {
            header: String
        }
    }
</script>

<style scoped>

    . {
        background-color: antiquewhite;
    }

</style>