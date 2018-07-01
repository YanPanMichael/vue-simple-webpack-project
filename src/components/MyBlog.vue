<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    h1, h2 {
        font-weight: normal;
    }
    ul {
        list-style-type: none;
        padding: 0;
    }
    li {
        display: inline-block;
        margin: 0 10px;
    }
    a {
        color: #42b983;
    }
</style>

<template>
  <div class="my-blog">
  </div>
</template>

<script>
    export default {
        name: 'myBlog',
        data () {
            return {
                msg: 'Welcome to my blog'
            }
        }
    }
</script>

