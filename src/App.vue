<template>
  <section>
      <b-tabs v-model="activeTab" type="is-toggle">
          <b-tab-item label="Bücher" icon="bookshelf">
              Lorem ipsum dolor sit amet.
          </b-tab-item>

          <b-tab-item label="Buch suchen" icon="book-search">
              Lorem <br>
              ipsum <br>
              dolor <br>
              sit <br>
              amet.
          </b-tab-item>

          <b-tab-item label="Buch hinzufügen" icon="book-plus">
              What light is light, if Silvia be not seen? <br>
              What joy is joy, if Silvia be not by— <br>
              Unless it be to think that she is by <br>
              And feed upon the shadow of perfection? <br>
              Except I be by Silvia in the night, <br>
              There is no music in the nightingale.
          </b-tab-item>

          <b-tab-item label="Videos">
              Nunc nec velit nec libero vestibulum eleifend.
              Curabitur pulvinar congue luctus.
              Nullam hendrerit iaculis augue vitae ornare.
              Maecenas vehicula pulvinar tellus, id sodales felis lobortis eget.
          </b-tab-item>
      </b-tabs>
  </section>
</template>

<script>
  export default {
      data() {
          return {
              activeTab: 0,
              showBooks: false
          }
      }
  }
</script>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
