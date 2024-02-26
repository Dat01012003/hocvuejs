<template>
    <div class="service">
        <div class="container">
            <div class="header">
                <h2>Dịch Vụ của chúng tôi</h2>
                <p>Dịch vụ nổi bật chúng tôi cung cấp</p>
            </div>
            <div class="row">
                <div class="item-service">
                    <div class="item-service_small">
                        <div class="img">
                            <img width="96" height="96" alt="ic1"
                                src="https://univn.vn/wp-content/themes/unicreation/lib/images/home/icon1.svg"
                                loading="lazy">
                            <h3 class="h4">Thiết Kế Website</h3>
                            <p class="p1">Dịch vụ thiết kế website chuẩn SEO giá rẻ,tối ưu trải nghiệm, người dùng và thân
                                thiện với mọi trình duyệt</p>
                            <a href="http://localhost:8080/" title="Xem chi tiết">Xem chi tiết</a>
                        </div>

                    </div>
                </div>
                <div class="item-service">
                    <div class="item-service_small">
                        <div class="img">
                            <img width="96" height="96" alt="ic2"
                                src="https://univn.vn/wp-content/themes/unicreation/lib/images/home/icon2.svg"
                                loading="lazy">
                            <h3 class="h4">Hosting Tên Miền</h3>
                            <p class="p1">Đăng ký tên miền, mua Domain đẹp nhanh chóng với giá cực kì ưu đãi kích hoạt chỉ 5
                                phút.Mua hosting tốc độ cao,an toàn phù hợp với cá nhân và doanh nghiệp</p>
                            <a href="http://localhost:8080/" title="Xem chi tiết">Xem chi tiết</a>
                        </div>
                    </div>

                </div>
                <div class="item-service">
                    <div class="item-service_small">
                        <div class="img">
                            <img width="96" height="96" alt="ic3"
                                src="https://univn.vn/wp-content/themes/unicreation/lib/images/home/icon3.svg"
                                loading="lazy">
                            <h3 class="h4">Chiến dịch quảng cáo</h3>
                            <p class="p1">Lựa chọn từ khóa phù hợp,nhắm đúng khách hàng mục tiêu, giá tăng doanh số bán hàng
                                với chi phí quảng cáo thấp nhất</p>
                            <a href="http://localhost:8080/" title="Xem chi tiết">Xem chi tiết</a>
                        </div>
                    </div>
                </div>
                <div class="item-service">
                    <div class="item-service_small">
                        <div class="img">
                            <img width="96" height="96" alt="ic4"
                                src="https://univn.vn/wp-content/themes/unicreation/lib/images/home/icon4.svg"
                                loading="lazy">
                            <h3 class="h4">Bộ nhận diện thương hiệu</h3>
                            <p class="p1">Tư vấn khách hàng lựa chọn.Bộ nhận diện thương hiệu chuyên nghiệp nhất cho doanh
                                nghiệp</p>
                            <a href="http://localhost:8080/" title="Xem chi tiết">Xem chi tiết</a>
                        </div>
                    </div>
                </div>
                <div class="item-service">
                    <div class="item-service_small">
                        <div class="img">
                            <img width="96" height="96" alt="ic5"
                                src="https://univn.vn/wp-content/themes/unicreation/lib/images/home/icon5.svg"
                                loading="lazy">
                            <h3 class="h4">Viết nội dung Website</h3>
                            <p class="p1">Xây dựng nội dung phù hợp với từng sản phẩm, dịch vụ của khách hàng.Đáp ứng chuẩn
                                SEO mang lại hiệu quả cao nhất</p>
                            <a href="http://localhost:8080/" title="Xem chi tiết">Xem chi tiết</a>
                        </div>
                    </div>
                </div>
                <div class="item-service">
                    <div class="item-service_small">
                        <div class="img">
                            <img width="96" height="96" alt="ic5"
                                src="https://univn.vn/wp-content/themes/unicreation/lib/images/home/icon5.svg"
                                loading="lazy">
                            <h3 class="h4">Email tên miền</h3>
                            <p class="p1">Dịch vụ Email tên miền mang đến giải pháp toàn diện: Email mang tên miền riêng,
                                Tốc độ nhanh, Bảo mật cao</p>
                            <a href="http://localhost:8080/" title="Xem chi tiết">Xem chi tiết</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {

}
</script>
<style scoped>
.service {
    width: 1912px;
    height: 900px;
    padding: 60px 0 40px;
    margin: 0;
}

.container {
    max-width: 1200px;
    padding-right: 15px;
    padding-left: 15px;
    margin-right: auto;
    margin-left: auto;
}

.header {
    width: 1170px;
    height: 86.8px;
    text-align: center;
    margin: 0;
    margin-bottom: 30px;

}

h2 {
    letter-spacing: .1rem;
    font-weight: normal;
    text-transform: uppercase;
    /**làm cho chữ bên trong in hoa hết */
    font-size: 36px;
    width: 1170px;
    height: 46.8;
    margin: 0;
    margin-bottom: 5px;

}

p {
    font-weight: normal;
    font-size: 20px;
    width: 1170px;
    height: 32px;
    margin: 0;
    margin-bottom: 20px;
}

.row {
    width: 1200px;
    height: 708px;
    display: flex;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
    margin-right: -15px;
    margin-left: -15px;
    ;

}

.item-service {
    width: 390px;
    height: 336px;
    margin: 0;
    padding-left: 15px;
    padding-right: 15px;

    margin-bottom: 30px;
    box-sizing: border-box;

}

.item-service_small {
    width: 100%;
    height: 100%;
    border: 1px solid #edf1f1;
    padding: 20px;
    margin: 0;
}

.img {
    width: 308px;
    height: 96px;
    text-align: center;

}

img {
    cursor: pointer;
    width: 96px;
    margin: 0 0 20px;

}

.h4 {
    width: 100%;
    height: 24px;
    margin: 0 0 10px;
}

.p1 {
    width: 100%;
    height: 72px;
    font-size: 16.8px;
    color: #888888;
    margin: 0 0 20px;
}</style>