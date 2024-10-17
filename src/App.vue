<script>
import Avatar from "./components/Avatar.vue";
import Tarjeta from './components/Tarjeta.vue';

export default {
  components: {
    Avatar,
  },
};
</script>

<template>
  <div>
    <Avatar
      url="https://media.istockphoto.com/id/2015429231/vector/vector-flat-illustration-in-black-color-avatar-user-profile-person-icon-profile-picture.jpg?s=612x612&w=0&k=20&c=Wu70OARg2npxWy5E22_ZLneabuTafvV_6avgYPhWOoU="
      :tamaño="100"
    />
  </div>
  <Tarjeta nombre="Producto 1" descripcion="Esta es mi descripcion 1" />
    <Tarjeta nombre="Producto 2" descripcion="Esta es mi descripcion 2" />
</template>

<style scoped></style>

