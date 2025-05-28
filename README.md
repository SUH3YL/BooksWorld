# BooksWorld
Projem kullanıcıların kitapları keşfetmesini, kategorilere göre incelemesini, detaylarını görmesini ve favorilerine eklemesini sağlayan  bir React Native mobil uygulamasıdır.
Temel Özellikler
Modern ve Minimal Tasarım:
Uygulamanın arayüzü, pastel bej-gri tonlarında sade ve göz yormayan bir tema ile tasarlanmıştır. Tüm ekranlarda yumuşak kartlar, açık arka plan ve koyu gri yazı renkleri kullanılmıştır.
Ana Sayfa (Home):
Popüler kitap kategorileri, kart şeklinde ve iki kitaplık örneklerle birlikte listelenir. Kategori kutuları ve kitap kartları modern, köşeleri yuvarlatılmış ve gölgeli bir tasarıma sahiptir.
Kategori Kitapları:
Bir kategoriye tıklandığında, o kategoriye ait kitaplar 2 sütunlu bir grid olarak gösterilir. Sonsuz kaydırma (infinite scroll) ile daha fazla kitap yüklenebilir.
Arama:
Kullanıcılar kitap ismine göre arama yapabilir. Sonuçlar kartlar halinde listelenir. Arama kutusu ve sonuçlar, uygulamanın genel renk paletine uygun şekilde tasarlanmıştır.
Kitap Detayları:
Bir kitaba tıklandığında, kitabın adı, yazar(lar)ı ve açıklaması detaylı olarak gösterilir. Kitap kapağı varsa büyük şekilde gösterilir.
Favoriler:
Kullanıcılar kitapları favorilerine ekleyebilir ve favori kitaplarını ayrı bir ekranda görebilir. Favoriler ekranında kitaplar kart şeklinde listelenir ve istenirse favorilerden çıkarılabilir.
Context API ile Yönetim:
Kitap verileri ve favoriler, Context API ile yönetilir. Böylece uygulama genelinde veri paylaşımı ve güncellenmesi kolaylaşır.
Pull-to-Refresh:
Ana sayfa ve favoriler ekranında, kullanıcılar ekranı aşağı çekerek verileri güncelleyebilir.
Kullanılan Teknolojiler
React Native (mobil uygulama geliştirme)
React Navigation (ekranlar arası geçiş)
Context API (global state yönetimi)
AsyncStorage (cihazda favori kitapları saklama)
OpenLibrary API (kitap verileri için)
Tasarım ve Kullanıcı Deneyimi
Tüm ekranlarda yumuşak, modern ve okunabilir bir arayüz.
Kartlar, kutular ve arka planlar pastel ve açık tonlarda.
Kategoriler, kitaplar ve favoriler kolayca erişilebilir.
Kullanıcı dostu ve akıcı bir deneyim.
