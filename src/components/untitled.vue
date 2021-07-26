<template>
  <carousel
    :nav="false"
    :dots="false"
    :loop="true"
    :autoplay="true"
    class="product-thumbs-track ps-slider"
  >
    <div
      class="pt"
      @click="changeImage(thumbs[0])"
      :class="thumbs[0] == photo ? 'active' : ''"
    >
      <img src="img/mickey1.jpg" alt="" />
    </div>

    <div
      class="pt"
      @click="changeImage(thumbs[1])"
      :class="thumbs[1] == photo ? 'active' : ''"
    >
      <img src="img/mickey2.jpg" alt="" />
    </div>

    <div
      class="pt"
      @click="changeImage(thumbs[2])"
      :class="thumbs[2] == photo ? 'active' : ''"
    >
      <img src="img/mickey3.jpg" alt="" />
    </div>

    <div
      class="pt"
      @click="changeImage(thumbs[3])"
      :class="thumbs[3] == photo ? 'active' : ''"
    >
      <img src="img/mickey4.jpg" alt="" />
    </div>
  </carousel>
</template>
