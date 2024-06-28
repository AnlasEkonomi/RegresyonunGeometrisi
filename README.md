# Regresyonun Geometrisi

Her şeyi ölçmek gibi çılgın bir alışkanlığınız olduğunu düşünün. Bir tiyatro veya toplantıda insanlar kaç defa esner, kaç defa kıpırdarlar? Masabaşı çalışan birisinin ayık kalması için kafasına kaç dakikada bir su damlatılması lazım? Bir masada yemeğe ulaşmak için sofraya doğru ne kadar eğilmek gerekir? İdam mahkumlarını asmak için gerekli olan ipin kalınlığı ne kadar olmalıdır? Bir portre için ortalama kaç fırça darbesi vurmak gerekir? Uzun boylu ebeveynler uzun boylu, kısa boylu ebeveynler kısa boylu çocuklara mı sahip olur? 

Uzun yıllar boyunca birçok çalışması büyük tartışmalara yol açan, insanların yaşamı boyunca parmak izlerinin değişmediğini belirten ilk antropolog. Charles Darwin’in kuzeni, Galton Kutusu’nun mucidi. İngiliz bilim insanı Sir Francis Galton, yukarıda yazdığım tüm çılgınlıkların sahibidir. 

![image](https://github.com/AnlasEkonomi/RegresyonunGeometrisi/assets/173607120/0814b80b-f2d7-48a3-bace-e266f552f230)   ![image](https://github.com/AnlasEkonomi/RegresyonunGeometrisi/assets/173607120/56f50335-cdc0-4420-879d-12dda23890ff)

Peki bunların regresyon ile ne ilgisi var?

Regresyon analizi, belirli varsayımlar altında bağımsız değişken veya değişkenlerin bağımlı değişkene nasıl bağlanacağı ile ilgili inceleme tekniğidir. Bu terimi ilk defa kullanan ise Sir Francis Galton’dur (Galton, 1886). Tabi ki daha öncesinde Adrien Marie Legendre ve Carl Friedrich Gauss gibi bilim insanları,  “En Küçük Kareler Prensibi” ile uyduların güneş etrafındaki yörüngelerini tespit etmek için çalışmalar yapmış ve Galton gibi bilim insanlarına yol gösterici olmuştur. 

Temel bir matematiksel model ile sürece başlayalım.

Y= a + bX 

Lise matematiğimize dönelim. Dersimiz “Analitik Geometri”, konumuz “İki Noktası Bilinen Doğrunun Denklemi” olsun. Öncelikle işe boş bir koordinat sistemi ve bir doğru çizerek başlayalım. 

![1](https://github.com/AnlasEkonomi/RegresyonunGeometrisi/assets/173607120/7b764ffd-8c14-45a8-86fa-1984e782ce2c)

İki noktası bilinen bir doğrunun denklemini bulabilmemiz için iki şart vardır. Bunlardan ilki “Doğrunun eğimi”, ikincisi ise “Doğru üzerinde iki noktanın oluşturduğu koordinatlar”. O zaman hemen devam edelim. 😊

Doğru üzerinde A noktasının koordinatları (X1 , Y1), B noktasının ise (X2 , Y2) olsun. 

![2](https://github.com/AnlasEkonomi/RegresyonunGeometrisi/assets/173607120/4b88e78a-d744-4ee2-8f22-424ea1c2f6fe)  

![3](https://github.com/AnlasEkonomi/RegresyonunGeometrisi/assets/173607120/5195ce63-8f98-49a6-af6b-eaee93c49574)

Doğrunun denklemi için şartlardan birisini sağlamış olduk. Yani A ve B noktalarına teorik olarak bir koordinat yerleştirmiş olduk. Şimdi denklemi yazmak için ikinci şart olan eğimi bulalım. Yine lise yıllarımıza dönersek, bu sefer dersimiz “Geometri”, konumuz “Eğim”. Geometri dersinde eğim konusunu düşünürsek, bir dik üçgende Tan α değeri bize eğimi verecektir. Hatırladınız mı? Şimdi biraz daha eğlenceli olmaya başladı sanki. 😊 

O zaman bir dik üçgen üzerinde inceleme yapalım. Yukarıda gösterdiğim doğru üzerindeki 2 noktanın oluşturduğu üçgenin büyük hali gibi düşünün bu üçgeni. Yani zoom yapıyoruz;

![4](https://github.com/AnlasEkonomi/RegresyonunGeometrisi/assets/173607120/2b39731c-d6c5-4e8c-8681-feb9d72b94c0)

Yine lise yıllarına dönüp ufak bir hatırlatma yaparsak, Tan α değerinin “karşı/komşu” olduğunu hatırladık değil mi? Matematiksel bir formüle dökersek, A-C mesafe / C-B mesafe diyebiliriz.
O zaman ilk başta çizdiğimiz koordinat sisteminde eğimi nasıl bulacağız? Yine aynı mantık ile bir formül oluşturursak ve eğime “m” dersek;


Koordinat sistemi üzerinde Tan α açısının karşısı (Y2 – Y1), komşusu  (X2 – X1) olacağına göre;

![5](https://github.com/AnlasEkonomi/RegresyonunGeometrisi/assets/173607120/84db11e1-f948-494a-8104-8f61efdbcce3)


şeklinde formül yapısına çevirebiliriz. Aslında bu formül yapısında, X’i bir girdi değişkeni olarak düşünürsek, çıktı değişkeni olarak düşüneceğimiz Y değişkenini ne kadarlık bir birimde değiştireceğini söyleyen katsayıdır.

O zaman bu cümleye dikkat!!!

“Matematiksel olarak eğim, X koordinatındaki değişim durumunda, Y koordinatında ne kadarlık bir değişimin söz konusu olduğunu tespit etmeye yarayan bir yapıdır.” 

Doğrunun denklemi için iki şartı da gerçekleştirdiğimize göre, doğrunun denklemini yazabiliriz artık değil mi? 

Y2 – Y1 = m (X2 – X1) ise, denklemimiz;

Y = mX şeklinde olacaktır. 

Şimdi Y= a + bX matematiksel modeli hatırlayalım. Y = mX ile arasında biraz benzerlik var gibi değil mi? O zaman “m” dediğimiz eğime “b” diyelim ki biraz daha benzesin. 😊

Y = bX 


Peki eksik olan nedir?  “a” sabiti !!! “a” sabitini neden bulamadık? Aslında doğrunun denklemi içerisinde a sabitini bulduk ama doğrumuz koordinat sisteminde orijinden (sıfır noktası) geçtiği varsayımı altında sıfır değerini aldı ve denklem içerisinde yokmuş gibi karşımıza çıktı. Doğru yapısı her zaman sıfır noktasından geçemeyeceği için biz denklem içerisine bir “a” sabit parametresi ekleyeceğiz. Peki bunu neden yaptık? 

Ekonometrik bir modelde doğruyu orijinden geçirirsek, bağımsız değişkenler sıfır olduğu varsayımı altında bağımlı değişkenimiz de sıfır olacaktır. Peki bu neden mantıksız olur? Bir fabrika açtığınızı düşünün. Maliyetlerinizi bir kağıda yazdığınızda, bazı maliyet kalemlerinin sabit, bazılarının ise değişken olduğunu göreceksiniz. Örneğin, fabrika için ödeyeceğiniz kira bedeli sizin sabit maliyetiniz olurken, ödeyeceğiniz elektrik faturası çalışacak makinaların çalışma saatlerine bağlı kalacaktır. 

Y= bX bu modele göre yukardaki örneği uygularsak, hiç üretim yapmazsanız X dediğimiz elektrik maliyeti sıfır olacak ve eğim katsayısı “b” ne olursa olsun Y dediğimiz toplam maliyet sıfır çıkacaktır. Peki ödeyeceğimiz kira bedeli ne olacak? İşte bu basit örnekte sabit maliyetlerimizi de ekleyebilmek için “a” sabiti ekledik. Birçok ekonometrik modelde bu “a” sabitine ihtiyacımız olacaktır. 

![6](https://github.com/AnlasEkonomi/RegresyonunGeometrisi/assets/173607120/cac4e876-7eb6-4dc0-b737-34b546ac89c2)


Sabit maliyetlere (Turuncu) dikkat ederseniz, üretim miktarı arttıkça (sağa doğru gittikçe) maliyetlerde bir değişiklik olmuyor. Ama değişken maliyetlere bakarsak (Siyah kesikli), üretim miktarı arttıkça maliyetler yukarı yönlü hareket etmektedir. İşte çizdiğimiz doğrunun orijinden geçmemesinin nedeni bu sabit maliyetlerdir. Umarım bu noktaya kadar kafamızda soru işareti kalmamıştır.

Şimdi matematiksel modeli bulduk. 😊

Y = a + bX  


“Bu cümleye dikkat” dediğim bir yer vardı. O zaman bu model için şöyle bir yorum yapabilir miyiz?

X bağımsız değişkeni sıfır olduğu varsayımı ile Y bağımlı değişkeni a sabitine eşittir. Yine aynı şekilde, X bağımsız değişken değerinin 1 birimlik artışı, Y bağımlı değişken değerini b (eğim katsayısı) kadar arttırır!!!

O zaman bunu temel bir regresyon modeli olarak yazabiliriz;

Y= α + βX + ε   

İşte bu modelin ismi “Basit Doğrusal Regresyon Modeli” dir. Peki bu model ismini biraz daha tanıyalım. “Basit” kelimesi model içerisindeki bağımsız değişken sayısına göre verilir. Bizim bu modelimizde X bağımsız değişkeni bir tane olduğu için “Basit” kavramı ile söylenir. Peki gerçek hayatta bir olayı etkileyen tek bir tane mi olay var? Tabi ki hayır. O zaman bu “basit” kavramını geliştirirsek ortaya “Çoklu Doğrusal Regresyon Modeli” çıkacaktır. Bu modelin özelliği ise birden fazla bağımsız değişkeni içerisinde barındırmasından kaynaklıdır. 


Y= α + β1X1 + β2X2 + β3X3 +  …………….. + βkXk + ε

şeklinde tanımladığımız model k adet bağımsız değişkeni içerisinde barındırdığı için çoklu doğrusal regresyon modelidir.

Buradaki "ε" ise bir hata değişkenidir. Regresyon modelinin tahmin olarak kullanılması durumunda elde ettiğimiz hata değişkenidir. 

![image](https://github.com/AnlasEkonomi/RegresyonunGeometrisi/assets/173607120/de3bf274-e4c2-446e-95b5-aeb3ad03a331)

Saygılarımla...
