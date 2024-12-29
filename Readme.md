# Shutdown Timer

Shutdown Timer adalah aplikasi sederhana yang memungkinkan Anda untuk menjadwalkan shutdown komputer Anda setelah jangka waktu tertentu. Aplikasi ini dibuat menggunakan `customtkinter`.

## Fitur

- Menjadwalkan shutdown komputer setelah jangka waktu tertentu (jam, menit, detik).
- Membatalkan shutdown yang dijadwalkan.
- Menampilkan hitungan mundur waktu yang tersisa sebelum shutdown.

## Persyaratan

- Python 3.x
- Library `customtkinter`

## Instalasi

1. Clone repositori ini ke komputer Anda:

    ```bash
    git clone https://github.com/username/shutdown-timer.git
    ```

2. Pindah ke direktori proyek:

    ```bash
    cd shutdown-timer
    ```

3. Instal dependensi yang diperlukan:

    ```bash
    pip install customtkinter
    ```

## Penggunaan

1. Jalankan aplikasi:

    ```bash
    python app/main.py
    ```

2. Masukkan waktu shutdown yang diinginkan dalam jam, menit, dan detik.
3. Klik tombol `Submit` untuk menjadwalkan shutdown.
4. Klik tombol `Cancel` untuk membatalkan shutdown yang dijadwalkan.

## Struktur Proyek

```plaintext
shutdown-timer/
│
├── app/
│   ├── main.py
│   └── icon.ico
│
├── README.md
└── requirements.txt
