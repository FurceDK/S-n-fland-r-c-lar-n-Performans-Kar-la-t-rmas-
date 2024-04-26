# Siniflandiricilarin-Performans-Karsilastirmasi
SVM , KNN , Stochastic Gradient Descent , Naive Bayes , Random Forest , Decision Tree sınıflandırıcılarının el yazısı okumadaki performanslarının karşılaştırılması.

El yazısı karakter tanıma , yapay zekanın örüntü tanıma içeren bir dalıdır. El yazılarını okuyabilen bir bilgisayar , kağıt belgeleri , fotoğrafları , ekranlardaki ve diğer kaynaklardaki karakterleri tanıyabilir ve makine diline dönüştürebilir. El yazısı tanıma günlük hayatta bilgi depolamak ve iletmek için pratik bir yol olduğu için önemli bir çalışma konusu haline geldi. Bu çalışmanın amacı öğrencilerin elle yazılmış notlarını okumak için yapılmış bir karakter tanıma sisteminin oluşturulmasını açıklamaktır. Makine öğrenmesi üzerine kurulu bu sistem , diğer işlem teknikleriyle karşılaştırıldığında daha yüksek verimli ve güçlüdür. Ayrıca bu çalışma “El yazısı karakter tanıma” metodolojisini ve sistem geliştirmedeki sonuçlarını ele almaktadır.


Problem Bildirimi: Burada el yazısı rakamları sınıflandırmak için kullanılan bir problem bildirimimiz var. Bu ifadenin temel amacı, el yazısı veri setini girdi olarak almak ve veri setinde hangi rakam veya karakterlerin bulunduğunu belirlemektir. Burada veri kümesindeki rakamlar birden (1) ila dokuz (9) arasında değişir.
Veri kümeleri : Burada, 8x8 görüntü (64 bit) basamak koleksiyonu olan Sklearn'ün load_digits veri kümesini kullandık. Burada veri seti toplam 1797 örnek nokta içerir. El yazısı rakamları sınıflandırmak için gerekli adımlar şunlardır:
• Öncelikle Sklearn dokümanlarından rakam veri setini indirin.
• Ve ardından rakam veri setini önişleyin.
•Sonra el ile yazılmış rakamlarını sınıflandırabilen bir sınıflayıcıyı eğitin.
• Son olarak modeli test seti üzerinde uygulayarak doğruluğunu raporlayın. Modelin performansını ölçmek için doğruluk puanını kullanacağız. Doğruluk bize test verilerimizin yüzde kaçının doğru sınıflandırıldığını söyleyecektir. Mevcut verilerden, görüntülerin %70'ini sınıflandırıcıyı eğitmek için kullandık ve geri kalan %30'u test etmek için kullanıldı. 
