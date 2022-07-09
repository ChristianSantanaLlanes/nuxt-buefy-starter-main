<template>
    <div class="card">
        <div class="card-image">
            <b-image ratio="5by3" :src="item.foto">
                <template #placeholder>
                    <b-skeleton
                    class="skeleton-placeholder"
                    height="100%"></b-skeleton>
                </template>
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
                require: true
            },
        },
    }
</script>

<style lang="scss" scoped>

</style>