<template>
  <main class="first-page">
    <img src="../../images/first/title.jpg">
    <ul>
      <li v-for="item in 6">
        <img src="">
        <p>瓷器</p>
      </li>
    </ul>
  </main>
</template>

<script>
  import Hello from '../../components/Hello.vue';

  export default {
    data () {
      return {
        button: {
          label: 'test1',
          disabled: {
            disabled: 'disabled'
          }
        }
      };

    },
    components: {
      Hello
    },
    methods: {
      hello () {
        console.log('1221');
      }
    }
  };
</script>
<style lang="scss" scoped>
  .div1{
    background-color : red;
  }
</style>
