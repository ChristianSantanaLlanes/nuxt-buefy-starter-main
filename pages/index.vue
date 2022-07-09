<template>
  <div>
    <section class="section">
      <p class="title has-text-centered">Christian Santana</p>
      <p class="subtitle has-text-centered">Desarrollador web</p>
    </section>
    <section class="section">
      <p class="subtitle has-text-centered">Mis trabajos</p>
      <div class="columns is-multiline">
        <div class="column is-4">
          <div class="card">
            <div class="card-image">
              <b-image src="https://picsum.photos/id/1074/800/400"
              placeholder="/assets/imgs/movieHero.jpg"
              ratop="2by1"></b-image>
            </div>
            <div class="card-content">
              <p class="title">Inicia el contenido</p>
            </div>
          </div>
        </div>
        <div class="column is-4">
          <div class="card">
            <div class="card-image">
              <b-image src="/static/product.png" ratio="2by1"></b-image>
            </div>
            <div class="card-content">
              <p class="title">Inicia el contenido</p>
            </div>
          </div>
        </div>
        <div class="column is-4">
          <div class="card">
            <div class="card-image">
                <b-image
                src="https://picsum.photos/id/1062/800/400"
                ratio="2by1"
                >
                <template #placeholder>
                    <b-skeleton
                        class="skeleton-placeholder"
                        height="100%"
                    ></b-skeleton>
                </template>
                </b-image>
            </div>
            <div class="card-content">
              <p class="title">Inicia el contenido</p>
            </div>
          </div>
        </div>
        <div class="column is-4">
          <div class="notification is-danger">Danger</div>
        </div>
        <div class="column is-4">
          <div class="notification is-warning">Warning</div>
        </div>
        <div class="column is-4">
          <div class="notification is-dark">Dark</div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  
}
</script>
