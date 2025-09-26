# Yüz İfadeleri ile Duygu Tanıma Sistemi 
Bu proje, görüntü işleme ve derin öğrenme tekniklerini kullanarak insan yüz ifadelerinden temel duyguları (Kızgın, Mutlu, Üzgün, Korku, İğrenme, Şaşkın, Tarafsız) otomatik olarak tanımayı amaçlamaktadır. 

# Giriş
Bu proje, insan yüz ifadelerinden duyguları tanımak için FER2013 veri setini temel almaktadır. Toplamda yaklaşık 36.000 adet gri tonlamalı görüntü, derin öğrenme için uygun hale getirilmiş ve Evrişimli Sinir Ağları (CNN) mimarisi kullanılarak yedi temel duygu sınıfını (Mutlu, Üzgün, Kızgın vb.) ayırt etmesi sağlanmıştır.

Modelin başarısı, Karışıklık Matrisi ve Sınıflandırma Raporları ile detaylıca analiz edilmiştir. Ayrıca, tahminlerin hangi yüz bölgelerine odaklanılarak yapıldığını göstermek için Grad-CAM / Eigen-CAM gibi açıklanabilirlik yöntemleri de uygulanmıştır. Bu çalışma, sadece yüksek doğruluk elde etmeyi değil, aynı zamanda yapay zekânın karar mekanizmasını şeffaf hale getirmeyi de hedeflemektedir.

# Metrikler
Bu projenin temel çıktısı, başarılı bir şekilde eğitilmiş bir Evrişimli Sinir Ağı (CNN) modelidir. Elde edilen sonuçlar, modelin genelleme yeteneğini ve duygular arasındaki ayrım gücünü (discriminative power) anlamamızı sağlamıştır. 

# Sonuç ve Gelecek Çalışmalar
Bu modeli oluştururkenki temel hedefim insanların yüz mimİk ve ifadelerine göre duygu durumlarını ölçmekti. Bu elde edilen veriler bir ürün pazarlamada insanlara olan yaklaşımımızı belirlemekte, mağazadaki insanların ürünlere olan tepkilerine bağlı olarak başarı değerlendirmesi yapmada, uzaktan eğitim platformlarında öğrencinin dikkatinin dağılıp dağılmadığını ölçmekte ve ders sırasında neler hissettiğine, insanların ruh halini anlamada kullanılabilir. Bu veriler tek başına başarı oranı düşük olacağından insanların ses, beden dili, vücut sıcaklığı ve nabız sayısı gibi etkenlerle aynı zamanda ele alındığında daha güvenilir bir sonuç verecek, bu sonuçlar kullanılarak da adli süreçlerde veya tıbbi tanılarda işleri kolaylaştıracaktır.

Bir diğer Önemli alan da yapay zeka destekli robotların insan ilişkilerinde olan başarısını arttırmaktır. Robot bu verileri birleştirerek insanların ruh hallerini anlayacak ve sOhbet ve davranışlarını bu çerçeve etrafında şekillendirerek daha sağlıklı ve etkili bir iletişim kuracaktır. 


# Linkler
https://www.kaggle.com/code/zehr4a/duygu-modeli
https://www.kaggle.com/code/zehr4a/model-test

