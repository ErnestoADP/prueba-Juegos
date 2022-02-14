<template>
  <div>
    <header class="container text-center py-5">
      <h1>Lista de Juegos Disponibles</h1>
    </header>
    <section class="container">
      <CartaListaJuegos />
    </section>
  </div>
</template>

<script>
import CartaListaJuegos from "@/components/CartaListaJuegos";

export default {
  name: "Home",
  components: {
    CartaListaJuegos,
  },
};
</script>
