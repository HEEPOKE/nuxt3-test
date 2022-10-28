<template>
  <NavbarVue />
  <tableVue />
</template>
<script>
import NavbarVue from "../../components/navbar.vue";
import tableVue from "~~/components/store/table.vue";

export default {
  name: "IndexVue",
  components: {
    NavbarVue,
    tableVue,
  },
};
</script>
