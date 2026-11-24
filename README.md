<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>Công Ty TNHH MTV TM SX & DV Nhôm Kính Đức Anh Vũ | ducanhvu.com</title>
    <meta name="description" content="Công Ty TNHH MTV TM SX & DV Nhôm Kính Đức Anh Vũ - Chuyên thi công cửa nhôm Xingfa, cửa kính cường lực, cửa nhựa lõi thép, cửa tự động, cầu thang kính, kính ốp bếp, phòng tắm kính tại Đà Nẵng. Hotline: 0934.434.543.">

    <!-- Favicon & Open Graph Thumbnail (Ảnh đại diện là Logo công ty khi chia sẻ link) -->
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1tr19Gbnp3Y2kyG3AgD4_ctjnVaKXoFk_=w256">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://ducanhvu.com/">
    <meta property="og:title" content="Nhôm Kính Đức Anh Vũ - Cửa Nhôm Xingfa & Kính Cường Lực Đà Nẵng">
    <meta property="og:description" content="Thi công cửa nhôm Xingfa chính hãng, cửa kính cường lực, cầu thang kính, kính ốp bếp, phòng tắm kính uy tín tại Đà Nẵng. Hotline: 0934.434.543.">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1tr19Gbnp3Y2kyG3AgD4_ctjnVaKXoFk_=w1200">
    <meta property="og:image:alt" content="Logo Công Ty Nhôm Kính Đức Anh Vũ">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Nhôm Kính Đức Anh Vũ - ducanhvu.com">
    <meta name="twitter:description" content="Chuyên cửa nhôm Xingfa, cửa kính cường lực tại Đà Nẵng - Hotline: 0934.434.543">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1tr19Gbnp3Y2kyG3AgD4_ctjnVaKXoFk_=w1200">

    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <style>
        /* =====================================================================
           BẢNG MÀU CHỦ ĐẠO (Dễ dàng tùy chỉnh theo sắc độ logo trên Flatsome)
        ===================================================================== */
        :root {
            --brand-primary: #0b3b8c;      /* Xanh Navy chủ đạo theo nhận diện nhôm kính */
            --brand-primary-dark: #072863; /* Xanh đậm cho Topbar & Hover */
            --brand-secondary: #1558c0;    /* Xanh sáng cho nút & điểm nhấn */
            --brand-accent: #d9232e;       /* Đỏ nổi bật cho % giảm giá & giá bán */
            --brand-gold: #e89b0c;         /* Vàng nhấn nhẹ nhàng */
            --bg-light: #f4f6f9;           /* Nền xám nhạt hiện đại */
            --text-dark: #1e293b;
            --text-muted: #475569;
            --border-color: #e2e8f0;
        }

        /* =====================================================================
           CHỐNG TRÀN VIỀN & TỐI ƯU BỐ CỤC 95% TRÊN MÁY TÍNH
        ===================================================================== */
        *, *::before, *::after {
            box-sizing: border-box;
        }

        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            color: var(--text-dark);
            background-color: #ffffff;
            scroll-behavior: smooth;
            -webkit-font-smoothing: antialiased;
        }

        /* Khung chuẩn Flatsome: Mobile 100% có padding gọn, Desktop rộng 95% màn hình */
        .dav-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }

        @media (min-width: 1024px) {
            .dav-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* =====================================================================
           THANH ĐIỀU HƯỚNG FLATSOME (1 HÀNG DUY NHẤT, KHÔNG XUỐNG DÒNG TÊN MỤC)
        ===================================================================== */
        .dav-nav-bar {
            background-color: var(--brand-primary);
        }

        .dav-nav-list {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-wrap: nowrap;
            gap: 2px;
            margin: 0;
            padding: 0;
            list-style: none;
        }

        .dav-nav-item {
            position: relative;
            flex-shrink: 0;
        }

        .dav-nav-link {
            display: inline-flex;
            align-items: center;
            gap: 4px;
            color: #ffffff;
            font-weight: 600;
            text-transform: uppercase;
            white-space: nowrap; /* Đảm bảo tên danh mục tuyệt đối không xuống dòng */
            font-size: 11.5px;
            letter-spacing: -0.01em;
            padding: 12px 7px;
            transition: background-color 0.2s ease, color 0.2s ease;
            border-radius: 4px;
        }

        @media (min-width: 1180px) {
            .dav-nav-link {
                font-size: 12.5px;
                padding: 13px 11px;
            }
        }

        @media (min-width: 1360px) {
            .dav-nav-link {
                font-size: 13px;
                padding: 13px 14px;
            }
        }

        .dav-nav-link:hover,
        .dav-nav-link.active {
            background-color: var(--brand-primary-dark);
            color: #fde047;
        }

        /* Menu cấp 2 (Dropdown) */
        .dav-dropdown {
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 225px;
            background: #ffffff;
            border: 1px solid var(--border-color);
            border-top: 3px solid var(--brand-accent);
            border-radius: 0 0 8px 8px;
            box-shadow: 0 12px 28px rgba(11, 59, 140, 0.16);
            opacity: 0;
            visibility: hidden;
            transform: translateY(6px);
            transition: all 0.2s ease;
            z-index: 60;
            padding: 6px 0;
        }

        .dav-nav-item:hover .dav-dropdown,
        .dav-nav-item:focus-within .dav-dropdown {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        .dav-dropdown a {
            display: block;
            padding: 9px 16px;
            font-size: 13px;
            font-weight: 500;
            color: var(--text-dark);
            white-space: nowrap;
            transition: background-color 0.15s ease, color 0.15s ease, padding-left 0.15s ease;
        }

        .dav-dropdown a:hover {
            background-color: #eef4ff;
            color: var(--brand-primary);
            padding-left: 20px;
        }

        /* =====================================================================
           SLIDER 2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU, CHỮ NẰM GỌN TRONG KHUNG
        ===================================================================== */
        .dav-banner-slider {
            position: relative;
            width: 100%;
            overflow: hidden;
            border-radius: 12px;
            background-color: var(--brand-primary-dark);
        }

        /* Dùng CSS Grid xếp chồng các slide để 2 banner luôn có chiều cao BẰNG NHAU tuyệt đối */
        .dav-banner-track {
            display: grid;
            grid-template-columns: 1fr;
            width: 100%;
        }

        .dav-banner-slide {
            grid-area: 1 / 1;
            width: 100%;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.65s ease, visibility 0.65s ease;
            position: relative;
            display: flex;
            align-items: center;
        }

        .dav-banner-slide.is-active {
            opacity: 1;
            visibility: visible;
            z-index: 2;
        }

        /* Khoảng đệm rộng đảm bảo chữ & ảnh luôn cách xa viền banner trên cả Mobile & Desktop */
        .dav-banner-inner {
            width: 100%;
            padding: 36px 42px 48px 42px;
        }

        @media (min-width: 640px) {
            .dav-banner-inner {
                padding: 44px 64px 54px 64px;
            }
        }

        @media (min-width: 1024px) {
            .dav-banner-inner {
                padding: 56px 84px 60px 84px;
            }
        }

        /* =====================================================================
           TIÊU ĐỀ SECTION PHONG CÁCH FLATSOME UX BUILDER
        ===================================================================== */
        .ux-section-title {
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            margin-bottom: 1.5rem;
        }

        .ux-section-title::before,
        .ux-section-title::after {
            content: "";
            flex: 1;
            height: 2px;
            background: #e2e8f0;
        }

        .ux-section-title h2 {
            padding: 0 14px;
            font-size: 16px;
            font-weight: 800;
            text-transform: uppercase;
            color: var(--brand-primary);
            letter-spacing: 0.02em;
            margin: 0;
        }

        @media (min-width: 768px) {
            .ux-section-title h2 {
                font-size: 21px;
                padding: 0 22px;
            }
        }

        /* =====================================================================
           THẺ SẢN PHẨM & DANH MỤC (KHÔNG TRÀN CHỮ, GIÁ + GIẢM GIÁ % GÓC TRÊN TRÁI)
        ===================================================================== */
        .ux-product-card {
            display: flex;
            flex-direction: column;
            background: #ffffff;
            border: 1px solid var(--border-color);
            border-radius: 10px;
            overflow: hidden;
            transition: transform 0.22s ease, box-shadow 0.22s ease, border-color 0.22s ease;
        }

        .ux-product-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 24px rgba(11, 59, 140, 0.12);
            border-color: #bfdbfe;
        }

        /* Nhãn giảm giá % duy nhất ở góc trên bên trái của sản phẩm */
        .ux-discount-badge {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            background-color: var(--brand-accent);
            color: #ffffff;
            font-size: 11px;
            font-weight: 700;
            padding: 3px 7px;
            border-radius: 6px;
            line-height: 1.2;
            box-shadow: 0 2px 6px rgba(217, 35, 46, 0.35);
        }

        /* =====================================================================
           CỤM NÚT LIÊN HỆ NỔI (ZALO, FACEBOOK, HOTLINE)
        ===================================================================== */
        .dav-floating-contacts {
            position: fixed;
            right: 12px;
            bottom: 16px;
            z-index: 90;
            display: flex;
            flex-direction: column;
            align-items: flex-end;
            gap: 10px;
        }

        @media (min-width: 768px) {
            .dav-floating-contacts {
                right: 20px;
                bottom: 24px;
                gap: 12px;
            }
        }

        .dav-float-btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            height: 44px;
            min-width: 44px;
            padding: 0 12px;
            border-radius: 9999px;
            color: #ffffff;
            font-weight: 700;
            font-size: 13px;
            text-decoration: none;
            box-shadow: 0 6px 18px rgba(0, 0, 0, 0.22);
            transition: transform 0.2s ease, box-shadow 0.2s ease;
        }

        .dav-float-btn:hover {
            transform: scale(1.06);
            box-shadow: 0 8px 22px rgba(0, 0, 0, 0.28);
        }

        @keyframes pulseRing {
            0% { box-shadow: 0 0 0 0 rgba(217, 35, 46, 0.6); }
            70% { box-shadow: 0 0 0 12px rgba(217, 35, 46, 0); }
            100% { box-shadow: 0 0 0 0 rgba(217, 35, 46, 0); }
        }

        .dav-hotline-pulse {
            animation: pulseRing 2s infinite;
        }

        /* Mobile drawer transition */
        .mobile-drawer {
            transform: translateX(-100%);
            transition: transform 0.28s ease;
        }
        .mobile-drawer.open {
            transform: translateX(0);
        }
    </style>
</head>
<body class="bg-white text-slate-800">

    <!-- =======================================================================
         TOP BAR (THÔNG TIN ĐỊA CHỈ & GIỜ LÀM VIỆC - CHUẨN FLATSOME)
    ======================================================================== -->
    <div style="background-color: var(--brand-primary-dark);" class="text-white text-[11px] sm:text-xs py-1.5">
        <div class="dav-container flex flex-wrap items-center justify-between gap-y-1">
            <div class="flex items-center gap-3 flex-wrap">
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-location-dot text-yellow-300"></i>
                    <span>Nguyễn Lương Bằng, Liên Chiểu, Đà Nẵng</span>
                </span>
                <span class="hidden sm:inline-flex items-center gap-1.5 border-l border-white/25 pl-3">
                    <i class="fa-regular fa-clock text-yellow-300"></i>
                    <span>Làm việc: 07:30 - 20:00 (T2 - CN)</span>
                </span>
            </div>
            <div class="hidden md:flex items-center gap-3">
                <a href="https://ducanhvu.com" class="hover:text-yellow-300 transition">
                    <i class="fa-solid fa-globe mr-1"></i>ducanhvu.com
                </a>
                <a href="https://www.facebook.com/profile.php?id=100063787495394&locale=ca_ES" target="_blank" rel="noopener noreferrer" class="hover:text-yellow-300 transition border-l border-white/25 pl-3">
                    <i class="fa-brands fa-facebook mr-1"></i>Fanpage Nhôm Kính Đức Anh Vũ
                </a>
            </div>
        </div>
    </div>

    <!-- =======================================================================
         HEADER CHÍNH (LOGO GỌN NHỎ + TÌM KIẾM - KHÔNG ĐỂ NÚT GỌI NGAY TRÁNH TRÀN VIỀN)
    ======================================================================== -->
    <header class="bg-white border-b border-slate-200 sticky top-0 z-50 shadow-sm">
        <div class="dav-container py-2 md:py-2.5 flex items-center justify-between gap-3">
            <!-- Nút Menu Mobile -->
            <button id="mobileMenuBtn" type="button" aria-label="Mở danh mục menu" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-slate-700 hover:bg-slate-100 shrink-0">
                <i class="fa-solid fa-bars text-lg"></i>
            </button>

            <!-- Logo Công ty chỉnh gọn nhỏ -->
            <a href="#trang-chu" class="flex items-center gap-2.5 min-w-0">
                <img
                    src="https://lh3.googleusercontent.com/d/1tr19Gbnp3Y2kyG3AgD4_ctjnVaKXoFk_=w400"
                    data-gdrive-id="1tr19Gbnp3Y2kyG3AgD4_ctjnVaKXoFk_"
                    data-fallback-text="DUC ANH VU"
                    alt="Logo Nhôm Kính Đức Anh Vũ"
                    class="h-10 sm:h-11 md:h-12 w-auto max-w-[115px] object-contain rounded shrink-0"
                    onerror="handleDriveImgError(this)"
                >
                <div class="leading-tight min-w-0">
                    <div class="font-extrabold text-[12px] sm:text-sm md:text-[15px] uppercase tracking-tight truncate" style="color: var(--brand-primary);">
                        NHÔM KÍNH ĐỨC ANH VŨ
                    </div>
                    <div class="text-[10px] sm:text-[11px] text-slate-500 font-medium truncate">
                        CÔNG TY TNHH MTV TM SX &amp; DV • ĐÀ NẴNG
                    </div>
                </div>
            </a>

            <!-- Thanh tìm kiếm sản phẩm (Desktop & Tablet) -->
            <form id="headerSearchForm" class="hidden md:flex items-center flex-1 max-w-md mx-4">
                <div class="relative w-full">
                    <input
                        id="searchInput"
                        type="text"
                        placeholder="Tìm cửa nhôm Xingfa, cửa kính, cầu thang kính..."
                        class="w-full pl-4 pr-11 py-2 text-sm bg-slate-50 border border-slate-300 rounded-full focus:outline-none focus:border-blue-700 focus:bg-white transition"
                    >
                    <button type="submit" aria-label="Tìm kiếm" style="background-color: var(--brand-primary);" class="absolute right-1 top-1 bottom-1 px-3.5 rounded-full text-white text-xs hover:opacity-90 transition">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </div>
            </form>

            <!-- Thông tin ngắn gọn góc phải (Chỉ hiển thị nhẹ trên Desktop, không đặt nút Gọi ngay) -->
            <div class="hidden xl:flex items-center gap-4 text-xs text-slate-600 shrink-0">
                <div class="flex items-center gap-2">
                    <span class="w-8 h-8 rounded-full bg-blue-50 flex items-center justify-center" style="color: var(--brand-primary);">
                        <i class="fa-solid fa-shield-halved"></i>
                    </span>
                    <div class="leading-tight">
                        <div class="font-bold text-slate-800">Xingfa Chính Hãng</div>
                        <div class="text-[11px] text-slate-500">Phụ kiện Kinlong đồng bộ</div>
                    </div>
                </div>
                <div class="flex items-center gap-2 border-l border-slate-200 pl-4">
                    <span class="w-8 h-8 rounded-full bg-blue-50 flex items-center justify-center" style="color: var(--brand-primary);">
                        <i class="fa-solid fa-screwdriver-wrench"></i>
                    </span>
                    <div class="leading-tight">
                        <div class="font-bold text-slate-800">Khảo Sát Tận Nơi</div>
                        <div class="text-[11px] text-slate-500">Bảo hành dài hạn tại Đà Nẵng</div>
                    </div>
                </div>
            </div>

            <!-- Nút tìm kiếm nhỏ trên Mobile -->
            <button id="mobileSearchToggle" type="button" aria-label="Tìm kiếm" class="md:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-slate-700 hover:bg-slate-100 shrink-0">
                <i class="fa-solid fa-magnifying-glass"></i>
            </button>
        </div>

        <!-- Ô tìm kiếm xổ xuống trên Mobile -->
        <div id="mobileSearchBar" class="hidden md:hidden border-t border-slate-100 bg-slate-50 px-3 py-2">
            <form id="mobileSearchForm" class="flex items-center gap-2">
                <input id="mobileSearchInput" type="text" placeholder="Tìm sản phẩm nhôm kính..." class="flex-1 px-3 py-2 text-sm bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-blue-700">
                <button type="submit" style="background-color: var(--brand-primary);" class="px-4 py-2 rounded-lg text-white text-sm font-semibold">Tìm</button>
            </form>
        </div>

        <!-- ===================================================================
             THANH MENU CHÍNH TRÊN MÁY TÍNH (VIẾT LIỀN 1 HÀNG, CHỮ GỌN, KHÔNG XUỐNG DÒNG)
        ==================================================================== -->
        <nav class="hidden lg:block dav-nav-bar" aria-label="Danh mục chính">
            <div class="dav-container">
                <ul class="dav-nav-list">
                    <li class="dav-nav-item">
                        <a href="#trang-chu" class="dav-nav-link active">Trang chủ</a>
                    </li>
                    <li class="dav-nav-item">
                        <a href="#gioi-thieu" class="dav-nav-link">Giới thiệu</a>
                    </li>
                    <li class="dav-nav-item">
                        <a href="#san-pham" class="dav-nav-link">
                            <span>Cửa nhôm xingfa</span>
                            <i class="fa-solid fa-chevron-down text-[10px]"></i>
                        </a>
                        <div class="dav-dropdown">
                            <a href="#san-pham" onclick="filterProducts('1-canh')">+ Cửa nhôm xingfa 1 cánh</a>
                            <a href="#san-pham" onclick="filterProducts('2-canh')">+ Cửa nhôm xingfa 2 cánh</a>
                            <a href="#san-pham" onclick="filterProducts('3-canh')">+ Cửa nhôm xingfa 3 cánh</a>
                            <a href="#san-pham" onclick="filterProducts('4-canh')">+ Cửa nhôm xingfa 4 cánh</a>
                            <a href="#san-pham" onclick="filterProducts('xep-truot')">+ Cửa nhôm xingfa 5 cánh</a>
                        </div>
                    </li>
                    <li class="dav-nav-item">
                        <a href="#danh-muc-san-pham" class="dav-nav-link">Cửa kính cường lực</a>
                    </li>
                    <li class="dav-nav-item">
                        <a href="#danh-muc-san-pham" class="dav-nav-link">
                            <span>Sản phẩm</span>
                            <i class="fa-solid fa-chevron-down text-[10px]"></i>
                        </a>
                        <div class="dav-dropdown">
                            <a href="#san-pham">+ Cửa nhôm xingfa</a>
                            <a href="#danh-muc-san-pham" onclick="openCategoryDetail('cua-nhua-loi-thep')">+ Cửa nhựa lõi thép</a>
                            <a href="#danh-muc-san-pham" onclick="openCategoryDetail('cua-tu-dong')">+ Cửa kính tự động</a>
                            <a href="#danh-muc-san-pham" onclick="openCategoryDetail('cau-thang-kinh')">+ Cầu thang kính</a>
                            <a href="#danh-muc-san-pham" onclick="openCategoryDetail('kinh-op-bep')">+ Kính ốp bếp</a>
                            <a href="#danh-muc-san-pham" onclick="openCategoryDetail('phong-tam-kinh')">+ Phòng tắm kính</a>
                        </div>
                    </li>
                    <li class="dav-nav-item">
                        <a href="#cong-trinh" class="dav-nav-link">Công trình</a>
                    </li>
                    <li class="dav-nav-item">
                        <a href="#bao-gia" class="dav-nav-link">Báo giá</a>
                    </li>
                    <li class="dav-nav-item">
                        <a href="#tin-tuc" class="dav-nav-link">Tin tức</a>
                    </li>
                    <li class="dav-nav-item">
                        <a href="#lien-he" class="dav-nav-link">Liên hệ</a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- =======================================================================
         MENU TRƯỢT TRÊN ĐIỆN THOẠI (MOBILE DRAWER - CHUẨN FLATSOME)
    ======================================================================== -->
    <div id="mobileOverlay" class="fixed inset-0 bg-black/50 z-[95] hidden"></div>
    <aside id="mobileDrawer" class="mobile-drawer fixed top-0 left-0 bottom-0 w-[82%] max-w-[320px] bg-white z-[100] shadow-2xl flex flex-col overflow-y-auto">
        <div class="p-4 flex items-center justify-between border-b border-slate-200" style="background-color: var(--brand-primary);">
            <div class="text-white font-bold text-sm uppercase">Danh mục Đức Anh Vũ</div>
            <button id="closeMobileMenu" type="button" aria-label="Đóng menu" class="w-8 h-8 rounded-full bg-white/15 text-white flex items-center justify-center">
                <i class="fa-solid fa-xmark"></i>
            </button>
        </div>

        <nav class="flex-1 divide-y divide-slate-100 text-sm font-semibold text-slate-800">
            <a href="#trang-chu" class="mobile-nav-link block px-4 py-3 hover:bg-blue-50">Trang chủ</a>
            <a href="#gioi-thieu" class="mobile-nav-link block px-4 py-3 hover:bg-blue-50">Giới thiệu</a>

            <!-- Accordion Cửa nhôm xingfa -->
            <div>
                <button type="button" class="accordion-toggle w-full flex items-center justify-between px-4 py-3 hover:bg-blue-50 text-left">
                    <span>Cửa nhôm xingfa</span>
                    <i class="fa-solid fa-chevron-down text-xs text-slate-400 transition-transform"></i>
                </button>
                <div class="accordion-content hidden bg-slate-50 pl-6 pr-4 py-1 text-[13px] font-medium text-slate-600 space-y-1">
                    <a href="#san-pham" onclick="filterProducts('1-canh')" class="mobile-nav-link block py-2 border-b border-slate-200/60">+ Cửa nhôm xingfa 1 cánh</a>
                    <a href="#san-pham" onclick="filterProducts('2-canh')" class="mobile-nav-link block py-2 border-b border-slate-200/60">+ Cửa nhôm xingfa 2 cánh</a>
                    <a href="#san-pham" onclick="filterProducts('3-canh')" class="mobile-nav-link block py-2 border-b border-slate-200/60">+ Cửa nhôm xingfa 3 cánh</a>
                    <a href="#san-pham" onclick="filterProducts('4-canh')" class="mobile-nav-link block py-2 border-b border-slate-200/60">+ Cửa nhôm xingfa 4 cánh</a>
                    <a href="#san-pham" onclick="filterProducts('xep-truot')" class="mobile-nav-link block py-2">+ Cửa nhôm xingfa 5 cánh</a>
                </div>
            </div>

            <a href="#danh-muc-san-pham" class="mobile-nav-link block px-4 py-3 hover:bg-blue-50">Cửa kính cường lực</a>

            <!-- Accordion Sản phẩm -->
            <div>
                <button type="button" class="accordion-toggle w-full flex items-center justify-between px-4 py-3 hover:bg-blue-50 text-left">
                    <span>Sản phẩm</span>
                    <i class="fa-solid fa-chevron-down text-xs text-slate-400 transition-transform"></i>
                </button>
                <div class="accordion-content hidden bg-slate-50 pl-6 pr-4 py-1 text-[13px] font-medium text-slate-600 space-y-1">
                    <a href="#san-pham" class="mobile-nav-link block py-2 border-b border-slate-200/60">+ Cửa nhôm xingfa</a>
                    <a href="#danh-muc-san-pham" onclick="openCategoryDetail('cua-nhua-loi-thep')" class="mobile-nav-link block py-2 border-b border-slate-200/60">+ Cửa nhựa lõi thép</a>
                    <a href="#danh-muc-san-pham" onclick="openCategoryDetail('cua-tu-dong')" class="mobile-nav-link block py-2 border-b border-slate-200/60">+ Cửa kính tự động</a>
                    <a href="#danh-muc-san-pham" onclick="openCategoryDetail('cau-thang-kinh')" class="mobile-nav-link block py-2 border-b border-slate-200/60">+ Cầu thang kính</a>
                    <a href="#danh-muc-san-pham" onclick="openCategoryDetail('kinh-op-bep')" class="mobile-nav-link block py-2 border-b border-slate-200/60">+ Kính ốp bếp</a>
                    <a href="#danh-muc-san-pham" onclick="openCategoryDetail('phong-tam-kinh')" class="mobile-nav-link block py-2">+ Phòng tắm kính</a>
                </div>
            </div>

            <a href="#cong-trinh" class="mobile-nav-link block px-4 py-3 hover:bg-blue-50">Công trình</a>
            <a href="#bao-gia" class="mobile-nav-link block px-4 py-3 hover:bg-blue-50">Báo giá</a>
            <a href="#tin-tuc" class="mobile-nav-link block px-4 py-3 hover:bg-blue-50">Tin tức</a>
            <a href="#lien-he" class="mobile-nav-link block px-4 py-3 hover:bg-blue-50">Liên hệ</a>
        </nav>

        <div class="p-4 bg-slate-50 border-t border-slate-200 text-xs text-slate-600 space-y-1.5">
            <div class="font-bold text-slate-800">CÔNG TY NHÔM KÍNH ĐỨC ANH VŨ</div>
            <div><i class="fa-solid fa-location-dot text-blue-700 mr-1.5"></i>Nguyễn Lương Bằng, Liên Chiểu, Đà Nẵng</div>
            <div><i class="fa-solid fa-phone text-red-600 mr-1.5"></i>Hotline: <strong>0934.434.543</strong></div>
        </div>
    </aside>

    <!-- =======================================================================
         PHẦN NỘI DUNG CHÍNH
    ======================================================================== -->
    <main id="trang-chu">

        <!-- ===================================================================
             SECTION 1: 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
             (Chữ & hình ảnh nằm trọn trong khung banner, cách xa viền, không mất chữ)
        ==================================================================== -->
        <section class="pt-3 pb-5 md:pt-4 md:pb-8 bg-slate-50">
            <div class="dav-container">
                <div id="heroBannerSlider" class="dav-banner-slider shadow-lg">
                    <div class="dav-banner-track">

                        <!-- BANNER 1 -->
                        <div class="dav-banner-slide is-active" style="background: linear-gradient(135deg, #072863 0%, #0b3b8c 55%, #1558c0 100%);">
                            <div class="dav-banner-inner">
                                <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 lg:gap-8 items-center">
                                    <!-- Khối chữ cách xa viền -->
                                    <div class="lg:col-span-7 text-white space-y-3 sm:space-y-4">
                                        <p class="text-[11px] sm:text-xs font-bold uppercase tracking-widest text-yellow-300">
                                            CÔNG TY TNHH MTV TM SX &amp; DV NHÔM KÍNH ĐỨC ANH VŨ
                                        </p>
                                        <h1 class="text-xl sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug">
                                            Cửa Nhôm Xingfa Chính Hãng &amp; Cửa Kính Cường Lực Đà Nẵng
                                        </h1>
                                        <p class="text-xs sm:text-sm md:text-[15px] text-blue-100 leading-relaxed max-w-2xl">
                                            Sản xuất trực tiếp tại xưởng với thanh nhôm Xingfa nhập khẩu, phụ kiện Kinlong đồng bộ, cách âm cách nhiệt vượt trội, giá gốc tận xưởng cho mọi công trình.
                                        </p>
                                        <div class="flex flex-wrap items-center gap-2.5 pt-1">
                                            <a href="#bao-gia" class="inline-flex items-center gap-2 px-4 py-2.5 sm:px-5 sm:py-3 rounded-lg bg-yellow-400 hover:bg-yellow-300 text-slate-900 font-bold text-xs sm:text-sm transition shadow">
                                                <i class="fa-solid fa-file-invoice-dollar"></i>
                                                <span>Nhận Báo Giá Nhanh</span>
                                            </a>
                                            <a href="#san-pham" class="inline-flex items-center gap-2 px-4 py-2.5 sm:px-5 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 border border-white/30 text-white font-semibold text-xs sm:text-sm transition">
                                                <span>Xem Mẫu Cửa</span>
                                                <i class="fa-solid fa-arrow-right"></i>
                                            </a>
                                        </div>
                                    </div>
                                    <!-- Khối ảnh sản phẩm nằm gọn trong banner -->
                                    <div class="lg:col-span-5">
                                        <div class="bg-white/10 p-2 sm:p-2.5 rounded-xl border border-white/20 backdrop-blur-sm">
                                            <img
                                                src="https://lh3.googleusercontent.com/d/1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX=w900"
                                                data-gdrive-id="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
                                                data-fallback-text="Cua Nhom Xingfa Duc Anh Vu"
                                                alt="Thi công cửa nhôm Xingfa Đức Anh Vũ Đà Nẵng"
                                                class="w-full h-44 sm:h-56 lg:h-64 object-cover rounded-lg"
                                                onerror="handleDriveImgError(this)"
                                            >
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- BANNER 2 (Cùng bố cục chuẩn, đảm bảo kích thước bằng hệt Banner 1) -->
                        <div class="dav-banner-slide" style="background: linear-gradient(135deg, #0f294a 0%, #0b3b8c 55%, #1d4ed8 100%);">
                            <div class="dav-banner-inner">
                                <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 lg:gap-8 items-center">
                                    <div class="lg:col-span-7 text-white space-y-3 sm:space-y-4">
                                        <p class="text-[11px] sm:text-xs font-bold uppercase tracking-widest text-yellow-300">
                                            ĐỐI TÁC THI CÔNG KHÁCH SẠN &amp; RESORT TẠI ĐÀ NẴNG
                                        </p>
                                        <h2 class="text-xl sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug">
                                            Giải Pháp Nhôm Kính Toàn Diện Cho Biệt Thự, Nhà Phố &amp; Dự Án
                                        </h2>
                                        <p class="text-xs sm:text-sm md:text-[15px] text-blue-100 leading-relaxed max-w-2xl">
                                            Thi công trọn gói Cửa tự động, Cầu thang kính, Phòng tắm kính, Kính ốp bếp và Cửa nhựa lõi thép. Cam kết tiến độ chuẩn xác, thẩm mỹ cao và bảo hành uy tín.
                                        </p>
                                        <div class="flex flex-wrap items-center gap-2.5 pt-1">
                                            <a href="#cong-trinh" class="inline-flex items-center gap-2 px-4 py-2.5 sm:px-5 sm:py-3 rounded-lg bg-yellow-400 hover:bg-yellow-300 text-slate-900 font-bold text-xs sm:text-sm transition shadow">
                                                <i class="fa-solid fa-building"></i>
                                                <span>Xem Dự Án Thực Tế</span>
                                            </a>
                                            <a href="#lien-he" class="inline-flex items-center gap-2 px-4 py-2.5 sm:px-5 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 border border-white/30 text-white font-semibold text-xs sm:text-sm transition">
                                                <span>Liên Hệ Tư Vấn</span>
                                                <i class="fa-solid fa-phone"></i>
                                            </a>
                                        </div>
                                    </div>
                                    <div class="lg:col-span-5">
                                        <div class="bg-white/10 p-2 sm:p-2.5 rounded-xl border border-white/20 backdrop-blur-sm">
                                            <img
                                                src="https://lh3.googleusercontent.com/d/1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ=w900"
                                                data-gdrive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                                                data-fallback-text="Du An Thi Cong Duc Anh Vu"
                                                alt="Dự án thi công nhôm kính cao cấp Đà Nẵng"
                                                class="w-full h-44 sm:h-56 lg:h-64 object-cover rounded-lg"
                                                onerror="handleDriveImgError(this)"
                                            >
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>

                    <!-- Nút điều hướng mũi tên đặt sát mép ngoài, không che chữ -->
                    <button id="bannerPrev" type="button" aria-label="Banner trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-10 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/30 hover:bg-black/55 text-white flex items-center justify-center transition">
                        <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                    </button>
                    <button id="bannerNext" type="button" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-10 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/30 hover:bg-black/55 text-white flex items-center justify-center transition">
                        <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                    </button>

                    <!-- Chấm tròn chỉ báo slide -->
                    <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-10 flex items-center gap-2">
                        <button type="button" class="banner-dot w-7 h-2 rounded-full bg-yellow-400 transition-all" data-slide="0" aria-label="Slide 1"></button>
                        <button type="button" class="banner-dot w-2.5 h-2 rounded-full bg-white/50 hover:bg-white/80 transition-all" data-slide="1" aria-label="Slide 2"></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===================================================================
             SECTION 2: DANH MỤC SẢN PHẨM NỔI BẬT (CHỮ DANH MỤC GỌN NHỎ, 6 MỤC CHUẨN WEB MẪU)
        ==================================================================== -->
        <section id="danh-muc-san-pham" class="py-8 md:py-10 bg-white">
            <div class="dav-container">
                <div class="ux-section-title">
                    <h2>Danh mục sản phẩm</h2>
                </div>

                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 md:gap-4">
                    <!-- Danh mục 1: Cửa nhôm Xingfa -->
                    <button type="button" onclick="openCategoryDetail('cua-nhom-xingfa')" class="group text-center bg-white border border-slate-200 rounded-xl overflow-hidden hover:border-blue-600 hover:shadow-md transition flex flex-col">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img
                                src="https://lh3.googleusercontent.com/d/1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX=w600"
                                data-gdrive-id="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
                                data-fallback-text="Cua Nhom Xingfa"
                                alt="Cửa nhôm Xingfa"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                                onerror="handleDriveImgError(this)"
                            >
                        </div>
                        <div class="p-2.5 flex-1 flex items-center justify-center">
                            <h3 class="text-[12px] sm:text-[13px] font-bold uppercase leading-tight text-slate-800 group-hover:text-blue-800">
                                Cửa Nhôm Xingfa
                            </h3>
                        </div>
                    </button>

                    <!-- Danh mục 2: Cửa nhựa lõi thép -->
                    <button type="button" onclick="openCategoryDetail('cua-nhua-loi-thep')" class="group text-center bg-white border border-slate-200 rounded-xl overflow-hidden hover:border-blue-600 hover:shadow-md transition flex flex-col">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img
                                src="https://lh3.googleusercontent.com/d/1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA=w600"
                                data-gdrive-id="1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA"
                                data-fallback-text="Cua Nhua Loi Thep"
                                alt="Cửa nhựa lõi thép"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                                onerror="handleDriveImgError(this)"
                            >
                        </div>
                        <div class="p-2.5 flex-1 flex items-center justify-center">
                            <h3 class="text-[12px] sm:text-[13px] font-bold uppercase leading-tight text-slate-800 group-hover:text-blue-800">
                                Cửa Nhựa Lõi Thép
                            </h3>
                        </div>
                    </button>

                    <!-- Danh mục 3: Cửa tự động -->
                    <button type="button" onclick="openCategoryDetail('cua-tu-dong')" class="group text-center bg-white border border-slate-200 rounded-xl overflow-hidden hover:border-blue-600 hover:shadow-md transition flex flex-col">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img
                                src="https://lh3.googleusercontent.com/d/1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ=w600"
                                data-gdrive-id="1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ"
                                data-fallback-text="Cua Kinh Tu Dong"
                                alt="Cửa tự động"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                                onerror="handleDriveImgError(this)"
                            >
                        </div>
                        <div class="p-2.5 flex-1 flex items-center justify-center">
                            <h3 class="text-[12px] sm:text-[13px] font-bold uppercase leading-tight text-slate-800 group-hover:text-blue-800">
                                Cửa Kính Tự Động
                            </h3>
                        </div>
                    </button>

                    <!-- Danh mục 4: Cầu thang kính -->
                    <button type="button" onclick="openCategoryDetail('cau-thang-kinh')" class="group text-center bg-white border border-slate-200 rounded-xl overflow-hidden hover:border-blue-600 hover:shadow-md transition flex flex-col">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img
                                src="https://lh3.googleusercontent.com/d/1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul=w600"
                                data-gdrive-id="1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul"
                                data-fallback-text="Cau Thang Kinh"
                                alt="Cầu thang kính"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                                onerror="handleDriveImgError(this)"
                            >
                        </div>
                        <div class="p-2.5 flex-1 flex items-center justify-center">
                            <h3 class="text-[12px] sm:text-[13px] font-bold uppercase leading-tight text-slate-800 group-hover:text-blue-800">
                                Cầu Thang Kính
                            </h3>
                        </div>
                    </button>

                    <!-- Danh mục 5: Kính ốp bếp -->
                    <button type="button" onclick="openCategoryDetail('kinh-op-bep')" class="group text-center bg-white border border-slate-200 rounded-xl overflow-hidden hover:border-blue-600 hover:shadow-md transition flex flex-col">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img
                                src="https://lh3.googleusercontent.com/d/1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb=w600"
                                data-gdrive-id="1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb"
                                data-fallback-text="Kinh Op Bep"
                                alt="Kính ốp bếp"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                                onerror="handleDriveImgError(this)"
                            >
                        </div>
                        <div class="p-2.5 flex-1 flex items-center justify-center">
                            <h3 class="text-[12px] sm:text-[13px] font-bold uppercase leading-tight text-slate-800 group-hover:text-blue-800">
                                Kính Ốp Bếp
                            </h3>
                        </div>
                    </button>

                    <!-- Danh mục 6: Phòng tắm kính -->
                    <button type="button" onclick="openCategoryDetail('phong-tam-kinh')" class="group text-center bg-white border border-slate-200 rounded-xl overflow-hidden hover:border-blue-600 hover:shadow-md transition flex flex-col">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img
                                src="https://lh3.googleusercontent.com/d/1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH=w600"
                                data-gdrive-id="1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH"
                                data-fallback-text="Phong Tam Kinh"
                                alt="Phòng tắm kính"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                                onerror="handleDriveImgError(this)"
                            >
                        </div>
                        <div class="p-2.5 flex-1 flex items-center justify-center">
                            <h3 class="text-[12px] sm:text-[13px] font-bold uppercase leading-tight text-slate-800 group-hover:text-blue-800">
                                Phòng Tắm Kính
                            </h3>
                        </div>
                    </button>
                </div>
            </div>
        </section>

        <!-- ===================================================================
             SECTION 3: SẢN PHẨM CỬA NHÔM XINGFA ĐÀ NẴNG
             (2 CỘT TRÊN MOBILE, GIÁ + GIẢM GIÁ % GÓC TRÊN TRÁI, KHÔNG THIẾU CHỮ)
        ==================================================================== -->
        <section id="san-pham" class="py-8 md:py-12" style="background-color: var(--bg-light);">
            <div class="dav-container">
                <div class="ux-section-title">
                    <h2>Sản phẩm cửa nhôm Xingfa nổi bật</h2>
                </div>

                <!-- Bộ lọc nhanh sản phẩm -->
                <div class="flex flex-wrap items-center justify-center gap-2 mb-6">
                    <button type="button" onclick="filterProducts('all')" data-filter="all" class="product-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold border transition text-white" style="background-color: var(--brand-primary); border-color: var(--brand-primary);">
                        Tất cả
                    </button>
                    <button type="button" onclick="filterProducts('1-canh')" data-filter="1-canh" class="product-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold border border-slate-300 bg-white text-slate-700 hover:border-blue-700 transition">
                        Cửa 1 cánh
                    </button>
                    <button type="button" onclick="filterProducts('2-canh')" data-filter="2-canh" class="product-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold border border-slate-300 bg-white text-slate-700 hover:border-blue-700 transition">
                        Cửa 2 cánh
                    </button>
                    <button type="button" onclick="filterProducts('3-canh')" data-filter="3-canh" class="product-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold border border-slate-300 bg-white text-slate-700 hover:border-blue-700 transition">
                        Cửa 3 cánh
                    </button>
                    <button type="button" onclick="filterProducts('4-canh')" data-filter="4-canh" class="product-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold border border-slate-300 bg-white text-slate-700 hover:border-blue-700 transition">
                        Cửa 4 cánh
                    </button>
                    <button type="button" onclick="filterProducts('xep-truot')" data-filter="xep-truot" class="product-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold border border-slate-300 bg-white text-slate-700 hover:border-blue-700 transition">
                        Xếp trượt &amp; Mở hất
                    </button>
                </div>

                <!-- Lưới sản phẩm: Mobile 2 cột chuẩn đẹp, Tablet/Desktop 3 cột rộng rãi -->
                <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 gap-2.5 sm:gap-4 lg:gap-5">
                    <!-- Sản phẩm được render tự động từ dữ liệu JS để đồng bộ tìm kiếm & lọc -->
                </div>

                <div id="noProductMsg" class="hidden text-center py-8 text-slate-500 text-sm">
                    Không tìm thấy sản phẩm phù hợp. Vui lòng thử lại hoặc xem tất cả sản phẩm.
                </div>
            </div>
        </section>

        <!-- ===================================================================
             SECTION 4: GIỚI THIỆU CÔNG TY NHÔM KÍNH ĐỨC ANH VŨ (CHUẨN FLATSOME)
        ==================================================================== -->
        <section id="gioi-thieu" class="py-10 md:py-14 bg-white">
            <div class="dav-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                    <div class="lg:col-span-7 space-y-4">
                        <div class="text-xs font-bold uppercase tracking-wider text-blue-700">
                            VỀ CHÚNG TÔI
                        </div>
                        <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold leading-snug" style="color: var(--brand-primary);">
                            CÔNG TY TNHH MTV TM SX &amp; DV NHÔM KÍNH ĐỨC ANH VŨ
                        </h2>
                        <p class="text-sm sm:text-[15px] text-slate-600 leading-relaxed">
                            <strong>Nhôm Kính Đức Anh Vũ</strong> (ducanhvu.com) là đơn vị chuyên nghiệp trong lĩnh vực tư vấn thiết kế, gia công sản xuất và lắp đặt các hạng mục nhôm kính cao cấp tại <strong>Đà Nẵng</strong> và khu vực Miền Trung.
                        </p>
                        <p class="text-sm sm:text-[15px] text-slate-600 leading-relaxed">
                            Các dòng sản phẩm chủ lực gồm: <strong>Cửa nhôm Xingfa nhập khẩu</strong>, <strong>Cửa kính cường lực</strong>, <strong>Cửa nhựa lõi thép</strong>, <strong>Cửa kính tự động</strong>, <strong>Cầu thang kính</strong>, <strong>Kính ốp bếp</strong> và <strong>Phòng tắm kính</strong>. Với phương châm <em>“Uy tín – Chất lượng – Thẩm mỹ”</em>, Đức Anh Vũ cam kết mang đến không gian bền đẹp, an toàn và tối ưu chi phí cho mọi gia đình, khách sạn và dự án.
                        </p>

                        <!-- Cam kết dịch vụ ngắn gọn -->
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 pt-1 text-xs sm:text-sm text-slate-700">
                            <div class="flex items-center gap-2">
                                <i class="fa-solid fa-circle-check text-blue-700 shrink-0"></i>
                                <span>Nhôm Xingfa &amp; kính cường lực chính hãng</span>
                            </div>
                            <div class="flex items-center gap-2">
                                <i class="fa-solid fa-circle-check text-blue-700 shrink-0"></i>
                                <span>Khảo sát, đo đạc, tư vấn miễn phí tận nơi</span>
                            </div>
                            <div class="flex items-center gap-2">
                                <i class="fa-solid fa-circle-check text-blue-700 shrink-0"></i>
                                <span>Giá xưởng cạnh tranh, ưu đãi thi công trọn gói</span>
                            </div>
                            <div class="flex items-center gap-2">
                                <i class="fa-solid fa-circle-check text-blue-700 shrink-0"></i>
                                <span>Bảo hành kỹ thuật &amp; phụ kiện dài hạn</span>
                            </div>
                        </div>
                    </div>

                    <!-- Thống kê năng lực -->
                    <div class="lg:col-span-5">
                        <div class="grid grid-cols-2 gap-3 sm:gap-4">
                            <div class="p-4 sm:p-5 rounded-xl border border-blue-100 bg-blue-50/60 text-center">
                                <div class="text-2xl sm:text-3xl font-extrabold" style="color: var(--brand-primary);">150+</div>
                                <div class="text-xs sm:text-sm font-semibold text-slate-700 mt-1">Dự án hoàn thành</div>
                            </div>
                            <div class="p-4 sm:p-5 rounded-xl border border-blue-100 bg-blue-50/60 text-center">
                                <div class="text-2xl sm:text-3xl font-extrabold" style="color: var(--brand-primary);">50+</div>
                                <div class="text-xs sm:text-sm font-semibold text-slate-700 mt-1">Kỹ thuật viên kinh nghiệm</div>
                            </div>
                            <div class="p-4 sm:p-5 rounded-xl border border-blue-100 bg-blue-50/60 text-center">
                                <div class="text-2xl sm:text-3xl font-extrabold" style="color: var(--brand-primary);">100+</div>
                                <div class="text-xs sm:text-sm font-semibold text-slate-700 mt-1">Mẫu sản phẩm cao cấp</div>
                            </div>
                            <div class="p-4 sm:p-5 rounded-xl border border-blue-100 bg-blue-50/60 text-center">
                                <div class="text-2xl sm:text-3xl font-extrabold" style="color: var(--brand-primary);">100%</div>
                                <div class="text-xs sm:text-sm font-semibold text-slate-700 mt-1">Khách hàng hài lòng</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===================================================================
             SECTION 5: CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
        ==================================================================== -->
        <section id="cong-trinh" class="py-10 md:py-12" style="background-color: var(--bg-light);">
            <div class="dav-container">
                <div class="ux-section-title">
                    <h2>Các dự án tiêu biểu tại Đà Nẵng</h2>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 md:gap-5">
                    <!-- Dự án 1 -->
                    <article class="bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                            <img
                                src="https://lh3.googleusercontent.com/d/1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ=w800"
                                data-gdrive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                                data-fallback-text="My Son Heritage Resort"
                                alt="Dự án Resort Mỹ Sơn 4 sao My Son Heritage Resort & Spa"
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                                onerror="handleDriveImgError(this)"
                            >
                        </div>
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <h3 class="text-sm sm:text-[15px] font-bold text-slate-800 leading-snug">
                                DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT &amp; SPA”
                            </h3>
                            <p class="text-xs text-slate-500 mt-2">
                                Hạng mục: Hệ thống cửa nhôm Xingfa, vách kính cường lực và phòng tắm kính cao cấp.
                            </p>
                        </div>
                    </article>

                    <!-- Dự án 2 -->
                    <article class="bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                            <img
                                src="https://lh3.googleusercontent.com/d/1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy=w800"
                                data-gdrive-id="1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy"
                                data-fallback-text="Khach San Goden Line"
                                alt="Thi công dự án khách sạn Goden Line"
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                                onerror="handleDriveImgError(this)"
                            >
                        </div>
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <h3 class="text-sm sm:text-[15px] font-bold text-slate-800 leading-snug">
                                THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE
                            </h3>
                            <p class="text-xs text-slate-500 mt-2">
                                Hạng mục: Mặt dựng kính, cửa đi nhôm Xingfa cách âm chuẩn khách sạn tại Đà Nẵng.
                            </p>
                        </div>
                    </article>

                    <!-- Dự án 3 -->
                    <article class="bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                            <img
                                src="https://lh3.googleusercontent.com/d/1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ=w800"
                                data-gdrive-id="1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ"
                                data-fallback-text="Khach San Ruby Light"
                                alt="Dự án khách sạn Ruby Light"
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                                onerror="handleDriveImgError(this)"
                            >
                        </div>
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <h3 class="text-sm sm:text-[15px] font-bold text-slate-800 leading-snug">
                                DỰ ÁN KHÁCH SẠN RUBY LIGHT
                            </h3>
                            <p class="text-xs text-slate-500 mt-2">
                                Hạng mục: Cửa đi ban công, cửa sổ mở hất nhôm Xingfa và lan can kính cường lực.
                            </p>
                        </div>
                    </article>

                    <!-- Dự án 4 -->
                    <article class="bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                            <img
                                src="https://lh3.googleusercontent.com/d/1za_IJpAm850uulT6IuhBsk1THb3LuPuc=w800"
                                data-gdrive-id="1za_IJpAm850uulT6IuhBsk1THb3LuPuc"
                                data-fallback-text="Raon Da Nang Beach Hotel"
                                alt="Thi công dự án Raon Đà Nẵng Beach Hotel"
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                                onerror="handleDriveImgError(this)"
                            >
                        </div>
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <h3 class="text-sm sm:text-[15px] font-bold text-slate-800 leading-snug">
                                THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL
                            </h3>
                            <p class="text-xs text-slate-500 mt-2">
                                Hạng mục: Cửa kính tự động sảnh chính, hệ cửa chống gió biển &amp; phòng tắm kính.
                            </p>
                        </div>
                    </article>

                    <!-- Dự án 5 -->
                    <article class="bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                            <img
                                src="https://lh3.googleusercontent.com/d/1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64=w800"
                                data-gdrive-id="1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64"
                                data-fallback-text="Khach San Jolia"
                                alt="Thi công dự án khách sạn Jolia"
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                                onerror="handleDriveImgError(this)"
                            >
                        </div>
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <h3 class="text-sm sm:text-[15px] font-bold text-slate-800 leading-snug">
                                THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA
                            </h3>
                            <p class="text-xs text-slate-500 mt-2">
                                Hạng mục: Toàn bộ hệ thống cửa nhôm Xingfa cao cấp &amp; vách kính mặt tiền.
                            </p>
                        </div>
                    </article>

                    <!-- Dự án 6 -->
                    <article class="bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                            <img
                                src="https://lh3.googleusercontent.com/d/1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt=w800"
                                data-gdrive-id="1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt"
                                data-fallback-text="Khach San Soho"
                                alt="Thi công dự án khách sạn Soho"
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                                onerror="handleDriveImgError(this)"
                            >
                        </div>
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <h3 class="text-sm sm:text-[15px] font-bold text-slate-800 leading-snug">
                                THI CÔNG DỰ ÁN KHÁCH SẠN SOHO
                            </h3>
                            <p class="text-xs text-slate-500 mt-2">
                                Hạng mục: Thi công trọn gói cửa nhôm kính cách âm, cầu thang kính và kính cường lực.
                            </p>
                        </div>
                    </article>
                </div>
            </div>
        </section>

        <!-- ===================================================================
             SECTION 6: BẢNG BÁO GIÁ & FORM YÊU CẦU TƯ VẤN BÁO GIÁ TRANG CHỦ
        ==================================================================== -->
        <section id="bao-gia" class="py-10 md:py-14 bg-white">
            <div class="dav-container">
                <div class="ux-section-title">
                    <h2>Đăng ký yêu cầu &amp; nhận báo giá</h2>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                    <!-- Cột trái: Bảng giá tham khảo ngắn gọn -->
                    <div class="lg:col-span-6 rounded-xl border border-slate-200 bg-slate-50 p-5 sm:p-6 flex flex-col justify-between">
                        <div>
                            <h3 class="text-base sm:text-lg font-extrabold uppercase mb-3" style="color: var(--brand-primary);">
                                Bảng giá tham khảo tại Đà Nẵng
                            </h3>
                            <p class="text-xs sm:text-sm text-slate-600 mb-4">
                                Giá trực tiếp tại xưởng Nhôm Kính Đức Anh Vũ (đã bao gồm tư vấn khảo sát thực tế tại công trình):
                            </p>
                            <div class="overflow-x-auto">
                                <table class="w-full text-left border-collapse text-xs sm:text-sm">
                                    <thead>
                                        <tr style="background-color: var(--brand-primary);" class="text-white">
                                            <th class="py-2.5 px-3 rounded-tl-lg">Hạng mục thi công</th>
                                            <th class="py-2.5 px-3 rounded-tr-lg text-right">Đơn giá tham khảo</th>
                                        </tr>
                                    </thead>
                                    <tbody class="divide-y divide-slate-200 bg-white">
                                        <tr>
                                            <td class="py-2.5 px-3 font-medium">Cửa đi mở quay nhôm Xingfa (1–4 cánh)</td>
                                            <td class="py-2.5 px-3 text-right font-bold text-red-600">2.100.000 ₫/m²</td>
                                        </tr>
                                        <tr>
                                            <td class="py-2.5 px-3 font-medium">Cửa đi xếp trượt nhôm Xingfa</td>
                                            <td class="py-2.5 px-3 text-right font-bold text-red-600">2.100.000 ₫/m²</td>
                                        </tr>
                                        <tr>
                                            <td class="py-2.5 px-3 font-medium">Cửa sổ mở hất / mở quay Xingfa</td>
                                            <td class="py-2.5 px-3 text-right font-bold text-red-600">2.050.000 ₫/m²</td>
                                        </tr>
                                        <tr>
                                            <td class="py-2.5 px-3 font-medium">Cửa kính cường lực 10mm – 12mm</td>
                                            <td class="py-2.5 px-3 text-right font-bold text-red-600">750.000 ₫/m²</td>
                                        </tr>
                                        <tr>
                                            <td class="py-2.5 px-3 font-medium">Cầu thang kính / Phòng tắm kính</td>
                                            <td class="py-2.5 px-3 text-right font-bold text-red-600">1.250.000 ₫/md</td>
                                        </tr>
                                        <tr>
                                            <td class="py-2.5 px-3 font-medium">Kính cường lực ốp bếp sơn màu</td>
                                            <td class="py-2.5 px-3 text-right font-bold text-red-600">850.000 ₫/md</td>
                                        </tr>
                                    </tbody>
                                </table>
                            </div>
                        </div>
                        <div class="mt-4 pt-3 border-t border-slate-200 text-xs text-slate-500">
                            * Đơn giá có thể ưu đãi thêm theo khối lượng thực tế công trình. Liên hệ <strong>0934.434.543</strong> để nhận dự toán chi tiết.
                        </div>
                    </div>

                    <!-- Cột phải: Form yêu cầu và báo giá -->
                    <div class="lg:col-span-6 rounded-xl p-5 sm:p-6 text-white shadow-md" style="background: linear-gradient(135deg, #072863 0%, #0b3b8c 100%);">
                        <h3 class="text-base sm:text-lg font-extrabold uppercase mb-1">
                            Gửi yêu cầu báo giá miễn phí
                        </h3>
                        <p class="text-xs sm:text-sm text-blue-100 mb-5">
                            Để lại thông tin, kỹ thuật viên Đức Anh Vũ sẽ liên hệ tư vấn &amp; gửi bảng báo giá chi tiết trong 15 phút.
                        </p>

                        <form id="quoteForm" class="space-y-3.5">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                                <div>
                                    <label for="qName" class="block text-xs font-semibold mb-1 text-blue-100">Họ và tên *</label>
                                    <input id="qName" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 rounded-lg text-sm text-slate-800 bg-white focus:outline-none focus:ring-2 focus:ring-yellow-400">
                                </div>
                                <div>
                                    <label for="qPhone" class="block text-xs font-semibold mb-1 text-blue-100">Số điện thoại *</label>
                                    <input id="qPhone" type="tel" required placeholder="VD: 0934.xxx.xxx" class="w-full px-3.5 py-2.5 rounded-lg text-sm text-slate-800 bg-white focus:outline-none focus:ring-2 focus:ring-yellow-400">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                                <div>
                                    <label for="qService" class="block text-xs font-semibold mb-1 text-blue-100">Hạng mục cần báo giá</label>
                                    <select id="qService" class="w-full px-3.5 py-2.5 rounded-lg text-sm text-slate-800 bg-white focus:outline-none focus:ring-2 focus:ring-yellow-400">
                                        <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa (1-5 cánh / Xếp trượt)</option>
                                        <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                                        <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                                        <option value="Cửa kính tự động">Cửa kính tự động</option>
                                        <option value="Cầu thang kính">Cầu thang kính</option>
                                        <option value="Kính ốp bếp">Kính ốp bếp</option>
                                        <option value="Phòng tắm kính">Phòng tắm kính</option>
                                    </select>
                                </div>
                                <div>
                                    <label for="qAddress" class="block text-xs font-semibold mb-1 text-blue-100">Địa chỉ công trình</label>
                                    <input id="qAddress" type="text" placeholder="Quận/Huyện tại Đà Nẵng..." class="w-full px-3.5 py-2.5 rounded-lg text-sm text-slate-800 bg-white focus:outline-none focus:ring-2 focus:ring-yellow-400">
                                </div>
                            </div>

                            <div>
                                <label for="qNote" class="block text-xs font-semibold mb-1 text-blue-100">Yêu cầu / Kích thước dự kiến</label>
                                <textarea id="qNote" rows="3" placeholder="Mô tả số lượng bộ cửa, kích thước hoặc thời gian muốn khảo sát..." class="w-full px-3.5 py-2.5 rounded-lg text-sm text-slate-800 bg-white focus:outline-none focus:ring-2 focus:ring-yellow-400"></textarea>
                            </div>

                            <button type="submit" class="w-full py-3 rounded-lg bg-yellow-400 hover:bg-yellow-300 text-slate-900 font-extrabold text-sm uppercase tracking-wide transition shadow">
                                <i class="fa-solid fa-paper-plane mr-1.5"></i>Gửi Yêu Cầu Báo Giá Ngay
                            </button>

                            <div id="quoteFeedback" class="hidden p-3 rounded-lg bg-emerald-500/20 border border-emerald-300 text-emerald-100 text-xs sm:text-sm font-medium"></div>
                        </form>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===================================================================
             SECTION 7: DANH MỤC CÁC BÀI VIẾT & TIN TỨC TRANG CHỦ
        ==================================================================== -->
        <section id="tin-tuc" class="py-10 md:py-12" style="background-color: var(--bg-light);">
            <div class="dav-container">
                <div class="ux-section-title">
                    <h2>Tin tức &amp; kinh nghiệm nhôm kính</h2>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                    <!-- Bài viết 1 -->
                    <article class="bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                        <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
                            <img
                                src="https://lh3.googleusercontent.com/d/1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-=w600"
                                data-gdrive-id="1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-"
                                data-fallback-text="Bai Viet Nhom Xingfa"
                                alt="Cửa nhôm Xingfa có phù hợp với khí hậu Đà Nẵng không"
                                class="w-full h-full object-cover"
                                onerror="handleDriveImgError(this)"
                            >
                        </div>
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <div class="text-[11px] font-semibold text-blue-700 mb-1">Kiến thức nhôm kính</div>
                                <h3 class="text-sm font-bold text-slate-800 leading-snug mb-2">
                                    Cửa nhôm Xingfa có phù hợp với khí hậu ven biển Đà Nẵng không?
                                </h3>
                                <p class="text-xs text-slate-600 leading-relaxed">
                                    Tìm hiểu khả năng chống ăn mòn muối biển, chịu gió bão và độ kín khít cách âm của nhôm Xingfa sơn tĩnh điện.
                                </p>
                            </div>
                            <button type="button" onclick="openArticleModal(0)" class="mt-3 inline-flex items-center gap-1 text-xs font-bold text-blue-700 hover:underline self-start">
                                Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                            </button>
                        </div>
                    </article>

                    <!-- Bài viết 2 -->
                    <article class="bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                        <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
                            <img
                                src="https://lh3.googleusercontent.com/d/1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ=w600"
                                data-gdrive-id="1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ"
                                data-fallback-text="Cua Nhom Xingfa Tiet Kiem Dien"
                                alt="Cách nhận biết cửa nhôm Xingfa chính hãng và phụ kiện Kinlong"
                                class="w-full h-full object-cover"
                                onerror="handleDriveImgError(this)"
                            >
                        </div>
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <div class="text-[11px] font-semibold text-blue-700 mb-1">Tư vấn chọn mua</div>
                                <h3 class="text-sm font-bold text-slate-800 leading-snug mb-2">
                                    Cửa nhôm Xingfa có tiết kiệm năng lượng &amp; cách âm tốt không?
                                </h3>
                                <p class="text-xs text-slate-600 leading-relaxed">
                                    Cấu trúc khoang rỗng kết hợp hệ gioăng EPDM và kính hộp giúp giảm thất thoát nhiệt điều hòa hiệu quả.
                                </p>
                            </div>
                            <button type="button" onclick="openArticleModal(1)" class="mt-3 inline-flex items-center gap-1 text-xs font-bold text-blue-700 hover:underline self-start">
                                Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                            </button>
                        </div>
                    </article>

                    <!-- Bài viết 3 -->
                    <article class="bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                        <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
                            <img
                                src="https://lh3.googleusercontent.com/d/1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA=w600"
                                data-gdrive-id="1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA"
                                data-fallback-text="So Sanh Cua Nhom Va Cua Nhua"
                                alt="So sánh cửa nhôm Xingfa và cửa nhựa lõi thép"
                                class="w-full h-full object-cover"
                                onerror="handleDriveImgError(this)"
                            >
                        </div>
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <div class="text-[11px] font-semibold text-blue-700 mb-1">So sánh sản phẩm</div>
                                <h3 class="text-sm font-bold text-slate-800 leading-snug mb-2">
                                    Nên chọn cửa nhôm Xingfa hay cửa nhựa lõi thép cho nhà phố?
                                </h3>
                                <p class="text-xs text-slate-600 leading-relaxed">
                                    Phân tích ưu nhược điểm về độ bền, thẩm mỹ, khả năng chống trộm và chi phí lắp đặt giữa hai dòng cửa.
                                </p>
                            </div>
                            <button type="button" onclick="openArticleModal(2)" class="mt-3 inline-flex items-center gap-1 text-xs font-bold text-blue-700 hover:underline self-start">
                                Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                            </button>
                        </div>
                    </article>

                    <!-- Bài viết 4 -->
                    <article class="bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                        <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
                            <img
                                src="https://lh3.googleusercontent.com/d/1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH=w600"
                                data-gdrive-id="1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH"
                                data-fallback-text="Kinh Cuong Luc An Toan"
                                alt="Kinh nghiệm chọn phòng tắm kính, cầu thang kính và kính ốp bếp"
                                class="w-full h-full object-cover"
                                onerror="handleDriveImgError(this)"
                            >
                        </div>
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <div class="text-[11px] font-semibold text-blue-700 mb-1">Nội thất kính</div>
                                <h3 class="text-sm font-bold text-slate-800 leading-snug mb-2">
                                    Kinh nghiệm chọn kính cường lực cho phòng tắm kính &amp; bếp đẹp
                                </h3>
                                <p class="text-xs text-slate-600 leading-relaxed">
                                    Hướng dẫn chọn độ dày kính 8mm – 10mm – 12mm cùng phụ kiện inox 304 chống gỉ bền đẹp theo thời gian.
                                </p>
                            </div>
                            <button type="button" onclick="openArticleModal(3)" class="mt-3 inline-flex items-center gap-1 text-xs font-bold text-blue-700 hover:underline self-start">
                                Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                            </button>
                        </div>
                    </article>
                </div>
            </div>
        </section>

        <!-- ===================================================================
             SECTION 8: ĐỐI TÁC CỦA CHÚNG TÔI (6 LOGO ĐỐI TÁC TỪ GOOGLE DRIVE)
        ==================================================================== -->
        <section class="py-9 md:py-11 bg-white border-t border-slate-100">
            <div class="dav-container">
                <div class="ux-section-title">
                    <h2>Đối tác của chúng tôi</h2>
                </div>

                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 md:gap-4">
                    <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-20 sm:h-24 hover:border-blue-400 transition">
                        <img src="https://lh3.googleusercontent.com/d/13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk=w400" data-gdrive-id="13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk" data-fallback-text="Doi Tac 1" alt="Đối tác nhôm kính 1" class="max-h-14 w-auto object-contain" onerror="handleDriveImgError(this)">
                    </div>
                    <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-20 sm:h-24 hover:border-blue-400 transition">
                        <img src="https://lh3.googleusercontent.com/d/1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq=w400" data-gdrive-id="1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq" data-fallback-text="Doi Tac 2" alt="Đối tác nhôm kính 2" class="max-h-14 w-auto object-contain" onerror="handleDriveImgError(this)">
                    </div>
                    <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-20 sm:h-24 hover:border-blue-400 transition">
                        <img src="https://lh3.googleusercontent.com/d/1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn=w400" data-gdrive-id="1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn" data-fallback-text="Doi Tac 3" alt="Đối tác nhôm kính 3" class="max-h-14 w-auto object-contain" onerror="handleDriveImgError(this)">
                    </div>
                    <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-20 sm:h-24 hover:border-blue-400 transition">
                        <img src="https://lh3.googleusercontent.com/d/1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT=w400" data-gdrive-id="1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT" data-fallback-text="Doi Tac 4" alt="Đối tác nhôm kính 4" class="max-h-14 w-auto object-contain" onerror="handleDriveImgError(this)">
                    </div>
                    <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-20 sm:h-24 hover:border-blue-400 transition">
                        <img src="https://lh3.googleusercontent.com/d/1SDcarhnX0yypmqdbawICjYBRtFnKngn-=w400" data-gdrive-id="1SDcarhnX0yypmqdbawICjYBRtFnKngn-" data-fallback-text="Doi Tac 5" alt="Đối tác nhôm kính 5" class="max-h-14 w-auto object-contain" onerror="handleDriveImgError(this)">
                    </div>
                    <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-20 sm:h-24 hover:border-blue-400 transition">
                        <img src="https://lh3.googleusercontent.com/d/1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg=w400" data-gdrive-id="1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg" data-fallback-text="Doi Tac 6" alt="Đối tác nhôm kính 6" class="max-h-14 w-auto object-contain" onerror="handleDriveImgError(this)">
                    </div>
                </div>
            </div>
        </section>

        <!-- ===================================================================
             SECTION 9: BẢN ĐỒ GOOGLE MAPS & FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ
        ==================================================================== -->
        <section id="lien-he" class="py-10 md:py-12" style="background-color: var(--bg-light);">
            <div class="dav-container">
                <div class="ux-section-title">
                    <h2>Bản đồ chỉ đường &amp; Fanpage Facebook</h2>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
                    <!-- Cột trái: Google Maps Nguyễn Lương Bằng, Liên Chiểu, Đà Nẵng -->
                    <div class="lg:col-span-7 bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm flex flex-col">
                        <div class="px-4 py-3 border-b border-slate-200 flex items-center justify-between gap-2">
                            <div class="font-bold text-sm text-slate-800">
                                <i class="fa-solid fa-map-location-dot text-blue-700 mr-1.5"></i>
                                Bản đồ: Nguyễn Lương Bằng, Liên Chiểu, Đà Nẵng
                            </div>
                            <a href="https://maps.google.com/?q=Nguy%E1%BB%85n+L%C6%B0%C6%A1ng+B%E1%BA%B1ng,+Li%C3%AAn+Chi%E1%BB%83u,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-blue-700 hover:underline whitespace-nowrap">
                                Mở Google Maps <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                            </a>
                        </div>
                        <div class="flex-1 min-h-[300px] sm:min-h-[340px] w-full bg-slate-100">
                            <iframe
                                title="Bản đồ Nhôm Kính Đức Anh Vũ - Nguyễn Lương Bằng, Liên Chiểu, Đà Nẵng"
                                src="https://maps.google.com/maps?q=Nguy%E1%BB%85n%20L%C6%B0%C6%A1ng%20B%E1%BA%B1ng,%20Li%C3%AAn%20Chi%E1%BB%83u,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-full min-h-[300px] sm:min-h-[340px] border-0"
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade"
                                allowfullscreen>
                            </iframe>
                        </div>
                    </div>

                    <!-- Cột phải: Fanpage Facebook chính thức của Công Ty Nhôm Kính Đức Anh Vũ -->
                    <div class="lg:col-span-5 bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm flex flex-col">
                        <div class="px-4 py-3 border-b border-slate-200 flex items-center justify-between gap-2">
                            <div class="font-bold text-sm text-slate-800">
                                <i class="fa-brands fa-facebook text-blue-600 mr-1.5"></i>
                                Fanpage Nhôm Kính Đức Anh Vũ
                            </div>
                            <a href="https://www.facebook.com/profile.php?id=100063787495394&locale=ca_ES" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-blue-700 hover:underline whitespace-nowrap">
                                Xem trang <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                            </a>
                        </div>

                        <div class="p-4 flex-1 flex flex-col justify-between gap-4">
                            <!-- Khung nhúng Fanpage Facebook chuẩn -->
                            <div class="w-full overflow-hidden rounded-lg border border-slate-200 bg-slate-50">
                                <iframe
                                    title="Fanpage Facebook Công Ty Nhôm Kính Đức Anh Vũ"
                                    src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D100063787495394&tabs=timeline&width=500&height=230&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                    class="w-full h-[230px] border-0"
                                    scrolling="no"
                                    frameborder="0"
                                    allowfullscreen="true"
                                    allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                                </iframe>
                            </div>

                            <!-- Thẻ thông tin Fanpage rõ nét (luôn hiển thị đẹp kể cả khi trình duyệt chặn plugin Facebook) -->
                            <div class="p-3.5 rounded-xl bg-blue-50/70 border border-blue-100 flex items-center justify-between gap-3">
                                <div class="flex items-center gap-3 min-w-0">
                                    <img
                                        src="https://lh3.googleusercontent.com/d/1tr19Gbnp3Y2kyG3AgD4_ctjnVaKXoFk_=w200"
                                        data-gdrive-id="1tr19Gbnp3Y2kyG3AgD4_ctjnVaKXoFk_"
                                        data-fallback-text="DAV"
                                        alt="Avatar Fanpage Đức Anh Vũ"
                                        class="w-11 h-11 rounded-full object-contain bg-white border border-blue-200 p-1 shrink-0"
                                        onerror="handleDriveImgError(this)"
                                    >
                                    <div class="min-w-0">
                                        <div class="text-xs sm:text-sm font-bold text-slate-800 truncate">Nhôm Kính Đức Anh Vũ</div>
                                        <div class="text-[11px] text-slate-500 truncate">Cập nhật công trình thực tế mỗi ngày</div>
                                    </div>
                                </div>
                                <a href="https://www.facebook.com/profile.php?id=100063787495394&locale=ca_ES" target="_blank" rel="noopener noreferrer" class="px-3.5 py-2 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold whitespace-nowrap transition shrink-0">
                                    <i class="fa-brands fa-facebook-f mr-1"></i>Theo dõi
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- =======================================================================
         FOOTER FLATSOME (THÔNG TIN CÔNG TY, DANH MỤC DỊCH VỤ, LIÊN HỆ)
    ======================================================================== -->
    <footer style="background-color: var(--brand-primary-dark);" class="text-blue-100 pt-10 pb-6">
        <div class="dav-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-white/15">
                <!-- Cột 1: Thông tin liên hệ -->
                <div class="space-y-3">
                    <div class="flex items-center gap-2.5">
                        <img
                            src="https://lh3.googleusercontent.com/d/1tr19Gbnp3Y2kyG3AgD4_ctjnVaKXoFk_=w250"
                            data-gdrive-id="1tr19Gbnp3Y2kyG3AgD4_ctjnVaKXoFk_"
                            data-fallback-text="DAV"
                            alt="Logo Đức Anh Vũ"
                            class="h-10 w-auto bg-white rounded p-1 object-contain"
                            onerror="handleDriveImgError(this)"
                        >
                        <div class="font-extrabold text-white text-sm uppercase leading-tight">
                            NHÔM KÍNH ĐỨC ANH VŨ
                        </div>
                    </div>
                    <p class="text-xs leading-relaxed text-blue-100/90">
                        <strong>CÔNG TY TNHH MTV TM SX &amp; DV NHÔM KÍNH ĐỨC ANH VŨ</strong> — Chuyên gia công, lắp đặt cửa nhôm Xingfa, cửa kính cường lực uy tín hàng đầu tại Đà Nẵng.
                    </p>
                    <ul class="space-y-2 text-xs">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-yellow-300 mt-0.5"></i>
                            <span>Địa chỉ: Nguyễn Lương Bằng, Liên Chiểu, Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-phone text-yellow-300"></i>
                            <a href="tel:0934434543" class="hover:text-yellow-300 font-bold text-white">Hotline: 0934.434.543</a>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-globe text-yellow-300"></i>
                            <a href="https://ducanhvu.com" class="hover:text-yellow-300">Website: ducanhvu.com</a>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Cửa nhôm Xingfa -->
                <div>
                    <h4 class="text-white font-bold text-sm uppercase mb-3 pb-2 border-b border-white/15">
                        Cửa nhôm Xingfa
                    </h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#san-pham" onclick="filterProducts('1-canh')" class="hover:text-yellow-300 transition">Cửa nhôm Xingfa 1 cánh Đà Nẵng</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('2-canh')" class="hover:text-yellow-300 transition">Cửa nhôm Xingfa 2 cánh Đà Nẵng</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('3-canh')" class="hover:text-yellow-300 transition">Cửa nhôm Xingfa 3 cánh Đà Nẵng</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('4-canh')" class="hover:text-yellow-300 transition">Cửa nhôm Xingfa 4 cánh Đà Nẵng</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('xep-truot')" class="hover:text-yellow-300 transition">Cửa nhôm Xingfa 5 cánh / Xếp trượt</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục dịch vụ -->
                <div>
                    <h4 class="text-white font-bold text-sm uppercase mb-3 pb-2 border-b border-white/15">
                        Danh mục dịch vụ
                    </h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#danh-muc-san-pham" onclick="openCategoryDetail('cua-nhom-xingfa')" class="hover:text-yellow-300 transition">Cửa nhôm Xingfa Đà Nẵng</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="openCategoryDetail('cua-nhua-loi-thep')" class="hover:text-yellow-300 transition">Cửa nhựa lõi thép Đà Nẵng</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="openCategoryDetail('cua-tu-dong')" class="hover:text-yellow-300 transition">Cửa kính tự động Đà Nẵng</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="openCategoryDetail('cau-thang-kinh')" class="hover:text-yellow-300 transition">Cầu thang kính cường lực</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="openCategoryDetail('kinh-op-bep')" class="hover:text-yellow-300 transition">Kính ốp bếp đẹp Đà Nẵng</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="openCategoryDetail('phong-tam-kinh')" class="hover:text-yellow-300 transition">Phòng tắm kính Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Liên kết nhanh & Kết nối -->
                <div>
                    <h4 class="text-white font-bold text-sm uppercase mb-3 pb-2 border-b border-white/15">
                        Kết nối với chúng tôi
                    </h4>
                    <p class="text-xs text-blue-100/90 mb-3 leading-relaxed">
                        Hỗ trợ tư vấn, khảo sát đo đạc và gửi mẫu nhôm kính trực tiếp tại công trình 24/7.
                    </p>
                    <div class="flex flex-wrap gap-2">
                        <a href="tel:0934434543" class="inline-flex items-center gap-1.5 px-3 py-2 rounded-lg bg-red-600 hover:bg-red-700 text-white text-xs font-bold transition">
                            <i class="fa-solid fa-phone"></i> 0934.434.543
                        </a>
                        <a href="https://zalo.me/0934434543" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 px-3 py-2 rounded-lg bg-[#0068FF] hover:bg-blue-600 text-white text-xs font-bold transition">
                            <i class="fa-solid fa-comment-dots"></i> Zalo
                        </a>
                        <a href="https://www.facebook.com/profile.php?id=100063787495394&locale=ca_ES" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 px-3 py-2 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold transition">
                            <i class="fa-brands fa-facebook-f"></i> Facebook
                        </a>
                    </div>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-blue-200/80 text-center">
                <div>Copyright &copy; 2026 Công Ty TNHH MTV TM SX &amp; DV Nhôm Kính Đức Anh Vũ (ducanhvu.com).</div>
                <div>Thiết kế chuẩn bố cục Flatsome UX Builder.</div>
            </div>
        </div>
    </footer>

    <!-- =======================================================================
         CỤM NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE - TƯƠNG THÍCH MOBILE & PC)
    ======================================================================== -->
    <div class="dav-floating-contacts" aria-label="Liên hệ nhanh">
        <!-- Nút Zalo -->
        <a href="https://zalo.me/0934434543" target="_blank" rel="noopener noreferrer" title="Nhắn tin Zalo 0934.434.543" class="dav-float-btn" style="background-color: #0068FF;">
            <span class="font-extrabold text-[13px] tracking-tight">Zalo</span>
            <span class="hidden sm:inline text-xs font-semibold">Chat Zalo</span>
        </a>

        <!-- Nút Facebook -->
        <a href="https://www.facebook.com/profile.php?id=100063787495394&locale=ca_ES" target="_blank" rel="noopener noreferrer" title="Fanpage Facebook Đức Anh Vũ" class="dav-float-btn" style="background-color: #1877F2;">
            <i class="fa-brands fa-facebook-f text-base"></i>
            <span class="hidden sm:inline text-xs font-semibold">Facebook</span>
        </a>

        <!-- Nút Hotline -->
        <a href="tel:0934434543" title="Gọi Hotline 0934.434.543" class="dav-float-btn dav-hotline-pulse" style="background-color: var(--brand-accent);">
            <i class="fa-solid fa-phone-volume text-base"></i>
            <span class="text-xs sm:text-[13px] font-extrabold">0934.434.543</span>
        </a>

        <!-- Nút cuộn lên đầu trang -->
        <button id="backToTopBtn" type="button" aria-label="Lên đầu trang" class="hidden w-10 h-10 rounded-full bg-slate-800/85 hover:bg-slate-900 text-white shadow-lg items-center justify-center transition">
            <i class="fa-solid fa-chevron-up text-sm"></i>
        </button>
    </div>

    <!-- =======================================================================
         MODAL CHI TIẾT SẢN PHẨM / DANH MỤC / BÀI VIẾT
    ======================================================================== -->
    <div id="detailModal" class="fixed inset-0 bg-black/60 z-[110] hidden items-center justify-center p-3 sm:p-4">
        <div class="bg-white rounded-2xl max-w-xl w-full max-h-[90vh] overflow-y-auto shadow-2xl">
            <div class="flex items-center justify-between px-5 py-3.5 border-b border-slate-200 sticky top-0 bg-white z-10">
                <h3 id="modalTitle" class="font-extrabold text-sm sm:text-base text-slate-800 pr-3"></h3>
                <button id="closeModalBtn" type="button" aria-label="Đóng hộp thoại" class="w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-600 flex items-center justify-center shrink-0">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div id="modalBody" class="p-5 space-y-4 text-sm text-slate-600"></div>
        </div>
    </div>

    <!-- =======================================================================
         JAVASCRIPT ĐIỀU KHIỂN TOÀN BỘ TƯƠNG TÁC
    ======================================================================== -->
    <script>
        /* =====================================================================
           1. HÀM DỰ PHÒNG ẢNH GOOGLE DRIVE (Tự động chuyển URL nếu CDN lỗi)
        ===================================================================== */
        function handleDriveImgError(img) {
            const driveId = img.getAttribute('data-gdrive-id');
            const fallbackText = encodeURIComponent(img.getAttribute('data-fallback-text') || 'Duc Anh Vu');
            const attempt = parseInt(img.getAttribute('data-attempt') || '0', 10);

            if (attempt === 0 && driveId) {
                img.setAttribute('data-attempt', '1');
                img.src = 'https://drive.google.com/thumbnail?id=' + driveId + '&sz=w1000';
            } else if (attempt === 1) {
                img.setAttribute('data-attempt', '2');
                img.src = 'https://placehold.co/600x450/0b3b8c/ffffff?text=' + fallbackText;
            }
        }

        /* =====================================================================
           2. DỮ LIỆU 6 SẢN PHẨM CHÍNH (GIÁ + GIẢM GIÁ % GÓC TRÊN TRÁI + ẢNH DRIVE)
        ===================================================================== */
        const productsData = [
            {
                id: 'xingfa-1-canh',
                category: '1-canh',
                name: 'Cửa đi quay mở 1 cánh nhôm Xingfa',
                driveId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
                originalPrice: '2.450.000 ₫',
                salePrice: '2.100.000 ₫',
                discount: '-14%',
                specs: 'Nhôm Xingfa hệ 55 dày 2.0mm, kính cường lực 8mm-10mm, phụ kiện Kinlong chính hãng đồng bộ. Phù hợp cửa phòng ngủ, cửa thông phòng, cửa ban công.'
            },
            {
                id: 'xingfa-2-canh',
                category: '2-canh',
                name: 'Cửa đi quay mở 2 cánh nhôm Xingfa',
                driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
                originalPrice: '2.500.000 ₫',
                salePrice: '2.100.000 ₫',
                discount: '-16%',
                specs: 'Nhôm Xingfa tem đỏ Quảng Đông hệ 55 dày 2.0mm, gioăng kép EPDM kín khít tuyệt đối, chống ồn, chống thấm nước mưa hiệu quả.'
            },
            {
                id: 'xingfa-3-canh',
                category: '3-canh',
                name: 'Cửa đi quay mở 3 cánh nhôm Xingfa',
                driveId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
                originalPrice: '2.550.000 ₫',
                salePrice: '2.100.000 ₫',
                discount: '-18%',
                specs: 'Thiết kế mở rộng tối đa không gian lối đi, kết cấu vững chắc chịu lực gió lớn, sơn tĩnh điện ngoài trời cao cấp bảo hành dài hạn.'
            },
            {
                id: 'xingfa-4-canh',
                category: '4-canh',
                name: 'Cửa đi quay mở 4 cánh nhôm Xingfa',
                driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
                originalPrice: '2.600.000 ₫',
                salePrice: '2.100.000 ₫',
                discount: '-19%',
                specs: 'Lựa chọn hàng đầu cho cửa mặt tiền nhà phố, biệt thự, khách sạn. Khóa đa điểm an toàn chống trộm cao, sang trọng và hiện đại.'
            },
            {
                id: 'xingfa-xep-truot',
                category: 'xep-truot',
                name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
                driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
                originalPrice: '2.650.000 ₫',
                salePrice: '2.100.000 ₫',
                discount: '-21%',
                specs: 'Nhôm Xingfa hệ 63 chuyên dụng xếp trượt (từ 3 cánh, 4 cánh, 5 cánh, 6 cánh), vận hành ray trượt êm ái, mở rộng tối đa 95% diện tích khung cửa.'
            },
            {
                id: 'xingfa-mo-hat-2-canh',
                category: 'xep-truot',
                name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
                driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
                originalPrice: '2.400.000 ₫',
                salePrice: '2.050.000 ₫',
                discount: '-15%',
                specs: 'Nhôm Xingfa hệ 55 dày 1.4mm, mở hất góc 45 độ kèm thanh định vị chống gió va đập, tránh hắt mưa tối ưu cho nhà cao tầng & khách sạn.'
            }
        ];

        /* =====================================================================
           3. DỮ LIỆU DANH MỤC SẢN PHẨM & BÀI VIẾT
        ===================================================================== */
        const categoryDetails = {
            'cua-nhom-xingfa': {
                title: 'Cửa Nhôm Xingfa Chính Hãng Đà Nẵng',
                driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
                desc: 'Gia công bằng dây chuyền máy ép góc CNC hiện đại, sử dụng thanh nhôm Xingfa nhập khẩu chính hãng kết hợp phụ kiện Kinlong và keo ép góc chuyên dụng. Đa dạng màu sắc: Đen tuyền, Xám ghi, Trắng sứ, Nâu cà phê, Vân gỗ.'
            },
            'cua-nhua-loi-thep': {
                title: 'Cửa Nhựa Lõi Thép uPVC Cao Cấp',
                driveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
                desc: 'Thanh nhựa uPVC có lõi thép gia cường bên trong giúp cách âm, cách nhiệt vượt trội, không cong vênh mối mọt, chi phí tối ưu cho cửa phòng ngủ, cửa nhà vệ sinh và văn phòng.'
            },
            'cua-tu-dong': {
                title: 'Cửa Kính Tự Động Đà Nẵng',
                driveId: '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ',
                desc: 'Hệ thống mắt thần cảm biến thông minh, motor vận hành êm ái bền bỉ, chuyên lắp đặt cho sảnh khách sạn, showroom, trung tâm thương mại, siêu thị và văn phòng hiện đại.'
            },
            'cau-thang-kinh': {
                title: 'Cầu Thang Kính & Lan Can Kính Cường Lực',
                driveId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
                desc: 'Kính cường lực 10mm – 12mm an toàn kết hợp tay vịn gỗ hoặc inox 304, trụ lửng/pad đơn hiện đại giúp nới rộng không gian và lấy sáng tự nhiên tối đa cho ngôi nhà.'
            },
            'kinh-op-bep': {
                title: 'Kính Cường Lực Ốp Bếp Sơn Màu Đẹp',
                driveId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
                desc: 'Kính cường lực 8mm chịu nhiệt cao, bề mặt phẳng mịn không mạch vữa giúp lau chùi dầu mỡ cực kỳ dễ dàng với bảng màu phong thủy phong phú.'
            },
            'phong-tam-kinh': {
                title: 'Phòng Tắm Kính (Cabin Tắm Kính Cường Lực)',
                driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
                desc: 'Thiết kế cabin tắm kính mở quay 90°, 135°, 180° hoặc cửa lùa tiết kiệm diện tích, phụ kiện inox 304 chống gỉ sét, ngăn nước bắn tuyệt đối giúp phòng tắm luôn khô ráo sạch sẽ.'
            }
        };

        const articlesData = [
            {
                title: 'Cửa nhôm Xingfa có phù hợp với khí hậu ven biển Đà Nẵng không?',
                driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
                content: 'Đà Nẵng có khí hậu nhiệt đới gió mùa ven biển, độ ẩm cao và thường chịu gió lớn vào mùa mưa bão. Cửa nhôm Xingfa với bề mặt sơn tĩnh điện cao cấp ngoài trời có khả năng chống oxy hóa, chống ăn mòn muối biển vượt trội. Kết hợp hệ gioăng cao su EPDM và kính cường lực giúp cửa kín nước, chịu áp lực gió mạnh và bền đẹp trên 20 năm.'
            },
            {
                title: 'Cửa nhôm Xingfa có tiết kiệm năng lượng & cách âm tốt không?',
                driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
                content: 'Nhờ cấu trúc thanh nhôm dạng hộp chia thành nhiều khoang trống kết hợp công nghệ ép góc tiên tiến và hệ kính an toàn/kính hộp, cửa nhôm Xingfa giảm truyền nhiệt từ bên ngoài vào phòng hiệu quả, giúp tiết kiệm đáng kể điện năng cho máy điều hòa đồng thời hạn chế tiếng ồn đô thị.'
            },
            {
                title: 'Nên chọn cửa nhôm Xingfa hay cửa nhựa lõi thép cho nhà phố?',
                driveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
                content: 'Nếu bạn ưu tiên độ cứng vững, khung viền thanh mảnh sang trọng, khả năng chịu nắng mưa trực tiếp ở mặt tiền và ban công thì cửa nhôm Xingfa là lựa chọn tối ưu. Trong khi đó, cửa nhựa lõi thép có giá thành mềm hơn và cách âm tốt, rất phù hợp cho các vị trí trong nhà như cửa phòng ngủ hay nhà vệ sinh.'
            },
            {
                title: 'Kinh nghiệm chọn kính cường lực cho phòng tắm kính & bếp đẹp',
                driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
                content: 'Đối với kính ốp bếp, độ dày tiêu chuẩn tốt nhất là kính cường lực 8mm chịu nhiệt cao. Đối với phòng tắm kính và cầu thang kính, nên sử dụng kính cường lực 10mm – 12mm đi kèm phụ kiện kẹp, bản lề bằng Inox 304 chính hãng để đảm bảo an toàn tuyệt đối và không bị han gỉ trong môi trường ẩm ướt.'
            }
        ];

        /* =====================================================================
           4. RENDER SẢN PHẨM (2 CỘT MOBILE, GIÁ + GIẢM GIÁ % GÓC TRÊN TRÁI, KHÔNG CẮT CHỮ)
        ===================================================================== */
        function renderProducts(list) {
            const grid = document.getElementById('productGrid');
            const emptyMsg = document.getElementById('noProductMsg');

            if (!list || list.length === 0) {
                grid.innerHTML = '';
                emptyMsg.classList.remove('hidden');
                return;
            }

            emptyMsg.classList.add('hidden');
            grid.innerHTML = list.map((p) => `
                <article class="ux-product-card">
                    <div class="relative aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <!-- Giảm giá % góc trên bên trái sản phẩm -->
                        <span class="ux-discount-badge">${p.discount}</span>
                        <img
                            src="https://lh3.googleusercontent.com/d/${p.driveId}=w700"
                            data-gdrive-id="${p.driveId}"
                            data-fallback-text="${p.name}"
                            alt="${p.name}"
                            class="w-full h-full object-cover transition duration-300 hover:scale-105 cursor-pointer"
                            onclick="openProductModal('${p.id}')"
                            onerror="handleDriveImgError(this)"
                        >
                    </div>
                    <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between gap-2">
                        <div>
                            <!-- Tên sản phẩm đầy đủ, không bị tràn hoặc cắt chữ -->
                            <h3
                                onclick="openProductModal('${p.id}')"
                                class="text-[12.5px] sm:text-sm md:text-[15px] font-bold text-slate-800 leading-snug break-words whitespace-normal cursor-pointer hover:text-blue-800 transition"
                            >
                                ${p.name}
                            </h3>
                        </div>

                        <div class="pt-1 border-t border-slate-100 space-y-2">
                            <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                                <span class="text-[13px] sm:text-base font-extrabold" style="color: var(--brand-accent);">
                                    ${p.salePrice}
                                </span>
                                <span class="text-[11px] sm:text-xs text-slate-400 line-through">
                                    ${p.originalPrice}
                                </span>
                            </div>

                            <div class="grid grid-cols-2 gap-1.5">
                                <button
                                    type="button"
                                    onclick="openProductModal('${p.id}')"
                                    class="py-1.5 px-2 rounded-lg border border-blue-800 text-blue-800 hover:bg-blue-50 text-[11px] sm:text-xs font-bold transition text-center"
                                >
                                    Xem nhanh
                                </button>
                                <a
                                    href="#bao-gia"
                                    onclick="selectQuoteService('${p.name}')"
                                    style="background-color: var(--brand-primary);"
                                    class="py-1.5 px-2 rounded-lg text-white hover:opacity-90 text-[11px] sm:text-xs font-bold transition text-center"
                                >
                                    Báo giá
                                </a>
                            </div>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        function filterProducts(category) {
            // Cập nhật trạng thái nút lọc
            document.querySelectorAll('.product-filter-btn').forEach((btn) => {
                const isMatch = btn.getAttribute('data-filter') === category;
                if (isMatch) {
                    btn.style.backgroundColor = 'var(--brand-primary)';
                    btn.style.borderColor = 'var(--brand-primary)';
                    btn.classList.add('text-white');
                    btn.classList.remove('bg-white', 'text-slate-700');
                } else {
                    btn.style.backgroundColor = '';
                    btn.style.borderColor = '';
                    btn.classList.remove('text-white');
                    btn.classList.add('bg-white', 'text-slate-700');
                }
            });

            if (category === 'all') {
                renderProducts(productsData);
            } else {
                renderProducts(productsData.filter((item) => item.category === category));
            }
        }

        function selectQuoteService(productName) {
            const noteEl = document.getElementById('qNote');
            if (noteEl) {
                noteEl.value = 'Tôi cần tư vấn và báo giá mẫu: ' + productName;
            }
        }

        /* =====================================================================
           5. MODAL XEM NHANH SẢN PHẨM / DANH MỤC / BÀI VIẾT
        ===================================================================== */
        const detailModal = document.getElementById('detailModal');
        const modalTitle = document.getElementById('modalTitle');
        const modalBody = document.getElementById('modalBody');

        function showModal(title, htmlContent) {
            modalTitle.textContent = title;
            modalBody.innerHTML = htmlContent;
            detailModal.classList.remove('hidden');
            detailModal.classList.add('flex');
        }

        function closeModal() {
            detailModal.classList.add('hidden');
            detailModal.classList.remove('flex');
        }

        function openProductModal(productId) {
            const p = productsData.find((item) => item.id === productId);
            if (!p) return;
            showModal(p.name, `
                <div class="relative rounded-xl overflow-hidden bg-slate-100">
                    <span class="ux-discount-badge">${p.discount}</span>
                    <img
                        src="https://lh3.googleusercontent.com/d/${p.driveId}=w900"
                        data-gdrive-id="${p.driveId}"
                        data-fallback-text="${p.name}"
                        alt="${p.name}"
                        class="w-full max-h-72 object-cover"
                        onerror="handleDriveImgError(this)"
                    >
                </div>
                <div class="flex items-baseline gap-3">
                    <span class="text-xl font-extrabold" style="color: var(--brand-accent);">${p.salePrice}/m²</span>
                    <span class="text-sm text-slate-400 line-through">${p.originalPrice}</span>
                </div>
                <p class="leading-relaxed text-slate-700">${p.specs}</p>
                <div class="flex flex-wrap gap-2.5 pt-2">
                    <a href="tel:0934434543" class="flex-1 min-w-[140px] py-2.5 px-4 rounded-lg text-white font-bold text-center text-xs sm:text-sm" style="background-color: var(--brand-accent);">
                        <i class="fa-solid fa-phone mr-1.5"></i>Gọi 0934.434.543
                    </a>
                    <a href="#bao-gia" onclick="closeModal(); selectQuoteService('${p.name}');" class="flex-1 min-w-[140px] py-2.5 px-4 rounded-lg text-white font-bold text-center text-xs sm:text-sm" style="background-color: var(--brand-primary);">
                        <i class="fa-solid fa-file-pen mr-1.5"></i>Yêu cầu báo giá
                    </a>
                </div>
            `);
        }

        function openCategoryDetail(key) {
            const cat = categoryDetails[key];
            if (!cat) return;
            showModal(cat.title, `
                <div class="rounded-xl overflow-hidden bg-slate-100">
                    <img
                        src="https://lh3.googleusercontent.com/d/${cat.driveId}=w900"
                        data-gdrive-id="${cat.driveId}"
                        data-fallback-text="${cat.title}"
                        alt="${cat.title}"
                        class="w-full max-h-72 object-cover"
                        onerror="handleDriveImgError(this)"
                    >
                </div>
                <p class="leading-relaxed text-slate-700">${cat.desc}</p>
                <div class="flex flex-wrap gap-2.5 pt-2">
                    <a href="https://zalo.me/0934434543" target="_blank" rel="noopener noreferrer" class="flex-1 min-w-[140px] py-2.5 px-4 rounded-lg bg-[#0068FF] text-white font-bold text-center text-xs sm:text-sm">
                        Nhắn Zalo nhận mẫu
                    </a>
                    <a href="#bao-gia" onclick="closeModal(); selectQuoteService('${cat.title}');" class="flex-1 min-w-[140px] py-2.5 px-4 rounded-lg text-white font-bold text-center text-xs sm:text-sm" style="background-color: var(--brand-primary);">
                        Nhận báo giá ngay
                    </a>
                </div>
            `);
        }

        function openArticleModal(idx) {
            const art = articlesData[idx];
            if (!art) return;
            showModal(art.title, `
                <div class="rounded-xl overflow-hidden bg-slate-100">
                    <img
                        src="https://lh3.googleusercontent.com/d/${art.driveId}=w900"
                        data-gdrive-id="${art.driveId}"
                        data-fallback-text="Tin Tuc Nhom Kinh"
                        alt="${art.title}"
                        class="w-full max-h-64 object-cover"
                        onerror="handleDriveImgError(this)"
                    >
                </div>
                <p class="leading-relaxed text-slate-700">${art.content}</p>
                <div class="p-3.5 rounded-xl bg-blue-50 border border-blue-100 text-xs text-slate-700">
                    Cần tư vấn miễn phí về giải pháp cửa nhôm kính cho công trình tại Đà Nẵng? Liên hệ ngay <strong>Công Ty Nhôm Kính Đức Anh Vũ</strong> qua Hotline <strong>0934.434.543</strong>.
                </div>
            `);
        }

        /* =====================================================================
           6. KHỞI TẠO SLIDER 2 BANNER TỰ TRƯỢT, MENU MOBILE, TÌM KIẾM & FORM
        ===================================================================== */
        window.addEventListener('DOMContentLoaded', function () {
            // Render danh sách sản phẩm ban đầu
            renderProducts(productsData);

            // --- Banner Auto Slider (2 Banner kích thước bằng nhau, hỗ trợ vuốt cảm ứng) ---
            const slides = document.querySelectorAll('.dav-banner-slide');
            const dots = document.querySelectorAll('.banner-dot');
            const sliderEl = document.getElementById('heroBannerSlider');
            let currentSlide = 0;
            let slideTimer = null;

            function goToSlide(index) {
                currentSlide = (index + slides.length) % slides.length;
                slides.forEach((s, i) => s.classList.toggle('is-active', i === currentSlide));
                dots.forEach((d, i) => {
                    if (i === currentSlide) {
                        d.classList.add('w-7', 'bg-yellow-400');
                        d.classList.remove('w-2.5', 'bg-white/50');
                    } else {
                        d.classList.remove('w-7', 'bg-yellow-400');
                        d.classList.add('w-2.5', 'bg-white/50');
                    }
                });
            }

            function startAutoSlide() {
                stopAutoSlide();
                slideTimer = setInterval(() => goToSlide(currentSlide + 1), 5000);
            }

            function stopAutoSlide() {
                if (slideTimer) clearInterval(slideTimer);
            }

            document.getElementById('bannerPrev').addEventListener('click', () => {
                goToSlide(currentSlide - 1);
                startAutoSlide();
            });
            document.getElementById('bannerNext').addEventListener('click', () => {
                goToSlide(currentSlide + 1);
                startAutoSlide();
            });
            dots.forEach((dot) => {
                dot.addEventListener('click', () => {
                    goToSlide(parseInt(dot.getAttribute('data-slide'), 10));
                    startAutoSlide();
                });
            });

            // Hỗ trợ vuốt cảm ứng trên điện thoại cho Banner
            let touchStartX = 0;
            sliderEl.addEventListener('touchstart', (e) => {
                touchStartX = e.changedTouches[0].screenX;
                stopAutoSlide();
            }, { passive: true });
            sliderEl.addEventListener('touchend', (e) => {
                const diff = touchStartX - e.changedTouches[0].screenX;
                if (Math.abs(diff) > 40) {
                    goToSlide(diff > 0 ? currentSlide + 1 : currentSlide - 1);
                }
                startAutoSlide();
            }, { passive: true });

            sliderEl.addEventListener('mouseenter', stopAutoSlide);
            sliderEl.addEventListener('mouseleave', startAutoSlide);
            startAutoSlide();

            // --- Menu Mobile Drawer ---
            const mobileDrawer = document.getElementById('mobileDrawer');
            const mobileOverlay = document.getElementById('mobileOverlay');

            function toggleMobileMenu(show) {
                mobileDrawer.classList.toggle('open', show);
                mobileOverlay.classList.toggle('hidden', !show);
                document.body.style.overflow = show ? 'hidden' : '';
            }

            document.getElementById('mobileMenuBtn').addEventListener('click', () => toggleMobileMenu(true));
            document.getElementById('closeMobileMenu').addEventListener('click', () => toggleMobileMenu(false));
            mobileOverlay.addEventListener('click', () => toggleMobileMenu(false));
            document.querySelectorAll('.mobile-nav-link').forEach((link) => {
                link.addEventListener('click', () => toggleMobileMenu(false));
            });

            // Accordion menu con trên Mobile
            document.querySelectorAll('.accordion-toggle').forEach((btn) => {
                btn.addEventListener('click', function () {
                    const content = this.nextElementSibling;
                    const icon = this.querySelector('i');
                    content.classList.toggle('hidden');
                    icon.classList.toggle('rotate-180');
                });
            });

            // --- Tìm kiếm sản phẩm ---
            const mobileSearchBar = document.getElementById('mobileSearchBar');
            document.getElementById('mobileSearchToggle').addEventListener('click', () => {
                mobileSearchBar.classList.toggle('hidden');
            });

            function handleSearch(keyword) {
                const q = (keyword || '').trim().toLowerCase();
                const matched = productsData.filter((p) =>
                    p.name.toLowerCase().includes(q) || p.specs.toLowerCase().includes(q)
                );
                renderProducts(q ? matched : productsData);
                document.getElementById('san-pham').scrollIntoView({ behavior: 'smooth' });
            }

            document.getElementById('headerSearchForm').addEventListener('submit', function (e) {
                e.preventDefault();
                handleSearch(document.getElementById('searchInput').value);
            });

            document.getElementById('mobileSearchForm').addEventListener('submit', function (e) {
                e.preventDefault();
                handleSearch(document.getElementById('mobileSearchInput').value);
                mobileSearchBar.classList.add('hidden');
            });

            // --- Form yêu cầu báo giá ---
            document.getElementById('quoteForm').addEventListener('submit', function (e) {
                e.preventDefault();
                const name = document.getElementById('qName').value.trim();
                const phone = document.getElementById('qPhone').value.trim();
                const service = document.getElementById('qService').value;
                const feedback = document.getElementById('quoteFeedback');

                if (!name || !phone) return;

                feedback.textContent = 'Cảm ơn ' + name + '! Yêu cầu báo giá "' + service + '" của bạn đã được ghi nhận. Nhôm Kính Đức Anh Vũ sẽ liên hệ qua số ' + phone + ' trong thời gian sớm nhất.';
                feedback.classList.remove('hidden');
                this.reset();
            });

            // --- Đóng Modal ---
            document.getElementById('closeModalBtn').addEventListener('click', closeModal);
            detailModal.addEventListener('click', function (e) {
                if (e.target === detailModal) closeModal();
            });

            // --- Nút lên đầu trang ---
            const backToTopBtn = document.getElementById('backToTopBtn');
            window.addEventListener('scroll', () => {
                if (window.scrollY > 380) {
                    backToTopBtn.classList.remove('hidden');
                    backToTopBtn.classList.add('flex');
                } else {
                    backToTopBtn.classList.add('hidden');
                    backToTopBtn.classList.remove('flex');
                }
            });
            backToTopBtn.addEventListener('click', () => {
                window.scrollTo({ top: 0, behavior: 'smooth' });
            });
        });
    </script>
</body>
</html>
