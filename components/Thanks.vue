<template>
  <div class="thanks__container">
    <h2 class="thanks__title">
      Спасибо всем, кто помог состояться этому проекту
    </h2>
    <main-menu />
    <contacts />
  </div>
</template>

<script>
import Menu from '@/components/Menu';
import Contacts from '@/components/Contacts';
export default {
  components: {
    'main-menu': Menu,
    contacts: Contacts,
  },
};
</script>

<style scoped></style>
