<template>
  <header class="container">
      <div class="img">
            <img src="@/assets/img/dc-logo.png" alt="">
      </div>
      <div class="menu">
          <ul>
              <li v-for="(link, index) in links" :key="index" :class="{active: link.current}" ><a :class="{color: link.current}" :href="link.url">{{ link.text }}</a></li>
          </ul>
      </div>
  </header>
</template>

<script>
export default {
    name: 'Header',
    data() {
        return {
            links: [
                { text: 'characters', url: '/characters', current: false },
                { text: 'comics', url: '/comics', current: true },
                { text: 'movies', url: '/movies', current: false },
                { text: 'tv', url: '/tv', current: false },
                { text: 'games', url: '/games', current: false },
                { text: 'collectibles', url: '/collectibles', current: false },
                { text: 'videos', url: '/videos', current: false },
                { text: 'fans', url: '/fans', current: false },
                { text: 'news', url: '/news', current: false },
                { text: 'shop', url: '/shop', current: false },
            ],
        };
    },
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

a {
    color: #000;
}

.menu ul {
    display: flex;
    justify-content: center;
}

.menu li {
    margin-left: 20px;
}

.color {
    color: dodgerblue;
}

.active {
    border-bottom: 5px solid dodgerblue;
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