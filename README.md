
## Takım İsmi
##  Coreteam

![ChatGPT Image 5 Tem 2025 15_52_34 (2)](https://github.com/user-attachments/assets/bec82d13-bfeb-4be1-a991-ad1fa78858bf)



| İsim                   | Rol           | Durum | Sosyal Medya                                                                                                                                                                                                                                                                                                    |
| ---------------------- | ------------- | ----- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Meltem Kartopu**     | Scrum Master  | Aktif | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/meltemkartopu/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/MeltemKartopu)         |
| **Ahmet Reşat Keyan**  | Product Owner | Aktif | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/ahmet-keyan-088995246/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/Drandalll)     |
| **Berke Sinan Yetkin** | Developer     | Aktif | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/berke-sinan-yetkin/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/BerkeSinanYetkin) |
| **Esra Öden**          | Developer     | Aktif | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/esra-%C3%B6den-92b552270/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/esrashub)   |
| **Mehmet Emin Şahin**  | Developer     | Aktif | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/mehmetemin-sahin/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/EMIN200097)         |

---
## Ürün İsmi
# PoseCore 

![posecore\_2](https://github.com/user-attachments/assets/daeb3e73-7297-464a-924d-2a8dc356ab1b)

## Ürün Açıklaması

PoseCore, kullanıcıların postür bozukluklarını gerçek zamanlı analiz eden ve düzeltici geri bildirim sağlayan yapay zeka tabanlı bir uygulamadır. Mediapipe tabanlı iskelet modellemesi kullanarak, ofis çalışanları, fizyoterapi hastaları ve uzun süre oturarak çalışan bireylere yönelik kişiselleştirilmiş duruş takibi sağlar.

##  Özellikler

* 📸 Gerçek zamanlı kamera ile postür analizi
* 📊 Postür açılarının matematiksel hesaplanması
* 🔔 Yanlış duruşta anında uyarı sistemi
* 📈 Kullanıcıya özel ilerleme raporları
* 📱 Çoklu cihaz ve kamera uyumluluğu

##  Hedef Kitle

* Ofis çalışanları
* Postür sorunu yaşayan hastalar (örn. skolyoz)
* Fizyoterapistler ve spor eğitmenleri
* Uzun süre oturarak çalışan bireyler

---

##  Sprint 1 (23 Haziran - 6 Temmuz 2025)

<details>
<summary>Tıklayarak Detayları Göster/Gizle</summary>

###  Sprint Notları

* **Proje fikri ve modüller:** Fizyoterapi / postür / spor modülleri netleştirildi
* **Teknoloji Stack:** Mediapipe, OpenCV, Python/Flask
* **Prototip Geliştirme:** Temel iskelet çıkarımı ve açı hesaplama prototipi oluşturuldu
* **Veri Seti İncelemesi:** Kaggle fizyoterapi hareketleri analiz edildi

###  Hedeflenen Puan

* **Sprint Puanı:** 100 / 300
* **Mantık:** Toplam proje 300 puan; her sprint için \~100 puan
* **Story Points:** Her sprintte 100 puana ulaşmak için atanan 7 ana kanban kartına ait altgörevlere, ana görevde ulaşılmak üzere (roll up story points) ayrı ayrı puanmalar yapılmıştır.
* 2 haftalık sprint sürecinde 5 takım üyesi için 14 günlük görev dağılımı "Sprint Görev Dağılımı ve Puan Mantığı Tablosu" nda yer almaktadır.

###  Sprint Görev Dağılımı ve Puan Mantığı Tablosu
| Ana Görev                     | Alt Görev                                                                 | Puan | Sorumlu Rol          | Açıklama                                                                |
|-------------------------------|---------------------------------------------------------------------------|------|----------------------|-------------------------------------------------------------------------|
| **Araştırma & Planlama**      | Proje fikirleri araştırması                                               | 10   | Tüm ekip             | Hızlı workshop + bireysel araştırma                                     |
|                               | Kullanıcı persona oluşturma                                               | 5    | Product Owner        | PO liderliğinde hazırlanması                                            |
|                               | Kullanıcı görüşmeleri                                                     | 10   | PO + 1 Developer     | Katılımcı bulma + 5 görüşme                                             |
|                               | Teknoloji seçimi (Mediapipe/YOLO)                                         | 15   | 2 Developer          | Prototip test + teknik rapor                                            |
|                               | Başarı metriklerinin tanımlanması                                         | 10   | PO + Scrum Master    | KPI'ların SMART prensibiyle belirlenmesi                                |
| **Veri Toplama & Ön İşleme** | Doğru hareket videolarının kaydı                                           | 10   | 2 Developer          | Senaryo başına 2 tekrar                                                 |
|                               | Çoklu kamera veri seti                                                    | 10   | 3 Developer          | 3 açı x 5 hareket (eşgüdüm gerektirir)                                  |
|                               | Yanlış hareket senaryoları                                                | 10   | 1 Developer + PO     | Hata senaryolarının klinik doğruluğu                                    |
|                               | Koordinat normalizasyonu                                                  | 10   | 1 Developer          | OpenPose/Mediapipe çıktılarının dönüşümü                                |
|                               | Ham Video Verisinden CSV Üreten Script/Aracın Geliştirilmesi              | 10   | 1 Developer          | video verilerinden veriseti elde edilmesi                               |                                                        
| **Toplam**                    |                                                                           | 100  |                      |                                                                         |

---

###  Daily Scrum

* **Saat:** Her akşam 20:00 - 21:00 (WhatsApp)
* **Kanallar:** WhatsApp, Google Meet
* [WhatsApp Daily Scrum Ekran Görüntüleri](https://imgur.com/a/coreteam-daily-scrum-chats-QgBy6N9)

###  Sprint Board

**ClickUp Proje Panosu:** [Buradan Ulaşabilirsiniz](https://clickup.com/)

![image](https://github.com/user-attachments/assets/f31ad366-bf1f-497d-8100-39f8fdd5e194)


**ClickUp Proje Raporu ve Tamamlanan Sprint Puanı 
![image](https://github.com/user-attachments/assets/c9620829-f56c-41d7-a9a7-5cbb06ce2ad2)
* 100 puandan 50 puan tamamlanmıştır
* Devam eden görevler sonraki sprinte devredelecektir.
* Artı 10 puan model aşaması model geliştirme 1 e ait Mediapipe ile iskelet çıkarımı testi görevinden gelmiştir. Araştırma ve Planlama'ya katkısından dolayı bu sprintte denenmek istenmiştir. 
  

###  Prototip Testleri

* **MediaPipe Nokta Algılama ve Açı Hesaplama:** [Test Ekran Görüntüsü İçin Tıklayın](https://imgur.com/a/mediapipe-nokta-alg-lama-ve-hesaplama-3VOvH1m)

  Tabii, görseldeki metni **Markdown formatında** sadeleştirerek ve düzenleyerek aşağıya dönüştürüyorum:

---

## Veri Seti Toplama

Bu dizin (dataset_gathering) , projede kullanılacak veri setlerini toplamak, işlemek ve düzenlemek için kullanılan araçları içerir. Ham video verisini Makine Öğrenmesi modellerine beslemek ve doğru postür analizi yapmak için kullanılacak bu veriyi toplamayı burada gerçekleştiriyoruz.

### İçerik

### `main.py` ile Video'dan CSV'ye Dönüştürme

`main.py`, `input/` klasöründeki bir video dosyasını alır ve işlenmiş verileri `output/` klasöründe bir CSV dosyasına kaydeder. Temel adımlar:

1. `input/` klasörüne dönüştürmek istediğiniz video dosyasını ekleyin.
2. `main.py`:173'de video\_name argümanına string olarak doğru oturuş postürü videosu dosyanızın ismini **dosya tipi uzantısıyla beraber** verin.

   * Ya da kamera kullanmak için bu keyword argümanını silin.
3. Programı çalıştırıp mevcut kareleri kaydetmeye başlamak için klavyenizdeki **"L"** tuşuna basın.
4. Program, videodaki kareleri işler ve ilgili verileri `output/` dizinindeki CSV dosyasına yazar. Yazmayı durdurmak için tekrar **"L"** tuşuna basabilirsiniz.
5. Programdan çıkış yapmak için klavyenizdeki **"Q"** tuşuna basın.

Detaylı parametreler ve ek seçenekler için `main.py` dosyasındaki açıklamaları inceleyin.

---

## Notlar

* Bir dizin yukarıdaki `requirements.txt` dosyasındaki gereksinimleri pip ile kurduğunuzdan emin olun.
* Tam olarak akışa hakim olmak için `main.py` dosyasındaki komut satırlarını okuyun.
* CSV dosyası kullanılmadan önce gözden geçirilmelidir.

---

Başka düzenleme veya eklemek istediğin detay varsa iletebilirsin!


###  Sprint Review

* ✅ Proje fikri ve modüller onaylandı
* ✅ Mediapipe entegrasyonu tamamlandı
* ✅ Veri seti analizi tamamlandı
* 🚧 Kullanıcı test senaryoları Sprint 2'ye ertelendi

###  Sprint Retrospective

#### 👍 İyi Yönler

* Hızlı teknoloji seçimi ve prototipleme
* WhatsApp üzerinden etkili asenkron iletişim

#### 📌 Geliştirmeler

* Toplantı zamanlamalarının erken duyurulması
* Veri etiketleme standartlarının belirlenmesi

---

</details>


