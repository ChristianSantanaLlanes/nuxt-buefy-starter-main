<template>
  <div>
    <section class="section">
      <p class="title has-text-centered">Christian Santana</p>
      <p class="subtitle has-text-centered">Desarrollador web</p>
    </section>
    <section class="section">
      <p class="subtitle has-text-centered">Mis trabajos</p>
      <div class="columns is-multiline">
        <div v-for="(item, i) in trabajos" :key="i" class="column is-4">
          <div class="card">
            <div class="card-image">
                <b-image ratio="2by1" :src="item.foto">
                    <template #placeholder>
                        <b-skeleton
                        class="skeleton-placeholder"
                        height="100%"></b-skeleton>
                    </template>
                </b-image>
            </div>
            <div class="card-content">
                <nuxt-link to="/">{{item.name}}</nuxt-link>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
    data() {
        return {
            trabajos: [
                {foto: 'https://picsum.photos/600/400', name: 'Producto 1'},
                {foto: 'https://picsum.photos/600/400', name: 'Producto 2'},
                {foto: 'https://picsum.photos/600/400', name: 'Producto 3'},
                {foto: 'https://picsum.photos/600/400', name: 'Producto 4'},
                {foto: 'https://picsum.photos/600/400', name: 'Producto 5'},
                {foto: 'https://picsum.photos/600/400', name: 'Producto 6'},
            ]
        }
    },
}
</script>
