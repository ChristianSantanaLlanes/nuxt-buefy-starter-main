<template>
    <div>
        <section class="section">
            <div class="columns">
                <div class="column">
                    <div class="notification is-primary">Hola</div>
                </div>
                <div class="column">
                    <div class="notification is-danger">Hiiiiiii</div>
                </div>
            </div>
        </section>
        <div class="container">
            <div class="buttons">
                <b-button type="is-warning" @click="confirmCustom">Ver dialogo</b-button>
                <b-button type="is-primary" tag="router-link" to="/">Atras</b-button>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

</style>