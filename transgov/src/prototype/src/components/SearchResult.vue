<template>
  <div id = "title" class = "result">
    Title: {{ searchresult.title }}
    <div id = "text" class = "result">
      Text: {{ searchresult.committee }}
    </div>
  </div>
</template>

<script>
export default {
  props: ['searchresult']
}
</script>

<style>
#title{
  font-size: 20 px;
  border-bottom: 1px solid black;
  text-overflow: ellipsis;
  overflow: hidden;
  width: 200px;
}

</style>
