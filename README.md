echo "# Flutter ToDo Uygulaması

Flutter kullanılarak geliştirilmiş basit ve kullanıcı dostu bir yapılacaklar listesi (ToDo) uygulaması. Bu uygulama, yapılacak görevlerin eklenmesi, güncellenmesi, silinmesi ve tamamlandığında işaretlenmesi gibi temel ToDo listesi işlevlerini gösterir.

## Özellikler

- **Yeni görev ekleme:** Görev açıklamasını girerek kolayca görev ekleyin.
- **Görev tamamlama:** Görevlere dokunarak tamamlandığını işaretleyin veya tamamlama işlemini geri alın.
- **Görev silme:** Listeden görevleri silin.
- **Arama fonksiyonu:** Entegre arama çubuğu ile görevlerinizde arama yapın.
- **Kalıcı görev listesi:** Görevler uygulama boyunca saklanır.

## Ekran Görüntüleri

_Uygulamanızın ekran görüntülerini buraya ekleyerek kullanıcılara görsel bir önizleme sunabilirsiniz._

## Kurulum

Bu uygulamayı klonlayıp çalıştırmak için bilgisayarınızda [Git](https://git-scm.com) ve [Flutter](https://flutter.dev) kurulu olmalıdır.

### Depoyu Klonlayın

\`\`\`bash
git clone https://github.com/YenerCenger/Flutter-ToDo-App.git
cd Flutter-ToDo-App
\`\`\`

### Bağımlılıkları Yükleyin

Gerekli bağımlılıkları yüklemek için aşağıdaki komutu çalıştırın:

\`\`\`bash
flutter pub get
\`\`\`

### Uygulamayı Çalıştırın

Bir cihazın veya emülatörün çalıştığından emin olun, ardından uygulamayı başlatmak için aşağıdaki komutu çalıştırın:

\`\`\`bash
flutter run
\`\`\`

## Klasör Yapısı

- **\`lib\`**
  - **\`constants\`**: Uygulama genelinde kullanılan renk ve tema tanımlamalarını içerir.
  - **\`model\`**: \`ToDo\` model sınıfını tanımlar.
  - **\`widgets\`**: Tekrar kullanılabilir UI bileşenlerini, örneğin ToDo öğesi bileşenlerini içerir.
  - **\`screens\`**: Görev listesi ve UI öğelerini içeren ana ekran.

## Teknoloji Yığını

- **Flutter**: Mobil, web ve masaüstü için tek bir kod tabanı ile derlenmiş uygulamalar geliştirmek için kullanılan framework.
- **Dart**: Flutter tarafından kullanılan programlama dili.

## Katkılar

Katkılara açıktır! Eğer bir hata bulursanız veya yeni bir özellik eklemek isterseniz, bir issue açabilir veya pull request oluşturabilirsiniz.

## Lisans

Bu proje MIT Lisansı altında lisanslanmıştır - daha fazla bilgi için [LICENSE](LICENSE) dosyasına bakabilirsiniz.
" > README.md
