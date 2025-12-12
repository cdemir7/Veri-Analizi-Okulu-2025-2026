# Veri Analizi Okulu 2025-2026
Veri Analizi Okulu'ndaki Yapay Zeka ve Makine Öğrenmesi modülündeki dersleri düzenli, tekrar edilebilir bir yapıda takip etmek için oluşturulan depo.

## 🎯 Amaç
- Yapay Zekâ ve Makine Öğrenmesi modülünü adım adım ilerleyip tekrar edilebilir bir öğrenme arşivi kurmak.
- Haftalık notlar, notebook’lar ve veri setlerini tek yerde toplayıp baştan kurulabilir bir çalışma alanı bırakmak.
- Uygulamaları dokümante ederek hızlı referans olacak kısa kod parçaları ve pratik ipuçları derlemek.

## 🗂️ Klasör Sözlüğü
- `docs/`          : Haftalık teorik notlar (weekN.md)
- `notebooks/`     : Haftaya/konuya özgü notebook’lar
- `data/`          : Ham / ara / işlenmiş veri (bkz. `data/README.md`) (versiyonlanmaz)
- `reports/`       : Haftalık çıktılar (figures / tables / slides) (versiyonlanmaz)
- `.venv/`         : Sanal ortam (versiyonlanmaz)

## 📦 Veri Yapısı
- Ham: `data/raw/...`
- Ara (interim): `data/interim/...` (ör. SPSS outputs/syntax)
- İşlenmiş: `data/processed/...`

## 🔄 Haftalık Akış
- Notlar: `docs/weekN/weekN.md`
- Notebook: `notebooks/weekN/...`
- Raporlar: `reports/weekN/figures|tables|slides`

## 📝 Adlandırma
- Dosyalar: `DDMMYYYY_konu.md` veya `weekN_konu.md`
- Revizyon: `v1`, `v2` ya da tarih damgası.

## 🛠️ Kullanılan Teknolojiler
- Excel
- SPSS
- Python
- Jupyter Notebook / Colab
- Anaconda
