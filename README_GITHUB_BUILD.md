# LOGO MAKER BY KALZ — Build APK lewat GitHub Actions

## Yang diperlukan
- Akun GitHub.
- Browser di HP.
- File ZIP proyek ini.

## Langkah dari HP
1. Buka https://github.com lalu masuk atau buat akun.
2. Buat repository baru bernama `logo-maker-by-kalz`.
3. Pilih **Public** untuk cara termudah memakai Actions pada akun gratis. Jangan unggah rahasia atau data pribadi.
4. Unggah semua isi folder `LOGO_MAKER_BY_KALZ_Android` ke repository. Pastikan folder tersembunyi `.github/workflows` dan file `build-apk.yml` ikut terunggah.
5. Buka tab **Actions** di repository.
6. Pilih **Build LOGO MAKER BY KALZ APK**.
7. Tekan **Run workflow**, lalu konfirmasi.
8. Tunggu sampai proses berhasil (tanda centang hijau).
9. Buka hasil run, cari **Artifacts**, lalu unduh `LOGO-MAKER-BY-KALZ-APK`.
10. Ekstrak ZIP artifact dan instal `app-debug.apk`. Jika diminta, izinkan browser/File Manager memasang aplikasi dari sumber tersebut.

Jika upload folder tersembunyi `.github` sulit dari HP, buat file baru di GitHub dengan nama `.github/workflows/build-apk.yml`, lalu salin isi file workflow di folder proyek.

## Catatan
- Hasilnya adalah debug APK untuk uji coba/pribadi.
- Build pertama memerlukan internet.
- Jika gagal, kirim screenshot error merah dari halaman Actions agar bisa diperiksa.
- Jangan membagikan password, token, atau kode pemulihan GitHub.
