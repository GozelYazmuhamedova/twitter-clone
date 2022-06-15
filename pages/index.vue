<template>
  <div class="tweet-flow">
    <header>
      <div class="header">
        <h2>Home</h2>
        <img src="~/assets/img/star.svg" alt="" />
      </div>
    </header>
    <div class="happening">
      <img src="~/assets/img/profile.jpg" alt="" />
      <div class="input">
        <input type="text" placeholder="What's happening?" />
        <div class="reply">
          <img src="~/assets/img/reply.svg" alt="" />Everyone can reply
        </div>
      </div>
    </div>
    <div class="buttons">
      <div>
        <button>
          <img src="~/assets/img/media.svg" alt="" />
        </button>
        <button>
          <img src="~/assets/img/gif.svg" alt="" />
        </button>
        <button>
          <img src="~/assets/img/poll.svg" alt="" />
        </button>
        <button>
          <img src="~/assets/img/emoji.svg" alt="" />
        </button>
        <button>
          <img src="~/assets/img/schedule.svg" alt="" />
        </button>
        <button class="disabled">
          <img src="~/assets/img/location.svg" alt="" />
        </button>
      </div>

      <div class="create-tweet">Tweet</div>
    </div>
    
    <div class="tweet-1">
      <div class="profile-button">
      <img class="profile-img" src="~/assets/img/profile.jpg" alt="" />
      <p><b>Andrew Johnson</b>    @andrewjhonson</p>
      <img class="profile-icon" src="~/assets/img/profile-button.svg" alt="" />
    </div>
   <p>
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quae, maiores
        aliquid. Laudantium repudiandae rerum est error cum excepturi, repellat
        illum, impedit accusantium, voluptate natus nam at temporibus? Hic,
        dignissimos voluptate.
      </p>
    <div class="tweet-flow-buttons">
      <button><img src="~/assets/img/tweet-reply.svg" alt="" /></button>
      <button><img src="~/assets/img/retweet.svg" alt="" /></button>
      <button><img src="~/assets/img/like.svg" alt="" /></button>
      <button><img src="~/assets/img/share.svg" alt="" /></button>
    </div>
    </div>
  </div>
</template>

<script>
export default {
  layout: 'main',
}
</script>

