<template>
<div class="wrapper">
    <top-nav></top-nav>
    <div class="post-wrapper">
      <posts></posts>
    </div>
  <site-footer></site-footer>
</div>
</template>

<script>
import topNav from '../components/topNav';
import siteFooter from '../components/siteFooter';
import posts from '../components/posts';

export default {
  name: 'articles',
  data() {
    return {};
  },
  components: {
    topNav,
    siteFooter,
    posts,
  },
  methods: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../stylesheets/primary";
.post-wrapper{
  padding-top: 6rem;
}
</style>
