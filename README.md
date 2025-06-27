# Traffic-Accidence

📁 Veri Seti
Kaynak: UK Department for Transport (AADF - Annual Average Daily Flow)

Veri Kümesi: 1.6 milyonun üzerinde trafik gözleminden örneklenmiş 275.000+ satır

Zaman Aralığı: 2000–2016

İçerik: Yıl, bölge, yol tipi, yol uzunluğu, araç türlerine göre trafik miktarı, koordinatlar vb.

🎯 Amaçlar
Trafik akışının yıllar içindeki değişimini analiz etmek

Araç türlerine göre dağılım ve artış oranlarını incelemek

Kentsel ve kırsal bölgelerdeki trafik farklarını ortaya koymak

En yoğun ilçeleri ve yolları belirlemek

Yol tiplerine göre trafik davranışlarını karşılaştırmak

🧪 Yapılan Analizler
📉 Yıllara Göre Toplam Trafik

🚗 Araç Türlerinin Yıllık Değişimi

🌍 Bölgesel Trafik Dağılımı

🏙️ En Yoğun Trafiğe Sahip İlçeler

🛣️ Yol Kategorisine Göre Araç Dağılımı

📏 Trafik Yoğunluğu (araç/km)

🏞️ Kırsal vs Kentsel Karşılaştırması

🛠️ Kullanılan Teknolojiler
Python 3.x

Pandas – Veri işlemleri

Matplotlib & Seaborn – Grafik ve görselleştirme

Jupyter Notebook – Analiz ortamı

📊 Örnek Grafikler
Yıllara göre toplam araç sayısı trendi

Yol türlerine göre araç yüzdesi

Pie chart ile kırsal/kentsel dağılım

En yoğun 10 yolun araç yoğunluğu (araç/km)

📌 Kurulum ve Kullanım
git clone https://github.com/kullanici-adi/uk-traffic-analysis.git
cd uk-traffic-analysis
pip install -r requirements.txt
jupyter notebook
Notebook'u çalıştırdıktan sonra ukTrafficAADF.csv dosyasının aynı klasörde olması gerekmektedir.

📝 Notlar
Bu proje, kaza verisi içermemektedir ancak trafik yoğunluğu üzerinden dolaylı çıkarımlar yapılabilir.

Veri setinde eksik veriler çok azdır, analiz öncesi kontroller yapılmıştır.

Kırsal ve kentsel sınıflandırma yol kategorisine göre tahmini olarak yapılmıştır.

