Bu projede, sinir ağı modeli kullanılarak diyabet veri kümesinde ikili sınıflandırma gerçekleştirilmiştir. Projenin amacı, hastaların tıbbi ölçümlerine dayalı olarak diyabet olup olmadıklarını tahmin etmektir. Veri kümesi yüklenip StandardScaler ile normalize edildikten sonra, sınıflar arası dengesizliği gidermek için RandomOverSampler kullanılarak yeniden örneklenmiştir. Veriler eğitim, doğrulama ve test kümelerine bölünmüş, ardından üç katmanlı bir sinir ağı modeli oluşturulmuştur. Model, TensorFlow ve Keras kullanılarak oluşturulmuş ve BinaryCrossentropy kayıp fonksiyonu ve Adam optimizasyonu ile eğitilmiştir. Son olarak model, eğitim ve test verileri üzerinde değerlendirilmiş, doğruluk sonuçları elde edilmiştir.