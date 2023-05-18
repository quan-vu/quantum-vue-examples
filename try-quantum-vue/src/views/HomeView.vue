<template>
  <div>
    <Heading :text="'Hello world'" />
  </div>
</template>

<script lang="ts">
import { Heading} from 'vue3-component-library-ts'; // Update the import path with the correct location and name of the component

export default {
  components: {
    Heading,
  },
};
</script>
