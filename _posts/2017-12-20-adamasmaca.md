---
layout: post
title: Adam Asmaca Oyunu

categories:
  - C#
  - Projeler
  
tags:
  - C#
  - Adam Asmaca
  - Yapay Zeka
  
excerpt_separator:  <!--more-->
---

Bu oyun kapalı gri renkte, sade ve flat tasarımlıdır. İçinde, `kullanıcı modu` ve `bilgisayar modu` olmak üzere 2 adet oyun modu bulunur.   
1. Kullanıcı Modu
 > Kullanıcının sorudaki harf sayısı ve türü belli olan kelimeyi, çöp adamın vucüt parçaları olan kafa, vucüt, 2 kol ve 2 bacak olmak üzere
toplam 6 kere yanmadan bilmeye çalıştığı oyun modu.  
2. Bilgisayar Modu
 > Kullanıcının **"BΛŞLΛT"** butonuna basmasıyla ***yapay zeka*** sorudaki harf sayısı ve türünü öğrenir. 
Ardından bu özelliklerle benzerlik gösteren kelimeleri belli bir algoritmayla kontrol ederek doğru kelimeyi bulmaya çalışır.
<!--more-->

## Başlangıç

![Görüntü](/screenshots/welcome.png?raw=true "Hoşgeldiniz")

Oyunu çalıştırdıktan sonra bizi yukarıdaki ekran karşılar. `Netzwerk` kısmı oyunun açıldığı bilgisayarın ismini alır.  
Oyun bize iki adet seçenek sunuyor, `Oyuna Başla (kullanıcı modu)` ve `Bilgisayar Modu`. Öncelikle kullanıcı modundan bahsedelim.


##	 Oyuna Başla (Kullanıcı Modu)

![Görüntü](/screenshots/user-1.png?raw=true "Kullanıcı Modu")

**Oyuna Başla** seçeneğini seçtikten sonra,  
kelime haznesinden rastgele bir kelime seçilir.  
üst taraftaki dikdörtgende sorulan kelimenin harf sayısı ve türünün bilgisi verilir ve dikdörtgenin içinde kelimenin harf sayısı kadar çizgi bulunur.  
Alt taraftaki dikdörtgende ise klavye, kelimeyi tahmin etmek için kutucuk ve buton bulunur.  
Sağ tarafta ise bir dar ağacı hazır ve nazır bi şekilde çöp adamı beklemektedir...

### Nasıl Oynanır?

* Klavyeden tahminde bulunmak istediğiniz harfi seçin. Yalnız dikkatli olun! Her yanlış harf seçtiğinizde çöp adamın bir bölgesi asılacak. 6 kere yanlış cevaplarsanız oyunu kaybedersiniz.
* Eğer tahminleriniz doğruysa, kelime kısmındaki çizgilerin uygun yerlerine kelimedeki doğru bildiğiniz harfler geçecek. 
* Sorudaki kelimeyi bulduğunuzu düşünüyorsanız, ya klavyeden diğer harflerini de açın ya da **TAHMİN ET!** kısmındaki kutucuğa kelimeyi yazın ve **TAHMİN ET!** butonuna basın.

Sorulan kelimeyi doğru bildiyseniz sizi aşağıdaki pencere karşılayacaktır:  
![Görüntü](/screenshots/bildin.png?raw=true "Oyun Sonu: bildiniz")

Ya da 6 kere yandıysanız ve kelimeyi bilemediyseniz de maalesef ki çöp adam asılacak ve sizi aşağıdaki pencere karşılayacaktır. *Parantez içindeki sayılar Çöp Adamın doğum ve ölüm saati :/*  
![Görüntü](/screenshots/bilemedin.png?raw=true "Oyun Sonu: bilemediniz")

Oyun bittikten sonra tekrar oynamak isterseniz pencerenin altındaki **"Yeniden Oyna"** butonuna basın. Pencere kapanacak ve başka bir kelime ile yeni oyuna başlayacaksınız. Umarım bu sefer sıfır hata ile kazanırsınız :)
Kullanıcı modu bu kadardı. Şimdi Bilgisayar moduna geçelim..


##	 Bilgisayar Modu

![Görüntü](/screenshots/pcmode-1.png?raw=true "Bilgisayar Modu")

Bu modun ekranı da kullanıcı modu ile aynıdır fakat tahmini bilgisayar yapacağı için tahmin kutucuğu ve butonu yerine oyunu başlatacağımız **BΛŞLΛT** butonu bulunur. Ayrıca klavyedeki harfler de pasiftir.

### Nasıl Oynanır?

* Yapay zekanın sorulan kelimeyi bulma çabasını izlemek için **BΛŞLΛT** butonuna basın.
* Biraz geriye yaslanıp ve çay, kahve, su veya herhangibir içeceği keyifle yudumlayarak yapay zekanın kelimeyi bulmak için nasıl uğraştığına şahit olabiliriz. Çünkü her tahminini canlı olarak izleyebiliyoruz.
* Ardından muhtemelen bu keyif, saniyeler içinde bitecek ve yapay zekanın kelimeyi bulduğuna şahit olacağız.

Oyun bittiğinde alttaki pencere karşılayacak bizi. İçinde bize el sallayan gayet mutlu bir robot (altı üstü kelime bildin ne bu artizlik) ve altında kaç adet benzer kelimeden kaç yanlışla bildiğinin bilgileri yer alıyor.
![Görüntü](/screenshots/pcmode-2.png?raw=true "Oyun Sonu - Bilgisayar Modu")

Yok bu kesmedi beni yeniden başlatayım da uğraşsın dursun ufaklık<abbr title="veya herhangibir hitap şekli :)">*</abbr> ben de keyifle izleyeyim derseniz: **"Yeniden Oyna"** butonuna bir click yeterli...

<p class="message">
Oyunun GitHub deposu: https://github.com/onuryarar/Adam-Asmaca
</p>

<strong> İyi Oyunlar! :) </strong>
