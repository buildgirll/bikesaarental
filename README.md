# Bike Rental Dashboard ✨

## Setup Environment - Anaconda
```
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt
```

## Setup Environment - Shell/Terminal
```
mkdir proyek_analisis_data
cd proyek_analisis_data
pipenv install
pipenv shell
pip install -r requirements.txt
```
# Bike Rental Analysis Dashboard

Dashboard ini menampilkan analisis interaktif dari data penyewaan sepeda berdasarkan kondisi cuaca, musim, dan jam-jam puncak. Dashboard dibangun menggunakan `Streamlit` dan menggunakan visualisasi yang dihasilkan oleh `Seaborn` dan `Matplotlib`.
# File yang Dibutuhkan
Pastikan file CSV berikut berada di direktori yang sama dengan dashboard_analisis_data.py:

cuaca_df_cleaned.csv - Data penyewaan sepeda berdasarkan cuaca
musim_df_cleaned.csv - Data penyewaan sepeda berdasarkan musim
waktu_puncak_df_cleaned.csv - Data penyewaan sepeda berdasarkan waktu puncak
Jika file CSV tidak ditemukan, pastikan jalur file diatur dengan benar di dalam skrip.

# Opsi Filter
Pada sidebar dashboard, Anda dapat memfilter data dengan berbagai pilihan, termasuk:

- Jam Puncak: Pilih jam untuk melihat data penyewaan sepeda.
- Musim: Pilih musim untuk melihat pola penyewaan sepeda pada musim tertentu.
# Visualisasi
- Weather and Bike Rentals: Menampilkan pengaruh kondisi cuaca terhadap jumlah penyewaan sepeda.
- Season and Rentals: Menunjukkan pola penyewaan sepeda di setiap musim.
- Peak Hours and Rentals: Menampilkan data penyewaan sepeda pada jam-jam puncak berdasarkan hari kerja dan non-kerja.
# Kesimpulan
Dashboard ini memberikan wawasan interaktif mengenai penyewaan sepeda berdasarkan data cuaca, musim, dan jam-jam puncak. Kesimpulan dari analisis dapat ditemukan langsung di dashboard.










  
