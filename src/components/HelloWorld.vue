<template>
  <v-container>
    <v-layout
      text-center
      wrap
    >
      <v-flex xs12>
        <v-img
          :src="require('../assets/logo.svg')"
          class="my-3"
          contain
          height="200"
        ></v-img>
      </v-flex>

      <v-flex mb-4>
        <h1 class="display-1 font-weight-light mb-3">
          ማዕበል ማዓልታዊ ዕቁብ
        </h1>
        <p class="subheading font-weight-regular">
          please register here
          <br>visit
          <a href="https://shuqbara.com" target="_blank">Shuqbara Community</a>
        </p>
      </v-flex>

    

  
    </v-layout>
  </v-container>
</template>

<script>
export default {
  name: 'HelloWorld',

  data: () => ({

  }),
};
</script>
