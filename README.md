Aplikasi Pencatatan Pengeluaran Harian

## Deskripsi
Aplikasi ini merupakan aplikasi sederhana berbasis Flask yang digunakan untuk mencatat pengeluaran harian pengguna.

Aplikasi dibuat untuk memenuhi tugas Platform as a Service (PaaS) menggunakan Railway sebagai layanan deployment cloud.

---

## Fitur
- Menambahkan data pengeluaran
- Menampilkan daftar pengeluaran
- Health check endpoint
- Deployment online menggunakan Railway

---

## Teknologi yang Digunakan
- Python
- Flask
- Flask-SQLAlchemy
- SQLite
- Railway
- GitHub

---

## Endpoint API

### Home
```bash
GET /
```

### Health Check
```bash
GET /health
```

### Lihat Pengeluaran
```bash
GET /pengeluaran
```

### Tambah Pengeluaran
```bash
POST /tambah
```

Contoh JSON:

```json
{
  "nama": "Makan",
  "jumlah": 15000
}
```

---

## Cara Menjalankan Localhost

Install dependency:

```bash
pip install -r requirements.txt
```

Jalankan aplikasi:

```bash
python app.py
```

---

## Deployment
Aplikasi dideploy menggunakan Railway.
