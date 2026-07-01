# Dataset

Dataset berupa sekumpulan citra (image) yang dibagi menjadi dua bagian.

## Data Latih (Train)

- **26.527 citra** dengan label kelas
- Disimpan dalam folder `train/` dengan setiap kelas pada subfolder terpisah
- Digunakan untuk eksplorasi, preprocessing, pengembangan model, training, validasi, dan penyempurnaan

## Data Uji (Test)

- **1.458 citra** tanpa label
- Disimpan dalam folder `test/` dengan nama file berurutan
- Hanya digunakan untuk prediksi akhir (dilarang untuk training, validasi, model selection, atau hyperparameter tuning)
- Urutan nama file sesuai dengan `submission.csv`

## Batasan Penggunaan

- Hanya informasi visual (image) yang boleh digunakan
- Metadata, label eksternal, atau sumber data lain di luar gambar **tidak diperkenankan**
- Data augmentation terhadap Data Latih diperbolehkan
- Model pre-trained (EfficientNet, ResNet, ConvNeXt, Vision Transformer) diperbolehkan untuk transfer learning selama tidak pernah dilatih dengan dataset kompetisi ini
- **Tidak boleh** menambahkan data citra berlabel dari sumber lain

## Tautan

- Download dataset: https://bit.ly/datasetbdc2026
- Template submission: https://bit.ly/submissionbdc2026
