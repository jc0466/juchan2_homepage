<template> 
   <section class="hero is-link">
  <div class="hero-body">
    <div class="container">
      <h1 class="title">
       임주찬의 포트폴리오
      </h1>
    </div>
  </div>
  <section class="hero is-dark">
  <div class="tabs is-toggle is-fullwidth">
  <ul>
    <li class="is-active">
      <a>
        <span>자기소개서</span>
      </a>
    </li>
    <li>
      <a>
        <span>나의활동</span>
      </a>
    </li>
    <li>
      <a>
        <span>앞으로의 계획</span>
      </a>
    </li>
  </ul>
</div>   
  </section>
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