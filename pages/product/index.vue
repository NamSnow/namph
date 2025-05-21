<template>
  <div class="container font-josefinsans">
    <!--  -->
    <div
      class="header bg-lightgray bg-center bg-cover bg-no-repeat"
      style="background-image: url('../../public/product/banner.png')"
    >
      <div class="banner p-4">
        <div class="container mx-auto">
          <div class="flex justify-between h-[60px] items-center">
            <div class="w-[350px] relative h-full">
              <input
                type="search"
                placeholder="Tìm kiếm"
                class="w-full h-full py-2 pl-3 pr-10 placeholder-gray-500 focus:outline-none focus:ring-1 focus:ring-brand-primary border-b-2 border-light-gray-text bg-transparent"
              />
              <img
                src="../../public/home/icons/search.svg"
                alt="Search"
                class="absolute right-3 top-1/2 transform -translate-y-1/2 h-5 w-5 text-gray-500 cursor-pointer"
              />
            </div>
            <div class="h-full flex items-center">
              <img
                src="../../public/home/icon-b.png"
                alt=""
                class="h-full object-contain"
              />
            </div>
            <div
              class="flex items-center justify-end space-x-1 w-[350px] gap-[15px]"
            >
              <img
                src="../../public/home/icons/account_circle.svg"
                alt=""
                class="cursor-pointer"
              />
              <div class="relative inline-block">
                <img
                  src="../../public/home/icons/shopping_bag.svg"
                  alt=""
                  class="cursor-pointer"
                />
                <div
                  class="w-[5px] h-[5px] rounded-full bg-brown-accent absolute right-[3px] top-0 flex items-center justify-center text-white text-[8px] font-bold"
                ></div>
              </div>
            </div>
          </div>

          <div class="py-4">
            <ul class="flex justify-center space-x-8 text-[26px]">
              <li>
                <a href="#" class="text-gray-700 hover:text-blue-500"
                  >Trang chủ</a
                >
              </li>
              <li class="flex items-center">
                <span
                  class="inline-block h-1 w-1 bg-amber-700 transform rotate-45 mr-2"
                ></span>
              </li>
              <li>
                <a href="#" class="text-gray-700 hover:text-blue-500"
                  >Về chúng tôi</a
                >
              </li>
              <li class="flex items-center">
                <span
                  class="inline-block h-1 w-1 bg-amber-700 transform rotate-45 mr-2"
                ></span>
              </li>
              <li>
                <a href="#" class="text-gray-700 hover:text-blue-500"
                  >Sản phẩm</a
                >
              </li>
              <li class="flex items-center">
                <span
                  class="inline-block h-1 w-1 bg-amber-700 transform rotate-45 mr-2"
                ></span>
              </li>
              <li>
                <a href="#" class="text-gray-700 hover:text-blue-500">Blog</a>
              </li>
              <li class="flex items-center">
                <span
                  class="inline-block h-1 w-1 bg-amber-700 transform rotate-45 mr-2"
                ></span>
              </li>
              <li>
                <a href="#" class="text-gray-700 hover:text-blue-500"
                  >Liên hệ</a
                >
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <!--  -->
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped></style>
