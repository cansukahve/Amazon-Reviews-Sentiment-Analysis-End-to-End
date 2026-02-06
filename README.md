# 📊 Amazon Elektronik Ürünleri Duygu Analizi ve Uçtan Uca Dashboard

Bu proje; 50.000'den fazla ham Amazon kullanıcı yorumunun temizlenmesinden, Makine Öğrenmesi (NLP) ile duygu analizine ve sonuçların profesyonel, etkileşimli bir Power BI Dashboard'una dönüştürülmesine kadar uzanan tam bir veri analitiği iş akışını kapsamaktadır.

---

## 🚀 Proje Özeti
Bu projenin temel amacı, yapılandırılmamış müşteri geri bildirimlerini anlamlı iş stratejilerine dönüştürmektir. Doğal Dil İşleme (NLP) teknikleri kullanarak Elektronik kategorisindeki müşteri memnuniyetini ölçümledik ve ürün bazlı sorunların kök nedenlerini tespit ettik.

### ✨ Temel Özellikler
* **Veri Ön İşleme:** Regex ve Pandas kullanılarak gürültülü verilerin (HTML etiketleri, noktalama işaretleri) temizlenmesi ve metinlerin analize hazır hale getirilmesi.
* **Duygu Analizi:** Yorumların "Pozitif", "Nötr" ve "Negatif" olarak etiketlenmesi ve TextBlob ile polarite skorlarının hesaplanması.
* **Makine Öğrenmesi:** TF-IDF Vektörleştirme ve Lojistik Regresyon modeli kullanılarak müşteri duygularını tahmin eden modelin eğitilmesi.
* **Etkileşimli Dashboard:** Karar vericiler için modern "Karanlık Mod" tasarımına sahip, yüksek görsellikli Power BI raporu.

---

## 🛠️ Kullanılan Teknolojiler
* **Python:** Pandas, NumPy, Scikit-Learn, TextBlob, Matplotlib, Seaborn.
* **NLP Teknikleri:** Tokenizasyon, Stopwords temizliği, N-gram analizi, Duygu skorlaması.
* **Görselleştirme:** Power BI Desktop (DAX, Etkileşimli Dilimleyiciler, Modern UI Tasarımı).

---

## 📈 Analiz Bulguları ve Çıktılar
* **Genel Memnuniyet:** Veri seti genelinde 5 üzerinden **4.1** ortalama puan korunmaktadır; yorumların yaklaşık **%76'sı pozitif** eğilimlidir.
* **Kritik Sorunlar:** Kelime frekans analizi, negatif yorumların çoğunlukla **"ses kalitesi" (sound quality)**, **"konfor" (comfort)** ve ürünlerin kısa sürede **"çalışmayı durdurması" (stopped working)** üzerinde yoğunlaştığını göstermektedir.
* **Riskli Ürünler:** En çok şikayet alan ilk 5 ürün belirlenmiş ve kalite kontrol süreçleri için listelenmiştir.

---

## 📂 Depo Yapısı
* `Amazon_Electronics_Sentiment_Analysis_NLP.ipynb`: Veri temizleme, NLP işlemleri ve ML modellerini içeren ana Python notebook dosyası.
* `Amazon_Reviews_Interactive_Dashboard.pbix`: Tüm etkileşimli raporu içeren Power BI dosyası.
* `amazon_reviews_dashboard.csv`: Analiz edilip temizlenmiş, görselleştirmeye hazır veri seti.

---

## 💡 Nasıl Kullanılır?
1. **Python Analizi:** Analiz adımlarını ve model eğitimini görmek için `.ipynb` dosyasını Jupyter Notebook veya Google Colab üzerinden açabilirsiniz.
2. **Power BI Dashboard:** Etkileşimli raporu incelemek için `.pbix` dosyasını indirip Power BI Desktop ile görüntüleyebilirsiniz.

---

## 👤 Hazırlayan
**Cansu Kahve**
* [LinkedIn](https://www.linkedin.com/in/cansukahve/) 
* [GitHub](https://github.com/cansukahve)

