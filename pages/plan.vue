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
    <li>
      <a>
        <nuxt-link to="/index" class="navbar-item">자기소개서</nuxt-link>
      </a>
    </li>
    <li>
      <a>
        <nuxt-link to="/index" class="navbar-item">나의활동</nuxt-link>
      </a>
    </li>
    <li class="is-active">
      <a>
         <nuxt-link to="/plan" class="navbar-item">앞으로의 계획</nuxt-link>
      </a>
    </li>
  </ul>
</div>
  </div>
  <br>
  <br>
  <article class="message">
      <div class="message-header">앞으로의 계획</div>
  </article>
  <table class="table">
  <thead>
    <tr>
      <th><abbr title="Position">Pos</abbr></th>
      <th>Team</th>
      <th><abbr title="Played">Pld</abbr></th>
      <th><abbr title="Won">W</abbr></th>
      <th><abbr title="Drawn">D</abbr></th>
      <th><abbr title="Lost">L</abbr></th>
      <th><abbr title="Goals for">GF</abbr></th>
      <th><abbr title="Goals against">GA</abbr></th>
      <th><abbr title="Goal difference">GD</abbr></th>
      <th><abbr title="Points">Pts</abbr></th>
      <th>Qualification or relegation</th>
    </tr>
  </thead>
  </table>
 
    

  </section>
  </template>