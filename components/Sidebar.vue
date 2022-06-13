<template>
  <div class="sidebar">
    <nuxt-link class="logo" to="/">
      <img src="@/assets/img/logo.svg" alt="logo" />
    </nuxt-link>
    <div class="nav">
      <a class="nav-link" href="#">
        <img src="@/assets/img/home.svg" alt="Home" />
        Home
      </a>
      <a class="nav-link" href="#">
        <img src="@/assets/img/discover.svg" alt="Explore" />
        Explore
      </a>
      <a class="nav-link" href="#">
        <img src="@/assets/img/notifications.svg" alt="notifications" />
        Notifications
      </a>
      <a class="nav-link" href="#">
        <img src="@/assets/img/messages.svg" alt="messages" />
        Messages
      </a>
      <a class="nav-link" href="#">
        <img src="@/assets/img/placemarks.svg" alt="Bookmarks" />
        Bookmarks
      </a>
      <a class="nav-link" href="#">
        <img src="@/assets/img/lists.svg" alt="lists" />
        Lists
      </a>
      <a class="nav-link" href="#">
        <img src="@/assets/img/profile.svg" alt="profile" />
        Profile
      </a>
      <a class="nav-link" href="#">
        <img src="@/assets/img/more.svg" alt="more" />
        More
      </a>
    </div>
    <div class="profile-button">
      Profile Button
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
@import '~/assets/scss/components/sidebar';
</style>