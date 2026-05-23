# 🚀 Laporan Praktikum Pengujian API Manual
## Restful Booker API Testing menggunakan Postman

---

<div align="center">

# 🧪 PRAKTIKUM PENGUJIAN API

### Mata Kuliah Software Testing

<img src="https://cdn-icons-png.flaticon.com/512/2166/2166823.png" width="180"/>

### Disusun Oleh

| Nama | NIM |
|---|---|
| **Fitri Salwa** | **231524009** |
| **Salma Nesya Putri Salia** | **231524024** |

---

### Teknik Informatika  
### Politeknik Negeri Bandung  
### 2026

</div>

---

# 📖 1. Pendahuluan

## 1.1 Latar Belakang

Application Programming Interface (API) merupakan media komunikasi antar sistem yang memungkinkan pertukaran data secara otomatis. Pengujian API dilakukan untuk memastikan bahwa endpoint yang tersedia dapat berjalan sesuai kebutuhan sistem.

Pada praktikum ini dilakukan pengujian API menggunakan aplikasi **Postman** terhadap sistem **Restful Booker API**. Pengujian dilakukan secara manual dengan membuat test case, melakukan test execution, validasi response, serta mendokumentasikan hasil pengujian dan bug yang ditemukan.

---

## 🎯 1.2 Tujuan Praktikum

Tujuan praktikum ini adalah:

- Memahami konsep dasar API Testing
- Mempelajari penggunaan Postman
- Membuat test case API
- Melakukan pengujian manual API
- Melakukan validasi response API
- Membuat dokumentasi testing
- Melakukan bug reporting dan monitoring

---

# 🛠️ 2. Persiapan Environment Testing

## 2.1 Tools dan Software

| Software | Fungsi |
|---|---|
| Postman | Pengujian API |
| Browser | Mengakses dokumentasi API |
| Restful Booker | Software Under Test |
| Windows 10/11 | Environment Testing |

---

## 🌐 2.2 API yang Digunakan

API yang digunakan pada praktikum ini:

```bash
https://restful-booker.herokuapp.com
```

Dokumentasi API:

```bash
https://restful-booker.herokuapp.com/apidoc/index.html
```

---

## 📌 Endpoint yang Diuji

| Method | Endpoint | Fungsi |
|---|---|---|
| GET | `/booking` | Mengambil seluruh booking |
| GET | `/booking/{id}` | Mengambil detail booking |
| POST | `/booking` | Membuat booking baru |
| PUT | `/booking/{id}` | Mengubah seluruh data booking |
| PATCH | `/booking/{id}` | Mengubah sebagian data booking |
| DELETE | `/booking/{id}` | Menghapus booking |

---

# ⚙️ 3. Pengaturan Environment

## 📥 3.1 Instalasi Postman

Langkah-langkah instalasi:

1. Download Postman dari website resmi
2. Install aplikasi Postman
3. Membuka aplikasi Postman
4. Membuat Workspace baru
5. Membuat Collection Testing API

---

## 🔧 3.2 Konfigurasi Testing

### Base URL

```bash
https://restful-booker.herokuapp.com
```

### Header

```json
{
  "Content-Type": "application/json",
  "Accept": "application/json"
}
```

---

# 📊 4. Analisis Test Case

## 🧩 Matriks Pengujian API

| No | API | Method | Skenario Pengujian | Expected Result |
|---|---|---|---|---|
| 1 | GetBookingIds | GET | Mengambil seluruh booking | Status 200 |
| 2 | GetBooking | GET | Mengambil booking berdasarkan ID valid | Status 200 |
| 3 | CreateBooking | POST | Membuat booking baru | Status 200 |
| 4 | UpdateBooking | PUT | Mengubah seluruh data booking | Status 200 |
| 5 | PartialUpdateBooking | PATCH | Mengubah sebagian data | Status 200 |
| 6 | DeleteBooking | DELETE | Menghapus booking | Status 201 |

<div align="center">

# 🎉 TERIMA KASIH 🎉

</div>