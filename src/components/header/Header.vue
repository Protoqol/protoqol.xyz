<template>
    <div class="header-wrapper">
        <div class="left-side">
            <img alt="PROTOQOL" title="PROTOQOL" src="@/assets/img/logo.png"/>
            <h1>PROTOQOL.</h1>
            <!--            <ul>-->
            <!--                <li>-->
            <!--                    <a href="/">-->
            <!--                        PROTOQOL.-->
            <!--                    </a>-->
            <!--                </li>-->
            <!--                <li>-->
            <!--                    <a href="/open-source">-->
            <!--                        Open Source-->
            <!--                    </a>-->
            <!--                </li>-->
            <!--                <li>-->
            <!--                    <a href="/contact">-->
            <!--                        Contact-->
            <!--                    </a>-->
            <!--                </li>-->
            <!--            </ul>-->
        </div>
        <div class="right-side">
            <ul>
                <li>
                    <a target="_blank" href="https://github.com/Protoqol">
                        <img src="@/assets/img/social/github.png">
                    </a>
                </li>
                <li>
                    <a target="_blank" href="https://twitter.com/intent/follow?screen_name=Protoqol_XYZ">
                        <img src="@/assets/img/social/twitter.png">
                    </a>
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
  export default {
    name: 'Header',
  };
</script>

<style lang="scss" scoped>
    .header-wrapper {
        background-color: rgba(255, 255, 255, 0.975);
        @apply flex;
        @apply flex-row;
        @apply justify-between;
        @apply py-1;
        @apply px-3;
        @apply shadow-lg;

        .left-side {
            @apply w-1/2;
            @apply flex;
            @apply flex-row;
            @apply justify-start;
            @apply items-center;

            h1 {
                @apply text-black;
                @apply text-3xl;
                @apply font-semibold;
                @apply ml-2;
            }

            img {
                @apply w-24;
            }

            ul {
                @apply w-full;
                @apply flex;
                @apply flex-row;
                @apply justify-around;

                li {
                    color: #000;
                    @apply text-2xl;
                    @apply font-semibold;
                }
            }
        }

        .right-side {
            @apply w-1/6;
            @apply flex;
            @apply flex-row-reverse;
            @apply justify-end;
            @apply items-center;

            img {
                @apply w-8;
            }

            ul {
                @apply w-full;
                @apply flex;
                @apply flex-row;
                @apply justify-around;

                li {
                    color: #000;
                    @apply text-2xl;
                    @apply font-semibold;
                }
            }
        }
    }
</style>
