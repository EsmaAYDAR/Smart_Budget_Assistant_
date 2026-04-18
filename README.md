# Smart_Budget_Assistant_
Fonksiyonlar, args yapısı ve hata yönetimi kullanılarak geliştirilmiş bütçe analiz projesi.

1. Fonksiyon kullanmanın avantajları:

Fonksiyonlar, yazılan kodu daha düzenli ve yönetilebilir hale getirmek için oldukça önemlidir. Aynı işlemi birden fazla yerde tekrar yazmak yerine fonksiyon kullanarak kod tekrarını azaltmak mümkün olur. Bu da hem geliştirme sürecini hızlandırır hem de hata yapma ihtimalini düşürür.

Ayrıca fonksiyonlar sayesinde kod parçaları anlamlı bölümlere ayrılır. Bu durum, projenin okunabilirliğini artırır ve başkaları tarafından daha kolay anlaşılmasını sağlar. Özellikle büyük projelerde fonksiyon kullanımı, kodun sürdürülebilirliği açısından büyük avantaj sağlar.

2. Args neden gereklidir?

Args yapısı, fonksiyonlara değişken sayıda parametre gönderebilmeyi sağlar. Bu da fonksiyonları daha esnek hale getirir. Sabit sayıda parametre ile yazılmış fonksiyonlar belirli durumlarla sınırlı kalırken, args kullanımı sayesinde farklı veri sayılarıyla da çalışabilen fonksiyonlar oluşturulabilir.

Bu esneklik özellikle kullanıcıdan gelen verilerin sayısının önceden bilinmediği durumlarda büyük kolaylık sağlar. Böylece fonksiyonlar daha genel amaçlı ve yeniden kullanılabilir hale gelir.

3. Scope-kapsam- hataları neden sık yapılır?

Scope (kapsam), bir değişkenin nerede tanımlandığını ve nerede kullanılabileceğini ifade eder. Scope hataları genellikle değişkenlerin hangi alanda geçerli olduğunun tam anlaşılmamasından kaynaklanır.

Örneğin bir fonksiyon içinde tanımlanan değişkenin, fonksiyon dışında da kullanılabileceği düşünülürse hata oluşur. Aynı şekilde global ve local değişkenlerin karıştırılması da sık yapılan hatalardandır. Bu hatalar özellikle yeni öğrenen kişilerde daha yaygındır çünkü değişkenlerin yaşam alanı ilk başta karmaşık gelebilir.

4. Try/except gerçek sistemlerde neden kritiktir?

Try/except yapısı, program çalışırken oluşabilecek hataların kontrol altına alınmasını sağlar. Gerçek sistemlerde kullanıcıdan alınan veriler her zaman doğru olmayabilir veya beklenmeyen durumlar oluşabilir. Bu tür durumlarda programın tamamen durması yerine hatayı yakalayıp uygun bir şekilde devam etmesi gerekir.

Bu nedenle try/except kullanımı, programın daha güvenli ve dayanıklı olmasını sağlar. Özellikle kullanıcı etkileşimli uygulamalarda, hataların yönetilmesi kullanıcı deneyimi açısından kritik bir öneme sahiptir.
Esma AYDAR
