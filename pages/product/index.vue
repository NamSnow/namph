<template>
  <Card v-for="product in products" :key="product.name" :product="product" />
</template>

<script>
import Card from "~/components/Card.vue";

const products = ref([
  {
    image: "/home/sanpham-1.png",
    name: "ÁO PHÔNG GRAPHIC YOU CANT PLEASE ALL",
    price: "599.000 đ",
  },
  {
    image: "/home/sanpham-2.png",
    name: "  ÁO PHÔNG NỮ BABY TEE LOGO LOTSO",
    price: "499.000 đ",
  },
  {
    image: "/home/sanpham-3.png",
    name: "ÁO SƠ MI KẺ CARO ESSENTIAL OVERSIZED",
    price: "699.000 đ",
  },
  {
    image: "/home/sanpham-4.png",
    name: "ÁO KHOÁC CARDIGAN STICKER LOTSO",
    price: "1.299.000 đ",
  },
]);
</script>
