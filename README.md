#🧃 SimPy ile Meyve Suyu Otomatı Simülasyonu

Bu proje, SimPy kütüphanesi kullanılarak geliştirilmiş bir meyve suyu otomatı (vending machine) simülasyonunu içermektedir. Amaç, bir otomat sisteminin zaman içindeki davranışını modellemek, müşteri etkileşimlerini incelemek ve sistem performansını analiz etmektir.

#📌 Projenin Amacı

Bu simülasyon ile aşağıdaki sorulara yanıt aranır:

Müşteriler otomatı hangi sıklıkla kullanır?
Yoğunluk durumunda bekleme süreleri nasıl değişir?
Otomatın servis kapasitesi yeterli midir?
Rastgele olaylar sistem performansını nasıl etkiler?

#⚙️ Kullanılan Teknolojiler
Python
SimPy (Süreç tabanlı ayrık olay simülasyonu kütüphanesi)
Random modülü (rastgele müşteri gelişleri ve işlem süreleri için)

#🧠 Simülasyon Mantığı

Simülasyonda:

Müşteriler belirli aralıklarla (rastgele) sisteme gelir.
Her müşteri bir meyve suyu almak için otomatı kullanır.
Otomat sınırlı kaynak olarak modellenmiştir (aynı anda sınırlı sayıda kullanıcıya hizmet verebilir).
İşlem süreleri ve müşteri gelişleri rastgele dağılımlarla belirlenir.
Simülasyon belirli bir süre boyunca çalıştırılır ve süreç boyunca sistem davranışı gözlemlenir.

#🔄 Süreç Akışı
Müşteri sisteme gelir
Otomatın müsait olması beklenir
Sipariş verilir ve işlem başlar
Meyve suyu hazırlanır (belirli bir süre alır)
Müşteri sistemi terk eder

#📊 Elde Edilebilecek Çıktılar

Bu simülasyon ile:

Ortalama bekleme süreleri
Sistem yoğunluğu
Kaynak kullanım oranı
Kuyruk uzunlukları

gibi performans metrikleri analiz edilebilir.

#▶️ Nasıl Çalıştırılır?
Gerekli kütüphaneleri yükleyin:
pip install simpy
Python dosyasını çalıştırın:
python randomsimulation.py

#📁 Dosya Yapısı
randomsimulation.py → Simülasyonun ana kodlarını içerir
