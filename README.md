Ürün Arama ve Fiyat Karşılaştırma
Açıklama
Bu Python betiği, kullanıcıdan belirli kriterlere göre ürün araması yapmanıza olanak sağlar. Kullanıcı, arama kelimesi, maksimum ve minimum fiyat aralıkları, ve sıralama seçeneği belirleyebilir. Betik, bu bilgileri kullanarak Akakçe web sitesinde arama yapar ve sonuçları listeler.

Gereksinimler
requests kütüphanesi
BeautifulSoup kütüphanesi: Henüz kurulu değilse, pip ile kurabilirsiniz.
pip install requests beautifulsoup4

Kullanım
Betik Çalıştırma

Betiği Python ortamınızda çalıştırın.

Arama Terimleri

Arama kelimesi: Aramak istediğiniz kelimeyi girin.
Max fiyat: İstemiyorsanız 0 girin, aksi takdirde maksimum fiyatı girin.
Min fiyat: İstemiyorsanız 0 girin, aksi takdirde minimum fiyatı girin.
Sıralama elemanı: (İstemiyorsanız 0 girin)
Popülerlik
En Düşük Fiyat
En Yeni
En Yüksek Fiyat
En Yüksek Puan
Sonuçlar

Betik, belirtilen kriterlere göre Akakçe'den ürünleri arar ve sonuçları aşağıdaki şekilde listeler:

Ürün adı
Kargo dahil en ucuz fiyat
Örnek Çıktı

Aramak istediğiniz kelimeyi girin : 
Arama kelimesi : telefon
Max fiyat gir : ( İstemiyorsan 0 Gir .)
Max fiyat : 1000
Min fiyat gir : ( İstemiyorsan 0 Gir .)
Min fiyat : 100
Sıralama elemanı ( İstemiyorsan 0 ) gir 
1.)Popülerlik
2.)En Düşük Fiyat
3.)En Yeni
4.)En Yüksek Fiyat
5.)En Yüksek Puan
Sıralama elemanı : 2

Sonuçlar:
- Ürün adı: Örnek Telefon
  Kargo Dahil En Ucuz : 950 TL

Hata Yönetimi
Eğer arama sonucu bulunamazsa veya veri çekilirken bir sorun oluşursa, kod herhangi bir hata mesajı vermeyecek şekilde tasarlanmıştır.
