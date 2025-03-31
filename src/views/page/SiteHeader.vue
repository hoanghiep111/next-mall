<template>
  <section id="header">
    <a href="#"><img src="/frontend/img/anh1-removebg.png" class="logo" /></a>
    <div>
      <ul id="navbar">
        <li><a class="active" href="index.html">Home</a></li>
        <li><a href="shop.html">Shop</a></li>
        <li><a href="blog.html">Blog</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="account.html">Account</a></li>
        <li id="search-bar">
          <input type="text" placeholder="Search..." />
          <button type="submit"><i class="fa fa-search"></i></button>
        </li>
        <li id="lg-bag">
          <a href="cart.html"><i class="fa-solid fa-cart-shopping"></i></a>
        </li>
        <a href="#" id="close"><i class="fa-solid fa-xmark"></i></a>
      </ul>
    </div>
    <div id="mobile">
      <a href="cart.html"><i class="fa-solid fa-cart-shopping"></i></a>
      <i id="bar" class="fas fa-outdent"></i>
    </div>
  </section>
</template>

<script>
export default {
  name: "SiteHeader",
  mounted() {
    let script = document.createElement("script");
    script.src = "/frontend/scrip.js"; // Đường dẫn từ `public`
    script.async = true;
    document.body.appendChild(script);
  },
};
</script>

<style></style>
