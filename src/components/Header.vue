<template>
    <div class="generalheader">
        <img v-bind:src="lmuLogo" id="lmu-logo">
        <div class="header-flag">
            <div class="header-text"></div>
            <div class="language"></div>
            <div class="hamburger-menu"></div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Header',
    data() {
        return {
            lmuLogo: require("../assets/images/lmu-logo-zugeschnitten.png")
        }
    }
}
</script>

<style>
.generalheader {
    height: 80px;
    width: 100%;
    background-color:#ffffff;
    display: flex;
    flex-direction: row;
    align-content: center;
}

.header-flag {
    margin-top: 7px;
    margin-bottom: 7px;
    margin-right: 7px;
    height: 66px;
    width: 100%;
    background-color: #4F4F4F;
}

#lmu-logo {
    margin: 7px;
}


</style>