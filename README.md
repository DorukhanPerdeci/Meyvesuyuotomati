🧃 SimPy ile Meyve Suyu Otomatı Simülasyonu

Bu proje, SimPy kütüphanesi kullanılarak geliştirilmiş bir meyve suyu otomatı (vending machine) simülasyonunu içermektedir.
Amaç, bir otomat sisteminin zaman içindeki davranışını modellemek, müşteri etkileşimlerini incelemek ve sistem performansını analiz etmektir.

📌 PROJENİN AMACI

Bu simülasyon ile aşağıdaki sorulara yanıt aranır:

Müşteriler otomatı hangi sıklıkla kullanır?
Yoğunluk durumunda bekleme süreleri nasıl değişir?
Otomatın servis kapasitesi yeterli midir?
Rastgele olaylar sistem performansını nasıl etkiler?
⚙️ KULLANILAN TEKNOLOJİLER
Python
SimPy (Süreç tabanlı ayrık olay simülasyonu)
Random modülü (rastgele müşteri gelişleri ve işlem süreleri için)
🧠 SİMÜLASYON MANTIĞI

Simülasyonda:

Müşteriler belirli aralıklarla (rastgele) sisteme gelir
Her müşteri bir meyve suyu almak için otomatı kullanır
Otomat sınırlı kaynak olarak modellenmiştir
Aynı anda sınırlı sayıda kullanıcıya hizmet verilebilir
İşlem süreleri ve müşteri gelişleri rastgele dağılımlarla belirlenir
Simülasyon belirli bir süre boyunca çalıştırılır
🔄 SÜREÇ AKIŞI
Müşteri sisteme gelir
Otomatın müsait olması beklenir
Sipariş verilir ve işlem başlar
Meyve suyu hazırlanır
Müşteri sistemi terk eder
📊 ELDE EDİLEBİLECEK ÇIKTILAR

Bu simülasyon ile:

Ortalama bekleme süreleri
Sistem yoğunluğu
Kaynak kullanım oranı
Kuyruk uzunlukları

gibi performans metrikleri analiz edilebilir.

▶️ NASIL ÇALIŞTIRILIR?
1️⃣ Gerekli kütüphaneleri yükleyin:
pip install simpy
2️⃣ Python dosyasını çalıştırın:
python randomsimulation.py
