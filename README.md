# Ruang Pintar - Daily Study, Attendance & Assignment Tracker

Aplikasi web modern **Single-File HTML** yang responsif untuk manajemen tugas harian, presensi kehadiran, dan penilaian kuis dengan dukungan **Role-Based Access Control (RBAC) Ketat** dan **Google Sign-In Gateway**.

---

## 🔒 Sistem Keamanan & Hak Akses Berdasarkan Peran

### 1. Pelajar (Murid)
- **Akses Terisolasi**: Siswa **tidak dapat mengakses atau melihat panel kontrol guru**. Tidak ada tombol pengalih peran saat login sebagai murid.
- **Fitur Khusus Pelajar**:
  - **Presensi Mandiri Harian**: Tombol satu-klik untuk check-in kehadiran harian (`Hadir`, `Izin`, `Sakit`) lengkap dengan cap waktu.
  - **Target & Progress Bar Belajar**: Indikator persentase penyelesaian modul secara visual.
  - **Checklist Tugas Harian**: Menandai materi yang telah selesai dipelajari.
  - **Pusat Unduh Modul**: Mengunduh berkas PDF materi dari guru.
  - **Kantong Pengumpulan Tugas**: Formulir kirim berkas tugas (`.zip`, `.pdf`, `.docx`, `.png`) & catatan kendala belajar.
  - **Buku Nilai & Evaluasi Guru**: Memantau hasil skor nilai tugas/quiz serta catatan evaluasi dari guru.

### 2. Pengajar (Guru)
- **Fitur Khusus Pengajar**:
  - **Cek Tugas Masuk Murid**: Memantau kiriman berkas tugas siswa, membaca kendala belajar, dan mengunduh berkas asli.
  - **Penilaian Tugas & Quiz**: Formulir input nilai/skor (0 - 100) dan catatan evaluasi/masukan guru.
  - **Presensi Kehadiran Siswa**: Rekapitulasi absensi siswa harian secara *real-time* (Hadir, Izin, Sakit).
  - **Rekap Buku Nilai Quiz & Tugas**: Tabel rekapitulasi nilai seluruh siswa dengan status KKM (Lulus / Remedial).
  - **Publikasi Tugas & Modul**: Form unggah materi harian dan lampiran PDF tanpa perlu memilih mata pelajaran (langsung judul tugas, tenggat waktu, dan deskripsi).

---

## 🚀 Cara Menjalankan di VS Code

1. Buka folder proyek di **VS Code**.
2. Klik kanan pada file `index.html`, lalu pilih **Open with Live Server** (atau tekan shortcut `Alt + L, Alt + O`).
3. Pilih peran Anda (**Pelajar** atau **Pengajar**), lalu klik **Lanjutkan Masuk dengan Google**.
