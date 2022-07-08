<template>
    <b-navbar transparent>
        <template #brand>
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                <img
                    src="@/assets//imgs/personaje.jpg"
                    alt="Logo de la empresa"
                >
            </b-navbar-item>
        </template>
        <template #start>
            <b-navbar-item tag="router-link" to="/">
                Home
            </b-navbar-item>
        </template>

        <template #end>
            <b-navbar-item tag="div">
                <div class="buttons">
                    <b-button type="is-twitter" tag="a" target="blank" href="https://t.me/Christian_S_Ll/" rounded icon-right="telegram">
                        Telegram
                    </b-button>
                    <b-button type="is-dark" tag="a" target="blank" href="https://github.com/ChristianSantanaLlanes/" rounded icon-right="github">
                        Github
                    </b-button>
                </div>
            </b-navbar-item>
        </template>
    </b-navbar>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

</style>