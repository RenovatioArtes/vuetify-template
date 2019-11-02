<template>
  <v-container>
    <v-layout text-center wrap>
      <p>{{ msg }}</p>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  name: "HelloWorld",
  props: ["msg"],
  data: () => ({
    ecosystem: []
  })
};
</script>
