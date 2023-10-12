<template>
  <LogIn />
</template>

<script>
import { defineComponent } from 'vue';

// Components
import LogIn from '../components/LogIn.vue';

export default defineComponent({
  name: 'LoginView',

  components: {
    LogIn,
  },
});
</script>
