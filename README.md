# Yapay Sinir Ağları — Sıfırdan Başlangıç / Seed 31040

**Yalnızca yeni çalışma:** 18 Kasım 2026. Eski sonuç dosyalarını bu yeni klasöre taşımayın.

- GitHub: https://github.com/Sdesry/YapaySinirA (GitHub entegrasyonunda yazma yetkisi 18 Kasım 2026'da doğrulandı)
- Drive çalışma klasörü: `MyDrive/Yapay Sinir Ağları/YSA_31040_20261118/`
- Öğrenci no son 5: `29014`; temel seed: `31040`; split seed: `31093`.

## Aşama 1 nasıl çalıştırılır?
1. https://colab.research.google.com/ açın.
2. `01_eda.ipynb` notebook'unu yükleyin; **Çalışma Zamanı → Tümünü Çalıştır**.
3. Google Drive bağlama iznini verin; başka hesaba bağlanmadığınızdan emin olun.
4. Veri indirilemezse UCI'nin **bank-additional.csv** dosyasını Colab penceresinden yükleyin.
5. Son hücrede `AŞAMA 1 BAŞARILI` yazısını ve Drive klasöründeki `results/`, `configs/`, `figures/` çıktılarını kontrol edin.

## Bilimsel zorunluluklar
- Yalnızca UCI Bank Marketing `bank-additional.csv` kullanılır; `bank-additional-full.csv` kullanılmaz.
- `duration` modelden çıkarılır, `pdays=999` ve `unknown` özel kod olarak açıklanır.
- Test EDA ve model seçiminde kullanılmaz.
- Tam kopya satırlar ham hedef etiketleriyle karşılaştırılarak bölünmeden önce çıkarılır; çıkarılan indeksler saklanır.
- `dataset_split.csv` ve `configs/seeds.json` değişirse sonraki aşama geçersizdir.
- Kod yalnızca Aşama 1'dir; Aşama 2/3 ve test commit kilidi henüz tamamlanmadı.

## SHA ayrımı
- **SHA-256**: dosyanın gerçek baytlarının özeti.
- **Git blob SHA**: GitHub'ın dosya nesnesi kimliği, genelde SHA-1.
- **Commit SHA**: sürüm kaydının kimliği. Birbirleriyle eşit olması beklenmez.
- SHA manifesti burada Aşama 1 için oluşturulur; test kilidi Aşama 3'te ayrı bir Git commit olarak yapılacaktır.

Kaynak: https://archive.ics.uci.edu/dataset/222/bank+marketing