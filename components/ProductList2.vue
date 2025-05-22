<template>
  <Card v-for="product in products" :key="product.name" :product="product" />
</template>

<script setup>
const products = ref([
  {
    image: "/home/sanpham-5.png",
    name: "QUẦN JEANS LOGO ESSENTIAL RELAX",
    price: "799.000",
    rating: 1,
    colors: ["bg-white", "bg-black", "bg-gray-500"],
  },
  {
    image: "/home/sanpham-6.png",
    name: "ÁO KHOÁC GIÓ IN LOGO ESSENTIAL BOMBER",
    price: "1.499.000",
    rating: 1,
    colors: ["bg-white", "bg-black", "bg-gray-500"],
  },
  {
    image: "/home/sanpham-7.png",
    name: "ÁO NỈ MŨ UN ESSENTIAL FALL BOOEST03",
    price: "427.000",
    rating: 1,
    colors: ["bg-white", "bg-black", "bg-gray-500"],
  },
  {
    image: "/home/sanpham-8.png",
    name: "MŨ DAD CAP THÊU LOGO MARVEL GO VN",
    price: "304.000",
    rating: 1,
    colors: ["bg-white", "bg-black", "bg-gray-500"],
  },
]);
</script>
