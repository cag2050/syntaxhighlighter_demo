<template lang='pug'>
div
    pre(class='brush: sql') select * from user where user_id = '12';

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
        SyntaxHighlighter.highlight()
        // SyntaxHighlighter.all()
    }
}
</script>

<style scoped>

</style>
