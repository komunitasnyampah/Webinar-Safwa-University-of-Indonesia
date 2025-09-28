# Webinar-Safwa-University-of-Indonesia

Membangun Profil Riset & Akademik Profesional (Conference Proceeding)

<!-- Ganti `xxxxx` dengan DOI Zenodo ketika sudah tersedia -->


Ringkas: Repo ini menyimpan materi webinar, template, dan berkas pendukung untuk membangun identitas riset global (ORCID), manajemen publikasi digital (DOI), serta pemanfaatan repositori terbuka (Zenodo). Disertai pengantar struktur penulisan akademik berbasis IMRAD, tata cara sitasi & referensi ilmiah, serta pengenalan jenis karya ilmiah (artikel, jurnal, paper, preprint).
Use-case: mahasiswa, dosen, peneliti, dan penyelenggara webinar yang ingin menaikkan kualitas publikasi sesuai standar nasional (SINTA) dan internasional (Scopus).

⸻

🔗 Tautan Utama
	•	Zenodo Record: masukkan link Zenodo rilis ini
	•	Halaman Komunitas/Organisasi: opsional – tambahkan website/landing
	•	Contact: Muhamad Oky Muhlisin (Project Lead)

⸻

📦 Isi & Struktur Repo

Direkomendasikan (boleh sesuaikan dengan kebutuhanmu):

.
├─ /slides/              # File presentasi (PDF/PPTX)
├─ /templates/           # Template dokumen (DOCX/ODT), surat, sertifikat, receipt
├─ /guides/              # Panduan langkah demi langkah (MD/PDF)
├─ /assets/              # Logo, banner, screenshot
├─ /examples/            # Contoh artikel IMRAD, contoh sitasi & daftar pustaka
├─ /data/                # Contoh metadata (JSON/CSV) untuk DOI/Zenodo/ORCID
└─ README.md

Tip: simpan gambar banner/screenshot ke folder /assets lalu tampilkan di README:
![Banner](assets/banner.png)

⸻

🧭 Cakupan Materi
	1.	ORCID – pembuatan, sinkronisasi karya, dan praktik afiliasi yang benar.
	2.	DOI & Zenodo – konsep dasar DOI, cara deposit, metadata minimum yang baik.
	3.	IMRAD – Introduction, Methods, Results, and Discussion + Abstract & Conclusion.
	4.	Sitasi & Referensi – contoh in-text citation (APA/IEEE) dan reference list.
	5.	Jenis Karya Ilmiah – artikel, jurnal, paper, preprint (kapan memilih mana).
	6.	Kurikulum Mini – alur cepat membangun profil akademik yang dapat diverifikasi.

⸻

🚀 Cara Pakai (Quickstart)
	1.	Unduh materi di /slides dan /guides.
	2.	Pakai template di /templates untuk naskah/artikel/sertifikat/receipt.
	3.	Ikuti panduan:
	•	guides/01_orcid.md → buat ORCID & hubungkan karya.
	•	guides/02_zenodo.md → siapkan metadata & unggah ke Zenodo.
	•	guides/03_imrad.md → susun artikel dengan pola IMRAD.
	•	guides/04_citation.md → terapkan sitasi & referensi otomatis.
	4.	Publikasi: unggah naskah ke Zenodo (atau OJS), input DOI di naskah, perbarui README (badge DOI).
	5.	Opsional (GitHub Pages): aktifkan Pages di Settings → Pages untuk membuat microsite materi.

⸻

📝 Contoh Sitasi (APA)

Muhlisin, M. O. (2025). Webinar Membangun Profil Riset dan Akademik Profesional (Conference proceeding). Safwa University of Indonesia. Zenodo. https://doi.org/10.5281/zenodo.xxxxxxx

BibTeX

@inproceedings{muhlisin2025webinar,
  author    = {Muhlisin, Muhamad Oky},
  title     = {Webinar Membangun Profil Riset dan Akademik Profesional},
  booktitle = {Conference Proceeding},
  year      = {2025},
  publisher = {Safwa University of Indonesia},
  doi       = {10.5281/zenodo.xxxxxxx},
  url       = {https://doi.org/10.5281/zenodo.xxxxxxx}
}


⸻

🧩 Template & Otomasi
	•	DOCX Template IMRAD (/templates/imrad.docx)
	•	Template Sertifikat/Receipt (/templates/certificate.docx, receipt.docx)
	•	Contoh Metadata Zenodo (/data/zenodo-metadata.json)
	•	Contoh Daftar Pustaka (/examples/references.bib)

Integrasi lanjutan (opsional):
	•	GitHub Actions untuk membangun PDF dari Markdown (Pandoc).
	•	CITATION.cff agar repo dapat disitasi otomatis di GitHub.

⸻

✅ Checklist Rilis
	•	Banner/logo di /assets
	•	DOI Zenodo sudah aktif & badge diperbarui
	•	Slides & handout di /slides
	•	Template naskah/sertifikat/receipt di /templates
	•	Panduan lengkap di /guides
	•	LICENSE (CC BY-SA 4.0) & CITATION.cff

⸻

👥 Kontributor
	•	Project Lead: Muhamad Oky Muhlisin
	•	Institusi: Safwa University of Indonesia
	•	Peran Tambahan: editor, penyusun materi, dan pengelola rilis.

Ingin berkontribusi? Buka Issue atau Pull Request dengan perubahan terarah (materi, perbaikan template, atau contoh baru).

⸻

📄 Lisensi

Konten repo ini berlisensi Creative Commons BY-SA 4.0.
Anda bebas berbagi & adaptasi, wajib menyertakan atribusi dan merilis turunan dengan lisensi serupa.
Lihat berkas LICENSE.

⸻

🌍 English Summary

This repository hosts the webinar materials, templates, and guides for building a verifiable research identity (ORCID), managing publications via DOI, and leveraging open repositories (Zenodo). It also introduces IMRAD structure, citation & referencing practices, and types of scholarly outputs (article, journal paper, preprint).
Target users: students, lecturers, researchers, and webinar organizers who aim for higher-quality publications aligned with national and international standards.

⸻

Catatan kecil
	•	Jika kamu ingin, aku bisa tambahkan CITATION.cff, Pandoc Action (MD → PDF), dan Pages layout agar repo ini langsung jadi microsite materi. Tinggal bilang, nanti kubuatin file-nya lengkap.