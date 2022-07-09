<template>
    <div class="card">
        <div class="card-image">
            <b-image ratio="5by3" :src="item.foto" placeholder="https://ar.pinterest.com/pin/251638697914794219/https://i.pinimg.com/originals/b8/3e/c9/b83ec9d8ac7a6f2dfaa93fa4f150e3b6.gifhttps://i.pinimg.com/originals/76/47/bb/7647bb7539382dd708010625c4598021.gif"></b-image>
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