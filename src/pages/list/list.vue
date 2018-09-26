<template>
    <div id="content">
       <list></list>
    </div>
</template>

<script>
import list from '@/components/list'
export default {
  name: 'content',
  components: { list }
}
</script>

<style>
#content {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
