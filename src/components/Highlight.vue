<template lang='pug'>
div
    pre(class='brush: sql') select * from user;

</template>

<script>
let SyntaxHighlighter = window.SyntaxHighlighter

export default {
    name: '',
    data () {
        return {
        }
    },
    mounted () {
        SyntaxHighlighter.all()
    }
}
</script>

<style scoped>

</style>
