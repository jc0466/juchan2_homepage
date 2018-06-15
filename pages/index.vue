<template> 
   <section class="hero is-link">
  <div class="hero-body">
    <div class="container">
      <h1 class="title">
       임주찬의 포트폴리오
      </h1>
    </div>
  </div>
  <div class="tabs is-toggle is-fullwidth">
  <ul>
    <li class="is-active">
      <a>
        <span>Pictures</span>
      </a>
    </li>
    <li>
      <a>
        <span>Music</span>
      </a>
    </li>
    <li>
      <a>
        <span>Videos</span>
      </a>
    </li>
    <li>
      <a>
        <span>Documents</span>
      </a>
    </li>
  </ul>
</div>
 </section>
</template> 
<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>