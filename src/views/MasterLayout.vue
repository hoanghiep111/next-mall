<template>
  <div>
    <SiteHeader></SiteHeader>
    <main>
      <!-- Home page -->
      <section id="hero">
        <h4>Giao dịch trong Ưu đãi</h4>
        <h2>Ưu đãi siêu giá trị</h2>
        <h1>Trên tất cả sản phẩm</h1>
        <p>Tiết kiệm nhiều hơn với phiếu giảm giá lên tới 70%</p>
        <button>Mua Ngay</button>
      </section>

      <!-- feature tính năng -->
      <section id="feature" class="section-p1">
        <div class="fe-box">
          <img src="/frontend/img/features/f1.png" alt="" />
          <h6>Miễn phí vận chuyển</h6>
        </div>
      </section>

      <!-- Product -->
      <section id="product1" class="section-p1">
        <h2>Sản Phẩm Nổi Bật</h2>
        <p>Bộ sưu tập hiện đại</p>
        <div class="pro-container">
          <div class="pro">
            <img
              src="/frontend/img/products/f1.jpg"
              alt="Carton Asttrount T-shirt"
            />
            <div class="des">
              <span>adidas</span>
              <h5>Carton Asttrount T-shirt</h5>
              <div class="star">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
              </div>
              <h4>$78</h4>
            </div>
            <a href="#"><i class="fa-solid fa-cart-plus cart"></i></a>
          </div>
        </div>
      </section>

      <!-- Banner lớn -->
      <section id="banner" class="section-m1">
        <h4>Dịch vụ sửa chữa</h4>
        <h2>Lên đến <span>Giảm 70%</span> - Tất cả phụ kiện</h2>
        <button class="normal">Tìm hiểu thêm</button>
      </section>

      <!-- Sản phẩm mới -->
      <section id="product1" class="section-p1">
        <h2>Hàng mới về</h2>
        <p>Bộ sưu tập hiện đại</p>
        <div class="pro-container">
          <div class="pro">
            <img
              src="/frontend/img/products/n1.jpg"
              alt="Carton Asttrount T-shirt"
            />
            <div class="des">
              <span>adidas</span>
              <h5>Carton Asttrount T-shirt</h5>
              <div class="star">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
              </div>
              <h4>$78</h4>
            </div>
            <a href="#"><i class="fa-solid fa-cart-plus cart"></i></a>
          </div>
        </div>
      </section>

      <!-- Banner nhỏ -->
      <section id="sm-banner" class="section-p1">
        <div class="banner-box">
          <h4>Ưu đãi điên rồ</h4>
          <h2>Mua 1 tặng 1</h2>
          <span>Đang được bán tại Store</span>
          <button class="white">Tìm hiểu thêm</button>
        </div>
        <div class="banner-box banner-box2">
          <h4>Xuân / Hè</h4>
          <h2>Mùa sắp tới</h2>
          <span>Đang được bán tại Store</span>
          <button class="white">Tìm hiểu thêm</button>
        </div>
      </section>

      <!-- 3 banner nhỏ -->
      <section id="banner3">
        <div class="banner-box">
          <h2>MÙA GIẢM GIÁ</h2>
          <h3>Bộ sưu tập mùa đông giảm - 50%</h3>
        </div>
        <div class="banner-box banner-box2">
          <h2>Bộ sưu tập</h2>
          <h3>Xuân / Hè</h3>
        </div>
        <div class="banner-box banner-box3">
          <h2>ÁO PHÔNG</h2>
          <h3>Bản in đẹp</h3>
        </div>
      </section>
    </main>

    <MainFooter></MainFooter>
  </div>
</template>

<script>
import MainFooter from "@/components/MainFooter.vue";
import SiteHeader from "@/components/SiteHeader.vue";

export default {
  components: { SiteHeader, MainFooter },
  name: "MasterLayout",
};
</script>

<style>
/* Thêm CSS nếu cần */
</style>
