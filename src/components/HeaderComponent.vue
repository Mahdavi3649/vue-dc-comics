<template>
  <header>
    <div class="container">
      <div class="row">
        <div class="col-4">
          <img src="@/assets/img/dc-logo.png" alt="logo" />
        </div>
        <div class="col-8">
          <nav>
            <div class="main-menu">
              <a
                v-for="item in menu"
                :key="item.id"
                :href="item.href"
                :class="item.text === 'comics' ? 'active' : ''"
                >{{ item.text }}</a
              >
            </div>
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
    nav {
      height: 70px;
    }
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
  height: 70px;
}

.main-menu {
  a {
    list-style: none;
    text-decoration: none;
    padding: 27px 10px;
    text-transform: uppercase;
    color: $dc-dark;
    font-weight: 700;
    display: inline-block;
    font-size: 14px;

    .active {
      color: $dc-primary;
      border-bottom: 3px solid $dc-primary;
    }

    &:hover {
      color: $dc-primary;
      border-bottom: 3px solid $dc-primary;
    }
  }
}
</style>
