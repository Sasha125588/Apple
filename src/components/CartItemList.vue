<script setup>
import CartItem from './CartItem.vue'

const onClickAdd = () => {
  alert('Добавить')
}
</script>

<template>
  <div class="flex flex-col flex-1 gap-4">
    <CartItem />
    <CartItem />
    <CartItem />
  </div>
</template>
