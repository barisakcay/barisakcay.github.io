# Barış Şu An Çalışıyor mu? 🛠️

Bu proje, bir Elektrik Mühendisi olarak vardiyalı çalışma düzenimi (12/36 ve gündüz vardiyaları) anlık olarak takip eden ve ziyaretçilere çalışma durumumu gösteren dinamik bir web sayfasıdır.

### 🔗 Canlı Site
[Siteye Gitmek İçin Tıkla](barisakcay.github.io)

---

## 🚀 Özellikler
- **Anlık Durum:** Çalışma saatlerindeyken "EVET" (Yeşil), mesai dışındayken "HAYIR" (Kırmızı) gösterir.
- **Canlı Geri Sayım:** Mesainin bitmesine veya yeni mesainin başlamasına kalan süreyi saniyelik olarak gösterir.
- **Türkiye Saat Dilimi:** Dünyanın neresinden girilirse girilsin, hesaplamaları Türkiye saatine (UTC+3) göre yapar.
- **Dinamik Veri:** Verileri her ay başında güncellenen bir `schedule.csv` dosyasından çeker.
- **Önbellek Yönetimi:** Dosya güncellendiğinde tarayıcı önbelleğine takılmadan en güncel veriyi anında yükler.

## 📁 Kullanım ve Güncelleme
Mesai takvimi `schedule.csv` dosyası üzerinden yönetilir. Excel üzerinden güncellenirken şu format korunmalıdır:

| start_date | start_time | end_date | end_time |
| :--- | :--- | :--- | :--- |
| GG.AA.YYYY | SS:DD | GG.AA.YYYY | SS:DD |

*Not: Excel'den dışa aktarırken ayırıcı olarak noktalı virgül (`;`) kullanılmalıdır.*

## 💻 Teknik Detaylar
- **Dil:** HTML5, CSS3, JavaScript (Vanilla JS)
- **Sunucu:** GitHub Pages
- **Veri Formatı:** CSV (Comma Separated Values)
