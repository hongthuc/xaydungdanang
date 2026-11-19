<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>Xây Dựng Nhà Ở Đà Nẵng | Thiết Kế &amp; Thi Công Trọn Gói - xaydungdanang.com</title>
    <meta name="description" content="Xây Dựng Nhà Ở Đà Nẵng (xaydungdanang.com) chuyên thiết kế kiến trúc, thi công phần thô, thi công hoàn thiện và xây nhà trọn gói uy tín tại Đà Nẵng. Hotline: 0905.233.903.">

    <!-- Meta Thumbnail chia sẻ liên kết sử dụng Logo thương hiệu xaydungdanang.com -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="Xây Dựng Nhà Ở Đà Nẵng - xaydungdanang.com">
    <meta property="og:title" content="Xây Dựng Nhà Ở Đà Nẵng - Thiết Kế &amp; Thi Công Trọn Gói Uy Tín">
    <meta property="og:description" content="Chuyên thiết kế kiến trúc, xây nhà phần thô, hoàn thiện nhà phố, biệt thự, căn hộ, khách sạn tại Đà Nẵng. Hotline tư vấn: 0905.233.903.">
    <meta property="og:url" content="https://xaydungdanang.com">
    <meta property="og:image" content="https://xaydungdanang.com/assets/logo-xaydungdanang.png">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Xây Dựng Nhà Ở Đà Nẵng - xaydungdanang.com">
    <meta name="twitter:description" content="Thiết kế &amp; thi công xây dựng nhà ở trọn gói tại Đà Nẵng. Hotline: 0905.233.903.">
    <meta name="twitter:image" content="https://xaydungdanang.com/assets/logo-xaydungdanang.png">

    <!-- Favicon động từ Logo SVG -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230F2A4A'/%3E%3Cpath d='M10 33L32 14L54 33H47V50H36V38H28V50H17V33H10Z' fill='%23D97706'/%3E%3Cpath d='M22 33L32 24L42 33' stroke='%23FFFFFF' stroke-width='3' fill='none'/%3E%3C/svg%3E">

    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            navy: '#0F2A4A',
                            navyDark: '#091C33',
                            navyLight: '#1A3D68',
                            gold: '#D97706',
                            goldHover: '#B45309',
                            goldSoft: '#FEF3C7',
                            slateBg: '#F4F6F9',
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Thiết lập cơ bản chống tràn ngang và lệch phải tuyệt đối */
        *, *::before, *::after {
            box-sizing: border-box;
        }

        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Inter', system-ui, -apple-system, sans-serif;
            color: #1E293B;
            background-color: #FFFFFF;
            scroll-behavior: smooth;
            -webkit-font-smoothing: antialiased;
        }

        /* Chiều ngang giao diện trên máy tính bằng đúng 95% kích thước màn hình */
        .flatsome-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }

        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Chuẩn Flatsome: Menu thả xuống mượt mà */
        .nav-dropdown {
            position: relative;
        }

        .nav-dropdown-menu {
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
            pointer-events: none;
        }

        .nav-dropdown:hover .nav-dropdown-menu,
        .nav-dropdown:focus-within .nav-dropdown-menu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
            pointer-events: auto;
        }

        /* Banner tự trượt mượt mà, kích thước 2 slide bằng nhau tuyệt đối */
        .hero-slider-viewport {
            position: relative;
            width: 100%;
            overflow: hidden;
            background-color: #091C33;
        }

        .hero-slider-track {
            display: flex;
            width: 200%;
            transition: transform 0.65s cubic-bezier(0.25, 0.8, 0.25, 1);
        }

        .hero-slide-item {
            width: 50%;
            flex: 0 0 50%;
            position: relative;
            display: flex;
            align-items: center;
            min-height: 310px;
        }

        @media (min-width: 640px) {
            .hero-slide-item {
                min-height: 390px;
            }
        }

        @media (min-width: 1024px) {
            .hero-slide-item {
                min-height: 470px;
            }
        }

        /* Hiệu ứng nhịp sóng cho nút Hotline nổi */
        @keyframes softPulse {
            0% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.45); }
            70% { box-shadow: 0 0 0 12px rgba(220, 38, 38, 0); }
            100% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0); }
        }

        .pulse-hotline {
            animation: softPulse 2s infinite;
        }

        /* Thanh cuộn danh mục gọn trên điện thoại nếu cần */
        .hide-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .hide-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }

        /* Gạch chân tiêu đề phong cách Flatsome */
        .section-divider {
            width: 56px;
            height: 3px;
            background-color: #D97706;
            margin: 10px auto 0 auto;
            border-radius: 9999px;
        }
    </style>
</head>
<body class="bg-white text-slate-800">

    <!-- ========================================================= -->
    <!-- UX BUILDER: TOP BAR (THÔNG TIN LIÊN HỆ NHANH - KHÔNG THANH CHỈNH SỬA) -->
    <!-- ========================================================= -->
    <div class="w-full bg-brand-navyDark text-slate-200 text-xs py-2 border-b border-white/10">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3 sm:gap-5 flex-wrap">
                <span class="inline-flex items-center gap-1.5 whitespace-nowrap">
                    <svg class="w-3.5 h-3.5 text-brand-gold shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                    <span>Đà Nẵng</span>
                </span>
                <a href="tel:0905233903" class="inline-flex items-center gap-1.5 hover:text-brand-gold transition whitespace-nowrap">
                    <svg class="w-3.5 h-3.5 text-brand-gold shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
                    <span class="font-semibold">0905.233.903</span>
                </a>
                <span class="hidden sm:inline-flex items-center gap-1.5 text-slate-300 whitespace-nowrap">
                    <svg class="w-3.5 h-3.5 text-brand-gold shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9"/></svg>
                    <span>xaydungdanang.com</span>
                </span>
            </div>
            <div class="hidden md:flex items-center gap-4 text-slate-300">
                <a href="https://www.facebook.com/profile.php?id=100063678894623" target="_blank" rel="noopener noreferrer" class="hover:text-brand-gold transition whitespace-nowrap">Fanpage Facebook</a>
                <span>|</span>
                <a href="https://zalo.me/0905233903" target="_blank" rel="noopener noreferrer" class="hover:text-brand-gold transition whitespace-nowrap">Tư vấn Zalo</a>
            </div>
        </div>
    </div>

    <!-- ========================================================= -->
    <!-- UX BUILDER: HEADER CHÍNH (LOGO NHỎ GỌN + MENU 1 HÀNG, KHÔNG NÚT GỌI NGAY) -->
    <!-- ========================================================= -->
    <header class="sticky top-0 z-40 w-full bg-white/95 backdrop-blur border-b border-slate-200 shadow-sm">
        <div class="flatsome-container flex items-center justify-between h-16 lg:h-[70px] gap-2">
            <!-- Logo chuyên nghiệp chỉnh gọn nhỏ -->
            <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group" aria-label="Xây Dựng Đà Nẵng - Trang chủ">
                <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0" viewBox="0 0 56 56" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <rect width="56" height="56" rx="10" fill="#0F2A4A"/>
                    <path d="M9 28.5L28 12L47 28.5H41.5V44H32.5V33H23.5V44H14.5V28.5H9Z" fill="#D97706"/>
                    <path d="M18.5 29L28 20.5L37.5 29" stroke="#FFFFFF" stroke-width="2.6" stroke-linecap="round" stroke-linejoin="round"/>
                    <rect x="25.5" y="26.5" width="5" height="4.5" rx="0.8" fill="#0F2A4A"/>
                </svg>
                <div class="leading-tight">
                    <div class="text-[13px] sm:text-[15px] font-extrabold tracking-tight text-brand-navy group-hover:text-brand-gold transition whitespace-nowrap">
                        XÂY DỰNG ĐÀ NẴNG
                    </div>
                    <div class="text-[10px] font-semibold tracking-wider text-brand-gold uppercase whitespace-nowrap">
                        xaydungdanang.com
                    </div>
                </div>
            </a>

            <!-- Menu máy tính: chữ gọn, viết liền trên 1 hàng, không xuống dòng từng danh mục -->
            <nav class="hidden lg:flex items-center justify-end gap-1 xl:gap-2 min-w-0" aria-label="Điều hướng chính">
                <a href="#trang-chu" class="px-2 py-2 text-[12px] xl:text-[13px] font-semibold text-brand-navy hover:text-brand-gold transition whitespace-nowrap">Trang chủ</a>
                <a href="#gioi-thieu" class="px-2 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition whitespace-nowrap">Giới thiệu</a>

                <!-- Dropdown: Công trình thực tế -->
                <div class="nav-dropdown">
                    <a href="#cong-trinh-thuc-te" class="inline-flex items-center gap-1 px-2 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition whitespace-nowrap">
                        <span>Công trình thực tế</span>
                        <svg class="w-3 h-3" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown-menu absolute left-0 top-full pt-1 w-56 z-50">
                        <div class="bg-white rounded-lg shadow-lg border border-slate-200 py-1.5">
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('can-ho')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-slateBg hover:text-brand-gold">Khách sạn – Căn hộ – Phòng trọ</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('biet-thu')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-slateBg hover:text-brand-gold">Biệt thự</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-slateBg hover:text-brand-gold">Nhà phố</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('van-phong')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-slateBg hover:text-brand-gold">Văn phòng</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown: Lĩnh vực hoạt động -->
                <div class="nav-dropdown">
                    <a href="#linh-vuc-hoat-dong" class="inline-flex items-center gap-1 px-2 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition whitespace-nowrap">
                        <span>Lĩnh vực hoạt động</span>
                        <svg class="w-3 h-3" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown-menu absolute left-0 top-full pt-1 w-56 z-50">
                        <div class="bg-white rounded-lg shadow-lg border border-slate-200 py-1.5">
                            <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-slateBg hover:text-brand-gold">Thiết kế Kiến trúc – Nội thất</a>
                            <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-slateBg hover:text-brand-gold">Thi công phần thô</a>
                            <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-slateBg hover:text-brand-gold">Thi công hoàn thiện</a>
                            <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-slateBg hover:text-brand-gold">Thi công nội thất</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown: Mẫu thiết kế / Dự án Đà Nẵng -->
                <a href="#du-an-da-nang" class="px-2 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition whitespace-nowrap">Dự án Đà Nẵng</a>

                <!-- Dropdown: Báo giá -->
                <div class="nav-dropdown">
                    <a href="#bao-gia" class="inline-flex items-center gap-1 px-2 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition whitespace-nowrap">
                        <span>Báo giá</span>
                        <svg class="w-3 h-3" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown-menu absolute right-0 top-full pt-1 w-56 z-50">
                        <div class="bg-white rounded-lg shadow-lg border border-slate-200 py-1.5">
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-slateBg hover:text-brand-gold">Báo giá thiết kế kiến trúc</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-slateBg hover:text-brand-gold">Báo giá thi công phần thô</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-slateBg hover:text-brand-gold">Báo giá thi công hoàn thiện</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-slateBg hover:text-brand-gold">Báo giá thi công trọn gói</a>
                        </div>
                    </div>
                </div>

                <a href="#tin-tuc" class="px-2 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition whitespace-nowrap">Tin tức</a>
                <a href="#lien-he" class="px-2 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition whitespace-nowrap">Liên hệ</a>
            </nav>

            <!-- Nút mở menu trên điện thoại (không có nút gọi ngay trên header tránh tràn viền) -->
            <button id="mobileMenuBtn" type="button" class="lg:hidden inline-flex items-center justify-center p-2.5 rounded-lg text-brand-navy hover:bg-slate-100 focus:outline-none" aria-label="Mở menu danh mục">
                <svg id="menuIconOpen" class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16"/></svg>
                <svg id="menuIconClose" class="w-6 h-6 hidden" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
            </button>
        </div>

        <!-- Menu thả xuống trên điện thoại -->
        <div id="mobileMenuPanel" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg w-full">
            <div class="px-4 py-3 space-y-1">
                <a href="#trang-chu" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-brand-navy hover:bg-brand-slateBg">Trang chủ</a>
                <a href="#gioi-thieu" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-brand-slateBg">Giới thiệu</a>
                <a href="#linh-vuc-hoat-dong" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-brand-slateBg">Lĩnh vực hoạt động</a>
                <a href="#cong-trinh-thuc-te" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-brand-slateBg">Công trình thực tế</a>
                <a href="#du-an-da-nang" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-brand-slateBg">Dự án tại Đà Nẵng</a>
                <a href="#bao-gia" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-brand-slateBg">Báo giá thi công</a>
                <a href="#tin-tuc" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-brand-slateBg">Tin tức &amp; Kinh nghiệm</a>
                <a href="#doi-tac" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-brand-slateBg">Đối tác</a>
                <a href="#lien-he" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-brand-slateBg">Liên hệ &amp; Bản đồ</a>
            </div>
        </div>
    </header>

    <main id="trang-chu" class="w-full overflow-x-hidden">

        <!-- ========================================================= -->
        <!-- UX BUILDER SECTION 1: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP -->
        <!-- Kích thước 2 banner bằng nhau, chữ nằm trọn bên trong, cách xa viền ảnh -->
        <!-- ========================================================= -->
        <section class="w-full bg-brand-navyDark">
            <div class="flatsome-container lg:py-4">
                <div id="heroSlider" class="hero-slider-viewport lg:rounded-xl shadow-md">
                    <div id="heroTrack" class="hero-slider-track">

                        <!-- SLIDE 1 -->
                        <div class="hero-slide-item">
                            <img
                                src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1400"
                                data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                                alt="Thi công xây dựng nhà ở Đà Nẵng chuyên nghiệp"
                                class="drive-img absolute inset-0 w-full h-full object-cover object-center"
                            >
                            <!-- Lớp phủ chuyển sắc giúp chữ luôn sắc nét -->
                            <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/90 via-brand-navy/75 to-brand-navyDark/45"></div>
                            <!-- Vùng an toàn chứa chữ: cách xa viền ảnh trên cả điện thoại và máy tính -->
                            <div class="relative z-10 w-full px-8 sm:px-14 lg:px-20 py-10 sm:py-14 lg:py-16">
                                <div class="max-w-xl">
                                    <p class="text-[11px] sm:text-xs font-bold uppercase tracking-widest text-brand-gold mb-2">
                                        XÂY DỰNG NHÀ Ở ĐÀ NẴNG • XAYDUNGDANANG.COM
                                    </p>
                                    <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold text-white leading-snug mb-3">
                                        Thiết Kế &amp; Thi Công Xây Dựng Nhà Ở Trọn Gói Tại Đà Nẵng
                                    </h1>
                                    <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed mb-6">
                                        Đội ngũ kỹ sư và thợ lành nghề trực tiếp thi công nhà phố, biệt thự, căn hộ, khách sạn. Cam kết đúng kỹ thuật, đúng tiến độ và chi phí minh bạch.
                                    </p>
                                    <div class="flex flex-wrap items-center gap-3">
                                        <a href="#form-bao-gia" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-brand-gold hover:bg-brand-goldHover text-white text-xs sm:text-sm font-bold transition shadow-sm">
                                            Nhận Báo Giá Miễn Phí
                                        </a>
                                        <a href="#cong-trinh-thuc-te" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 text-xs sm:text-sm font-semibold transition">
                                            Xem Công Trình Thực Tế
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- SLIDE 2 -->
                        <div class="hero-slide-item">
                            <img
                                src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1400"
                                data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                                alt="Dự án xây dựng nhà phố biệt thự thực tế tại Đà Nẵng"
                                class="drive-img absolute inset-0 w-full h-full object-cover object-center"
                            >
                            <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/90 via-brand-navy/75 to-brand-navyDark/45"></div>
                            <!-- Vùng an toàn chứa chữ đồng nhất kích thước với Slide 1 -->
                            <div class="relative z-10 w-full px-8 sm:px-14 lg:px-20 py-10 sm:py-14 lg:py-16">
                                <div class="max-w-xl">
                                    <p class="text-[11px] sm:text-xs font-bold uppercase tracking-widest text-brand-gold mb-2">
                                        CHẤT LƯỢNG CÔNG TRÌNH • BẢO HÀNH DÀI LÂU
                                    </p>
                                    <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold text-white leading-snug mb-3">
                                        Thi Công Phần Thô &amp; Hoàn Thiện Chuẩn Kỹ Thuật Miền Trung
                                    </h2>
                                    <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed mb-6">
                                        Giải pháp chống thấm, kết cấu bền vững phù hợp khí hậu ven biển Đà Nẵng. Tư vấn bản vẽ 3D, xin phép xây dựng và giám sát chặt chẽ 24/7.
                                    </p>
                                    <div class="flex flex-wrap items-center gap-3">
                                        <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-brand-gold hover:bg-brand-goldHover text-white text-xs sm:text-sm font-bold transition shadow-sm">
                                            Khám Phá Dự Án Đà Nẵng
                                        </a>
                                        <a href="tel:0905233903" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 text-xs sm:text-sm font-semibold transition">
                                            Hotline: 0905.233.903
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>

                    <!-- Nút điều hướng Slide trái / phải gọn gàng sát mép ngoài vùng chữ -->
                    <button id="prevSlideBtn" type="button" aria-label="Banner trước" class="hidden sm:flex absolute left-3 top-1/2 -translate-y-1/2 z-20 w-9 h-9 rounded-full bg-black/35 hover:bg-brand-gold text-white items-center justify-center transition">
                        <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7"/></svg>
                    </button>
                    <button id="nextSlideBtn" type="button" aria-label="Banner tiếp theo" class="hidden sm:flex absolute right-3 top-1/2 -translate-y-1/2 z-20 w-9 h-9 rounded-full bg-black/35 hover:bg-brand-gold text-white items-center justify-center transition">
                        <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/></svg>
                    </button>

                    <!-- Chấm chỉ báo 2 Slide -->
                    <div class="absolute bottom-3.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                        <button type="button" onclick="goToSlide(0)" id="dot0" aria-label="Chọn banner 1" class="w-6 h-2 rounded-full bg-brand-gold transition-all"></button>
                        <button type="button" onclick="goToSlide(1)" id="dot1" aria-label="Chọn banner 2" class="w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all"></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- ========================================================= -->
        <!-- UX BUILDER SECTION 2: DỊCH VỤ TIÊU BIỂU (LĨNH VỰC HOẠT ĐỘNG) -->
        <!-- ========================================================= -->
        <section id="linh-vuc-hoat-dong" class="py-10 sm:py-14 bg-white">
            <div class="flatsome-container">
                <div class="text-center max-w-2xl mx-auto mb-8">
                    <h2 class="text-xl sm:text-2xl font-extrabold text-brand-navy uppercase tracking-tight">
                        Lĩnh Vực Hoạt Động Tiêu Biểu
                    </h2>
                    <div class="section-divider"></div>
                    <p class="text-xs sm:text-sm text-slate-600 mt-3">
                        Cung cấp giải pháp toàn diện từ khâu thiết kế bản vẽ đến thi công phần thô, hoàn thiện và nội thất nhà ở tại Đà Nẵng.
                    </p>
                </div>

                <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <!-- Dịch vụ 1 -->
                    <div class="group bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO=w800" data-drive-id="1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO" alt="Thiết kế Kiến trúc - Nội thất" class="drive-img w-full h-full object-cover group-hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-3 sm:p-4 text-center flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="text-[13px] sm:text-sm font-bold text-brand-navy leading-snug break-words">
                                    Thiết Kế Kiến Trúc – Nội Thất
                                </h3>
                                <p class="text-[11px] sm:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                    Tối ưu công năng, thông gió tự nhiên và thẩm mỹ hiện đại cho nhà phố, biệt thự.
                                </p>
                            </div>
                            <a href="#form-bao-gia" class="inline-block mt-3 text-[11px] sm:text-xs font-bold text-brand-gold hover:text-brand-navy transition">
                                Nhận tư vấn &rarr;
                            </a>
                        </div>
                    </div>

                    <!-- Dịch vụ 2 -->
                    <div class="group bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w800" data-drive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR" alt="Thi công phần thô" class="drive-img w-full h-full object-cover group-hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-3 sm:p-4 text-center flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="text-[13px] sm:text-sm font-bold text-brand-navy leading-snug break-words">
                                    Thi Công Phần Thô Chuẩn Kết Cấu
                                </h3>
                                <p class="text-[11px] sm:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                    Thi công móng, cột, dầm, sàn bê tông cốt thép đúng tiêu chuẩn kỹ thuật, vật tư chính hãng.
                                </p>
                            </div>
                            <a href="#form-bao-gia" class="inline-block mt-3 text-[11px] sm:text-xs font-bold text-brand-gold hover:text-brand-navy transition">
                                Nhận tư vấn &rarr;
                            </a>
                        </div>
                    </div>

                    <!-- Dịch vụ 3 -->
                    <div class="group bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_=w800" data-drive-id="1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_" alt="Thi công hoàn thiện trọn gói" class="drive-img w-full h-full object-cover group-hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-3 sm:p-4 text-center flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="text-[13px] sm:text-sm font-bold text-brand-navy leading-snug break-words">
                                    Thi Công Hoàn Thiện Trọn Gói
                                </h3>
                                <p class="text-[11px] sm:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                    Chìa khóa trao tay từ ốp lát, sơn nước, chống thấm đến hệ thống điện nước hoàn chỉnh.
                                </p>
                            </div>
                            <a href="#form-bao-gia" class="inline-block mt-3 text-[11px] sm:text-xs font-bold text-brand-gold hover:text-brand-navy transition">
                                Nhận tư vấn &rarr;
                            </a>
                        </div>
                    </div>

                    <!-- Dịch vụ 4 -->
                    <div class="group bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT=w800" data-drive-id="1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT" alt="Thi công nội thất và cải tạo" class="drive-img w-full h-full object-cover group-hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-3 sm:p-4 text-center flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="text-[13px] sm:text-sm font-bold text-brand-navy leading-snug break-words">
                                    Thi Công Nội Thất &amp; Cải Tạo Nhà
                                </h3>
                                <p class="text-[11px] sm:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                    Sản xuất, lắp đặt nội thất gỗ tinh tế và cải tạo nâng tầng nhà phố, văn phòng, căn hộ.
                                </p>
                            </div>
                            <a href="#form-bao-gia" class="inline-block mt-3 text-[11px] sm:text-xs font-bold text-brand-gold hover:text-brand-navy transition">
                                Nhận tư vấn &rarr;
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ========================================================= -->
        <!-- UX BUILDER SECTION 3: GIỚI THIỆU & THẾ MẠNH CỦA CHÚNG TÔI -->
        <!-- ========================================================= -->
        <section id="gioi-thieu" class="py-10 sm:py-14 bg-brand-slateBg border-y border-slate-200/80">
            <div class="flatsome-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center mb-10">
                    <div class="lg:col-span-6">
                        <p class="text-xs font-bold uppercase tracking-wider text-brand-gold mb-1.5">Về chúng tôi</p>
                        <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-navy leading-tight mb-4">
                            XÂY DỰNG NHÀ Ở ĐÀ NẴNG – ĐỒNG HÀNH KIẾN TẠO TỔ ẤM BỀN VỮNG
                        </h2>
                        <p class="text-sm text-slate-700 leading-relaxed mb-3">
                            <strong>xaydungdanang.com</strong> chuyên thiết kế kiến trúc, thi công xây dựng phần thô, hoàn thiện và nội thất các công trình nhà phố, biệt thự, căn hộ cho thuê, khách sạn và văn phòng tại khu vực Đà Nẵng và lân cận.
                        </p>
                        <p class="text-sm text-slate-700 leading-relaxed mb-5">
                            Với phương châm <strong>“An Toàn – Chất Lượng – Đúng Tiến Độ – Minh Bạch Chi Phí”</strong>, đội ngũ kỹ sư, kiến trúc sư cùng thợ thi công giàu kinh nghiệm luôn trực tiếp giám sát tại công trường, đảm bảo mỗi ngôi nhà bàn giao đều đạt độ bền cao và thẩm mỹ sắc nét.
                        </p>
                        <div class="grid grid-cols-3 gap-3 text-center">
                            <div class="bg-white rounded-xl p-3 border border-slate-200">
                                <div class="text-lg sm:text-2xl font-extrabold text-brand-navy">10+</div>
                                <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Năm kinh nghiệm</div>
                            </div>
                            <div class="bg-white rounded-xl p-3 border border-slate-200">
                                <div class="text-lg sm:text-2xl font-extrabold text-brand-gold">150+</div>
                                <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Công trình bàn giao</div>
                            </div>
                            <div class="bg-white rounded-xl p-3 border border-slate-200">
                                <div class="text-lg sm:text-2xl font-extrabold text-brand-navy">5 Năm</div>
                                <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Bảo hành kết cấu</div>
                            </div>
                        </div>
                    </div>

                    <div class="lg:col-span-6">
                        <div class="grid grid-cols-2 gap-3">
                            <div class="rounded-xl overflow-hidden shadow-sm border border-slate-200 aspect-[4/3] bg-slate-200">
                                <img src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv=w800" data-drive-id="1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv" alt="Hình ảnh thi công thực tế tại Đà Nẵng" class="drive-img w-full h-full object-cover">
                            </div>
                            <div class="rounded-xl overflow-hidden shadow-sm border border-slate-200 aspect-[4/3] bg-slate-200">
                                <img src="https://lh3.googleusercontent.com/d/1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t=w800" data-drive-id="1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t" alt="Thi công kết cấu công trình Đà Nẵng" class="drive-img w-full h-full object-cover">
                            </div>
                        </div>
                    </div>
                </div>

                <!-- 6 Thế mạnh cốt lõi -->
                <div class="text-center mb-6">
                    <h3 class="text-lg sm:text-xl font-extrabold text-brand-navy uppercase">Thế Mạnh Của Chúng Tôi</h3>
                    <div class="section-divider"></div>
                </div>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
                    <div class="bg-white p-5 rounded-xl border border-slate-200 flex items-start gap-3.5">
                        <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-gold flex items-center justify-center shrink-0">
                            <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                        </div>
                        <div>
                            <h4 class="text-sm font-bold text-brand-navy">Đội ngũ kỹ sư, thợ lành nghề</h4>
                            <p class="text-xs text-slate-600 mt-1 leading-relaxed">Kiến trúc sư sáng tạo cùng đội thợ thi công trực tiếp lâu năm, không bán thầu.</p>
                        </div>
                    </div>
                    <div class="bg-white p-5 rounded-xl border border-slate-200 flex items-start gap-3.5">
                        <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-gold flex items-center justify-center shrink-0">
                            <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
                        </div>
                        <div>
                            <h4 class="text-sm font-bold text-brand-navy">Vật tư chuẩn chính hãng</h4>
                            <p class="text-xs text-slate-600 mt-1 leading-relaxed">Cam kết đúng chủng loại sắt thép, xi măng, dây điện, ống nước theo hợp đồng.</p>
                        </div>
                    </div>
                    <div class="bg-white p-5 rounded-xl border border-slate-200 flex items-start gap-3.5">
                        <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-gold flex items-center justify-center shrink-0">
                            <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
                        </div>
                        <div>
                            <h4 class="text-sm font-bold text-brand-navy">Giám sát tiến độ chuẩn xác</h4>
                            <p class="text-xs text-slate-600 mt-1 leading-relaxed">Báo cáo hình ảnh thi công hàng ngày để chủ nhà dễ dàng theo dõi từ xa.</p>
                        </div>
                    </div>
                    <div class="bg-white p-5 rounded-xl border border-slate-200 flex items-start gap-3.5">
                        <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-gold flex items-center justify-center shrink-0">
                            <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"/></svg>
                        </div>
                        <div>
                            <h4 class="text-sm font-bold text-brand-navy">Bảo hành công trình lâu dài</h4>
                            <p class="text-xs text-slate-600 mt-1 leading-relaxed">Bảo hành kết cấu dài hạn và hỗ trợ bảo trì nhanh chóng ngay tại Đà Nẵng.</p>
                        </div>
                    </div>
                    <div class="bg-white p-5 rounded-xl border border-slate-200 flex items-start gap-3.5">
                        <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-gold flex items-center justify-center shrink-0">
                            <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
                        </div>
                        <div>
                            <h4 class="text-sm font-bold text-brand-navy">Chi phí hợp lý, không phát sinh</h4>
                            <p class="text-xs text-slate-600 mt-1 leading-relaxed">Lập dự toán rõ ràng từng hạng mục, tối ưu ngân sách tốt nhất cho gia chủ.</p>
                        </div>
                    </div>
                    <div class="bg-white p-5 rounded-xl border border-slate-200 flex items-start gap-3.5">
                        <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-gold flex items-center justify-center shrink-0">
                            <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M18.364 5.636l-3.536 3.536m0 5.656l3.536 3.536M9.172 9.172L5.636 5.636m3.536 9.192l-3.536 3.536M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
                        </div>
                        <div>
                            <h4 class="text-sm font-bold text-brand-navy">Tư vấn &amp; khảo sát miễn phí</h4>
                            <p class="text-xs text-slate-600 mt-1 leading-relaxed">Hỗ trợ khảo sát thực địa, tư vấn phong thủy và thủ tục xin phép xây dựng.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ========================================================= -->
        <!-- UX BUILDER SECTION 4: CÔNG TRÌNH THI CÔNG THỰC TẾ (9 ẢNH DRIVE NHÓM 1) -->
        <!-- Danh mục gọn 1 hàng trên máy tính, 2 cột trên điện thoại, không nhãn dán -->
        <!-- ========================================================= -->
        <section id="cong-trinh-thuc-te" class="py-10 sm:py-14 bg-white">
            <div class="flatsome-container">
                <div class="text-center max-w-2xl mx-auto mb-6">
                    <h2 class="text-xl sm:text-2xl font-extrabold text-brand-navy uppercase tracking-tight">
                        Công Trình Thi Công Thực Tế
                    </h2>
                    <div class="section-divider"></div>
                    <p class="text-xs sm:text-sm text-slate-600 mt-3">
                        Hình ảnh thi công thực tế tại công trường phần thô, hoàn thiện nhà phố, biệt thự, căn hộ và văn phòng ở Đà Nẵng.
                    </p>
                </div>

                <!-- Thanh lọc danh mục trang chủ: chữ nhỏ gọn, không xuống dòng từng tên danh mục -->
                <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-7" id="constructionTabs">
                    <button type="button" onclick="filterConstruction('all')" data-cat="all" class="cat-tab px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-brand-navy text-white transition">Tất cả</button>
                    <button type="button" onclick="filterConstruction('nha-pho')" data-cat="nha-pho" class="cat-tab px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-gold hover:text-white transition">Nhà phố</button>
                    <button type="button" onclick="filterConstruction('biet-thu')" data-cat="biet-thu" class="cat-tab px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-gold hover:text-white transition">Biệt thự</button>
                    <button type="button" onclick="filterConstruction('can-ho')" data-cat="can-ho" class="cat-tab px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-gold hover:text-white transition">Khách sạn – Căn hộ – Phòng trọ</button>
                    <button type="button" onclick="filterConstruction('van-phong')" data-cat="van-phong" class="cat-tab px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-gold hover:text-white transition">Văn phòng</button>
                    <button type="button" onclick="filterConstruction('phan-tho')" data-cat="phan-tho" class="cat-tab px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-gold hover:text-white transition">Thi công phần thô</button>
                    <button type="button" onclick="filterConstruction('hoan-thien')" data-cat="hoan-thien" class="cat-tab px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-gold hover:text-white transition">Thi công hoàn thiện</button>
                </div>

                <!-- Lưới công trình thực tế: 2 cột trên điện thoại, 3 cột trên máy tính -->
                <div id="constructionGrid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
                    <!-- Nội dung được render tự động từ dữ liệu 9 ảnh Google Drive thực tế -->
                </div>
            </div>
        </section>

        <!-- ========================================================= -->
        <!-- UX BUILDER SECTION 5: CÁC DỰ ÁN TẠI ĐÀ NẴNG (10 ẢNH DRIVE NHÓM 2) -->
        <!-- Chia 2 cột trên điện thoại, 5 cột cân đối (2 hàng x 5) trên máy tính -->
        <!-- ========================================================= -->
        <section id="du-an-da-nang" class="py-10 sm:py-14 bg-brand-slateBg border-y border-slate-200/80">
            <div class="flatsome-container">
                <div class="text-center max-w-2xl mx-auto mb-8">
                    <h2 class="text-xl sm:text-2xl font-extrabold text-brand-navy uppercase tracking-tight">
                        Các Dự Án Tiêu Biểu Ở Đà Nẵng
                    </h2>
                    <div class="section-divider"></div>
                    <p class="text-xs sm:text-sm text-slate-600 mt-3">
                        Tổng hợp các công trình nhà ở, biệt thự, căn hộ dịch vụ và nhà phố đã và đang triển khai tại các quận Hải Châu, Thanh Khê, Sơn Trà, Ngũ Hành Sơn, Cẩm Lệ, Liên Chiểu.
                    </p>
                </div>

                <!-- 2 cột trên điện thoại, 3 cột trên tablet, 5 cột trên desktop -->
                <div id="danangProjectsGrid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                    <!-- Nội dung được render từ dữ liệu 10 ảnh dự án Google Drive -->
                </div>
            </div>
        </section>

        <!-- ========================================================= -->
        <!-- UX BUILDER SECTION 6: BÁO GIÁ XÂY DỰNG TẠI ĐÀ NẴNG -->
        <!-- ========================================================= -->
        <section id="bao-gia" class="py-10 sm:py-14 bg-white">
            <div class="flatsome-container">
                <div class="text-center max-w-2xl mx-auto mb-8">
                    <h2 class="text-xl sm:text-2xl font-extrabold text-brand-navy uppercase tracking-tight">
                        Bảng Báo Giá Xây Dựng Tham Khảo
                    </h2>
                    <div class="section-divider"></div>
                    <p class="text-xs sm:text-sm text-slate-600 mt-3">
                        Đơn giá minh bạch theo từng gói dịch vụ tại Đà Nẵng. Liên hệ trực tiếp 0905.233.903 để nhận dự toán chi tiết theo diện tích đất.
                    </p>
                </div>

                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <div class="bg-brand-slateBg rounded-xl p-4 sm:p-5 border border-slate-200 flex flex-col justify-between">
                        <div>
                            <h3 class="text-[13px] sm:text-sm font-bold text-brand-navy leading-snug">Báo Giá Thiết Kế Kiến Trúc</h3>
                            <div class="text-base sm:text-xl font-extrabold text-brand-gold mt-2">120.000 – 180.000 đ/m²</div>
                            <ul class="mt-3 space-y-1.5 text-[11px] sm:text-xs text-slate-600">
                                <li>• Phối cảnh 3D mặt tiền</li>
                                <li>• Hồ sơ kết cấu &amp; điện nước</li>
                                <li>• Hỗ trợ xin giấy phép xây dựng</li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" class="mt-4 block text-center py-2 px-3 rounded-lg bg-brand-navy hover:bg-brand-gold text-white text-xs font-semibold transition">Yêu cầu báo giá</a>
                    </div>

                    <div class="bg-brand-slateBg rounded-xl p-4 sm:p-5 border border-slate-200 flex flex-col justify-between">
                        <div>
                            <h3 class="text-[13px] sm:text-sm font-bold text-brand-navy leading-snug">Báo Giá Thi Công Phần Thô</h3>
                            <div class="text-base sm:text-xl font-extrabold text-brand-gold mt-2">3.400.000 – 3.700.000 đ/m²</div>
                            <ul class="mt-3 space-y-1.5 text-[11px] sm:text-xs text-slate-600">
                                <li>• Nhân công hoàn thiện toàn bộ</li>
                                <li>• Thép Hòa Phát / Việt Nhật</li>
                                <li>• Bê tông tươi chuẩn mác kỹ thuật</li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" class="mt-4 block text-center py-2 px-3 rounded-lg bg-brand-navy hover:bg-brand-gold text-white text-xs font-semibold transition">Yêu cầu báo giá</a>
                    </div>

                    <div class="bg-brand-slateBg rounded-xl p-4 sm:p-5 border border-slate-200 flex flex-col justify-between">
                        <div>
                            <h3 class="text-[13px] sm:text-sm font-bold text-brand-navy leading-snug">Báo Giá Thi Công Hoàn Thiện</h3>
                            <div class="text-base sm:text-xl font-extrabold text-brand-gold mt-2">2.400.000 – 3.100.000 đ/m²</div>
                            <ul class="mt-3 space-y-1.5 text-[11px] sm:text-xs text-slate-600">
                                <li>• Ốp lát gạch, đá granite cầu thang</li>
                                <li>• Sơn nước chống thấm ngoại thất</li>
                                <li>• Cửa nhôm kính, thiết bị vệ sinh</li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" class="mt-4 block text-center py-2 px-3 rounded-lg bg-brand-navy hover:bg-brand-gold text-white text-xs font-semibold transition">Yêu cầu báo giá</a>
                    </div>

                    <div class="bg-brand-navy rounded-xl p-4 sm:p-5 border border-brand-navy text-white flex flex-col justify-between">
                        <div>
                            <h3 class="text-[13px] sm:text-sm font-bold text-white leading-snug">Báo Giá Xây Nhà Trọn Gói</h3>
                            <div class="text-base sm:text-xl font-extrabold text-brand-gold mt-2">5.600.000 – 6.800.000 đ/m²</div>
                            <ul class="mt-3 space-y-1.5 text-[11px] sm:text-xs text-slate-200">
                                <li>• Miễn phí thiết kế kiến trúc</li>
                                <li>• Chìa khóa trao tay không phát sinh</li>
                                <li>• Bảo hành kết cấu lên đến 5 năm</li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" class="mt-4 block text-center py-2 px-3 rounded-lg bg-brand-gold hover:bg-brand-goldHover text-white text-xs font-semibold transition">Nhận dự toán ngay</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- ========================================================= -->
        <!-- UX BUILDER SECTION 7: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ -->
        <!-- ========================================================= -->
        <section id="form-bao-gia" class="py-10 sm:py-14 bg-brand-navy text-white">
            <div class="flatsome-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                    <div class="lg:col-span-5">
                        <p class="text-xs font-bold uppercase tracking-widest text-brand-gold mb-2">Miễn phí tư vấn 24/7</p>
                        <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold leading-snug mb-3">
                            Đăng Ký Nhận Tư Vấn &amp; Báo Giá Xây Dựng Chi Tiết
                        </h2>
                        <p class="text-xs sm:text-sm text-slate-300 leading-relaxed mb-5">
                            Để lại thông tin nhu cầu xây dựng của anh/chị. Kỹ sư của <strong>xaydungdanang.com</strong> sẽ liên hệ khảo sát mặt bằng và gửi bảng dự toán chi tiết trong thời gian sớm nhất.
                        </p>
                        <div class="space-y-2.5 text-xs sm:text-sm text-slate-200">
                            <div class="flex items-center gap-2.5">
                                <span class="w-8 h-8 rounded-lg bg-white/10 text-brand-gold flex items-center justify-center shrink-0">
                                    <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
                                </span>
                                <span>Hotline / Zalo: <strong class="text-white">0905.233.903</strong></span>
                            </div>
                            <div class="flex items-center gap-2.5">
                                <span class="w-8 h-8 rounded-lg bg-white/10 text-brand-gold flex items-center justify-center shrink-0">
                                    <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                                </span>
                                <span>Khu vực hoạt động: <strong class="text-white">Thành phố Đà Nẵng</strong></span>
                            </div>
                        </div>
                    </div>

                    <div class="lg:col-span-7">
                        <form id="quoteForm" class="bg-white text-slate-800 rounded-xl p-5 sm:p-7 shadow-lg">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label for="customerName" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
                                    <input id="customerName" name="customerName" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none">
                                </div>
                                <div>
                                    <label for="customerPhone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                    <input id="customerPhone" name="customerPhone" type="tel" required placeholder="VD: 0905 xxx xxx" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none">
                                </div>
                                <div>
                                    <label for="projectType" class="block text-xs font-semibold text-slate-700 mb-1">Loại công trình</label>
                                    <select id="projectType" name="projectType" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none">
                                        <option value="Nhà phố">Nhà phố</option>
                                        <option value="Biệt thự">Biệt thự</option>
                                        <option value="Khách sạn - Căn hộ - Phòng trọ">Khách sạn – Căn hộ – Phòng trọ</option>
                                        <option value="Văn phòng">Văn phòng</option>
                                        <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                    </select>
                                </div>
                                <div>
                                    <label for="budgetRange" class="block text-xs font-semibold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                                    <select id="budgetRange" name="budgetRange" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none">
                                        <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                        <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                                        <option value="1 tỷ - 2 tỷ" selected>1 tỷ – 2 tỷ</option>
                                        <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                                        <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                    </select>
                                </div>
                                <div class="sm:col-span-2">
                                    <label for="customerNote" class="block text-xs font-semibold text-slate-700 mb-1">Mô tả diện tích đất &amp; yêu cầu thêm</label>
                                    <textarea id="customerNote" name="customerNote" rows="3" placeholder="VD: Đất 5x20m tại Hòa Xuân, dự kiến xây nhà 3 tầng..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none"></textarea>
                                </div>
                            </div>

                            <div class="mt-4 flex flex-col sm:flex-row sm:items-center justify-between gap-3">
                                <button type="submit" class="w-full sm:w-auto px-6 py-3 rounded-lg bg-brand-gold hover:bg-brand-goldHover text-white text-sm font-bold transition shadow-sm">
                                    Gửi Yêu Cầu Báo Giá
                                </button>
                                <span class="text-[11px] text-slate-500">Hoặc gọi trực tiếp: <strong class="text-brand-navy">0905.233.903</strong></span>
                            </div>

                            <!-- Thông báo phản hồi trực tiếp trên giao diện (không dùng alert) -->
                            <div id="quoteFeedback" class="hidden mt-4 p-3.5 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-medium"></div>
                        </form>
                    </div>
                </div>
            </div>
        </section>

        <!-- ========================================================= -->
        <!-- UX BUILDER SECTION 8: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ -->
        <!-- ========================================================= -->
        <section id="tin-tuc" class="py-10 sm:py-14 bg-white">
            <div class="flatsome-container">
                <div class="text-center max-w-2xl mx-auto mb-8">
                    <h2 class="text-xl sm:text-2xl font-extrabold text-brand-navy uppercase tracking-tight">
                        Tin Tức &amp; Kinh Nghiệm Xây Nhà
                    </h2>
                    <div class="section-divider"></div>
                    <p class="text-xs sm:text-sm text-slate-600 mt-3">
                        Cập nhật quy định xây dựng tại Đà Nẵng, kinh nghiệm chọn vật liệu, kỹ thuật bảo dưỡng bê tông và tối ưu chi phí làm nhà.
                    </p>
                </div>

                <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div id="articlesGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <!-- Bài viết được render bằng JS để hỗ trợ mở đọc chi tiết -->
                </div>
            </div>
        </section>

        <!-- ========================================================= -->
        <!-- UX BUILDER SECTION 9: DANH MỤC CÁC ĐỐI TÁC -->
        <!-- ========================================================= -->
        <section id="doi-tac" class="py-10 sm:py-12 bg-brand-slateBg border-y border-slate-200/80">
            <div class="flatsome-container">
                <div class="text-center max-w-2xl mx-auto mb-7">
                    <h2 class="text-xl sm:text-2xl font-extrabold text-brand-navy uppercase tracking-tight">
                        Đối Tác Cung Cấp Vật Tư Uy Tín
                    </h2>
                    <div class="section-divider"></div>
                    <p class="text-xs sm:text-sm text-slate-600 mt-2.5">
                        Hợp tác cùng các thương hiệu vật liệu xây dựng hàng đầu đảm bảo chất lượng bền vững cho mọi công trình.
                    </p>
                </div>

                <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-3">
                    <div class="bg-white rounded-xl border border-slate-200 p-3.5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                        <span class="text-xs sm:text-sm font-extrabold text-brand-navy tracking-tight">HÒA PHÁT</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Thép xây dựng</span>
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 p-3.5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                        <span class="text-xs sm:text-sm font-extrabold text-brand-navy tracking-tight">SÔNG GIANH</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Xi măng</span>
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 p-3.5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                        <span class="text-xs sm:text-sm font-extrabold text-brand-navy tracking-tight">JOTUN</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Sơn cao cấp</span>
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 p-3.5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                        <span class="text-xs sm:text-sm font-extrabold text-brand-navy tracking-tight">CADIVI</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Dây cáp điện</span>
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 p-3.5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                        <span class="text-xs sm:text-sm font-extrabold text-brand-navy tracking-tight">BÌNH MINH</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Ống cấp thoát nước</span>
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 p-3.5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                        <span class="text-xs sm:text-sm font-extrabold text-brand-navy tracking-tight">XINGFA</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Nhôm kính</span>
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 p-3.5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                        <span class="text-xs sm:text-sm font-extrabold text-brand-navy tracking-tight">TOTO</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Thiết bị vệ sinh</span>
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 p-3.5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                        <span class="text-xs sm:text-sm font-extrabold text-brand-navy tracking-tight">ĐỒNG TÂM</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Gạch ốp lát</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- ========================================================= -->
        <!-- UX BUILDER SECTION 10: GOOGLE MAP ĐÀ NẴNG & FANPAGE FACEBOOK TRANG CHỦ -->
        <!-- ========================================================= -->
        <section id="lien-he" class="py-10 sm:py-14 bg-white">
            <div class="flatsome-container">
                <div class="text-center max-w-2xl mx-auto mb-8">
                    <h2 class="text-xl sm:text-2xl font-extrabold text-brand-navy uppercase tracking-tight">
                        Bản Đồ Google Map &amp; Kết Nối Fanpage
                    </h2>
                    <div class="section-divider"></div>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                    <!-- Cột trái: Google Map Đà Nẵng -->
                    <div class="lg:col-span-7 bg-brand-slateBg rounded-xl border border-slate-200 p-4 flex flex-col">
                        <div class="flex items-center justify-between gap-2 mb-3">
                            <div>
                                <h3 class="text-sm sm:text-base font-bold text-brand-navy">Bản Đồ Khu Vực Hoạt Động – Đà Nẵng</h3>
                                <p class="text-xs text-slate-600">Địa chỉ: Thành phố Đà Nẵng • Hotline: 0905.233.903</p>
                            </div>
                            <a href="https://maps.google.com/?q=Da+Nang,+Vietnam" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-brand-gold hover:text-brand-navy whitespace-nowrap">
                                Mở Google Map &rarr;
                            </a>
                        </div>
                        <div class="w-full rounded-lg overflow-hidden border border-slate-200 flex-1 min-h-[280px] sm:min-h-[340px] bg-slate-200">
                            <iframe
                                title="Bản đồ Google Map Xây Dựng Nhà Ở Đà Nẵng"
                                src="https://maps.google.com/maps?q=%C4%90%C3%A0%20N%E1%BA%B5ng,%20Vi%E1%BB%87t%20Nam&t=&z=12&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-full min-h-[280px] sm:min-h-[340px] border-0"
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>

                    <!-- Cột phải: Fanpage Facebook ra ngoài trang chủ -->
                    <div class="lg:col-span-5 bg-brand-slateBg rounded-xl border border-slate-200 p-4 flex flex-col justify-between">
                        <div>
                            <div class="flex items-center justify-between gap-2 mb-3">
                                <h3 class="text-sm sm:text-base font-bold text-brand-navy">Fanpage Facebook Chính Thức</h3>
                                <a href="https://www.facebook.com/profile.php?id=100063678894623" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-blue-600 hover:underline whitespace-nowrap">
                                    Xem trên Facebook
                                </a>
                            </div>

                            <!-- Thẻ nhận diện Fanpage hiển thị rõ nét ngay cả khi trình duyệt chặn iframe bên thứ 3 -->
                            <div class="bg-white rounded-lg border border-slate-200 overflow-hidden mb-3">
                                <div class="relative h-28 bg-brand-navy overflow-hidden">
                                    <img src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w800" data-drive-id="1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff" alt="Ảnh bìa Fanpage Xây Dựng Nhà Ở Đà Nẵng" class="drive-img w-full h-full object-cover opacity-55">
                                    <div class="absolute inset-0 bg-gradient-to-t from-brand-navyDark/90 via-brand-navyDark/40 to-transparent"></div>
                                    <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                                        <div class="w-12 h-12 rounded-lg bg-brand-navy border-2 border-white flex items-center justify-center shrink-0 shadow">
                                            <svg class="w-8 h-8" viewBox="0 0 56 56" fill="none"><path d="M9 28.5L28 12L47 28.5H41.5V44H32.5V33H23.5V44H14.5V28.5H9Z" fill="#D97706"/><path d="M18.5 29L28 20.5L37.5 29" stroke="#FFFFFF" stroke-width="2.8" stroke-linecap="round" stroke-linejoin="round"/></svg>
                                        </div>
                                        <div class="min-w-0">
                                            <div class="text-sm font-bold text-white leading-tight break-words">Xây Dựng Nhà Ở Đà Nẵng</div>
                                            <div class="text-[11px] text-slate-200">Thiết kế &amp; Thi công nhà ở trọn gói</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="p-3.5 flex flex-wrap items-center justify-between gap-2 bg-white">
                                    <span class="text-xs text-slate-600">Cập nhật tiến độ công trình hàng ngày</span>
                                    <a href="https://www.facebook.com/profile.php?id=100063678894623" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 px-3.5 py-2 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-semibold transition">
                                        <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
                                        <span>Theo Dõi Fanpage</span>
                                    </a>
                                </div>
                            </div>

                            <!-- Nhúng Facebook Page Plugin chuẩn Flatsome -->
                            <div class="w-full rounded-lg overflow-hidden border border-slate-200 bg-white">
                                <iframe
                                    title="Fanpage Facebook Xây Dựng Nhà Ở Đà Nẵng"
                                    src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D100063678894623&tabs=timeline&width=420&height=175&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                    class="w-full h-[175px] border-0 overflow-hidden"
                                    scrolling="no"
                                    frameborder="0"
                                    allowfullscreen="true"
                                    allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                                    loading="lazy">
                                </iframe>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- ========================================================= -->
    <!-- UX BUILDER: FOOTER CHUẨN FLATSOME -->
    <!-- ========================================================= -->
    <footer class="w-full bg-brand-navyDark text-slate-300 pt-10 pb-20 sm:pb-10 border-t-4 border-brand-gold">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-white/10">
                <!-- Cột 1: Logo & Thông tin -->
                <div>
                    <div class="flex items-center gap-2.5 mb-3">
                        <svg class="w-9 h-9 shrink-0" viewBox="0 0 56 56" fill="none">
                            <rect width="56" height="56" rx="10" fill="#0F2A4A" stroke="#D97706" stroke-width="2"/>
                            <path d="M9 28.5L28 12L47 28.5H41.5V44H32.5V33H23.5V44H14.5V28.5H9Z" fill="#D97706"/>
                            <path d="M18.5 29L28 20.5L37.5 29" stroke="#FFFFFF" stroke-width="2.6" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                        <div>
                            <div class="text-sm font-extrabold text-white">XÂY DỰNG ĐÀ NẴNG</div>
                            <div class="text-[11px] text-brand-gold font-semibold">xaydungdanang.com</div>
                        </div>
                    </div>
                    <p class="text-xs leading-relaxed text-slate-400 mb-3">
                        Đơn vị chuyên thiết kế kiến trúc, thi công xây dựng phần thô, hoàn thiện nhà phố, biệt thự, căn hộ, khách sạn uy tín tại Đà Nẵng.
                    </p>
                    <ul class="space-y-1.5 text-xs">
                        <li><strong class="text-white">Địa chỉ:</strong> Thành phố Đà Nẵng</li>
                        <li><strong class="text-white">Hotline:</strong> <a href="tel:0905233903" class="text-brand-gold hover:underline">0905.233.903</a></li>
                        <li><strong class="text-white">Website:</strong> xaydungdanang.com</li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div>
                    <h4 class="text-xs font-bold uppercase tracking-wider text-white mb-3">Lĩnh Vực Hoạt Động</h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-gold transition">Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-gold transition">Thi công phần thô chuẩn kỹ thuật</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-gold transition">Thi công hoàn thiện trọn gói</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-gold transition">Thi công nội thất &amp; Cải tạo nhà</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục công trình -->
                <div>
                    <h4 class="text-xs font-bold uppercase tracking-wider text-white mb-3">Danh Mục Công Trình</h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho')" class="hover:text-brand-gold transition">Thi công Nhà phố Đà Nẵng</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('biet-thu')" class="hover:text-brand-gold transition">Thi công Biệt thự hiện đại</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('can-ho')" class="hover:text-brand-gold transition">Khách sạn – Căn hộ – Phòng trọ</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-brand-gold transition">Dự án tiêu biểu tại Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Liên hệ nhanh -->
                <div>
                    <h4 class="text-xs font-bold uppercase tracking-wider text-white mb-3">Hỗ Trợ Khách Hàng</h4>
                    <ul class="space-y-2 text-xs mb-4">
                        <li><a href="#bao-gia" class="hover:text-brand-gold transition">Bảng báo giá xây dựng mới nhất</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-brand-gold transition">Đăng ký khảo sát &amp; tư vấn miễn phí</a></li>
                        <li><a href="#tin-tuc" class="hover:text-brand-gold transition">Kinh nghiệm xây nhà tại Đà Nẵng</a></li>
                        <li><a href="https://www.facebook.com/profile.php?id=100063678894623" target="_blank" rel="noopener noreferrer" class="hover:text-brand-gold transition">Fanpage Xây Dựng Nhà Ở Đà Nẵng</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
                <p>Copyright 2026 &copy; <strong>Xây Dựng Nhà Ở Đà Nẵng</strong> – xaydungdanang.com</p>
                <p>Hotline tư vấn: <a href="tel:0905233903" class="text-brand-gold font-semibold">0905.233.903</a></p>
            </div>
        </div>
    </footer>

    <!-- ========================================================= -->
    <!-- CỤM NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (MÁY TÍNH & ĐIỆN THOẠI) -->
    <!-- ========================================================= -->
    <!-- Giao diện Máy tính: Cụm nút nổi gọn góc phải dưới -->
    <div class="hidden sm:flex fixed right-4 bottom-5 z-50 flex-col items-end gap-2.5">
        <a href="https://www.facebook.com/profile.php?id=100063678894623" target="_blank" rel="noopener noreferrer" aria-label="Nhắn tin Facebook" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition">
            <svg class="w-5 h-5 shrink-0" fill="currentColor" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
            <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
        </a>

        <a href="https://zalo.me/0905233903" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0905.233.903" class="group flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition">
            <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="text-xs font-bold whitespace-nowrap">Chat Zalo</span>
        </a>

        <a href="tel:0905233903" aria-label="Gọi Hotline 0905.233.903" class="pulse-hotline flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition">
            <svg class="w-5 h-5 shrink-0" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
            <span class="text-xs font-extrabold whitespace-nowrap">0905.233.903</span>
        </a>
    </div>

    <!-- Giao diện Điện thoại: Thanh liên hệ nổi cố định dưới đáy màn hình (không tràn viền, dễ bấm) -->
    <div class="sm:hidden fixed bottom-0 left-0 right-0 z-50 bg-white border-t border-slate-200 shadow-[0_-4px_12px_rgba(0,0,0,0.08)] px-2 py-2 grid grid-cols-3 gap-2">
        <a href="tel:0905233903" class="flex items-center justify-center gap-1.5 py-2.5 rounded-lg bg-red-600 text-white text-xs font-bold active:scale-95 transition">
            <svg class="w-4 h-4 shrink-0" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
            <span>Hotline</span>
        </a>
        <a href="https://zalo.me/0905233903" target="_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 py-2.5 rounded-lg bg-[#0068FF] text-white text-xs font-bold active:scale-95 transition">
            <span class="w-4 h-4 rounded-full bg-white text-[#0068FF] text-[9px] font-extrabold flex items-center justify-center shrink-0">Z</span>
            <span>Zalo</span>
        </a>
        <a href="https://www.facebook.com/profile.php?id=100063678894623" target="_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 py-2.5 rounded-lg bg-[#1877F2] text-white text-xs font-bold active:scale-95 transition">
            <svg class="w-4 h-4 shrink-0" fill="currentColor" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
            <span>Facebook</span>
        </a>
    </div>

    <!-- ========================================================= -->
    <!-- MODAL XEM ẢNH CÔNG TRÌNH / ĐỌC BÀI VIẾT CHI TIẾT -->
    <!-- ========================================================= -->
    <div id="detailModal" class="hidden fixed inset-0 z-[60] bg-black/75 backdrop-blur-sm flex items-center justify-center p-3 sm:p-6">
        <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
            <div class="flex items-center justify-between px-4 sm:px-5 py-3.5 border-b border-slate-200 sticky top-0 bg-white z-10">
                <h3 id="modalTitle" class="text-sm sm:text-base font-bold text-brand-navy pr-4"></h3>
                <button type="button" onclick="closeModal()" aria-label="Đóng cửa sổ" class="p-1.5 rounded-lg text-slate-500 hover:bg-slate-100 hover:text-slate-800">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
                </button>
            </div>
            <div class="p-4 sm:p-5">
                <div class="rounded-lg overflow-hidden bg-slate-100 mb-4 max-h-[420px] flex items-center justify-center">
                    <img id="modalImage" src="" alt="" class="w-full h-auto max-h-[420px] object-contain">
                </div>
                <p id="modalCategory" class="text-xs font-bold text-brand-gold uppercase mb-1.5"></p>
                <div id="modalBody" class="text-xs sm:text-sm text-slate-700 leading-relaxed space-y-2.5"></div>
                <div class="mt-5 pt-4 border-t border-slate-200 flex flex-wrap items-center justify-between gap-2">
                    <span class="text-xs text-slate-600">Cần tư vấn mẫu công trình tương tự?</span>
                    <a href="#form-bao-gia" onclick="closeModal()" class="px-4 py-2 rounded-lg bg-brand-gold hover:bg-brand-goldHover text-white text-xs font-bold transition">Nhận Báo Giá Ngay</a>
                </div>
            </div>
        </div>
    </div>

    <!-- ========================================================= -->
    <!-- JAVASCRIPT: DỮ LIỆU ẢNH GOOGLE DRIVE, SLIDER, LỌC DANH MỤC, FORM -->
    <!-- ========================================================= -->
    <script>
        /* Hàm tạo đường dẫn ảnh Google Drive ưu tiên tốc độ cao và có cơ chế tự động dự phòng */
        function getDriveUrl(fileId, width = 1000) {
            return `https://lh3.googleusercontent.com/d/${fileId}=w${width}`;
        }

        function attachDriveFallback(imgEl) {
            if (!imgEl || imgEl.dataset.fallbackBound) return;
            imgEl.dataset.fallbackBound = '1';
            imgEl.addEventListener('error', function () {
                const fileId = this.dataset.driveId;
                const step = parseInt(this.dataset.retryStep || '0', 10);
                if (fileId && step === 0) {
                    this.dataset.retryStep = '1';
                    this.src = `https://drive.google.com/thumbnail?id=${fileId}&sz=w1000`;
                } else if (step <= 1) {
                    this.dataset.retryStep = '2';
                    const label = encodeURIComponent(this.alt || 'Xay Dung Da Nang');
                    this.src = `https://placehold.co/800x600/0F2A4A/F59E0B?text=${label}`;
                }
            });
        }

        /* ========================================================= */
        /* NHÓM 1: 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG TỪ GOOGLE DRIVE */
        /* ========================================================= */
        const constructionWorks = [
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                title: 'Thi Công Phần Thô Nhà Phố 3 Tầng – Hòa Xuân',
                categoryLabel: 'Nhà phố • Thi công phần thô',
                categories: ['nha-pho', 'phan-tho'],
                desc: 'Công tác thi công kết cấu khung bê tông cốt thép, xây tường gạch ống đúng kỹ thuật và giám sát nghiệm thu từng giai đoạn tại Khu đô thị Hòa Xuân, Đà Nẵng.'
            },
            {
                id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                title: 'Thi Công Cốt Thép & Đổ Bê Tông Sàn – Cẩm Lệ',
                categoryLabel: 'Nhà phố • Thi công phần thô',
                categories: ['nha-pho', 'phan-tho'],
                desc: 'Đan thép sàn 2 lớp đúng bản vẽ kết cấu, sử dụng cục kê bê tông chuẩn lớp bảo vệ và đổ bê tông tươi thương phẩm đảm bảo độ bền vững cho công trình.'
            },
            {
                id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                title: 'Xây Tường & Tô Trát Hoàn Thiện Nhà Phố – Liên Chiểu',
                categoryLabel: 'Nhà phố • Thi công hoàn thiện',
                categories: ['nha-pho', 'hoan-thien'],
                desc: 'Thi công xây tường thẳng hàng, đóng lưới mắt cáo chống nứt tiếp giáp cột – tường và tô trát phẳng mịn sẵn sàng cho giai đoạn sơn bả.'
            },
            {
                id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                title: 'Thi Công Trọn Gói Căn Hộ Cho Thuê – Sơn Trà',
                categoryLabel: 'Khách sạn – Căn hộ – Phòng trọ',
                categories: ['can-ho', 'hoan-thien'],
                desc: 'Xây dựng trọn gói tòa căn hộ dịch vụ cao tầng tối ưu công năng phòng ở, hệ thống cấp thoát nước và phòng cháy chữa cháy tiêu chuẩn.'
            },
            {
                id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                title: 'Thi Công Biệt Thự Hiện Đại – Ngũ Hành Sơn',
                categoryLabel: 'Biệt thự • Thi công hoàn thiện',
                categories: ['biet-thu', 'hoan-thien'],
                desc: 'Thi công trọn gói biệt thự sân vườn với kiến trúc mở, hệ cửa nhôm kính cao cấp và giải pháp chống thấm toàn diện cho khu vực ven biển.'
            },
            {
                id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                title: 'Thi Công Móng & Khung Cột Chịu Lực – Hải Châu',
                categoryLabel: 'Nhà phố • Thi công phần thô',
                categories: ['nha-pho', 'phan-tho'],
                desc: 'Thi công hệ móng băng kiên cố, giằng móng và cột chịu lực chuẩn xác tuyệt đối về tim trục, đảm bảo an toàn cho các công trình lân cận.'
            },
            {
                id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                title: 'Hoàn Thiện Mặt Tiền Nhà Phố Hiện Đại – Thanh Khê',
                categoryLabel: 'Nhà phố • Thi công hoàn thiện',
                categories: ['nha-pho', 'hoan-thien'],
                desc: 'Hoàn thiện mặt tiền sắc nét với vật liệu ốp lát cao cấp, sơn ngoại thất chống bám bẩn và hệ thống chiếu sáng kiến trúc sang trọng.'
            },
            {
                id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                title: 'Thi Công & Cải Tạo Không Gian Văn Phòng – Hải Châu',
                categoryLabel: 'Văn phòng • Thi công hoàn thiện',
                categories: ['van-phong', 'hoan-thien'],
                desc: 'Thiết kế và thi công hoàn thiện văn phòng làm việc hiện đại, tối ưu ánh sáng tự nhiên, trần thạch cao và hệ thống điện mạng gọn gàng.'
            },
            {
                id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                title: 'Thi Công Khách Sạn Mini & Căn Hộ Biển Mỹ Khê',
                categoryLabel: 'Khách sạn – Căn hộ – Phòng trọ',
                categories: ['can-ho', 'hoan-thien'],
                desc: 'Triển khai thi công trọn gói khách sạn mini ven biển Đà Nẵng với vật liệu chống ăn mòn hơi muối và tiến độ bàn giao nhanh chóng.'
            }
        ];

        /* ========================================================= */
        /* NHÓM 2: 10 ẢNH DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG TỪ GOOGLE DRIVE */
        /* ========================================================= */
        const danangProjects = [
            {
                id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                title: 'Dự Án Nhà Phố 3 Tầng – Khu Đô Thị Hòa Xuân',
                location: 'Quận Cẩm Lệ, Đà Nẵng',
                desc: 'Công trình nhà phố 3 tầng thiết kế hiện đại, thông thoáng, thi công trọn gói từ phần thô đến hoàn thiện bàn giao chìa khóa trao tay.'
            },
            {
                id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                title: 'Dự Án Nhà Ở Gia Đình – Đường Nguyễn Phước Lan',
                location: 'Hòa Xuân, Đà Nẵng',
                desc: 'Ngôi nhà phố tối ưu ánh sáng giếng trời và mảng xanh ban công, thi công đảm bảo chuẩn kỹ thuật và tiến độ cam kết.'
            },
            {
                id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
                title: 'Dự Án Biệt Thự Sân Vườn – Khu Nam Việt Á',
                location: 'Quận Ngũ Hành Sơn, Đà Nẵng',
                desc: 'Biệt thự 2 mặt tiền sang trọng với không gian phòng khách liên thông bếp và sân vườn thoáng mát.'
            },
            {
                id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                title: 'Dự Án Tòa Căn Hộ Dịch Vụ Cho Thuê – An Thượng',
                location: 'Quận Ngũ Hành Sơn, Đà Nẵng',
                desc: 'Thi công căn hộ dịch vụ cao tầng đáp ứng nhu cầu lưu trú du lịch và chuyên gia tại khu vực biển Đà Nẵng.'
            },
            {
                id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
                title: 'Dự Án Nhà Phố Mặt Tiền Kinh Doanh – Hải Châu',
                location: 'Quận Hải Châu, Đà Nẵng',
                desc: 'Thiết kế nhà phố kết hợp mặt bằng kinh doanh tầng trệt và không gian sinh hoạt riêng tư cho gia đình ở các tầng trên.'
            },
            {
                id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
                title: 'Dự Án Nhà Phố 2 Tầng 1 Tum – Khu Phước Lý',
                location: 'Quận Liên Chiểu, Đà Nẵng',
                desc: 'Giải pháp xây dựng tối ưu ngân sách cho gia đình trẻ với đầy đủ 3 phòng ngủ, phòng thờ và sân thượng rộng rãi.'
            },
            {
                id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
                title: 'Dự Án Khách Sạn Boutique – Quận Sơn Trà',
                location: 'Quận Sơn Trà, Đà Nẵng',
                desc: 'Công trình khách sạn phong cách hiện đại gần biển Mỹ Khê, được đội ngũ kỹ sư giám sát kỹ lưỡng từng công đoạn.'
            },
            {
                id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
                title: 'Dự Án Nhà Phố Hiện Đại – Quận Thanh Khê',
                location: 'Quận Thanh Khê, Đà Nẵng',
                desc: 'Thi công nhà phố trong khu dân cư đông đúc đảm bảo an toàn tuyệt đối, gọn gàng vệ sinh công trường và thẩm mỹ cao.'
            },
            {
                id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
                title: 'Dự Án Biệt Thự Nghỉ Dưỡng – Ven Sông Hàn',
                location: 'Thành phố Đà Nẵng',
                desc: 'Biệt thự phong cách đương đại với vật liệu hoàn thiện cao cấp, mang lại trải nghiệm sống đẳng cấp và bền bỉ theo thời gian.'
            },
            {
                id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
                title: 'Dự Án Văn Phòng & Showroom – Trung Tâm Đà Nẵng',
                location: 'Quận Hải Châu, Đà Nẵng',
                desc: 'Thi công kết cấu và hoàn thiện mặt dựng kính cho tòa nhà văn phòng thương mại hiện đại tại trung tâm thành phố.'
            }
        ];

        /* ========================================================= */
        /* DỮ LIỆU DANH MỤC BÀI VIẾT TRANG CHỦ */
        /* ========================================================= */
        const newsArticles = [
            {
                title: 'Quy Định Chiều Cao & Mật Độ Xây Dựng Nhà Ở Đà Nẵng Mới Nhất',
                date: 'Cập nhật mới nhất',
                imageId: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                excerpt: 'Tổng hợp quy định khoảng lùi, mật độ xây dựng và số tầng cho phép theo lộ giới đường tại Đà Nẵng để xin phép nhanh chóng.',
                content: 'Khi chuẩn bị xây dựng nhà ở tại Đà Nẵng, chủ đầu tư cần nắm rõ mật độ xây dựng tối đa theo diện tích lô đất (từ 70% đến 100% tùy diện tích), quy định khoảng lùi theo lộ giới đường và chiều cao từng tầng. Đội ngũ xaydungdanang.com luôn hỗ trợ kiểm tra quy hoạch và hoàn thiện hồ sơ xin phép xây dựng miễn phí khi ký hợp đồng thi công.'
            },
            {
                title: 'Hướng Dẫn Bảo Dưỡng Bê Tông Móng & Sàn Đúng Kỹ Thuật',
                date: 'Kỹ thuật thi công',
                imageId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                excerpt: 'Giữ ẩm đúng cách trong 7 ngày đầu sau khi đổ bê tông giúp kết cấu đạt cường độ tối đa và hạn chế nứt chân chim.',
                content: 'Với thời tiết nắng gió đặc trưng của Đà Nẵng, bê tông rất dễ bị mất nước nhanh sau khi đổ. Việc che phủ bao bố giữ ẩm, tưới nước định kỳ 3–4 lần/ngày trong 7 ngày đầu tiên và chỉ tháo cốp pha đúng thời gian quy định là yếu tố then chốt quyết định tuổi thọ kết cấu ngôi nhà.'
            },
            {
                title: 'Kinh Nghiệm Chọn Nhà Thầu Xây Nhà Trọn Gói Uy Tín Tại Đà Nẵng',
                date: 'Kinh nghiệm làm nhà',
                imageId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                excerpt: '5 tiêu chí quan trọng giúp gia chủ tránh phát sinh chi phí và đảm bảo chất lượng vật tư khi xây dựng tổ ấm.',
                content: 'Để chọn đúng nhà thầu uy tín, gia chủ nên tham quan trực tiếp các công trình đang thi công thực tế, kiểm tra bảng chủng loại vật tư rõ ràng trong hợp đồng, xác nhận tiến độ thanh toán theo từng giai đoạn nghiệm thu và yêu cầu cam kết bảo hành kết cấu – chống thấm rõ ràng.'
            },
            {
                title: 'Giải Pháp Chống Thấm Tường & Sân Thượng Cho Nhà Ven Biển',
                date: 'Tư vấn vật liệu',
                imageId: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                excerpt: 'Mùa mưa bão miền Trung đòi hỏi quy trình xử lý cổ ống, sàn mái và tường ngoài bài bản ngay từ giai đoạn phần thô.',
                content: 'Chống thấm hiệu quả phải bắt đầu từ khâu đổ bê tông đầm kỹ, tạo độ dốc thoát nước chuẩn, xử lý cổ ống xuyên sàn bằng vữa không co ngót và quét ít nhất 2–3 lớp màng chống thấm gốc xi măng – polymer trước khi cán vữa bảo vệ và lát gạch.'
            }
        ];

        /* Render Công trình thi công thực tế theo danh mục */
        function renderConstruction(category = 'all') {
            const grid = document.getElementById('constructionGrid');
            if (!grid) return;

            const filtered = category === 'all'
                ? constructionWorks
                : constructionWorks.filter(item => item.categories.includes(category));

            grid.innerHTML = filtered.map((item, idx) => `
                <article onclick="openWorkModal(${constructionWorks.indexOf(item)})" class="cursor-pointer group bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img
                            src="${getDriveUrl(item.id, 900)}"
                            data-drive-id="${item.id}"
                            alt="${item.title}"
                            loading="lazy"
                            class="drive-img w-full h-full object-cover group-hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10px] sm:text-[11px] font-semibold text-brand-gold mb-1 leading-tight">${item.categoryLabel}</p>
                            <h3 class="text-[12.5px] sm:text-sm font-bold text-brand-navy group-hover:text-brand-gold transition leading-snug break-words">
                                ${item.title}
                            </h3>
                        </div>
                        <span class="mt-2.5 text-[11px] font-semibold text-slate-500 group-hover:text-brand-navy transition">Xem chi tiết &rarr;</span>
                    </div>
                </article>
            `).join('');

            grid.querySelectorAll('img.drive-img').forEach(attachDriveFallback);
        }

        function filterConstruction(category) {
            renderConstruction(category);
            document.querySelectorAll('#constructionTabs .cat-tab').forEach(btn => {
                const isActive = btn.dataset.cat === category;
                btn.className = isActive
                    ? 'cat-tab px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-brand-navy text-white transition'
                    : 'cat-tab px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-gold hover:text-white transition';
            });
        }

        /* Render 10 Dự án tiêu biểu ở Đà Nẵng */
        function renderDanangProjects() {
            const grid = document.getElementById('danangProjectsGrid');
            if (!grid) return;

            grid.innerHTML = danangProjects.map((project, index) => `
                <article onclick="openProjectModal(${index})" class="cursor-pointer group bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img
                            src="${getDriveUrl(project.id, 800)}"
                            data-drive-id="${project.id}"
                            alt="${project.title}"
                            loading="lazy"
                            class="drive-img w-full h-full object-cover group-hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-[12px] sm:text-[13px] font-bold text-brand-navy group-hover:text-brand-gold transition leading-snug break-words">
                                ${project.title}
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1">${project.location}</p>
                        </div>
                    </div>
                </article>
            `).join('');

            grid.querySelectorAll('img.drive-img').forEach(attachDriveFallback);
        }

        /* Render Danh mục bài viết trang chủ */
        function renderArticles() {
            const grid = document.getElementById('articlesGrid');
            if (!grid) return;

            grid.innerHTML = newsArticles.map((art, index) => `
                <article onclick="openArticleModal(${index})" class="cursor-pointer group bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img
                            src="${getDriveUrl(art.imageId, 800)}"
                            data-drive-id="${art.imageId}"
                            alt="${art.title}"
                            loading="lazy"
                            class="drive-img w-full h-full object-cover group-hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10px] sm:text-[11px] font-semibold text-brand-gold mb-1">${art.date}</p>
                            <h3 class="text-[12.5px] sm:text-sm font-bold text-brand-navy group-hover:text-brand-gold transition leading-snug break-words">
                                ${art.title}
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                ${art.excerpt}
                            </p>
                        </div>
                        <span class="mt-3 text-[11px] font-bold text-brand-navy group-hover:text-brand-gold transition">Đọc tiếp &rarr;</span>
                    </div>
                </article>
            `).join('');

            grid.querySelectorAll('img.drive-img').forEach(attachDriveFallback);
        }

        /* Điều khiển Modal xem chi tiết */
        function showModal(title, category, imageId, bodyText) {
            const modal = document.getElementById('detailModal');
            const img = document.getElementById('modalImage');
            document.getElementById('modalTitle').textContent = title;
            document.getElementById('modalCategory').textContent = category;
            document.getElementById('modalBody').textContent = bodyText;
            img.dataset.driveId = imageId;
            img.dataset.retryStep = '0';
            img.alt = title;
            img.src = getDriveUrl(imageId, 1200);
            attachDriveFallback(img);
            modal.classList.remove('hidden');
            document.body.style.overflow = 'hidden';
        }

        function openWorkModal(index) {
            const item = constructionWorks[index];
            if (!item) return;
            showModal(item.title, item.categoryLabel, item.id, item.desc);
        }

        function openProjectModal(index) {
            const item = danangProjects[index];
            if (!item) return;
            showModal(item.title, `Dự án tại ${item.location}`, item.id, item.desc);
        }

        function openArticleModal(index) {
            const item = newsArticles[index];
            if (!item) return;
            showModal(item.title, item.date, item.imageId, item.content);
        }

        function closeModal() {
            document.getElementById('detailModal').classList.add('hidden');
            document.body.style.overflow = '';
        }

        document.getElementById('detailModal').addEventListener('click', function (e) {
            if (e.target === this) closeModal();
        });

        /* ========================================================= */
        /* ĐIỀU KHIỂN 2 BANNER TỰ TRƯỢT + VUỐT CẢM ỨNG TRÊN ĐIỆN THOẠI */
        /* ========================================================= */
        let currentSlide = 0;
        const totalSlides = 2;
        let slideTimer = null;

        function updateSlider() {
            const track = document.getElementById('heroTrack');
            if (!track) return;
            track.style.transform = `translateX(-${currentSlide * 50}%)`;

            const d0 = document.getElementById('dot0');
            const d1 = document.getElementById('dot1');
            if (d0 && d1) {
                d0.className = currentSlide === 0 ? 'w-6 h-2 rounded-full bg-brand-gold transition-all' : 'w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all';
                d1.className = currentSlide === 1 ? 'w-6 h-2 rounded-full bg-brand-gold transition-all' : 'w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all';
            }
        }

        function goToSlide(index) {
            currentSlide = (index + totalSlides) % totalSlides;
            updateSlider();
            restartAutoSlide();
        }

        function restartAutoSlide() {
            if (slideTimer) clearInterval(slideTimer);
            slideTimer = setInterval(() => {
                currentSlide = (currentSlide + 1) % totalSlides;
                updateSlider();
            }, 5200);
        }

        /* Điều khiển menu điện thoại */
        const mobileMenuBtn = document.getElementById('mobileMenuBtn');
        const mobileMenuPanel = document.getElementById('mobileMenuPanel');
        const menuIconOpen = document.getElementById('menuIconOpen');
        const menuIconClose = document.getElementById('menuIconClose');

        function closeMobileMenu() {
            mobileMenuPanel.classList.add('hidden');
            menuIconOpen.classList.remove('hidden');
            menuIconClose.classList.add('hidden');
        }

        mobileMenuBtn.addEventListener('click', function () {
            const isHidden = mobileMenuPanel.classList.contains('hidden');
            if (isHidden) {
                mobileMenuPanel.classList.remove('hidden');
                menuIconOpen.classList.add('hidden');
                menuIconClose.classList.remove('hidden');
            } else {
                closeMobileMenu();
            }
        });

        /* Xử lý Form yêu cầu báo giá trang chủ */
        document.getElementById('quoteForm').addEventListener('submit', function (e) {
            e.preventDefault();
            const name = document.getElementById('customerName').value.trim();
            const phone = document.getElementById('customerPhone').value.trim();
            const projectType = document.getElementById('projectType').value;
            const budget = document.getElementById('budgetRange').value;
            const feedback = document.getElementById('quoteFeedback');

            if (!name || !phone) {
                feedback.className = 'mt-4 p-3.5 rounded-lg bg-amber-50 border border-amber-200 text-amber-800 text-xs sm:text-sm font-medium';
                feedback.textContent = 'Vui lòng nhập đầy đủ họ tên và số điện thoại để chúng tôi liên hệ báo giá.';
                return;
            }

            feedback.className = 'mt-4 p-3.5 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-medium';
            feedback.textContent = `Cảm ơn ${name}! Yêu cầu báo giá công trình "${projectType}" (${budget}) đã được ghi nhận. Kỹ sư của xaydungdanang.com sẽ liên hệ qua số ${phone} hoặc Hotline 0905.233.903 trong thời gian sớm nhất.`;
            this.reset();
        });

        /* Khởi tạo toàn bộ trang */
        document.addEventListener('DOMContentLoaded', function () {
            document.querySelectorAll('img.drive-img').forEach(attachDriveFallback);
            renderConstruction('all');
            renderDanangProjects();
            renderArticles();

            document.getElementById('prevSlideBtn').addEventListener('click', () => goToSlide(currentSlide - 1));
            document.getElementById('nextSlideBtn').addEventListener('click', () => goToSlide(currentSlide + 1));

            /* Hỗ trợ vuốt cảm ứng trái/phải cho 2 banner trên điện thoại */
            let touchStartX = 0;
            const sliderEl = document.getElementById('heroSlider');
            sliderEl.addEventListener('touchstart', (e) => {
                touchStartX = e.changedTouches[0].screenX;
            }, { passive: true });
            sliderEl.addEventListener('touchend', (e) => {
                const diff = e.changedTouches[0].screenX - touchStartX;
                if (Math.abs(diff) > 45) {
                    if (diff < 0) goToSlide(currentSlide + 1);
                    else goToSlide(currentSlide - 1);
                }
            }, { passive: true });

            restartAutoSlide();
        });
    </script>
</body>
</html>
