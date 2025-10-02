# 🚢 Titanic Hayatta Kalma Tahmini

Bu proje, Kaggle'ın ünlü "Titanic: Machine Learning from Disaster" yarışması veri setini kullanarak yolcuların hayatta kalma durumlarını tahmin etmeyi amaçlar. Kapsamlı veri analizi, eksik veri doldurma ve özellik mühendisliği adımları uygulanmıştır.

## 🎯 Proje Amacı

Veri setindeki yolcu özelliklerini (yaş, cinsiyet, sınıf, bilet ücreti vb.) kullanarak, belirli bir yolcunun kazadan sağ kurtulup kurtulamayacağını yüksek doğrulukla tahmin eden bir sınıflandırma modeli geliştirmektir.

## ✨ Temel Özellikler ve Aşamalar

- **Kapsamlı Veri Analizi (EDA):** Hayatta kalma oranlarını etkileyen faktörlerin (cinsiyet, bilet sınıfı vb.) incelenmesi.
- **Özellik Mühendisliği:** Yeni özellikler oluşturulması (örneğin Aile Büyüklüğü, Unvan/Kibar Hitap şekli).
- **Eksik Veri Yönetimi:** Yaş ve bilet ücreti gibi eksik verilerin uygun yöntemlerle doldurulması.
- **Model Eğitimi:** Tahmin için Lojistik Regresyon, Karar Ağacı veya Rastgele Orman gibi sınıflandırma algoritmalarının kullanılması.
- **Model Değerlendirmesi:** Doğruluk (Accuracy) ve F1 Skoru gibi metriklerle modelin performansının ölçülmesi.

## 🛠️ Kullanılan Teknolojiler ve Kütüphaneler

Bu projenin çalışması için temel Python veri bilimi kütüphanelerine ihtiyacınız olacaktır.

- **Python** (Tercihen 3.8+)
- **Pandas:** Veri işleme ve analizi için.
- **Numpy:** Sayısal hesaplamalar için.
- **Matplotlib / Seaborn:** Veri görselleştirme için.
- **Scikit-learn:** Makine öğrenimi algoritmaları ve model değerlendirme için.

### Kurulum

Aşağıdaki komutu kullanarak gerekli kütüphaneleri tek seferde kurabilirsiniz:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
