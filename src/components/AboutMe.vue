<template>
    <div class="container-AboutMe">
        <p class="AboutMe-line"></p>
        <h3 class="AboutMe-h3">About me</h3>
        <p class="AboutMe-p">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit fames turpis pretium bibendum nisl est sagittis aliquam
            pretium nunc curabitur est in nulla id volutpat et nenatis at lacus.
        </p>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>
.container-AboutMe {
    max-width: 350px;

    .AboutMe-line {
        background-color: #fff;
        width: 58px;
        height: 3px;
        margin: 0;
    }

    .AboutMe-h3 {
        font-size: 18px;
        font-style: normal;
        font-weight: 700;
        line-height: 130%;
        color: #fff;
        margin: 0;
        margin-top: 14px;
        margin-bottom: 14px;
    }

    .AboutMe-p {
        font-size: 16px;
        font-style: normal;
        font-weight: 400;
        line-height: 130%;
        color: #C3CAD5;
        margin: 0;
    }
}
</style>