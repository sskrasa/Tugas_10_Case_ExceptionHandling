# TUGAS 8 PBO — EXCEPTION HANDLING

**Mata Kuliah:** Pemrograman Berorientasi Objek
**Sesi:** 10 (Praktikum Exception Handling)





## 📁 Struktur Folder

Tugas_10_Case_ExceptionHandling/
│
├── percobaan1/
│ ├── Error.java
│ └── Fix.java
├── percobaan2/
│ ├── Error.java
│ └── Fix.java
├── percobaan3/
│ ├── Error.java
│ └── Fix.java
├── percobaan4/
│ ├── Error.java
│ └── Fix.java
├── percobaan5/
│ └── Exception5.java
├── percobaan6/
│ └── ThrowExample.java
├── percobaan7/
│ └── ThrowExample2.java
├── percobaan8/
│ └── Test3.java
├── percobaan9/
│ └── Propagate.java
├── percobaan10/
│ └── RandomAccessRevisi.java
├── percobaan11/
│ └── RangeErrorException.java
└── percobaan12/
└── Eksepsi.java









## Ringkasan Percobaan

| No | Topik | Penjelasan |
|----|-------|------------|
| 1 | ArrayIndexOutOfBoundsException | Akses array di luar batas |
| 2 | ArrayIndexOutOfBoundsException + Reset | Error array, index direset ke 0 |
| 3 | ArithmeticException | Pembagian bilangan dengan nol |
| 4 | Multiple Catch | Dua error berbeda dalam satu try |
| 5 | getMessage() & printStackTrace() | Mendapatkan pesan error dan stack trace |
| 6 | throw | Melempar exception manual |
| 7 | throw Exception | Melempar exception dengan pesan |
| 8 | throws vs finally | Method lempar exception vs pakai finally |
| 9 | Propagate | Exception menyebar ke method pemanggil |
| 10 | File I/O Exception | FileNotFoundException & IOException |
| 11 | Custom Exception | Membuat exception sendiri |
| 12 | Multiple Catch & Finally | Contoh lengkap |

---

## Menjalankan

```bash
# Contoh percobaan1
cd percobaan1
javac Error.java
java Error
javac Fix.java
java Fix
