# doanka
kaka

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>S-Phone</title>
    <link rel="icon" href="./css/img/logo.jpg">
    <link rel="stylesheet" href="./css/base.css">
    <link rel="stylesheet" href="./css/main.css">
    <link rel="stylesheet" href="./css/grid.css">
    <link rel="stylesheet" href="./css/responsive.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css">
</head>

<body">
    <!-- all information product S-Phone  -->
    <div id="app">
        <div class="header">
            <div class="header__container grid wide">
                <div class="header__menu">
                    <div class="mobile-menu">
                        <i class="fa-solid fa-bars"></i>
                    </div>
                    <div class="header__heading">
                        <a href="./index.html" class="heading-logo">
                            <div class="logo-title animationLeft delay-02">S</div>
                            <p class="logo-nav animationLeft delay-04">Phone</p>
                        </a>
                    </div>

                    <div class="menu-container">
                        <ul class="menu-list">
                            <li class="menu-list__item none menu-list__item--view  animationLeft delay-06">
                                <a class="menu-list__item-link" href="">Trang Chủ</a>
                            </li>
                            <li class="menu-list__item none menu-list__cellphone   animationLeft delay-08">
                                <a href="#cellphone" class="menu-list__item-link ">Điện Thoại</a>
                                <i class=" fa-sharp fa-solid fa-caret-down"></i>
                                <ul class="menu__child">
                                    <li onclick="listIP()" class="menu__child-item ani-dropdown delay-01"><a class="menu__child-item__link"
                                            href="#">iPhone</a></li>
                                    <li onclick="listSS()" class="menu__child-item ani-dropdown delay-02"><a class="menu__child-item__link"
                                            href="#">Samsung</a></li>
                                    <li onclick="listOP()" class="menu__child-item ani-dropdown delay-03"><a class="menu__child-item__link"
                                            href="#">OPPO</a></li>
                                    <li class="menu__child-item ani-dropdown delay-04"><a class="menu__child-item__link"
                                            href="#">OnePlus</a></li>
                                    <li class="menu__child-item ani-dropdown delay-05"><a class="menu__child-item__link"
                                            href="#">Xiomi</a></li>
                                    <li class="menu__child-item ani-dropdown delay-06"><a class="menu__child-item__link"
                                            href="#">Phụ Kiện</a>
                                    </li>
                                </ul>
                            </li>

                            <li class="menu-list__item none  animationLeft delay-1 "><a class="menu-list__item-link"
                                    href="#tablet-laptop">Tablet, Laptop</a>
                            </li>
                            <li class="menu-list__item none menu-list__item-accessory  animationLeft delay-12 ">
                                <a class="menu-list__item-link" href="#accessory">Phụ Kiện
                                    <i class=" fa-sharp fa-solid fa-caret-down"></i>
                                    <ul class="menu__child-accessory">
                                        <li class="menu__child-item ani-dropdown delay-01"><a
                                                class="menu__child-item__link" href="#">Cáp, Sạc</a>
                                        </li>
                                        <li class="menu__child-item ani-dropdown delay-02"><a
                                                class="menu__child-item__link" href="#">Ốp Lưng</a>
                                        </li>
                                        <li class="menu__child-item ani-dropdown delay-03"><a
                                                class="menu__child-item__link" href="#">Cường
                                                Lực</a></li>
                                        <li class="menu__child-item ani-dropdown delay-04"><a
                                                class="menu__child-item__link" href="#">Dán Màn
                                                Hình</a></li>
                                        <li class="menu__child-item ani-dropdown delay-05"><a
                                                class="menu__child-item__link" href="#">Pin Dự </a>
                                        </li>
                                        <li class="menu__child-item ani-dropdown delay-06"><a
                                                class="menu__child-item__link" href="#">Thẻ Nhớ</a>
                                        </li>
                                    </ul>
                                </a>
                            </li>

                        </ul>
                    </div>
                </div>
                <div class="header__logIn">
                    <form class="header__search animationRight delay-08">
                        <input type="search" placeholder="Tìm Kiếm" class="search">
                        <button class="search__btn">
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </button>
                    </form>

                    <div class="header-cart animationRight delay-06">
                        <i class="fa-solid fa-bag-shopping"></i>
                        <div class="amount-cart">
                        </div>
                            <div class="bag-product-container">
                            <ul class="list-bag-product">
                                
                            </ul>
                            <div class="bag-product-all">
                                <div class="bag-product-all-seening">
                                    <button class="btn btn-seening">
                                        <h3> Xem Tất Cả </h3>
                                    </button>
                                    <div class="count-SUM">
                                        
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                
                    <div class="login animationRight delay-04">
                        <div class="login--box">
                            <div class="avatar__login">
                                <i class="fa-solid fa-user"></i>
                            </div>
                            <ul class="list-login">
                                <li class="login-item js_lognIn">Đăng Nhập</li>
                                <li class="login-item js_lognUp">Đăng Ký</li>
                                <li class="login-item">Trợ Giúp</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>

     
        <!-- </div>
        <div class="snowflakes" aria-hidden="true">
            <div class="snowflake"><img src="./css/img/flower1.webp" alt=""></div>
            <div class="snowflake"><img src="./css/img/flower2.webp" alt=""></div>
            <div class="snowflake"><img src="./css/img/flower1.webp" alt=""></div>
            <div class="snowflake"><img src="./css/img/flower2.webp" alt=""></div>
            <div class="snowflake"><img src="./css/img/flower1.webp" alt=""></div>
            <div class="snowflake"><img src="./css/img/flower2.webp" alt=""></div>
            <div class="snowflake"><img src="./css/img/flower1.webp" alt=""></div>
            <div class="snowflake"><img src="./css/img/flower2.webp" alt=""></div>
            <div class="snowflake"><img src="./css/img/flower1.webp" alt=""></div>
            <div class="snowflake"><img src="./css/img/flower2.webp" alt=""></div>
            <div class="snowflake"><img src="./css/img/flower1.webp" alt=""></div>
            <div class="snowflake"><img src="./css/img/flower2.webp" alt=""></div>
        </div>  -->
        <div class="content">

            <!-- content slider  -->
            <div class="content__background" style="background-image: url(./css/img/ip14-8.jpg) ;">
                <div class="content-welcome">
                    <div class="welcome-title  animationTop delay-03" data-glitch="Welcome To S-Phone">Welcome To S-Phone</div>
                </div>

                <div class="getTime">
                    <div class="hour">
                        00
                    </div>
                    <div class="minutes">
                        00
                    </div>
                    <div class="seconds">
                        00
                    </div>
                </div>
                <div class="slider-text">
                    <div class="notification">
                        <i class="fa-solid fa-bullhorn"></i>
                    </div>

                    <div class="box-text-list">
                        <div class="content-item"><a href="#" class="content-item-link">* iPhone 14 Tuyệt vời ngất trời
                                ưu đãi đến 8.500.000đ sẵn sàng mua ngay</a></div>
                        <div class="content-item"><a href="#" class="content-item-link">* Galaxy Z fold 3 giá sốc
                                26.990.000 lên đời trợ giá 1.000.000đ</a></div>
                        <div class="content-item"><a href="#" class="content-item-link">* Watch 2022 series 8 | SE |
                                Ultra Ưu đãi đến 3.500.000đ</a></div>
                        <div class="content-item"><a href="#" class="content-item-link">* ƯU ĐÃI THANH TOÁN IPHONE 14
                                SERIES - GIẢM ĐẾN 2 TRIỆU</a></div>
                    </div>
                </div>
            </div>

            <!-- event  -->
           
            <!-- cellphone-container -->
            <div class="grid wide">
                <div id="cellphone">
                    <!-- html render interface product iphone -->
                    <div class="position-btn ">
                        <div class="box-head-parent">
                            <h1 class="title-heading">iPhone</h1>
                            <button onclick="listIP()" class="btn btn-seen-product">Xem Tất Cả</button>
                        </div>
                        <div class="scroll-box js-scroll-iphone">
                            <div class="list-produc js-iphone">
                            </div>
                        </div>
                        <div class="box-click-btn">
                            <button class="btn-left js-left-iphone btn-active">
                                <i class="fa-solid fa-angles-left"></i>
                            </button>
                            <button class="btn-right js-right-iphone btn-active">
                                <i class="fa-solid fa-angles-right"></i>
                            </button>
                        </div>
                    </div>
                    <!-- html render interface product samsung  -->
                    <div class="position-btn ">
                        <div class="box-head-parent">
                            <h1 class="title-heading">SamSung</h1>
                            <button onclick="listSS()" class="btn btn-seen-product">Xem Tất Cả</button>
                        </div>
                        <div class="scroll-box js-scroll-samsung">
                            <div class="list-produc js-samsung">
                            </div>
                            <div class="box-click-btn">
                                <button class="btn-left js-left-samsung btn-active">
                                    <i class="fa-solid fa-angles-left"></i>
                                </button>
                                <button class="btn-right js-right-samsung btn-active">
                                    <i class="fa-solid fa-angles-right"></i>
                                </button>
                            </div>
                        </div>
                    </div>
                    <!-- html render interface product Oppo  -->
                    <div class="position-btn ">
                        <div class="box-head-parent">
                            <h1 class="title-heading">Oppo</h1>
                            <button onclick="listOP()" class="btn btn-seen-product">Xem Tất Cả</button>
                        </div>

                        <div class="scroll-box js-scroll-oppo">
                            <div class="list-produc js-oppo">
                            </div>
                            <div class="box-click-btn">
                                <button class="btn-left js-left-oppo btn-active">
                                    <i class="fa-solid fa-angles-left"></i>
                                </button>
                                <button class="btn-right js-right-oppo btn-active">
                                    <i class="fa-solid fa-angles-right"></i>
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- content slider video -->
                    <div class="scrol row">
                        <div class="scrol-item col l-2-4 m-2-4 c-2-4 active-bg">iPhone</div>
                        <div class="scrol-item col l-2-4 m-2-4 c-2-4 ">SamSung</div>
                        <div class="scrol-item col l-2-4 m-2-4 c-2-4 ">Oppo</div>
                        <div class="scrol-item col l-2-4 m-2-4 c-2-4 ">OnePlus</div>
                        <div class="scrol-item col l-2-4 m-2-4 c-2-4 ">Xiomi</div>
                        <div class="active"></div>
                    </div>
                    <div class="page">
                        <div class="video active-page">
                            <video width="100%" height="100%" autoplay loop muted>
                                <source src="css/video/videoApple.mp4" type="video/mp4">
                            </video>
                        </div>
                        <div class="video">
                            <video width="100%" height="100%" autoplay loop muted>
                                <source src="css/video//videoSamsung.mp4" type="video/mp4">
                            </video>
                        </div>

                        <div class="video">
                            <video width="100%" height="100%" autoplay loop muted>
                                <source src="css/video/videoOppo.mp4" type="video/mp4">
                            </video>
                        </div>

                        <div class="video">
                            <video width="100%" height="100%" autoplay loop muted>
                                <source src="css/video/videoOneplus.mp4" type="video/mp4">
                            </video>
                        </div>

                        <div class="video">
                            <video width="100%" height="100%" autoplay loop muted>
                                <source src="css/video/videosamsungfix.mp4" type="video/mp4">
                            </video>
                        </div>
                    </div>
                <!-- ipad laptop product  -->
                <div id="tablet-laptop" class="product-tablet">
                    <div class="product-box">
                        <div class="box-head-parent">
                            <h1 class="title-heading">iPad</h1>
                            <button class="btn btn-seen-product">Xem Tất Cả</button>
                        </div>
                        <div class="row js-tablet">
                        </div>
                        <button onclick="ShowTablet()" class="btn btn-seen-product js-btn-tablet">Xem Thêm </button>
                    </div>


                    <!-- laptop product s-phone -->
                    <div class="product-box">
                        <div class="box-head-parent">
                            <h1 class="title-heading">Laptop</h1>
                            <button class="btn btn-seen-product">Xem Tất Cả</button>
                        </div>
                        <div class="row js-laptop ">
                        </div>
                        <button onclick="ShowLabtop()" class="btn btn-seen-product js-btn-laptop ">Xem Thêm </button>
                    </div>
                </div>

                <div id="accessory" class="accessory-container">
                    <div class="accessory-title animationTop delay-02">
                        <h2>THIẾT BỊ - PHỤ KIỆN</h2>
                    </div>
                    <div class="row">
                        <div class="accessory-item col l-2 m-3 c-6 animationTop delay-01">
                            <span>Cáp, sạc</span>
                            <a href="#" class="accessory-item_link"
                                style="background-image:url(./css/img/capsac1.jpg) ;">
                            </a>
                        </div>

                        <div class="accessory-item col l-2 m-3 c-6 animationTop delay-02">
                            <span>Ốp lưng</span>
                            <a href="#" class="accessory-item_link"
                                style="background-image:url(./css/img/oplung.png) ;">
                            </a>
                        </div>

                        <div class="accessory-item col l-2 m-3 c-6 animationTop delay-03">
                            <span>Cường lực </span>
                            <a href="#" class="accessory-item_link"
                                style="background-image:url(./css/img/cuongluc.png) ;">
                            </a>
                        </div>

                        <div class="accessory-item col l-2 m-3 c-6 animationTop delay-04">
                            <span>Pin dự phòng</span>
                            <a href="#" class="accessory-item_link"
                                style="background-image:url(./css/img/pinduphong.jpg) ;">
                            </a>
                        </div>

                        <div class="accessory-item col l-2 m-3 c-6 animationTop delay-05">
                            <span>Thiết bị mạng </span>
                            <a href="#" class="accessory-item_link"
                                style="background-image:url(./css/img/thietbimang.png) ;">
                            </a>
                        </div>

                        <div class="accessory-item col l-2 m-3 c-6 animationTop delay-06">
                            <span>Chuột, bàn phím</span>
                            <a href="#" class="accessory-item_link" style="background-image:url(./css/img/chuot.png) ;">
                            </a>
                        </div>

                        <div class="accessory-item col l-2 m-3 c-6 animationTop delay-07">
                            <span>Sim 4G</span>
                            <a href="#" class="accessory-item_link" style="background-image:url(./css/img/sim.png) ;">
                            </a>
                        </div>

                        <div class="accessory-item col l-2 m-3 c-6 animationTop delay-08">
                            <span>Phụ kiện laptop </span>
                            <a href="#" class="accessory-item_link"
                                style="background-image:url(./css/img/phukienlaptops.png) ;">
                            </a>
                        </div>

                        <div class="accessory-item col l-2 m-3 c-6 animationTop delay-09">
                            <span>Ba Lô </span>
                            <a href="#" class="accessory-item_link"
                                style="background-image:url(./css/img/balos.webp) ;">
                            </a>
                        </div>

                        <div class="accessory-item col l-2 m-3 c-6 animationTop delay-1">
                            <span>Ổ cứng di động </span>
                            <a href="#" class="accessory-item_link"
                                style="background-image:url(./css/img/ocungdidng.webp) ;">
                            </a>
                        </div>

                        <div class="accessory-item col l-2 m-3 c-6 animationTop delay-12">
                            <span>Thẻ nhớ, USB</span>
                            <a href="#" class="accessory-item_link" style="background-image:url(./css/img/usb.png) ;">
                            </a>
                        </div>

                        <div class="accessory-item col l-2 m-3 c-6 animationTop delay-13">
                            <span>Camera </span>
                            <a href="#" class="accessory-item_link"
                                style="background-image:url(./css/img/camera.png) ;">
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>


        <div id="list">     
            <div class="list-product-iphone grid wide">       
                <button onclick="showNone()" class="btn btn-seen-product">Trang Chủ > IPhone</button>
                <div class="pr-scroll">    
                        <img src="./css/img/ip-2-list.webp" alt="" class="img-item">
                        <img src="./css/img/ip-1-list.webp" alt="" class="img-item">
                        <img src="./css/img/ip-2-list.webp" alt="" class="img-item">
                        <img src="./css/img/ip-1-list.webp" alt="" class="img-item">
                        <img src="./css/img/ip-2-list.webp" alt="" class="img-item">
                </div>
                <div id="tablet-laptop" class="product-tablet">
                    <div class="product-box">
                        <div class="box-head-parent">
                            <h1 class="title-heading">iPhone</h1>        
                        </div>
                        <div class="row js-list-iphone">
                        </div>
                    </div>
                </div>
            </div>


            <div class="list-product-samsung grid wide">     
                <button onclick="showNone()" class="btn btn-seen-product">Trang Chủ > SamSung</button>

                <div class="pr-scroll">    
                        <img src="./css/img/ss-1-list.webp" alt="" class="img-item">
                        <img src="./css/img/ss-2-list.webp" alt="" class="img-item">
                        <img src="./css/img/ss-3-list.webp" alt="" class="img-item">
                        <img src="./css/img/ss-4-list.webp" alt="" class="img-item">
                        <img src="./css/img/ss-2-list.webp" alt="" class="img-item">
                </div>
                <div id="tablet-laptop" class="product-tablet">
                    <div class="product-box">
                        <div class="box-head-parent">
                            <h1 class="title-heading">SamSung</h1>        
                        </div>
                        <div class="row js-list-samsung">
                        </div>
                    </div>
                </div>

            </div>


            <div class="list-product-oppo grid wide">       
                <button onclick="showNone()" class="btn btn-seen-product">Trang Chủ > OPPO</button>

                <div class="pr-scroll">    
                        <img src="./css/img/ss-1-list.webp" alt="" class="img-item">
                        <img src="./css/img/ss-2-list.webp" alt="" class="img-item">
                        <img src="./css/img/ss-3-list.webp" alt="" class="img-item">
                        <img src="./css/img/ss-4-list.webp" alt="" class="img-item">
                        <img src="./css/img/ss-2-list.webp" alt="" class="img-item">
                </div>
                <div id="tablet-laptop" class="product-tablet">
                    <div class="product-box">
                        <div class="box-head-parent">
                            <h1 class="title-heading">Oppo</h1>        
                        </div>
                        <div class="row js-list-oppo">
                        </div>
                    </div>
                </div>

            </div>
        </div>

        <div class="footer">
            <div class="grid wide">
                <div class="row">
                    <div class="logo-item col l-2 m-4 c-6">
                        <img src="./css/img/logo-apple-removebg-preview.png" class="logo-img" alt="">
                    </div>

                    <div class="logo-item col l-2 m-4 c-6">
                        <img src="./css/img/logo-samsung.png" class="logo-img" alt="">
                    </div>

                    <div class="logo-item col l-2 m-4 c-6">
                        <img src="./css/img/logo-oneplus.png" class="logo-img" alt="">
                    </div>

                    <div class="logo-item col l-2 m-4 c-6">
                        <img src="./css/img/logo-oppo.png" class="logo-img" alt="">
                    </div>

                    <div class="logo-item col l-2 m-4 c-6">
                        <img src="./css/img/logo-asus.png" class="logo-img" alt="">
                    </div>

                    <div class="logo-item col l-2 m-4 c-6">
                        <img src="./css/img/logo-xiaomi.png" class="logo-img" alt="">
                    </div>

                </div>

                <div class="row">
                    <div class="logo-item col l-3 m-6 c-6">
                        <ul class="list-suport">
                            <li class="item-suport">
                                <a href="#" class="suport-link">Mua hàng và thanh toán online </a>
                            </li>

                            <li class="item-suport">
                                <a href="#" class="suport-link">Mua hàng trả góp online </a>
                            </li>

                            <li class="item-suport">
                                <a href="#" class="suport-link">Xem mọi thông tin khuyến mãi </a>
                            </li>

                            <li class="item-suport">
                                <a href="#" class="suport-link">Dịch vụ và bảo hành điện thoại </a>
                            </li>
                        </ul>
                    </div>

                    <div class="logo-item col l-3 m-6 c-6">
                        <ul class="list-suport">
                            <li class="item-suport">
                                <a href="" class="suport-link"> <i
                                        class="fa-solid fa-envelope"></i> Email</a>
                            </li>
                            <li class="item-suport">
                                <a href="" target="_blank" class="suport-link"> <i
                                        class="fa-brands fa-facebook"></i> Facebook </a>
                            </li>
                            <li class="item-suport">
                                <a href="" class="suport-link">Zalo: </a>
                            </li>
                        </ul>
                    </div>
                    <div class="logo-item col l-3 m-6 c-6">
                        <h2>Phương Thức Thanh Toán </h2>
                        <ul class="list-suport row">
                            <li class="item-suport l-3  m-6 c-6 ">
                                <img src="./css/img/bank-zalo.png" alt="">
                            </li>
                            <li class="item-suport l-3 m-6 c-6 ">
                                <img src="./css/img/bank-alepay.png" alt="">
                            </li>

                            <li class="item-suport l-3 m-6 c-6 ">
                                <img src="./css/img/bank-onepay.png" alt="">
                            </li>

                            <li class="item-suport l-3 m-6 c-6 ">
                                <img src="./css/img/bank-vnpay.png" alt="">
                            </li>
                        </ul>
                    </div>
                    <div class="logo-item col l-3 m-6 c-6">
                    <div class="video video2">
                       
                    </div>
                    </div>
                </div>
            </div>
          
        </div>

    </div>


    <!-- onloading start in S-Phone  -->
    <div class="onloading">
        <div class="spinner"></div>
    </div>
    <!-- double click prev top and click contact  -->
    <!----> <div class="contact-btn">
        <div class="fixed-contact">
            <div title="Hoàng Hân " class="contact  zalo">
                <a href="https://zalo.me/0388518340" target="_blank">
                    <img class="img-logo-zalo" src="./css/img/logozalo.png" alt="">
                </a>
            </div>
            <div title="0943217670" class="contact  phone">
                <a class="" href="tel://0388518340">
                    <img class="img-logo-zalo" src="./css/img/logo-phone.png" alt="">
                </a>
            </div>
            <div title="dtc21h4802010561@ictu.edu.vn" class="contact  email">
                <a href="mailto:dtc21h4802010561@ictu.edu.vn" target="_blank">
                    <img class="img-logo-zalo" src="./css/img/logo-email.png" alt="">
                </a>
            </div>
        </div>
        <button onclick="showContact()" ondblclick="upTop()" class="contact up-header">
            <i class="fa-solid fa-circle-chevron-up"></i>
        </button>
    </div> 
    <!-- modal login create account  -->
    <div class="modal">
        <div class="modal-lognUp">
            <div class="modal__introduce">
                <h1 class="modal-welcome">Welcome</h1>
                <p class="modal-text">To keep connected with us please login with your personal info</p>
                <button class="modal-signup js-btn-Up">Sign In</button>
            </div>
            <div class="modal__container">
                <div class="modal-header">
                    <h1 class="modal-header__signUp">Đăng Ký </h1>
                    <div class="modal-icon-login">
                        <div class="modal-connected"><a href="#" class="modal-connected-link"><i
                                    class="fa-brands fa-facebook"></i></a></div>
                        <div class="modal-connected"><a href="#" class="modal-connected-link"><i
                                    class="fa-brands fa-google-plus-g"></i></a></div>
                        <div class="modal-connected"><a href="#" class="modal-connected-link"><i
                                    class="fa-brands fa-square-instagram"></i></a></div>
                    </div>

                </div>
                <div class="modal-body">
                    <p class="modal-body__text">Hoặc đăng ký bằng email của bạn</p>

                    <form action="" class="modal-form">
                        <input type="text" placeholder="Name">
                        <input type="email" placeholder="Email">
                        <input type="password" placeholder="Password">

                        <button class="modal-signup modal-signIn ">Đăng Ký</button>
                    </form>
                </div>
                <div class="modal-footer">

                </div>
            </div>
        </div>


        <div class="modal-lognIn">
            <div class="modal__container container-lognIn">
                <div class="modal-header">
                    <h1 class="modal-header__signUp modal-header__signIn">Đăng Nhập</h1>
                    <div class="modal-icon-login">
                        <div class="modal-connected"><a href="#" class="modal-connected-link"><i
                                    class="fa-brands fa-facebook"></i></a></div>
                        <div class="modal-connected"><a href="#" class="modal-connected-link"><i
                                    class="fa-brands fa-google-plus-g"></i></a></div>
                        <div class="modal-connected"><a href="#" class="modal-connected-link"><i
                                    class="fa-brands fa-square-instagram"></i></a></div>
                    </div>

                </div>
                <div class="modal-body">
                    <p class="modal-body__text">Hoặc sử dụng tài khoản đã có</p>
                    <form action="" class="modal-form">
                        <input type="email" placeholder="Email">
                        <input type="password" placeholder="Password">
                        <a href="#" class="modal-getpassword">Lấy mật khẩu?</a>
                        <button class="modal-signup modal-signIn ">Đăng Nhập</button>
                    </form>
                </div>
                <div class="modal-footer">

                </div>
            </div>

            <div class="modal__introduce introduce-lognIn">
                <h1 class="modal-welcome">Hello, Friend!</h1>
                <p class="modal-text">Enter your personal details and start journey with us</p>
                <button class="modal-signup js-btn-In">Sign Up</button>
            </div>

        </div>
    </div>
    <!-- toast notication add product in cart  -->
    <div id="toast">
    </div>


    <script src="./javascript/FakeAPI.js"></script>
    <script src="./javascript/main.js"></script>
    </body>

</html>
