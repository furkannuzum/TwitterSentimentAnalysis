# Twitter Sentiment Analysis Projesi

## Proje Hakkında
Bu proje kapsamında, Twitter'dan toplanan tweet verileri kullanılarak duygu analizi yapılmıştır. Amaç, bir tweet'in pozitif mi, negatif mi yoksa nötr mü olduğunu otomatik olarak sınıflandırabilen bir model geliştirmektir. Sosyal medya üzerindeki duygu durumunu anlamak, markalar ve kurumlar için oldukça önemlidir ve bu proje de bu ihtiyaca yönelik bir çözüm sunmayı hedeflemektedir.

## Veri Seti ve Problem Tanımı
Kullanılan veri seti, çeşitli tweet'lerin metin içeriklerini ve bunlara ait duygu etiketlerini içermektedir. Gözetimli öğrenme yöntemleriyle bu tweet'ler sınıflandırılmıştır. Proje temel olarak ikili sınıflandırma olarak ele alınmış ancak gerektiğinde çoklu sınıflandırmaya da uyarlanabilir.

## Kullanılan Yöntemler ve Modeller
Projede aşağıdaki algoritmalar denenmiştir:  
- Logistic Regression  
- Decision Tree Classifier  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  

Modeller, veri ön işleme ve özellik mühendisliği adımlarından sonra eğitilmiş ve çapraz doğrulama ile performansları değerlendirilmiştir.

## Sonuçlar ve Model Seçimi
- Logistic Regression ve SVM modelleri en yüksek doğruluk oranlarını elde etti.  
- Decision Tree ve KNN modelleri, özellikle dengesiz sınıflar nedeniyle daha düşük performans gösterdi.  
- Model açıklanabilirliği ve eğitim hızı göz önüne alınarak Logistic Regression tercih edildi.

## Projenin Gerçek Dünya Katkısı
Bu proje, sosyal medya analizleri, müşteri duygu takibi ve halkla ilişkiler alanlarında kullanılabilir. Otomatik duygu sınıflandırması sayesinde hızlı ve doğru karar destek sistemleri geliştirilebilir.

## İyileştirme Fırsatları
- Daha büyük ve farklı veri kaynaklarıyla modelin genellenebilirliği artırılabilir.  
- Derin öğrenme tabanlı doğal dil işleme yöntemleri (BERT, GPT gibi) entegre edilebilir.  
- Modelin sonuçları gerçek zamanlı analiz yapabilen bir web uygulaması şeklinde sunulabilir.  
- Veri ön işleme aşaması geliştirilerek daha temiz ve anlamlı özellikler çıkarılabilir.

## Proje Dosyaları
- `twittersentimentanalysis.ipynb`: Kodlar ve detaylı açıklamalar.  
- `README.md`: Proje özeti, sonuçlar ve geliştirme önerileri.

## Kaggle Linki
[Twitter Sentiment Analysis Notebook](https://www.kaggle.com/code/furkannuzum/twittersentimentanalysis/notebook)

---

Sorularınız ve önerileriniz için iletişime geçebilirsiniz.  
Teşekkürler!
