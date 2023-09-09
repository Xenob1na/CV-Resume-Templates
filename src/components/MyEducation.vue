<template>
    <div class="container-MyEducation">
        <p class="MyEducation-line"></p>
        <h3 class="MyEducation-h3">My education</h3>
        <div class="MyEducation-1">
            <p class="MyEducation-p">Ca Institute of Technology / 2017 - 2020</p>
            <h5 class="MyEducation-h5">Master Computer Engineering</h5>
        </div>
        <div class="MyEducation-2">
            <p class="MyEducation-p">Austin College / 2013 - 2017</p>
            <h5 class="MyEducation-h5">B.S Computer Engineering Technology</h5>
        </div>
        <div class="MyEducation-3">
            <p class="MyEducation-p">New York University / 2009 - 2013</p>
            <h5 class="MyEducation-h5">B.S Data Structures</h5>
        </div>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>
.container-MyEducation {
    max-width: 350px;
    margin-top: 28px;

    .MyEducation-line {
        background-color: #fff;
        width: 58px;
        height: 3px;
        margin: 0;
    }

    .MyEducation-h3 {
        font-size: 18px;
        font-style: normal;
        font-weight: 700;
        line-height: 130%;
        color: #fff;
        margin: 0;
        margin-top: 14px;
        margin-bottom: 14px;
    }

    .MyEducation-1,
    .MyEducation-2,
    .MyEducation-3 {
        margin-bottom: 20px;

        .MyEducation-p {
            font-size: 14px;
            font-style: normal;
            font-weight: 500;
            line-height: 130%;
            letter-spacing: 0.7px;
            text-transform: uppercase;
            color: #C3CAD5;
            margin: 0;
            margin-bottom: 5px;
        }

        .MyEducation-h5 {
            font-size: 14px;
            font-style: normal;
            font-weight: 700;
            line-height: 120%;
            color: #fff;
            margin: 0;
        }
    }

}
</style>