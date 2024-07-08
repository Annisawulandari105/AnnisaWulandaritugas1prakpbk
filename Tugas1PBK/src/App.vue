<template>
  <div id="app">
    <header>
      <img src="./assets/profile.jpg " alt="Foto Annisa Wulandari" class="profile-pic"/>
      <h1>Annisa Wulandari</h1>
      <p>Mahasiswa Teknik Informatika</p>
      <p>Universitas Islam Riau</p>
      <p>Riau, Rokan Hulu</p>
    </header>
    <section class="about">
      <h2>Tentang Saya</h2>
      <p>Perkenalkan, saya Annisa Wulandari, seorang mahasiswa Teknik Informatika di Universitas Islam Riau...</p>
    </section>
    <section class="education">
      <h2>Pendidikan</h2>
      <ul>
        <li>S1 Teknik Informatika - Universitas Islam Riau (2022 - Sekarang)</li>
      </ul>
    </section>
    <section class="skills">
      <h2>Keahlian</h2>
      <ul>
        <li>Programming: C++, Java, Python</li>
        <li>Web Development: HTML, CSS, JavaScript, Vue.js</li>
        <li>Database: MySQL, MongoDB</li>
      </ul>
    </section>
    <section class="contact">
      <h2>Kontak</h2>
      <p>Email: wulandarianisa@gmail.com</p>
    </section>
  </div>
</template>

<style>
  body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
  }

  #app {
    max-width: 900px;
    margin: auto;
    padding: 20px;
  }

  header {
    text-align: center;
    margin-bottom: 50px;
  }

  header h1 {
    margin-bottom: 0;
  }

  .profile-pic {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 20px;
  }

  section {
    margin-bottom: 40px;
  }

  .about p {
    text-indent: 50px;
  }
</style>

<script>
export default {
  name: 'App',
}
</script>