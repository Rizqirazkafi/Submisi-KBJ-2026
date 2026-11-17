# Submisi-KBJ-2026
Repositori ini merupakan tempat untuk mengunggah hasil penelitian berupa draft paper, source code, dataset, dan aspek pendukung lainnya sebagai bentuk pertanggungjawaban mahasiswa S2 Departemen Informatika pada mata kuliah Komputasi Berbasis Jaringan (KBJ) Institut Teknologi Sepuluh Nopember (ITS) Semester 1 2026.

Segala bentuk pertanggungjawaban mengenai orisinalitas penelitian dikembalikan ke author.

## Struktur Direktori
/
└── Nama_Lengkap_Mahasiswa
    ├── README.md
    ├── paper
    │   ├── article.tex
    │   ├── article.bib
    │   ├── article.docx
    │   ├── article.pdf
    │   └── image.png
    ├── src
    ├── results
    └── datasets.md

### Penjelasan Isi Direktori
1. Setiap mahasiswa meng-clone git repo ini kemudian menambahkan folder dengan nama lengkap masing-masing.
1. README.md berisi Nama Lengkap, NIM, judul, abstract, dan keyword.
1. Direktory "paper" berisi file mentah paper (tex, bib, png) serta hasil cetak paper berupa file pdf.
1. Direktori "src" berisi source code dari penelitian.
> Disarankan menggunakan docker dengan menyertakan Dockerfile,nix-flake, atau devenv agar lebih mudah di replikasi untuk memastikan reproducibility penelitian.

> Apabila tidak menyertakan, diwajibkan memberikan detail berupa versi library, framework, dan bahasa pemrograman yang dipakai di akhir README.md

1. Direktori "results" berisi hasil penelitian, dapat berupa tabel dan/atau gambar yang disertai penjelasan singkat mengenai hasil penelitian tersebut.
1. File "datasets.md" berisi url dari setiap dataset yang digunakan pada penelitian.

### Metode submisi 
Clone -> Add -> Commit -> Pull Request
