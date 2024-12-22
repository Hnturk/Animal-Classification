# Veri Seti Hikayesi

Bu proje, **hayvan sınıflarını** tanımak amacıyla bir **derin öğrenme** modelinin eğitilmesini hedeflemektedir. Veri seti, farklı hayvan türlerini içeren **JPEG görüntülerinden** oluşmaktadır. Bu proje kapsamında, yalnızca seçilen **10 hayvan sınıfı** kullanılacaktır. Bu sınıflar, **collie**, **dolphin**, **elephant**, **fox**, **moose**, **rabbit**, **sheep**, **squirrel**, **giant panda**, ve **polar bear**'dan oluşmaktadır. 

Veri seti hazırlık sürecinde her bir sınıftan **650 görüntü** seçilmiş ve veri setinin her bir öğesi, modelin öğrenmesi için uygun hale getirilmiştir. Görüntüler, boyutlandırma, artırma (data augmentation) ve normalizasyon işlemleri uygulanarak eğitim ve test setlerine ayrılmıştır.

Projenin amacı, **Convolutional Neural Network (CNN)** kullanarak, verilen hayvan sınıflarını doğru bir şekilde tanıyacak bir model geliştirmektir. Ayrıca, modelin doğruluğunu test etmek amacıyla veri üzerinde bazı **manipülasyonlar** yapılacak ve modelin renk sabitliği gibi faktörlere karşı ne kadar sağlam olduğu değerlendirilecektir. Sonuç olarak, modelin her türlü görüntü manipülasyonuna karşı ne kadar genellenebilir olduğunu ölçmeyi amaçlıyoruz.

kaggle proje linki: https://www.kaggle.com/code/mehmethantrk/animal-classification

Güncel olarak:
Normal Test Doğruluğu: 48.26%
Manipüle Edilmiş Test Doğruluğu: 38.72%
Renk Sabitliği Test Doğruluğu: 38.26%
