<template>
  <div class="flex justify-center items-center">
    <div class="rounded shadow-md p-2">
      Hello Tailwind
      <p>{{ msg }}</p>
    </div>
  </div>
</template>
<script lang="ts">
import { Vue } from 'vue-class-component';

export default class Login extends Vue {
  msg = 'Hello World'
}
</script>
