<template>
  <ul></ul>
</template>

<script>
export default {
  data() {
    return {
      storedResources: [
        {
          id: 'official-guide',
          title: 'Official Guide',
          description: 'The official Vue.js documentation.',
          link: 'https://vuejs.org'
        },
                {
          id: 'google',
          title: 'google',
          description: 'The official Google documentation.',
          link: 'https://google.com'
        },
      ],
    };
  },
};
</script>
