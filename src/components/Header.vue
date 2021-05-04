<template>
  <header class="container">
      <div class="img">
            <img src="@/assets/img/dc-logo.png" alt="">
      </div>
      <div class="menu">
          <ul>
              <li><a href="/">characters</a></li>
              <li><a href="/">comics</a></li>
              <li><a href="/">movies</a></li>
              <li><a href="/">tv</a></li>
              <li><a href="/">games</a></li>
              <li><a href="/">collectibles</a></li>
              <li><a href="/">videos</a></li>
              <li><a href="/">fans</a></li>
              <li><a href="/">news</a></li>
              <li><a href="/">shop</a></li>
          </ul>
      </div>
  </header>
</template>

<script>
export default {
    name: 'Header',
}
</script>

<style scoped>

header {
    display: flex;
    justify-content: space-between;
    line-height: 150px;
    text-transform: uppercase;
    font-weight: bold;
    font-size: 13px;
}


.menu ul {
    display: flex;
    justify-content: center;
    list-style: none;
}

.menu li {
    margin-left: 20px;
}

.menu li:nth-child(2) {
    border-bottom: 5px solid blue;
}

.img {
    display: flex;
    align-items: center;
}

.img img  {
    width: 80px;
    height: 80px;
}

</style>