<template>
  <div
    class="bg-white overflow-hidden flex flex-col items-center pb-4 relative group"
  >
    <div class="relative w-full h-auto">
      <img
        :src="product.image"
        :alt="product.name"
        class="w-full h-auto object-cover"
      />
      <div
        class="absolute inset-0 bg-black opacity-0 group-hover:opacity-65 transition-opacity duration-300"
      ></div>
      <img
        src="/home/icons/heart.svg"
        alt="Add to wishlist"
        class="absolute right-4 top-4 w-6 h-6 cursor-pointer opacity-0 group-hover:opacity-100 transition-opacity duration-300 delay-100"
      />
      <div
        class="flex items-center gap-2 absolute bottom-[45px] opacity-0 group-hover:opacity-100 transition-opacity duration-300 delay-150 left-1/2 transform -translate-x-1/2"
      >
        <div
          v-for="(colorClass, index) in product.colors"
          :key="index"
          :class="[
            colorClass,
            'w-6 h-6 border border-gray-300 cursor-pointer outline outline-1 outline-offset-1 outline-gray-400',
          ]"
          @click="selectColor(colorClass)"
        ></div>
      </div>
    </div>
    <div class="mt-5 text-center px-4">
      <h3 class="font-bold text-gray-800 mb-1">
        {{ product.name }}
      </h3>
      <div class="text-[#CF9163] mb-1">{{ product.price }} đ</div>
      <div class="flex justify-center items-center gap-1">
        <img
          src="/home/icons/star.svg"
          alt="star"
          v-for="n in product.rating"
          :key="`filled-${n}`"
          class="w-4 h-4"
          style="
            filter: invert(79%) sepia(87%) saturate(542%) hue-rotate(359deg)
              brightness(103%) contrast(97%);
          "
        />
        <img
          src="/home/icons/star.svg"
          alt="empty star"
          v-for="n in 5 - product.rating"
          :key="`empty-${n}`"
          class="w-4 h-4"
          style="filter: grayscale(100%); opacity: 0.5"
        />
      </div>
    </div>
  </div>
</template>

<script setup>
const props = defineProps({
  product: {
    type: Object,
    required: true,
  },
});

const selectColor = (color) => {
  console.log(`Selected color for ${props.product.name}: ${color}`);
};
</script>
