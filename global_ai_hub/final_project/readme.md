### Global Ai Hub - Introduction to Machine Learning Kursu Final Projesi

Bu proje kaggle.com'dan alınmış 8124 mantardan oluşan bir veri setini içermektedir. Yenilebilir ve zehirli olarak tanımlanmaktadır. 
Biz de Makine Öğrenmesi modelleriyle bu veri setini inceleyeceğiz. 
Mantar söz konusu olduğunda, yenilebilirliği belirlemek için basit bir kural yoktur ve dikkatli olmalıyız.

Veri setini import ettikten sonra verileri grafik üzerinde yenilebilir - zehirli olarak inceliyoruz.
Ardından verileri train ve test olarak bölüyoruz. (70-30 oranında böldük.)
Burada verilerin %70'ini makine öğrenmesini eğitmek için %30'unu ise doğruluğunu test etmek için kullanıyoruz.

Ardından farklı modeller için eğitiyoruz ve test ediyoruz. 

* Logistic Classifier
* Ridge Classifier
* Decision Tree
* Naive Bayes
* Neural Network

Ardından tüm bu modellerin performanslarını karşılaştırıyoruz. Performans karşılaştırmasında en iyi sonucun Decision Tree (Karar Ağaçları) 'nin verdiğini görüyoruz. 

Bir adım daha ileri giderek Random Forest modeli ile aynı işlemleri gerçekleştiriyoruz ve Decision Tree ile aynı sonucu aldığımızı görüyoruz ve bu veri seti için Decision Tree (Karar Ağacı) veya Random Forest (Rastgele Orman) kullanmak arasında bir fark olmadığı sonucuna varıyoruz. Modellerin başlangıç değerleri rastgele oluşturulduğu için her seferinde farklı sonuçlar elde etmek mümkündür. Modelleri değerlendirirken ve karşılaştırırken bunu daima aklınızda bulundurun.
