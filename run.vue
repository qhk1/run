<template>
    <div class='main_box'>
        <audio src="../assets/img/music.mp3" controls></audio>
    </div>
</template>

<script>
    export default {
        data() {
            return {

            }
        },
        created() {},
        mounted() {},
        methods: {},
    };

</script>

<style scoped lang='less'>
* {
    box-sizing: border-box;
}
    .main_box {
        padding: 20px;
        width: 100%;
        height: 100%;
        .audio {
            width: 100%;
        }
    }

</style>
