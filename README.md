# Twitter Sentiment Analysis

## Proje Hakkında
Bu proje, Twitter verileri üzerinde duygu analizi yapmayı amaçlamaktadır. Gözetimli öğrenme teknikleri kullanılarak tweetlerin pozitif, negatif veya nötr duygu taşıyıp taşımadığı sınıflandırılmıştır. Proje, veri ön işleme, model seçimi, eğitim, değerlendirme ve sonuçların yorumlanmasını içermektedir.

## Kullanılan Veri Seti
- Twitter üzerinden çekilmiş tweetler
- Veri setinde metinler ve etiketli duygu sınıfları bulunmaktadır.
- Veri seti detayları ve kaynakları notebook içerisinde açıklanmıştır.

## Proje Adımları
1. **Keşifsel Veri Analizi (EDA):**  
   Pandas, Matplotlib ve Seaborn kullanılarak veri setinin genel özellikleri incelenmiş, görselleştirmeler yapılmıştır.

2. **Veri Ön İşleme:**  
   Metin temizleme, tokenizasyon, stopword çıkarımı ve gerekirse etiketlerin dönüştürülmesi yapılmıştır.

3. **Model Seçimi:**  
   Logistic Regression, Decision Tree, KNN ve SVM gibi farklı sınıflandırma algoritmaları denenmiştir.

4. **Model Eğitimi ve Değerlendirme:**  
   Modellerin doğruluk, precision, recall, f1-score gibi performans metrikleri hesaplanmış, çapraz doğrulama uygulanmıştır.

5. **Sonuç ve Yorumlar:**  
   En iyi performansı Logistic Regression ve SVM göstermiştir. Model seçimi ve gelecekte yapılabilecek geliştirmeler README dosyasında açıklanmıştır.

## Kullanılan Teknolojiler ve Kütüphaneler
- Python 3.x
- Jupyter Notebook
- Pandas, Numpy
- Scikit-learn
- Matplotlib, Seaborn


## Kaggle Notebook Linki
[Twitter Sentiment Analysis Notebook](https://www.kaggle.com/code/furkannuzum/twittersentimentanalysis)


**Not:** Proje dosyaları ve detaylı kod açıklamaları `twittersentimentanalysis.ipynb` dosyasında bulunmaktadır.
