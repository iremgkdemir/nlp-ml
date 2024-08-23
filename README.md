

# Doğal Dil İşleme (NLP) ve Makine Öğrenimi Projeleri

Bu depo, Doğal Dil İşleme (NLP) ve makine öğrenimi alanlarında çeşitli konulara odaklanan Jupyter Notebook'larının bir koleksiyonunu içermektedir. Her bir notebook, belirli bir konuya ayrılmış olup, detaylı açıklamalar ve kod örnekleri sunmaktadır.

## İçerik Özeti

- **Ön İşleme (Pre-processing).ipynb**: Bu notebook, metin verilerinin ön işleme adımlarını ele alır. Tokenizasyon, durak kelimelerin çıkarılması, kök bulma (stemming), kök çözümleme (lemmatization) gibi temel teknikleri ve ham metin verilerini daha ileri analiz veya modelleme için hazırlayan diğer adımları içerir.

- **Özellik Mühendisliği (Feature Engineering).ipynb**: Bu notebook, n-gramlar, TF-IDF ve embedding tabanlı özellikler gibi metin verilerinden özellik çıkarma tekniklerini tartışarak, makine öğreniminde verilerin altında yatan yapıyı en iyi temsil eden özellikleri yaratmayı amaçlar.

- **Metin Sınıflandırma.ipynb**: NLP'de temel bir görev olan metin sınıflandırmaya giriş sağlar. Naive Bayes, SVM gibi geleneksel makine öğrenimi modelleri ve sinir ağı tabanlı modeller gibi farklı metin sınıflandırma yaklaşımlarını ele alır. Ayrıca, model performansının nasıl değerlendirileceğine dair örnekler de sunar.

- **Skip-gram Modeli ile Word Embedding.ipynb**: Bu notebook, büyük veri setlerinden yüksek kaliteli kelime vektörleri öğrenmek için bir yöntem olan Skip-gram modeline odaklanır. Kelime embeddinglerini eğitmek için kod örnekleri içerir ve bu embeddinglerin nasıl kullanılacağını gösterir.

- **spaCy_introduction.ipynb**: spaCy, NLP görevleri için güçlü ve verimli bir kütüphanedir. Bu notebook, tokenizasyon, sözcük türü etiketi, adlandırılmış varlık tanıma ve bağımlılık çözümlemesi gibi spaCy'nin ana özelliklerini ele alarak bir giriş sunar. spaCy'yi projelerine dahil etmek isteyenler için mükemmel bir başlangıç noktasıdır.

## Gerekli Dosyalar ve Kurulum

Bu proje, bazı büyük boyutlu dosyalar ve ek veri setleri gerektirmektedir. Bu dosyalar ve veri setleri, depo boyutunu aşırı büyütmemek adına projeye dahil edilmemiştir. Aşağıda, projenin tam çalışabilmesi için indirmeniz ve proje dizininde ilgili yerlere eklemeniz gereken dosyalar listelenmiştir:

### Gerekli Dosyalar:
- **GoogleNews-vectors-negative300.bin**: Word2Vec modeliyle önceden eğitilmiş kelime vektörlerini içeren bu dosyayı [buradan](https://example.com) indirebilirsiniz.
- **Cell_Phones_and_Accessories_5.json**: Bu veri seti, inceleme verileri içerir ve çeşitli NLP görevlerinde kullanılmaktadır. Dosyayı [buradan](https://example.com) indirebilirsiniz.
- **Chunkers, Corpora, Taggers, Tokenizers Klasörleri**: Bu klasörler, NLTK kütüphanesinin farklı modülleri için gereken veri ve model dosyalarını içerir. Bu klasörler, NLTK'nin `nltk.download()` fonksiyonu kullanılarak kod içinde otomatik olarak indirilebilir. Eğer bu dosyalar eksikse, ilgili notebook'ta bu komutları çalıştırarak indirme işlemini gerçekleştirebilirsiniz.

## Kurulum

1. Bu projeyi bilgisayarınıza klonlayın:

    ```bash
    git clone https://github.com/kullaniciadi/projeadi.git
    ```

2. Gerekli bağımlılıkları yükleyin:

    ```bash
    pip install -r requirements.txt
    ```
