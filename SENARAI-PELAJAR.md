# 🏆 Balai Kemasyhuran (*Hall of Fame*) — Senarai Pelajar Kursus Git & GitHub

Selamat datang ke **Balai Kemasyhuran**!

Fail ini adalah ruang rasmi untuk meraikan setiap pelajar dan pembangun baharu yang telah berjaya menguasai aliran kerja kolaborasi Git dan GitHub: daripada melakukan **Fork**, **Clone**, mencipta **Branch**, melakukan **Commit**, memuat naik kod melalui **Push**, sehinggalah menghantar **Pull Request (PR)** pertama yang sebenar.

Jika nama anda sudah tertera di dalam jadual di bawah, tahniah! Anda telah membuktikan bahawa anda mampu menggunakan aliran kerja yang sama seperti yang diamalkan oleh jurutera perisian profesional di dalam industri.

---

## 🛠️ Cara Menambah Nama Anda ke Dalam Senarai Ini (Amali Bab 6)

Panduan penuh berserta penerangan konsep terdapat di dalam **[Bab 6: Branching dan Pull Request](./bab-06-branching-dan-pull-request.md)**. Berikut adalah ringkasan langkah demi langkah untuk rujukan pantas anda:

### Langkah 1: *Fork* dan *Clone* Repositori Ini
1. Klik butang **Fork** di penjuru kanan atas halaman repositori utama kursus ini untuk menyalinnya ke dalam akaun GitHub anda sendiri.
2. Salin URL repositori *Fork* anda, kemudian jalankan arahan berikut di dalam terminal komputer anda:
   ```bash
   git clone https://github.com/USERNAME-ANDA/kursus-git-github.git
   cd kursus-git-github
   ```

### Langkah 2: Cipta *Branch* Baharu
Jangan sunting fail secara terus di atas cawangan `main`. Cipta satu `branch` khas menggunakan nama panggilan atau *username* anda supaya perubahan anda terasing dengan kemas:
```bash
git switch -c tambah-nama-anda
```

### Langkah 3: Tambah Baris Nama Anda di Bahagian Paling Bawah Jadual
1. Buka fail `SENARAI-PELAJAR.md` ini menggunakan penyunting kod anda (seperti VS Code).
2. Tatal ke bahagian paling bawah jadual di bawah.
3. Tambahkan **satu baris baharu di bahagian paling akhir jadual** mengikut format lajur berikut (jangan ubah atau padam baris pelajar lain bagi mengelakkan *Merge Conflict*), dan link portfolio adalah opsional:
   ```markdown
   | Bil | Nama / Panggilan | Institusi / Latar Belakang | Pautan GitHub & Portfolio | Tarikh |
   ```
   **Contoh Baris:**
   ```markdown
   | 4 | Aiman Hakim | Universiti Malaya (Sains Komputer) | [GitHub](https://github.com/aimanhakim) • [Portfolio](https://aimanhakim.github.io) | 2026-11-15 |
   ```
   *(Nota: Jika anda masih di Bab 6 dan belum menerbitkan laman GitHub Pages di Bab 8, anda boleh meletakkan pautan profil GitHub anda dahulu, dan mengemas kininya kemudian!)*

### Langkah 4: *Stage*, *Commit*, dan *Push* Perubahan Anda
Simpan fail ini, kemudian rekodkan perubahan anda dan muat naik ke akaun GitHub anda:
```bash
git add SENARAI-PELAJAR.md
git commit -m "Tambah nama [Nama Anda] ke dalam SENARAI-PELAJAR.md"
git push -u origin tambah-nama-anda
```

### Langkah 5: Hantar *Pull Request* (PR) di GitHub
1. Buka halaman repositori *Fork* anda di pelayar web GitHub.
2. Klik butang hijau **Compare & pull request** yang muncul di bahagian atas.
3. Tulis tajuk PR yang jelas seperti: `Tambah [Nama Anda] ke dalam Senarai Pelajar`.
4. Klik **Create pull request**. Penyelenggara repositori akan menyemak dan menggabungkan (*Merge*) PR anda!

---

## 🌟 Satu Permintaan Kecil (Tanda Sokongan Komuniti)

Jika panduan percuma ini telah membantu anda memahami Git & GitHub dengan lebih jelas:

1. **Klik ⭐ Star pada Repositori Ini:** Sila pastikan anda telah menekan butang **⭐ Star** di penjuru kanan atas repositori utama. Selain berfungsi sebagai *bookmark* di dalam profil anda, setiap ⭐ Star membantu lebih ramai pelajar IT di Malaysia menemui kursus percuma ini.
2. **Kongsikan Kejayaan Anda di Threads:** Ambil tangkapan skrin (*screenshot*) *Pull Request* pertama anda atau laman portfolio anda yang telah siap, dan kongsikan di **Threads**! Ceritakan pengalaman anda belajar Git dalam Bahasa Melayu supaya rakan-rakan sekelas anda turut bersemangat untuk mencuba. Jangan lupa tag saya di thread (rann.404) supaya saya dapat melihat dan memberi sokongan kepada anda.

---

## 📜 Senarai Rasmi Pelajar & Pembangun (*Hall of Fame*)

| Bil | Nama / Panggilan | Institusi / Latar Belakang | Pautan GitHub & Portfolio | Tarikh |
| :---: | :--- | :--- | :--- | :---: |
| 1 | Penyelenggara Kursus (Rann) | Komuniti Pembangun | [GitHub](https://github.com/zfrnaa) | 15-11-2026 |
| 2 | <Nama anda> | <Nama institusi dan kos ambilan> | [GitHub](https://github.com/<username>) • [Portfolio](https://example.com) | tarikh |

<!-- TAMBAH BARIS NAMA ANDA DI BAWAH BARIS INI MENGIKUT FORMAT DI ATAS -->
