# Airbnb Price Prediction

Bu proje, İstanbul Airbnb ilanları üzerinden fiyatları analiz etmek ve makine öğrenmesi ile fiyat tahmini yapmak için hazırlanmıştır.

## Proje Amacı

Airbnb ilanlarında fiyatı etkileyen temel faktörleri anlamak ve bu değişkenleri kullanarak fiyat tahmin modeli geliştirmek.

## Kullanılan Teknolojiler

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- Jupyter Notebook

## Repository Yapısı

```text
airbnb-price-prediction/
│
├── README.md
├── requirements.txt
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── airbnb_analysis.ipynb
│
├── presentation/
│   └── business_presentation.pdf
│
├── outputs/
│   ├── figures/
│   └── model_results/
│
└── medium_link.txt
```

## Proje Adımları

1. Veri setinin yüklenmesi
2. Veri temizleme
3. Eksik değer analizi
4. Keşifsel veri analizi
5. Görselleştirme
6. Feature engineering
7. Regresyon modeli kurulması
8. Model performansının değerlendirilmesi
9. İş sonuçlarının yorumlanması

## Hedef Değişken

Modelin tahmin etmeye çalıştığı değişken:

```text
price
```

## Örnek Analiz Başlıkları

- Fiyat dağılımı
- Oda tipine göre fiyat farklılıkları
- Mahalle / bölge bazlı fiyat değişimi
- Konumun fiyata etkisi
- Yorum sayısı ve müsaitlik gibi değişkenlerin etkisi

## Modelleme

Projede temel olarak regresyon problemi ele alınmıştır.

Kullanılabilecek modeller:

- Linear Regression
- Random Forest Regressor
- Decision Tree Regressor
- Gradient Boosting Regressor

## İş Yorumu

Bu proje, Airbnb ev sahiplerinin fiyat belirleme stratejisini anlamasına ve yeni ilanlar için makul fiyat tahmini yapılmasına yardımcı olabilir.

## Çalıştırma

Gerekli paketleri yüklemek için:

```bash
pip install -r requirements.txt
```

Notebook'u çalıştırmak için:

```bash
jupyter notebook notebooks/airbnb_analysis.ipynb
```

## Sunum ve Blog

- `presentation/` klasörü business sunumu için ayrılmıştır.
- `medium_link.txt` dosyası Medium blog bağlantısı için ayrılmıştır.

## Not

Bu proje eğitim ve portföy amacıyla hazırlanmıştır.
