# Shopiku - Aplikasi Shopee Clone (Modul UAS 12 Layar)

Shopiku adalah aplikasi e-commerce Android modern yang terinspirasi dari Shopee dengan desain AntiGravity / Material 3 UI yang presisi, performa tinggi, dan bebas error.

## 🚀 Fitur Utama & 12 Layar Utama:
1. **Splash Screen**: Animasi fade-in logo Shopiku modern.
2. **Login Screen**: Form autentikasi pengguna yang bersih.
3. **Register Screen**: Form pendaftaran pengguna baru.
4. **Home Screen (Beranda)**:
   - Header Oranye Shopee + Search Bar.
   - Banner Promo Spesial Cirebon (Diskon 70% + Gratis Ongkir).
   - Scroll Kategori Horizontal.
   - Grid 2 Kolom Produk (Card presisi, harga bold oranye, rating bintang).
   - Bottom Navigation Bar (Beranda, Kategori, Keranjang, Profil).
5. **Category Screen**: Filter produk otomatis sesuai kategori pilihan.
6. **Product Detail Screen**: Gambar produk besar, varian produk, deskripsi, & Bottom Action Bar (+ Keranjang & Beli Sekarang).
7. **Cart Screen**: Full CRUD Keranjang (kuantitas, hapus, total bayar, checkout).
8. **Checkout Screen**: Alamat Pengiriman Kota Cirebon, Pilihan Kurir, Ringkasan Biaya.
9. **Payment Sandbox Screen**: BCA Virtual Account, Timer Countdown, & Simulasi Cek Pembayaran.
10. **Tracking Screen**: Lacak Status Pengiriman Paket Real-time.
11. **Profile Screen**: Informasi akun, Saldo ShopeePay, Status Pesanan, Menu Pengaturan.
12. **Product Review Screen**: Form Ulasan & Rating Bintang Produk.

## 🛠 Tech Stack:
- **Language**: Kotlin
- **Architecture**: MVVM / Modular Clean Architecture
- **UI Framework**: Material Design 3 / ViewBinding
- **Networking**: Retrofit 2 + OkHttp Logging Interceptor
- **JSON Parsing**: Gson Converter
- **Image Loading**: Coil 2.6.0
- **SDK**: compileSdk 37 / targetSdk 34 / minSdk 24

## 📦 API Endpoint (MockAPI):
- BASE_URL: `https://6adc5ac9fa5e73d4ab2d59f6.mockapi.io/`
- Endpoints: `/products`, `/cart`
