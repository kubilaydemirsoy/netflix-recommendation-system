
# 🎬 Netflix İçerik Tavsiye Motoru (Content-Based Recommendation System)

Bu proje, Netflix veri seti kullanılarak geliştirilmiş **İçerik Tabanlı bir Makine Öğrenmesi** modelidir. 
Kullanıcının sevdiği bir filme en çok benzeyen diğer 5 filmi/diziyi matematiksel olarak hesaplayıp önerir.

## 🚀 Proje Adımları
1. **Keşifsel Veri Analizi (EDA):** Veri seti incelendi ve yapı anlaşıldı.
2. **Veri Temizliği:** Eksik (Missing) veriler modelin çökmemesi için uygun stratejilerle dolduruldu ve temizlendi.
3. **Özellik Mühendisliği (Feature Engineering):** Yönetmen, oyuncu, tür ve açıklama metinleri tek bir 'Kelime Çorbası' (Combined Features) haline getirildi.
4. **Metin Ön İşleme (NLP):** Noktalama işaretleri ve büyük/küçük harf karmaşası temizlendi.
5. **Vektörizasyon (TF-IDF):** Temizlenen metinler yapay zekanın anlayacağı sayısal matrislere dönüştürüldü.
6. **Kosinüs Benzerliği (Cosine Similarity):** Filmlerin uzaydaki matematiksel açıları ölçülerek benzerlik skorları hesaplandı.
7. **Hata Yakalama (Try-Except):** Sistemin hatalı aramalarda çökmesini engelleyen güvenlik blokları yazıldı.
8. **Veri Görselleştirme:** Matplotlib ve Seaborn ile verideki trendler grafiklere döküldü.

## 🛠️ Kullanılan Teknolojiler
* **Python** (Pandas, Numpy, Regular Expressions)
* **Scikit-Learn** (TfidfVectorizer, Cosine Similarity)
* **Veri Görselleştirme** (Matplotlib, Seaborn)

## 💡 Nasıl Çalışır?
Arama fonksiyonuna bir film adı girersiniz (örn: `The Matrix`) ve sistem size en yüksek kosinüs benzerliği skoruna sahip 5 filmi listeler. Ayrıca büyük/küçük harf hatalarını otomatik tolere eder.

---
*Geliştirici: [Senin Adın/Soyadın]* | *Bu proje sıfırdan adım adım veri bilimi mantığıyla inşa edilmiştir.*
