<template>
  <div>
      <h1>Hello from Vue</h1>
      <Test />
  </div>
</template>

<script>
    import Test from './test.vue';
    export default {
        name: 'Main',
        components: {
            Test,
        },
    };
</script>