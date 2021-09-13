<template>
  <h2>{{title}}</h2>
</template>

<script>
export default {
    props: {
        title: String,
    }
}
</script>

<style>

h2 {
    font-size: 22px;
    margin: 20px 0;
}

</style>