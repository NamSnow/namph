<template>
  <div class="container font-josefinsans">
    <!--  -->
    <div class="header bg-colornew">
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
                src="../public/home/icons/search.svg"
                alt="Search"
                class="absolute right-3 top-1/2 transform -translate-y-1/2 h-5 w-5 text-gray-500 cursor-pointer"
              />
            </div>
            <div class="h-full flex items-center">
              <img
                src="../public/home/icon-b.png"
                alt=""
                class="h-full object-contain"
              />
            </div>
            <div
              class="flex items-center justify-end space-x-1 w-[350px] gap-[15px]"
            >
              <img
                src="../public/home/icons/account_circle.svg"
                alt=""
                class="cursor-pointer"
              />
              <div class="relative inline-block">
                <img
                  src="../public/home/icons/shopping_bag.svg"
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

      <div
        class="container mx-auto flex items-center justify-between w-viewport-80"
      >
        <img src="../public/home/boy-left-header.png" alt="" class="max-w-sm" />
        <div class="text-center">
          <div>
            <div class="text-[32px]">
              Giảm giá tới
              <span class="font-semibold text-brown-accent">40%</span>
            </div>
            <div
              class="text-[90px] font-bold text-brown-accent font-kaushan w-[583px] h-[130px] flex-shrink-0 t"
            >
              Mùa hè
            </div>
          </div>
          <div class="text-[32px] mt-2">Chỉ Trong tuần này</div>
          <button
            class="bg-brown-accent hover:bg-brown-darker text-white font-bold py-2 px-4 rounded mt-4 text-sm"
          >
            Mua ngay
          </button>
          <div
            class="flex justify-center items-center my-2 gap-[15px] mt-[180px]"
          >
            <div class="relative flex items-center justify-center w-16 h-16">
              <div
                class="w-full h-full border border-gray-300 rounded-full"
              ></div>
              <div
                class="w-4 h-4 transform rotate-45 bg-brown-accent absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 cursor-pointer"
              ></div>
            </div>

            <div class="relative flex items-center justify-center w-16 h-16">
              <div
                class="w-4 h-4 transform rotate-45 bg-silver cursor-pointer"
              ></div>
            </div>

            <div class="relative flex items-center justify-center w-16 h-16">
              <div
                class="w-4 h-4 transform rotate-45 bg-silver cursor-pointer"
              ></div>
            </div>
          </div>
        </div>
        <img
          src="../public/home/boy-right-header.png"
          alt=""
          class="max-w-sm"
        />
      </div>
    </div>

    <!--  -->
    <div class="banner mt-16 container w-viewport-80 mx-auto">
      <div class="flex justify-between gap-[30px]">
        <div class="flex justify-between bg-gray-100 w-[690px] h-[430px]">
          <div class="mr-8 mt-16 ml-16">
            <div class="text-[30px] font-semibold text-gray-800">Sản phẩm</div>
            <div class="text-[30px] font-bold text-gray-900">Bán chạy nhất</div>
            <div class="text-sm text-gray-600">Tuần khuyến mại lớn</div>
            <button
              class="bg-brown-accent hover:bg-brown-darker text-white font-bold py-2 px-4 rounded mt-4 text-sm"
            >
              Mua ngay
            </button>
          </div>
          <img
            src="../public/home/girl-banner-left.png"
            alt=""
            class="max-w-sm"
          />
        </div>

        <div class="flex justify-between bg-gray-100 w-[690px] h-[430px]">
          <div class="mr-8 mt-16 ml-16">
            <div class="text-[30px] font-semibold text-gray-800">
              Bộ sưu tập mới
            </div>
            <div class="text-sm text-gray-600">Có sẵn ngay</div>
            <button
              class="bg-brown-accent hover:bg-brown-darker text-white font-bold py-2 px-4 rounded mt-4 text-sm"
            >
              Mua ngay
            </button>
          </div>
          <img
            src="../public/home/boy-banner-right.png"
            alt=""
            class="max-w-sm"
          />
        </div>
      </div>
    </div>

    <!--  -->
    <div class="mx-auto mt-8 w-viewport-80 text-center">
      <div class="mb-8 text-center">
        <h2 class="text-2xl font-bold text-gray-800 mb-2">Sản phẩm mới</h2>
        <div class="flex justify-center items-center mb-2 gap-[15px]">
          <img src="../public/home/icons/nexttrangsmall.svg" alt="" />
        </div>
        <p class="text-sm text-gray-600">
          Thời Trang Mới, Phong Cách Mới - Khám Phá Sản Phẩm Mới Để Tỏa Sáng
        </p>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <div
          class="bg-white overflow-hidden flex flex-col items-center pb-4 relative group"
        >
          <div class="relative w-full h-auto">
            <img
              src="../public/home/sanpham-1.png"
              alt=""
              class="w-full h-auto object-cover"
            />

            <div
              class="absolute inset-0 bg-black opacity-0 group-hover:opacity-65 transition-opacity duration-300"
            ></div>

            <img
              src="../public/home/icons/heart.svg"
              alt=""
              class="absolute right-4 top-4 text-xl cursor-pointer opacity-0 group-hover:opacity-100 transition-opacity duration-300 delay-100"
            />

            <div
              class="flex items-center gap-2 absolute bottom-[45px] opacity-0 group-hover:opacity-100 transition-opacity duration-300 delay-150 left-1/2 transform -translate-x-1/2"
            >
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
          </div>

          <div class="mt-5 text-center px-4">
            <h3 class="font-bold text-gray-800 mb-1">
              ÁO PHÔNG GRAPHIC YOU CAN'T PLEASE ALL
            </h3>
            <div class="text-[#CF9163] mb-1">599.000 đ</div>
            <div class="flex justify-center items-center gap-1">
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
            </div>
          </div>
        </div>

        <div
          class="bg-white overflow-hidden flex flex-col items-center pb-4 relative group"
        >
          <div class="relative w-full h-auto">
            <img
              src="../public/home/sanpham-2.png"
              alt=""
              class="w-full h-auto object-cover"
            />
            <div
              class="absolute inset-0 bg-black opacity-0 group-hover:opacity-65 transition-opacity duration-300"
            ></div>
            <img
              src="../public/home/icons/heart.svg"
              alt=""
              class="absolute right-4 top-4 text-xl cursor-pointer opacity-0 group-hover:opacity-100 transition-opacity duration-300 delay-100"
            />
            <div
              class="flex items-center gap-2 absolute bottom-[45px] opacity-0 group-hover:opacity-100 transition-opacity duration-300 delay-150 left-1/2 transform -translate-x-1/2"
            >
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
          </div>
          <div class="mt-5 text-center px-4">
            <h3 class="font-bold text-gray-800 mb-1">
              ÁO PHÔNG NỮ BABY TEE LOGO LOTSO
            </h3>
            <div class="text-[#CF9163] mb-1">499.000 đ</div>
            <div class="flex justify-center items-center gap-1">
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
            </div>
          </div>
        </div>

        <div
          class="bg-white overflow-hidden flex flex-col items-center pb-4 relative group"
        >
          <div class="relative w-full h-auto">
            <img
              src="../public/home/sanpham-3.png"
              alt=""
              class="w-full h-auto object-cover"
            />
            <div
              class="absolute inset-0 bg-black opacity-0 group-hover:opacity-65 transition-opacity duration-300"
            ></div>
            <img
              src="../public/home/icons/heart.svg"
              alt=""
              class="absolute right-4 top-4 text-xl cursor-pointer opacity-0 group-hover:opacity-100 transition-opacity duration-300 delay-100"
            />
            <div
              class="flex items-center gap-2 absolute bottom-[45px] opacity-0 group-hover:opacity-100 transition-opacity duration-300 delay-150 left-1/2 transform -translate-x-1/2"
            >
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
          </div>
          <div class="mt-5 text-center px-4">
            <h3 class="font-bold text-gray-800 mb-1">
              ÁO SƠ MI KẺ CARO ESSENTIAL OVERSIZED
            </h3>
            <div class="text-[#CF9163] mb-1">699.000 đ</div>
            <div class="flex justify-center items-center gap-1">
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
            </div>
          </div>
        </div>

        <div
          class="bg-white overflow-hidden flex flex-col items-center pb-4 relative group"
        >
          <div class="relative w-full h-auto">
            <img
              src="../public/home/sanpham-4.png"
              alt=""
              class="w-full h-auto object-cover"
            />
            <div
              class="absolute inset-0 bg-black opacity-0 group-hover:opacity-65 transition-opacity duration-300"
            ></div>
            <img
              src="../public/home/icons/heart.svg"
              alt=""
              class="absolute right-4 top-4 text-xl cursor-pointer opacity-0 group-hover:opacity-100 transition-opacity duration-300 delay-100"
            />
            <div
              class="flex items-center gap-2 absolute bottom-[45px] opacity-0 group-hover:opacity-100 transition-opacity duration-300 delay-150 left-1/2 transform -translate-x-1/2"
            >
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
          </div>
          <div class="mt-5 text-center px-4">
            <h3 class="font-bold text-gray-800 mb-1">
              MŨ DAD CAP THÊU LOGO MARVEL GO VN
            </h3>
            <div class="text-[#CF9163] mb-1">304.000 đ</div>
            <div class="flex justify-center items-center gap-1">
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
            </div>
          </div>
        </div>
      </div>

      <div class="flex justify-center items-center my-2 gap-[45px] mt-[47px]">
        <img src="../public/home/icons/nexttrangbig.svg" alt="" />
      </div>
    </div>

    <!--  -->
    <div class="bg-beige pt-10 text-center">
      <div class="container mx-auto">
        <div class="mb-6 text-center">
          <h2 class="text-2xl font-bold text-dark">Ưu đãi trong ngày</h2>
          <div class="flex justify-center items-center my-2 gap-[15px]">
            <img src="../public/home/icons/nexttrangsmall.svg" alt="" />
          </div>
          <p class="text-sm text-gray-600">
            Duy Nhất Trong Hôm Nay, Ưu Đãi Không Thể Bỏ Lỡ
          </p>
        </div>

        <div class="flex justify-around gap-[30px] w-viewport-80 mx-auto">
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
                  class="bg-brown-accent rounded-full h-2 absolute left-0 w-[13%]"
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
              src="../public/home/uudai-1.png"
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
                  class="bg-brown-accent rounded-full h-2 absolute left-0 w-[50%]"
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
              src="../public/home/uudai-2.png"
              alt=""
              class="w-[210px] h-[290px] object-cover pr-[15px] py-[25px]"
            />
          </div>
        </div>

        <div class="flex justify-center items-center my-2 gap-[45px] mt-[47px]">
          <img
            src="../public/home/icons/nexttrangbig.svg"
            alt=""
            class="mb-[70px]"
          />
        </div>
      </div>
    </div>

    <!--  -->
    <div class="flex gap-[30px] justify-center mt-[80px] w-viewport-80 mx-auto">
      <div
        class="relative w-[450px] h-[323px] bg-light-bg flex flex-row-reverse"
      >
        <img
          src="../public/home/product-new1.png"
          alt=""
          class="w-1/2 h-full object-cover"
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
          src="../public/home/product-new2.png"
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
          src="../public/home/product-new3.png"
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
    <div class="mx-auto mt-8 w-viewport-80 text-center">
      <div class="mb-8 text-center">
        <h2 class="text-2xl font-bold text-gray-800 mb-2">
          Sản phẩm bán chạy nhất
        </h2>
        <div class="flex justify-center items-center mb-2 gap-[15px]">
          <img src="../public/home/icons/nexttrangsmall.svg" alt="" />
        </div>
        <p class="text-sm text-gray-600">
          Tạo Nên Phong Cách Của Bạn - Sản Phẩm Đình Đám Trong Thời Trang!
        </p>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <div class="bg-white overflow-hidden flex flex-col items-center pb-4">
          <img
            src="../public/home/product-selling1.png"
            alt=""
            class="w-[330px] h-[462px] object-cover"
          />
          <div class="mt-5 text-center px-4">
            <h3 class="font-bold text-gray-800 mb-1">
              QUẦN JEANS LOGO ESSENTIAL RELAX
            </h3>
            <div class="text-[#CF9163] mb-1">799.000 ₫</div>
            <div class="flex justify-center items-center gap-1">
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
            </div>
          </div>
        </div>

        <div class="bg-white overflow-hidden flex flex-col items-center pb-4">
          <img
            src="../public/home/product-selling2.png"
            alt=""
            class="w-[330px] h-[462px] object-cover"
          />
          <div class="mt-5 text-center px-4">
            <h3 class="font-bold text-gray-800 mb-1">
              ÁO KHOÁC GIÓ IN LOGO ESSENTIAL BOMBER
            </h3>
            <div class="text-[#CF9163] mb-1">1.499.000 đ</div>
            <div class="flex justify-center items-center gap-1">
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
            </div>
          </div>
        </div>

        <div class="bg-white overflow-hidden flex flex-col items-center pb-4">
          <img
            src="../public/home/product-selling3.png"
            alt=""
            class="w-[330px] h-[462px] object-cover"
          />
          <div class="mt-5 text-center px-4">
            <h3 class="font-bold text-gray-800 mb-1">
              ÁO NỈ MŨ UN ESSENTIAL FALL BOOEST03
            </h3>
            <div class="text-[#CF9163] mb-1">427.000 đ</div>
            <div class="flex justify-center items-center gap-1">
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
            </div>
          </div>
        </div>

        <div class="bg-white overflow-hidden flex flex-col items-center pb-4">
          <img
            src="../public/home/product-selling4.png"
            alt=""
            class="w-[330px] h-[462px] object-cover"
          />
          <div class="mt-5 text-center px-4">
            <h3 class="font-bold text-gray-800 mb-1">
              MŨ DAD CAP THÊU LOGO MARVEL GO VN
            </h3>
            <div class="text-[#CF9163] mb-1">304.000 đ</div>
            <div class="flex justify-center items-center gap-1">
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
              <img src="../public/home/icons/star.svg" alt="" />
            </div>
          </div>
        </div>
      </div>

      <div class="flex justify-center items-center my-2 gap-[45px] mt-[47px]">
        <img src="../public/home/icons/nexttrangbig.svg" alt="" />
      </div>
    </div>

    <!--  -->
    <div class="bg-off-white pt-[50px] text-center mx-auto">
      <div class="container mx-auto px-4 w-viewport-80">
        <div
          class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 text-center text-white"
        >
          <div class="flex flex-col items-center">
            <img
              src="../public/home/icons/truck1.svg"
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
              src="../public/home/icons/unlock1.svg"
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
              src="../public/home/icons/refresh-ccw1.svg"
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
              src="../public/home/icons/shopping-bag1.svg"
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
    <div class="flex w-full py-[30px] gap-[30px] overflow-x-auto justify-start">
      <img
        src="../public/home/insta11.png"
        alt=""
        class="w-[310px] h-[305px] flex-shrink-0"
      />
      <img
        src="../public/home/insta21.png"
        alt=""
        class="w-[310px] h-[305px] flex-shrink-0"
      />
      <img
        src="../public/home/insta31.png"
        alt=""
        class="w-[310px] h-[305px] flex-shrink-0"
      />
      <img
        src="../public/home/insta41.png"
        alt=""
        class="w-[310px] h-[305px] flex-shrink-0"
      />
      <img
        src="../public/home/insta51.png"
        alt=""
        class="w-[310px] h-[305px] flex-shrink-0"
      />
      <img
        src="../public/home/insta71.png"
        alt=""
        class="w-[310px] h-[305px] flex-shrink-0"
      />
    </div>

    <!--  -->
    <div
      class="flex flex-col items-center justify-center py-16 px-4 bg-[#F2F2F2] text-center"
    >
      <div
        class="text-[#B28A6B] text-base md:text-lg font-bold uppercase tracking-widest mb-2"
      >
        Thư thông báo
      </div>
      <div
        class="text-[#524B46] text-3xl md:text-5xl font-bold mb-4 leading-tight"
      >
        Nhận giảm giá 30%
      </div>
      <div class="text-[#888888] text-sm md:text-base mb-8 max-w-md">
        30% off trên toàn bộ đơn hàng của bạn khi nhập mã khuyến mãi.
      </div>
      <div
        class="flex flex-col md:flex-row items-center w-full max-w-lg px-4 md:px-0"
      >
        <input
          type="email"
          placeholder="Nhập Email của bạn..."
          class="w-full md:flex-grow p-3 border border-[#E0E0E0] focus:outline-none focus:ring-2 focus:ring-[#B28A6B] mb-4 md:mb-0 text-[#524B46] placeholder-[#AAAAAA]"
        />
        <button
          class="w-full md:w-auto px-8 py-3 bg-[#B28A6B] text-white font-bold hover:bg-[#A37B5C] transition-colors duration-300 whitespace-nowrap"
        >
          Đăng ký
        </button>
      </div>
    </div>

    <!--  -->
    <div class="w-viewport-80 mx-auto">
      <div
        class="flex flex-col md:flex-row justify-around items-start md:items-start p-8 bg-white text-[#524B46]"
      >
        <div
          class="flex flex-col items-center text-center pb-8 md:pb-0 md:border-r md:border-gray-200 md:pr-12 lg:pr-24"
        >
          <div class="font-bold text-lg mb-4 text-[#524B46] relative">
            <span
              class="absolute -left-3 top-1/2 -translate-y-1/2 w-1.5 h-1.5 bg-[#B28A6B] rounded-full"
            ></span>
            Khách hàng
          </div>
          <ul class="space-y-2">
            <li>
              <a href="#" class="text-sm hover:text-[#B28A6B]"
                >Vận chuyển & Đổi/trả hàng</a
              >
            </li>
            <li>
              <a href="#" class="text-sm hover:text-[#B28A6B]"
                >Mua sắm an toàn</a
              >
            </li>
            <li>
              <a href="#" class="text-sm hover:text-[#B28A6B]"
                >Trạng thái đơn hàng</a
              >
            </li>
            <li>
              <a href="#" class="text-sm hover:text-[#B28A6B]"
                >Vận chuyển quốc tế</a
              >
            </li>
          </ul>
        </div>

        <div
          class="flex flex-col items-center text-center px-4 md:px-8 mb-8 md:mb-0 md:border-r md:border-gray-200 md:pr-12 lg:pr-24"
        >
          <div class="mb-4">
            <img src="../public/home/icon-b.png" alt="BCO Logo" class="h-16" />
          </div>
          <div class="text-sm leading-relaxed mb-6 max-w-xs">
            Khám phá phong cách mới tại cửa hàng Nơi mua sắm độc đáo và thú vị!
          </div>
          <div class="flex space-x-[10px] gap-[10px]">
            <div
              class="w-[38px] h-[38px] transform rotate-45 bg-[#212121] flex justify-center items-center shadow-md hover:bg-[#B28A6B] transition-colors duration-300"
            >
              <img
                src="../public/home/icons/facebook.svg"
                alt="Facebook"
                class="transform -rotate-45 w-5 h-5"
              />
            </div>
            <div
              class="w-[38px] h-[38px] transform rotate-45 bg-[#212121] flex justify-center items-center shadow-md hover:bg-[#B28A6B] transition-colors duration-300"
            >
              <img
                src="../public/home/icons/insta.svg"
                alt="Instagram"
                class="transform -rotate-45 w-5 h-5"
              />
            </div>
            <div
              class="w-[38px] h-[38px] transform rotate-45 bg-[#212121] flex justify-center items-center shadow-md hover:bg-[#B28A6B] transition-colors duration-300"
            >
              <img
                src="../public/home/icons/twitter.svg"
                alt="Twitter"
                class="transform -rotate-45 w-5 h-5"
              />
            </div>
            <div
              class="w-[38px] h-[38px] transform rotate-45 bg-[#212121] flex justify-center items-center shadow-md hover:bg-[#B28A6B] transition-colors duration-300"
            >
              <img
                src="../public/home/icons/p.svg"
                alt="Pinterest"
                class="transform -rotate-45 w-5 h-5"
              />
            </div>
          </div>
        </div>

        <div class="flex flex-col items-center text-center pt-8 md:pt-0">
          <div class="font-bold text-lg mb-4 text-[#524B46] relative">
            <span
              class="absolute -left-3 top-1/2 -translate-y-1/2 w-1.5 h-1.5 bg-[#B28A6B] rounded-full"
            ></span>
            Thông tin
          </div>
          <ul class="space-y-2">
            <li>
              <a href="#" class="text-sm hover:text-[#B28A6B]"
                >Chính sách bảo mật</a
              >
            </li>
            <li>
              <a href="#" class="text-sm hover:text-[#B28A6B]"
                >Dịch vụ khách hàng</a
              >
            </li>
            <li>
              <a href="#" class="text-sm hover:text-[#B28A6B]"
                >Đơn hàng và đổi/trả hàng</a
              >
            </li>
            <li>
              <a href="#" class="text-sm hover:text-[#B28A6B]">Liên hệ</a>
            </li>
          </ul>
        </div>
      </div>

      <div
        class="flex flex-col md:flex-row justify-between items-center py-4 px-8 border-t border-gray-200 text-gray-600 text-sm"
      >
        <div class="mb-2 md:mb-0">
          © Copyright 2020 BOO. All Rights Reserved.
        </div>
        <div>
          <img
            src="../public/home/payment1.png"
            alt="Payment Methods"
            class="h-6"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import "@fortawesome/fontawesome-free/css/all.min.css";
</script>
