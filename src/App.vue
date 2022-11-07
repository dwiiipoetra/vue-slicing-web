
<template>
  <!-- section 1 -->
  <div class="container-fluid" style="padding:0;">
    <div class="stripe-20"></div>
    <!-- navbar -->
    <nav class="navbar navbar-light bg-light">
      <div class="container px-5 py-3">
        <a class="navbar-brand ms-3" href="#">
          <img src="./assets/logo.png" alt="logo" />
        </a>
        <button class="btn fw-light me-3">KEMBALI KE PILIHANKU</button>
      </div>
    </nav>
    <!-- subheading-text -->
    <div class="container subheading-text">
      <div class="row py-4">
        <div class="col">
          <p class="lead fw-normal fs-6 mb-0">DAPATKAN ASURANSI GRATIS DARI AXA LIFE INDONESIA</p>
          <p class="lead fw-bold fs-3 mb-0">UNTUK PEMEGANG KARTU KREDIT</p>
        </div>
      </div>
    </div>
    <!-- hero-image -->
    <div class="container hero-image">
      <img src="./assets/slides.png" class="img-fluid" alt="Family with AXA Life Indonesia" />
      <p class="lead fw-bold fs-5 mb-0">Keuntungan mendaftar <a href="#" class="">Axa Life Indonesia</a> di Pilihkartu
      </p>
    </div>
    <!-- services -->
    <div class="container services">
      <div class="row mt-5">
        <!-- row 1 -->
        <div class="col-lg-5">
          <p class="text-end">
            Diberikan gratis secara cuma-cuma tanpa premi. <br><b>PREMI : 0,-(NOL RUPIAH)</b>
          </p>
        </div>
        <div class="col-lg-1 mx-auto">
          <img src="./assets/icon_1.png" alt="" />
        </div>
        <div class="col-lg-1">
          <img src="./assets/icon_4.png" alt="" />
        </div>
        <div class="col-lg-5">
          <p>
            Pendaftar yang lolos verifikasi dari tim AXA berhak mendapat perlindungan Asuransi
            Kecelakaan diri <b>selama 3 bulan</b>
          </p>
        </div>
        <!-- row 2 -->
        <div class="col-lg-5">
          <p class="text-end">
            Santunan meninggal dunia akibat kecelakaan <br>sebesar <b>Rp 25.000.000,-</b> (dua puluh
            lima
            juta rupiah)
          </p>
        </div>
        <div class="col-lg-1">
          <img src="./assets/icon_2.png" alt="" />
        </div>
        <div class="col-lg-1">
          <img src="./assets/icon_5.png" alt="" />
        </div>
        <div class="col-lg-5">
          <p>
            <b>Tanpa masa tunggu</b> perlindungan yang didapatkan <br>dimulai sejak polis aktif
          </p>
        </div>
        <!-- row 3 -->
        <div class="col-lg-5">
          <p class="text-end">
            Perlindungan <b>Asuransi Gratis</b> akan diberikan kepada pemegang <br>kartu kredit yang
            mendaftar program AXA Care Protection melalui pilihkartu.com
          </p>
        </div>
        <div class="col-lg-1">
          <img src="./assets/icon_3.png" alt="" />
        </div>
        <div class="col-lg-1">
          <img src="./assets/icon_6.png" alt="" />
        </div>
        <div class="col-lg-5">
          <p>
            <b>Bukan penawaran</b> melainkan pemberian secara cuma-cuma <br>kepada semua nasabah
            ter-registrasi via pilihkartu.com yang sudah memiliki kartu kredit
          </p>
        </div>
      </div>
    </div>
  </div>
  <!-- section 2 -->
  <!-- about -->
  <div class="container-fluid mb-5" style="padding:0; background: aliceblue;">
    <div class="container about py-5">
      <p class="lead fw-bold fs-5 mb-2 text-center">Tentang <a href="#" class="text-blue-900">Axa Protection</a>
        Sekarang</p>
      <p class="text-center px-5">
        Program asuransi gratis AXA Care Protection merupakan program berupa asuransi kecelakaan dari asuransi AXA Life
        indonesia.
        Peserta yang lolos verifikasi akan mendapatkan benefit berupa uang pertanggungan bila terjadi kecelakaan yang
        mengakibatkan meninggal dunia
      </p>
      <div class="text-center">
        <button class="btn px-5 fs-5">DAFTAR SEKARANG JUGA</button>
      </div>
    </div>
  </div>
  <!-- register form -->
  <div class="container register-form">
    <div class="row mb-2">
      <div class="col-12">
        <p class="lead fw-bold fs-5 mb-2 text-center">Dapatkan Perlindungan <a href="#" class="text-blue-900">Axa
            Protection</a>
          Sekarang</p>
        <p class="text-center fw-bold px-5">
          Cukup isi data diri Anda pada form dibawah ini
        </p>
      </div>
      <div class="col-6 text-end fw-bolder">
        <label for="nama" class="form-label">Nama Lengkap</label>
      </div>
      <div class="col-6">
        <input type="text" class="form-control mb-3" id="nama" style="width:70%">
      </div>
      <div class="col-6 text-end fw-bolder">
        <label for="tgl_lahir" class="form-label">Tanggal Lahir (mm/dd/yyyy)</label>
      </div>
      <div class="col-6">
        <input type="date" class="form-control mb-3" id="tgl_lahir" style="width:70%">
      </div>
      <div class="col-6 text-end fw-bolder">
        <label for="email" class="form-label">Email Address</label>
      </div>
      <div class="col-6">
        <input type="email" class="form-control mb-3" id="email" style="width:70%">
      </div>
      <div class="col-6 text-end fw-bolder">
        <label for="nomor" class="form-label">Nomor Ponsel</label>
      </div>
      <div class="col-6">
        <input type="text" class="form-control mb-3" id="nomor" style="width:70%">
      </div>
      <div class="col-6 text-end fw-bolder">
        <label for="kartu_kredit" class="form-label">Memiliki Kartu Kredit</label>
      </div>
      <div class="col-6 mb-3">
        <input class="form-check-input" type="checkbox" value="" id="visa">
        <label class="form-check-label me-2" for="visa">&nbsp;Visa</label>
        <input class="form-check-input" type="checkbox" value="" id="master_card">
        <label class="form-check-label me-2" for="master_card">&nbsp;MASTER CARD</label>
        <input class="form-check-input" type="checkbox" value="" id="bca_card">
        <label class="form-check-label me-2" for="bca_card">&nbsp;BCA CARD</label>
        <input class="form-check-input" type="checkbox" value="" id="other">
        <label class="form-check-label" for="other">&nbsp;LAINNYA</label>
      </div>
      <div class="col-6"></div>
      <div class="col-6">
        <p><u><a href="#" class="fst-italic">Syarat & Ketentuan Aplikasi</a></u></p>
      </div>
      <div class="col-6"></div>
      <div class="col-6">
        <input class="form-check-input" type="checkbox" value="" id="agreement">
        <label class="form-check-label" for="agreement" style="font-size:11px; width:70%; margin-left:4px;">Saya
          mengetahui dan
          menyetujui syarat dan ketentuan diatas<br>serta bersedia dihubungi oleh PT. AXA Life Indonesia untuk
          mendapatkan<br>penjelasan tentang produk dan informasi lainnya</label>
      </div>
      <div class="col-6"></div>
      <div class="col-6"><button class="btn fw-light mt-4 px-5">Kirim</button></div>
    </div>
  </div>
  <!-- order-step -->
  <div class="container-fluid" style="padding:0; background: whitesmoke;">
    <div class="container order-step py-5">
      <p class="lead fw-bold text-center">4 Langkah Mudah Mendapatkan Asuransi <a href="#">AXA
          Life Indonesia</a> di Pilihkartu</p>
      <div class="row">
        <div class="col-12">
          <div class="col-8 mx-auto">
            <img src="./assets/langkah.png" class="img-fluid" alt="Step Order AXA Indonesia" />
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- footer -->
  <footer>
    <div class="stripe-40">
      <p class="text-center pt-1">Copyright (c) 2017 Pilihkartu.com and AXA All Rights Reserved</p>
    </div>
  </footer>
</template>