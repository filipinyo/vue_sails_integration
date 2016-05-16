<template>
    <h1>{{ message }}</h1>
</template>

<script>
module.exports {
    el: "body",
    components: {

    },
    data: function() {
        return {
            message: "We did it!"
        }
    }
}
</script>

<style>
    h1 {
        color: teal;
    }
</style>
