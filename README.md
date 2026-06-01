# Müşteri Terk Tahmini Projesi

## Proje Amacı

Bu projede, müşterilerin bir hizmeti terk edip etmeyeceğini tahmin etmek amacıyla makine öğrenmesi yöntemleri kullanılmıştır. Amaç, müşteri davranışlarını analiz ederek müşteri kaybını önceden tahmin edebilmektir.

## Veri Seti

Kullanılan veri seti:

Telco Customer Churn Dataset

Veri setinde müşterilere ait demografik bilgiler, abonelik bilgileri, sözleşme türleri, ödeme yöntemleri ve hizmet kullanım bilgileri bulunmaktadır.

## Veri Ön İşleme

Proje kapsamında aşağıdaki veri ön işleme işlemleri uygulanmıştır:

- Eksik verilerin temizlenmesi
- TotalCharges değişkeninin sayısal formata dönüştürülmesi
- Kategorik verilerin One-Hot Encoding yöntemi ile sayısallaştırılması
- Verilerin eğitim ve test kümelerine ayrılması
- StandardScaler kullanılarak ölçeklendirme yapılması

## Kullanılan Algoritmalar

Bu projede iki farklı makine öğrenmesi algoritması kullanılmıştır:

1. Logistic Regression
2. Random Forest Classifier

## Model Değerlendirme

Modeller aşağıdaki performans metrikleri kullanılarak değerlendirilmiştir:

- Accuracy
- Precision
- Recall
- F1 Score

Ayrıca modellerin doğruluk oranları grafik ile karşılaştırılmıştır.

## Sonuçlar

Yapılan analiz sonucunda:

- Logistic Regression modeli yaklaşık %78 doğruluk elde etmiştir.
- Random Forest modeli yaklaşık %79 doğruluk elde etmiştir.

Sonuçlara göre Random Forest modeli daha yüksek performans göstermiştir.

## Kullanılan Kütüphaneler

- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

## Geliştirici

Sena Tatar

