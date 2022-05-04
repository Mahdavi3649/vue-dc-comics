<template>
  <header>
    <div class="container">
      <div class="row">
        <div class="col-4">
          <img src="@/assets/img/dc-logo.png" alt="logo" />
        </div>
        <div class="col-8">
          <nav>
            <ul>
              <li v-for="item in menu" :key="item.id">
                <a
                  :href="item.href"
                  :class="item.text === 'comics' ? 'active' : ''"
                  >{{ item.text }}</a
                >
              </li>
            </ul>
          </nav>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
  data() {
    return {
      menu: [
        {
          id: 1,
          href: "#",
          text: "characters",
        },
        {
          id: 2,
          href: "#",
          text: "comics",
        },
        {
          id: 3,
          href: "#",
          text: "movies",
        },
        {
          id: 4,
          href: "#",
          text: "tv",
        },
        {
          id: 5,
          href: "#",
          text: "games",
        },
        {
          id: 6,
          href: "#",
          text: "collectibles",
        },
        {
          id: 7,
          href: "#",
          text: "videos",
        },
        {
          id: 8,
          href: "#",
          text: "fans",
        },
        {
          id: 9,
          href: "#",
          text: "news",
        },
        {
          id: 10,
          href: "#",
          text: "shop",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
header {
  .container {
    margin: auto;
    width: 1300px;
  }

  .row {
    display: flex;
    align-items: center;
    justify-content: space-around;
  }
  img {
    width: 70px;
  }
}

nav {
  ul {
    list-style: none;

    li {
      display: inline-block;
      text-transform: uppercase;
      padding: 32px 10px;
      font-size: 14px;
      font-weight: 700;
      border-bottom: px solid transparent;

      &:hover {
        border-bottom: 3px solid $dc-primary;
      }

      a {
        text-decoration: none;
        color: $dc-dark;
      }
    }
  }
}

.active {
  color: blue;
}
</style>
