<template>
  <div class="header-main">
    <div class="between">
      <div class="container">
        <img src="../assets/logo.svg">
      </div>
      <div class="menu-main">
        <ul>
          <li class="abc"><a href="#">Giao diện theo chủ đề</a>
            <ul class="sub-menu">
              <li><a href="#">Giới thiệu công ty</a></li>
              <li><a href="#">Thương mại điện tử</a></li>
              <li><a href="#">Bất động sản</a></li>
              <li><a href="#">Ô tô</a></li>
              <li><a href="#">Nội thất</a></li>
              <li><a href="#">Xây dụng</a></li>
              <li><a href="#">Du lịch</a></li>
              <li><a href="#">Du học</a></li>
              <li><a href="#">Dịch vụ khác</a></li>
            </ul>
          </li>
          <li class="ab"><a href="#">Giao diện theo gói</a>
            <ul class="subb-menu">
              <li><a href="#">Gói startup</a></li>
              <li><a href="#">Gói Pro</a></li>
              <li><a href="#">Gói dự án Vip</a></li>
            </ul>
          </li>
          <li class="abd"><a href="#">Dịch vụ cung cấp</a>
            <ul class="sub-menu1">
              <li><a href="#">Thiết kế website trọn gói</a></li>
              <li><a href="#">Dịch vụ quảng cáo</a></li>
              <li><a href="#">Dịch vụ hosting</a></li>
              <li><a href="#">Dịch vụ VPS giá rẻ</a></li>
              <li><a href="#">Dịch vụ VPS PRO SSD</a></li>
              <li><a href="#">Dịch vụ VPS NVME</a></li>
              <li><a href="#">Dịch vụ tên miền</a></li>
              <li><a href="#">Dịch vụ email hosting</a></li>
              <li><a href="#">Dịch vụ Email Google</a></li>
              <li><a href="#">Nhận diện thương hiệu</a></li>
              <li><a href="#">Viết nội dung website</a></li>
              <li><a href="#">Dịch vụ FaceBook</a></li>
            </ul>
          </li>
        </ul>
      </div>
      <div class="dat">Đăng ký tư vấn</div>
    </div>
  </div>
</template>
<script>
export default {

}
</script>
<style scoped> /* stype mỗi phần này thôi*/
 img {
   width: 100%;
   height: 58.09px;
   padding: 0;
   margin: 0;
 }

 .header-main {
   display: flex;
   /* Sử dụng flexbox để căn giữa theo chiều dọc và ngang */
   position: relative;
   justify-content: center;
   width: 1912px;
   height: 91px;
   padding: 0;
   margin: 0;
 }

 .between {
   align-items: center;
   display: flex;
   /* Sử dụng flexbox để căn giữa theo chiều dọc và ngang */
   width: 1200px;
   height: 90px;
   padding: 0;
   margin: 0;
 }

 .container {
   width: 160px;
   height: 90px;
   padding: 0;
   margin: 0;
   display: flex;
   /* Sử dụng flexbox để căn giữa theo chiều dọc và ngang */
   align-items: center;
   /* Căn giữa theo chiều dọc */
 }

 .menu-main {
   line-height: 90px;
   width: 700px;
   height: 100%;
   padding: 0;
   margin: 0;
   display: flex;
   justify-content: center;

 }

 .abc {
   color: #333333;
   width: 186px;
   height: 90px;
 }

 .abc a :hover {
   color: #06b5ad;
   /* Màu xanh khi di chuột vào */
 }

 .ab {
   width: 159px;
   height: 100%;
 }

 .abd {
   width: 151px;
   height: 100%;
 }

 a {

   text-decoration: none;
   color: #333333;
 }


 ul {
   list-style: none;
   margin: 0;
   padding: 0;
   display: flex;
   flex-wrap: wrap;
 }

 .dat {
   padding: 0;
   margin: 0;
 }
 .sub-menu {
   width: 700px;
   height: 142.4px;
   background: white;
   border-top: 2px solid #06b5ad;
 }

 .abc .sub-menu li {

   margin-top: -17px;
   text-align: justify;
   /** Sắp xếp nội dung cho các dòng có chiều rộng bằng nhau */
   display: block;
   max-height: 40px;
   text-decoration: none;
   color: #333333;

 }

 .sub-menu li a:hover {
   color: #06b5ad;
 }

 .sub-menu li {
  text-indent: 30px;
   text-align: center;
   width: 233.2px;
   height: 47.4px;
 }

 body {
   margin: 0;
 }

 .sub-menu a {
   text-decoration: none;
 }

 .abc:hover .sub-menu li {
   display: block;
 }


 .subb-menu {
  border-top: 2px solid #06b5ad;
   width: 210px;
   height: 140px;
   background: white;
 }

 .subb-menu li {
  text-indent: 30px;
   width: 210px;
   height: 46.5px;
 }

 .subb-menu ul {
   padding: 0;
   border: 0;
   
 }

 .subb-menu li a {
   margin-top: -17px;
   text-align: justify;
   max-height: 40px;
   text-decoration: none;
 }

 .ab:hover .subb-menu li a {
   display: block;
 }

 .subb-menu li a:hover {
   color: #06b5ad;
 }

 .abc .sub-menu {
   visibility: hidden;
   /*để ẩn các phần tử khi chúng không được hover */
   position: absolute;
   /*để kiểm soát đc vị trí */
   z-index: 1;
   /*để đẩm bảo rẳng sub-mune hiện thị trên các phần tử khác */
   opacity: 0;
   /* để làm cho phần tử ban đầu trở nên ko thấy */

 }

 .abc:hover .sub-menu {
   visibility: visible;
   opacity: 1;
 }

 .ab .subb-menu {
   visibility: hidden;
   position: absolute;
   z-index: 1;
   opacity: 0;
   transition: opacity 0.3s;
 }

 .ab:hover .subb-menu {
   visibility: visible;
   opacity: 1;
 }

 .sub-menu1 {
   width: 700px;
   height: 182px;
   background: white;
   border-top: 2px solid #06b5ad;

 }

 .sub-menu1 li {
  text-indent: 30px;
   text-align: center;
   width: 226px;
   height: 40px;
 }

 .abd .sub-menu1 li {
   margin-top: -17px;
   max-height: 40px;
   text-align: justify;
   display: block;
   text-decoration: none;
   color: #333333;
 }

 .abd :hover .sub-menu1 li a {
   display: block;
 }

 .sub-menu1 li a:hover {
   color: #06b5ad;
 }

 .abd .sub-menu1 {
   visibility: hidden;
   position: absolute;
   z-index: 1;
   opacity: 0;
   transition: opacity 0.3s;
 }

 .abd:hover .sub-menu1 {
   visibility: visible;
   opacity: 1;
 }
 .header-main .between >.sub-menu1 {
  display: flex; /* Sử dụng flexbox để căn giữa theo chiều dọc và ngang */
  justify-content: center; /* Căn giữa theo chiều ngang */
  align-items: center; /* Căn giữa theo chiều dọc */
   position: relative;
 }

 </style>