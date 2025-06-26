# Power-Pulse-GoIT-Final-Project

## Power Pulse QA Test Süreci

Bu depo, **Power Pulse Web Uygulaması** için yürütülen kalite güvence (QA) çalışmalarına ait test planı, test raporları ve hata takibini içeren dökümantasyonu barındırmaktadır. Bu çalışmalar, GoIT Yazılım Test Uzmanlığı Kursu Final Projesi kapsamında gerçekleştirilmiştir.

---

## 📄 İçerik

Depoda bulunan başlıca belgeler:

- [PowerPulse QA_Test_Plani.pdf](./PowerPulse%20QA_Test_Plani.pdf)  
  → Test sürecine ait kapsam, strateji, roller, zaman çizelgesi ve risk değerlendirmesi.

- [PowerPulse_Test_Raporu.pdf](./PowerPulse_Test_Raporu.pdf)  
  → Gerçekleştirilen UI ve API testlerinin sonuçları, grafikler, hata sayıları ve genel değerlendirme.

- [BugBusters - PowerPulse Bug Raporları.xlsx](./BugBusters%20-%20PowerPulse%20Bug%20Raporları.xlsx)  
  → Hataların detaylı listesi, durumları ve öncelik düzeyleri.

- [BugBusters Trello Linki.docx](./BugBusters%20Trello%20Linki.docx)  
  → Proje sürecinin yönetildiği Trello panosu linki.

---

## 🌐 Swagger API Dokümantasyonu

Test edilen API uç noktaları için Swagger arayüzü:  
🔗 [Swagger UI – Power Pulse](https://power-pulse-qa.f.goit.study/api-docs/)  

---

## 🛠️ Kullanılan Test Yöntemleri

- Fonksiyonel Testler  
- UI & UX Testleri  
- API Testleri (Postman & Swagger)  
- Statik Kod Gözden Geçirme  
- Veri Doğruluğu Testleri

Testler aşağıdaki ortamlarda gerçekleştirilmiştir:

- Windows 11, macOS Sequoia  
- Android 13, iOS 18  
- Chrome, Safari, Opera, Edge

---

## 📊 Özet Test Sonuçları

| Test Türü      | Test Case | Passed | Failed | Bug |
|----------------|-----------|--------|--------|-----|
| UI             | 351       | 291    | 60     | 60  |
| API            | 53        | 45     | 8      | 8   |
| Statik         | 6         | 0      | 0      | 0   |
| **Toplam**     | **410**   | **336**| **68** | **68** |

Başarı oranı: **%83.2**

---

## 👥 Ekip

- **Scrum Master:** Damla Patterson  
- **QA Team Lead:** Handan Çileli  
- **QA Engineers:** Dilan Balaman, Begüm Dökmetaş, Gamze Merve Bal, Musa Eren Tanrıöver, Nuray Elmas

---

## 📅 Takvim

| Aşama               | Tarih                  |
|---------------------|------------------------|
| Test Planlama       | 11.06.2025 – 12.06.2025 |
| Test Case Yazımı    | 13.06.2025 – 19.06.2025 |
| Test Yürütme        | 20.06.2025 – 24.06.2025 |
| Raporlama           | 25.06.2025             |

---

## 📌 Notlar

- Test otomasyonu henüz uygulanmamıştır. Manuel testler yürütülmüştür.  
- Şifre yenileme ve oturum yönetimi gibi bazı alanlarda dokümantasyon eksiklikleri tespit edilmiştir.  
- Tespit edilen hatalar Trello panosu üzerinden takip edilmektedir.

---

## ✅ Yayına Hazır mı?

Genel olarak sistemin temel işlevleri beklentileri karşılamakta, kritik hataların çözülmesiyle birlikte uygulama yayına hazır hale gelebilir.
