#🧠 Beyin Kanaması Tespiti için Görüntü İşleme ve Makine Öğrenimi Projesi
Beyin Kanaması Tespiti için Görüntü İşleme ve Makine Öğrenimi Projesi
Bu proje, medikal görüntüler üzerinde beyin kanaması (hemorajik lezyon) bölgelerinin tespiti amacıyla geliştirilmiş ileri düzey bir görüntü işleme ve makine öğrenmesi çalışmasıdır.

📌 Proje İçeriği:
Kenar yönelimi çıkarımı ve tanımlayıcı kodlama
Gaussian Mixture Model (GMM) ile doku modelleme
Morfolojik iyileştirme teknikleri
Çok seviyeli görüntü piramidi oluşturma
Transfer öğrenme destekli model geliştirme (model.pth)
Label karşılaştırmalı doğruluk analizi

🎯 Amaç:
Beyin kanaması gibi hayati risk taşıyan durumların, erken teşhis ve hızlı müdahale süreçlerinde kullanılabilecek otomatik bir destek sistemi geliştirmek.

🚀 Teknik Detaylar:
Python (Jupyter Notebook) tabanlı geliştirme
OpenCV, Scikit-Learn, PyTorch kullanımı
Gaussian Mixture Modelling, Morfoloji Operasyonları, Multi-Scale Analysis

🧩 Projeyi neden farklı kılıyor?
Sadece kenar tespitine odaklanmakla kalmıyor, aynı zamanda doku davranışını istatistiksel modellere entegre ediyor.
Geleneksel ön işleme adımlarını, çok katmanlı piramit analiziyle güçlendiriyor.
Tüm pipeline, klinik uyumluluk hedefiyle optimize edildi.

💡 Gelecek Gelişim Alanları:
Daha büyük veri setleriyle eğitim
U-Net, V-Net gibi derin öğrenme mimarileriyle tam segmentasyon
Gerçek zamanlı görüntüleme sistemlerine entegrasyon

💡Kullanım
Onislem.ipynb ile veri setine ön işlemler uygulayın.
DesenKodla.ipynb ile kenar çıkarımı ve desen kodlama işlemlerini gerçekleştirin.
Piramit.ipynb ile çok katmanlı piramit analizi yapın.
Eğitilmiş modeli (model.pth) kullanarak tahminlerinizi ve doğruluk analizlerinizi gerçekleştirin.

⚙️ Kurulum Adımları
# Gerekli kütüphaneleri yükleyin
pip install -r requirements.txt

