<template>
  <div>
    <header class="container text-center py-5">
      <h1>Administrando la Lista de Opiniones</h1>
    </header>
    <section class="container">
      <TablaOpiniones />
    </section>
  </div>
</template>

<script>
import TablaOpiniones from "@/components/administration/TablaOpiniones";
export default {
  name: "Administracion",
  components: {
    TablaOpiniones,
  },
};
</script>
