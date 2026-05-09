# Barış Akçay | Working Status 🛠️

---

## 🇹🇷 Türkçe

Bu proje, bir Elektrik Mühendisi olarak vardiyalı çalışma düzenimi anlık takip eden ve ziyaretçilere çalışma durumumu gösteren dinamik bir web sayfasıdır.

### 🔗 Canlı Site
[https://barisakcay.github.io/](https://barisakcay.github.io/)

### 🚀 Özellikler
- **Anlık Durum:** Mesai saatlerinde **EVET** (Yeşil), mesai dışında **HAYIR** (Kırmızı) gösterir.
- **Canlı Geri Sayım:** Mesai bitimine veya başlangıcına kalan süreyi saniyelik gösterir.
- **Sabit Saat Dilimi:** Hesaplamalar cihazdan bağımsız olarak Türkiye saatine (UTC+3) göredir.
- **Dinamik Veri:** Verileri `schedule.csv` dosyasından her zaman en güncel haliyle çeker.

### 📁 Veri Formatı
Takvim `schedule.csv` üzerinden güncellenir. Excel'den aktarırken **noktalı virgül (;)** kullanılmalıdır:
`start_date;start_time;end_date;end_time`

---

## 🇺🇸 English

A dynamic web page that tracks my shift schedule as an Electrical Engineer in real-time and displays my current working status.

### 🔗 Live Site
[https://barisakcay.github.io/](https://barisakcay.github.io/)

### 🚀 Features
- **Real-Time Status:** Displays **YES** (Green) during shifts and **NO** (Red) during off-hours.
- **Live Countdown:** A second-by-second countdown to the end or start of the shift.
- **Fixed Time Zone:** Calculations are pinned to Turkey Time (UTC+3) regardless of device location.
- **Dynamic Fetching:** Always pulls the most recent version of the `schedule.csv` file.

### 📁 Data Structure
The schedule is managed via `schedule.csv`. Use **semicolon (;)** as a delimiter when exporting:
`start_date;start_time;end_date;end_time`

---

## 💻 Tech Stack
- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Deployment:** GitHub Pages
- **Data:** CSV Parsing
