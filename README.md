# Kredi Kartı Dolandırıcılık Tespiti

Bu proje, kredi kartı dolandırıcılık işlemlerini tespit etmek için çeşitli makine öğrenimi modellerinin uygulanmasını ve değerlendirilmesini içerir. Proje, kredi kartı işlemlerine dair bir veri seti üzerinde çalışmakta ve bu işlemlerden dolandırıcılık niteliği taşıyanları tespit etmeyi amaçlamaktadır.

# İçindekiler

- Proje Hakkında
- Kullanılan Modeller
- Veri Seti
- Kurulum
- Kullanım
- Sonuçlar

# Proje Hakkında
Kredi kartı dolandırıcılığı, finans sektöründe yıllık olarak önemli mali kayıplara yol açan ciddi bir sorundur. Bu çalışmada, dolandırıcılık işlemlerini tespit etmek amacıyla çeşitli makine öğrenimi tekniklerinin uygulanması ve değerlendirilmesi üzerine odaklanılmıştır. Çalışmada, hem geleneksel hem de modern makine öğrenimi modellerinin performansı kıyaslanmıştır.

# Kullanılan Modeller
Bu çalışmada aşağıdaki makine öğrenimi modelleri kullanılmıştır:

- Lojistik Regresyon (Logistic Regression): Basit ve yorumlanabilir bir modeldir. Kredi kartı dolandırıcılık tespitinde temel bir referans model olarak kullanılır.
- Karar Ağaçları (Decision Trees): Özellikler arasındaki doğrusal olmayan ilişkileri ve etkileşimleri ele alabilir.

- Rastgele Ormanlar (Random Forest): Birden çok karar ağacının birleştirilmesiyle oluşturulan bir topluluk yöntemidir.

- Gradyan Artırma Makineleri (Gradient Boosting Machines): Zayıf öğrenicilerin sıralı olarak birleşimiyle performansı artıran bir yöntemdir.

- Destek Vektör Makineleri (Support Vector Machines): Sınıflandırma problemleri için karar sınırları belirleyen güçlü bir modeldir.

Her modelin performansı çeşitli metriklerle değerlendirilmiştir, özellikle doğruluk, kesinlik, duyarlılık, F1 skoru ve ROC-AUC gibi metrikler dikkate alınmıştır.

# Veri Seti
Kullanılan veri seti, kredi kartı işlemlerini içermektedir ve aşağıdaki özellikleri barındırır:

- İşlem Miktarı (Transaction Amount): İşlemin parasal değeri.
- İşlemler Arasındaki Zaman (Time Between Transactions): İki işlem arasındaki süre.
- Satıcı Konumu (Merchant Location): İşlemin gerçekleştirildiği satıcının konumu.

Veri seti, yasal ve dolandırıcılık işlemlerini içerir ve dolandırıcılığı tespit edebilmek için çeşitli özellik mühendisliği teknikleri uygulanmıştır.

Kurulum
Projenizi çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

1. Bu depoyu klonlayın:

git clone https://github.com/cevahirozgur/credit-card-fraud-detection.git

2. Gerekli Python kütüphanelerini yükleyin:

pip install -r requirements.txt

3. Jupyter Notebook'u başlatın:

jupyter notebook

# Kullanım
Jupyter Notebook dosyasını (credit-card-fraud-detection.ipynb) açarak, çalışmayı adım adım takip edebilir ve modellerin nasıl uygulandığını görebilirsiniz. Her bir modelin nasıl eğitildiği, test edildiği ve değerlendirildiği detaylı olarak açıklanmıştır.

# Sonuçlar
Çalışmanın sonucunda, kullanılan makine öğrenimi modellerinin performansı çeşitli metriklerle karşılaştırılmıştır. Modellerin her birinin kredi kartı dolandırıcılığını tespit etme başarısı ve avantajları ayrıntılı olarak ele alınmıştır. Ayrıca, topluluk yöntemlerinin (ensemble methods) dolandırıcılık tespit oranlarını nasıl artırdığı ve yanlış alarmları nasıl azalttığı incelenmiştir.
