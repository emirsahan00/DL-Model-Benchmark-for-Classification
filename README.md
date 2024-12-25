# Deep Learning Model Comparisın for Classification
Bu projede, atık sınıflandırması için en doğru modeli belirlemek amacıyla popüler derin öğrenme mimarilerinin performansı test edilmiş ve karşılaştırılmıştır.
Karşılaştırılan modeller:

- Xception
- DenseNet121
- InceptionV3
- InceptionResNetV2
- VGG16
- VGG19

## Sonuçlar 
Modeller, bir atık sınıflandırma veri seti üzerinde test doğruluklarına göre değerlendirilmiştir. Sonuçlar aşağıdaki grafikte özetlenmiştir:


<img src="https://github.com/user-attachments/assets/1c8a396a-1668-4cb7-9cdf-a837784884c6" alt="deneme2" width="600"/>


Görüldüğü üzere, **Xception modeli %89.63** test doğruluğu ile diğer modellerden daha iyi performans göstermiştir.

## Veri Seti

Bu projede, herkese açık bir atık sınıflandırma veri seti kullanılmıştır. Veri seti, plastik, metal, kağıt, cam ve organik atık gibi çeşitli atık kategorilerine ait etiketlenmiş görüntülerden oluşmaktadır. 

Veri Seti Boyutu : Yaklaşık 2527 görüntü   
Sınıf Sayısı : 6   
Kaynak : [Kaggle Split Garbage Dataset](https://www.kaggle.com/datasets/andreasantoro/split-garbage-dataset)


## Uygulama  

Proje, TensorFlow ve Keras kullanılarak Python dilinde gerçekleştirilmiştir. Her model, adil bir karşılaştırma yapabilmek için aynı şartlarda eğitilmiştir. Projenin ana dosyası BenchmarkingModels.ipynb formatında bir Jupyter Notebook dosyasıdır.  

## Kütüphaneler 
- **TensorFlow**
- **Keras**
- **NumPy**
- **Matplotlib**
- **Pandas**

## Eğitim Detayları 

**Girdi Boyutları :** 224x224, 299x299

**Batch Size :** 256

**Epoch Sayısı :** 30

**Optimizasyon Yöntemleri :** RMSprop, SGD, Adam, Nadam

## Sonuç 
Bu karşılaştırma çalışması, **Xception** modelinin atık sınıflandırma görevi için en uygun performansı sunduğunu göstermektedir. Gelecekteki çalışmalar, ek modellerin denenmesi, hiperparametre optimizasyonu veya veri arttırma teknikleri ile doğruluğun daha da artırılmasını araştırabilir.











