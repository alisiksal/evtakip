EVTAKİP — İLK PROTOTİP

Bu klasör, telefon tarayıcısında çalışabilen basit bir PWA prototipidir.
Özellikler:
- Aylık takvim
- Yerel olarak manuel kapalı/rezervasyon işaretleme
- JSON yedekleme ve geri yükleme
- Basit çevrimdışı önbellek (HTTPS veya localhost üzerinde)

ÖNEMLİ SINIRLAR:
Bu sürüm Airbnb, Agoda veya Vrbo hesaplarına bağlanmaz; rezervasyonları otomatik çekmez veya platformlarda tarih kapatmaz.
Gerçek senkronizasyon için HTTPS üzerinde barındırma, sunucu tarafında iCal içe aktarma/işleme ve platformların desteklediği dışa yazma/API/kanal yöneticisi bağlantıları gerekir.
iCal URL'leri gizli bağlantılar olabilir; onları herkese açık istemci koduna koymayın.

Android'de ana ekrana ekleme:
1. Dosyaları HTTPS destekleyen bir statik hosting alanına yükleyin.
2. Chrome'da siteyi açın.
3. Menü (⋮) > Ana ekrana ekle / Uygulamayı yükle seçeneğini kullanın.

Bu klasörü sadece dosyaya çift tıklayarak açarsanız PWA yükleme ve çevrimdışı özellikleri sınırlı olabilir.
