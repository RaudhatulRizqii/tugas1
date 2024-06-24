<template>
  <div>
    <section id="about" class="about">
      <h2><span>About Me</span></h2>
      <div class="row">
        <div class="about-img">
          <img
            src="../assets/photo.png"
            alt=""
          />
        </div>
        <div class="content">
          <p>
            Saya merupakan seorang mahasiswa semester 4 yang sedang belajar pemrograman di Universitas Islam Riau. Hobi saya adalah bermain futsal, ps, modif motor, dan lainnya.
          </p>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.about .row {
  display:block;
  padding: 0 10rem;
}
.about .row .about-img {
  margin: 0;
  justify-content: center;
}
.about .row .about-img img {
  width: 100%;
  height: auto;
  border-radius: 0.5rem;
}

.about .row .content {
  padding: 0 2rem;
  text-align: center;
}

.about h2 {
  font-size: 2.5rem;
  text-align: center;
  margin-bottom: 2rem;
}

.about p {
  font-size: 1.6rem;
  line-height: 1.5;
  font-weight: 700;
  text-align: center;
}
</style>
