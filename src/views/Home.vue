<template>
  <div>
    <h1>
      Welcome in NewsDesk
    </h1>
    <Newsfeed/>
  </div>
</template>

<script>
import Newsfeed from '@/components/newsfeed';

export default {
  name: 'Home',
  components: {
    Newsfeed
  }
};
</script>