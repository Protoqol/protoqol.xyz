<template>
    <div>
        <Header/>
        <Home/>
    </div>
</template>

<script>
  import Home   from './components/Home.vue';
  import Header from './components/header/Header';

  export default {
    name      : 'app',
    components: {
      Header,
      Home,
    },
  };
</script>

<style>
    @import 'assets/styles/tailwind.postcss';
    @import url('https://fonts.googleapis.com/css?family=Lato&display=swap');

    * {
        font-family: 'Lato', sans-serif;
    }
</style>
