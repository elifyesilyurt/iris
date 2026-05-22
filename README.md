# 🌸 Iris Çiçeği — Keşifsel Veri Analizi (EDA)

Bu proje, makine öğrenmesinin klasik veri seti olan **Iris** üzerinde temel bir Keşifsel Veri Analizi (EDA) gerçekleştirir. Pandas, Seaborn ve Matplotlib kullanılarak veri incelenir, görselleştirilir ve türler arasındaki ilişkiler ortaya konur.

---

## 📊 İçerik

| Adım | Açıklama |
|------|----------|
| Veri Yükleme | `bezdekIris.data` dosyası pandas ile okunur, sütun isimleri atanır |
| Keşif | `shape`, `describe`, `info`, `isnull` ile veri tanıma |
| Görselleştirme | Pairplot, Boxplot, Korelasyon Heatmap |

---

## 🗂️ Veri Seti

UCI Machine Learning Repository'den alınan klasik Iris veri seti kullanılmaktadır.

**Özellikler:**

- `sepal_length` — Çanak yaprak uzunluğu (cm)
- `sepal_width` — Çanak yaprak genişliği (cm)
- `petal_length` — Taç yaprak uzunluğu (cm)
- `petal_width` — Taç yaprak genişliği (cm)
- `species` — Çiçek türü: *Iris-setosa*, *Iris-versicolor*, *Iris-virginica*

Veri setini indirmek için: [UCI Iris Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/iris/bezdekIris.data)

---

## 🚀 Kurulum ve Çalıştırma

### Gereksinimler

```
Python 3.8+
pandas
seaborn
matplotlib
jupyter
```

### Adımlar

```bash
# 1. Repoyu klonla
git clone https://github.com/KULLANICI_ADIN/iris-eda.git
cd iris-eda

# 2. Bağımlılıkları yükle
pip install -r requirements.txt

# 3. Veri setini indir (bezdekIris.data dosyasını proje klasörüne koy)

# 4. Notebook'u aç
jupyter notebook iris.ipynb
```

---

## 📈 Görseller

### Pairplot — Tüm Özellik İlişkileri
Türlere göre renklendirilmiş ikili ilişki grafikleri

### Boxplot — Taç Yaprak Uzunluğu Dağılımı
Türler arasındaki fark en net petal_length'te görülür

### Heatmap — Korelasyon Matrisi
`petal_length` ve `petal_width` arasında güçlü pozitif korelasyon (~0.96)

---

## 🛠️ Kullanılan Teknolojiler

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0-150458?logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-4C72B0)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

---

## 📁 Proje Yapısı

```
iris-eda/
├── iris.ipynb          # Ana notebook
├── bezdekIris.data     # Veri seti (manuel indirilmeli)
├── requirements.txt    # Python bağımlılıkları
└── README.md           # Bu dosya
```

---

## 📝 Lisans

MIT License
