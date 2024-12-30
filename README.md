# Bike-Shairng Dashboard ✨

Aplikasi untuk menganalisis dan memvisualisasikan data koleksi Dicoding. Aplikasi ini dibuat menggunakan **Streamlit** dan memungkinkan pengguna untuk mengeksplorasi dataset interaktif dan melihat visualisasi yang menarik.

## Setup Environment di VS Code

### 1. Install Visual Studio Code (VS Code)
Pastikan Anda telah menginstal **Visual Studio Code (VS Code)**. Jika belum, Anda bisa mengunduhnya [di sini](https://code.visualstudio.com/).

### 2. Install Python dan VS Code Extension
- Pastikan Anda telah menginstal **Python** versi 3.9 ke atas di sistem Anda. Jika belum, Anda dapat mengunduhnya [di sini](https://www.python.org/downloads/).
- Install extension Python di **VS Code**. Caranya:
  1. Buka **VS Code**.
  2. Buka **Extensions** di sidebar atau tekan `Ctrl + Shift + X`.
  3. Cari `Python` dan install extension resmi dari Microsoft.

### 3. Setup Virtual Environment

1. **Buat folder proyek** (misalnya `proyek_analisis_data`):
    ```bash
    mkdir proyek_analisis_data
    cd proyek_analisis_data
    ```

2. **Buat virtual environment** dengan perintah:
    ```bash
    python -m venv venv
    ```

3. **Aktifkan virtual environment**:
    - Di Windows:
      ```bash
      .\venv\Scripts\activate
      ```
    - Di macOS/Linux:
      ```bash
      source venv/bin/activate
      ```

4. **Install dependensi**:
    Pastikan Anda sudah memiliki file `requirements.txt`. Jika belum, buat file tersebut dan masukkan dependensi berikut:
    ```
    streamlit
    pandas
    matplotlib
    seaborn
    ```

    Install dependensi dengan perintah:
    ```bash
    pip install -r requirements.txt
    ```

### 4. Buka Proyek di VS Code

1. Buka **VS Code** dan pilih **Open Folder**.
2. Pilih folder proyek yang baru saja dibuat (`proyek_analisis_data`).
3. Buka terminal di **VS Code** dengan `Ctrl + ` (tombol backtick) atau pilih **Terminal** > **New Terminal** dari menu.

### 5. Menjalankan Aplikasi Streamlit

Setelah semua terpasang, jalankan aplikasi **Streamlit** dengan perintah berikut di terminal **VS Code**:
```bash
streamlit run dashboard.py
