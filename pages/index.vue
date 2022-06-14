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
      </div>

      <div class="reply">
        <img src="~/assets/img/reply.svg" alt="" />Everyone can reply
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
        <button>
          <img src="~/assets/img/location.svg" alt="" />
        </button>
      </div>

      <div class="create-tweet">Tweet</div>
    </div>
  </div>
</template>

<script>
export default {
  layout: 'main',
}
</script>

