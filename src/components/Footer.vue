<template>
  <footer>
      <div class="foot">
      <div class="top container">
          <ul>
              <li class="title">dc comics</li>
              <li><a href="/">Characters</a></li>
              <li><a href="/">Comics</a></li>
              <li><a href="/">Movies</a></li>
              <li><a href="/">TV</a></li>
              <li><a href="/">Games</a></li>
              <li><a href="/">Videos</a></li>
              <li><a href="/">News</a></li>
              <li class="title">shop</li>
              <li><a href="/">Shop DC</a></li>
              <li><a href="/">Shop DC Collectibles</a></li>
          </ul>
          <ul>
              <li class="title">dc </li>
              <li><a href="/">Terms of use</a></li>
              <li><a href="/">Privacy policy (New)</a></li>
              <li><a href="/">Ad Choise</a></li>
              <li><a href="/">Advertising</a></li>
              <li><a href="/">Jobs</a></li>
              <li><a href="/">Subscriptions</a></li>
              <li><a href="/">Talent Workshop</a></li>
              <li><a href="/">CPSC Certificates</a></li>
              <li><a href="/">Ratings</a></li>
              <li><a href="/">Shop Help</a></li>
              <li><a href="/">Contact Us</a></li>
          </ul>
          <ul>
              <li class="title">sites</li>
              <li><a href="/">Characters</a></li>
              <li><a href="/">Comics</a></li>
              <li><a href="/">Movies</a></li>
              <li><a href="/">TV</a></li>

          </ul>
      </div>
      <div class="logo">
          <img src="../assets/img/dc-logo-bg.png" alt="">
      </div>
      </div>
        <!--FOOTER BOTTOM  -->
      <div class="foot-bot">
        <div class="bottom container">
            <div class="button">
                <h3>sign-up now!</h3>
            </div>
            <div class="social">
                <ul>
                    <li>follow us</li>
                    <li><a href="/"><img src="../assets/img/footer-facebook.png" alt=""></a></li>
                    <li><a href="/"><img src="../assets/img/footer-twitter.png" alt=""></a></li>
                    <li><a href="/"><img src="../assets/img/footer-youtube.png" alt=""></a></li>
                    <li><a href="/"><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
                    <li><a href="/"><img src="../assets/img/footer-periscope.png" alt=""></a></li>
                </ul>
            </div>
        </div>
      </div>
  </footer>
</template>

<script>
export default {
    name: 'Footer',
}
</script>

<style scope>

footer {
    background-image: url(../assets/img/footer-bg.jpg);
    color: #fff;
}

.foot {
    display: flex;
    justify-content: space-between;
}

.top {
    display: flex;
}

.top ul {
    margin-right: 50px;
}

.top li {
    margin-bottom: 10px;
}

a {
    color: #8e8e8e;
}

.title {
    font-weight: bold;
    text-transform: uppercase;
    font-size: 18px;
    padding: 20px 0;
}

/* FOOTER BOTTOM */

.foot-bot {
    background: #303030;
    padding: 30px;
}

.bottom {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.button h3{
    border: 2px solid dodgerblue;
    padding: 15px;
    text-transform: uppercase;
}

.social ul {
    display: flex;
    justify-content: center;
    align-items: center;
}

.social li {
    margin: 0 10px;
}

.social li:first-child {
    color: dodgerblue;
    font-weight: bold;
    text-transform: uppercase;
}

</style>