<template>
  <div class="container">
    <div class="header" style="background-color: #d9d9d9">
      <div class="banner">
        <div class="">
          <div class="search">
            <input type="search" />
            <font-awesome-icon :icon="['fas', 'magnifying-glass']" />
          </div>
          <div class="">
            <img src="../public/Boolab Light Brown-06 1.png" alt="" />
          </div>
          <div>
            <font-awesome-icon :icon="['far', 'circle-user']" />
            <font-awesome-icon :icon="['fal', 'bag-shopping']" />
          </div>
        </div>

        <div class="">
          <ul class="flex">
            <li><a href="">Trang chủ</a></li>
            <li><a href="">Về chúng tôi</a></li>
            <li><a href="">Sản phẩm</a></li>
            <li><a href="">Blog</a></li>
            <li><a href="">Liên hệ</a></li>
          </ul>
        </div>

        <div class="flex">
          <img src="../public/boy-left1.png" alt="" />
          <div class="">
            <div class="">
              <div class="">Giảm giá tới <span>40%</span></div>
              <div class="">Mùa hè</div>
            </div>
            <div class="">Chỉ Trong tuần này</div>
            <button>Mua ngay</button>
          </div>
          <img src="../public/boy-right.png" alt="" />
        </div>

        <div class="flex">
          <span></span>
          <span></span>
          <span></span>
        </div>
      </div>
    </div>
  </div>
</template>
