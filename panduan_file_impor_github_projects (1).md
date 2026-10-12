# Manajemen Proyek GitHub: Buku Kalkulator Warung

Dokumen ini berisi struktur **GitHub Projects (Kanban Board)**, **GitHub Issues**, serta **Milestones** berdasarkan WBS dan Jadwal 8 Minggu yang telah dirancang untuk **Anggota 1** dan **Anggota 2**.

---

## 1. Daftar Milestones (Target Waktu)

Buat Milestone ini pada repository GitHub Anda di menu **Issues > Milestones**:

*   **Milestone 1: Analisis & Riset** (Minggu 1 - 2)
*   **Milestone 2: Desain UI/UX Prototipe** (Minggu 2 - 3)
*   **Milestone 3: Pengembangan Aplikasi (Frontend & Backend)** (Minggu 4 - 6)
*   **Milestone 4: Testing & Peluncuran** (Minggu 7 - 8)

---

## 2. Daftar GitHub Issues Siap Impor / Dibuat Manual

Setiap tugas dari WBS diubah menjadi **GitHub Issue**. Anda dapat menyalin daftar tugas di bawah ini secara langsung ke daftar **Issues** repository GitHub Anda:

### 🔹 Fase 1: Analisis & Riset
- [ ] **[M1-01] Wawancara Pemilik Warung & Identifikasi Masalah**
  - **Assignee:** `@Anggota1`
  - **Milestone:** `Milestone 1: Analisis & Riset`
  - **Labels:** `research`, `documentation`
  - **Deskripsi:** Melakukan wawancara langsung dengan ibu/bapak pemilik warung untuk menggali kendala hitung manual, kehilangan stok, dan rekap setoran kas.

- [ ] **[M1-02] Menyusun Dokumen Spesifikasi Kebutuhan Sistem (SRS)**
  - **Assignee:** `@Anggota1`
  - **Milestone:** `Milestone 1: Analisis & Riset`
  - **Labels:** `documentation`
  - **Deskripsi:** Mendokumentasikan alur kasir kalkulator, fitur data barang, dan rekap setoran harian dalam dokumen SRS.

---

### 🔹 Fase 2: Desain UI/UX
- [ ] **[M2-01] Desain Wireframe Layar Utama Kalkulator Warung**
  - **Assignee:** `@Anggota2`
  - **Milestone:** `Milestone 2: Desain UI/UX Prototipe`
  - **Labels:** `design`, `ui/ux`
  - **Deskripsi:** Merancang tata letak angka besar, tombol `000`, layar struk atas, dan tombol pintas ke Data Barang & Setoran Kas.

- [ ] **[M2-02] Desain Interface Menu Data Barang & Rekap Setoran**
  - **Assignee:** `@Anggota2`
  - **Milestone:** `Milestone 2: Desain UI/UX Prototipe`
  - **Labels:** `design`, `ui/ux`
  - **Deskripsi:** Membuat antarmuka pencarian barang, status warna stok, serta kartu ringkas total uang kas masuk.

---

### 🔹 Fase 3: Pemrograman & Coding
- [ ] **[M3-01] Pengembangan UI Frontend Aplikasi (Kalkulator, Menu, Setoran)**
  - **Assignee:** `@Anggota2`
  - **Milestone:** `Milestone 3: Pengembangan Aplikasi`
  - **Labels:** `frontend`, `feature`
  - **Deskripsi:** Mengimplementasikan hasil desain Figma/Wireframe ke dalam kode antarmuka aplikasi.

- [ ] **[M3-02] Pengembangan Mesin Logika Kalkulator & Matematika Kasir**
  - **Assignee:** `@Anggota1`
  - **Milestone:** `Milestone 3: Pengembangan Aplikasi`
  - **Labels:** `backend`, `feature`
  - **Deskripsi:** Membuat fungsi perhitungan matematika, riwayat penambahan item, dan tombol `000` otomatis.

- [ ] **[M3-03] Database Stok Barang Lokal & Sistem Rekap Setoran Harian**
  - **Assignee:** `@Anggota1`
  - **Milestone:** `Milestone 3: Pengembangan Aplikasi`
  - **Labels:** `backend`, `database`
  - **Deskripsi:** Mengatur penyimpanan data barang offline-first (SQLite/Local Storage) serta pengurangan stok otomatis setiap transaksi.

---

### 🔹 Fase 4: Testing & Peluncuran
- [ ] **[M4-01] Testing Usability & Uji Coba Penggunaan di Warung**
  - **Assignee:** `@Anggota1`, `@Anggota2`
  - **Milestone:** `Milestone 4: Testing & Peluncuran`
  - **Labels:** `testing`, `qa`
  - **Deskripsi:** Menguji aplikasi secara langsung bersama pemilik warung untuk mengevaluasi kemudahan penggunaan.

- [ ] **[M4-02] Perbaikan Bug (Bugfix), Refactoring Kode, & Rilis Final**
  - **Assignee:** `@Anggota1`, `@Anggota2`
  - **Milestone:** `Milestone 4: Testing & Peluncuran`
  - **Labels:** `bugfix`, `release`
  - **Deskripsi:** Memperbaiki bug hasil ujicoba warung dan merilis versi final aplikasi beserta panduan penggunaan ringkas.

---

## 3. Template CSV untuk Impor Otomatis ke GitHub Projects (v2)

Jika menggunakan alat bantu seperti CLI / plugin impor GitHub, gunakan format data tabel berikut:

| Title | Assignees | Milestone | Labels | Estimate (Weeks) |
| :--- | :--- | :--- | :--- | :--- |
| Analisis & Wawancara Warung | Anggota 1 | Milestone 1 | research | 1 |
| Dokumen Spesifikasi Kebutuhan | Anggota 1 | Milestone 1 | documentation | 1 |
| Wireframe UI Kalkulator & Menu | Anggota 2 | Milestone 2 | design, ui/ux | 2 |
| Frontend UI App Development | Anggota 2 | Milestone 3 | frontend | 3 |
| Logic Kalkulator & Backend | Anggota 1 | Milestone 3 | backend | 3 |
| Database Local & Logic Setoran | Anggota 1 | Milestone 3 | database | 2 |
| Testing Usability Langsung di Warung | Anggota 1, Anggota 2 | Milestone 4 | testing | 1 |
| Bugfixing & Rilis Panduan Warung | Anggota 1, Anggota 2 | Milestone 4 | release | 1 |

---

## 4. Cara Mengimpor ke GitHub Projects

1. Buka repository GitHub Anda, lalu klik tab **Projects** di bagian atas.
2. Klik tombol **New Project** dan pilih template **Board** (Kanban).
3. Buat kolom status: `Todo`, `In Progress`, `In Review`, `Done`.
4. Tambahkan custom field **Assignee** (pilih Anggota 1 / Anggota 2) dan **Milestone**.
5. Klik **+ Add Item** untuk menambahkan setiap tugas dari dokumen di atas ke papan kerja.