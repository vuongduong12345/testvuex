<template>
    <p>This is Results {{ result }} </p>
</template>
<script>
export default {
    // computed chạy trước khi data đc load, hthi dc result lấy từ store
    computed: {
        result() {
            return this.$store.state.result
        }
    }
}
</script>
<style>

</style>