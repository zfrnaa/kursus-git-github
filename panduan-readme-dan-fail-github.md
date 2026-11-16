# 📄 Panduan Lengkap Fail Standard GitHub & Format Markdown (`.md`)

Apabila anda melawat mana-mana repositori profesional di GitHub, anda akan perasan beberapa fail standard yang sentiasa ada di muka hadapan projek—seperti `README.md`, `LICENSE`, dan `CONTRIBUTING.md`.

Panduan ini menerangkan fungsi setiap fail tersebut berserta rujukan lengkap **Markdown (`.md`)** supaya projek universiti, FYP, dan portfolio anda kelihatan kemas dan bertaraf industri.

---

## 1. Apa Itu `README.md` & Mengapa Ia Penting?

`README.md` ialah **"pintu hadapan"** atau manual rasmi bagi sesuatu projek. Apabila seseorang membuka pautan repositori GitHub anda, GitHub akan memaparkan kandungan fail `README.md` secara automatik di halaman utama.

> **💡 Tip Kerjaya (*Internship*):** Perekrut (*recruiter*) dan pengurus teknikal jarang membaca setiap baris kod anda terlebih dahulu. Mereka akan membaca **`README.md`** anda dahulu. Projek yang mempunyai `README.md` yang kemas, berserta gambar pratonton dan cara pemasangan, memberi tanggapan pertama yang sangat profesional.

### Templat `README.md` Sedia Guna untuk Projek Anda
Anda boleh menyalin templat ini untuk projek tugasan atau FYP anda:

```markdown
# Nama Projek Anda

Penerangan ringkas 1–2 ayat tentang apa yang projek ini lakukan dan masalah yang diselesaikan.

## ✨ Ciri-Ciri Utama
- Ciri 1 (contoh: Log masuk pengguna dengan pengesahan selamat)
- Ciri 2 (contoh: Eksport laporan ke format PDF)

## 🛠️ Teknologi yang Digunakan
- HTML5, CSS3, JavaScript / Python / React

## 🚀 Cara Memasang & Menjalankan Projek
1. Klon repositori ini:
   `git clone https://github.com/username-anda/nama-projek.git`
2. Buka folder projek dan jalankan fail utama.

## 📸 Tangkapan Skrin
![Paparan Utama Aplikasi](./assets/screenshot.png)

## 📄 Lesen
Projek ini dilesenkan di bawah Lesen MIT.
```

---

## 2. Panduan Lengkap Format Markdown (`.md`)

Fail `README.md` ditulis menggunakan **Markdown**—bahasa penanda teks ringkas yang ditukar oleh GitHub menjadi paparan web yang cantik.

| Elemen | Sintaks Markdown yang Anda Taip | Hasil Paparan di GitHub |
| :--- | :--- | :--- |
| **Tajuk Besar (H1)** | `# Tajuk Utama` | Tajuk paling besar (guna sekali sahaja di atas) |
| **Tajuk Bahagian (H2 / H3)** | `## Subtajuk` / `### Tajuk Kecil` | Tajuk bahagian dengan garisan pemisah kemas |
| **Teks Tebal (*Bold*)** | `**perkataan penting**` | **perkataan penting** |
| **Teks Condong (*Italic*)** | `*istilah Inggeris*` | *istilah Inggeris* |
| **Senarai Titik (*Bullet*)** | `- Perkara satu` | • Perkara satu |
| **Senarai Nombor** | `1. Langkah pertama` | 1. Langkah pertama |
| **Kotak Semak (*Checklist*)** | `- [x] Siap` / `- [ ] Belum` | ☑️ Siap / ⬜ Belum |
| **Kod Sebaris (*Inline*)** | `` `git status` `` | `git status` |
| **Pautan (*Link*)** | `[Klik di sini](https://github.com)` | [Klik di sini](https://github.com) |
| **Gambar (*Image*)** | `![Teks Alternatif](./gambar.png)` | Memaparkan gambar daripada folder projek |
| **Petikan (*Blockquote*)** | `> Nota penting untuk pembaca.` | Kotak petikan berindentasi di sebelah kiri |

### Blok Kod (*Code Block*) dengan Warna Sintaks
Untuk memaparkan beberapa baris kod atau arahan terminal, balut kod anda menggunakan **tiga tanda *backtick* (`` ``` ``)** diikuti nama bahasa (`bash`, `python`, `html`, `javascript`):

````markdown
```bash
git status
git add .
git commit -m "Kemaskini halaman utama"
```
````

### Jadual (*Table*)
Gunakan simbol paip `|` dan tanda sempang `-` untuk membina jadual:

```markdown
| Arahan | Fungsi |
| :--- | :--- |
| `git init` | Memulakan repositori Git |
| `git push` | Memuat naik kod ke GitHub |
```

---

## 3. Fail Standard Lain di Dalam Repositori GitHub

Selain `README.md`, berikut ialah fail-fail rasmi yang sering ditemui di dalam projek sumber terbuka dan industri:

### A. `LICENSE` (Lesen Penggunaan)
Tanpa fail `LICENSE`, secara teknikalnya orang lain **tidak dibenarkan** menyalin atau menggunakan kod anda mengikut undang-undang hak cipta. Pilihan lesen paling popular ialah:
- **MIT License:** Sangat bebas—sesiapa sahaja boleh menggunakan, mengubah suai, dan menggunakan kod anda (termasuk untuk tujuan komersial) selagi mereka mengekalkan nama hak cipta anda. Paling sesuai untuk kod atur cara dan templat.
- **Creative Commons (`CC BY-NC 4.0`):** Sesuai untuk **buku panduan, nota kuliah, dan bahan pendidikan percuma**—orang lain boleh berkongsi dengan kredit kepada anda, tetapi **dilarang menjualnya** untuk keuntungan komersial.
- **GPL v3:** Sesiapa yang mengubah suai kod anda wajib berkongsi semula kod mereka secara terbuka di bawah lesen yang sama.

### B. `CONTRIBUTING.md` (Panduan Penyumbang)
Fail ini memberitahu pembangun luar peraturan sebelum mereka menghantar *Pull Request* (PR) ke projek anda:
- Bagaimana cara membuat *Fork* dan *Branch* (`git switch -c fix/nama-isu`).
- Format mesej `commit` yang dikehendaki.
- Cara menguji kod sebelum menghantar PR.

### C. `.gitignore` (Senarai Pengecualian)
Memberitahu Git fail atau folder mana yang **tidak boleh** dimasukkan ke dalam repositori (contohnya `.env` yang mengandungi kata laluan API, `node_modules/`, atau fail sementara sistem operasi seperti `.DS_Store`). *(Lihat **[Bab 3](./bab-03-asas-git-tempatan.md)** untuk latihan amali penuh).*

### D. `CODE_OF_CONDUCT.md` (Kod Etika Komuniti)
Digunakan oleh projek komuniti yang besar untuk menetapkan adab perbincangan di ruang *Issues* dan *Discussions* supaya semua penyumbang saling menghormati.

---

> **🧭 Kembali:** [Jadual Kandungan Utama (`README.md`)](./README.md) • [Bab 4: Berhubung dengan GitHub](./bab-04-berhubung-dengan-github.md)
