<template>
    <div>
      <TheHeader />
      <Nuxt />
      <TheFooter />
    </div>
</template>
  

<script>

    import TheHeader from '~/components/inc/TheHeader.vue';
    import TheFooter from '~/components/inc/TheFooter.vue';

    export default{
        name: 'default',
        components:{
            TheHeader,
            TheFooter,

        }
    }

</script>