# Data Science Mini‑Portfolio

Bu depo; veri bilimi ders çalışmalarımı **ödev havası olmadan** anlaşılır ve yeniden üretilebilir biçimde sunmak için hazırlandı. Kod hücrelerine **dokunulmadı**; yalnızca notebook’lardaki (Markdown) “homework/assignment/puan” ifadeleri projeye uygun dile çevrildi.

## İçerik

| Klasör / Dosya | Açıklama | Çalıştırma / Notlar |
|---|---|---|
| **01-temporal-energy-analysis/** | Küresel enerji tüketimi üzerine keşifsel veri analizi (EDA) notebook’u. | Aynı klasördeki `World Energy Consumption.csv.zip` dosyasını çıkarıp **`World Energy Consumption.csv`** dosyasını notebook’un yanına koyun. |
| **02-homework-1/** | İlk ödev setinden bağımsız bir analiz notebook’u (ödev terimleri temizlendi). | `jupyter notebook` ile açın. |
| **03-term-project-team/** | **Takım projesi**: notebook + sunum. | Ekip arkadaşım: **Hasan Kan**. Sunum: `term-project-presentation.pptx` – Video bağlantısı: `term-project-youtube-link.txt`. |
| **04-streamlit-whisper-ner-legacy/** | Eski bir Streamlit uygulamasına ait arşiv (Whisper ASR + NER). | Referans amaçlıdır. |
| **requirements.txt** | Gerekli temel Python paketleri. | Aşağıdaki “Kurulum” bölümüne bakın. |

## Kurulum
```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install --upgrade pip
pip install -r requirements.txt
```

## Notebook’ları Çalıştırma
```bash
jupyter notebook  # veya jupyter lab
```
- **Veri erişimi:** `01-temporal-energy-analysis/` içindeki **CSV** sıkıştırılmıştır. `World Energy Consumption.csv.zip` dosyasını açın ve `World Energy Consumption.csv` dosyasını aynı klasöre bırakın. Dosya adı değişirse notebook’taki okuma yolunu güncelleyin.

## Notlar
- Kod hücreleri **değiştirilmedi**; yalnızca açıklama metinleri projeye uygun olarak düzenlendi (örn. *“Q1 (20 pts)” → “Analysis 1”*).
- Büyük veri dosyaları repoya eklenmez; gerekirse küçük örnek/bağlantı kullanılır.
- Takım projesi klasöründe ortak çalışma bilgisi özellikle belirtilmiştir.

## Lisans
Kodlar: **MIT**. Veri setlerinin lisansı kaynağına göre değişebilir.
