# Alzheimer Tespiti - Makine Ogrenmesi

Hasta klinik verileri kullanilarak Alzheimer hastaligi tespiti yapan makine ogrenmesi projesi.

## Veri Seti

`veriseti.csv` dosyasi hasta demografik ve klinik verilerini icermektedir:

- **Demografik:** Yas, cinsiyet, etnik koken, egitim seviyesi
- **Saglik Gostergeleri:** BMI, kolesterol, tansiyon degerleri
- **Yas Tarzi:** Sigara, alkol, fiziksel aktivite, diyet kalitesi, uyku kalitesi
- **Tibbi Gecmis:** Aile gecmisi, kalp hastaligi, diyabet, depresyon
- **Bilisssel Testler:** MMSE skoru, fonksiyonel degerlendirme
- **Hedef:** `Diagnosis` (0 = Alzheimer yok, 1 = Alzheimer)

## Icerik

| Dosya | Aciklama |
|-------|----------|
| `detection.ipynb` | Veri analizi, model egitimi ve degerlendirme |
| `veriseti.csv` | Hasta verileri (2000+ kayit, 35 ozellik) |

## Kullanim

```bash
jupyter notebook detection.ipynb
```

## Gereksinimler

```
pandas
numpy
scikit-learn
matplotlib
seaborn
jupyter
```

## Teknolojiler

- Python 3
- Jupyter Notebook
- Scikit-learn
- Pandas / NumPy
