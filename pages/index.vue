<template>
  <!-- Hero Section -->
  <section class="hero" id="home">
    <main class="content">
      <h1>Rekomendasi Film Indonesia</h1>
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cumque, dolore.</p>
    </main>
  </section>
<!-- End Section -->
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style>
.hero{
  min-height: 100vh;
  display: flex;
  background-image: url('@/assets/gambar/bioskop.jpg');
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;

}
.hero .content {
    padding: 15rem 7%;
    max-width: 45rem;

}
.hero .content h1 {
    font-size: 3rem;
    color: #fff;
    text-shadow: rgba(1, 1, 3, 0.5);
    line-height: 1.1;

}
.hero .content p {
  color: #fff;
    font-size: 1.2rem;
    margin-top: 1.5rem;
    font-weight: 100;
    /* digunakan untuk mencampurkan warna ketika beda warna */

}
</style>
