<template>
  <div>
    <section class="home" id="home">
      <main class="content">
        <h3>Perkenalkan, saya Raudhatul Rizqi!</h3>
        <p>
          Saya merupakan seorang mahasiswa  semester 4 yang sedang belajar pemrograman di Universitas Islam Riau
        </p>
        
      </main>
    </section>
  </div>
</template>

<style scoped>
h3 {
  font-family: roboto;
  color: #000;
  font-size: 50px;
  margin-bottom: 10px;
}
.home {
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  background-size: cover;
  background-position: center;
  position: relative;
}

.home .content {
  padding: 1.4rem 7%;
  max-width: 70;
  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: repeat(3, auto);
  align-items: center;
  text-align: center;
}

.home .content h3 {
  font-size: 4.5em;
  line-height: 1.2;
  text-align: center;
}

.home .content p {
  font-size: 2rem;
  margin-top: 1rem;
  line-height: 1.4;
  font-weight: 300;
  text-align: center;
}
</style>

<script setup>
</script>
