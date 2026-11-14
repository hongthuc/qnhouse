<html lang="vi" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>QN HOUSE - Nhà Thầu Thiết Kế & Thi Công Trọn Gói | Kiến Trúc - Xây Dựng - Nội Thất</title>
    <meta name="description" content="Nhà thầu xây dựng QN HOUSE (qnhouse.com) - Chuyên Thiết Kế & Thi Công Trọn Gói, Kiến Trúc - Xây Dựng - Nội Thất tại Đà Nẵng và Quảng Ngãi. Hotline: 0904.106.468.">
    <meta name="keywords" content="QN HOUSE, qnhouse.com, nhà thầu xây dựng Đà Nẵng, thiết kế thi công trọn gói, xây nhà trọn gói Đà Nẵng, xây dựng Quảng Ngãi, thiết kế nội thất">
    <meta name="author" content="CÔNG TY TNHH ĐẦU TƯ XÂY DỰNG QN HOUSE">

    <!-- Open Graph / Thumbnail là ảnh Logo khi gửi link trang web -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="qnhouse.com - Nhà Thầu Xây Dựng QN HOUSE">
    <meta property="og:url" content="https://qnhouse.com/">
    <meta property="og:title" content="Nhà Thầu Xây Dựng QN HOUSE - Thiết Kế & Thi Công Trọn Gói Kiến Trúc - Xây Dựng - Nội Thất">
    <meta property="og:description" content="Chuyên Thiết Kế & Thi Công Trọn Gói Khách sạn, Căn hộ, Biệt thự, Nhà phố, Văn phòng tại Đà Nẵng & Quảng Ngãi. Hotline: 0904.106.468">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=19TR4aCX55hs8zwz36DkY9aE2GrHZz6r_&sz=w1200">
    <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/19TR4aCX55hs8zwz36DkY9aE2GrHZz6r_=w1200">
    <meta property="og:image:alt" content="Logo Nhà Thầu Xây Dựng QN HOUSE">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Nhà Thầu Xây Dựng QN HOUSE - qnhouse.com">
    <meta name="twitter:description" content="Nhà Thầu Thiết Kế & Thi Công Trọn Gói, Kiến Trúc - Xây Dựng - Nội Thất. Hotline: 0904.106.468">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=19TR4aCX55hs8zwz36DkY9aE2GrHZz6r_&sz=w1200">
    <link rel="image_src" href="https://drive.google.com/thumbnail?id=19TR4aCX55hs8zwz36DkY9aE2GrHZz6r_&sz=w1200">
    <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=19TR4aCX55hs8zwz36DkY9aE2GrHZz6r_&sz=w200">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Montserrat:wght@600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome 6 -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        qn: {
                            navy: '#0f2942',      /* Màu xanh đậm chủ đạo theo logo xây dựng */
                            blue: '#163d61',      /* Màu xanh kiến trúc phụ */
                            gold: '#d49a2a',      /* Màu vàng đồng/cam vàng điểm nhấn theo logo */
                            goldlight: '#eab308',
                            dark: '#111827',
                            graybg: '#f5f7fa'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        heading: ['Montserrat', 'sans-serif']
                    }
                }
            }
        }
    </script>

    <style>
        /* Khóa tràn viền ngang & đảm bảo không lệch phải trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100%;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            color: #1f2937;
            background-color: #ffffff;
            -webkit-text-size-adjust: 100%;
        }

        /* Chiều ngang giao diện trên máy tính bằng đúng 95% kích thước màn hình máy tính */
        .fs-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .fs-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Menu danh mục trên máy tính: viết liền trên 1 hàng, chữ nhỏ gọn, tuyệt đối không xuống dòng trong tên danh mục */
        .fs-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: flex-end;
            gap: 2px;
        }
        @media (min-width: 1280px) {
            .fs-nav-list {
                flex-wrap: nowrap;
                gap: 4px;
            }
        }
        .fs-nav-item {
            position: relative;
            white-space: nowrap;
        }
        .fs-nav-link {
            display: inline-flex;
            align-items: center;
            gap: 3px;
            white-space: nowrap !important;
            font-size: 11.5px;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 0.01em;
            padding: 7px 7px;
            color: #0f2942;
            border-radius: 4px;
            transition: all 0.2s ease;
        }
        @media (min-width: 1366px) {
            .fs-nav-link {
                font-size: 12.5px;
                padding: 8px 9px;
            }
        }
        .fs-nav-link:hover, .fs-nav-link.active {
            color: #d49a2a;
            background-color: rgba(212, 154, 42, 0.08);
        }

        /* Dropdown menu chuẩn Flatsome */
        .fs-dropdown {
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 220px;
            background: #ffffff;
            border-top: 3px solid #d49a2a;
            box-shadow: 0 10px 25px rgba(15, 41, 66, 0.15);
            border-radius: 0 0 6px 6px;
            padding: 6px 0;
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
            z-index: 100;
        }
        .fs-nav-item:hover .fs-dropdown {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }
        .fs-dropdown a {
            display: block;
            padding: 8px 14px;
            font-size: 12.5px;
            font-weight: 600;
            color: #1f2937;
            white-space: nowrap;
            border-bottom: 1px solid #f3f4f6;
            transition: all 0.15s ease;
        }
        .fs-dropdown a:last-child {
            border-bottom: none;
        }
        .fs-dropdown a:hover {
            background-color: #f8fafc;
            color: #d49a2a;
            padding-left: 18px;
        }

        /* Chữ danh mục (Filter tabs) ở trang chủ nhỏ gọn, viết liền không gãy dòng tên danh mục */
        .fs-cat-bar {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            gap: 6px;
        }
        .fs-cat-btn {
            white-space: nowrap !important;
            font-size: 11.5px;
            font-weight: 600;
            padding: 5px 11px;
            border-radius: 4px;
            border: 1px solid #d1d5db;
            background-color: #ffffff;
            color: #0f2942;
            transition: all 0.2s ease;
            cursor: pointer;
        }
        @media (min-width: 768px) {
            .fs-cat-btn {
                font-size: 12px;
                padding: 6px 13px;
            }
        }
        .fs-cat-btn:hover, .fs-cat-btn.active {
            background-color: #0f2942;
            border-color: #0f2942;
            color: #ffffff;
        }

        /* Tiêu đề Section chuẩn Flatsome (Section Title Divider) */
        .fs-section-title-wrap {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
            margin-bottom: 8px;
        }
        .fs-section-line {
            flex: 1;
            max-width: 90px;
            height: 2px;
            background-color: #d49a2a;
        }

        /* Card sản phẩm / công trình chuẩn Flatsome: Tên sản phẩm đầy đủ không cắt chữ, không tràn viền */
        .fs-box {
            display: flex;
            flex-direction: column;
            height: 100%;
            background: #ffffff;
            border: 1px solid #e5e7eb;
            border-radius: 6px;
            overflow: hidden;
            transition: transform 0.25s ease, box-shadow 0.25s ease;
        }
        .fs-box:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(15, 41, 66, 0.1);
            border-color: #d49a2a;
        }
        .fs-box-image {
            position: relative;
            width: 100%;
            aspect-ratio: 4 / 3;
            overflow: hidden;
            background-color: #f3f4f6;
        }
        .fs-box-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.45s ease;
        }
        .fs-box:hover .fs-box-image img {
            transform: scale(1.05);
        }
        .fs-box-text {
            padding: 10px 10px 12px;
            display: flex;
            flex-direction: column;
            flex: 1;
            justify-content: space-between;
            text-align: center;
        }
        @media (min-width: 640px) {
            .fs-box-text {
                padding: 12px 14px 14px;
            }
        }
        .fs-product-title {
            font-size: 12.5px;
            line-height: 1.4;
            font-weight: 700;
            color: #0f2942;
            word-break: break-word;
            overflow-wrap: break-word;
            white-space: normal;
            margin-bottom: 6px;
        }
        @media (min-width: 640px) {
            .fs-product-title {
                font-size: 14px;
            }
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
        @keyframes pulseRing {
            0% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.55); }
            70% { box-shadow: 0 0 0 12px rgba(220, 38, 38, 0); }
            100% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0); }
        }
        .floating-pulse {
            animation: pulseRing 2s infinite;
        }
    </style>
</head>
<body class="bg-white text-gray-800 antialiased selection:bg-qn-gold selection:text-white">

    <!-- ==========================================
         TOPBAR CHUẨN FLATSOME (ĐƠN GIẢN, KHÔNG CÓ THANH UX BUILDER)
    =========================================== -->
    <div class="bg-qn-navy text-white text-xs py-1.5 border-b border-white/10">
        <div class="fs-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex flex-wrap items-center gap-3 sm:gap-5">
                <a href="tel:0904106468" class="inline-flex items-center gap-1.5 hover:text-qn-gold transition font-medium">
                    <i class="fa-solid fa-phone-volume text-qn-gold"></i>
                    <span>0904.106.468</span>
                </a>
                <span class="hidden sm:inline text-white/30">|</span>
                <span class="hidden md:inline-flex items-center gap-1.5 text-gray-200">
                    <i class="fa-solid fa-location-dot text-qn-gold"></i>
                    <span>605 Hoà Tiến - Hoà Vang - Đà Nẵng</span>
                </span>
                <span class="hidden lg:inline text-white/30">|</span>
                <span class="hidden lg:inline-flex items-center gap-1.5 text-gray-200">
                    <i class="fa-solid fa-building text-qn-gold"></i>
                    <span>CN: Nguyễn Huệ - Tư Nghĩa - Quảng Ngãi, Đà Nẵng</span>
                </span>
            </div>
            <div class="flex items-center gap-3 ml-auto">
                <a href="https://qnhouse.com" class="hover:text-qn-gold transition font-semibold">qnhouse.com</a>
                <span class="text-white/30">|</span>
                <a href="https://www.facebook.com/angkhoa.111853" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1 hover:text-qn-gold transition">
                    <i class="fa-brands fa-facebook"></i>
                    <span>Facebook QN HOUSE</span>
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER CHÍNH (LOGO GỌN NHỎ, DANH MỤC 1 HÀNG CHỮ NHỎ, KHÔNG ĐỂ NÚT GỌI NGAY)
    =========================================== -->
    <header id="header" class="sticky top-0 z-40 bg-white shadow-sm border-b border-gray-200">
        <div class="fs-container py-2">
            <div class="flex items-center justify-between gap-2">
                <!-- Logo chỉnh gọn nhỏ lại -->
                <a href="#top" class="flex items-center gap-2.5 shrink-0 group">
                    <div class="w-10 h-10 sm:w-11 sm:h-11 rounded border border-gray-200 bg-white p-0.5 flex items-center justify-center overflow-hidden shrink-0 shadow-xs">
                        <img src="https://lh3.googleusercontent.com/d/19TR4aCX55hs8zwz36DkY9aE2GrHZz6r_=w400"
                             data-drive-id="19TR4aCX55hs8zwz36DkY9aE2GrHZz6r_"
                             onerror="handleDriveImgError(this, '19TR4aCX55hs8zwz36DkY9aE2GrHZz6r_', 'QN+HOUSE')"
                             alt="Logo Nhà Thầu Xây Dựng QN HOUSE"
                             class="w-full h-full object-contain">
                    </div>
                    <div class="leading-tight">
                        <span class="block font-heading font-extrabold text-sm sm:text-base md:text-lg text-qn-navy tracking-tight group-hover:text-qn-gold transition">
                            QN HOUSE
                        </span>
                        <span class="block text-[10px] sm:text-[11px] font-semibold text-gray-500">
                            KIẾN TRÚC - XÂY DỰNG - NỘI THẤT
                        </span>
                    </div>
                </a>

                <!-- Menu Danh Mục Trên Máy Tính: Chữ nhỏ gọn nằm trên cùng 1 hàng (hoặc xuống hàng 2 nguyên cụm, không bao giờ gãy dòng tên danh mục) -->
                <nav class="hidden lg:block flex-1 pl-2" aria-label="Menu chính">
                    <ul class="fs-nav-list">
                        <li class="fs-nav-item">
                            <a href="#top" class="fs-nav-link active">Trang chủ</a>
                        </li>
                        <li class="fs-nav-item">
                            <a href="#gioi-thieu" class="fs-nav-link">Giới thiệu</a>
                        </li>
                        <li class="fs-nav-item">
                            <a href="#cong-trinh-thuc-te" class="fs-nav-link">
                                Công trình thực tế <i class="fa-solid fa-chevron-down text-[9px] opacity-75"></i>
                            </a>
                            <div class="fs-dropdown">
                                <a href="#cong-trinh-thuc-te" onclick="filterProjects('khach-san-can-ho')">Khách sạn – Căn hộ – Phòng trọ</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterProjects('biet-thu')">Biệt thự</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterProjects('nha-pho')">Nhà phố</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterProjects('van-phong')">Văn phòng</a>
                            </div>
                        </li>
                        <li class="fs-nav-item">
                            <a href="#du-an-da-nang" class="fs-nav-link">
                                Dự án Đà Nẵng <i class="fa-solid fa-chevron-down text-[9px] opacity-75"></i>
                            </a>
                            <div class="fs-dropdown">
                                <a href="#du-an-da-nang" onclick="filterDaNang('all')">Tất cả dự án tại Đà Nẵng</a>
                                <a href="#du-an-da-nang" onclick="filterDaNang('hoa-vang')">Khu vực Hòa Tiến – Hòa Vang</a>
                                <a href="#du-an-da-nang" onclick="filterDaNang('cam-le')">Khu vực Hòa Xuân – Cẩm Lệ</a>
                                <a href="#du-an-da-nang" onclick="filterDaNang('hai-chau')">Khu vực Hải Châu – Sơn Trà</a>
                                <a href="#du-an-da-nang" onclick="filterDaNang('lien-chieu')">Khu vực Liên Chiểu – Ngũ Hành Sơn</a>
                            </div>
                        </li>
                        <li class="fs-nav-item">
                            <a href="#linh-vuc-hoat-dong" class="fs-nav-link">
                                Lĩnh vực hoạt động <i class="fa-solid fa-chevron-down text-[9px] opacity-75"></i>
                            </a>
                            <div class="fs-dropdown">
                                <a href="#linh-vuc-hoat-dong">Thiết kế Kiến trúc – Nội thất</a>
                                <a href="#linh-vuc-hoat-dong">Thi công phần thô</a>
                                <a href="#linh-vuc-hoat-dong">Thi công hoàn thiện</a>
                                <a href="#linh-vuc-hoat-dong">Thi công nội thất</a>
                            </div>
                        </li>
                        <li class="fs-nav-item">
                            <a href="#mau-thiet-ke" class="fs-nav-link">
                                Mẫu thiết kế <i class="fa-solid fa-chevron-down text-[9px] opacity-75"></i>
                            </a>
                            <div class="fs-dropdown">
                                <a href="#mau-thiet-ke" onclick="filterDesigns('nha-pho')">Mẫu thiết kế nhà phố</a>
                                <a href="#mau-thiet-ke" onclick="filterDesigns('biet-thu')">Mẫu thiết kế biệt thự</a>
                                <a href="#mau-thiet-ke" onclick="filterDesigns('noi-that')">Mẫu thiết kế nội thất</a>
                            </div>
                        </li>
                        <li class="fs-nav-item">
                            <a href="#bao-gia" class="fs-nav-link">
                                Báo giá <i class="fa-solid fa-chevron-down text-[9px] opacity-75"></i>
                            </a>
                            <div class="fs-dropdown">
                                <a href="#bao-gia">Báo giá thiết kế kiến trúc</a>
                                <a href="#bao-gia">Báo giá thi công phần thô</a>
                                <a href="#bao-gia">Báo giá thi công hoàn thiện</a>
                                <a href="#bao-gia">Báo giá thi công trọn gói</a>
                            </div>
                        </li>
                        <li class="fs-nav-item">
                            <a href="#doi-tac" class="fs-nav-link">Đối tác</a>
                        </li>
                        <li class="fs-nav-item">
                            <a href="#tin-tuc" class="fs-nav-link">Tin tức</a>
                        </li>
                        <li class="fs-nav-item">
                            <a href="#lien-he" class="fs-nav-link">Liên hệ</a>
                        </li>
                    </ul>
                </nav>

                <!-- Nút mở Menu trên Điện Thoại (Không để nút gọi ngay trên Header để tránh tràn viền) -->
                <button type="button" onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center gap-1.5 px-3 py-2 rounded border border-gray-300 text-qn-navy hover:bg-gray-100 text-xs font-bold shrink-0">
                    <i class="fa-solid fa-bars text-sm"></i>
                    <span>DANH MỤC</span>
                </button>
            </div>

            <!-- Thanh danh mục nhanh trên điện thoại: gọn đẹp, cuộn mượt không tràn viền -->
            <div class="lg:hidden mt-2 pt-2 border-t border-gray-100 flex items-center gap-1.5 overflow-x-auto no-scrollbar pb-1">
                <a href="#cong-trinh-thuc-te" class=" whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-gray-100 text-qn-navy hover:bg-qn-navy hover:text-white transition">Công trình thực tế</a>
                <a href="#du-an-da-nang" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-gray-100 text-qn-navy hover:bg-qn-navy hover:text-white transition">Dự án Đà Nẵng</a>
                <a href="#linh-vuc-hoat-dong" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-gray-100 text-qn-navy hover:bg-qn-navy hover:text-white transition">Lĩnh vực hoạt động</a>
                <a href="#mau-thiet-ke" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-gray-100 text-qn-navy hover:bg-qn-navy hover:text-white transition">Mẫu thiết kế</a>
                <a href="#bao-gia" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-gray-100 text-qn-navy hover:bg-qn-navy hover:text-white transition">Báo giá</a>
                <a href="#yeu-cau-bao-gia" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-qn-gold text-white">Tư vấn & Báo giá</a>
            </div>
        </div>

        <!-- Menu Drawer trên Điện Thoại -->
        <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-t border-gray-200 shadow-xl">
            <div class="fs-container py-3 divide-y divide-gray-100 text-xs font-bold text-qn-navy">
                <a href="#top" onclick="toggleMobileMenu()" class="block py-2.5 hover:text-qn-gold">TRANG CHỦ</a>
                <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="block py-2.5 hover:text-qn-gold">GIỚI THIỆU QN HOUSE</a>
                <div class="py-2.5">
                    <a href="#cong-trinh-thuc-te" onclick="toggleMobileMenu()" class="block hover:text-qn-gold mb-1.5">CÔNG TRÌNH THỰC TẾ</a>
                    <div class="grid grid-cols-2 gap-1.5 pl-2 font-medium text-gray-600">
                        <a href="#cong-trinh-thuc-te" onclick="filterProjects('khach-san-can-ho'); toggleMobileMenu()" class="py-1 hover:text-qn-gold">• Khách sạn – Căn hộ</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterProjects('biet-thu'); toggleMobileMenu()" class="py-1 hover:text-qn-gold">• Biệt thự</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterProjects('nha-pho'); toggleMobileMenu()" class="py-1 hover:text-qn-gold">• Nhà phố</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterProjects('van-phong'); toggleMobileMenu()" class="py-1 hover:text-qn-gold">• Văn phòng</a>
                    </div>
                </div>
                <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="block py-2.5 hover:text-qn-gold">DỰ ÁN TẠI ĐÀ NẴNG</a>
                <div class="py-2.5">
                    <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu()" class="block hover:text-qn-gold mb-1.5">LĨNH VỰC HOẠT ĐỘNG</a>
                    <div class="grid grid-cols-2 gap-1.5 pl-2 font-medium text-gray-600">
                        <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu()" class="py-1 hover:text-qn-gold">• Thiết kế Kiến trúc</a>
                        <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu()" class="py-1 hover:text-qn-gold">• Thi công phần thô</a>
                        <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu()" class="py-1 hover:text-qn-gold">• Thi công hoàn thiện</a>
                        <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu()" class="py-1 hover:text-qn-gold">• Thi công nội thất</a>
                    </div>
                </div>
                <div class="py-2.5">
                    <a href="#mau-thiet-ke" onclick="toggleMobileMenu()" class="block hover:text-qn-gold mb-1.5">MẪU THIẾT KẾ</a>
                    <div class="grid grid-cols-2 gap-1.5 pl-2 font-medium text-gray-600">
                        <a href="#mau-thiet-ke" onclick="filterDesigns('nha-pho'); toggleMobileMenu()" class="py-1 hover:text-qn-gold">• Mẫu nhà phố</a>
                        <a href="#mau-thiet-ke" onclick="filterDesigns('biet-thu'); toggleMobileMenu()" class="py-1 hover:text-qn-gold">• Mẫu biệt thự</a>
                        <a href="#mau-thiet-ke" onclick="filterDesigns('noi-that'); toggleMobileMenu()" class="py-1 hover:text-qn-gold">• Mẫu nội thất</a>
                    </div>
                </div>
                <a href="#bao-gia" onclick="toggleMobileMenu()" class="block py-2.5 hover:text-qn-gold">BÁO GIÁ XÂY DỰNG TRỌN GÓI</a>
                <a href="#doi-tac" onclick="toggleMobileMenu()" class="block py-2.5 hover:text-qn-gold">ĐỐI TÁC CHIẾN LƯỢC</a>
                <a href="#tin-tuc" onclick="toggleMobileMenu()" class="block py-2.5 hover:text-qn-gold">TIN TỨC & KINH NGHIỆM</a>
                <a href="#lien-he" onclick="toggleMobileMenu()" class="block py-2.5 hover:text-qn-gold">LIÊN HỆ & BẢN ĐỒ</a>
            </div>
        </div>
    </header>

    <!-- ==========================================
         SLIDER 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP
         - Kích thước 2 banner bằng nhau tuyệt đối
         - Hình ảnh & chữ nằm trọn trong banner
         - Chữ cách xa viền ảnh banner, không bị thiếu chữ trên cả điện thoại và máy tính
    =========================================== -->
    <section id="top" class="py-3 bg-gray-50">
        <div class="fs-container">
            <div class="relative w-full h-[260px] sm:h-[340px] md:h-[420px] lg:h-[480px] rounded-lg overflow-hidden shadow-md bg-qn-navy">

                <!-- SLIDE 1 -->
                <div class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10" data-slide="0">
                    <img src="https://lh3.googleusercontent.com/d/1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk=w1600"
                         onerror="handleDriveImgError(this, '1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk', 'QN+HOUSE+BANNER+1')"
                         alt="Banner 1 - Nhà thầu xây dựng QN HOUSE"
                         class="w-full h-full object-cover object-center">
                    <!-- Lớp phủ tối giúp chữ nổi bật 100% -->
                    <div class="absolute inset-0 bg-gradient-to-r from-qn-navy/90 via-qn-navy/75 to-qn-navy/60"></div>

                    <!-- Vùng chữ cách xa viền banner (padding rộng rãi cả 4 phía) -->
                    <div class="absolute inset-0 flex items-center justify-center px-10 sm:px-16 md:px-24 lg:px-32 py-8 sm:py-12">
                        <div class="w-full max-w-3xl text-center text-white">
                            <p class="text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-widest text-qn-gold mb-1.5 sm:mb-2">
                                CÔNG TY TNHH ĐẦU TƯ XÂY DỰNG QN HOUSE
                            </p>
                            <h1 class="font-heading font-extrabold text-base sm:text-2xl md:text-3xl lg:text-4xl leading-snug mb-2 sm:mb-3 text-white">
                                NHÀ THẦU THIẾT KẾ & THI CÔNG TRỌN GÓI
                            </h1>
                            <p class="text-xs sm:text-sm md:text-base font-semibold text-gray-100 mb-2 sm:mb-4">
                                KIẾN TRÚC – XÂY DỰNG – NỘI THẤT TẠI ĐÀ NẴNG & QUẢNG NGÃI
                            </p>
                            <p class="hidden sm:block text-xs md:text-sm text-gray-200 max-w-2xl mx-auto mb-4">
                                “Nhà ở Gia đình – Tiêu chuẩn Công trình” | An Toàn – Chất Lượng – Tiến Độ – Tối Ưu Chi Phí
                            </p>
                            <div class="flex flex-wrap items-center justify-center gap-2 sm:gap-3">
                                <a href="#yeu-cau-bao-gia" class="px-3.5 py-1.5 sm:px-5 sm:py-2.5 rounded bg-qn-gold hover:bg-amber-600 text-white font-bold text-xs sm:text-sm transition shadow">
                                    Nhận Báo Giá Trọn Gói
                                </a>
                                <a href="#cong-trinh-thuc-te" class="px-3.5 py-1.5 sm:px-5 sm:py-2.5 rounded bg-white/15 hover:bg-white/25 border border-white/40 text-white font-bold text-xs sm:text-sm transition">
                                    Xem Công Trình Thực Tế
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- SLIDE 2 (Kích thước bằng hệt Slide 1) -->
                <div class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0 pointer-events-none" data-slide="1">
                    <img src="https://lh3.googleusercontent.com/d/1PjtEF4hlMU_42b438GmEQhYZTba75kRJ=w1600"
                         onerror="handleDriveImgError(this, '1PjtEF4hlMU_42b438GmEQhYZTba75kRJ', 'QN+HOUSE+BANNER+2')"
                         alt="Banner 2 - Kiến Trúc Xây Dựng Nội Thất QN HOUSE"
                         class="w-full h-full object-cover object-center">
                    <div class="absolute inset-0 bg-gradient-to-r from-qn-navy/90 via-qn-navy/75 to-qn-navy/60"></div>

                    <!-- Vùng chữ cách xa viền banner -->
                    <div class="absolute inset-0 flex items-center justify-center px-10 sm:px-16 md:px-24 lg:px-32 py-8 sm:py-12">
                        <div class="w-full max-w-3xl text-center text-white">
                            <p class="text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-widest text-qn-gold mb-1.5 sm:mb-2">
                                UY TÍN – TẬN TÂM – CHUYÊN NGHIỆP
                            </p>
                            <h2 class="font-heading font-extrabold text-base sm:text-2xl md:text-3xl lg:text-4xl leading-snug mb-2 sm:mb-3 text-white">
                                KIẾN TẠO KHÔNG GIAN SỐNG ĐẲNG CẤP & BỀN VỮNG
                            </h2>
                            <p class="text-xs sm:text-sm md:text-base font-semibold text-gray-100 mb-2 sm:mb-4">
                                Biệt Thự – Nhà Phố – Khách Sạn – Căn Hộ Cho Thuê – Văn Phòng
                            </p>
                            <p class="hidden sm:block text-xs md:text-sm text-gray-200 max-w-2xl mx-auto mb-4">
                                Trụ sở: 605 Hoà Tiến - Hoà Vang - Đà Nẵng | Chi nhánh: Nguyễn Huệ - Tư Nghĩa - Quảng Ngãi, Đà Nẵng
                            </p>
                            <div class="flex flex-wrap items-center justify-center gap-2 sm:gap-3">
                                <a href="tel:0904106468" class="px-3.5 py-1.5 sm:px-5 sm:py-2.5 rounded bg-qn-gold hover:bg-amber-600 text-white font-bold text-xs sm:text-sm transition shadow">
                                    Hotline: 0904.106.468
                                </a>
                                <a href="#du-an-da-nang" class="px-3.5 py-1.5 sm:px-5 sm:py-2.5 rounded bg-white/15 hover:bg-white/25 border border-white/40 text-white font-bold text-xs sm:text-sm transition">
                                    Dự Án Tại Đà Nẵng
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Slider -->
                <button type="button" onclick="changeBannerSlide(-1)" aria-label="Slide trước" class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/40 hover:bg-qn-gold text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                </button>
                <button type="button" onclick="changeBannerSlide(1)" aria-label="Slide tiếp" class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/40 hover:bg-qn-gold text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                </button>

                <!-- Chấm chỉ báo Slide -->
                <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" onclick="goToBannerSlide(0)" class="banner-dot w-6 h-2 rounded-full bg-qn-gold transition-all" aria-label="Banner 1"></button>
                    <button type="button" onclick="goToBannerSlide(1)" class="banner-dot w-2.5 h-2 rounded-full bg-white/60 transition-all" aria-label="Banner 2"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DỊCH VỤ TIÊU BIỂU (3 KHỐI GIỐNG WEB MẪU TINTRUONGTHINH.COM: THIẾT KẾ - THI CÔNG - NỘI THẤT)
    =========================================== -->
    <section class="py-8 sm:py-10 bg-white">
        <div class="fs-container">
            <div class="text-center mb-6">
                <div class="fs-section-title-wrap">
                    <span class="fs-section-line"></span>
                    <h2 class="font-heading font-extrabold text-lg sm:text-xl md:text-2xl text-qn-navy uppercase">
                        DỊCH VỤ TIÊU BIỂU
                    </h2>
                    <span class="fs-section-line"></span>
                </div>
                <p class="text-xs sm:text-sm text-gray-600">Giải pháp toàn diện từ Tư vấn thiết kế Kiến trúc đến Thi công Xây dựng & Hoàn thiện Nội thất</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-4 sm:gap-6">
                <!-- Khối 1: THIẾT KẾ -->
                <div class="fs-box">
                    <div class="fs-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA=w800"
                             onerror="handleDriveImgError(this, '1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA', 'THIET+KE')"
                             alt="Dịch vụ Thiết kế Kiến trúc QN HOUSE">
                    </div>
                    <div class="fs-box-text">
                        <div>
                            <h3 class="font-heading font-bold text-base sm:text-lg text-qn-navy uppercase mb-1.5">THIẾT KẾ</h3>
                            <p class="text-xs sm:text-sm text-gray-600 leading-relaxed mb-3">
                                Thiết kế kiến trúc & kết cấu Nhà phố, Biệt thự, Khách sạn, Căn hộ cho thuê, Văn phòng tối ưu công năng, thẩm mỹ và chuẩn phong thủy.
                            </p>
                        </div>
                        <a href="#mau-thiet-ke" class="inline-block text-xs font-bold text-qn-gold hover:text-qn-navy uppercase tracking-wide">
                            Xem chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                        </a>
                    </div>
                </div>

                <!-- Khối 2: THI CÔNG -->
                <div class="fs-box">
                    <div class="fs-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1ng7_50Be4LsQqNa28KBn8rSCicz40ir9=w800"
                             onerror="handleDriveImgError(this, '1ng7_50Be4LsQqNa28KBn8rSCicz40ir9', 'THI+CONG')"
                             alt="Dịch vụ Thi công Xây dựng QN HOUSE">
                    </div>
                    <div class="fs-box-text">
                        <div>
                            <h3 class="font-heading font-bold text-base sm:text-lg text-qn-navy uppercase mb-1.5">THI CÔNG</h3>
                            <p class="text-xs sm:text-sm text-gray-600 leading-relaxed mb-3">
                                Thi công phần thô, thi công hoàn thiện và xây nhà trọn gói chìa khóa trao tay đúng tiến độ, vật tư chính hãng, giám sát kỹ thuật 24/7.
                            </p>
                        </div>
                        <a href="#cong-trinh-thuc-te" class="inline-block text-xs font-bold text-qn-gold hover:text-qn-navy uppercase tracking-wide">
                            Xem chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                        </a>
                    </div>
                </div>

                <!-- Khối 3: NỘI THẤT -->
                <div class="fs-box">
                    <div class="fs-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS=w800"
                             onerror="handleDriveImgError(this, '1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS', 'NOI+THAT')"
                             alt="Dịch vụ Thiết kế & Thi công Nội thất QN HOUSE">
                    </div>
                    <div class="fs-box-text">
                        <div>
                            <h3 class="font-heading font-bold text-base sm:text-lg text-qn-navy uppercase mb-1.5">NỘI THẤT</h3>
                            <p class="text-xs sm:text-sm text-gray-600 leading-relaxed mb-3">
                                Thiết kế & sản xuất thi công nội thất trọn gói phòng khách, bếp, phòng ngủ, căn hộ, văn phòng với độ hoàn thiện sắc nét, sang trọng.
                            </p>
                        </div>
                        <a href="#mau-thiet-ke" onclick="filterDesigns('noi-that')" class="inline-block text-xs font-bold text-qn-gold hover:text-qn-navy uppercase tracking-wide">
                            Xem chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         GIỚI THIỆU CÔNG TY & 6 THẾ MẠNH CỦA CHÚNG TÔI (GIỐNG WEB MẪU TINTRUONGTHINH.COM)
    =========================================== -->
    <section id="gioi-thieu" class="py-10 bg-qn-graybg border-y border-gray-200">
        <div class="fs-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center mb-10">
                <div class="lg:col-span-7">
                    <p class="text-xs font-bold uppercase tracking-widest text-qn-gold mb-1">VỀ CHÚNG TÔI – QNHOUSE.COM</p>
                    <h2 class="font-heading font-extrabold text-xl sm:text-2xl md:text-3xl text-qn-navy mb-3">
                        NHÀ THẦU XÂY DỰNG QN HOUSE
                    </h2>
                    <p class="text-xs sm:text-sm font-bold text-qn-blue mb-3">
                        Nhà Thầu Thiết Kế & Thi Công Trọn Gói: Kiến Trúc – Xây Dựng – Nội Thất
                    </p>
                    <p class="text-xs sm:text-sm text-gray-700 leading-relaxed mb-3">
                        <strong>QN HOUSE</strong> chuyên Thiết kế – Xây dựng – Nội thất các công trình Khách sạn, Biệt thự, Căn hộ, Văn phòng, Nhà phố tại khu vực <strong>Đà Nẵng – Quảng Ngãi</strong> và miền Trung. Với tiêu chí <em>“Nhà ở Gia đình – Tiêu chuẩn Công trình”</em>, chúng tôi luôn mang đến sự trải nghiệm chuyên nghiệp và an tâm tuyệt đối dành cho Quý Khách hàng.
                    </p>
                    <p class="text-xs sm:text-sm text-gray-700 leading-relaxed mb-4">
                        Đặt cái <strong>“TÂM”</strong> trong nghề lên hàng đầu để mỗi công trình luôn đạt kết quả <strong>“AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – SỰ HÀI LÒNG CỦA KHÁCH HÀNG”</strong>. Đội ngũ kiến trúc sư và kỹ sư giàu kinh nghiệm thực chiến của QN HOUSE luôn là nơi được khách hàng gửi gắm niềm tin.
                    </p>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 text-xs bg-white p-3.5 rounded-lg border border-gray-200">
                        <div class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-qn-gold mt-0.5"></i>
                            <div>
                                <strong class="text-qn-navy block">Trụ sở chính Đà Nẵng:</strong>
                                <span class="text-gray-600">605 Hoà Tiến - Hoà Vang - Đà Nẵng</span>
                            </div>
                        </div>
                        <div class="flex items-start gap-2">
                            <i class="fa-solid fa-building text-qn-gold mt-0.5"></i>
                            <div>
                                <strong class="text-qn-navy block">Chi nhánh:</strong>
                                <span class="text-gray-600">Nguyễn Huệ - Tư Nghĩa - Quảng Ngãi, Đà Nẵng</span>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="lg:col-span-5">
                    <div class="rounded-lg overflow-hidden shadow-md border-2 border-white bg-white">
                        <img src="https://lh3.googleusercontent.com/d/1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF=w1000"
                             onerror="handleDriveImgError(this, '1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF', 'QN+HOUSE+CONG+TRINH')"
                             alt="Công trình thực tế Nhà thầu xây dựng QN HOUSE"
                             class="w-full h-64 sm:h-72 object-cover">
                    </div>
                </div>
            </div>

            <!-- 6 Thế mạnh chuẩn bố cục Tin Trường Thịnh -->
            <div class="text-center mb-6">
                <div class="fs-section-title-wrap">
                    <span class="fs-section-line"></span>
                    <h3 class="font-heading font-extrabold text-base sm:text-xl text-qn-navy uppercase">
                        THẾ MẠNH CỦA CHÚNG TÔI
                    </h3>
                    <span class="fs-section-line"></span>
                </div>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">
                <div class="bg-white p-3.5 sm:p-5 rounded-lg border border-gray-200 hover:border-qn-gold transition">
                    <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-qn-navy text-qn-gold flex items-center justify-center mb-2.5 text-sm sm:text-base">
                        <i class="fa-solid fa-user-tie"></i>
                    </div>
                    <h4 class="font-bold text-xs sm:text-sm text-qn-navy mb-1">Đội ngũ kiến trúc sư, kỹ sư chuyên nghiệp</h4>
                    <p class="text-[11px] sm:text-xs text-gray-600 leading-relaxed">
                        Kiến trúc sư trẻ trung, sáng tạo cùng đội ngũ kỹ sư giàu kinh nghiệm và thợ lành nghề lâu năm.
                    </p>
                </div>

                <div class="bg-white p-3.5 sm:p-5 rounded-lg border border-gray-200 hover:border-qn-gold transition">
                    <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-qn-navy text-qn-gold flex items-center justify-center mb-2.5 text-sm sm:text-base">
                        <i class="fa-solid fa-compass-drafting"></i>
                    </div>
                    <h4 class="font-bold text-xs sm:text-sm text-qn-navy mb-1">Cập nhật xu hướng mới nhất hiện đại</h4>
                    <p class="text-[11px] sm:text-xs text-gray-600 leading-relaxed">
                        Không ngừng cải tiến, mang đến xu thế thiết kế mới, vật liệu bền vững và giải pháp thi công hiện đại.
                    </p>
                </div>

                <div class="bg-white p-3.5 sm:p-5 rounded-lg border border-gray-200 hover:border-qn-gold transition">
                    <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-qn-navy text-qn-gold flex items-center justify-center mb-2.5 text-sm sm:text-base">
                        <i class="fa-solid fa-calendar-check"></i>
                    </div>
                    <h4 class="font-bold text-xs sm:text-sm text-qn-navy mb-1">Giám sát tiến độ chuẩn xác</h4>
                    <p class="text-[11px] sm:text-xs text-gray-600 leading-relaxed">
                        Hoàn thành đúng tiến độ cam kết, thường xuyên báo cáo hình ảnh thi công thực tế để khách hàng theo dõi.
                    </p>
                </div>

                <div class="bg-white p-3.5 sm:p-5 rounded-lg border border-gray-200 hover:border-qn-gold transition">
                    <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-qn-navy text-qn-gold flex items-center justify-center mb-2.5 text-sm sm:text-base">
                        <i class="fa-solid fa-shield-halved"></i>
                    </div>
                    <h4 class="font-bold text-xs sm:text-sm text-qn-navy mb-1">Bảo hành công trình lâu dài</h4>
                    <p class="text-[11px] sm:text-xs text-gray-600 leading-relaxed">
                        “Gọi đâu có đó” là tiêu chí làm việc của QN HOUSE, giúp khách hàng hoàn toàn yên tâm về chế độ hậu mãi.
                    </p>
                </div>

                <div class="bg-white p-3.5 sm:p-5 rounded-lg border border-gray-200 hover:border-qn-gold transition">
                    <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-qn-navy text-qn-gold flex items-center justify-center mb-2.5 text-sm sm:text-base">
                        <i class="fa-solid fa-hand-holding-dollar"></i>
                    </div>
                    <h4 class="font-bold text-xs sm:text-sm text-qn-navy mb-1">Giá cả hợp lý phải chăng</h4>
                    <p class="text-[11px] sm:text-xs text-gray-600 leading-relaxed">
                        Báo giá minh bạch từng hạng mục, cân đối tối ưu ngân sách và cam kết không phát sinh chi phí ngoài hợp đồng.
                    </p>
                </div>

                <div class="bg-white p-3.5 sm:p-5 rounded-lg border border-gray-200 hover:border-qn-gold transition">
                    <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-qn-navy text-qn-gold flex items-center justify-center mb-2.5 text-sm sm:text-base">
                        <i class="fa-solid fa-headset"></i>
                    </div>
                    <h4 class="font-bold text-xs sm:text-sm text-qn-navy mb-1">Hỗ trợ tư vấn miễn phí 24/7</h4>
                    <p class="text-[11px] sm:text-xs text-gray-600 leading-relaxed">
                        Đội ngũ QN HOUSE luôn sẵn sàng tư vấn khảo sát thực tế và lên phương án sơ bộ miễn phí 24/7.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         CÔNG TRÌNH THỰC TẾ (15 ẢNH THỰC TẾ GOOGLE DRIVE, CHIA 2 CỘT TRÊN ĐIỆN THOẠI, TÊN ĐẦY ĐỦ, KHÔNG DÙNG NHÃN DÁN)
    =========================================== -->
    <section id="cong-trinh-thuc-te" class="py-10 bg-white">
        <div class="fs-container">
            <div class="text-center mb-5">
                <div class="fs-section-title-wrap">
                    <span class="fs-section-line"></span>
                    <h2 class="font-heading font-extrabold text-lg sm:text-xl md:text-2xl text-qn-navy uppercase">
                        CÔNG TRÌNH THỰC TẾ
                    </h2>
                    <span class="fs-section-line"></span>
                </div>
                <p class="text-xs sm:text-sm text-gray-600 mb-4">
                    Hình ảnh thực tế các công trình do đội ngũ QN HOUSE trực tiếp thiết kế & thi công trọn gói
                </p>

                <!-- Danh mục lọc chữ nhỏ gọn, viết liền không xuống dòng tên danh mục -->
                <div class="fs-cat-bar" id="projectFilterBar">
                    <button type="button" onclick="filterProjects('all')" data-cat="all" class="fs-cat-btn active">Tất cả</button>
                    <button type="button" onclick="filterProjects('khach-san-can-ho')" data-cat="khach-san-can-ho" class="fs-cat-btn">Khách sạn – Căn hộ – Phòng trọ</button>
                    <button type="button" onclick="filterProjects('biet-thu')" data-cat="biet-thu" class="fs-cat-btn">Biệt thự</button>
                    <button type="button" onclick="filterProjects('nha-pho')" data-cat="nha-pho" class="fs-cat-btn">Nhà phố</button>
                    <button type="button" onclick="filterProjects('van-phong')" data-cat="van-phong" class="fs-cat-btn">Văn phòng</button>
                </div>
            </div>

            <!-- Grid sản phẩm: 2 cột trên giao diện điện thoại (grid-cols-2), 4 cột trên máy tính -->
            <div id="projectsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
                <!-- Các sản phẩm được render tự động từ mảng 15 ảnh thực tế Google Drive bên dưới -->
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG (TRÊN TRANG CHỦ)
    =========================================== -->
    <section id="du-an-da-nang" class="py-10 bg-qn-graybg border-t border-gray-200">
        <div class="fs-container">
            <div class="text-center mb-5">
                <div class="fs-section-title-wrap">
                    <span class="fs-section-line"></span>
                    <h2 class="font-heading font-extrabold text-lg sm:text-xl md:text-2xl text-qn-navy uppercase">
                        DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
                    </h2>
                    <span class="fs-section-line"></span>
                </div>
                <p class="text-xs sm:text-sm text-gray-600 mb-4">
                    Tổng hợp các công trình Nhà phố, Biệt thự, Căn hộ & Văn phòng tiêu biểu của QN HOUSE tại TP. Đà Nẵng
                </p>

                <!-- Bộ lọc khu vực Đà Nẵng nhỏ gọn -->
                <div class="fs-cat-bar" id="daNangFilterBar">
                    <button type="button" onclick="filterDaNang('all')" data-dn="all" class="fs-cat-btn active">Tất cả Đà Nẵng</button>
                    <button type="button" onclick="filterDaNang('hoa-vang')" data-dn="hoa-vang" class="fs-cat-btn">Hòa Tiến – Hòa Vang</button>
                    <button type="button" onclick="filterDaNang('cam-le')" data-dn="cam-le" class="fs-cat-btn">Hòa Xuân – Cẩm Lệ</button>
                    <button type="button" onclick="filterDaNang('hai-chau')" data-dn="hai-chau" class="fs-cat-btn">Hải Châu – Sơn Trà</button>
                    <button type="button" onclick="filterDaNang('lien-chieu')" data-dn="lien-chieu" class="fs-cat-btn">Liên Chiểu – Ngũ Hành Sơn</button>
                </div>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính, không dán nhãn đè lên ảnh -->
            <div id="daNangGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
                <!-- Render bằng JS -->
            </div>
        </div>
    </section>

    <!-- ==========================================
         LĨNH VỰC HOẠT ĐỘNG (4 HẠNG MỤC CHUẨN WEB MẪU)
    =========================================== -->
    <section id="linh-vuc-hoat-dong" class="py-10 bg-white border-t border-gray-200">
        <div class="fs-container">
            <div class="text-center mb-6">
                <div class="fs-section-title-wrap">
                    <span class="fs-section-line"></span>
                    <h2 class="font-heading font-extrabold text-lg sm:text-xl md:text-2xl text-qn-navy uppercase">
                        LĨNH VỰC HOẠT ĐỘNG
                    </h2>
                    <span class="fs-section-line"></span>
                </div>
                <p class="text-xs sm:text-sm text-gray-600">Chuyên môn hóa quy trình từ Thiết kế đến Thi công Phần thô, Hoàn thiện và Nội thất</p>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-4">
                <div class="fs-box">
                    <div class="fs-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1cmI83UnySYJ5Zt1I8A0kB0n94W4XgXgi=w800"
                             onerror="handleDriveImgError(this, '1cmI83UnySYJ5Zt1I8A0kB0n94W4XgXgi', 'THIET+KE+KIEN+TRUC')"
                             alt="Thiết kế Kiến trúc – Nội thất">
                    </div>
                    <div class="fs-box-text">
                        <div>
                            <h3 class="fs-product-title">Thiết Kế Kiến Trúc – Nội Thất</h3>
                            <p class="text-[11px] sm:text-xs text-gray-600 leading-relaxed">
                                Hồ sơ bản vẽ kiến trúc 3D, kết cấu, điện nước ME và phối cảnh nội thất chi tiết, hỗ trợ xin phép xây dựng.
                            </p>
                        </div>
                        <a href="#yeu-cau-bao-gia" class="mt-2 inline-block text-[11px] sm:text-xs font-bold text-qn-gold hover:text-qn-navy">Nhận tư vấn →</a>
                    </div>
                </div>

                <div class="fs-box">
                    <div class="fs-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1A271daJ-s3V5Ws6LRrcDIJ9-Il34FXLq=w800"
                             onerror="handleDriveImgError(this, '1A271daJ-s3V5Ws6LRrcDIJ9-Il34FXLq', 'THI+CONG+PHAN+THO')"
                             alt="Thi công phần thô và nhân công hoàn thiện">
                    </div>
                    <div class="fs-box-text">
                        <div>
                            <h3 class="fs-product-title">Thi Công Phần Thô</h3>
                            <p class="text-[11px] sm:text-xs text-gray-600 leading-relaxed">
                                Thi công nền móng, khung bê tông cốt thép, xây tô tường đúng tiêu chuẩn kỹ thuật với vật tư chuẩn chính hãng.
                            </p>
                        </div>
                        <a href="#yeu-cau-bao-gia" class="mt-2 inline-block text-[11px] sm:text-xs font-bold text-qn-gold hover:text-qn-navy">Nhận tư vấn →</a>
                    </div>
                </div>

                <div class="fs-box">
                    <div class="fs-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1fqJikC677z_7x28XQaAx3VQD7zqWtiUy=w800"
                             onerror="handleDriveImgError(this, '1fqJikC677z_7x28XQaAx3VQD7zqWtiUy', 'THI+CONG+HOAN+THIEN')"
                             alt="Thi công hoàn thiện công trình">
                    </div>
                    <div class="fs-box-text">
                        <div>
                            <h3 class="fs-product-title">Thi Công Hoàn Thiện</h3>
                            <p class="text-[11px] sm:text-xs text-gray-600 leading-relaxed">
                                Ốp lát gạch đá, sơn bả, trần thạch cao, cửa nhôm kính Xingfa, thiết bị vệ sinh và hệ thống chiếu sáng.
                            </p>
                        </div>
                        <a href="#yeu-cau-bao-gia" class="mt-2 inline-block text-[11px] sm:text-xs font-bold text-qn-gold hover:text-qn-navy">Nhận tư vấn →</a>
                    </div>
                </div>

                <div class="fs-box">
                    <div class="fs-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1ImsuD--QivYj4IV9Nx10yzvXfmuRmZ8x=w800"
                             onerror="handleDriveImgError(this, '1ImsuD--QivYj4IV9Nx10yzvXfmuRmZ8x', 'THI+CONG+NOI+THAT')"
                             alt="Thi công nội thất trọn gói">
                    </div>
                    <div class="fs-box-text">
                        <div>
                            <h3 class="fs-product-title">Thi Công Nội Thất</h3>
                            <p class="text-[11px] sm:text-xs text-gray-600 leading-relaxed">
                                Sản xuất và lắp đặt nội thất gỗ An Cường, gỗ tự nhiên, đá Vicostone đồng bộ 99% so với bản vẽ 3D.
                            </p>
                        </div>
                        <a href="#yeu-cau-bao-gia" class="mt-2 inline-block text-[11px] sm:text-xs font-bold text-qn-gold hover:text-qn-navy">Nhận tư vấn →</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         MẪU THIẾT KẾ (MẪU NHÀ PHỐ - MẪU BIỆT THỰ - MẪU NỘI THẤT)
    =========================================== -->
    <section id="mau-thiet-ke" class="py-10 bg-qn-graybg border-t border-gray-200">
        <div class="fs-container">
            <div class="text-center mb-5">
                <div class="fs-section-title-wrap">
                    <span class="fs-section-line"></span>
                    <h2 class="font-heading font-extrabold text-lg sm:text-xl md:text-2xl text-qn-navy uppercase">
                        MẪU THIẾT KẾ KIẾN TRÚC & NỘI THẤT
                    </h2>
                    <span class="fs-section-line"></span>
                </div>
                <p class="text-xs sm:text-sm text-gray-600 mb-4">
                    Bộ sưu tập các mẫu thiết kế nhà phố, biệt thự và nội thất hiện đại được yêu thích nhất tại QN HOUSE
                </p>

                <div class="fs-cat-bar" id="designFilterBar">
                    <button type="button" onclick="filterDesigns('all')" data-des="all" class="fs-cat-btn active">Tất cả mẫu thiết kế</button>
                    <button type="button" onclick="filterDesigns('nha-pho')" data-des="nha-pho" class="fs-cat-btn">Mẫu thiết kế nhà phố</button>
                    <button type="button" onclick="filterDesigns('biet-thu')" data-des="biet-thu" class="fs-cat-btn">Mẫu thiết kế biệt thự</button>
                    <button type="button" onclick="filterDesigns('noi-that')" data-des="noi-that" class="fs-cat-btn">Mẫu thiết kế nội thất</button>
                </div>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div id="designsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
                <!-- Render bằng JS -->
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC BÁO GIÁ (4 GÓI BÁO GIÁ CHUẨN WEB MẪU TINTRUONGTHINH.COM)
    =========================================== -->
    <section id="bao-gia" class="py-10 bg-white border-t border-gray-200">
        <div class="fs-container">
            <div class="text-center mb-6">
                <div class="fs-section-title-wrap">
                    <span class="fs-section-line"></span>
                    <h2 class="font-heading font-extrabold text-lg sm:text-xl md:text-2xl text-qn-navy uppercase">
                        BẢNG BÁO GIÁ THIẾT KẾ & THI CÔNG
                    </h2>
                    <span class="fs-section-line"></span>
                </div>
                <p class="text-xs sm:text-sm text-gray-600">
                    Đơn giá minh bạch, rõ ràng từng chủng loại vật tư – Miễn phí 100% thiết kế khi ký hợp đồng thi công trọn gói
                </p>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-4">
                <div class="border border-gray-200 rounded-lg p-3.5 sm:p-5 flex flex-col justify-between bg-white hover:border-qn-gold transition">
                    <div>
                        <h3 class="font-heading font-bold text-xs sm:text-sm md:text-base text-qn-navy uppercase mb-1">
                            Báo Giá Thiết Kế Kiến Trúc
                        </h3>
                        <p class="text-sm sm:text-lg font-extrabold text-qn-gold mb-2">120.000đ - 180.000đ/m²</p>
                        <ul class="text-[11px] sm:text-xs text-gray-600 space-y-1.5 mb-4">
                            <li>• Phối cảnh 3D mặt tiền & nội thất</li>
                            <li>• Bản vẽ kiến trúc & kết cấu chi tiết</li>
                            <li>• Bản vẽ điện nước ME & dự toán</li>
                            <li>• Hoàn tiền 100% khi thi công trọn gói</li>
                        </ul>
                    </div>
                    <a href="#yeu-cau-bao-gia" onclick="selectQuotePackage('Báo giá thiết kế kiến trúc')" class="block w-full text-center py-2 rounded bg-qn-navy hover:bg-qn-gold text-white font-bold text-xs transition">
                        Đăng ký nhận báo giá
                    </a>
                </div>

                <div class="border border-gray-200 rounded-lg p-3.5 sm:p-5 flex flex-col justify-between bg-white hover:border-qn-gold transition">
                    <div>
                        <h3 class="font-heading font-bold text-xs sm:text-sm md:text-base text-qn-navy uppercase mb-1">
                            Báo Giá Thi Công Phần Thô
                        </h3>
                        <p class="text-sm sm:text-lg font-extrabold text-qn-gold mb-2">3.500.000đ - 3.900.000đ/m²</p>
                        <ul class="text-[11px] sm:text-xs text-gray-600 space-y-1.5 mb-4">
                            <li>• Vật tư thô chuẩn chính hãng</li>
                            <li>• Nhân công hoàn thiện lành nghề</li>
                            <li>• Giám sát kỹ thuật trực tiếp tại công trình</li>
                            <li>• Bảo hành kết cấu lên đến 10 năm</li>
                        </ul>
                    </div>
                    <a href="#yeu-cau-bao-gia" onclick="selectQuotePackage('Báo giá thi công phần thô')" class="block w-full text-center py-2 rounded bg-qn-navy hover:bg-qn-gold text-white font-bold text-xs transition">
                        Đăng ký nhận báo giá
                    </a>
                </div>

                <div class="border border-gray-200 rounded-lg p-3.5 sm:p-5 flex flex-col justify-between bg-white hover:border-qn-gold transition">
                    <div>
                        <h3 class="font-heading font-bold text-xs sm:text-sm md:text-base text-qn-navy uppercase mb-1">
                            Báo Giá Thi Công Hoàn Thiện
                        </h3>
                        <p class="text-sm sm:text-lg font-extrabold text-qn-gold mb-2">2.200.000đ - 3.200.000đ/m²</p>
                        <ul class="text-[11px] sm:text-xs text-gray-600 space-y-1.5 mb-4">
                            <li>• Gạch ốp lát, đá Granite/Marble</li>
                            <li>• Sơn Dulux/Jotun, trần thạch cao</li>
                            <li>• Cửa nhôm Xingfa, thiết bị Inax/Toto</li>
                            <li>• Cam kết đúng mã vật tư hợp đồng</li>
                        </ul>
                    </div>
                    <a href="#yeu-cau-bao-gia" onclick="selectQuotePackage('Báo giá thi công hoàn thiện')" class="block w-full text-center py-2 rounded bg-qn-navy hover:bg-qn-gold text-white font-bold text-xs transition">
                        Đăng ký nhận báo giá
                    </a>
                </div>

                <div class="border-2 border-qn-gold rounded-lg p-3.5 sm:p-5 flex flex-col justify-between bg-amber-50/30">
                    <div>
                        <h3 class="font-heading font-bold text-xs sm:text-sm md:text-base text-qn-navy uppercase mb-1">
                            Báo Giá Thi Công Trọn Gói
                        </h3>
                        <p class="text-sm sm:text-lg font-extrabold text-qn-gold mb-2">5.600.000đ - 7.200.000đ/m²</p>
                        <ul class="text-[11px] sm:text-xs text-gray-600 space-y-1.5 mb-4">
                            <li>• Chìa khóa trao tay từ A - Z</li>
                            <li>• Miễn phí xin GPXD & hồ sơ thiết kế</li>
                            <li>• Không phát sinh chi phí ngoài HĐ</li>
                            <li>• Bảo hành tổng thể nhanh chóng 24/7</li>
                        </ul>
                    </div>
                    <a href="#yeu-cau-bao-gia" onclick="selectQuotePackage('Báo giá thi công trọn gói')" class="block w-full text-center py-2 rounded bg-qn-gold hover:bg-amber-600 text-white font-bold text-xs transition">
                        Đăng ký nhận báo giá
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ TRANG CHỦ (CHUẨN WEB MẪU TINTRUONGTHINH.COM)
    =========================================== -->
    <section id="yeu-cau-bao-gia" class="py-10 bg-qn-navy text-white">
        <div class="fs-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                <div class="lg:col-span-5">
                    <p class="text-xs font-bold uppercase tracking-widest text-qn-gold mb-1.5">HỖ TRỢ KHÁCH HÀNG 24/7</p>
                    <h2 class="font-heading font-extrabold text-xl sm:text-2xl md:text-3xl uppercase mb-3">
                        MIỄN PHÍ TƯ VẤN & BÁO GIÁ XÂY DỰNG
                    </h2>
                    <p class="text-xs sm:text-sm text-gray-200 leading-relaxed mb-4">
                        Quý khách vui lòng để lại thông tin công trình. Kiến trúc sư trưởng của <strong>QN HOUSE</strong> sẽ liên hệ tư vấn phương án mặt bằng, dự toán chi phí sát thực tế nhất trong vòng 15 phút.
                    </p>
                    <div class="space-y-2.5 text-xs sm:text-sm bg-white/5 p-4 rounded-lg border border-white/10">
                        <div class="flex items-center gap-2.5">
                            <i class="fa-solid fa-phone-volume text-qn-gold w-4"></i>
                            <span>Hotline / Zalo: <a href="tel:0904106468" class="font-bold text-qn-gold hover:underline">0904.106.468</a></span>
                        </div>
                        <div class="flex items-start gap-2.5">
                            <i class="fa-solid fa-location-dot text-qn-gold w-4 mt-1"></i>
                            <span>Địa chỉ: 605 Hoà Tiến - Hoà Vang - Đà Nẵng</span>
                        </div>
                        <div class="flex items-start gap-2.5">
                            <i class="fa-solid fa-building text-qn-gold w-4 mt-1"></i>
                            <span>Chi nhánh: Nguyễn Huệ - Tư Nghĩa - Quảng Ngãi, Đà Nẵng</span>
                        </div>
                        <div class="flex items-center gap-2.5">
                            <i class="fa-solid fa-globe text-qn-gold w-4"></i>
                            <span>Website: <a href="https://qnhouse.com" class="text-qn-gold hover:underline">qnhouse.com</a></span>
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-7">
                    <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="bg-white text-gray-800 rounded-lg p-4 sm:p-6 shadow-lg">
                        <h3 class="font-heading font-bold text-base sm:text-lg text-qn-navy uppercase mb-4 pb-2 border-b border-gray-200">
                            ĐĂNG KÝ YÊU CẦU TƯ VẤN & BÁO GIÁ
                        </h3>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 sm:gap-4">
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Họ tên Quý khách *</label>
                                <input type="text" id="qName" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-xs sm:text-sm border border-gray-300 rounded focus:outline-none focus:border-qn-navy">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Số điện thoại / Zalo *</label>
                                <input type="tel" id="qPhone" required placeholder="Ví dụ: 0904.106.468" class="w-full px-3 py-2 text-xs sm:text-sm border border-gray-300 rounded focus:outline-none focus:border-qn-navy">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Loại công trình</label>
                                <select id="qType" class="w-full px-3 py-2 text-xs sm:text-sm border border-gray-300 rounded focus:outline-none focus:border-qn-navy bg-white">
                                    <option value="Nhà phố">Nhà phố</option>
                                    <option value="Biệt thự">Biệt thự</option>
                                    <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                                    <option value="Văn phòng">Văn phòng</option>
                                    <option value="Thiết kế & Thi công nội thất">Thiết kế & Thi công nội thất</option>
                                    <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Mức đầu tư dự kiến</label>
                                <select id="qBudget" class="w-full px-3 py-2 text-xs sm:text-sm border border-gray-300 rounded focus:outline-none focus:border-qn-navy bg-white">
                                    <option value="Chưa xác định">Chưa xác định</option>
                                    <option value="Dưới 1 tỷ">Dưới 1 tỷ</option>
                                    <option value="1 - 2 tỷ">1 - 2 tỷ</option>
                                    <option value="2 - 3 tỷ">2 - 3 tỷ</option>
                                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Khu vực xây dựng</label>
                                <input type="text" id="qLocation" placeholder="Đà Nẵng / Quảng Ngãi / Khác..." class="w-full px-3 py-2 text-xs sm:text-sm border border-gray-300 rounded focus:outline-none focus:border-qn-navy">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Diện tích đất / Số tầng</label>
                                <input type="text" id="qArea" placeholder="VD: 5x20m, 3 tầng..." class="w-full px-3 py-2 text-xs sm:text-sm border border-gray-300 rounded focus:outline-none focus:border-qn-navy">
                            </div>
                            <div class="sm:col-span-2">
                                <label class="block text-xs font-bold text-gray-700 mb-1">Yêu cầu chi tiết</label>
                                <textarea id="qNote" rows="2" placeholder="Nhập nhu cầu công năng hoặc gói báo giá cần tư vấn..." class="w-full px-3 py-2 text-xs sm:text-sm border border-gray-300 rounded focus:outline-none focus:border-qn-navy"></textarea>
                            </div>
                        </div>

                        <div class="mt-4 flex flex-wrap items-center justify-between gap-3">
                            <button type="submit" class="w-full sm:w-auto px-6 py-2.5 rounded bg-qn-gold hover:bg-amber-600 text-white font-bold text-xs sm:text-sm uppercase tracking-wide transition shadow">
                                <i class="fa-solid fa-paper-plane mr-1.5"></i> Gửi Yêu Cầu Báo Giá Ngay
                            </button>
                            <span class="text-[11px] text-gray-500">Hoặc gọi trực tiếp: <strong class="text-qn-navy">0904.106.468</strong></span>
                        </div>

                        <div id="quoteSuccessMsg" class="hidden mt-3 p-3 rounded bg-green-50 border border-green-300 text-green-800 text-xs font-medium"></div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ (CHUẨN WEB MẪU TINTRUONGTHINH.COM)
    =========================================== -->
    <section id="tin-tuc" class="py-10 bg-white border-t border-gray-200">
        <div class="fs-container">
            <div class="text-center mb-6">
                <div class="fs-section-title-wrap">
                    <span class="fs-section-line"></span>
                    <h2 class="font-heading font-extrabold text-lg sm:text-xl md:text-2xl text-qn-navy uppercase">
                        TIN TỨC & KINH NGHIỆM XÂY NHÀ
                    </h2>
                    <span class="fs-section-line"></span>
                </div>
                <p class="text-xs sm:text-sm text-gray-600">Cập nhật kiến thức thiết kế kiến trúc, kỹ thuật thi công và cẩm nang xây nhà trọn gói</p>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-4">
                <article class="fs-box">
                    <div class="fs-box-image">
                        <img src="https://lh3.googleusercontent.com/d/11oZAhO2AsbGFYm1pdsPS5Vtgkd9IP2yZ=w800"
                             onerror="handleDriveImgError(this, '11oZAhO2AsbGFYm1pdsPS5Vtgkd9IP2yZ', 'TIN+TUC+1')"
                             alt="Hướng dẫn bảo dưỡng bê tông móng đúng cách">
                    </div>
                    <div class="fs-box-text text-left">
                        <div>
                            <h3 class="fs-product-title">Hướng Dẫn Bảo Dưỡng Bê Tông Móng Và Sàn Đúng Kỹ Thuật Xây Dựng</h3>
                            <p class="text-[11px] sm:text-xs text-gray-600 leading-relaxed">
                                Trong quá trình xây dựng công trình, bê tông móng đóng vai trò quyết định đến độ bền vững lâu dài của ngôi nhà...
                            </p>
                        </div>
                        <span class="mt-2 inline-block text-[11px] font-bold text-qn-gold">Đọc bài viết →</span>
                    </div>
                </article>

                <article class="fs-box">
                    <div class="fs-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1ugKZwI_07LD42SRgLweM-PeRQt9-01Lw=w800"
                             onerror="handleDriveImgError(this, '1ugKZwI_07LD42SRgLweM-PeRQt9-01Lw', 'TIN+TUC+2')"
                             alt="03 Nỗi lo lớn nhất khi xây nhà mà Chủ đầu tư thường gặp phải">
                    </div>
                    <div class="fs-box-text text-left">
                        <div>
                            <h3 class="fs-product-title">03 Nỗi Lo Lớn Nhất Khi Xây Nhà Mà Chủ Đầu Tư Thường Gặp Phải</h3>
                            <p class="text-[11px] sm:text-xs text-gray-600 leading-relaxed">
                                Làm sao để kiểm soát chi phí không phát sinh, đảm bảo chất lượng vật tư và đúng tiến độ bàn giao tại Đà Nẵng...
                            </p>
                        </div>
                        <span class="mt-2 inline-block text-[11px] font-bold text-qn-gold">Đọc bài viết →</span>
                    </div>
                </article>

                <article class="fs-box">
                    <div class="fs-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1QcvBpsk1aY6aHVHIVrZs9ALP17TUWfkK=w800"
                             onerror="handleDriveImgError(this, '1QcvBpsk1aY6aHVHIVrZs9ALP17TUWfkK', 'TIN+TUC+3')"
                             alt="Tâm lý học không gian: Nội thất tác động đến hành vi của chúng ta như thế nào">
                    </div>
                    <div class="fs-box-text text-left">
                        <div>
                            <h3 class="fs-product-title">Tâm Lý Học Không Gian: Thiết Kế Nội Thất Tác Động Đến Tổ Ấm Thế Nào?</h3>
                            <p class="text-[11px] sm:text-xs text-gray-600 leading-relaxed">
                                Cách bố trí ánh sáng tự nhiên, thông gió và vật liệu nội thất giúp nâng cao chất lượng sống cho mọi thành viên...
                            </p>
                        </div>
                        <span class="mt-2 inline-block text-[11px] font-bold text-qn-gold">Đọc bài viết →</span>
                    </div>
                </article>

                <article class="fs-box">
                    <div class="fs-box-image">
                        <img src="https://lh3.googleusercontent.com/d/1TWxo6uXoJMty8Qsbu4z8HFR5TeLvWph1=w800"
                             onerror="handleDriveImgError(this, '1TWxo6uXoJMty8Qsbu4z8HFR5TeLvWph1', 'TIN+TUC+4')"
                             alt="Kinh nghiệm xin giấy phép xây dựng và thiết kế nhà trọn gói Đà Nẵng">
                    </div>
                    <div class="fs-box-text text-left">
                        <div>
                            <h3 class="fs-product-title">Kinh Nghiệm Xây Nhà Trọn Gói Tại Đà Nẵng & Quảng Ngãi Tiết Kiệm Nhất</h3>
                            <p class="text-[11px] sm:text-xs text-gray-600 leading-relaxed">
                                Quy trình từ khảo sát hiện trạng, thiết kế hồ sơ thi công, xin phép xây dựng đến nghiệm thu bàn giao nhà...
                            </p>
                        </div>
                        <span class="mt-2 inline-block text-[11px] font-bold text-qn-gold">Đọc bài viết →</span>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC ĐỐI TÁC VẬT LIỆU & NỘI THẤT TRÊN TRANG CHỦ
    =========================================== -->
    <section id="doi-tac" class="py-8 bg-qn-graybg border-t border-gray-200">
        <div class="fs-container">
            <div class="text-center mb-5">
                <div class="fs-section-title-wrap">
                    <span class="fs-section-line"></span>
                    <h2 class="font-heading font-extrabold text-lg sm:text-xl text-qn-navy uppercase">
                        ĐỐI TÁC ĐỒNG HÀNH CÙNG QN HOUSE
                    </h2>
                    <span class="fs-section-line"></span>
                </div>
                <p class="text-xs sm:text-sm text-gray-600">Cam kết sử dụng 100% vật tư và thiết bị chính hãng từ các thương hiệu hàng đầu</p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-2.5 sm:gap-3">
                <div class="bg-white border border-gray-200 rounded p-3 text-center hover:border-qn-gold transition">
                    <div class="font-heading font-extrabold text-sm text-qn-navy">THÉP HÒA PHÁT</div>
                    <div class="text-[11px] text-gray-500">Kết cấu thép xây dựng</div>
                </div>
                <div class="bg-white border border-gray-200 rounded p-3 text-center hover:border-qn-gold transition">
                    <div class="font-heading font-extrabold text-sm text-qn-navy">GỖ AN CƯỜNG</div>
                    <div class="text-[11px] text-gray-500">Vật liệu gỗ nội thất</div>
                </div>
                <div class="bg-white border border-gray-200 rounded p-3 text-center hover:border-qn-gold transition">
                    <div class="font-heading font-extrabold text-sm text-qn-navy">SƠN DULUX / JOTUN</div>
                    <div class="text-[11px] text-gray-500">Sơn ngoại & nội thất</div>
                </div>
                <div class="bg-white border border-gray-200 rounded p-3 text-center hover:border-qn-gold transition">
                    <div class="font-heading font-extrabold text-sm text-qn-navy">INAX & TOTO</div>
                    <div class="text-[11px] text-gray-500">Thiết bị vệ sinh cao cấp</div>
                </div>
                <div class="bg-white border border-gray-200 rounded p-3 text-center hover:border-qn-gold transition">
                    <div class="font-heading font-extrabold text-sm text-qn-navy">NHÔM XINGFA</div>
                    <div class="text-[11px] text-gray-500">Hệ cửa nhôm kính</div>
                </div>
                <div class="bg-white border border-gray-200 rounded p-3 text-center hover:border-qn-gold transition">
                    <div class="font-heading font-extrabold text-sm text-qn-navy">PANASONIC / SIKA</div>
                    <div class="text-[11px] text-gray-500">Thiết bị điện & Chống thấm</div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         ĐƯA FACEBOOK & ẢNH BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ
    =========================================== -->
    <section id="lien-he" class="py-10 bg-white border-t border-gray-200">
        <div class="fs-container">
            <div class="text-center mb-6">
                <div class="fs-section-title-wrap">
                    <span class="fs-section-line"></span>
                    <h2 class="font-heading font-extrabold text-lg sm:text-xl md:text-2xl text-qn-navy uppercase">
                        KẾT NỐI FACEBOOK & BẢN ĐỒ GOOGLE MAPS QN HOUSE
                    </h2>
                    <span class="fs-section-line"></span>
                </div>
                <p class="text-xs sm:text-sm text-gray-600">
                    Theo dõi hoạt động thi công hàng ngày trên Facebook và định vị trực tiếp văn phòng QN HOUSE
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
                <!-- Cột 1: Đưa Facebook https://www.facebook.com/angkhoa.111853 ra ngoài trang chủ -->
                <div class="lg:col-span-5 bg-qn-graybg rounded-lg border border-gray-200 p-4 flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between gap-2 pb-3 mb-3 border-b border-gray-200">
                            <div class="flex items-center gap-2.5">
                                <div class="w-10 h-10 rounded-full bg-blue-600 text-white flex items-center justify-center text-lg shrink-0">
                                    <i class="fa-brands fa-facebook-f"></i>
                                </div>
                                <div>
                                    <h3 class="font-bold text-sm text-qn-navy">KẾT NỐI FACEBOOK CHÍNH THỨC</h3>
                                    <p class="text-[11px] text-gray-500">Nhà Thầu Xây Dựng QN HOUSE</p>
                                </div>
                            </div>
                            <a href="https://www.facebook.com/angkhoa.111853" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded bg-blue-600 hover:bg-blue-700 text-white text-xs font-bold shrink-0">
                                Mở Facebook
                            </a>
                        </div>

                        <!-- Khung hiển thị trang Facebook trực quan ngay ngoài trang chủ -->
                        <div class="bg-white rounded-lg border border-gray-200 overflow-hidden shadow-xs mb-3">
                            <div class="relative h-36 bg-qn-navy">
                                <img src="https://lh3.googleusercontent.com/d/1nv_lSxn0mu-71NGKss3abLOuEMcB-bkQ=w900"
                                     onerror="handleDriveImgError(this, '1nv_lSxn0mu-71NGKss3abLOuEMcB-bkQ', 'FACEBOOK+QN+HOUSE')"
                                     alt="Ảnh bìa Facebook QN HOUSE"
                                     class="w-full h-full object-cover opacity-80">
                                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                                <div class="absolute bottom-3 left-3 right-3 flex items-end gap-3">
                                    <img src="https://lh3.googleusercontent.com/d/19TR4aCX55hs8zwz36DkY9aE2GrHZz6r_=w200"
                                         onerror="handleDriveImgError(this, '19TR4aCX55hs8zwz36DkY9aE2GrHZz6r_', 'QN')"
                                         alt="Logo QN HOUSE"
                                         class="w-12 h-12 rounded-lg border-2 border-white bg-white object-contain p-0.5 shrink-0">
                                    <div class="text-white">
                                        <h4 class="font-bold text-sm leading-tight">QN HOUSE - Thiết Kế & Thi Công Trọn Gói</h4>
                                        <p class="text-[11px] text-gray-200 break-all">facebook.com/angkhoa.111853</p>
                                    </div>
                                </div>
                            </div>
                            <div class="p-3 text-xs text-gray-700 space-y-2">
                                <p class="leading-relaxed">
                                    Cập nhật nhật ký thi công thực tế, bàn giao nhà trọn gói tại Đà Nẵng & Quảng Ngãi. Tư vấn trực tiếp cùng Giám đốc Kỹ thuật QN HOUSE.
                                </p>
                                <div class="flex flex-wrap gap-2 pt-1">
                                    <a href="https://www.facebook.com/angkhoa.111853" target="_blank" rel="noopener noreferrer" class="flex-1 text-center py-2 px-3 rounded bg-blue-600 hover:bg-blue-700 text-white font-bold text-xs transition">
                                        <i class="fa-brands fa-facebook mr-1"></i> Xem Trang Facebook
                                    </a>
                                    <a href="https://www.facebook.com/angkhoa.111853" target="_blank" rel="noopener noreferrer" class="flex-1 text-center py-2 px-3 rounded bg-gray-100 hover:bg-gray-200 text-qn-navy font-bold text-xs transition">
                                        <i class="fa-brands fa-facebook-messenger mr-1 text-blue-600"></i> Nhắn Tin Tư Vấn
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white rounded-lg p-3 border border-gray-200 text-xs space-y-1.5">
                        <div class="font-bold text-qn-navy uppercase">THÔNG TIN LIÊN HỆ TRỰC TIẾP:</div>
                        <div>• <strong>Website:</strong> <a href="https://qnhouse.com" class="text-qn-blue hover:underline">qnhouse.com</a></div>
                        <div>• <strong>Hotline / Zalo:</strong> <a href="tel:0904106468" class="text-red-600 font-bold">0904.106.468</a></div>
                        <div>• <strong>Trụ sở chính:</strong> 605 Hoà Tiến - Hoà Vang - Đà Nẵng</div>
                        <div>• <strong>Chi nhánh:</strong> Nguyễn Huệ - Tư Nghĩa - Quảng Ngãi, Đà Nẵng</div>
                    </div>
                </div>

                <!-- Cột 2: Đưa ảnh & bản đồ Google Map ra ngoài trang chủ -->
                <div class="lg:col-span-7 bg-qn-graybg rounded-lg border border-gray-200 p-4 flex flex-col justify-between">
                    <div class="flex flex-wrap items-center justify-between gap-2 pb-3 mb-3 border-b border-gray-200">
                        <div>
                            <h3 class="font-bold text-sm text-qn-navy uppercase">
                                <i class="fa-solid fa-map-location-dot text-qn-gold mr-1.5"></i> BẢN ĐỒ GOOGLE MAPS TRỤ SỞ & CHI NHÁNH
                            </h3>
                            <p class="text-[11px] text-gray-600">605 Hoà Tiến - Hoà Vang - Đà Nẵng | CN: Nguyễn Huệ - Tư Nghĩa - Quảng Ngãi, Đà Nẵng</p>
                        </div>
                        <div class="flex items-center gap-1.5">
                            <button type="button" onclick="switchMapLocation('danang')" id="btnMapDN" class="px-2.5 py-1 rounded text-xs font-bold bg-qn-navy text-white">
                                Map Đà Nẵng
                            </button>
                            <button type="button" onclick="switchMapLocation('quangngai')" id="btnMapQN" class="px-2.5 py-1 rounded text-xs font-bold bg-white border border-gray-300 text-qn-navy hover:bg-gray-100">
                                Map CN Quảng Ngãi
                            </button>
                        </div>
                    </div>

                    <!-- Khung Bản Đồ Google Maps trực tiếp ngoài trang chủ -->
                    <div class="w-full h-64 sm:h-72 rounded-lg overflow-hidden border border-gray-300 bg-white relative">
                        <iframe id="googleMapIframe"
                                title="Bản đồ Google Maps Nhà thầu xây dựng QN HOUSE"
                                src="https://maps.google.com/maps?q=605%20Ho%C3%A0%20Ti%E1%BA%BFn%2C%20Ho%C3%A0%20Vang%2C%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=14&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-full border-0"
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade"></iframe>
                    </div>

                    <div class="mt-3 grid grid-cols-1 sm:grid-cols-2 gap-2.5 text-xs">
                        <a href="https://www.google.com/maps/search/?api=1&query=605+Hoa+Tien+Hoa+Vang+Da+Nang" target="_blank" rel="noopener noreferrer" class="flex items-center justify-between p-2.5 rounded bg-white border border-gray-200 hover:border-qn-gold transition">
                            <div>
                                <strong class="block text-qn-navy">Trụ sở Đà Nẵng</strong>
                                <span class="text-[11px] text-gray-600">605 Hoà Tiến - Hoà Vang - Đà Nẵng</span>
                            </div>
                            <span class="text-qn-gold font-bold whitespace-nowrap ml-2">Chỉ đường <i class="fa-solid fa-diamond-turn-right"></i></span>
                        </a>
                        <a href="https://www.google.com/maps/search/?api=1&query=Nguyen+Hue+Tu+Nghia+Quang+Ngai" target="_blank" rel="noopener noreferrer" class="flex items-center justify-between p-2.5 rounded bg-white border border-gray-200 hover:border-qn-gold transition">
                            <div>
                                <strong class="block text-qn-navy">Chi nhánh</strong>
                                <span class="text-[11px] text-gray-600">Nguyễn Huệ - Tư Nghĩa - Quảng Ngãi, Đà Nẵng</span>
                            </div>
                            <span class="text-qn-gold font-bold whitespace-nowrap ml-2">Chỉ đường <i class="fa-solid fa-diamond-turn-right"></i></span>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FOOTER CHUẨN FLATSOME (GIỐNG WEB MẪU TINTRUONGTHINH.COM)
    =========================================== -->
    <footer class="bg-qn-navy text-gray-200 pt-10 pb-20 lg:pb-8 border-t-4 border-qn-gold">
        <div class="fs-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-8 border-b border-white/10">
                <!-- Thông tin công ty -->
                <div class="lg:col-span-5">
                    <div class="flex items-center gap-3 mb-3">
                        <img src="https://lh3.googleusercontent.com/d/19TR4aCX55hs8zwz36DkY9aE2GrHZz6r_=w200"
                             onerror="handleDriveImgError(this, '19TR4aCX55hs8zwz36DkY9aE2GrHZz6r_', 'QN+HOUSE')"
                             alt="Logo QN HOUSE"
                             class="w-11 h-11 rounded bg-white p-0.5 object-contain shrink-0">
                        <div>
                            <h3 class="font-heading font-extrabold text-base text-white">NHÀ THẦU XÂY DỰNG QN HOUSE</h3>
                            <p class="text-xs text-qn-gold font-semibold">Nhà Thầu Thiết Kế & Thi Công Trọn Gói</p>
                        </div>
                    </div>
                    <p class="text-xs text-gray-300 leading-relaxed mb-3">
                        Chuyên Thiết kế Kiến trúc – Thi công Xây dựng – Thi công Nội thất trọn gói các công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ, Văn phòng tại Đà Nẵng & Quảng Ngãi.
                    </p>
                    <ul class="text-xs space-y-1.5 text-gray-200">
                        <li><i class="fa-solid fa-location-dot text-qn-gold w-4"></i> <strong>Địa chỉ:</strong> 605 Hoà Tiến - Hoà Vang - Đà Nẵng</li>
                        <li><i class="fa-solid fa-building text-qn-gold w-4"></i> <strong>Chi nhánh:</strong> Nguyễn Huệ - Tư Nghĩa - Quảng Ngãi, Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-qn-gold w-4"></i> <strong>Hotline:</strong> <a href="tel:0904106468" class="text-qn-gold font-bold hover:underline">0904.106.468</a></li>
                        <li><i class="fa-solid fa-globe text-qn-gold w-4"></i> <strong>Website:</strong> <a href="https://qnhouse.com" class="hover:text-qn-gold">qnhouse.com</a></li>
                        <li><i class="fa-brands fa-facebook text-qn-gold w-4"></i> <strong>Facebook:</strong> <a href="https://www.facebook.com/angkhoa.111853" target="_blank" rel="noopener noreferrer" class="hover:text-qn-gold break-all">facebook.com/angkhoa.111853</a></li>
                    </ul>
                </div>

                <!-- Lĩnh vực hoạt động -->
                <div class="lg:col-span-3">
                    <h4 class="font-heading font-bold text-sm text-white uppercase mb-3 pb-1.5 border-b border-white/15">
                        LĨNH VỰC HOẠT ĐỘNG
                    </h4>
                    <ul class="text-xs space-y-2">
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-qn-gold transition">• Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-qn-gold transition">• Thi công phần thô</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-qn-gold transition">• Thi công hoàn thiện</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-qn-gold transition">• Thi công nội thất trọn gói</a></li>
                        <li><a href="#bao-gia" class="hover:text-qn-gold transition">• Báo giá thi công trọn gói</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-qn-gold transition">• Dự án xây dựng tại Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Danh mục công trình -->
                <div class="lg:col-span-4">
                    <h4 class="font-heading font-bold text-sm text-white uppercase mb-3 pb-1.5 border-b border-white/15">
                        DANH MỤC SẢN PHẨM & DỰ ÁN
                    </h4>
                    <div class="grid grid-cols-2 gap-2 text-xs">
                        <a href="#cong-trinh-thuc-te" onclick="filterProjects('khach-san-can-ho')" class="hover:text-qn-gold transition">• Khách sạn – Căn hộ</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterProjects('biet-thu')" class="hover:text-qn-gold transition">• Biệt thự hiện đại</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterProjects('nha-pho')" class="hover:text-qn-gold transition">• Nhà phố trọn gói</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterProjects('van-phong')" class="hover:text-qn-gold transition">• Văn phòng công ty</a>
                        <a href="#mau-thiet-ke" onclick="filterDesigns('nha-pho')" class="hover:text-qn-gold transition">• Mẫu thiết kế nhà phố</a>
                        <a href="#mau-thiet-ke" onclick="filterDesigns('noi-that')" class="hover:text-qn-gold transition">• Mẫu thiết kế nội thất</a>
                    </div>
                    <div class="mt-4 p-3 rounded bg-white/5 border border-white/10 text-xs">
                        <div class="font-bold text-qn-gold mb-1">TƯ VẤN MIỄN PHÍ 24/7:</div>
                        <p class="text-gray-300 text-[11px]">Gọi ngay <strong>0904.106.468</strong> để nhận khảo sát và báo giá xây dựng trọn gói tốt nhất.</p>
                    </div>
                </div>
            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-gray-400">
                <p>Copyright 2026 © <strong>CÔNG TY TNHH ĐẦU TƯ XÂY DỰNG QN HOUSE (qnhouse.com)</strong></p>
                <p>Kiến Trúc – Xây Dựng – Nội Thất Trọn Gói Uy Tín</p>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         Tương thích hoàn hảo trên cả máy tính và điện thoại
    =========================================== -->
    <!-- Cụm nút nổi bên trái/phải trên Máy tính & Điện thoại -->
    <div class="fixed right-3 bottom-20 sm:bottom-6 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook -->
        <a href="https://www.facebook.com/angkhoa.111853" target="_blank" rel="noopener noreferrer"
           title="Facebook QN HOUSE"
           class="flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105">
            <i class="fa-brands fa-facebook-f text-sm sm:text-base w-4 text-center"></i>
            <span class="text-xs font-bold pr-1">Facebook</span>
        </a>

        <!-- Nút Zalo -->
        <a href="https://zalo.me/0904106468" target="_blank" rel="noopener noreferrer"
           title="Chat Zalo 0904.106.468"
           class="flex items-center gap-2 bg-sky-500 hover:bg-sky-600 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105">
            <span class="font-extrabold text-xs sm:text-sm bg-white text-sky-600 rounded-full w-5 h-5 flex items-center justify-center">Z</span>
            <span class="text-xs font-bold pr-1">Chat Zalo</span>
        </a>

        <!-- Nút Hotline -->
        <a href="tel:0904106468"
           title="Gọi Hotline 0904.106.468"
           class="floating-pulse flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white px-3.5 py-2.5 rounded-full shadow-xl transition transform hover:scale-105">
            <i class="fa-solid fa-phone-volume text-sm sm:text-base"></i>
            <span class="text-xs sm:text-sm font-extrabold">0904.106.468</span>
        </a>
    </div>

    <!-- Thanh liên hệ nhanh cố định đáy màn hình trên Điện Thoại -->
    <div class="sm:hidden fixed bottom-0 left-0 right-0 z-50 bg-white border-t border-gray-200 shadow-2xl grid grid-cols-3 text-center">
        <a href="tel:0904106468" class="py-2.5 flex flex-col items-center justify-center text-red-600 font-bold text-[11px] border-r border-gray-100">
            <i class="fa-solid fa-phone-volume text-sm mb-0.5"></i>
            <span>Gọi 0904.106.468</span>
        </a>
        <a href="https://zalo.me/0904106468" target="_blank" rel="noopener noreferrer" class="py-2.5 flex flex-col items-center justify-center text-sky-600 font-bold text-[11px] border-r border-gray-100">
            <i class="fa-solid fa-comment-dots text-sm mb-0.5"></i>
            <span>Nhắn Zalo</span>
        </a>
        <a href="https://www.facebook.com/angkhoa.111853" target="_blank" rel="noopener noreferrer" class="py-2.5 flex flex-col items-center justify-center text-blue-600 font-bold text-[11px]">
            <i class="fa-brands fa-facebook text-sm mb-0.5"></i>
            <span>Facebook</span>
        </a>
    </div>

    <!-- ==========================================
         MODAL XEM CHI TIẾT CÔNG TRÌNH / SẢN PHẨM
    =========================================== -->
    <div id="projectModal" class="fixed inset-0 z-50 hidden bg-black/75 flex items-center justify-center p-3">
        <div class="bg-white rounded-lg max-w-2xl w-full overflow-hidden shadow-2xl border border-gray-200">
            <div class="flex items-center justify-between px-4 py-3 bg-qn-navy text-white">
                <h3 id="modalTitle" class="font-heading font-bold text-sm sm:text-base">Chi tiết công trình</h3>
                <button type="button" onclick="closeProjectModal()" class="w-7 h-7 rounded-full bg-white/10 hover:bg-white/20 flex items-center justify-center text-white">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="p-4">
                <div class="aspect-video w-full rounded overflow-hidden bg-gray-100 mb-3">
                    <img id="modalImg" src="" alt="Ảnh thực tế công trình QN HOUSE" class="w-full h-full object-cover">
                </div>
                <p id="modalCat" class="text-xs font-bold text-qn-gold uppercase mb-1"></p>
                <p id="modalDesc" class="text-xs sm:text-sm text-gray-700 leading-relaxed mb-4"></p>
                <div class="flex flex-wrap items-center justify-between gap-2 pt-3 border-t border-gray-100">
                    <a href="tel:0904106468" class="px-4 py-2 rounded bg-red-600 text-white font-bold text-xs">
                        <i class="fa-solid fa-phone mr-1"></i> Tư vấn mẫu này: 0904.106.468
                    </a>
                    <a href="#yeu-cau-bao-gia" onclick="closeProjectModal()" class="px-4 py-2 rounded bg-qn-navy text-white font-bold text-xs">
                        Nhận báo giá tương tự
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ ẢNH GOOGLE DRIVE, SLIDER, BỘ LỌC SẢN PHẨM & FORM
    =========================================== -->
    <script>
        /* Xử lý tự động dự phòng link ảnh Google Drive để luôn hiển thị mượt mà trên mọi trình duyệt */
        function handleDriveImgError(imgEl, fileId, fallbackText) {
            const step = parseInt(imgEl.getAttribute('data-retry-step') || '0', 10);
            if (step === 0) {
                imgEl.setAttribute('data-retry-step', '1');
                imgEl.src = 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w1200';
            } else if (step === 1) {
                imgEl.setAttribute('data-retry-step', '2');
                imgEl.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
            } else {
                imgEl.onerror = null;
                imgEl.src = 'https://placehold.co/800x600/0f2942/d49a2a?text=' + (fallbackText || 'QN+HOUSE');
            }
        }

        /* Danh sách toàn bộ 15 ảnh công trình thực tế từ Google Drive gắn đúng tên sản phẩm & danh mục web mẫu */
        const realProjectsData = [
            {
                id: 1,
                driveId: '1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk',
                title: 'KHÁCH SẠN BẮC NAM – THIẾT KẾ & THI CÔNG TRỌN GÓI',
                category: 'khach-san-can-ho',
                categoryName: 'Khách sạn – Căn hộ – Phòng trọ',
                daNangArea: 'hai-chau',
                location: 'Đà Nẵng',
                desc: 'Công trình khách sạn kết hợp căn hộ lưu trú cao cấp do QN HOUSE thiết kế kiến trúc và thi công hoàn thiện trọn gói.'
            },
            {
                id: 2,
                driveId: '1PjtEF4hlMU_42b438GmEQhYZTba75kRJ',
                title: 'BIỆT THỰ 2 MẶT TIỀN HIỆN ĐẠI – KHU ĐÔ THỊ HÒA XUÂN',
                category: 'biet-thu',
                categoryName: 'Biệt thự',
                daNangArea: 'cam-le',
                location: 'Hòa Xuân, Cẩm Lệ, Đà Nẵng',
                desc: 'Thiết kế và thi công trọn gói biệt thự 2 mặt tiền phong cách hiện đại, không gian mở xanh mát tại Hòa Xuân, Đà Nẵng.'
            },
            {
                id: 3,
                driveId: '1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA',
                title: 'NHÀ CHỊ LY – NGUYỄN CHÁNH, ĐÀ NẴNG',
                category: 'nha-pho',
                categoryName: 'Nhà phố',
                daNangArea: 'lien-chieu',
                location: 'Nguyễn Chánh, Liên Chiểu, Đà Nẵng',
                desc: 'Công trình nhà phố hiện đại 3 tầng tại đường Nguyễn Chánh, Đà Nẵng – Thi công phần thô và hoàn thiện nội thất trọn gói.'
            },
            {
                id: 4,
                driveId: '1ng7_50Be4LsQqNa28KBn8rSCicz40ir9',
                title: 'NHÀ ANH BÌNH – KHU ĐÔ THỊ HÒA XUÂN, ĐÀ NẴNG',
                category: 'nha-pho',
                categoryName: 'Nhà phố',
                daNangArea: 'cam-le',
                location: 'Hòa Xuân, Cẩm Lệ, Đà Nẵng',
                desc: 'Nhà phố 3 tầng 1 tum thiết kế thông tầng lấy sáng tự nhiên, thi công trọn gói chìa khóa trao tay tại Hòa Xuân.'
            },
            {
                id: 5,
                driveId: '1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS',
                title: 'KYO APARTMENT – CĂN HỘ CAO CẤP VIEW SÔNG ĐÀ NẴNG',
                category: 'khach-san-can-ho',
                categoryName: 'Khách sạn – Căn hộ – Phòng trọ',
                daNangArea: 'hai-chau',
                location: 'Sơn Trà – Hải Châu, Đà Nẵng',
                desc: 'Tổ hợp căn hộ dịch vụ cho thuê cao cấp view sông Hàn với thiết kế nội thất hiện đại, tối ưu công năng khai thác.'
            },
            {
                id: 6,
                driveId: '1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF',
                title: 'NHÀ ANH QUANG – TIỂU LA, HẢI CHÂU, ĐÀ NẴNG',
                category: 'nha-pho',
                categoryName: 'Nhà phố',
                daNangArea: 'hai-chau',
                location: 'Tiểu La, Hải Châu, Đà Nẵng',
                desc: 'Công trình nhà phố trung tâm quận Hải Châu, Đà Nẵng với mặt tiền sang trọng, thi công đúng tiến độ cam kết.'
            },
            {
                id: 7,
                driveId: '1cmI83UnySYJ5Zt1I8A0kB0n94W4XgXgi',
                title: 'CĂN HỘ HỒ BIỂU CHÁNH – HẢI CHÂU, ĐÀ NẴNG',
                category: 'khach-san-can-ho',
                categoryName: 'Khách sạn – Căn hộ – Phòng trọ',
                daNangArea: 'hai-chau',
                location: 'Hồ Biểu Chánh, Hải Châu, Đà Nẵng',
                desc: 'Tòa nhà căn hộ cho thuê kết hợp ở gia đình tại đường Hồ Biểu Chánh, Đà Nẵng do QN HOUSE thi công trọn gói.'
            },
            {
                id: 8,
                driveId: '1A271daJ-s3V5Ws6LRrcDIJ9-Il34FXLq',
                title: 'NHÀ ANH TUẤN – KHU NAM VIỆT Á, ĐÀ NẴNG',
                category: 'nha-pho',
                categoryName: 'Nhà phố',
                daNangArea: 'lien-chieu',
                location: 'Khu Nam Việt Á, Ngũ Hành Sơn, Đà Nẵng',
                desc: 'Thi công phần thô và hoàn thiện trọn gói nhà phố 3 tầng tại Khu đô thị Nam Việt Á, TP. Đà Nẵng.'
            },
            {
                id: 9,
                driveId: '1fqJikC677z_7x28XQaAx3VQD7zqWtiUy',
                title: 'BIỆT THỰ NGHỈ DƯỠNG & KHÁCH SẠN NESTA',
                category: 'biet-thu',
                categoryName: 'Biệt thự',
                daNangArea: 'hoa-vang',
                location: 'Hòa Tiến, Hòa Vang, Đà Nẵng',
                desc: 'Công trình biệt thự sân vườn nghỉ dưỡng cao cấp, kiến trúc nhiệt đới sang trọng và bền vững.'
            },
            {
                id: 10,
                driveId: '1ImsuD--QivYj4IV9Nx10yzvXfmuRmZ8x',
                title: 'THIẾT KẾ & THI CÔNG VĂN PHÒNG HUSBLE',
                category: 'van-phong',
                categoryName: 'Văn phòng',
                daNangArea: 'hai-chau',
                location: 'Hải Châu, Đà Nẵng',
                desc: 'Không gian văn phòng làm việc hiện đại, tối ưu trải nghiệm nhân sự và nhận diện thương hiệu doanh nghiệp.'
            },
            {
                id: 11,
                driveId: '11oZAhO2AsbGFYm1pdsPS5Vtgkd9IP2yZ',
                title: 'NHÀ ANH LỘC – Bầu CẦU, HÒA TIẾN, HÒA VANG, ĐÀ NẴNG',
                category: 'nha-pho',
                categoryName: 'Nhà phố',
                daNangArea: 'hoa-vang',
                location: 'Hòa Tiến, Hòa Vang, Đà Nẵng',
                desc: 'Công trình nhà ở gia đình tiêu chuẩn kỹ thuật cao tại Hòa Tiến – Hòa Vang, Đà Nẵng.'
            },
            {
                id: 12,
                driveId: '1ugKZwI_07LD42SRgLweM-PeRQt9-01Lw',
                title: 'CĂN HỘ ANH THƯ – THI CÔNG CĂN HỘ CHO THUÊ',
                category: 'khach-san-can-ho',
                categoryName: 'Khách sạn – Căn hộ – Phòng trọ',
                daNangArea: 'cam-le',
                location: 'Cẩm Lệ, Đà Nẵng',
                desc: 'Dự án căn hộ dịch vụ cao cấp nhiều tầng, tối ưu diện tích phòng và hệ thống kỹ thuật ME an toàn.'
            },
            {
                id: 13,
                driveId: '1QcvBpsk1aY6aHVHIVrZs9ALP17TUWfkK',
                title: 'NHÀ ANH PHONG – KHU ĐÔ THỊ PHƯỚC LÝ, ĐÀ NẴNG',
                category: 'nha-pho',
                categoryName: 'Nhà phố',
                daNangArea: 'lien-chieu',
                location: 'Khu Phước Lý, Liên Chiểu, Đà Nẵng',
                desc: 'Nhà phố hiện đại 3 tầng thiết kế lệch tầng thông thoáng tại Khu đô thị Phước Lý, Đà Nẵng.'
            },
            {
                id: 14,
                driveId: '1TWxo6uXoJMty8Qsbu4z8HFR5TeLvWph1',
                title: 'TRỤ SỞ & VĂN PHÒNG THÀNH VINH HOLDING',
                category: 'van-phong',
                categoryName: 'Văn phòng',
                daNangArea: 'hoa-vang',
                location: 'Đà Nẵng',
                desc: 'Thiết kế và thi công tòa nhà văn phòng kết hợp showroom trưng bày hiện đại, mặt dựng kính sang trọng.'
            },
            {
                id: 15,
                driveId: '1nv_lSxn0mu-71NGKss3abLOuEMcB-bkQ',
                title: 'KHÁCH SẠN & BIỆT THỰ PHỐ TƯ NGHĨA – QUẢNG NGÃI',
                category: 'biet-thu',
                categoryName: 'Biệt thự',
                daNangArea: 'hoa-vang',
                location: 'Nguyễn Huệ, Tư Nghĩa, Quảng Ngãi – Đà Nẵng',
                desc: 'Công trình tiêu biểu do chi nhánh QN HOUSE thực hiện trọn gói từ thiết kế kiến trúc đến hoàn thiện nội thất.'
            }
        ];

        /* Danh sách Mẫu Thiết Kế (Mẫu nhà phố, Mẫu biệt thự, Mẫu nội thất) */
        const designSamplesData = [
            {
                driveId: '1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA',
                title: 'MẪU THIẾT KẾ NHÀ PHỐ HIỆN ĐẠI 3 TẦNG 5X20M',
                type: 'nha-pho',
                desc: 'Mẫu nhà phố 3 tầng mặt tiền 5m hiện đại, tối ưu thông tầng và sân vườn xanh mát.'
            },
            {
                driveId: '1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF',
                title: 'MẪU THIẾT KẾ NHÀ PHỐ 2 MẶT TIỀN KẾT HỢP KINH DOANH',
                type: 'nha-pho',
                desc: 'Thiết kế nhà phố 2 mặt tiền sang trọng, vừa ở vừa kết hợp văn phòng hoặc kinh doanh.'
            },
            {
                driveId: '1PjtEF4hlMU_42b438GmEQhYZTba75kRJ',
                title: 'MẪU THIẾT KẾ BIỆT THỰ HIỆN ĐẠI SÂN VƯỜN NGHỈ DƯỠNG',
                type: 'biet-thu',
                desc: 'Không gian biệt thự mở kết nối thiên nhiên, hồ cá Koi và phòng khách thông tầng.'
            },
            {
                driveId: '1fqJikC677z_7x28XQaAx3VQD7zqWtiUy',
                title: 'MẪU THIẾT KẾ BIỆT THỰ PHỐ TÂN CỔ ĐIỂN SANG TRỌNG',
                type: 'biet-thu',
                desc: 'Kiến trúc biệt thự tinh tế, bền vững theo thời gian với bố cục công năng chuẩn phong thủy.'
            },
            {
                driveId: '1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS',
                title: 'MẪU THIẾT KẾ NỘI THẤT PHÒNG KHÁCH & BẾP GỖ AN CƯỜNG',
                type: 'noi-that',
                desc: 'Nội thất phòng khách liền bếp hiện đại, sang trọng, tối ưu không gian sinh hoạt gia đình.'
            },
            {
                driveId: '1ImsuD--QivYj4IV9Nx10yzvXfmuRmZ8x',
                title: 'MẪU THIẾT KẾ NỘI THẤT PHÒNG NGỦ MASTER & CĂN HỘ',
                type: 'noi-that',
                desc: 'Thiết kế nội thất phòng ngủ Master ấm cúng, đầy đủ tủ áo kịch trần và bàn trang điểm.'
            },
            {
                driveId: '1QcvBpsk1aY6aHVHIVrZs9ALP17TUWfkK',
                title: 'MẪU THIẾT KẾ NHÀ PHỐ LỆCH TẦNG THÔNG THOÁNG TẠI ĐÀ NẴNG',
                type: 'nha-pho',
                desc: 'Giải pháp kiến trúc lệch tầng đón gió biển và ánh sáng tự nhiên cho nhà phố Đà Nẵng.'
            },
            {
                driveId: '1nv_lSxn0mu-71NGKss3abLOuEMcB-bkQ',
                title: 'MẪU THIẾT KẾ NỘI THẤT BIỆT THỰ & VĂN PHÒNG CAO CẤP',
                type: 'noi-that',
                desc: 'Phối cảnh 3D nội thất đồng bộ từ vật liệu gỗ, đá tự nhiên đến hệ đèn chiếu sáng.'
            }
        ];

        /* Hàm tạo HTML cho từng Card sản phẩm (Không để nhãn dán ở trang chủ, tên sản phẩm đầy đủ không cắt chữ) */
        function createProjectCardHTML(item) {
            const imgUrl = 'https://lh3.googleusercontent.com/d/' + item.driveId + '=w800';
            return `
                <div class="fs-box cursor-pointer" onclick="openProjectModal(${item.id})">
                    <div class="fs-box-image">
                        <img src="${imgUrl}"
                             onerror="handleDriveImgError(this, '${item.driveId}', 'QN+HOUSE')"
                             alt="${item.title}"
                             loading="lazy">
                    </div>
                    <div class="fs-box-text">
                        <div>
                            <h3 class="fs-product-title">${item.title}</h3>
                            <p class="text-[11px] text-gray-500">${item.location}</p>
                        </div>
                        <span class="mt-2 inline-block text-[11px] font-bold text-qn-gold hover:text-qn-navy">
                            Xem thực tế →
                        </span>
                    </div>
                </div>
            `;
        }

        /* Render Công trình thực tế */
        function filterProjects(category) {
            const grid = document.getElementById('projectsGrid');
            const buttons = document.querySelectorAll('#projectFilterBar .fs-cat-btn');
            buttons.forEach(btn => {
                btn.classList.toggle('active', btn.getAttribute('data-cat') === category);
            });

            const filtered = category === 'all'
                ? realProjectsData
                : realProjectsData.filter(item => item.category === category);

            grid.innerHTML = filtered.map(createProjectCardHTML).join('');
        }

        /* Render Dự án tại Đà Nẵng */
        function filterDaNang(area) {
            const grid = document.getElementById('daNangGrid');
            const buttons = document.querySelectorAll('#daNangFilterBar .fs-cat-btn');
            buttons.forEach(btn => {
                btn.classList.toggle('active', btn.getAttribute('data-dn') === area);
            });

            const filtered = area === 'all'
                ? realProjectsData.slice(0, 8)
                : realProjectsData.filter(item => item.daNangArea === area);

            grid.innerHTML = filtered.map(createProjectCardHTML).join('');
        }

        /* Render Mẫu thiết kế */
        function filterDesigns(type) {
            const grid = document.getElementById('designsGrid');
            const buttons = document.querySelectorAll('#designFilterBar .fs-cat-btn');
            buttons.forEach(btn => {
                btn.classList.toggle('active', btn.getAttribute('data-des') === type);
            });

            const filtered = type === 'all'
                ? designSamplesData
                : designSamplesData.filter(item => item.type === type);

            grid.innerHTML = filtered.map(item => {
                const imgUrl = 'https://lh3.googleusercontent.com/d/' + item.driveId + '=w800';
                return `
                    <div class="fs-box">
                        <div class="fs-box-image">
                            <img src="${imgUrl}"
                                 onerror="handleDriveImgError(this, '${item.driveId}', 'MAU+THIET+KE')"
                                 alt="${item.title}"
                                 loading="lazy">
                        </div>
                        <div class="fs-box-text">
                            <div>
                                <h3 class="fs-product-title">${item.title}</h3>
                                <p class="text-[11px] text-gray-600 leading-relaxed">${item.desc}</p>
                            </div>
                            <a href="#yeu-cau-bao-gia" class="mt-2 inline-block text-[11px] font-bold text-qn-gold hover:text-qn-navy">
                                Nhận bản vẽ & Báo giá →
                            </a>
                        </div>
                    </div>
                `;
            }).join('');
        }

        /* Xem chi tiết công trình trong Modal */
        function openProjectModal(projectId) {
            const item = realProjectsData.find(p => p.id === projectId);
            if (!item) return;
            const modal = document.getElementById('projectModal');
            const modalImg = document.getElementById('modalImg');
            document.getElementById('modalTitle').textContent = item.title;
            document.getElementById('modalCat').textContent = item.categoryName + ' | ' + item.location;
            document.getElementById('modalDesc').textContent = item.desc;
            modalImg.removeAttribute('data-retry-step');
            modalImg.onerror = function() {
                handleDriveImgError(modalImg, item.driveId, 'QN+HOUSE');
            };
            modalImg.src = 'https://lh3.googleusercontent.com/d/' + item.driveId + '=w1200';
            modal.classList.remove('hidden');
        }

        function closeProjectModal() {
            document.getElementById('projectModal').classList.add('hidden');
        }

        /* Điều khiển Slider 2 Banner tự trượt chuyên nghiệp */
        let currentBannerIdx = 0;
        let bannerInterval = null;

        function showBannerSlide(index) {
            const slides = document.querySelectorAll('.banner-slide');
            const dots = document.querySelectorAll('.banner-dot');
            if (!slides.length) return;

            currentBannerIdx = (index + slides.length) % slides.length;
            slides.forEach((slide, i) => {
                if (i === currentBannerIdx) {
                    slide.classList.remove('opacity-0', 'z-0', 'pointer-events-none');
                    slide.classList.add('opacity-100', 'z-10');
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0', 'pointer-events-none');
                }
            });

            dots.forEach((dot, i) => {
                if (i === currentBannerIdx) {
                    dot.className = 'banner-dot w-6 h-2 rounded-full bg-qn-gold transition-all';
                } else {
                    dot.className = 'banner-dot w-2.5 h-2 rounded-full bg-white/60 transition-all';
                }
            });
        }

        function changeBannerSlide(step) {
            showBannerSlide(currentBannerIdx + step);
            resetBannerTimer();
        }

        function goToBannerSlide(index) {
            showBannerSlide(index);
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                showBannerSlide(currentBannerIdx + 1);
            }, 5000);
        }

        /* Đổi địa점 Google Maps ngoài trang chủ */
        function switchMapLocation(loc) {
            const iframe = document.getElementById('googleMapIframe');
            const btnDN = document.getElementById('btnMapDN');
            const btnQN = document.getElementById('btnMapQN');
            if (loc === 'danang') {
                iframe.src = 'https://maps.google.com/maps?q=605%20Ho%C3%A0%20Ti%E1%BA%BFn%2C%20Ho%C3%A0%20Vang%2C%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=14&ie=UTF8&iwloc=&output=embed';
                btnDN.className = 'px-2.5 py-1 rounded text-xs font-bold bg-qn-navy text-white';
                btnQN.className = 'px-2.5 py-1 rounded text-xs font-bold bg-white border border-gray-300 text-qn-navy hover:bg-gray-100';
            } else {
                iframe.src = 'https://maps.google.com/maps?q=Nguy%E1%BB%85n%20Hu%E1%BB%87%2C%20T%C6%B0%20Ngh%C4%A9a%2C%20Qu%E1%BA%A3ng%20Ng%C3%A3i&t=&z=14&ie=UTF8&iwloc=&output=embed';
                btnQN.className = 'px-2.5 py-1 rounded text-xs font-bold bg-qn-navy text-white';
                btnDN.className = 'px-2.5 py-1 rounded text-xs font-bold bg-white border border-gray-300 text-qn-navy hover:bg-gray-100';
            }
        }

        /* Chọn gói báo giá tự động điền vào form */
        function selectQuotePackage(pkgName) {
            const noteEl = document.getElementById('qNote');
            if (noteEl) {
                noteEl.value = 'Tôi cần tư vấn chi tiết gói: ' + pkgName;
            }
        }

        /* Xử lý gửi Form Yêu cầu & Báo giá trên trang chủ */
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const type = document.getElementById('qType').value;
            const budget = document.getElementById('qBudget').value;
            const msgBox = document.getElementById('quoteSuccessMsg');

            msgBox.innerHTML = `<i class="fa-solid fa-circle-check mr-1"></i> Cảm ơn <strong>${name}</strong> (${phone})! Yêu cầu tư vấn <strong>${type}</strong> (Mức đầu tư: ${budget}) đã được gửi đến <strong>QN HOUSE</strong>. Kiến trúc sư sẽ liên hệ ngay qua số <strong>0904.106.468</strong>.`;
            msgBox.classList.remove('hidden');
            document.getElementById('quoteForm').reset();
        }

        /* Bật/tắt Menu trên Điện thoại */
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            drawer.classList.toggle('hidden');
        }

        /* Khởi tạo toàn bộ dữ liệu khi tải trang */
        window.onload = function() {
            filterProjects('all');
            filterDaNang('all');
            filterDesigns('all');
            resetBannerTimer();
        };
    </script>
</body>
</html>
