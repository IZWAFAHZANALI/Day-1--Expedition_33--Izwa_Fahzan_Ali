# Day-1--Expedition_33--Izwa_Fahzan_Ali

# Day 1 Proyek Workshop - Building with AI, Managing Change with GitHub

## Informasi Peserta
- Nama : Izwa Fahzan Ali
- Kelas : TI 1c
- Kelompok : Expedition 33

## Deskripsi & Tujuan Repository
Repository ini dibuat untuk mendokumentasikan kegiatan **Day 1 Proyek Workshop** pada acara sosialisasi jurusan. Repository ini berfungsi sebagai wadah untuk menyimpan catatan materi, poin-poin pengetahuan baru yang dipelajari, serta mengelola kode dari proyek praktikal *Student Task Planner* menggunakan sistem kontrol versi (Git & GitHub).

---

## Rangkuman Materi Workshop

**Pemateri:** Nugi Farhan (Senior Product Designer)  
**Topik:** Building with AI, Managing Change with GitHub  

### 1. Prompt Engineering & AI
* **Definisi Prompt:** Prompt adalah instruksi atau masukan (dapat berupa pertanyaan, kata kunci, hingga potongan kode) yang diberikan kepada model AI untuk mendapatkan hasil tertentu.
* **Pentingnya Konteks:** AI menghasilkan keluaran yang jauh lebih akurat dan relevan jika instruksi dilengkapi dengan konteks yang spesifik dan batasan (constraints) yang jelas.
* **Struktur Prompt yang Baik:**
  * **Role:** Menentukan peran/identitas AI (misal: *Web Developer*).
  * **Task:** Tugas atau perintah utama yang harus dikerjakan AI.
  * **Context:** Latar belakang, kebutuhan, dan batasan teknis proyek.
  * **Format:** Bentuk luaran yang diharapkan (misal: *struktur kode HTML/CSS/JS*).
* **Keuntungan:** Meningkatkan performa AI, mengurangi bias/respons yang kurang relevan, serta memberikan kontrol yang lebih baik atas hasil keluaran.

### 2. Dasar Git & GitHub
* **Perbedaan Git dan GitHub:**
  * **Git:** Sistem *Distributed Version Control System* (DVCS) lokal diciptakan oleh Linus Torvalds (2005) untuk melacak dan mengelola riwayat perubahan berkas/kode di komputer lokal.
  * **GitHub:** Platform berbasis cloud/web untuk menyimpan repository Git secara online dan memfasilitasi kolaborasi antar pengembang.
* **Tiga Area Utama Git (Git Workflow):**
  1. **Working Directory:** Salinan proyek lokal tempat berkas dibuat dan dimodifikasi.
  2. **Staging Area (Index):** Area penampungan sementara untuk memilih berkas yang siap dimasukkan ke dalam commit berikutnya.
  3. **Git Directory (.git):** Database utama tempat Git menyimpan seluruh metadata dan riwayat riwayat commit proyek.
* **Perintah Dasar Git:**
  * `git init` : Menginisialisasi repository Git baru di folder lokal.
  * `git add .` : Memindahkan seluruh perubahan file ke Staging Area.
  * `git commit -m "pesan"` : Menyimpan perubahan dari Staging Area ke direktori Git.
  * `git remote add origin <URL>` : Menghubungkan repository lokal ke GitHub.
  * `git push origin main` : Mengirim commit lokal ke repository remote di GitHub.
  * `git pull origin main` : Mengambil dan menggabungkan perubahan dari GitHub ke lokal.
* **Konfigurasi Keamanan:** Pembuatan kunci SSH (`ssh-keygen -t ed25519`) dan pendaftarannya pada akun GitHub untuk otentikasi koneksi secara aman.

---

## Poin Penting & Pengetahuan Baru
1. **Penyusunan Prompt Terstruktur:** Memahami bahwa efektivitas penggunaan AI dalam pemrograman sangat bergantung pada kejelasan *Role*, *Task*, *Context*, dan *Format* pada instruksi.
2. **Manajemen Perubahan Kode (Version Control):** Memahami pentingnya alur pencatatan kode dari *Working Directory* $\rightarrow$ *Staging Area* $\rightarrow$ *Commit*, sehingga perubahan berkas dapat dilacak dan dikelola dengan aman.
3. **Koneksi Remote Repository:** Mengetahui cara menghubungkan proyek lokal ke platform cloud GitHub dan melakukan otentikasi menggunakan SSH Key.

---

## Pendapat Pribadi (Day 1 Proyek Workshop)
Kegiatan workshop Day 1 ini sangat bermanfaat dan memberikan pengalaman praktis yang relevan dengan alur kerja industri saat ini. Materi diajarkan secara terstruktur, mulai dari cara memanfaatkan AI untuk membantu pembuatan aplikasi sederhana (*Student Task Planner*) hingga praktik langsung mengelola versi kode menggunakan Git dan GitHub. Workshop ini memberikan fondasi yang kuat bagi mahasiswa baru dalam memahami kontrol versi dan kolaborasi proyek berbasis kode.
