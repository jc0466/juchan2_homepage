<template> 

   <section class="hero is-link">
  <div class="hero-body">
    <div class="container">
      <h1 class="title">
       임주찬의 포트폴리오
      </h1>
    </div>
  </div>
 <div class="hero is-dark">
  <div class="tabs is-toggle is-fullwidth">
  <ul>
    <li class="is-active">
      <a>
        <nuxt-link to="/index" class="navbar-item">자기소개서</nuxt-link>
      </a>
    </li>
    <li>
      <a>
        <nuxt-link to="/about" class="navbar-item">나의활동</nuxt-link>
      </a>
    </li>
    <li>
      <a>
        <nuxt-link to="/plan" class="navbar-item">앞으로의 계획</nuxt-link>
      </a>
    </li>
  </ul>
</div>
  </div>
   <div class="tile is-parent"> 
          <figure class="image is-128x128">
            <img src="my.png" alt="">
          </figure>
      </div>
<br>
<br>
<article class="message">
      <div class="message-header">자기소개서</div>
      <div class="message-body">나는 임주찬입니다.</div>
    </article>
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
