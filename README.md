# Intel-mage-classification-cnn-project-AKBANK-DER-N-RENME-BOOTCAMP
🌍 Akbank Bootcamp – Intel Görüntü Sınıflandırma

Bu repo, Akbank Derin Öğrenme Bootcamp kapsamında geliştirilmiştir.
Proje, Intel Image Classification Dataset üzerinde CNN tabanlı bir model kurarak görüntü sınıflarını (dağ, deniz, orman, sokak vb.) sınıflandırmayı amaçlamaktadır.

📌 Giriş

Bu projede:

Veri seti: Intel Image Classification (Kaggle) https://www.kaggle.com/datasets/puneet6060/intel-image-classification

Yöntem: Convolutional Neural Network (CNN)

Amaç: Görüntüleri 6 farklı sınıfa olabildiğince yüksek bir doğruluk oranıyla ayırmak

Kullanılan teknolojiler: TensorFlow, Keras, NumPy, Matplotlib, Seaborn, OpenCV

Projenin teknik anlatımı, notebook içerisindeki markdown hücrelerinde detaylı olarak verilmiştir.




📊 Metrikler ve Yorumlar

Modelin performansı aşağıdaki metriklerle değerlendirilmiştir:

Accuracy (Doğruluk): Eğitim ve doğrulama süreçlerinde doğruluk değerleri takip edilmiştir.

Loss (Kayıp): EarlyStopping sayesinde model aşırı öğrenmeden korunmuştur.

Confusion Matrix: Bazı sınıflar (ör. dağ ve orman) arasında karışıklık gözlemlenmiştir.

Classification Report: Precision, recall ve F1 skorları sınıflara göre değerlendirilmiştir.




🧠 Çıkarımlar

Model, görsel olarak çok benzer sınıfları ayırt etmekte zorlanmıştır.

Data augmentation (rotation, shift, flip) sayesinde overfitting azaltılmıştır.

Callback mekanizmaları (EarlyStopping, ReduceLROnPlateau, ModelCheckpoint) eğitim sürecini daha verimli hale getirmiştir.

Bu sonuçlardan hareketle, modelin genel performansının tatmin edici, ancak bazı sınıflarda iyileştirmeye ihtiyaç duyduğu yorumunu yapabiliriz.



🔮 Sonuç ve Gelecek Çalışmalar

Bu çalışmada temel bir CNN modeli ile başarılı sonuçlar elde edilmiştir.
Ancak ilerleyen aşamalarda:

Daha derin modeller (ResNet, EfficientNet, VGG16 transfer learning) denenebilir.

Gerçek zamanlı veri toplama ve sınıflandırma senaryoları geliştirilebilir.

Unsupervised yöntemler eklenerek daha kapsamlı bir proje haline getirilebilir.

Bu proje, bootcamp sonrası da geliştirilmeye açık olup, yeni özellikler eklenerek daha profesyonel hale getirilebilir.

Linkler
https://www.kaggle.com/datasets/puneet6060/intel-image-classification

  https://www.kaggle.com/code/sefayolsal0661/akbank-derin-renme-cnn
