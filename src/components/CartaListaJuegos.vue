<template>
  <div class="row">
    <CartaJuegos
      v-for="(juego, index) in juegos"
      :key="index"
      :juego="juego"
      :index="index"
    />
    <ModalComments />
  </div>
</template>

<script>
import { mapState } from "vuex";

import CartaJuegos from "@/components/CartaJuegos";
import ModalComments from "@/components/ModalComments";

export default {
  name: "CartaListaJuegos",
  components: {
    CartaJuegos,
    ModalComments,
  },
  computed: {
    ...mapState(["juegos"]),
  },
};
</script>
