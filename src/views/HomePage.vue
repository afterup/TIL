<template>
  <div class="container">
    <header class="header">
      <img src="img/logo.png" alt="logo" class="logo" />
      <form action="#" class="search">
        <input type="text" class="search__input" placeholder="Search Tag" />
        <button class="search__button">
          <svg class="search__icon">
            <use xlink:href="img/sprite.svg#icon-magnifying-glass" />
          </svg>
        </button>
      </form>

      <nav class="nav">
        <ul class="nav__nav-group">
          <li class="nav__nav-item">Home</li>
          <li class="nav__nav-item">TIL</li>
          <li class="nav__nav-item">SignIn</li>
          <li class="nav__nav-item">SignUp</li>
        </ul>
        <div class="nav__user">
          <img src="img/user.jpg" alt="User photo" class="nav__user-photo" />
          <span class="nav__user-name">Jonas</span>
        </div>
      </nav>
    </header>

    <div class="banner">
      <h1>Today I Learned</h1>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorem atque st ullam</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'home',
  components: {},
};
</script>
