<template>
  <div class="container font-josefinsans">
    <!--  -->
    <div class="header bg-colornew">
      <div class="banner p-4">
        <div class="container mx-auto">
          <div class="flex justify-between py-4">
            <div class="w-[350px] relative">
              <input
                type="search"
                class="w-full py-2 pl-3 pr-10 text-gray-700 focus:outline-none focus:ring border-b-2 border-gray-700 bg-transparent"
              />
              <img
                src="../public/icons/search.svg"
                alt=""
                class="absolute right-3 top-1/2 transform -translate-y-1/2 h-5 w-5 text-gray-400"
              />
            </div>
            <div class="h-8">
              <img src="/icon-b.png" alt="" class="h-full object-contain" />
            </div>
            <div
              class="flex items-center justify-end space-x-1 w-[350px] gap-[15px]"
            >
              <img src="../public/icons/account_circle.svg" alt="" />
              <img src="../public/icons/shopping_bag.svg" alt="" />
            </div>
          </div>

          <div class="py-4">
            <ul class="flex justify-center space-x-8">
              <li>
                <a href="#" class="text-gray-700 hover:text-blue-500"
                  >Trang chủ</a
                >
              </li>
              <li>
                <span
                  class="inline-block h-1 w-1 bg-amber-700 transform rotate-45 mr-2"
                ></span>
              </li>
              <li>
                <a href="#" class="text-gray-700 hover:text-blue-500"
                  >Về chúng tôi</a
                >
              </li>
              <li>
                <span
                  class="inline-block h-1 w-1 bg-amber-700 transform rotate-45 mr-2"
                ></span>
              </li>
              <li>
                <a href="#" class="text-gray-700 hover:text-blue-500"
                  >Sản phẩm</a
                >
              </li>
              <li>
                <span
                  class="inline-block h-1 w-1 bg-amber-700 transform rotate-45 mr-2"
                ></span>
              </li>
              <li>
                <a href="#" class="text-gray-700 hover:text-blue-500">Blog</a>
              </li>
              <li>
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

      <div class="container mx-auto flex items-center justify-between w-[80vw]">
        <img src="../public/boy-left-header.png" alt="" class="max-w-sm" />
        <div class="text-center">
          <div>
            <div class="text-sm">
              Giảm giá tới
              <span class="font-semibold text-brown-accent">40%</span>
            </div>
            <div
              class="text-[90px] font-bold text-brown-accent font-kaushan w-[583px] h-[130px] flex-shrink-0 t"
              style=""
            >
              Mùa hè
            </div>
          </div>
          <div class="text-sm mt-2">Chỉ Trong tuần này</div>
          <button
            class="bg-brown-accent hover:bg-brown-darker text-white font-bold py-2 px-4 rounded mt-4 text-sm"
          >
            Mua ngay
          </button>
        </div>
        <img src="../public/boy-right-header.png" alt="" class="max-w-sm" />
      </div>

      <div class="flex justify-center items-center my-2 gap-[45px] mt-[47px]">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="157"
          height="42"
          viewBox="0 0 157 42"
          fill="none"
        >
          <path
            d="M22.2457 11.6L31.094 20.5705L22.1235 29.4187L13.2753 20.4483L22.2457 11.6Z"
            fill="#CF9163"
          />
          <rect
            x="1.33539"
            y="0.5"
            width="41.0875"
            height="41"
            rx="20.5"
            stroke="#D9D9D9"
          />
          <path
            d="M84.9308 12L93.7791 20.9704L84.8086 29.8187L75.9604 20.8482L84.9308 12Z"
            fill="#D9D9D9"
          />
          <path
            d="M147.931 11.9999L156.779 20.9704L147.809 29.8186L138.961 20.8482L147.931 11.9999Z"
            fill="#D9D9D9"
          />
        </svg>
      </div>
    </div>

    <!--  -->
    <div class="banner mt-16 container">
      <div class="flex justify-between gap-[30px]">
        <div class="flex justify-between bg-gray-100 w-[690px] h-[430px]">
          <div class="mr-8 mt-16 ml-16">
            <div class="text-lg font-semibold text-gray-800">Sản phẩm</div>
            <div class="text-xl font-bold text-gray-900">Bán chạy nhất</div>
            <div class="text-sm text-gray-600">Tuần khuyến mại lớn</div>
            <button
              class="bg-brown-accent hover:bg-brown-darker text-white font-bold py-2 px-4 rounded mt-4 text-sm"
            >
              Mua ngay
            </button>
          </div>
          <img src="../public/girl-banner-left.png" alt="" class="max-w-sm" />
        </div>

        <div class="flex justify-between bg-gray-100 w-[690px] h-[430px]">
          <div class="mr-8 mt-16 ml-16">
            <div class="text-lg font-semibold text-gray-800">
              Bộ sưu tập mới
            </div>
            <div class="text-xl font-bold text-gray-900">Có sẵn ngay</div>
            <button
              class="bg-brown-accent hover:bg-brown-darker text-white font-bold py-2 px-4 rounded mt-4 text-sm"
            >
              Mua ngay
            </button>
          </div>
          <img src="../public/boy-banner-right.png" alt="" class="max-w-sm" />
        </div>
      </div>
    </div>

    <!--  -->
    <div class="mx-auto mt-8">
      <div class="mb-8 text-center">
        <h2 class="text-2xl font-bold text-gray-800 mb-2">Sản phẩm mới</h2>
        <div class="flex justify-center items-center mb-2 gap-[15px]">
          <img src="../public/icons/nexttrangsmall.svg" alt="" />
        </div>
        <p class="text-sm text-gray-600">
          Thời Trang Mới, Phong Cách Mới - Khám Phá Sản Phẩm Mới Để Tỏa Sáng
        </p>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <div
          class="bg-white overflow-hidden flex flex-col items-center pb-4 relative"
        >
          <img
            src="../public/sanpham-1.png"
            alt=""
            class="w-full h-auto object-cover"
          />
          <i
            class="fa-regular fa-heart absolute right-4 top-4 text-xl text-gray-500 hover:text-red-500 cursor-pointer"
          ></i>
          <div class="flex items-center gap-2 absolute bottom-4 left-4">
            <div
              class="w-6 h-6 bg-white border border-gray-300 cursor-pointer outline outline-1 outline-offset-1 outline-gray-400"
            ></div>
            <div
              class="w-6 h-6 bg-black border border-gray-300 cursor-pointer outline outline-1 outline-offset-1 outline-gray-400"
            ></div>
            <div
              class="w-6 h-6 bg-gray-400 border border-gray-300 cursor-pointer outline outline-1 outline-offset-1 outline-gray-400"
            ></div>
          </div>
          <div class="mt-5 text-center px-4">
            <h3 class="font-bold text-gray-800 mb-1">
              ÁO PHÔNG GRAPHIC YOU CAN'T PLEASE ALL
            </h3>
            <div class="text-[#CF9163] mb-1">599.000 đ</div>
            <div class="flex justify-center items-center gap-1">
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
            </div>
          </div>
        </div>

        <div
          class="bg-white overflow-hidden flex flex-col items-center pb-4 relative"
        >
          <img
            src="../public/sanpham-2.png"
            alt=""
            class="w-full h-auto object-cover"
          />
          <i
            class="fa-regular fa-heart absolute right-4 top-4 text-xl text-gray-500 hover:text-red-500 cursor-pointer"
          ></i>
          <div class="mt-5 text-center px-4">
            <h3 class="font-bold text-gray-800 mb-1">
              ÁO PHÔNG NỮ BABY TEE LOGO LOTSO
            </h3>
            <div class="text-[#CF9163] mb-1">499.000 đ</div>
            <div class="flex justify-center items-center gap-1">
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
            </div>
          </div>
        </div>

        <div
          class="bg-white overflow-hidden flex flex-col items-center pb-4 relative"
        >
          <img
            src="../public/sanpham-3.png"
            alt=""
            class="w-full h-auto object-cover"
          />
          <i
            class="fa-regular fa-heart absolute right-4 top-4 text-xl text-gray-500 hover:text-red-500 cursor-pointer"
          ></i>
          <div class="mt-5 text-center px-4">
            <h3 class="font-bold text-gray-800 mb-1">
              ÁO SƠ MI KẺ CARO ESSENTIAL OVERSIZED
            </h3>
            <div class="text-[#CF9163] mb-1">699.000 đ</div>
            <div class="flex justify-center items-center gap-1">
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
            </div>
          </div>
        </div>

        <div
          class="bg-white overflow-hidden flex flex-col items-center pb-4 relative"
        >
          <img
            src="../public/sanpham-4.png"
            alt=""
            class="w-full h-auto object-cover"
          />
          <i
            class="fa-regular fa-heart absolute right-4 top-4 text-xl text-gray-500 hover:text-red-500 cursor-pointer"
          ></i>
          <div class="mt-5 text-center px-4">
            <h3 class="font-bold text-gray-800 mb-1">
              MŨ DAD CAP THÊU LOGO MARVEL GO VN
            </h3>
            <div class="text-[#CF9163] mb-1">304.000 đ</div>
            <div class="flex justify-center items-center gap-1">
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
            </div>
          </div>
        </div>
      </div>

      <div class="flex justify-center items-center my-2 gap-[45px] mt-[47px]">
        <img src="../public/icons/nexttrangbig.svg" alt="" />
      </div>
    </div>

    <!--  -->
    <div class="bg-beige py-10">
      <div class="container mx-auto">
        <div class="mb-6 text-center">
          <h2 class="text-2xl font-bold text-dark">Ưu đãi trong ngày</h2>
          <div class="flex justify-center items-center my-2 gap-[15px]">
            <img src="../public/icons/nexttrangsmall.svg" alt="" />
          </div>
          <p class="text-sm text-gray-600">
            Duy Nhất Trong Hôm Nay, Ưu Đãi Không Thể Bỏ Lỡ
          </p>
        </div>

        <div class="flex justify-around gap-8">
          <div class="bg-white shadow-md overflow-hidden flex">
            <div class="p-6 flex-1">
              <h3 class="font-semibold text-gray-800 mb-2">
                ÁO PHÔNG LOGO KIND OF BASIC REGULAR
              </h3>
              <div
                class="text-gray-600 line-through mr-2 inline-block align-middle"
              >
                599.000 đ
              </div>
              <div class="text-brown-accent inline-block align-middle">
                304.000 đ
              </div>
              <div class="flex justify-between items-center mt-2">
                <div class="text-sm text-gray-600">13% đã bán</div>
                <div class="text-sm text-gray-600">Số lượng: 21</div>
              </div>
              <div class="bg-gray-200 rounded-full h-2 mt-2 relative">
                <div
                  class="bg-brown-accent rounded-full h-2 absolute left-0"
                  style="width: 13%"
                ></div>
              </div>
              <div class="flex text-xs text-gray-700 mt-4">
                <div class="text-center">
                  <span class="font-bold text-lg align-middle">00</span
                  ><br />Ngày
                </div>
                <div class="text-center pl-[20px]">
                  <span class="font-bold text-lg align-middle">00</span
                  ><br />Giờ
                </div>
                <div class="text-center pl-[20px]">
                  <span class="font-bold text-lg align-middle">00</span
                  ><br />Phút
                </div>
                <div class="text-center pl-[20px]">
                  <span class="font-bold text-lg align-middle">00</span
                  ><br />Giây
                </div>
              </div>
              <button
                class="bg-brown-accent hover:bg-brown-darker text-white font-semibold py-2 px-4 rounded-md mt-4 text-sm"
              >
                Thêm vào giỏ hàng
              </button>
            </div>
            <img
              src="../public/uudai-1.png"
              alt=""
              class="w-[210px] h-[290px] object-cover pr-[15px] py-[25px]"
            />
          </div>

          <div class="bg-white shadow-md overflow-hidden flex">
            <div class="p-6 flex-1">
              <h3 class="font-semibold text-gray-800 mb-2">
                QUẦN JOGGER PHỐI LINE BOOLAAB
              </h3>
              <div
                class="text-gray-600 line-through mr-2 inline-block align-middle"
              >
                899.000 đ
              </div>
              <div class="text-brown-accent inline-block align-middle">
                304.000 đ
              </div>
              <div class="flex justify-between items-center mt-2">
                <div class="text-sm text-gray-600">50% đã bán</div>
                <div class="text-sm text-gray-600">Số lượng: 15</div>
              </div>
              <div class="bg-gray-200 rounded-full h-2 mt-2 relative">
                <div
                  class="bg-brown-accent rounded-full h-2 absolute left-0"
                  style="width: 50%"
                ></div>
              </div>
              <div class="flex text-xs text-gray-700 mt-4">
                <div class="text-center">
                  <span class="font-bold text-lg align-middle">00</span
                  ><br />Ngày
                </div>
                <div class="text-center pl-[20px]">
                  <span class="font-bold text-lg align-middle">00</span
                  ><br />Giờ
                </div>
                <div class="text-center pl-[20px]">
                  <span class="font-bold text-lg align-middle">00</span
                  ><br />Phút
                </div>
                <div class="text-center pl-[20px]">
                  <span class="font-bold text-lg align-middle">00</span
                  ><br />Giây
                </div>
              </div>
              <button
                class="bg-brown-accent hover:bg-brown-darker text-white font-semibold py-2 px-4 rounded-md mt-4 text-sm"
              >
                Thêm vào giỏ hàng
              </button>
            </div>
            <img
              src="../public/uudai-2.png"
              alt=""
              class="w-[210px] h-[290px] object-cover pr-[15px] py-[25px]"
            />
          </div>
        </div>

        <div class="flex justify-center items-center my-2 gap-[45px] mt-[47px]">
          <img src="../public/icons/nexttrangbig.svg" alt="" />
        </div>
      </div>
    </div>

    <!--  -->
    <div class="flex gap-[30px] justify-center mt-[80px]">
      <div
        class="relative w-[450px] h-[323px] bg-light-bg flex flex-row-reverse"
      >
        <img
          src="../public/product-new1.png"
          alt=""
          class="w-1/2 h-full object-contain"
        />
        <div class="absolute left-0 pt-[30px] pl-[35px] gap-[10px]">
          <div class="text-xs text-gray-800 mb-1 underline">MUA NGAY</div>
          <div class="text-xl font-semibold text-gray-800">Xu hướng</div>
        </div>
      </div>
      <div
        class="relative w-[450px] h-[323px] bg-lightest flex flex-row-reverse"
      >
        <img
          src="../public/product-new2.png"
          alt=""
          class="w-1/2 h-full object-contain"
        />
        <div class="absolute left-0 pt-[30px] pl-[35px] gap-[10px]">
          <div class="text-xs text-gray-800 mb-1 underline">MUA NGAY</div>
          <div class="text-xl font-semibold text-gray-800">Mới</div>
        </div>
      </div>
      <div class="relative w-[450px] h-[323px] bg-light flex flex-row-reverse">
        <img
          src="../public/product-new3.png"
          alt=""
          class="w-1/2 h-full object-contain"
        />
        <div class="absolute left-0 pt-[30px] pl-[35px] gap-[10px]">
          <div class="text-xs text-gray-800 mb-1 underline">MUA NGAY</div>
          <div class="text-xl font-semibold text-gray-800">Giảm giá</div>
        </div>
      </div>
    </div>

    <!--  -->
    <div class="mx-auto mt-8">
      <div class="mb-8 text-center">
        <h2 class="text-2xl font-bold text-gray-800 mb-2">
          Sản phẩm bán chạy nhất
        </h2>
        <div class="flex justify-center items-center mb-2 gap-[15px]">
          <img src="../public/icons/nexttrangsmall.svg" alt="" />
        </div>
        <p class="text-sm text-gray-600">
          Tạo Nên Phong Cách Của Bạn - Sản Phẩm Đình Đám Trong Thời Trang!
        </p>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <div class="bg-white overflow-hidden flex flex-col items-center pb-4">
          <img
            src="../public/product-selling1.png"
            alt=""
            class="w-[330px] h-[462px] object-cover"
          />
          <div class="mt-5 text-center px-4">
            <h3 class="font-bold text-gray-800 mb-1">
              QUẦN JEANS LOGO ESSENTIAL RELAX
            </h3>
            <div class="text-[#CF9163] mb-1">799.000 ₫</div>
            <div class="flex justify-center items-center gap-1">
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
            </div>
          </div>
        </div>

        <div class="bg-white overflow-hidden flex flex-col items-center pb-4">
          <img
            src="../public/product-selling2.png"
            alt=""
            class="w-[330px] h-[462px] object-cover"
          />
          <div class="mt-5 text-center px-4">
            <h3 class="font-bold text-gray-800 mb-1">
              ÁO KHOÁC GIÓ IN LOGO ESSENTIAL BOMBER
            </h3>
            <div class="text-[#CF9163] mb-1">1.499.000 đ</div>
            <div class="flex justify-center items-center gap-1">
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
            </div>
          </div>
        </div>

        <div class="bg-white overflow-hidden flex flex-col items-center pb-4">
          <img
            src="../public/product-selling3.png"
            alt=""
            class="w-[330px] h-[462px] object-cover"
          />
          <div class="mt-5 text-center px-4">
            <h3 class="font-bold text-gray-800 mb-1">
              ÁO NỈ MŨ UN ESSENTIAL FALL BOOEST03
            </h3>
            <div class="text-[#CF9163] mb-1">427.000 đ</div>
            <div class="flex justify-center items-center gap-1">
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
            </div>
          </div>
        </div>

        <div class="bg-white overflow-hidden flex flex-col items-center pb-4">
          <img
            src="../public/product-selling4.png"
            alt=""
            class="w-[330px] h-[462px] object-cover"
          />
          <div class="mt-5 text-center px-4">
            <h3 class="font-bold text-gray-800 mb-1">
              MŨ DAD CAP THÊU LOGO MARVEL GO VN
            </h3>
            <div class="text-[#CF9163] mb-1">304.000 đ</div>
            <div class="flex justify-center items-center gap-1">
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
              <img src="../public/icons/star.svg" alt="" />
            </div>
          </div>
        </div>
      </div>

      <div class="flex justify-center items-center my-2 gap-[45px] mt-[47px]">
        <img src="../public/icons/nexttrangbig.svg" alt="" />
      </div>
    </div>

    <!--  -->
    <div class="bg-off-white py-[50px]">
      <div class="container mx-auto px-4">
        <div
          class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 text-center text-white"
        >
          <div class="flex flex-col items-center">
            <img
              src="../public/icons/truck1.svg"
              alt="Truck icon"
              class="w-14 h-14 mb-4"
            />
            <h3
              class="text-[16px] font-bold text-[#CF9163] mb-2 min-h-[30px] flex items-center justify-center"
            >
              GIAO HÀNG TOÀN CẦU
            </h3>
            <p class="text-[14px] text-gray-400 flex-grow">
              Hoạt động bằng 5 ngôn ngữ, chúng tôi giao hàng đến hơn 200 quốc
              gia và vùng lãnh thổ.
            </p>
          </div>

          <div class="flex flex-col items-center">
            <img
              src="../public/icons/unlock1.svg"
              alt="Unlock icon"
              class="w-14 h-14 mb-4"
            />
            <h3
              class="text-[16px] font-bold text-[#CF9163] mb-2 min-h-[30px] flex items-center justify-center"
            >
              GIAO HÀNG ĐẢM BẢO
            </h3>
            <p class="text-[14px] text-gray-400 flex-grow">
              Thanh toán bằng các phương thức thanh toán phổ biến và an toàn
              nhất trên thế giới.
            </p>
          </div>

          <div class="flex flex-col items-center">
            <img
              src="../public/icons/refresh-ccw1.svg"
              alt="Refresh icon"
              class="w-14 h-14 mb-4"
            />
            <h3
              class="text-[16px] font-bold text-[#CF9163] mb-2 min-h-[30px] flex items-center justify-center"
            >
              ĐỔI/TRẢ HÀNG TRONG VÒNG 365 NGÀY
            </h3>
            <p class="text-[14px] text-gray-400 flex-grow">
              Chúng tôi hỗ trợ 24/7 để mang lại trải nghiệm mua sắm trơn tru.
            </p>
          </div>

          <div class="flex flex-col items-center">
            <img
              src="../public/icons/shopping-bag1.svg"
              alt="Shopping bag icon"
              class="w-14 h-14 mb-4"
            />
            <h3
              class="text-[16px] font-bold text-[#CF9163] mb-2 min-h-[30px] flex items-center justify-center"
            >
              MUA HÀNG MỘT CÁCH TỰ TIN
            </h3>
            <p class="text-[14px] text-gray-400 flex-grow">
              Chính sách bảo vệ người mua bao gồm mọi giao dịch từ khi nhấp
              chuột đến khi nhận hàng.
            </p>
          </div>
        </div>
      </div>
    </div>

    <!--  -->
    <div>
      <img src="../public/insta11.png" alt="" />
      <img src="../public/insta21.png" alt="" />
      <img src="../public/insta31.png" alt="" />
      <img src="../public/insta41.png" alt="" />
      <img src="../public/insta51.png" alt="" />
      <img src="../public/insta71.png" alt="" />
    </div>
  </div>
</template>

<script>
import "@fortawesome/fontawesome-free/css/all.min.css";
</script>
