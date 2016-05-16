<template>
    <h1>{{ message }}</h1>
</template>

<script>
module.exports = {
    el: "body",
    replace: false,
    data: {
        message: "We did it!"
    }
}
</script>

<style>
    h1 {
        color: teal;
    }
</style>
