<template>
  <div class="flex justify-center items-center">
    <div class="rounded shadow-md p-2">
      Hello Tailwind
      <p>{{ msg }}</p>
    </div>
  </div>
  <Eye />
  <AdminImage />
</template>
<script lang="ts">
import { Options, Vue } from 'vue-class-component';

import Eye from '@/components/icons/Eye.vue';
import AdminImage from './AdminImage.vue';

@Options({
  components: {
    Eye,
    AdminImage,
  },
})
export default class Login extends Vue {
  msg = 'Hello World'
}
</script>
