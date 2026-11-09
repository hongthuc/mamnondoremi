<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Mầm Non Doremi - Chương Trình Giáo Dục Hiện Đại Tại Đà Nẵng | mamnondoremi.com</title>
    <meta name="description" content="Mầm non Doremi (mamnondoremi.com) - Chương trình giáo dục hiện đại, chú trọng phát triển trí tuệ, kỹ năng và nhân cách cho trẻ. Môi trường an toàn, yêu thương, giúp trẻ phát triển toàn diện thông qua học mà chơi – chơi mà học. Địa chỉ: 118 Hà Duy Phiên, Phường Hoà Xuân, Đà Nẵng.">

    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://mamnondoremi.com/">
    <meta property="og:site_name" content="mamnondoremi.com">
    <meta property="og:title" content="Mầm Non Doremi - Học Mà Chơi, Chơi Mà Học | mamnondoremi.com">
    <meta property="og:description" content="Chương trình giáo dục hiện đại, chú trọng phát triển trí tuệ, kỹ năng và nhân cách cho trẻ. Địa chỉ: 118 Hà Duy Phiên, Phường Hoà Xuân, Đà Nẵng - Hotline: 0919.027.681">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1oEWr9xKObkPIg-_4skHWRAJbXHHfoAVJ">
    <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/1oEWr9xKObkPIg-_4skHWRAJbXHHfoAVJ">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1oEWr9xKObkPIg-_4skHWRAJbXHHfoAVJ">
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1oEWr9xKObkPIg-_4skHWRAJbXHHfoAVJ">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Google Fonts: Inter / Roboto chuẩn Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        doremi: {
                            blue: '#0d6efd',
                            darkblue: '#084298',
                            lightblue: '#eef6ff',
                            green: '#2e7d32',
                            lightgreen: '#f1f8e9',
                            orange: '#f59e0b',
                            red: '#e11d48'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif']
                    }
                }
            }
        }
    </script>

    <style>
        /* Khóa tràn viền ngang tuyệt đối trên mọi thiết bị, đảm bảo không lệch phải */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            background-color: #ffffff;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Khung chuẩn Flatsome rộng 1500px trên máy tính */
        .flatsome-container {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 768px) {
            .flatsome-container {
                padding-left: 20px;
                padding-right: 20px;
            }
        }

        /* Tối ưu tên danh mục viết liền trên 1 hàng, chữ nhỏ gọn, không xuống dòng */
        .cat-nowrap {
            white-space: nowrap;
        }

        /* Ẩn thanh cuộn nhưng vẫn cho phép vuốt mượt trên điện thoại nếu cần */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }

        /* Hiệu ứng chuyển cảnh mượt cho Banner Slider */
        .banner-slide {
            transition: opacity 0.6s ease-in-out;
        }

        /* Đảm bảo tên sản phẩm hiển thị đầy đủ, không bị cắt chữ hoặc tràn ra ngoài */
        .product-title-full {
            word-break: break-word;
            overflow-wrap: break-word;
            white-space: normal;
            line-height: 1.38;
        }
    </style>
</head>
<body class="w-full overflow-x-hidden">

    <!-- ==========================================
         TOP BAR (Chuẩn bố cục Edunow / Flatsome)
         ========================================== -->
    <div class="bg-[#084298] text-white text-xs py-2 w-full">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center flex-wrap gap-3 md:gap-5">
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-location-dot text-amber-300"></i>
                    <span>118 Hà Duy Phiên, Phường Hoà Xuân, Đà Nẵng</span>
                </span>
                <span class="hidden sm:inline-flex items-center gap-1.5">
                    <i class="fa-regular fa-clock text-amber-300"></i>
                    <span>06:30 - 18:00 (Thứ 2 - Thứ 7)</span>
                </span>
            </div>
            <div class="flex items-center gap-4">
                <a href="https://mamnondoremi.com" class="hover:text-amber-300 transition hidden md:inline-flex items-center gap-1">
                    <i class="fa-solid fa-globe"></i> mamnondoremi.com
                </a>
                <a href="tel:0919027681" class="font-semibold text-amber-300 hover:underline inline-flex items-center gap-1">
                    <i class="fa-solid fa-phone"></i> 0919.027.681
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER CHÍNH (Logo gọn nhỏ, Không để nút gọi ngay để tránh tràn viền)
         ========================================== -->
    <header class="sticky top-0 z-40 bg-white border-b border-slate-200 shadow-sm w-full">
        <div class="flatsome-container py-2.5 flex items-center justify-between gap-3">
            <!-- Logo chỉnh gọn nhỏ lại -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0">
                <img 
                    src="https://lh3.googleusercontent.com/d/1oEWr9xKObkPIg-_4skHWRAJbXHHfoAVJ" 
                    onerror="if(!this.dataset.fb){this.dataset.fb='1';this.src='https://drive.google.com/thumbnail?id=1oEWr9xKObkPIg-_4skHWRAJbXHHfoAVJ&sz=w400';}else{this.src='https://placehold.co/120x120/0d6efd/ffffff?text=DOREMI';}"
                    alt="Logo Mầm Non Doremi" 
                    class="h-10 md:h-11 w-auto object-contain rounded-lg border border-slate-100 p-0.5 bg-white"
                >
                <div class="leading-tight">
                    <span class="block text-sm md:text-base font-extrabold text-[#084298] tracking-tight">MẦM NON DOREMI</span>
                    <span class="block text-[10px] md:text-[11px] text-emerald-700 font-medium">mamnondoremi.com</span>
                </div>
            </a>

            <!-- Menu danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng từng mục -->
            <nav class="hidden lg:flex items-center justify-end flex-wrap gap-x-1.5 gap-y-1">
                <a href="#trang-chu" class="cat-nowrap px-2.5 py-1.5 text-[12.5px] font-semibold text-[#084298] bg-blue-50 rounded-md hover:bg-[#0d6efd] hover:text-white transition">Trang Chủ</a>
                <a href="#gioi-thieu" class="cat-nowrap px-2.5 py-1.5 text-[12.5px] font-semibold text-slate-700 rounded-md hover:bg-[#0d6efd] hover:text-white transition">Giới Thiệu</a>
                <a href="#danh-muc-chuong-trinh" class="cat-nowrap px-2.5 py-1.5 text-[12.5px] font-semibold text-slate-700 rounded-md hover:bg-[#0d6efd] hover:text-white transition">Lớp Nhà Trẻ & Mẫu Giáo</a>
                <a href="#danh-muc-chuong-trinh" class="cat-nowrap px-2.5 py-1.5 text-[12.5px] font-semibold text-slate-700 rounded-md hover:bg-[#0d6efd] hover:text-white transition">Tiền Học Đường</a>
                <a href="#danh-muc-chuong-trinh" class="cat-nowrap px-2.5 py-1.5 text-[12.5px] font-semibold text-slate-700 rounded-md hover:bg-[#0d6efd] hover:text-white transition">Học Bán Trú</a>
                <a href="#danh-muc-chuong-trinh" class="cat-nowrap px-2.5 py-1.5 text-[12.5px] font-semibold text-slate-700 rounded-md hover:bg-[#0d6efd] hover:text-white transition">Phát Triển Kỹ Năng & STEAM</a>
                <a href="#danh-muc-chuong-trinh" class="cat-nowrap px-2.5 py-1.5 text-[12.5px] font-semibold text-slate-700 rounded-md hover:bg-[#0d6efd] hover:text-white transition">Đánh Giá & Tư Vấn</a>
                <a href="#hoat-dong" class="cat-nowrap px-2.5 py-1.5 text-[12.5px] font-semibold text-slate-700 rounded-md hover:bg-[#0d6efd] hover:text-white transition">Hoạt Động</a>
                <a href="#bai-viet" class="cat-nowrap px-2.5 py-1.5 text-[12.5px] font-semibold text-slate-700 rounded-md hover:bg-[#0d6efd] hover:text-white transition">Kiến Thức & Tin Tức</a>
                <a href="#doi-tac" class="cat-nowrap px-2.5 py-1.5 text-[12.5px] font-semibold text-slate-700 rounded-md hover:bg-[#0d6efd] hover:text-white transition">Đối Tác</a>
                <a href="#lien-he" class="cat-nowrap px-2.5 py-1.5 text-[12.5px] font-semibold text-slate-700 rounded-md hover:bg-[#0d6efd] hover:text-white transition">Liên Hệ</a>
            </nav>

            <!-- Nút mở menu trên điện thoại (không để nút gọi ngay để tránh tràn viền) -->
            <button id="mobileMenuBtn" type="button" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center justify-center w-9 h-9 rounded-lg border border-slate-200 text-[#084298] hover:bg-blue-50">
                <i class="fa-solid fa-bars text-base"></i>
            </button>
        </div>

        <!-- Menu xổ xuống trên điện thoại -->
        <div id="mobileMenuPanel" class="hidden lg:hidden bg-white border-t border-slate-100 px-3 py-3">
            <div class="grid grid-cols-2 gap-1.5 text-xs font-semibold">
                <a href="#trang-chu" class="mobile-nav-link px-3 py-2 rounded-md bg-blue-50 text-[#084298] cat-nowrap">Trang Chủ</a>
                <a href="#gioi-thieu" class="mobile-nav-link px-3 py-2 rounded-md bg-slate-50 text-slate-700 cat-nowrap">Giới Thiệu</a>
                <a href="#danh-muc-chuong-trinh" class="mobile-nav-link px-3 py-2 rounded-md bg-slate-50 text-slate-700 cat-nowrap">Nhà Trẻ & Mẫu Giáo</a>
                <a href="#danh-muc-chuong-trinh" class="mobile-nav-link px-3 py-2 rounded-md bg-slate-50 text-slate-700 cat-nowrap">Tiền Học Đường</a>
                <a href="#danh-muc-chuong-trinh" class="mobile-nav-link px-3 py-2 rounded-md bg-slate-50 text-slate-700 cat-nowrap">Học Bán Trú</a>
                <a href="#danh-muc-chuong-trinh" class="mobile-nav-link px-3 py-2 rounded-md bg-slate-50 text-slate-700 cat-nowrap">Kỹ Năng & STEAM</a>
                <a href="#danh-muc-chuong-trinh" class="mobile-nav-link px-3 py-2 rounded-md bg-slate-50 text-slate-700 cat-nowrap">Đánh Giá & Tư Vấn</a>
                <a href="#hoat-dong" class="mobile-nav-link px-3 py-2 rounded-md bg-slate-50 text-slate-700 cat-nowrap">Hoạt Động Thực Tế</a>
                <a href="#bai-viet" class="mobile-nav-link px-3 py-2 rounded-md bg-slate-50 text-slate-700 cat-nowrap">Kiến Thức Mầm Non</a>
                <a href="#doi-tac" class="mobile-nav-link px-3 py-2 rounded-md bg-slate-50 text-slate-700 cat-nowrap">Đối Tác Liên Kết</a>
                <a href="#lien-he" class="mobile-nav-link col-span-2 text-center px-3 py-2 rounded-md bg-[#084298] text-white cat-nowrap">Liên Hệ & Bản Đồ Chỉ Đường</a>
            </div>
        </div>
    </header>

    <!-- ==========================================
         2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
         - Thiết kế riêng Banner Máy Tính và Banner Điện Thoại khác nhau
         - Chữ nhỏ gọn nằm trọn bên trong ảnh banner, tuyệt đối không tràn viền
         ========================================== -->
    <section id="trang-chu" class="w-full bg-slate-50 py-3 md:py-4">
        <div class="flatsome-container">
            <div class="relative w-full overflow-hidden rounded-2xl shadow-sm border border-slate-200 bg-[#084298]">

                <!-- ================= SLIDE 1 ================= -->
                <div class="banner-slide w-full" data-slide="0">
                    <!-- BANNER 1 TRÊN MÁY TÍNH (Desktop Only - kích thước cố định 420px) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center h-[420px] w-full bg-gradient-to-r from-[#084298] via-[#0d6efd] to-[#1e88e5] text-white px-10 lg:px-14 gap-8">
                        <div class="col-span-7 space-y-3 pr-4">
                            <p class="text-xs font-bold uppercase tracking-wider text-amber-300">TRƯỜNG MẦM NON DOREMI ĐÀ NẴNG - MAMNONDOREMI.COM</p>
                            <h1 class="text-2xl lg:text-3xl font-extrabold leading-snug">
                                CHƯƠNG TRÌNH GIÁO DỤC HIỆN ĐẠI – PHÁT TRIỂN TRÍ TUỆ, KỸ NĂNG & NHÂN CÁCH CHO TRẺ
                            </h1>
                            <p class="text-sm text-blue-50 leading-relaxed max-w-2xl">
                                Môi trường an toàn, yêu thương, giúp trẻ phát triển toàn diện thông qua phương pháp <strong>Học mà chơi – Chơi mà học</strong>. Đồng hành cùng ba mẹ ươm mầm tương lai hạnh phúc cho bé.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-3 text-xs text-white/95">
                                <span class="bg-white/15 px-3 py-1.5 rounded-lg"><i class="fa-solid fa-location-dot text-amber-300 mr-1.5"></i>118 Hà Duy Phiên, P. Hoà Xuân, Đà Nẵng</span>
                                <span class="bg-white/15 px-3 py-1.5 rounded-lg"><i class="fa-solid fa-phone text-amber-300 mr-1.5"></i>Hotline: 0919.027.681</span>
                            </div>
                            <div class="pt-2 flex items-center gap-3">
                                <a href="#danh-muc-chuong-trinh" class="px-5 py-2.5 rounded-lg bg-amber-400 text-slate-900 font-bold text-xs hover:bg-amber-300 transition">Xem Chương Trình Học</a>
                                <a href="#lien-he" class="px-5 py-2.5 rounded-lg bg-white/15 text-white font-semibold text-xs hover:bg-white/25 transition border border-white/30">Đăng Ký Tư Vấn</a>
                            </div>
                        </div>
                        <div class="col-span-5 grid grid-cols-2 gap-3 h-[340px]">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1vajURjF5zyxb04WPTqMlaSy8HY_WbZFN" 
                                onerror="this.src='https://drive.google.com/thumbnail?id=1vajURjF5zyxb04WPTqMlaSy8HY_WbZFN&sz=w800'"
                                alt="Mầm non Doremi Đà Nẵng" 
                                class="w-full h-full object-cover rounded-xl border-2 border-white/40 shadow-md"
                            >
                            <img 
                                src="https://lh3.googleusercontent.com/d/1U5JFS6zCRm06rQp6BFp_XPffcvJlQIBF" 
                                onerror="this.src='https://drive.google.com/thumbnail?id=1U5JFS6zCRm06rQp6BFp_XPffcvJlQIBF&sz=w800'"
                                alt="Hoạt động học tập Mầm non Doremi" 
                                class="w-full h-full object-cover rounded-xl border-2 border-white/40 shadow-md"
                            >
                        </div>
                    </div>

                    <!-- BANNER 1 TRÊN ĐIỆN THOẠI (Mobile Only - Thiết kế riêng biệt, chữ nhỏ gọn nằm hết trong ảnh banner, kích thước 310px) -->
                    <div class="flex md:hidden flex-col justify-between h-[310px] w-full relative overflow-hidden bg-gradient-to-b from-[#084298] to-[#0b5ed7] text-white p-4">
                        <div class="flex items-center gap-2.5">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1oEWr9xKObkPIg-_4skHWRAJbXHHfoAVJ" 
                                onerror="this.src='https://drive.google.com/thumbnail?id=1oEWr9xKObkPIg-_4skHWRAJbXHHfoAVJ&sz=w300'"
                                alt="Logo Doremi" 
                                class="w-9 h-9 rounded-lg bg-white p-0.5 object-contain shrink-0"
                            >
                            <div class="min-w-0">
                                <p class="text-[10px] font-bold text-amber-300 uppercase tracking-tight truncate">MẦM NON DOREMI - MAMNONDOREMI.COM</p>
                                <p class="text-[11px] text-blue-100 truncate">118 Hà Duy Phiên, Hoà Xuân, Đà Nẵng</p>
                            </div>
                        </div>

                        <div class="my-auto py-1">
                            <h2 class="text-[15px] font-extrabold leading-snug text-white">
                                Chương Trình Giáo Dục Hiện Đại – Phát Triển Trí Tuệ, Kỹ Năng & Nhân Cách
                            </h2>
                            <p class="text-[11.5px] text-blue-100 mt-1 leading-normal">
                                Môi trường an toàn, yêu thương, giúp trẻ phát triển toàn diện qua Học mà chơi – Chơi mà học.
                            </p>
                        </div>

                        <div class="grid grid-cols-2 gap-2 items-center pt-1">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1vajURjF5zyxb04WPTqMlaSy8HY_WbZFN" 
                                onerror="this.src='https://drive.google.com/thumbnail?id=1vajURjF5zyxb04WPTqMlaSy8HY_WbZFN&sz=w600'"
                                alt="Ảnh thực tế Doremi 1" 
                                class="w-full h-20 object-cover rounded-lg border border-white/30"
                            >
                            <div class="flex flex-col justify-center gap-1.5">
                                <div class="text-[11px] font-semibold text-amber-300">
                                    <i class="fa-solid fa-phone mr-1"></i>0919.027.681
                                </div>
                                <a href="#danh-muc-chuong-trinh" class="text-center py-1.5 px-2 rounded-md bg-amber-400 text-slate-900 font-bold text-[11px]">
                                    Xem Chương Trình
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- ================= SLIDE 2 ================= -->
                <div class="banner-slide w-full hidden" data-slide="1">
                    <!-- BANNER 2 TRÊN MÁY TÍNH (Desktop Only - kích thước cố định 420px bằng Slide 1) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center h-[420px] w-full bg-gradient-to-r from-[#1b5e20] via-[#2e7d32] to-[#084298] text-white px-10 lg:px-14 gap-8">
                        <div class="col-span-7 space-y-3 pr-4">
                            <p class="text-xs font-bold uppercase tracking-wider text-amber-300">HỌC MÀ CHƠI – CHƠI MÀ HỌC TẠI MẦM NON DOREMI</p>
                            <h2 class="text-2xl lg:text-3xl font-extrabold leading-snug">
                                MÔI TRƯỜNG AN TOÀN, YÊU THƯƠNG – ĐỒNG HÀNH CÙNG TRẺ PHÁT TRIỂN TOÀN DIỆN
                            </h2>
                            <p class="text-sm text-emerald-50 leading-relaxed max-w-2xl">
                                Đa dạng loại hình đào tạo: Lớp Nhà trẻ, Mẫu giáo, Tiền tiểu học, Bán trú tiêu chuẩn, Phát triển ngôn ngữ & Kỹ năng sống STEAM tại Hòa Xuân, Đà Nẵng.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-3 text-xs text-white/95">
                                <span class="bg-white/15 px-3 py-1.5 rounded-lg"><i class="fa-solid fa-location-dot text-amber-300 mr-1.5"></i>118 Hà Duy Phiên, P. Hoà Xuân, Đà Nẵng</span>
                                <span class="bg-white/15 px-3 py-1.5 rounded-lg"><i class="fa-solid fa-phone text-amber-300 mr-1.5"></i>Tư vấn tuyển sinh: 0919.027.681</span>
                            </div>
                            <div class="pt-2 flex items-center gap-3">
                                <a href="#hoat-dong" class="px-5 py-2.5 rounded-lg bg-amber-400 text-slate-900 font-bold text-xs hover:bg-amber-300 transition">Hình Ảnh Thực Tế</a>
                                <a href="#lien-he" class="px-5 py-2.5 rounded-lg bg-white/15 text-white font-semibold text-xs hover:bg-white/25 transition border border-white/30">Xem Bản Đồ Trường</a>
                            </div>
                        </div>
                        <div class="col-span-5 grid grid-cols-2 gap-3 h-[340px]">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1YZQ_Bs6tJ7wpRuutngZBsi4j2w5pGLk-" 
                                onerror="this.src='https://drive.google.com/thumbnail?id=1YZQ_Bs6tJ7wpRuutngZBsi4j2w5pGLk-&sz=w800'"
                                alt="Hoạt động vui chơi Mầm non Doremi" 
                                class="w-full h-full object-cover rounded-xl border-2 border-white/40 shadow-md"
                            >
                            <img 
                                src="https://lh3.googleusercontent.com/d/1sXL1dJdDXxpIthRkY5pfrWTqbNUj3Iaa" 
                                onerror="this.src='https://drive.google.com/thumbnail?id=1sXL1dJdDXxpIthRkY5pfrWTqbNUj3Iaa&sz=w800'"
                                alt="Lớp học thân thiện Mầm non Doremi" 
                                class="w-full h-full object-cover rounded-xl border-2 border-white/40 shadow-md"
                            >
                        </div>
                    </div>

                    <!-- BANNER 2 TRÊN ĐIỆN THOẠI (Mobile Only - Thiết kế riêng biệt, chữ nhỏ gọn nằm hết trong khung 310px) -->
                    <div class="flex md:hidden flex-col justify-between h-[310px] w-full relative overflow-hidden bg-gradient-to-b from-[#1b5e20] to-[#084298] text-white p-4">
                        <div class="flex items-center gap-2.5">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1oEWr9xKObkPIg-_4skHWRAJbXHHfoAVJ" 
                                onerror="this.src='https://drive.google.com/thumbnail?id=1oEWr9xKObkPIg-_4skHWRAJbXHHfoAVJ&sz=w300'"
                                alt="Logo Doremi" 
                                class="w-9 h-9 rounded-lg bg-white p-0.5 object-contain shrink-0"
                            >
                            <div class="min-w-0">
                                <p class="text-[10px] font-bold text-amber-300 uppercase tracking-tight truncate">TUYỂN SINH MẦM NON DOREMI ĐÀ NẴNG</p>
                                <p class="text-[11px] text-emerald-100 truncate">Học Mà Chơi – Chơi Mà Học</p>
                            </div>
                        </div>

                        <div class="my-auto py-1">
                            <h2 class="text-[15px] font-extrabold leading-snug text-white">
                                Môi Trường An Toàn, Yêu Thương – Ươm Mầm Tuổi Thơ Hạnh Phúc
                            </h2>
                            <p class="text-[11.5px] text-emerald-100 mt-1 leading-normal">
                                Lớp Nhà trẻ, Mẫu giáo, Bán trú, Tiền học đường & Kỹ năng STEAM. Đ/c: 118 Hà Duy Phiên, Đà Nẵng.
                            </p>
                        </div>

                        <div class="grid grid-cols-2 gap-2 items-center pt-1">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1YZQ_Bs6tJ7wpRuutngZBsi4j2w5pGLk-" 
                                onerror="this.src='https://drive.google.com/thumbnail?id=1YZQ_Bs6tJ7wpRuutngZBsi4j2w5pGLk-&sz=w600'"
                                alt="Ảnh thực tế Doremi 2" 
                                class="w-full h-20 object-cover rounded-lg border border-white/30"
                            >
                            <div class="flex flex-col justify-center gap-1.5">
                                <div class="text-[11px] font-semibold text-amber-300">
                                    <i class="fa-solid fa-phone mr-1"></i>0919.027.681
                                </div>
                                <a href="#lien-he" class="text-center py-1.5 px-2 rounded-md bg-amber-400 text-slate-900 font-bold text-[11px]">
                                    Đăng Ký Ngay
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng 2 Banner -->
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2 z-10">
                    <button type="button" onclick="showBannerSlide(0)" id="dot0" aria-label="Banner 1" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
                    <button type="button" onclick="showBannerSlide(1)" id="dot1" aria-label="Banner 2" class="w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         THANH DANH MỤC TRANG CHỦ (Tối ưu cho cả Máy tính & Điện thoại)
         - Trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng (hoặc xuống hàng 2 nguyên cụm), tuyệt đối không đứt dòng tên danh mục
         - Trên điện thoại: chia lưới 2 cột đều đẹp, chữ nhỏ gọn
         ========================================== -->
    <section class="w-full py-5 bg-white border-b border-slate-100">
        <div class="flatsome-container">
            <div class="text-center mb-3">
                <h2 class="text-base md:text-lg font-extrabold text-[#084298] uppercase tracking-tight">
                    DANH MỤC CHƯƠNG TRÌNH & HÌNH THỨC GIÁO DỤC
                </h2>
            </div>

            <!-- Danh mục hiển thị trên Máy tính (nằm gọn trên 1 hàng, chữ nhỏ gọn, không xuống dòng từng tên danh mục) -->
            <div class="hidden md:flex items-center justify-center flex-wrap gap-2">
                <button type="button" onclick="filterPrograms('all')" class="cat-filter-btn active-cat cat-nowrap px-3.5 py-2 rounded-lg text-[12.5px] font-bold bg-[#084298] text-white border border-[#084298] transition">
                    Tất Cả Chương Trình
                </button>
                <button type="button" onclick="filterPrograms('mam-non')" class="cat-filter-btn cat-nowrap px-3.5 py-2 rounded-lg text-[12.5px] font-semibold bg-slate-50 text-slate-700 border border-slate-200 hover:border-[#0d6efd] hover:text-[#084298] transition">
                    Khối Nhà Trẻ & Mẫu Giáo
                </button>
                <button type="button" onclick="filterPrograms('ban-tru')" class="cat-filter-btn cat-nowrap px-3.5 py-2 rounded-lg text-[12.5px] font-semibold bg-slate-50 text-slate-700 border border-slate-200 hover:border-[#0d6efd] hover:text-[#084298] transition">
                    Học Bán Trú & Tiền Học Đường
                </button>
                <button type="button" onclick="filterPrograms('ky-nang')" class="cat-filter-btn cat-nowrap px-3.5 py-2 rounded-lg text-[12.5px] font-semibold bg-slate-50 text-slate-700 border border-slate-200 hover:border-[#0d6efd] hover:text-[#084298] transition">
                    Kỹ Năng Sống, Nghệ Thuật & STEAM
                </button>
                <button type="button" onclick="filterPrograms('ho-tro')" class="cat-filter-btn cat-nowrap px-3.5 py-2 rounded-lg text-[12.5px] font-semibold bg-slate-50 text-slate-700 border border-slate-200 hover:border-[#0d6efd] hover:text-[#084298] transition">
                    Đánh Giá, Tư Vấn & Dạy Cá Nhân 1:1
                </button>
                <button type="button" onclick="filterPrograms('ngoai-gio')" class="cat-filter-btn cat-nowrap px-3.5 py-2 rounded-lg text-[12.5px] font-semibold bg-slate-50 text-slate-700 border border-slate-200 hover:border-[#0d6efd] hover:text-[#084298] transition">
                    Can Thiệp Ngoài Giờ & Phát Triển Ngôn Ngữ
                </button>
            </div>

            <!-- Danh mục hiển thị trên Điện thoại (2 cột gọn đẹp, không tràn viền) -->
            <div class="grid grid-cols-2 gap-2 md:hidden">
                <button type="button" onclick="filterPrograms('all')" class="cat-filter-btn-mobile px-2.5 py-2 rounded-lg text-[11.5px] font-bold bg-[#084298] text-white text-center cat-nowrap truncate">
                    Tất Cả Chương Trình
                </button>
                <button type="button" onclick="filterPrograms('mam-non')" class="cat-filter-btn-mobile px-2.5 py-2 rounded-lg text-[11.5px] font-semibold bg-slate-100 text-slate-700 text-center cat-nowrap truncate">
                    Nhà Trẻ & Mẫu Giáo
                </button>
                <button type="button" onclick="filterPrograms('ban-tru')" class="cat-filter-btn-mobile px-2.5 py-2 rounded-lg text-[11.5px] font-semibold bg-slate-100 text-slate-700 text-center cat-nowrap truncate">
                    Bán Trú & Tiền Học Đường
                </button>
                <button type="button" onclick="filterPrograms('ky-nang')" class="cat-filter-btn-mobile px-2.5 py-2 rounded-lg text-[11.5px] font-semibold bg-slate-100 text-slate-700 text-center cat-nowrap truncate">
                    Kỹ Năng & STEAM
                </button>
                <button type="button" onclick="filterPrograms('ho-tro')" class="cat-filter-btn-mobile px-2.5 py-2 rounded-lg text-[11.5px] font-semibold bg-slate-100 text-slate-700 text-center cat-nowrap truncate">
                    Đánh Giá & Cá Nhân 1:1
                </button>
                <button type="button" onclick="filterPrograms('ngoai-gio')" class="cat-filter-btn-mobile px-2.5 py-2 rounded-lg text-[11.5px] font-semibold bg-slate-100 text-slate-700 text-center cat-nowrap truncate">
                    Hỗ Trợ Ngoài Giờ
                </button>
            </div>
        </div>
    </section>

    <!-- ==========================================
         GIỚI THIỆU MẦM NON DOREMI (Theo chuẩn bố cục Edunow.edu.vn)
         ========================================== -->
    <section id="gioi-thieu" class="w-full py-8 md:py-10 bg-white">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center bg-[#eef6ff] rounded-2xl p-5 md:p-8 border border-blue-100">
                <div class="lg:col-span-7 space-y-3">
                    <h2 class="text-lg md:text-2xl font-extrabold text-[#084298] leading-snug">
                        TRƯỜNG MẦM NON DOREMI – ĐỒNG HÀNH CÙNG SỰ PHÁT TRIỂN TOÀN DIỆN CỦA TRẺ
                    </h2>
                    <p class="text-sm text-slate-700 leading-relaxed">
                        <strong>Mầm non Doremi (mamnondoremi.com)</strong> tự hào mang đến chương trình giáo dục hiện đại, chú trọng phát triển hài hòa cả <strong>Trí tuệ – Kỹ năng – Nhân cách</strong> cho trẻ trong những năm tháng đầu đời.
                    </p>
                    <p class="text-sm text-slate-700 leading-relaxed">
                        Với môi trường học tập an toàn, giàu tình yêu thương tại <strong>118 Hà Duy Phiên, Phường Hoà Xuân, Đà Nẵng</strong>, nhà trường áp dụng phương pháp giáo dục tiên tiến <em>“Học mà chơi – Chơi mà học”</em>, giúp mỗi ngày đến trường của bé đều là một ngày vui trọn vẹn.
                    </p>
                    <div class="grid grid-cols-2 sm:grid-cols-3 gap-2.5 pt-2">
                        <div class="bg-white p-3 rounded-xl border border-blue-100">
                            <p class="text-xs font-bold text-[#084298]">Phát Triển Trí Tuệ</p>
                            <p class="text-[11px] text-slate-600 mt-0.5">Khơi dậy tư duy sáng tạo, ngôn ngữ & nhận thức sớm</p>
                        </div>
                        <div class="bg-white p-3 rounded-xl border border-blue-100">
                            <p class="text-xs font-bold text-emerald-700">Rèn Luyện Kỹ Năng</p>
                            <p class="text-[11px] text-slate-600 mt-0.5">Kỹ năng tự lập, giao tiếp, làm việc nhóm & vận động</p>
                        </div>
                        <div class="bg-white p-3 rounded-xl border border-blue-100 col-span-2 sm:col-span-1">
                            <p class="text-xs font-bold text-amber-600">Nuôi Dưỡng Nhân Cách</p>
                            <p class="text-[11px] text-slate-600 mt-0.5">Biết yêu thương, sẻ chia, lễ phép và tự tin</p>
                        </div>
                    </div>
                </div>
                <div class="lg:col-span-5 grid grid-cols-2 gap-3">
                    <img 
                        src="https://lh3.googleusercontent.com/d/1xmyuMvoT1QxS6bL561JMQ-zMS9FJo-Ir" 
                        onerror="this.src='https://drive.google.com/thumbnail?id=1xmyuMvoT1QxS6bL561JMQ-zMS9FJo-Ir&sz=w800'"
                        alt="Cơ sở vật chất Mầm non Doremi" 
                        class="w-full h-44 md:h-52 object-cover rounded-xl shadow-sm border border-white"
                    >
                    <img 
                        src="https://lh3.googleusercontent.com/d/1G5hkL5V3KT7ogKgfljcH74QhhzZ87-1I" 
                        onerror="this.src='https://drive.google.com/thumbnail?id=1G5hkL5V3KT7ogKgfljcH74QhhzZ87-1I&sz=w800'"
                        alt="Cô và trò Mầm non Doremi" 
                        class="w-full h-44 md:h-52 object-cover rounded-xl shadow-sm border border-white"
                    >
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC SẢN PHẨM / CHƯƠNG TRÌNH GIÁO DỤC (Lấy theo mẫu Edunow + Mầm non Doremi)
         - Sử dụng toàn bộ 9 ảnh thực tế từ Google Drive
         - Chia thành 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính
         - Không để các nhãn dán ở trang chủ
         - Tên sản phẩm hiển thị đầy đủ, không bị tràn hoặc thiếu chữ
         ========================================== -->
    <section id="danh-muc-chuong-trinh" class="w-full py-8 bg-slate-50">
        <div class="flatsome-container">
            <div class="text-center mb-6">
                <h2 class="text-lg md:text-2xl font-extrabold text-[#084298] uppercase">
                    CÁC CHƯƠNG TRÌNH GIÁO DỤC & ĐÀO TẠO TẠI MẦM NON DOREMI
                </h2>
                <p class="text-xs md:text-sm text-slate-600 mt-1">
                    Học mà chơi – Chơi mà học | Phát triển toàn diện Trí tuệ, Kỹ năng và Nhân cách cho trẻ
                </p>
            </div>

            <!-- Lưới sản phẩm/chương trình: 2 cột trên điện thoại, 3 cột tablet, 4 cột máy tính -->
            <div id="programGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 md:gap-5">

                <!-- Sản phẩm 1 (Ảnh Drive 1) -->
                <div class="program-card bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between shadow-sm hover:shadow-md transition" data-category="mam-non">
                    <div>
                        <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1vajURjF5zyxb04WPTqMlaSy8HY_WbZFN" 
                                onerror="this.src='https://drive.google.com/thumbnail?id=1vajURjF5zyxb04WPTqMlaSy8HY_WbZFN&sz=w800'"
                                alt="Lớp Nhà Trẻ Mầm Non Doremi (12 – 36 Tháng Tuổi)" 
                                class="w-full h-full object-cover"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <p class="text-[11px] font-semibold text-emerald-700 cat-nowrap truncate">Khối Nhà Trẻ & Mẫu Giáo</p>
                            <h3 class="product-title-full text-xs sm:text-sm md:text-[15px] font-bold text-[#084298] mt-1">
                                Lớp Nhà Trẻ Mầm Non Doremi (12 – 36 Tháng Tuổi)
                            </h3>
                            <p class="text-[11px] md:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Chăm sóc dinh dưỡng tận tâm, rèn nề nếp sinh hoạt, phát triển vận động thô, vận động tinh và ngôn ngữ đầu đời.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1">
                        <a href="#lien-he" class="block w-full text-center py-2 px-2 rounded-lg bg-[#eef6ff] hover:bg-[#0d6efd] text-[#084298] hover:text-white font-semibold text-xs transition">
                            Xem Chi Tiết
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm 2 (Ảnh Drive 2) -->
                <div class="program-card bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between shadow-sm hover:shadow-md transition" data-category="mam-non">
                    <div>
                        <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1U5JFS6zCRm06rQp6BFp_XPffcvJlQIBF" 
                                onerror="this.src='https://drive.google.com/thumbnail?id=1U5JFS6zCRm06rQp6BFp_XPffcvJlQIBF&sz=w800'"
                                alt="Lớp Mẫu Giáo Bé – Nhỡ – Lớn (3 – 5 Tuổi)" 
                                class="w-full h-full object-cover"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <p class="text-[11px] font-semibold text-emerald-700 cat-nowrap truncate">Khối Nhà Trẻ & Mẫu Giáo</p>
                            <h3 class="product-title-full text-xs sm:text-sm md:text-[15px] font-bold text-[#084298] mt-1">
                                Lớp Mẫu Giáo Bé – Nhỡ – Lớn (3 – 5 Tuổi)
                            </h3>
                            <p class="text-[11px] md:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Chương trình học mà chơi – chơi mà học, khám phá thế giới xung quanh, phát triển tư duy, cảm xúc và kỹ năng xã hội.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1">
                        <a href="#lien-he" class="block w-full text-center py-2 px-2 rounded-lg bg-[#eef6ff] hover:bg-[#0d6efd] text-[#084298] hover:text-white font-semibold text-xs transition">
                            Xem Chi Tiết
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm 3 (Ảnh Drive 3) -->
                <div class="program-card bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between shadow-sm hover:shadow-md transition" data-category="ban-tru">
                    <div>
                        <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1YZQ_Bs6tJ7wpRuutngZBsi4j2w5pGLk-" 
                                onerror="this.src='https://drive.google.com/thumbnail?id=1YZQ_Bs6tJ7wpRuutngZBsi4j2w5pGLk-&sz=w800'"
                                alt="Chương Trình Tiền Học Đường – Hành Trang Vào Lớp 1" 
                                class="w-full h-full object-cover"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <p class="text-[11px] font-semibold text-emerald-700 cat-nowrap truncate">Bán Trú & Tiền Học Đường</p>
                            <h3 class="product-title-full text-xs sm:text-sm md:text-[15px] font-bold text-[#084298] mt-1">
                                Chương Trình Tiền Học Đường – Hành Trang Vào Lớp 1
                            </h3>
                            <p class="text-[11px] md:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Rèn luyện sự tập trung, làm quen chữ cái, toán tư duy, tư thế ngồi học đúng và tâm lý tự tin bước vào lớp 1.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1">
                        <a href="#lien-he" class="block w-full text-center py-2 px-2 rounded-lg bg-[#eef6ff] hover:bg-[#0d6efd] text-[#084298] hover:text-white font-semibold text-xs transition">
                            Xem Chi Tiết
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm 4 (Ảnh Drive 4) -->
                <div class="program-card bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between shadow-sm hover:shadow-md transition" data-category="ban-tru">
                    <div>
                        <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1sXL1dJdDXxpIthRkY5pfrWTqbNUj3Iaa" 
                                onerror="this.src='https://drive.google.com/thumbnail?id=1sXL1dJdDXxpIthRkY5pfrWTqbNUj3Iaa&sz=w800'"
                                alt="Học Bán Trú & Chăm Sóc Dinh Dưỡng Toàn Diện" 
                                class="w-full h-full object-cover"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <p class="text-[11px] font-semibold text-emerald-700 cat-nowrap truncate">Bán Trú & Tiền Học Đường</p>
                            <h3 class="product-title-full text-xs sm:text-sm md:text-[15px] font-bold text-[#084298] mt-1">
                                Học Bán Trú & Chăm Sóc Dinh Dưỡng Toàn Diện
                            </h3>
                            <p class="text-[11px] md:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Thực đơn đa dạng, an toàn vệ sinh thực phẩm, phòng ngủ thoáng mát, theo dõi sức khỏe và chiều cao cân nặng định kỳ.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1">
                        <a href="#lien-he" class="block w-full text-center py-2 px-2 rounded-lg bg-[#eef6ff] hover:bg-[#0d6efd] text-[#084298] hover:text-white font-semibold text-xs transition">
                            Xem Chi Tiết
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm 5 (Ảnh Drive 5) -->
                <div class="program-card bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between shadow-sm hover:shadow-md transition" data-category="ky-nang">
                    <div>
                        <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1xmyuMvoT1QxS6bL561JMQ-zMS9FJo-Ir" 
                                onerror="this.src='https://drive.google.com/thumbnail?id=1xmyuMvoT1QxS6bL561JMQ-zMS9FJo-Ir&sz=w800'"
                                alt="Giáo Dục Kỹ Năng Sống & Phát Triển Nhân Cách Trẻ" 
                                class="w-full h-full object-cover"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <p class="text-[11px] font-semibold text-emerald-700 cat-nowrap truncate">Kỹ Năng & STEAM</p>
                            <h3 class="product-title-full text-xs sm:text-sm md:text-[15px] font-bold text-[#084298] mt-1">
                                Giáo Dục Kỹ Năng Sống & Phát Triển Nhân Cách Trẻ
                            </h3>
                            <p class="text-[11px] md:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Hình thành thói quen tự phục vụ, kỹ năng phòng tránh nguy hiểm, lễ phép, biết yêu thương và hợp tác cùng bạn bè.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1">
                        <a href="#lien-he" class="block w-full text-center py-2 px-2 rounded-lg bg-[#eef6ff] hover:bg-[#0d6efd] text-[#084298] hover:text-white font-semibold text-xs transition">
                            Xem Chi Tiết
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm 6 (Ảnh Drive 6) -->
                <div class="program-card bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between shadow-sm hover:shadow-md transition" data-category="ky-nang">
                    <div>
                        <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1G5hkL5V3KT7ogKgfljcH74QhhzZ87-1I" 
                                onerror="this.src='https://drive.google.com/thumbnail?id=1G5hkL5V3KT7ogKgfljcH74QhhzZ87-1I&sz=w800'"
                                alt="Hoạt Động Trải Nghiệm STEAM, Âm Nhạc & Mỹ Thuật Sáng Tạo" 
                                class="w-full h-full object-cover"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <p class="text-[11px] font-semibold text-emerald-700 cat-nowrap truncate">Kỹ Năng & STEAM</p>
                            <h3 class="product-title-full text-xs sm:text-sm md:text-[15px] font-bold text-[#084298] mt-1">
                                Hoạt Động Trải Nghiệm STEAM, Âm Nhạc & Mỹ Thuật Sáng Tạo
                            </h3>
                            <p class="text-[11px] md:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Học qua dự án thực hành, thí nghiệm khoa học vui, cảm thụ âm nhạc, hội họa và thủ công giúp bé phát huy năng khiếu.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1">
                        <a href="#lien-he" class="block w-full text-center py-2 px-2 rounded-lg bg-[#eef6ff] hover:bg-[#0d6efd] text-[#084298] hover:text-white font-semibold text-xs transition">
                            Xem Chi Tiết
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm 7 (Ảnh Drive 7 - Theo danh mục web mẫu Edunow: Dạy Cá Nhân 1:1 / Phát triển ngôn ngữ) -->
                <div class="program-card bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between shadow-sm hover:shadow-md transition" data-category="ho-tro">
                    <div>
                        <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1v_OgUFXCRD4skxn_MuMn4j4Rl7DEphXQ" 
                                onerror="this.src='https://drive.google.com/thumbnail?id=1v_OgUFXCRD4skxn_MuMn4j4Rl7DEphXQ&sz=w800'"
                                alt="Hỗ Trợ Cá Nhân 1:1 & Phát Triển Ngôn Ngữ Giao Tiếp" 
                                class="w-full h-full object-cover"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <p class="text-[11px] font-semibold text-emerald-700 cat-nowrap truncate">Đánh Giá & Dạy Cá Nhân 1:1</p>
                            <h3 class="product-title-full text-xs sm:text-sm md:text-[15px] font-bold text-[#084298] mt-1">
                                Hỗ Trợ Cá Nhân 1:1 & Phát Triển Ngôn Ngữ Giao Tiếp
                            </h3>
                            <p class="text-[11px] md:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Đồng hành sát sao cùng trẻ chậm nói, tăng cường khả năng tương tác, phát âm rõ ràng và tự tin hòa nhập cùng bạn bè.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1">
                        <a href="#lien-he" class="block w-full text-center py-2 px-2 rounded-lg bg-[#eef6ff] hover:bg-[#0d6efd] text-[#084298] hover:text-white font-semibold text-xs transition">
                            Xem Chi Tiết
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm 8 (Ảnh Drive 8 - Theo danh mục web mẫu Edunow: Can thiệp ngoài giờ / Đánh giá & Tư vấn) -->
                <div class="program-card bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between shadow-sm hover:shadow-md transition" data-category="ngoai-gio">
                    <div>
                        <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1K52u1UWpoRzTtMl_39m2cKaZaKhb6geA" 
                                onerror="this.src='https://drive.google.com/thumbnail?id=1K52u1UWpoRzTtMl_39m2cKaZaKhb6geA&sz=w800'"
                                alt="Đánh Giá, Tư Vấn Tâm Lý & Lớp Bổ Trợ Kỹ Năng Ngoài Giờ" 
                                class="w-full h-full object-cover"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <p class="text-[11px] font-semibold text-emerald-700 cat-nowrap truncate">Hỗ Trợ Ngoài Giờ</p>
                            <h3 class="product-title-full text-xs sm:text-sm md:text-[15px] font-bold text-[#084298] mt-1">
                                Đánh Giá, Tư Vấn Tâm Lý & Lớp Bổ Trợ Kỹ Năng Ngoài Giờ
                            </h3>
                            <p class="text-[11px] md:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Khung giờ linh hoạt hỗ trợ phụ huynh bận rộn, tư vấn phương pháp giáo dục sớm và đồng hành nuôi dạy con tại nhà.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1">
                        <a href="#lien-he" class="block w-full text-center py-2 px-2 rounded-lg bg-[#eef6ff] hover:bg-[#0d6efd] text-[#084298] hover:text-white font-semibold text-xs transition">
                            Xem Chi Tiết
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         6 LÝ DO CHỌN MẦM NON DOREMI (Thiết kế giống web mẫu Edunow.edu.vn)
         ========================================== -->
    <section class="w-full py-8 md:py-10 bg-white">
        <div class="flatsome-container">
            <div class="text-center mb-6">
                <h2 class="text-lg md:text-2xl font-extrabold text-[#084298] uppercase">
                    LÝ DO PHỤ HUYNH TIN CHỌN MẦM NON DOREMI
                </h2>
                <p class="text-xs md:text-sm text-slate-600 mt-1">
                    Ngôi nhà thứ hai an toàn, tràn ngập tiếng cười cho bé tại Hòa Xuân, Đà Nẵng
                </p>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
                <div class="p-5 rounded-xl bg-slate-50 border border-slate-200">
                    <div class="w-10 h-10 rounded-lg bg-[#084298] text-white flex items-center justify-center mb-3">
                        <i class="fa-solid fa-graduation-cap"></i>
                    </div>
                    <h3 class="text-sm md:text-base font-bold text-[#084298]">Chương trình giáo dục hiện đại</h3>
                    <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                        Áp dụng phương pháp “Học mà chơi – Chơi mà học”, lấy trẻ làm trung tâm, phát triển cân bằng cả trí tuệ, kỹ năng và nhân cách.
                    </p>
                </div>

                <div class="p-5 rounded-xl bg-slate-50 border border-slate-200">
                    <div class="w-10 h-10 rounded-lg bg-emerald-700 text-white flex items-center justify-center mb-3">
                        <i class="fa-solid fa-heart"></i>
                    </div>
                    <h3 class="text-sm md:text-base font-bold text-[#084298]">Giáo viên tận tâm, yêu trẻ</h3>
                    <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                        Đội ngũ giáo viên có chuyên môn sư phạm mầm non vững vàng, giàu kinh nghiệm, luôn lắng nghe và chăm sóc từng bé bằng sự yêu thương.
                    </p>
                </div>

                <div class="p-5 rounded-xl bg-slate-50 border border-slate-200">
                    <div class="w-10 h-10 rounded-lg bg-amber-500 text-white flex items-center justify-center mb-3">
                        <i class="fa-solid fa-shield-heart"></i>
                    </div>
                    <h3 class="text-sm md:text-base font-bold text-[#084298]">Môi trường an toàn, thân thiện</h3>
                    <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                        Phòng học thoáng mát, tràn ngập ánh sáng tự nhiên; giáo cụ và đồ chơi đạt chuẩn an toàn tuyệt đối cho sức khỏe của trẻ.
                    </p>
                </div>

                <div class="p-5 rounded-xl bg-slate-50 border border-slate-200">
                    <div class="w-10 h-10 rounded-lg bg-[#0d6efd] text-white flex items-center justify-center mb-3">
                        <i class="fa-solid fa-apple-whole"></i>
                    </div>
                    <h3 class="text-sm md:text-base font-bold text-[#084298]">Dinh dưỡng chuẩn khoa học</h3>
                    <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                        Thực đơn thay đổi theo tuần, nguồn thực phẩm tươi sạch có nguồn gốc rõ ràng, giúp bé ăn ngon miệng và phát triển thể chất tối ưu.
                    </p>
                </div>

                <div class="p-5 rounded-xl bg-slate-50 border border-slate-200">
                    <div class="w-10 h-10 rounded-lg bg-emerald-600 text-white flex items-center justify-center mb-3">
                        <i class="fa-solid fa-shapes"></i>
                    </div>
                    <h3 class="text-sm md:text-base font-bold text-[#084298]">Hoạt động trải nghiệm đa dạng</h3>
                    <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                        Thường xuyên tổ chức các tiết học STEAM, âm nhạc, mỹ thuật, vận động thể chất và lễ hội theo chủ đề suốt năm học.
                    </p>
                </div>

                <div class="p-5 rounded-xl bg-slate-50 border border-slate-200">
                    <div class="w-10 h-10 rounded-lg bg-[#084298] text-white flex items-center justify-center mb-3">
                        <i class="fa-solid fa-handshake-angle"></i>
                    </div>
                    <h3 class="text-sm md:text-base font-bold text-[#084298]">Đồng hành cùng cha mẹ</h3>
                    <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                        Cập nhật thường xuyên hình ảnh, video hoạt động và sự tiến bộ của con mỗi ngày để phụ huynh hoàn toàn yên tâm công tác.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         HÌNH ẢNH HOẠT ĐỘNG THỰC TẾ TẠI TRƯỜNG (Đầy đủ 9 ảnh thực tế Google Drive)
         ========================================== -->
    <section id="hoat-dong" class="w-full py-8 bg-slate-50">
        <div class="flatsome-container">
            <div class="text-center mb-6">
                <h2 class="text-lg md:text-2xl font-extrabold text-[#084298] uppercase">
                    HÌNH ẢNH THỰC TẾ HOẠT ĐỘNG TẠI MẦM NON DOREMI
                </h2>
                <p class="text-xs md:text-sm text-slate-600 mt-1">
                    Không gian lớp học, góc vui chơi và những khoảnh khắc đáng yêu của cô trò Mầm non Doremi
                </p>
            </div>

            <!-- Chia 2 cột trên điện thoại, 3 cột trên máy tính -->
            <div class="grid grid-cols-2 md:grid-cols-3 gap-3 md:gap-4">
                <div class="bg-white p-2 rounded-xl border border-slate-200">
                    <img src="https://lh3.googleusercontent.com/d/1vajURjF5zyxb04WPTqMlaSy8HY_WbZFN" onerror="this.src='https://drive.google.com/thumbnail?id=1vajURjF5zyxb04WPTqMlaSy8HY_WbZFN&sz=w800'" alt="Hoạt động thực tế 1" class="w-full h-36 sm:h-48 md:h-56 object-cover rounded-lg">
                    <p class="text-xs font-semibold text-slate-700 mt-2 text-center">Giờ học khám phá & tương tác nhóm</p>
                </div>
                <div class="bg-white p-2 rounded-xl border border-slate-200">
                    <img src="https://lh3.googleusercontent.com/d/1U5JFS6zCRm06rQp6BFp_XPffcvJlQIBF" onerror="this.src='https://drive.google.com/thumbnail?id=1U5JFS6zCRm06rQp6BFp_XPffcvJlQIBF&sz=w800'" alt="Hoạt động thực tế 2" class="w-full h-36 sm:h-48 md:h-56 object-cover rounded-lg">
                    <p class="text-xs font-semibold text-slate-700 mt-2 text-center">Rèn luyện tư duy & sự khéo léo</p>
                </div>
                <div class="bg-white p-2 rounded-xl border border-slate-200">
                    <img src="https://lh3.googleusercontent.com/d/1YZQ_Bs6tJ7wpRuutngZBsi4j2w5pGLk-" onerror="this.src='https://drive.google.com/thumbnail?id=1YZQ_Bs6tJ7wpRuutngZBsi4j2w5pGLk-&sz=w800'" alt="Hoạt động thực tế 3" class="w-full h-36 sm:h-48 md:h-56 object-cover rounded-lg">
                    <p class="text-xs font-semibold text-slate-700 mt-2 text-center">Học mà chơi – Chơi mà học mỗi ngày</p>
                </div>
                <div class="bg-white p-2 rounded-xl border border-slate-200">
                    <img src="https://lh3.googleusercontent.com/d/1sXL1dJdDXxpIthRkY5pfrWTqbNUj3Iaa" onerror="this.src='https://drive.google.com/thumbnail?id=1sXL1dJdDXxpIthRkY5pfrWTqbNUj3Iaa&sz=w800'" alt="Hoạt động thực tế 4" class="w-full h-36 sm:h-48 md:h-56 object-cover rounded-lg">
                    <p class="text-xs font-semibold text-slate-700 mt-2 text-center">Môi trường lớp học an toàn, ấm áp</p>
                </div>
                <div class="bg-white p-2 rounded-xl border border-slate-200">
                    <img src="https://lh3.googleusercontent.com/d/1xmyuMvoT1QxS6bL561JMQ-zMS9FJo-Ir" onerror="this.src='https://drive.google.com/thumbnail?id=1xmyuMvoT1QxS6bL561JMQ-zMS9FJo-Ir&sz=w800'" alt="Hoạt động thực tế 5" class="w-full h-36 sm:h-48 md:h-56 object-cover rounded-lg">
                    <p class="text-xs font-semibold text-slate-700 mt-2 text-center">Hoạt động phát triển kỹ năng & vận động</p>
                </div>
                <div class="bg-white p-2 rounded-xl border border-slate-200">
                    <img src="https://lh3.googleusercontent.com/d/1G5hkL5V3KT7ogKgfljcH74QhhzZ87-1I" onerror="this.src='https://drive.google.com/thumbnail?id=1G5hkL5V3KT7ogKgfljcH74QhhzZ87-1I&sz=w800'" alt="Hoạt động thực tế 6" class="w-full h-36 sm:h-48 md:h-56 object-cover rounded-lg">
                    <p class="text-xs font-semibold text-slate-700 mt-2 text-center">Trải nghiệm nghệ thuật & sáng tạo</p>
                </div>
                <div class="bg-white p-2 rounded-xl border border-slate-200">
                    <img src="https://lh3.googleusercontent.com/d/1v_OgUFXCRD4skxn_MuMn4j4Rl7DEphXQ" onerror="this.src='https://drive.google.com/thumbnail?id=1v_OgUFXCRD4skxn_MuMn4j4Rl7DEphXQ&sz=w800'" alt="Hoạt động thực tế 7" class="w-full h-36 sm:h-48 md:h-56 object-cover rounded-lg">
                    <p class="text-xs font-semibold text-slate-700 mt-2 text-center">Cô giáo ân cần hướng dẫn từng bé</p>
                </div>
                <div class="bg-white p-2 rounded-xl border border-slate-200">
                    <img src="https://lh3.googleusercontent.com/d/1K52u1UWpoRzTtMl_39m2cKaZaKhb6geA" onerror="this.src='https://drive.google.com/thumbnail?id=1K52u1UWpoRzTtMl_39m2cKaZaKhb6geA&sz=w800'" alt="Hoạt động thực tế 8" class="w-full h-36 sm:h-48 md:h-56 object-cover rounded-lg">
                    <p class="text-xs font-semibold text-slate-700 mt-2 text-center">Niềm vui đến trường của các bé Doremi</p>
                </div>
                <div class="bg-white p-2 rounded-xl border border-slate-200 col-span-2 md:col-span-1">
                    <img src="https://lh3.googleusercontent.com/d/1mK_sWqYuYAKgnpt7z3XOMbNilo4CqATX" onerror="this.src='https://drive.google.com/thumbnail?id=1mK_sWqYuYAKgnpt7z3XOMbNilo4CqATX&sz=w800'" alt="Hoạt động thực tế 9" class="w-full h-40 sm:h-48 md:h-56 object-cover rounded-lg">
                    <p class="text-xs font-semibold text-slate-700 mt-2 text-center">Gắn kết yêu thương dưới mái trường Doremi</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KIẾN THỨC MẦM NON)
         ========================================== -->
    <section id="bai-viet" class="w-full py-8 md:py-10 bg-white">
        <div class="flatsome-container">
            <div class="text-center mb-6">
                <h2 class="text-lg md:text-2xl font-extrabold text-[#084298] uppercase">
                    TIN TỨC SỰ KIỆN & CẨM NANG NUÔI DẠY TRẺ
                </h2>
                <p class="text-xs md:text-sm text-slate-600 mt-1">
                    Chia sẻ kiến thức giáo dục sớm, dinh dưỡng và phương pháp đồng hành cùng con tại nhà
                </p>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-5">
                <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between">
                    <div>
                        <img src="https://lh3.googleusercontent.com/d/1mK_sWqYuYAKgnpt7z3XOMbNilo4CqATX" onerror="this.src='https://drive.google.com/thumbnail?id=1mK_sWqYuYAKgnpt7z3XOMbNilo4CqATX&sz=w600'" alt="Phương pháp Học mà chơi" class="w-full aspect-[16/10] object-cover">
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-[#084298]">
                                Lợi ích của phương pháp “Học mà chơi – Chơi mà học” đối với sự phát triển trí tuệ của trẻ
                            </h3>
                            <p class="text-[11px] text-slate-600 mt-1.5 leading-relaxed">
                                Thông qua các trò chơi có định hướng, trẻ tiếp thu kiến thức tự nhiên, phát triển ngôn ngữ và tư duy sáng tạo vượt trội.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4">
                        <a href="#lien-he" class="text-xs font-semibold text-[#0d6efd] hover:underline">Xem thêm →</a>
                    </div>
                </article>

                <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between">
                    <div>
                        <img src="https://lh3.googleusercontent.com/d/1v_OgUFXCRD4skxn_MuMn4j4Rl7DEphXQ" onerror="this.src='https://drive.google.com/thumbnail?id=1v_OgUFXCRD4skxn_MuMn4j4Rl7DEphXQ&sz=w600'" alt="Bí quyết giúp bé tự tin ngày đầu đến lớp" class="w-full aspect-[16/10] object-cover">
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-[#084298]">
                                Cẩm nang giúp bé làm quen trường lớp mầm non nhanh chóng, vui vẻ không quấy khóc
                            </h3>
                            <p class="text-[11px] text-slate-600 mt-1.5 leading-relaxed">
                                Những bước chuẩn bị tâm lý và thói quen sinh hoạt tại nhà giúp con hào hứng mỗi sáng đến trường cùng cô và bạn.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4">
                        <a href="#lien-he" class="text-xs font-semibold text-[#0d6efd] hover:underline">Xem thêm →</a>
                    </div>
                </article>

                <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between">
                    <div>
                        <img src="https://lh3.googleusercontent.com/d/1K52u1UWpoRzTtMl_39m2cKaZaKhb6geA" onerror="this.src='https://drive.google.com/thumbnail?id=1K52u1UWpoRzTtMl_39m2cKaZaKhb6geA&sz=w600'" alt="Rèn luyện vận động tinh và vận động thô" class="w-full aspect-[16/10] object-cover">
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-[#084298]">
                                Vận động thô và vận động tinh là gì? Hướng dẫn ba mẹ tập cho con tại nhà hiệu quả
                            </h3>
                            <p class="text-[11px] text-slate-600 mt-1.5 leading-relaxed">
                                Các bài tập vận động phù hợp theo từng độ tuổi giúp trẻ linh hoạt, khỏe mạnh và kích thích sự phát triển não bộ.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4">
                        <a href="#lien-he" class="text-xs font-semibold text-[#0d6efd] hover:underline">Xem thêm →</a>
                    </div>
                </article>

                <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between">
                    <div>
                        <img src="https://lh3.googleusercontent.com/d/1G5hkL5V3KT7ogKgfljcH74QhhzZ87-1I" onerror="this.src='https://drive.google.com/thumbnail?id=1G5hkL5V3KT7ogKgfljcH74QhhzZ87-1I&sz=w600'" alt="Phát triển ngôn ngữ và kỹ năng giao tiếp" class="w-full aspect-[16/10] object-cover">
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-[#084298]">
                                Phương pháp kích thích ngôn ngữ và rèn kỹ năng tự lập cho trẻ từ 1 đến 5 tuổi
                            </h3>
                            <p class="text-[11px] text-slate-600 mt-1.5 leading-relaxed">
                                Bí quyết trò chuyện, đọc sách cùng con và xây dựng môi trường giàu ngôn ngữ giúp trẻ tự tin thể hiện bản thân.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4">
                        <a href="#lien-he" class="text-xs font-semibold text-[#0d6efd] hover:underline">Xem thêm →</a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC ĐỐI TÁC (Đối tác liên kết chuyên môn, dinh dưỡng & giáo dục)
         ========================================== -->
    <section id="doi-tac" class="w-full py-8 bg-slate-50 border-t border-slate-200">
        <div class="flatsome-container">
            <div class="text-center mb-5">
                <h2 class="text-lg md:text-xl font-extrabold text-[#084298] uppercase">
                    ĐỐI TÁC ĐỒNG HÀNH & LIÊN KẾT GIÁO DỤC
                </h2>
                <p class="text-xs text-slate-600 mt-1">
                    Hợp tác cùng các đơn vị giáo dục, đào tạo kỹ năng và cung ứng thực phẩm an toàn đạt chuẩn
                </p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-book-open-reader text-xl text-[#084298] mb-1.5"></i>
                    <p class="text-xs font-bold text-slate-800">STEAM Kids VN</p>
                    <p class="text-[10px] text-slate-500">Đối tác Giáo dục STEAM</p>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-earth-americas text-xl text-emerald-600 mb-1.5"></i>
                    <p class="text-xs font-bold text-slate-800">Smart English</p>
                    <p class="text-[10px] text-slate-500">Tiếng Anh Mầm Non</p>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-seedling text-xl text-green-600 mb-1.5"></i>
                    <p class="text-xs font-bold text-slate-800">GreenFood Đà Nẵng</p>
                    <p class="text-[10px] text-slate-500">Thực Phẩm Sạch Chuẩn VietGAP</p>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-music text-xl text-amber-500 mb-1.5"></i>
                    <p class="text-xs font-bold text-slate-800">Art & Music Kids</p>
                    <p class="text-[10px] text-slate-500">Năng Khiếu & Cảm Thụ</p>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-user-doctor text-xl text-blue-600 mb-1.5"></i>
                    <p class="text-xs font-bold text-slate-800">Chuyên Gia Tâm Lý</p>
                    <p class="text-[10px] text-slate-500">Đánh Giá & Giáo Dục Sớm</p>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-Child-reaching text-xl text-rose-500 mb-1.5"></i>
                    <p class="text-xs font-bold text-slate-800">Kỹ Năng Sống Poki</p>
                    <p class="text-[10px] text-slate-500">Rèn Kỹ Năng Mầm Non</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         KHU VỰC LIÊN HỆ, FANPAGE FACEBOOK & GOOGLE MAP NGOÀI TRANG CHỦ
         - Đưa Fanpage ra ngoài trang chủ
         - Đưa ảnh/bản đồ Google Map địa chỉ 118 Hà Duy Phiên, Phường Hoà Xuân, Đà Nẵng ra ngoài trang chủ
         ========================================== -->
    <section id="lien-he" class="w-full py-8 md:py-10 bg-white border-t border-slate-200">
        <div class="flatsome-container">
            <div class="text-center mb-6">
                <h2 class="text-lg md:text-2xl font-extrabold text-[#084298] uppercase">
                    LIÊN HỆ TƯ VẤN, KẾT NỐI FANPAGE & BẢN ĐỒ CHỈ ĐƯỜNG
                </h2>
                <p class="text-xs md:text-sm text-slate-600 mt-1">
                    Địa chỉ: 118 Hà Duy Phiên, Phường Hoà Xuân, Đà Nẵng | Hotline/Zalo: 0919.027.681
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5">
                <!-- Cột 1: Form Đăng ký tư vấn tuyển sinh -->
                <div class="lg:col-span-4 bg-slate-50 p-5 rounded-2xl border border-slate-200">
                    <h3 class="text-base font-extrabold text-[#084298] mb-2">ĐĂNG KÝ TƯ VẤN & THAM QUAN TRƯỜNG</h3>
                    <p class="text-xs text-slate-600 mb-4">
                        Quý Phụ huynh để lại thông tin, Mầm non Doremi sẽ liên hệ tư vấn chi tiết chương trình học phù hợp với độ tuổi của bé.
                    </p>
                    <form id="consultForm" onsubmit="submitConsultForm(event)" class="space-y-3">
                        <div>
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Họ tên Phụ huynh & Tên của bé *</label>
                            <input type="text" required placeholder="Nhập họ tên phụ huynh / tên bé" class="w-full px-3 py-2 text-xs rounded-lg border border-slate-300 focus:outline-none focus:border-[#0d6efd] bg-white">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo Phụ huynh *</label>
                            <input type="tel" required placeholder="Ví dụ: 0919027681" class="w-full px-3 py-2 text-xs rounded-lg border border-slate-300 focus:outline-none focus:border-[#0d6efd] bg-white">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Chương trình quan tâm</label>
                            <select class="w-full px-3 py-2 text-xs rounded-lg border border-slate-300 focus:outline-none focus:border-[#0d6efd] bg-white">
                                <option>Lớp Nhà Trẻ (12 – 36 tháng)</option>
                                <option>Lớp Mẫu Giáo (3 – 5 tuổi)</option>
                                <option>Chương Trình Tiền Học Đường</option>
                                <option>Học Bán Trú & Kỹ Năng STEAM</option>
                                <option>Đánh Giá, Tư Vấn & Hỗ Trợ Cá Nhân 1:1</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Ghi chú thêm</label>
                            <textarea rows="2" placeholder="Độ tuổi của bé hoặc câu hỏi cần tư vấn..." class="w-full px-3 py-2 text-xs rounded-lg border border-slate-300 focus:outline-none focus:border-[#0d6efd] bg-white"></textarea>
                        </div>
                        <button type="submit" class="w-full py-2.5 px-4 rounded-lg bg-[#084298] hover:bg-[#0d6efd] text-white font-bold text-xs transition">
                            GỬI THÔNG TIN ĐĂNG KÝ
                        </button>
                        <div id="formSuccessMsg" class="hidden p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs font-medium">
                            Cảm ơn Quý Phụ huynh! Mầm non Doremi đã ghi nhận thông tin và sẽ liên hệ qua SĐT/Zalo 0919.027.681 sớm nhất.
                        </div>
                    </form>
                </div>

                <!-- Cột 2: Fanpage Facebook Mầm non Doremi ngay ngoài trang chủ -->
                <div class="lg:col-span-4 bg-slate-50 p-5 rounded-2xl border border-slate-200 flex flex-col justify-between">
                    <div>
                        <h3 class="text-base font-extrabold text-[#084298] mb-2 flex items-center gap-2">
                            <i class="fa-brands fa-facebook text-[#1877f2]"></i> FANPAGE MẦM NON DOREMI
                        </h3>
                        <p class="text-xs text-slate-600 mb-3">
                            Theo dõi Fanpage chính thức để cập nhật hình ảnh hoạt động, thực đơn và sự kiện hàng ngày của các bé.
                        </p>

                        <!-- Khung thẻ Fanpage trực quan kèm Iframe Plugin -->
                        <div class="bg-white rounded-xl border border-slate-200 p-3 mb-3">
                            <div class="flex items-center gap-3">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1oEWr9xKObkPIg-_4skHWRAJbXHHfoAVJ" 
                                    onerror="this.src='https://drive.google.com/thumbnail?id=1oEWr9xKObkPIg-_4skHWRAJbXHHfoAVJ&sz=w300'"
                                    alt="Logo Mầm Non Doremi" 
                                    class="w-12 h-12 rounded-lg object-contain border border-slate-200 p-0.5 shrink-0"
                                >
                                <div class="min-w-0">
                                    <a href="https://www.facebook.com/profile.php?id=61572564510050" target="_blank" rel="noopener noreferrer" class="text-sm font-bold text-[#084298] hover:underline block truncate">
                                        Mầm Non Doremi - Đà Nẵng
                                    </a>
                                    <p class="text-[11px] text-slate-500">Trường Mầm Non • Hòa Xuân, Đà Nẵng</p>
                                    <a href="https://www.facebook.com/profile.php?id=61572564510050" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1 mt-1 px-2.5 py-1 rounded bg-[#1877f2] text-white text-[11px] font-semibold">
                                        <i class="fa-brands fa-facebook-f"></i> Theo dõi Fanpage
                                    </a>
                                </div>
                            </div>
                        </div>

                        <div class="w-full overflow-hidden rounded-xl border border-slate-200 bg-white">
                            <iframe 
                                title="Fanpage Mầm non Doremi"
                                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D61572564510050&tabs=timeline&width=340&height=220&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                                class="w-full h-[220px] border-0" 
                                scrolling="no" 
                                frameborder="0" 
                                allowfullscreen="true" 
                                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                            </iframe>
                        </div>
                    </div>

                    <div class="pt-3">
                        <a href="https://www.facebook.com/profile.php?id=61572564510050" target="_blank" rel="noopener noreferrer" class="block w-full text-center py-2.5 px-3 rounded-lg bg-[#1877f2] hover:bg-blue-700 text-white font-bold text-xs transition">
                            MỞ TRANG FANPAGE FACEBOOK
                        </a>
                    </div>
                </div>

                <!-- Cột 3: Bản đồ Google Map ngoài trang chủ (118 Hà Duy Phiên, Phường Hoà Xuân, Đà Nẵng) -->
                <div class="lg:col-span-4 bg-slate-50 p-5 rounded-2xl border border-slate-200 flex flex-col justify-between">
                    <div>
                        <h3 class="text-base font-extrabold text-[#084298] mb-2 flex items-center gap-2">
                            <i class="fa-solid fa-map-location-dot text-rose-600"></i> BẢN ĐỒ GOOGLE MAPS
                        </h3>
                        <p class="text-xs text-slate-600 mb-3">
                            <strong>Địa chỉ:</strong> 118 Hà Duy Phiên, Phường Hoà Xuân, Đà Nẵng
                        </p>
                        <div class="w-full h-[290px] rounded-xl overflow-hidden border border-slate-200 bg-white">
                            <iframe 
                                title="Google Map Mầm non Doremi 118 Hà Duy Phiên Hòa Xuân Đà Nẵng"
                                src="https://maps.google.com/maps?q=118%20H%C3%A0%20Duy%20Phi%C3%AAn,%20H%C3%B2a%20Xu%C3%A2n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
                                class="w-full h-full border-0" 
                                allowfullscreen="" 
                                loading="lazy" 
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>
                    <div class="pt-3">
                        <a href="https://www.google.com/maps/search/?api=1&query=118+Hà+Duy+Phiên,+Phường+Hoà+Xuân,+Đà+Nẵng" target="_blank" rel="noopener noreferrer" class="block w-full text-center py-2.5 px-3 rounded-lg bg-emerald-700 hover:bg-emerald-800 text-white font-bold text-xs transition">
                            XEM CHỈ ĐƯỜNG TRÊN GOOGLE MAPS
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FOOTER (Chân trang chuẩn Flatsome)
         ========================================== -->
    <footer class="w-full bg-[#084298] text-white pt-8 pb-6">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-12 gap-6 pb-6 border-b border-white/15">
                <div class="md:col-span-5 space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1oEWr9xKObkPIg-_4skHWRAJbXHHfoAVJ" 
                            onerror="this.src='https://drive.google.com/thumbnail?id=1oEWr9xKObkPIg-_4skHWRAJbXHHfoAVJ&sz=w300'"
                            alt="Logo Mầm Non Doremi" 
                            class="h-10 w-auto bg-white p-0.5 rounded-lg object-contain"
                        >
                        <div>
                            <p class="text-base font-extrabold tracking-tight">TRƯỜNG MẦM NON DOREMI</p>
                            <p class="text-xs text-amber-300">Website: mamnondoremi.com</p>
                        </div>
                    </div>
                    <p class="text-xs text-blue-100 leading-relaxed">
                        Chương trình giáo dục hiện đại, chú trọng phát triển trí tuệ, kỹ năng và nhân cách cho trẻ. Môi trường an toàn, yêu thương, giúp trẻ phát triển toàn diện thông qua học mà chơi – chơi mà học.
                    </p>
                </div>

                <div class="md:col-span-4 space-y-2 text-xs">
                    <h4 class="text-sm font-bold text-amber-300 uppercase">THÔNG TIN LIÊN HỆ</h4>
                    <p><i class="fa-solid fa-location-dot w-5 text-amber-300"></i>Địa chỉ: 118 Hà Duy Phiên, Phường Hoà Xuân, Đà Nẵng</p>
                    <p><i class="fa-solid fa-phone w-5 text-amber-300"></i>Hotline / Zalo: <a href="tel:0919027681" class="font-bold hover:underline">0919.027.681</a></p>
                    <p><i class="fa-solid fa-globe w-5 text-amber-300"></i>Website: <a href="https://mamnondoremi.com" class="hover:underline">mamnondoremi.com</a></p>
                    <p><i class="fa-brands fa-facebook w-5 text-amber-300"></i>Fanpage: <a href="https://www.facebook.com/profile.php?id=61572564510050" target="_blank" rel="noopener noreferrer" class="hover:underline">Mầm Non Doremi</a></p>
                </div>

                <div class="md:col-span-3 space-y-2 text-xs">
                    <h4 class="text-sm font-bold text-amber-300 uppercase">LIÊN KẾT NHANH</h4>
                    <ul class="space-y-1.5 text-blue-100">
                        <li><a href="#trang-chu" class="hover:text-white">Trang chủ</a></li>
                        <li><a href="#gioi-thieu" class="hover:text-white">Giới thiệu nhà trường</a></li>
                        <li><a href="#danh-muc-chuong-trinh" class="hover:text-white">Chương trình giáo dục</a></li>
                        <li><a href="#hoat-dong" class="hover:text-white">Hình ảnh hoạt động thực tế</a></li>
                        <li><a href="#doi-tac" class="hover:text-white">Đối tác liên kết</a></li>
                        <li><a href="#lien-he" class="hover:text-white">Đăng ký tư vấn & Bản đồ</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-4 text-center text-xs text-blue-200">
                © 2026 Bản quyền thuộc về <strong>Mầm Non Doremi (mamnondoremi.com)</strong> – Địa chỉ: 118 Hà Duy Phiên, Phường Hoà Xuân, Đà Nẵng.
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         - Tương thích hoàn toàn trên máy tính và điện thoại
         - Nằm gọn trong khung nhìn, không gây tràn viền
         ========================================== -->
    <div class="fixed bottom-4 right-3 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a 
            href="https://www.facebook.com/profile.php?id=61572564510050" 
            target="_blank" 
            rel="noopener noreferrer"
            aria-label="Facebook Mầm Non Doremi"
            class="flex items-center gap-2 px-3 py-2 rounded-full bg-[#1877f2] text-white shadow-lg hover:scale-105 transition"
        >
            <i class="fa-brands fa-facebook-messenger text-base"></i>
            <span class="text-xs font-bold">Facebook</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a 
            href="https://zalo.me/0919027681" 
            target="_blank" 
            rel="noopener noreferrer"
            aria-label="Zalo 0919.027.681"
            class="flex items-center gap-2 px-3 py-2 rounded-full bg-[#0068ff] text-white shadow-lg hover:scale-105 transition"
        >
            <span class="w-4 h-4 rounded-full bg-white text-[#0068ff] font-extrabold text-[10px] flex items-center justify-center">Z</span>
            <span class="text-xs font-bold">Zalo</span>
        </a>

        <!-- Nút Gọi Hotline -->
        <a 
            href="tel:0919027681" 
            aria-label="Gọi 0919.027.681"
            class="flex items-center gap-2 px-3.5 py-2.5 rounded-full bg-rose-600 text-white shadow-lg hover:scale-105 transition"
        >
            <i class="fa-solid fa-phone-volume text-sm"></i>
            <span class="text-xs font-extrabold">0919.027.681</span>
        </a>
    </div>

    <!-- ==========================================
         JAVASCRIPT ĐIỀU KHIỂN BANNER TỰ TRƯỢT, LỌC DANH MỤC & MENU
         ========================================== -->
    <script>
        // Menu điện thoại
        const mobileMenuBtn = document.getElementById('mobileMenuBtn');
        const mobileMenuPanel = document.getElementById('mobileMenuPanel');
        if (mobileMenuBtn && mobileMenuPanel) {
            mobileMenuBtn.addEventListener('click', function () {
                mobileMenuPanel.classList.toggle('hidden');
            });
            document.querySelectorAll('.mobile-nav-link').forEach(function (link) {
                link.addEventListener('click', function () {
                    mobileMenuPanel.classList.add('hidden');
                });
            });
        }

        // 2 Banner tự trượt chuyên nghiệp kích thước bằng nhau
        let currentBannerIndex = 0;
        const slides = document.querySelectorAll('.banner-slide');
        const dot0 = document.getElementById('dot0');
        const dot1 = document.getElementById('dot1');

        function showBannerSlide(index) {
            currentBannerIndex = index;
            slides.forEach(function (slide, idx) {
                if (idx === index) {
                    slide.classList.remove('hidden');
                } else {
                    slide.classList.add('hidden');
                }
            });
            if (dot0 && dot1) {
                if (index === 0) {
                    dot0.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
                    dot1.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
                } else {
                    dot0.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
                    dot1.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
                }
            }
        }

        setInterval(function () {
            const nextSlide = (currentBannerIndex + 1) % slides.length;
            showBannerSlide(nextSlide);
        }, 5000);

        // Lọc danh mục chương trình giáo dục trên trang chủ
        function filterPrograms(category) {
            const cards = document.querySelectorAll('.program-card');
            cards.forEach(function (card) {
                if (category === 'all' || card.getAttribute('data-category') === category) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });

            // Cuộn nhẹ tới khu vực sản phẩm khi bấm lọc
            const section = document.getElementById('danh-muc-chuong-trinh');
            if (section && category !== 'all') {
                section.scrollIntoView({ behavior: 'smooth', block: 'start' });
            }
        }

        // Xử lý gửi form tư vấn
        function submitConsultForm(e) {
            e.preventDefault();
            const msg = document.getElementById('formSuccessMsg');
            if (msg) {
                msg.classList.remove('hidden');
            }
            e.target.reset();
        }
    </script>
</body>
</html>
