<template>
  <div>
    <section class="section">
      <p class="title has-text-centered">Christian Santana</p>
      <p class="subtitle has-text-centered">Desarrollador web</p>
    </section>
    <section class="section">
      <p class="title has-text-centered">Mis trabajos</p>
      <div class="columns is-multiline">
        <div v-for="(item, i) in trabajos" :key="i" class="column is-4">
            <PageCard :item="item"/>
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
                { foto: "https://picsum.photos/600/400", name: "Producto 1", descripcion: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad, eos autem! Eos, dolor, alias culpa ipsam earum repellat ipsum, fugit ab hic veritatis accusantium cupiditate atque magnam deleniti. Modi, molestias?' },
                { foto: "https://picsum.photos/600/400", name: "Producto 2", descripcion: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad, eos autem! Eos, dolor, alias culpa ipsam earum repellat ipsum, fugit ab hic veritatis accusantium cupiditate atque magnam deleniti. Modi, molestias?' },
                { foto: "https://picsum.photos/600/400", name: "Producto 3", descripcion: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad, eos autem! Eos, dolor, alias culpa ipsam earum repellat ipsum, fugit ab hic veritatis accusantium cupiditate atque magnam deleniti. Modi, molestias?' },
                { foto: "https://picsum.photos/600/400", name: "Producto 4", descripcion: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad, eos autem! Eos, dolor, alias culpa ipsam earum repellat ipsum, fugit ab hic veritatis accusantium cupiditate atque magnam deleniti. Modi, molestias?' },
                { foto: "https://picsum.photos/600/400", name: "Producto 5", descripcion: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad, eos autem! Eos, dolor, alias culpa ipsam earum repellat ipsum, fugit ab hic veritatis accusantium cupiditate atque magnam deleniti. Modi, molestias?' },
                { foto: "https://picsum.photos/600/400", name: "Producto 6", descripcion: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad, eos autem! Eos, dolor, alias culpa ipsam earum repellat ipsum, fugit ab hic veritatis accusantium cupiditate atque magnam deleniti. Modi, molestias?' },
            ]
        };
    },
}
</script>
