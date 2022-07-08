<template>
    <b-navbar transparent>
        <template #brand>
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                <img
                    src="@/assets//imgs/logo.png"
                    alt="Logo de la empresa"
                >
            </b-navbar-item>
        </template>
        <template #start>
            <b-navbar-item tag="div">
                <PageSidebar />
            </b-navbar-item>
        </template>

        <template #end>
            <b-navbar-item tag="div">
                <div class="buttons">
                    <b-button type="is-success" tag="router-link" to="/" rounded >
                        Registro
                    </b-button>
                    <b-button tag="router-link" to="/" rounded >
                        Iniciar Sesion
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