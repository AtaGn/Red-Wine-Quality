# Red-Wine-Quality

## **Kullanılan Makine Öğrenimi Modelleri**
1. **Lojistik Regresyon (Logistic Regression)**
Lojistik Regresyon, bağımlı değişkenin kategorik olduğu durumlarda kullanılan ve sonucu olasılık cinsinden veren bir regresyon modelidir. Özellikle ikili sınıflandırma problemlerinde tercih edilir. Model, verilen bağımsız değişkenlere göre sonucun olma olasılığını hesaplar.

2. **KNeighbors Sınıflandırıcı (KNeighborsClassifier)**
K-En Yakın Komşu (KNN), bir veri noktasını, en yakın k komşusunun çoğunluk sınıfına göre sınıflandıran temel bir sınıflandırma algoritmasıdır. Uzaklık ölçütleri (genellikle Öklid mesafesi) kullanılarak, yeni bir veri noktasının, mevcut veri noktalarına olan yakınlığına göre sınıfı tahmin edilir.

3. **Destek Vektör Makineleri (Support Vector Classifier - SVC)**
Destek Vektör Makineleri, verileri en iyi ayıran hiper-düzlemi bulmaya çalışan güçlü ve esnek bir sınıflandırma modelidir. SVC, özellikle verilerin doğrusal olarak ayrılamadığı durumlar için çekirdek hileleri (kernel tricks) kullanarak etkili sonuçlar elde edebilir.

4. **Karar Ağacı Sınıflandırıcısı (DecisionTree Classifier)**
Karar Ağaçları, kararlar ve olası sonuçları, rastgele olayları, maliyetleri ve faydaları ağaç yapıları olarak modelleyen bir sınıflandırma ve regresyon modelidir. Ağaç, karar düğümleri ve yaprak düğümlerden oluşur, her karar düğümü bir öznitelik üzerinden bir testi temsil eder.

5. **Rastgele Orman Sınıflandırıcısı (RandomForest Classifier)**
Rastgele Orman, birden fazla karar ağacını birleştirerek çalışan bir ansamble öğrenme tekniğidir. Her bir karar ağacı biraz farklı veri alt kümeleri üzerinde eğitilir ve sonuçta, bireysel ağaçların tahminlerinin ortalaması alınarak daha kararlı ve doğru tahminler elde edilir.


Data Link: https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009/data
