# Bitki Hastalığı Tespiti

Bu proje, Kaggle'daki "New Plant Diseases Dataset" kullanılarak ve MobileNetV2 modeli temel alınarak, Kotlin dilinde gerçek zamanlı bitki hastalığı tespiti yapmayı amaçlamaktadır. Keras kütüphanesi ile entegre edilen bu sistem, tarım sektöründe erken teşhis ve tedavi için hızlı ve doğru sonuçlar sunar.

## Özellikler
- **Geniş Kapsamlı Dataset**: 20'den fazla bitki türü ve 30'dan fazla hastalık kategorisi içeren geniş bir veri seti.
- **MobileNetV2 ve Keras**: Hafif ve etkili bir model olan MobileNetV2, Keras ile kolay entegrasyon sağlar.
- **Kotlin Entegrasyonu**: Android uygulamaları için tercih edilen Kotlin, performans ve kullanılabilirlik açısından avantajlar sunar.
- **Gerçek Zamanlı Analiz**: Yüksek doğruluk oranı ile hızlı hastalık tespiti.

## Nasıl Çalışır?
Uygulama, kullanıcının yüklediği bitki görüntülerini analiz eder ve MobileNetV2 tabanlı yapay zeka modeli ile hastalık belirtilerini tespit eder. Sonuçlar, kullanıcıya hastalığın türü ve olası tedavi önerileri ile birlikte sunulur.

## Kullanım Senaryoları
- **Tarım Uzmanları**: Bitki sağlığını izlemek ve yönetmek için güçlü bir araç.
- **Çiftçiler**: Erken teşhis ile ürün kaybını önleme.
- **Araştırmacılar**: Bitki hastalıkları üzerine veri toplama ve analiz.

Bu proje, tarım teknolojilerinde yapay zekanın potansiyelini ortaya koymak ve sürdürülebilir bir gelecek için katkıda bulunmak amacıyla geliştirilmiştir.





## Çalıştırmak İçin Yapılması Gerekenler
1-Gerekli SDK’ları Yükleyin: Projede kullanılan Android SDK sürümünün yüklü olduğundan emin olun. SDK Manager aracılığıyla eksik olanları yükleyebilirsiniz.

2-Bağımlılıkları Yükleyin: build.gradle dosyasında belirtilen tüm bağımlılıkların yüklendiğinden emin olun. Eksik olanları yüklemek için “Sync Project with Gradle Files” seçeneğini kullanın.

3-Emülatör Oluşturun veya Gerçek Bir Cihazı Bağlayın: Uygulamayı test etmek için bir Android emülatörü oluşturabilir veya USB hata ayıklama modunda bir Android cihazı bağlayabilirsiniz.

4-Uygulamayı Çalıştırın: “Run” düğmesine tıklayarak uygulamanızı emülatörde veya bağlı cihazda başlatın.

5-Hata Ayıklama Yapın: Uygulama çalışırken herhangi bir hata ile karşılaşırsanız, Logcat’i kullanarak hataları izleyin ve giderin.