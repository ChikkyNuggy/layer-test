<script setup lang="ts">
import axios from 'axios';

const response = await axios.get('https://catfact.ninja/fact');

</script>

<template>
  <div>
    <h1>Hi this is my Cool Layer</h1>
    <pre>{{ response.data.fact }}</pre>
  </div>
</template>
