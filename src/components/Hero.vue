<!-- eslint-disable vue/multi-word-component-names -->
<template>
    <div class="container-flex">
        <Title />
        <img src="/img/ProfilePhoto.png" alt="" class="Hero-img">
        <SocialMedia />
    </div>
    <MainSection />
</template>

<script setup>
import Title from './Title.vue';
import SocialMedia from './SocialMedia.vue';
import MainSection from './MainSection.vue';
</script>


<style lang="scss" scoped>
.container-flex {
    display: flex;
    justify-content: space-between;

    .Hero-img {
        width: 350px;
        height: 350px;
        position: absolute;
        margin-left: 240px;
    }
}
</style>