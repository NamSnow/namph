<template>
  <div class="font-josefinsans container">
    <!--  -->
    <div class="header bg-colornew container">
      <div class="banner p-4">
        <div class="mx-auto">
          <div
            class="flex items-center justify-between h-[3.75rem] flex-wrap sm:flex-nowrap"
          >
            <div class="relative h-full w-full sm:w-[21.875rem]">
              <input
                type="search"
                placeholder="Tìm kiếm"
                class="h-full w-full py-2 pl-3 pr-10 placeholder-gray-500 focus:outline-none focus:ring-1 focus:ring-brand-primary border-b-2 border-light-gray-text bg-transparent"
              />
              <img
                src="../../home/icons/search.svg"
                alt="Search"
                class="absolute right-3 top-1/2 h-5 w-5 -translate-y-1/2 cursor-pointer text-gray-500"
              />
            </div>
            <div class="flex h-full items-center">
              <img
                src="../../home/icon-b.png"
                alt=""
                class="h-full object-contain"
              />
            </div>
            <div
              class="flex w-full sm:w-[21.875rem] items-center justify-end gap-[0.9375rem] space-x-1 mt-2 sm:mt-0"
            >
              <img
                src="../../home/icons/account_circle.svg"
                alt=""
                class="cursor-pointer"
              />
              <div class="relative inline-block">
                <img
                  src="../../home/icons/shopping_bag.svg"
                  alt=""
                  class="cursor-pointer"
                />
                <div
                  class="absolute right-[3px] top-0 flex h-1 w-1 items-center justify-center rounded-full bg-brown-accent text-[0.5rem] font-bold text-white"
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
        class="mx-auto flex w-full flex-col items-center justify-between sm:flex-row md:w-viewport-80"
      >
        <img
          src="../../home/boy-left-header.png"
          alt=""
          class="max-w-xs sm:max-w-sm mb-4 sm:mb-0"
        />
        <div class="text-center flex-grow">
          <div>
            <div class="text-[1.5rem] sm:text-[2rem] font-bold">
              Giảm giá tới
              <span class="font-semibold text-brown-accent">40%</span>
            </div>
            <div
              class="flex h-[5rem] sm:h-[8.125rem] w-full flex-shrink-0 items-center justify-center font-kaushan text-[3rem] sm:text-[5.625rem] font-bold text-brown-accent"
            >
              Mùa hè
            </div>
          </div>
          <div class="mt-2 text-[1.5rem] sm:text-[2rem]">
            Chỉ Trong tuần này
          </div>
          <button
            class="mt-4 rounded bg-brown-accent px-4 py-2 text-sm text-[1rem] sm:text-[1.25rem] font-bold text-white hover:bg-brown-darker"
          >
            Mua ngay
          </button>
          <div
            class="my-2 mt-[2rem] sm:mt-[11.25rem] flex items-center justify-center gap-[0.46875rem]"
          >
            <NextPageBig />
          </div>
        </div>
        <img
          src="../../home/boy-right-header.png"
          alt=""
          class="max-w-xs sm:max-w-sm mt-4 sm:mt-0"
        />
      </div>
    </div>

    <!--  -->
    <div class="banner mt-16 w-[80vw] mx-auto">
      <div class="flex justify-between gap-[1.875rem]">
        <div
          class="flex justify-between bg-gray-100 w-[43.125rem] h-[26.875rem]"
        >
          <div class="mr-8 mt-16 ml-16">
            <div class="text-[1.875rem] font-semibold text-gray-800">
              Sản phẩm
            </div>
            <div class="text-[1.875rem] font-bold text-gray-900">
              Bán chạy nhất
            </div>
            <div class="text-sm text-gray-600">Tuần khuyến mại lớn</div>
            <button
              class="bg-brown-accent hover:bg-brown-darker text-white font-bold py-2 px-4 rounded mt-4 text-sm"
            >
              Mua ngay
            </button>
          </div>
          <img src="../../home/girl-banner-left.png" alt="" class="max-w-sm" />
        </div>

        <div
          class="flex justify-between bg-gray-100 w-[43.125rem] h-[26.875rem]"
        >
          <div class="mr-8 mt-16 ml-16">
            <div class="text-[1.875rem] font-semibold text-gray-800">
              Bộ sưu tập mới
            </div>
            <div class="text-sm text-gray-600">Có sẵn ngay</div>
            <button
              class="bg-brown-accent hover:bg-brown-darker text-white font-bold py-2 px-4 rounded mt-4 text-sm"
            >
              Mua ngay
            </button>
          </div>
          <img src="../../home/boy-banner-right.png" alt="" class="max-w-sm" />
        </div>
      </div>
    </div>

    <!--  -->
    <div class="mx-auto mt-8 w-[80vw] text-center">
      <div class="mb-8 text-center">
        <h2 class="text-2xl font-bold text-gray-800 mb-2">Sản phẩm mới</h2>
        <NextPageSmall />
        <p class="text-sm text-gray-600">
          Thời Trang Mới, Phong Cách Mới - Khám Phá Sản Phẩm Mới Để Tỏa Sáng
        </p>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <ProductList1 />
      </div>

      <div
        class="flex justify-center items-center my-2 gap-[0.46875rem] mt-[2.9375rem] mb-[4.375rem]"
      >
        <NextPageBig />
      </div>
    </div>

    <!--  -->
    <div class="bg-beige pt-10 h-screen">
      <div class="mx-auto">
        <div class="mb-6 text-center">
          <div class="relative w-full">
            <img
              src="../../home/title-bg1.png"
              alt="Ưu đãi trong ngày background"
              class="mx-auto object-cover"
            />
            <h2
              class="text-2xl font-bold text-dark absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 whitespace-nowrap"
            >
              Ưu đãi trong ngày
            </h2>
          </div>
          <div class="flex justify-center items-center mb-2 gap-[0.9375rem]">
            <NextPageSmall />
          </div>
          <p class="text-sm text-gray-600">
            Duy Nhất Trong Hôm Nay, Ưu Đãi Không Thể Bỏ Lỡ
          </p>
        </div>

        <div class="flex justify-around gap-[1.875rem] w-[80vw] mx-auto">
          <div
            class="bg-white shadow-md overflow-hidden flex flex-1 transform transition-transform duration-300 hover:scale-105"
          >
            <div class="p-6 flex-1">
              <h3 class="font-semibold text-gray-800 mb-2">
                ÁO PHÔNG LOGO KIND OF BASIC REGULAR
              </h3>
              <div class="flex items-center mb-2">
                <div class="text-gray-600 line-through mr-2">599.000 đ</div>
                <div class="text-brown-accent">304.000 đ</div>
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
                <div class="text-center pl-[1.25rem]">
                  <span class="font-bold text-lg align-middle">00</span
                  ><br />Giờ
                </div>
                <div class="text-center pl-[1.25rem]">
                  <span class="font-bold text-lg align-middle">00</span
                  ><br />Phút
                </div>
                <div class="text-center pl-[1.25rem]">
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
              src="../../home/uudai-1.png"
              alt=""
              class="w-[13.125rem] h-[18.125rem] object-cover pr-[0.9375rem] py-[1.5625rem]"
            />
          </div>

          <div
            class="bg-white shadow-md overflow-hidden flex flex-1 transform transition-transform duration-300 hover:scale-105"
          >
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
                <div class="text-center pl-[1.25rem]">
                  <span class="font-bold text-lg align-middle">00</span
                  ><br />Giờ
                </div>
                <div class="text-center pl-[1.25rem]">
                  <span class="font-bold text-lg align-middle">00</span
                  ><br />Phút
                </div>
                <div class="text-center pl-[1.25rem]">
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
              src="../../home/uudai-2.png"
              alt=""
              class="w-[13.125rem] h-[18.125rem] object-cover pr-[0.9375rem] py-[1.5625rem]"
            />
          </div>
        </div>

        <div
          class="flex justify-center items-center my-2 gap-[0.46875rem] mt-[3.75rem] mb-[4.375rem]"
        >
          <NextPageBig />
        </div>
      </div>
    </div>

    <!--  -->
    <div class="flex gap-[1.875rem] justify-center mt-[5rem] w-[80vw] mx-auto">
      <div
        class="relative w-[28.125rem] h-[20.1875rem] bg-light-bg flex flex-row-reverse"
      >
        <img
          src="../../home/product-new1.png"
          alt=""
          class="w-1/2 h-full object-cover"
        />
        <div
          class="absolute left-0 pt-[1.875rem] pl-[2.1875rem] gap-[0.625rem]"
        >
          <div class="text-xs text-gray-800 mb-1 underline">MUA NGAY</div>
          <div class="text-xl font-semibold text-gray-800">Xu hướng</div>
        </div>
      </div>
      <div
        class="relative w-[28.125rem] h-[20.1875rem] bg-lightest flex flex-row-reverse"
      >
        <img
          src="../../home/product-new2.png"
          alt=""
          class="w-1/2 h-full object-contain"
        />
        <div
          class="absolute left-0 pt-[1.875rem] pl-[2.1875rem] gap-[0.625rem]"
        >
          <div class="text-xs text-gray-800 mb-1 underline">MUA NGAY</div>
          <div class="text-xl font-semibold text-gray-800">Mới</div>
        </div>
      </div>
      <div
        class="relative w-[28.125rem] h-[20.1875rem] bg-light flex flex-row-reverse"
      >
        <img
          src="../../home/product-new3.png"
          alt=""
          class="w-1/2 h-full object-contain"
        />
        <div
          class="absolute left-0 pt-[1.875rem] pl-[2.1875rem] gap-[0.625rem]"
        >
          <div class="text-xs text-gray-800 mb-1 underline">MUA NGAY</div>
          <div class="text-xl font-semibold text-gray-800">Giảm giá</div>
        </div>
      </div>
    </div>

    <!--  -->
    <div class="mx-auto mt-8 w-[80vw] text-center">
      <div class="mb-8 text-center">
        <h2 class="text-2xl font-bold text-gray-800 mb-2">
          Sản phẩm bán chạy nhất
        </h2>
        <div class="flex justify-center items-center mb-2 gap-[0.9375rem]">
          <NextPageSmall />
        </div>
        <p class="text-sm text-gray-600">
          Tạo Nên Phong Cách Của Bạn - Sản Phẩm Đình Đám Trong Thời Trang!
        </p>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <ProductList2 />
      </div>

      <div
        class="flex justify-center items-center my-2 gap-[0.46875rem] mt-[2.9375rem] mb-[1.3125rem]"
      >
        <NextPageBig />
      </div>
    </div>

    <!--  -->
    <div class="bg-off-white pt-[3.125rem] text-center mx-auto">
      <div class="mx-auto px-4 w-[80vw]">
        <div
          class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 text-center text-white"
        >
          <div class="flex flex-col items-center">
            <img
              src="../../home/icons/truck1.svg"
              alt="Truck icon"
              class="w-14 h-14 mb-4 cursor-pointer"
            />
            <h3
              class="text-[1rem] font-bold text-black mb-2 min-h-[1.875rem] flex items-center justify-center"
            >
              GIAO HÀNG TOÀN CẦU
            </h3>
            <p class="text-[0.875rem] text-gray-400 flex-grow">
              Hoạt động bằng 5 ngôn ngữ, chúng tôi giao hàng đến hơn 200 quốc
              gia và vùng lãnh thổ.
            </p>
          </div>

          <div class="flex flex-col items-center">
            <img
              src="../../home/icons/unlock1.svg"
              alt="Unlock icon"
              class="w-14 h-14 mb-4 cursor-pointer"
            />
            <h3
              class="text-[1rem] font-bold text-black mb-2 min-h-[1.875rem] flex items-center justify-center"
            >
              GIAO HÀNG ĐẢM BẢO
            </h3>
            <p class="text-[0.875rem] text-gray-400 flex-grow">
              Thanh toán bằng các phương thức thanh toán phổ biến và an toàn
              nhất trên thế giới.
            </p>
          </div>

          <div class="flex flex-col items-center">
            <img
              src="../../home/icons/refresh-ccw1.svg"
              alt="Refresh icon"
              class="w-14 h-14 mb-4 cursor-pointer"
            />
            <h3
              class="text-[1rem] font-bold text-black mb-2 min-h-[1.875rem] flex items-center justify-center"
            >
              ĐỔI/TRẢ HÀNG TRONG VÒNG 365 NGÀY
            </h3>
            <p class="text-[0.875rem] text-gray-400 flex-grow">
              Chúng tôi hỗ trợ 24/7 để mang lại trải nghiệm mua sắm trơn tru.
            </p>
          </div>

          <div class="flex flex-col items-center">
            <img
              src="../../home/icons/shopping-bag1.svg"
              alt="Shopping bag icon"
              class="w-14 h-14 mb-4 cursor-pointer"
            />
            <h3
              class="text-[1rem] font-bold text-black mb-2 min-h-[1.875rem] flex items-center justify-center"
            >
              MUA HÀNG MỘT CÁCH TỰ TIN
            </h3>
            <p class="text-[0.875rem] text-gray-400 flex-grow">
              Chính sách bảo vệ người mua bao gồm mọi giao dịch từ khi nhấp
              chuột đến khi nhận hàng.
            </p>
          </div>
        </div>
      </div>
    </div>

    <!--  -->
    <div class="flex w-full py-8 gap-x-[1.875rem] justify-center">
      <img
        src="../../home/insta11.png"
        alt=""
        class="h-[14rem] object-cover flex-grow"
      />
      <img
        src="../../home/insta21.png"
        alt=""
        class="h-[14rem] object-cover flex-grow"
      />
      <img
        src="../../home/insta31.png"
        alt=""
        class="h-[14rem] object-cover flex-grow"
      />
      <img
        src="../../home/insta41.png"
        alt=""
        class="h-[14rem] object-cover flex-grow"
      />
      <img
        src="../../home/insta51.png"
        alt=""
        class="h-[14rem] object-cover flex-grow"
      />
      <img
        src="../../home/insta71.png"
        alt=""
        class="h-[14rem] object-cover flex-grow"
      />
    </div>

    <!--  -->
    <div
      class="flex flex-col items-center justify-center py-16 px-4 bg-off-white text-center"
    >
      <div
        class="text-brown-accent text-base md:text-lg font-bold uppercase tracking-widest mb-2"
      >
        Thư thông báo
      </div>
      <div class="text-3xl md:text-5xl font-bold mb-4 leading-tight">
        Nhận giảm giá 30%
      </div>
      <div class="text-light-gray text-sm md:text-base mb-8 max-w-md">
        30% off trên toàn bộ đơn hàng của bạn khi nhập mã khuyến mãi.
      </div>
      <div
        class="flex flex-col md:flex-row items-center w-full max-w-2xl px-4 md:px-0"
      >
        <input
          type="email"
          placeholder="Nhập Email của bạn..."
          class="w-full md:flex-grow py-[0.625rem] pl-[1.25rem] border focus:outline-none focus:ring-2 focus:ring-brown-accent mb-4 md:mb-0 text-light-gray placeholder-light-gray"
        />
        <button
          class="w-full md:w-auto px-8 py-[0.625rem] bg-brown-accent text-white font-bold hover:bg-brown-accent transition-colors duration-300 whitespace-nowrap"
        >
          Đăng ký
        </button>
      </div>
    </div>

    <!--  -->
    <div class="w-full mx-auto text-center">
      <div
        class="flex flex-col md:flex-row justify-around items-start md:items-start p-8 bg-white relative"
      >
        <div
          class="flex flex-col items-center text-center pb-8 md:pb-0 md:pr-12 lg:pr-24 flex-1"
        >
          <div class="font-bold text-lg mb-4 relative">
            <span
              class="absolute -left-[0.75rem] top-1/2 -translate-y-1/2 w-[0.375rem] h-[0.375rem] bg-brown-accent rounded-full"
            ></span>
            Khách hàng
          </div>
          <ul class="space-y-2">
            <li>
              <a href="#" class="text-sm hover:text-brown-accent"
                >Vận chuyển & Đổi/trả hàng</a
              >
            </li>
            <li>
              <a href="#" class="text-sm hover:text-brown-accent"
                >Mua sắm an toàn</a
              >
            </li>
            <li>
              <a href="#" class="text-sm hover:text-brown-accent"
                >Trạng thái đơn hàng</a
              >
            </li>
            <li>
              <a href="#" class="text-sm hover:text-brown-accent"
                >Vận chuyển quốc tế</a
              >
            </li>
          </ul>
        </div>

        <div
          class="hidden md:block absolute left-1/3 top-0 bottom-0 w-px bg-gray-200"
        ></div>

        <div
          class="flex flex-col items-center text-center px-4 md:px-8 mb-8 md:mb-0 flex-1"
        >
          <div class="mb-4">
            <img src="../../home/icon-b.png" alt="BCO Logo" class="h-16" />
          </div>
          <div class="text-sm leading-relaxed mb-6 max-w-xs">
            Khám phá phong cách mới tại cửa hàng. <br />
            Nơi mua sắm độc đáo và thú vị!
          </div>
          <div class="flex space-x-[0.625rem] gap-[0.625rem]">
            <div
              class="cursor-pointer w-[2.375rem] h-[2.375rem] transform rotate-45 bg-black flex justify-center items-center shadow-md hover:bg-brown-accent transition-colors duration-300"
            >
              <img
                src="../../home/icons/facebook.svg"
                alt="Facebook"
                class="transform -rotate-45 w-5 h-5"
              />
            </div>
            <div
              class="cursor-pointer w-[2.375rem] h-[2.375rem] transform rotate-45 bg-black flex justify-center items-center shadow-md hover:bg-brown-accent transition-colors duration-300"
            >
              <img
                src="../../home/icons/insta.svg"
                alt="Instagram"
                class="transform -rotate-45 w-5 h-5"
              />
            </div>
            <div
              class="cursor-pointer w-[2.375rem] h-[2.375rem] transform rotate-45 bg-black flex justify-center items-center shadow-md hover:bg-brown-accent transition-colors duration-300"
            >
              <img
                src="../../home/icons/twitter.svg"
                alt="Twitter"
                class="transform -rotate-45 w-5 h-5"
              />
            </div>
            <div
              class="cursor-pointer w-[2.375rem] h-[2.375rem] transform rotate-45 bg-black flex justify-center items-center shadow-md hover:bg-brown-accent transition-colors duration-300"
            >
              <img
                src="../../home/icons/p.svg"
                alt="Pinterest"
                class="transform -rotate-45 w-5 h-5"
              />
            </div>
          </div>
        </div>

        <div
          class="hidden md:block absolute left-2/3 top-0 bottom-0 w-px bg-gray-200"
        ></div>

        <div class="flex flex-col items-center text-center pt-8 md:pt-0 flex-1">
          <div class="font-bold text-lg mb-4 text-[#524B46] relative">
            <span
              class="absolute -left-[0.75rem] top-1/2 -translate-y-1/2 w-[0.375rem] h-[0.375rem] bg-brown-accent rounded-full"
            ></span>
            Thông tin
          </div>
          <ul class="space-y-2">
            <li>
              <a href="#" class="text-sm hover:text-brown-accent"
                >Chính sách bảo mật</a
              >
            </li>
            <li>
              <a href="#" class="text-sm hover:text-brown-accent"
                >Dịch vụ khách hàng</a
              >
            </li>
            <li>
              <a href="#" class="text-sm hover:text-brown-accent"
                >Đơn hàng và đổi/trả hàng</a
              >
            </li>
            <li>
              <a href="#" class="text-sm hover:text-brown-accent">Liên hệ</a>
            </li>
          </ul>
        </div>
      </div>

      <div
        class="flex flex-col md:flex-row justify-between items-center py-4 px-8 border-t border-gray-200 text-gray-600 text-sm w-full"
      >
        <div class="mb-2 md:mb-0">
          © Copyright 2020 BOO. All Rights Reserved.
        </div>
        <div>
          <img
            src="../../home/payment1.png"
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

import ProductList1 from "~/components/ProductList1.vue";
import ProductList2 from "~/components/ProductList2.vue";
// import "../assets/app.scss";
</script>
