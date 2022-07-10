<template>
    <section class="section">
        <div class="columns is-centered">
            <div class="column is-8">
                <b-image :src="item.foto" ratio="2by1" :placeholder="item.foto"></b-image>
                <div class="columns is-multiline">
                    <div class="column is-12">
                        <p class="title">{{item.name}}</p>
                    </div>
                    <div class="column is-12">
                        <p>{{item.descripcion}}</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        data() {
            return {
                item: this.$route.params
            }
        },
    }
</script>

<style lang="scss" scoped>

</style>