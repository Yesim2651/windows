# Temel Windows MS-DOS Komutları Nedir?
---
MS-DOS komutları, Windows'un komut satırı arayüzünde (CMD) kullanılan temel komutlardır. Bu komutlar, dosya ve dizin yönetimi gibi işlemleri gerçekleştirmek için kullanılır. 

## Komut istemi nasıl çalışır ?
 **1**
 klavyenizdeki
     
    Win +R

tuşlarına aynı anda basınız.

<img src="win + r.png">

**2**
Açılan "**Çalıştır**" penceresindeki kutuya 

       cmd
        
yazarak  " **Tamam** " butonuna basınız.

<img src="cm.png">

## Komut İstemi Penceresi Neye Benzer

    Başlat - Programlar - Donatılar - Konut İstemi

Şimdi  ms-dos komut istemi penceremizi açtık artık kodlarımızı birer birer öğrenmeye ve uygulamaya başlayalım :

**1.dir** :
---
     
**dir(directory)** komutu, bir dizindeki dosya ve klasörlerin listesini, son değiştirme zamanı ve dosya boyutlarıyla birlikte görüntüler.

- dir /a :

**/a**  parametresi ile dir komutu, gizli ve sistem dosya ve dizinleri dahil olmak üzere tümünü (a)ll listeler.

- dir/ah :

**/ah** parametresi ile dir komutu sadece gizli /(h)idden dosya ve klasörleri listeler.

<img src="dir komutu.png">


**2.cd** :
---


**cd(change directory)** komutu, üzerinde bulunan dizini değiştirmek için kullanılır.

- **cd** komutundan sonra direk bir dizin yolu (directory path) da girilebilir.
  

<img src="cd komut.png">

**3.md** :
---

**md komutu(make directory)** bulunulan dizin içerisinde " **Yeni Klasör** " adında, bir boş dizin oluşturur. Sizde bu komutu uuygulayıp ardından " **dir** " komutu ile " **Yeni klasör** " adında bir klasörün oluştuğunu gözlemleyebiliriz.

- md komutu ile tek cümle ile iç içe dizinler oluşturmanız mümkündür.

<img src="mkdir.png">


**4.ver** :
---

**ver komutu** işletim sisteminin sürüm bilgilerini görüntülemek için kullanılır. 
 
 
 ver **komutunun Özellikleri** :

 **1.işlevi** :

 * kullanıldığı zaman işletim sisteminin sürüm numarasını gösterilir.
 * Daha detaylı bilgi vermez; sadece sürüm numarası gösterir.
  
  **kullanımı** :

  * Komut istemine (command prompt) şeklinde yazılır.


 <img src="ver.png">

 **5.del** :
  ---

 del(delete) komutu dosyaları silmek için kullanılır.

 **del** a.txt :

 -bu komut bulunulan dizindeki "**a.txt**" metin dosyasını siler.
 <img src="type nul.png">

 <img src="del-1.png">


 

 **6.ren** :
 ---

 Dosya ve klasörlerin isimlerini değiştirmemize yarar. Windows arayüzündeki karşılığı " **sağ Tuş Menü> Yeniden Adlandır** " butonudur. 

 * dosya veya kalsörün uzantısını da değiştirir.
  
  <img src="ren1.png">
  
  <img src="ren.png">


 **7.move**  :
 ---

 Dosya ve klasörleri, bulunduğu dizinden başka bir dizine taşımamıza yarar.(kes + yapıştır olarak da düşünülebilir.
 )

<img src="MOVE1.png">

<img src="move.png">

 **8. ping** :
 ---


**ping** komutu, ağ bağlantılarını test etmek ve bir hedefin  (bir sunucu veya cihazın) erişilebilirliğini kontrol etmek için kullanılan bir ağ teşhis aracıdır. Hem Windows hem de Linux gibi sistemlerde bulunur.

  **İşlevi** :

  a. Hedef cihazın eriişilebilirliğini kontrol eder.

  b. Ağ gecikme süresini (ms) ölçer.

  c. Ağ sorunlarını teşhis eder.

<img src="ping.png">



**9.tree**  : 
---

Klasör içindeki dizinleri **soy ağacı** şeklinde görüntüler.

<img src="tree.png">

**10.vol** :
---

Bir sürücünün etiket adını (volume label) ve seri numarasını görüntüler.
  **Kullanımı** : 

  Komut istemcisine (CMD) aşağıdaki gibi çalışır :

  <img src="vol.png">



**11.date** :
---

Bilgisayarın geçerli sistem tarihi görüntülemek ve güncellemek için kullanılır.

İPUCU:  Eğer **date** komutunu kullandıktan sonra tarihi değiştirmekten vazgeçerseniz hiçbir şey yazmadan sadece **enter** tuşuna basmanız yeterlidir.



<img src="date.png">


**12.net**  :
---

Ağ bağlantılarını ve ilişkili servisleri yönetmek için kullanılan kapsamlı bir komuttur.


* 1.net user : Kullanıcı hesaplarını listelemek veya silmek için kullanılır.
  

* 2.net user : Klasör paylaşımını yönetir.

* 3.net view : Ağdaki cihazları ve paylaşılan kaynakları gösterir.

* 4.net use : Ağ sürücülerini eşleştirir veya bağlantıları kaldırır.



<img src="net.png">

**13.hostname** :
---

Bilgisayarın adını öğrenmek için kullanılır.



<img src="hostname.png">


 **14.getmac**  :
---
 

 AMACI :

 Windows işletim sisteminde bilgisayarın ağ bağdaştırılarına ait  **MAC (Media Access Control)**  adreslerini görüntülemek için kullanılır. 

 Bu komut bir bilgisayarın ağ arayüzlerine dair hızlı bir şekilde bilgi edinmek için oldukça kullanışlıdır.


 <img src="getmac.png">


 **15.assic**  :
 ---

 **assic** komutu : 

 1.Tüm dosya ilişkilendirmelerini listeler.

2.Belirli bir dosya uzantısının ilişkilendirmesini görmemizi sağlar.

3.Dosya uzantısını programla ilişkilendirmesini değiştirmemizi sağlar.

4.Bir ilişkilendirmeyi kaldırır.


<img src="assic komutu.png">

 


**16.ipconfig** : 
---

**ipconfig**  komutu bilgisayarın sahip olduğu ağ bağdaştırıcılarının geçerli ağ yapılandırmasını listeler.

Genellikle daha ayrıntılı görüntülemek için **/all** parametresi ile kullanılır.

<img src="ipconfig.png">
 


**17.cls** :
---
Windows komut istemcisinde (command prompt) ekranı temizler. Kullanıcıya mevcut komut geçmişini gizleyerek yeni bir başlangıç sağlar ve komut satırında daha düzenli bir görünüm sağlar.

<img src="csl sil.png">

<img src="Ekran görüntüsü 2024-11-16 202858 - Kopya.png">

**18.netsh wlan show profile** :
---


  cihazda kaydedilmiş tüm kablosuz ağ profillerini (wi-fi bağlantıları) listelemek için kullanılır

  **Komutun İşlevi**

  1. Kaydedilmiş Wi-Fİ Ağlarını görüntüler.
  2. Wi-Fi profilleri hakkında detaylı bilgi almamızı sağlar.
  3. Kaydedilmiş Wi-Fi şifresini görmemizi sağlar.

<img src="netsh.png">  



**19.shutdown**
---

**Bilgisayarı kapatmak** (shutdown) veya **yeniden başlatmak** (restart) için kullanılır.

* Bilgisayarı kapatmak için **/s** parametresi ile kullanılır.

* Bilgisayarı yeniden başlatmak için ise **/r** parametresi ile kullanılır.

<img src="shutdown.png">

**20.help**
---

* Komut Yardımı Sağlar : help  [komut_adı] şeklinde kullanıldığında belirli bir komut hakkında ayrıntılı bilg, verir. 


#ipconfig komutunu kullanarak **ipconfig** komutunun ne işe yaradığını ve hangi parametrelerin kullanılabileceğini öğrenilir. 


* Komut Listesi Görüntüler : 
Sadece help komutu yazdığınızda mevcut tüm komutların kısa açıklamalarıyla bir listesini gösterir. Bu komut işlemcisinde hangi komutların kullanılabileceğini görmek için faydalıdır.


<img src="help-1.png">


