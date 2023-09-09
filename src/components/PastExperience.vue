<template>
    <div class="container-PastExperience">
        <p class="PastExperience-line"></p>
        <h3 class="PastExperience-h3">Past Experience</h3>
        <div class="PastExperience-box" v-for="(Experience, index) in Experiences" :key="index">
            <div class="PastExperience-box-head">
                <img :src="Experience.img" alt="" class="head-img">
                <p class="head-p">{{ Experience.date }}</p>
            </div>
            <p class="PastExperience-box-title">{{ Experience.title }}</p>
            <p class="PastExperience-box-p">{{ Experience.body }}</p>
            <hr>
        </div>
    </div>
</template>

<script setup>
import { ref } from 'vue';

const Experiences = ref([
    {
        img: '/img/Google.svg',
        date: 'Jan 2021 / Present',
        title: 'Head of Engineering at Google',
        body: 'Lorem ipsum dolor sit amet consectet adipiscing elit et et est eget tortor lacus aliquam pulvinar senectus ut sapien type specimen book. It has survived not only five centuries.'
    },
    {
        img: '/img/Facebook-1.svg',
        date: 'APR 2018 / Jan 2021',
        title: 'Lead Frontend Developer at React',
        body: 'Lorem ipsum dolor sit amet consectet adipiscing elit et et est eget tortor lacus aliquam pulvinar senectus ut sapien type specimen book. It has survived not only five centuries.'
    },
    {
        img: '/img/Youtube1.svg',
        date: 'Aug 2014 / APR 2018',
        title: 'Frontend Lead at YouTube',
        body: 'Lorem ipsum dolor sit amet consectet adipiscing elit et et est eget tortor lacus aliquam pulvinar senectus ut sapien type specimen book. It has survived not only five centuries.'
    },
    {
        img: '/img/Microsoft.svg',
        date: 'jan 2010 / APR 2014',
        title: 'Junior developer at Microsoft',
        body: 'Lorem ipsum dolor sit amet consectet adipiscing elit et et est eget tortor lacus aliquam pulvinar senectus ut sapien type specimen book. It has survived not only five centuries.'
    }
])
</script>

<style lang="scss" scoped>
.container-PastExperience {
    max-width: 400px;

    .PastExperience-line {
        background-color: #fff;
        width: 58px;
        height: 3px;
        margin: 0;
    }

    .PastExperience-h3 {
        margin: 0;
        margin-top: 13px;
        margin-bottom: 28px;
        font-size: 18px;
        font-style: normal;
        font-weight: 700;
        line-height: 130%;
        color: #fff;
    }

    .PastExperience-box {
        margin-bottom: 31px;
        .PastExperience-box-title {
            font-size: 18px;
            font-style: normal;
            font-weight: 700;
            line-height: 130%;
            color: #fff;
            margin: 0;
            margin-top: 11px;
        }

        .PastExperience-box-p {
            font-size: 16px;
            font-style: normal;
            font-weight: 400;
            line-height: 130%;
            color: #C3CAD5;
            margin: 0;
            margin-top: 12px;
            margin-bottom: 12px;
        }

        .PastExperience-box-head {
            display: flex;
            gap: 18px;

            .head-img {
                width: 80px;
            }

            .head-p {
                font-size: 14px;
                font-style: normal;
                font-weight: 500;
                line-height: 71%;
                letter-spacing: 0.7px;
                text-transform: uppercase;
                color: #C3CAD5;
            }
        }
    }
}
</style>