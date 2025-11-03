# 📊 Aplikasi Rekap Nilai Siswa
Aplikasi input & rekap nilai siswa berbasis Google Sheets tanpa backend database.  
Guru cukup login menggunakan akun Google, lalu bisa menginput nilai langsung dari web — data otomatis tersimpan ke Google Spreadsheet.

✅ Tanpa server backend / hosting database  
✅ Spreadsheet dibuat otomatis per pengguna  
✅ Input nilai per kelas & per jenis penilaian (Tugas, Ulangan, PAS, PAT, dll)  
✅ Google OAuth aman & resmi (GIS)  
✅ React + Tailwind CSS — UI responsif & mobile friendly  

---
## 🌐 Demo Online  
🔗 **[https://smkyappiwns.github.io/rekap-nilai/](https://smkyappiwns.github.io/rekap-nilai/)**  
---
## 🖼️ Tampilan Aplikasi
| Halaman | Deskripsi |
|---------|-----------|
| 🔐 Login Google | Login aman via Google OAuth |
| 🏫 Pilih Kelas | Guru memilih kelas yang akan di-input nilainya |
| ✍️ Input Nilai | Input Tugas, Ulangan, PAS, PAT → kolom otomatis dibuat |
| 📄 Rekap Otomatis | Nilai rata-rata otomatis dihitung di Spreadsheet |
| 📤 Export | File otomatis bisa dibuka di Excel / dibagikan ke wali kelas / TU |

---

## 🚀 Fitur Utama

| Fitur | Detail |
|-------|--------|
| 🔑 Google Login | Tanpa password lokal, aman & mudah |
| 📄 Spreadsheet Otomatis | Jika belum ada → dibuat di Google Drive |
| 🏫 Multi Kelas | Guru dapat memilih kelas |
| 📝 Input Kolom Dinamis | Tambah "Tugas 1", "Ulangan 2", dll otomatis muncul di sheet |
| 📊 Hitung Nilai Otomatis | Spreadsheet menghitung rata-rata & total otomatis |
| 🗂 Cache LocalStorage | Mempercepat load data |
| 📱 Full Responsive | Bisa dipakai dari HP / Tablet / Laptop |
| 🧽 Tidak perlu server | Murni frontend + Google API |
| 🔁 Auto Refresh Token | Token login diperbarui otomatis |

---

## 🛠️ Teknologi yang Digunakan

| Teknologi | Digunakan Untuk |
|-----------|-----------------|
| React + Vite | Frontend utama |
| TypeScript | Type safety |
| TailwindCSS | Tampilan UI |
| Google Identity Services | Login OAuth 2.0 resmi |
| Google Drive API | Membuat file spreadsheet |
| Google Sheets API | Menyimpan & mengambil nilai |
| LocalStorage | Cache user & spreadsheet ID |
| XLSX.js (opsional) | Export / import Excel |

---

