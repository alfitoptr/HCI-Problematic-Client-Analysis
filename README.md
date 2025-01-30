# Home Credit Indonesia - Problematic Client Analysis

## Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis dan mengklasifikasikan klien bermasalah di Home Credit Indonesia menggunakan model machine learning. Tujuan utama adalah mengidentifikasi faktor-faktor yang berkontribusi terhadap status klien yang bermasalah dan membangun model prediktif yang akurat.

## Tujuan
- Membangun model machine learning untuk mengklasifikasikan klien bermasalah.
- Mengidentifikasi faktor-faktor utama yang menyebabkan klien menjadi bermasalah.
- Menyediakan rekomendasi berdasarkan analisis untuk mengurangi risiko klien bermasalah.

## Struktur Repositori
- **output/**: Berisi file `model.pkl` (model machine learning yang telah dilatih) dan `submission.csv` (hasil prediksi).
- **notebook.ipynb**: Berisi analisis data dan pembangunan model.
- **prediction.ipynb**: Berisi kode untuk melakukan prediksi pada klien yang ditugaskan.
- **variable.csv**: Berisi daftar variabel yang digunakan dalam analisis.

## Saran Tindakan Untuk Home Credit Indonesia

### Optimalisasi Kebijakan Kredit
- **Tingkatkan pengawasan** pada klien dengan pendidikan Secondary / Special dan pekerjaan Working.
  - Batasi jumlah kredit yang dapat diajukan oleh klien dalam kategori ini atau tambahkan persyaratan lebih ketat, seperti agunan atau analisis keuangan mendalam.
- **Buat kebijakan kredit yang lebih fleksibel** untuk klien dengan pendidikan Lower Secondary dan Incomplete Higher, karena mereka cenderung memiliki risiko kredit bermasalah lebih rendah.
- **Tingkatkan promosi dan penawaran kredit** kepada Pensioners dan State Servants, karena mereka memiliki pendapatan stabil dan risiko lebih rendah.

### Pengembangan Strategi untuk Mengurangi Kredit Bermasalah
- **Sediakan program edukasi keuangan** bagi klien dengan pendidikan Secondary / Special, untuk meningkatkan kesadaran tentang pengelolaan utang dan pengeluaran.
- **Implementasikan sistem pemantauan dini** untuk mendeteksi tanda-tanda potensi gagal bayar, terutama pada klien yang termasuk dalam kategori risiko tinggi.
- **Bangun komunikasi yang lebih proaktif** dengan klien dalam kategori risiko tinggi untuk memberikan solusi restrukturisasi kredit atau saran keuangan jika diperlukan.

## Cara Menggunakan
1. **Klon repositori**:
   ```bash
   git clone https://github.com/username/HCI-Problematic-Client-Analysis.git
   
2. Jalankan notebook:

   - Buka notebook.ipynb untuk melihat analisis dan pembangunan model.
   - Buka prediction.ipynb untuk melakukan prediksi pada data baru.

3. Gunakan model:

   - Model yang telah dilatih dapat ditemukan di output/model.pkl.
   - Hasil prediksi dapat ditemukan di output/submission.csv.

## Lisensi
Proyek ini dilisensikan di bawah MIT License.

## Kontak
Untuk pertanyaan lebih lanjut, silakan hubungi di alfito.pfp@gmail.com.
