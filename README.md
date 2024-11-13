# Laporan Proyek Kelompok 3

Selamat datang di repositori **Laporan Proyek Kelompok 3**. Repo ini bertujuan untuk kolaborasi, pengembangan, dan pengelolaan laporan proyek kelompok secara efektif. Silakan ikuti panduan berikut untuk memudahkan kolaborasi antar anggota.

## Daftar Isi

-   [Persyaratan](#persyaratan)
-   [Cara Memulai](#cara-memulai)
-   [Struktur Folder](#struktur-folder)
-   [Workflow Kolaborasi](#workflow-kolaborasi)
-   [Branching dan Merge Request](#branching-dan-merge-request)
-   [Kontribusi](#kontribusi)

## Persyaratan

Pastikan kalian sudah menginstall:

-   [Git](https://git-scm.com/)
-   [Code Editor](https://code.visualstudio.com/) (seperti Visual Studio Code)

## Cara Memulai

1. **Fork** repositori ini ke akun GitHub masing-masing.
2. **Clone** repositori dari hasil fork kalian:

    ```bash
    git clone https://github.com/USERNAME/lp-kelompok3.git
    ```

    Ganti `USERNAME` dengan username GitHub masing-masing.

3. Masuk ke direktori proyek:

    ```bash
    cd lp-kelompok3
    ```

4. Tambahkan repositori utama sebagai `remote upstream`:
    ```bash
    git remote add upstream https://github.com/adzibilal/lp-kelompok3.git
    ```

## Struktur Folder

Pastikan untuk mengikuti struktur berikut agar tidak terjadi konflik file antar anggota:

```
lp-kelompok3/
│
├── assets/           # Folder untuk assets
├── index.html
└── README.md         # File README ini
```

## Workflow Kolaborasi

Ikuti langkah-langkah berikut untuk memastikan perubahan kalian masuk ke repositori utama:

1. **Sync dengan repositori utama**:
   Sebelum memulai, pastikan kalian melakukan sync untuk mendapatkan update terbaru:

    ```bash
    git fetch upstream
    git checkout main
    git merge upstream/main
    ```

2. **Buat Branch Baru**:
   Untuk setiap fitur atau perubahan, buat branch baru agar mudah untuk melacak perubahan yang dibuat.

    ```bash
    git checkout -b nama-feature
    ```

3. **Commit Perubahan**:
   Lakukan commit setelah membuat perubahan.

    ```bash
    git add .
    git commit -m "Deskripsi singkat perubahan"
    ```

4. **Push Branch ke Fork Pribadi**:

    ```bash
    git push origin nama-feature
    ```

5. **Buat Pull Request**:
   Setelah push, buat **Pull Request (PR)** ke repositori utama (`adzibilal/lp-kelompok3`) melalui GitHub.

## Branching dan Merge Request

-   Gunakan **branching** untuk setiap perubahan besar, baik itu fitur, bugfix, atau dokumentasi.
-   Pastikan untuk memberikan **deskripsi yang jelas** di setiap PR agar anggota lain bisa memahami perubahan yang dilakukan.
-   Cek PR lain yang belum di-merge untuk menghindari konflik dan mempermudah proses review.

## Kontribusi

Agar kolaborasi berjalan dengan lancar, mohon ikuti panduan berikut:

-   Selalu perbarui `upstream` kalian sebelum mulai mengerjakan sesuatu yang baru.
-   Lakukan review terhadap PR anggota lain jika ada waktu luang.

Jika ada pertanyaan atau kendala, silakan hubungi anggota yang lain. Selamat berkolaborasi!
