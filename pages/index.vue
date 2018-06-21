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
        <nuxt-link to="/index" class="navbar-item">소개</nuxt-link>
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
<article class="message">
      <div class="message-header">자기소개서</div>
      <div class="message-body"><p>안녕하세요?</p>
      <p>저, 임주찬은 현재 목원대학교 정보통신공학융합부 재학중이며 남다른 열정으로 사회에 이바지하고
         자 노력하는 사람입니다.</p> 
      <p>취미는 독서, 영화 시청입니다. 다른 사람과 소통을 하며 진실한 관계를 이어
            가는 것을 좋아합니다.</p>
			<p>무엇보다 제가 하는 일을 가장 좋아합니다. 저는 졸업작품에서 웹서버를 담당하고 있습니다.</p>
			<p>또한 도맡아 진행하고 있습니다. 다른 사람에게 저의 작업한 소스를 보여줄 수 
         있으며 무엇보다도</p>
			<p>개발자라는 직업을 통해 다른 사람에게 도움을 주는 일을 하고 싶습니다.</p>
   	  <p>무엇보다 항상 배움의 자세를 갖고 저 자신에게 부끄럽지 않은 사람이 되
         고자 노력하겠습니다.</p>
         <br>
         <div class="message-header">자기소개</div>
         
				<p>생년월일 : 1994년 08월 07일</p>
        <p>이름 : 임주찬</p>
				<p>사는 곳 : 대전광역시 유성구 봉명동</p>
				<p>이메일 : sa0466@nate.com</p>
       
        </div>
    </article>
  </section>
</template> 

<script>
export default {
 name: 'myApp',
 data() {
 return {};
  },
 asyncData() {
 return {};
  },
 methods: {
    fun() { return {}; }
  }
};
</script>
