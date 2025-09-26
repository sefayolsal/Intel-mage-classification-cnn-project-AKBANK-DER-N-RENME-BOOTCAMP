# Intel-mage-classification-cnn-project-AKBANK-DER-N-RENME-BOOTCAMP
AKBANK DERİN ÖĞRENME BOOTCAMPİ kapsamında bu proje, kapsamlı veri artırma teknikleri ve özelleştirilmiş bir Evrişimli Sinir Ağı (CNN) mimarisi kullanarak bir görüntü veri seti üzerindeki sınıflandırma doğruluğunu maksimize etmeyi amaçlamaktadır
🌍 Akbank Bootcamp – Intel Görüntü Sınıflandırma

Bu repo, Akbank Derin Öğrenme Bootcamp kapsamında geliştirilmiştir.
Proje, Intel Image Classification Dataset üzerinde CNN tabanlı bir model kurarak görüntü sınıflarını (dağ, deniz, orman, sokak vb.) sınıflandırmayı amaçlamaktadır.

📌 Giriş

Bu projede:

Veri seti: Intel Image Classification (Kaggle)

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

🚀 Ekler (Deployment ve Ekstra Çalışmalar)

Proje Kaggle/Colab GPU ortamında çalıştırılabilir, böylece eğitim süresi ciddi şekilde kısalmaktadır.

Ek olarak, model .h5 formatında kaydedilip Streamlit tabanlı bir arayüz ile deploy edilebilir.

Örneğin UI/ klasöründe bir app.py dosyası bulunabilir.

Kullanıcılar bir görsel yüklediğinde, model tahmini sınıfı ekranda gösterebilir.

Unsupervised yöntem opsiyonel olarak eklenebilir:

CNN’den elde edilen özellikler üzerinde k-means clustering veya PCA uygulanarak sınıflar arasındaki benzerlikler incelenebilir.

🔮 Sonuç ve Gelecek Çalışmalar

Bu çalışmada temel bir CNN modeli ile başarılı sonuçlar elde edilmiştir.
Ancak ilerleyen aşamalarda:

Daha derin modeller (ResNet, EfficientNet, VGG16 transfer learning) denenebilir.

Gerçek zamanlı veri toplama ve sınıflandırma senaryoları geliştirilebilir.

Streamlit veya benzeri araçlarla kullanıcı dostu bir arayüz eklenebilir.

Unsupervised yöntemler eklenerek daha kapsamlı bir proje haline getirilebilir.

Bu proje, bootcamp sonrası da geliştirilmeye açık olup, yeni özellikler eklenerek daha profesyonel hale getirilebilir.
