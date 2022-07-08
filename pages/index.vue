<template>
  <div>
    <section class="section">
      <section>
          <b-skeleton width="10%" :animated="animated"></b-skeleton>

          <b-skeleton width="20%" :animated="animated"></b-skeleton>

          <b-skeleton width="40%" :animated="animated"></b-skeleton>

          <b-skeleton width="50%" :animated="animated"></b-skeleton>

      </section>
    </section>
  </div>
</template>

<script>
export default {
  data() {
      return {
          animated: true
      }
  }
}
</script>
