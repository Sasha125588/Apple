<script setup>
import DrawerHead from './DrawerHead.vue'
import CartItemList from './CartItemList.vue'
</script>

<template>
  <div class="fixed top-0 left-0 h-full w-full bg-black z-10 opacity-70"></div>
  <div class="bg-white w-96 h-full fixed right-0 top-0 z-20 p-8">
    <DrawerHead />

    <CartItemList />

    <div class="flex flex-col gap-5 mt-7">
      <div class="flex gap-2">
        <span>Итого:</span>
        <div class="flex-1 borber-b border-dashed"></div>
        <b>58 499 ₴</b>
      </div>

      <div class="flex gap-2">
        <span>Налог 5%:</span>
        <div class="flex-1 borber-b border-dashed"></div>
        <b>2925 ₴</b>
      </div>

      <button
        disabled=""
        class="mt-3 transition bg-lime-500 w-full rounded-xl py-3 text-white disabled:bg-slate-400 hover:bg-lime-600 active:bg-lime-700 cursor-pointer"
      >
        Оформить Заказ
      </button>
    </div>
  </div>
</template>
