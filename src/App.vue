<template>
  <h1>
    {{ msg }}
  </h1>
  <div></div>
  <div></div>
  <img />
  <Hello />
</template>

<script>
import Hello from '~/components/Hello';

export default {
  components: {
    Hello
  },
  data() {
    return {
      msg: 'Hello Vue!'
    };
  },
};
</script>
