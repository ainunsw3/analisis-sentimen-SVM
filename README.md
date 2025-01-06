**Analisis Sentimen Ulasan Aplikasi dengan SVM**
Analisis sentimen bertujuan untuk menilai opini pengguna aplikasi yang dapat digunakan sebagai pertimbangan untuk melakukan improvisasi dari hasil analisis sentimen. 

**Set**
Dataset: Ulasan aplikasi dari Google Play Store 
Lexicon: VaderSentiment
Classifier: Support Vector Machine dengan kernel Linear

**ALGORITMA**
- Scraping data
- Pelabelan Lexicon : VaderSentiment
- Text Preprocessing : case folding, remove stopwords, tokenizing, stemming
- Pembobotan kata : TF-IDF
- Klaifikasi : SVM
- Pengujian : Cross Validation
