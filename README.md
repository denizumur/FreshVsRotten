# 🍎 Gıda Tazelik ve Tür Sınıflandırması – CNN Modeli (14 Sınıf)

Bu proje, çeşitli meyve ve sebzeleri **türüne göre (örnek: muz, domates,elma,portakal)** ve **tazelik durumuna göre (taze / çürük)** sınıflandırmak üzere bir derin öğrenme modelidir.

Veri seti, Hugging Face'den alınan [Fresh-rotten-fruit](https://huggingface.co/datasets/Densu341/Fresh-rotten-fruit) görsel veri kümesidir. Bu veri kümesi üzerinde 14 sınıflı bir CNN modeli Keras ile eğitilmiştir.

---

## 🧠 Tahmin Edilen Sınıflar

| Taze Ürünler      | Çürük Ürünler     |
|-------------------|-------------------|
| freshapples       | rottenapples      |
| freshbanana       | rottenbanana      |
| freshcucumber     | rottencucumber    |
| freshokra         | rottenokra        |
| freshoranges      | rottenoranges     |
| freshpotato       | rottenpotato      |
| freshtomato       | rottentomato      |

Toplam **14 sınıf** (7 taze + 7 çürük).

---

## 🛠️ Kullanılan Teknolojiler

- Python 3.9+
- TensorFlow / Keras
- PIL & OpenCV
- Google Colab
- Matplotlib (grafikler için)

---

