<script setup>
import Card from './Card.vue'

const onClickAdd = () => {
  alert('Добавить')
}
</script>

<template>
  <div class="grid grid-cols-3 gap-5">
    <Card
      image-url="/iphons/iPhone-15-pro.jpg"
      title="Apple iPhone 15 Pro 256GB Natural Titanium"
      price="58 499 ₴"
      :on-click-add="onClickAdd"
    />
    <Card
      image-url="/iphons/iphone-13-pink.png"
      title="Apple iPhone 13 128GB Pink"
      price="29 999 ₴"
      :on-click-add="onClickAdd"
    />
    <Card
      image-url="/iphons/iPhone132.jpg"
      title="Apple iPhone 13 128GB Midnight"
      price="29 999 ₴"
      :on-click-add="onClickAdd"
    />
    <Card
      image-url="/iphons/iPhone-14-pro.jpg"
      title="Apple iPhone 14 Pro 512GB Deep Purple"
      price="62 499 ₴"
      :on-click-add="onClickAdd"
    />
    <Card />
    <Card />
  </div>
</template>
