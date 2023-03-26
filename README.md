Buku kelas publik {
  Judul string;
  kategori string;
  Penulis string;
  Penerbit string;
  int tahun;
  static final String[] CATEGORIES = {"Teknik", "Manajemen", "Fiksi", "Lainnya"};

  Buku publik(Judul string, Kategori string, Penulis string, Penerbit string, tahun int){
    this.judul = judul;
    this.kategori = kategori;
    this.pengarang = penulis;
    this.publisher = penerbit;
    this.year = tahun;
  }
}
