# Portföy Botu

Discord üzerinden kendi projelerimi ve portföyümü takip etmek için yazdığım bot. Projelerin hangi aşamada olduğunu, hangi dilleri/araçları kullandığımı ve proje linklerini SQLite veritabanında tutuyor.

## Neler Yapıyor?

* **Proje Kaydı:** Proje adı, açıklaması, GitHub linki ve ekran görüntüsünü (`screenshot`) kaydediyor.
* **Durum Takibi:** Projenin o anki durumunu (Prototip Oluşturma, Geliştirme Aşamasında, Tamamlandı vb.) tutuyor ve sonradan değiştirmeye izin veriyor.
* **Teknoloji Eşleştirme:** Hangi projede hangi teknolojilerin (Python, SQL, API, Discord vb.) kullanıldığını eşleştiriyor. İstenirse veritabanına yeni yetenekler de eklenebiliyor.
* **Veritabanı Yönetimi:** Tabloları sıfırdan kurma, varsayılan ayarları içeri aktarma ve sonradan tabloya yeni sütun ekleme (`add_column`) işlemleri doğrudan kod içinden yapılabiliyor.

## Kurulum

1. **Dosyaları indirin ve klasöre girin:**
   ```bash
   git clone <repo-linki>
   cd <klasor-adi>
