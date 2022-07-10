<template>
    <div class="card">
        <div class="card-image">
            <b-image ratio="1by1" :src="item.foto" :placeholder="item.foto">
            </b-image>
        </div>
        <div class="card-content">
            <nuxt-link class="subtitle" :to="{name:'detail', params:item}">{{item.name}}</nuxt-link>
        </div>
    </div>
</template>

<script>
    export default {
        props: {
            item: {
                type: Object,
                default() {
                    return { message: 'hello' }
                },
                require: true
            },
        },
    }
</script>

<style lang="scss" scoped>
</style>