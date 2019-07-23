<template>
    <div class="home-wrapper">
        <h1>Following Protoqol.</h1>
        <h2>You might know us from</h2>

        <div class="content-wrapper">
            <link-prevue url="https://github.com/Protoqol/Prequel"></link-prevue>
            <link-prevue url="https://github.com/Protoqol/Quark"></link-prevue>
        </div>
    </div>
</template>

<script>
  import LinkPrevue from 'link-prevue';

  export default {
    name      : 'Home',
    components: {LinkPrevue},
  };
</script>

<style lang="scss" scoped>
    .home-wrapper {
        @apply m-10;
        @apply p-2;
        @apply text-black;

        h1 {
            text-shadow: 0 3px 4px rgba(0, 0, 0, .8);
            @apply text-center;
            @apply text-6xl;
            @apply text-white;
        }

        h2 {
            @apply text-center;
            @apply text-2xl;
            @apply text-gray-700;
            @apply italic;
        }

        .content-wrapper {
            @apply mt-10;
            @apply flex;
            @apply flex-row;
            @apply justify-around;
            @apply items-center;
        }
    }
</style>
