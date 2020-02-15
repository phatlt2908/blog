<template>
  <div class="row">
    <div class="col-lg-8 col-md-10 mx-auto">
      <!-- Home Post List -->
      <article class="post-preview">
        <!-- <a href="#" class="post-meta">Game</a> -->
        <a href="#">
          <h2 class="post-title">Man must explore, and this is exploration at its greatest</h2>
          <h3 class="post-subtitle">Problems look mighty small from 150 miles up</h3>
        </a>
        <p class="post-meta">Posted by Start Bootstrap on October 31, 2017 · <span class="reading-time">4 mins read</span></p>
      </article>
      <hr>
      <article class="post-preview">
        <!-- <a href="#" class="post-meta">Phim ảnh</a> -->
        <a href="#">
          <h2 class="post-title">Man must explore, and this is exploration at its greatest</h2>
          <h3 class="post-subtitle">Problems look mighty small from 150 miles up</h3>
        </a>
        <p class="post-meta">Posted by Start Bootstrap on October 31, 2017 · <span class="reading-time">4 mins read</span></p>
      </article>
      <hr>
      <article class="post-preview">
        <!-- <a href="#" class="post-meta">Phim ảnh</a> -->
        <a href="#">
          <h2 class="post-title">Man must explore, and this is exploration at its greatest</h2>
          <h3 class="post-subtitle">Problems look mighty small from 150 miles up</h3>
        </a>
        <p class="post-meta">Posted by Start Bootstrap on October 31, 2017 · <span class="reading-time">4 mins read</span></p>
      </article>
    </div>


    <!-- <div v-show="isLoading">
      <dotLoading></dotLoading>
    </div> -->
    
  </div>
</template>

<script>

// import dotLoading from '@/components/block/dotLoading'

export default {
  name: 'HomePage',
  components: {
    // 'dotLoading': dotLoading
  },

  data () {
    return {
      isLoading: false
    }
  },

  created() {
    this.getList()
  },

  methods: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
