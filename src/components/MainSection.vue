<template>
    <div class="container">
        <div class="container-left">
            <AboutMe />
            <MyEducation />
            <ContactInformation />
            <Skills />
        </div>
        <div class="container-right">
            <PastExperience />
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .container {
        background-color: #232B35;
        position: relative;
        border-radius: 20px;
        padding: 36px 20px 20px 20px;
        display: flex;
        justify-content: space-between;
    }
</style>

<script setup>
import AboutMe from './AboutMe.vue';
import MyEducation from './MyEducation.vue';
import ContactInformation from './ContactInformation.vue'
import Skills from './Skills.vue';
import PastExperience from './PastExperience.vue';
</script>