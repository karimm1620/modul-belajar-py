# Daftar Materi

### Materi Dasar
1. **Variabel dan Tipe Data** - Memahami variabel, integer, float, string, dan boolean
2. **String dan Manipulasi String** - Indexing, slicing, method string, dan f-string
3. **Operator** - Operator aritmatika, assignment, perbandingan, logika, dan string
4. **Kontrol alur program** - Percabangan (if, elif, else)
5. **Perulangan** - Perulangan (for, while)
6. **Struktur Data** - List, Tuple, Set, dan Dictionary
7. **Function**
8. **Penanganan Error** - Error Handling
9. **File I/O (Input/Output)** - File Handling

### Roadmap Materi Ke Depan
- [ ] Module dan Package
- [ ] File Handling
- [ ] Object-Oriented Programming
- [ ] Mini Project

## Quick Start

### Prerequisites
- Python 3.11+ sudah terinstall di komputer Anda
- pip (Python package manager)
- Terminal/Command Prompt
- Text Editor atau IDE (VSCode, PyCharm, dll)

### Setup Awal

1. **Clone repository**
   ```bash
   git clone https://github.com/karimm1620/modul-belajar-py.git
   cd modul-belajar-py
   ```

2. **Buat virtual environment**
   
   **Linux/macOS:**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```
   
   **Windows:**
   ```bash
   python -m venv .venv
   .venv\Scripts\activate
   ```

3. **Install Jupyter**
   ```bash
   pip install jupyter
   ```

4. **Jalankan Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
   
   Browser akan otomatis terbuka di `http://localhost:8888`

5. **Setup Python kernel di VSCode (Optional)**
   - Download extension **Python** dan **Jupyter** dari VSCode marketplace
   - Buka salah satu file notebook
   - Klik tombol "Select Kernel" di kanan atas
   - Pilih kernel yang sesuai dengan virtual environment yang baru dibuat

### Update Materi

Jika Anda sudah meng-clone repository ini sebelumnya, untuk update ke versi terbaru:

```bash
git pull origin main
```

## Struktur Folder

```
modul-belajar-py/
├── README.md                          # File ini
├── .gitignore                         # File git ignore
├── materi_dasar/                      # Folder materi dasar
│   ├── variabel_dan_tipe_data.ipynb  # Materi 1: Variabel dan Tipe Data
│   ├── str_dn_manipulasi_str.ipynb   # Materi 2: String dan Manipulasi String
│   ├── operator.ipynb                # Materi 3: Operator
|   ├── kotrol_alur_program.ipynb     # Materi 4: percabangan (if-else)
│   ├── perulangan.ipynb              # Materi 5: Perulangan (while, for)
│   ├── struktur_data.ipynb           # Materi 6: Struktur data (List, Tuple, Set, dan Dictionary)
│   ├── function.ipynb                # Materi 7: Function
│   ├── penanganan_error.ipynb        # Materi 8: Penanganan Error (Error Handling)
│   ├── file_input_output.ipynb       # Materi 9: File I/O (Input/Output) (File Handling)
|   └── ...
|                    
└── ...
```

## Cara Belajar

1. **Buka notebook** sesuai urutan materi
2. **Baca penjelasan** di setiap markdown cell
3. **Pahami kode** di setiap code cell
4. **Jalankan code** dengan menekan `Shift + Enter` atau mengklik tombol Run
5. **Eksperimen** dengan mengubah nilai atau menulis kode baru
6. **Ulangi** hingga Anda benar-benar memahami konsepnya

## FAQ

### Q: Apakah saya perlu install extension di VSCode?
**A:** Opsional. Jika Anda ingin membuka notebook di VSCode, install extension Python dan Jupyter. Jika tidak, gunakan Jupyter Notebook dari terminal. Atau bisa juga menggunakan google collab di browser

### Q: Bagaimana jika saya menggunakan Python 2?
**A:** Materi ini menggunakan Python 3. Pastikan Python versi 3.11 atau lebih tinggi sudah terinstall.

### Q: Bagaimana cara menjalankan file `.py`?
**A:** Gunakan terminal dan jalankan:
```bash
python materi_dasar/input.py
```

---

**Happy Learning! 🎉**
