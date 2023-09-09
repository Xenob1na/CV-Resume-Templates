<template>
    <div class="container-ContactInformation">
        <p class="ContactInformation-line"></p>
        <h3 class="ContactInformation-h3">Contact information</h3>
        <div class="ContactInformation-1">
            <p class="ContactInformation-email">Email:</p>
            <a href="mailto:contact@johncarter.com" class="email-link">contact@johncarter.com</a>
        </div>
        <div class="ContactInformation-2">
            <p class="ContactInformation-Call">Call:</p>
            <a href="tel:(414)977048" class="Call-link">(414) 977 - 048</a>
        </div>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>
.container-ContactInformation {
    max-width: 350px;
    margin-top: 29px;

    .ContactInformation-line {
        background-color: #fff;
        width: 58px;
        height: 3px;
        margin: 0;
    }

    .ContactInformation-h3 {
        margin: 0;
        margin-top: 13px;
        font-size: 18px;
        font-style: normal;
        font-weight: 700;
        line-height: 130%;
        color: #fff;
    }

    .ContactInformation-1,
    .ContactInformation-2 {
        .ContactInformation-email {
            margin: 0;
            margin-top: 20px;
            margin-bottom: 10px;
            font-size: 14px;
            font-style: normal;
            font-weight: 700;
            line-height: 8.358px;
            letter-spacing: 0.446px;
            text-transform: uppercase;
            color: #C3CAD5;
        }

        .email-link {
            margin: 0;
            font-size: 14px;
            font-style: normal;
            font-weight: 700;
            line-height: 130%;
            color: #fff;
            text-decoration: none;
        }
        .ContactInformation-Call {
            margin: 0;
            margin-top: 20px;
            margin-bottom: 10px;
            font-size: 14px;
            font-style: normal;
            font-weight: 700;
            line-height: 8.358px;
            letter-spacing: 0.446px;
            text-transform: uppercase;
            color: #C3CAD5;
        }
        .Call-link {
            margin: 0;
            font-size: 14px;
            font-style: normal;
            font-weight: 700;
            line-height: 130%;
            color: #fff;
            text-decoration: none;
        }

    }
}
</style>