---
title: "Wii Menü Temaları yükleme"
---

{% include toc title="Table of Contents" %}

Eğer bu öğreticiye bağlı herhangi bir yardıma ihtiyacınız olursa lütfen [RiiConnect24’ün Discord sunucusuna katılın](https://discord.gg/rc24) (tavsiye edilen) ya da [support@riiconnect24.net üzerinden mail atın](mailto:support@riiconnect24.net).
{: .notice--info}

Wii Menü'nün beyaz teması canınızı oldukça sıkıp sizi yeni tema arayışlarına mı soktu? Bu öğretici size Wii Menü'nüz için yeni bir tema elde etmenizi sağlayacak!

Brick modu gibi bir durumda [Priiloader'ı yüklemeniz gerekir](priiloader). Ayrıca BootMii'yi (ilk Wiiler için Boot2) yükleyin. Bu rehberi takip ederken brick koruması yüklemek sizi brick modundan koruyacaktır. PRIILOADER VE BOOTMII'Yİ YÜKLEMEDEN SAKIN DEVAM ETMEYİN!
{: .notice--warning}

Eğer vWii ve Wii U'nuzun bölgesine uygun olarak formatlanmadıysa, sakın vWii'nize özel tema yüklemeyin! vWii temalarına [bu GBATemp gönderisinden](https://gbatemp.net/threads/tutorial-installing-custom-themes-in-vwii.476012/) ulaşabilirsiniz.
{: .notice--warning}

Güvenliğiniz için, lütfen en güvenli tema yükleme yolu olan MyMenuify’ın linkte verilen dışında başka bir sürümünü kullanmayınız.
{: .notice--info}

Linki verilen ThemeMii sürümü dışında başka bir sürüm kullanmayınız. Linki verilen sürüm, Wii Menü'nün 4.3 sürümü için tema üretebilir ancak diğer sürümler üretemeyebilir.
{: .notice--info}

Devam etmeden önce [cIOS yüklemenizi](cios) öneririz.
{: .notice--info}

#### İhtiyacınız olan şeyler

* Wii
* SD Kart veya USB sürücü
* Windows’u olan bir bilgisayar (ya da Mac/Linux için Mono veya Wine)
* [MyMenuify Mod](/assets/files/MyMenuifyModv1.5.zip)
* [ThemeMii Mod](/assets/files/New_Thememii_MOD.rar)

#### Tema Bağlantıları

Yüklenecek temalar için 3 kaynak bulunmaktadır. Bunlar:

* [Google Drive deposu](https://drive.google.com/drive/folders/19tyeVQ--bJ0ZUTNg5yvAGvc3G4-euEpm?usp=sharing)
* [RiiConnect24 tema sayfası](https://rc24.xyz/goodies/themes/)
* [Bu GBAtemp gönderisi](https://gbatemp.net/threads/wii-theme-team-creations-v2.336596/)

DEVAM ETMEDEN ÖNCE YUKARIDAKİ UYARILARI OKUDUĞUNUZDAN EMİN OLUN!
{: .notice--warning}

#### Talimatlar

##### Bölüm I - Tema Bulma

* Kaynakları inceleyerek istediğiniz temayı bulun. Bazı temaların neye benzediklerini gösteren YouTube videoları var; ancak maalesef bazılarının yok.
* Bulduğunuz vakit, Wii Menü sürümünüze uygun olan bir bağlantıyı indirin. **Brickleri engellemek için doğru olanını seçmek önemlidir.**
* Büyük ihtimalle 4.X yazan bir bağlantıyı indireceksiniz. Bu da, bu temanın Wii Menü'nün 4.1, 4.2 ve 4.3 sürümlerinde çalıştığı anlamına gelir.
* Bazı temalar, bölgeye göre farklı bağlantılara sahiptir. O yüzden Wii'nizin bölgesine uygun olanını seçin.
* Wii Menü temaları için başka kaynaklar da bulunmaktadır. Ancak scm formunda (Wii'ye yüklemeye hazır) olabilir. Eğer csm Wii Menü'nüzün sürümü ve bölgesi ile uyuşmuyorsa, ThemeMii Mod ile mym formuna dönüştürebilir ve buradaki sürüm ve bölge kullanımı talimatlarıyla tekrardan csm formuna dönüştürebilirsiniz.
* Temayı yüklediğiniz zaman doğru dosya olduğunu kontrol etmek istiyorsanız ThemeMii Mod'u açın.

##### Bölüm I - Tema Yapımı

1. Bir iletişim penceresi, size sadece brick koruması olan temaları yüklemenizi söyleyecek. Eğer Priiloader ve(ya) BootMii yüklediyseniz (Rehberin başlangıcındaki uyarıya bakın), OK'a basın.
2. `Tools` > `Download Base App` > Version of your Wii Menu > Region of your Wii Menu kısmına gidin.
3. Bir iletişim penceresi, sizden anahtar oluşturmak için bir değer girmenizi isteyecek. Ne yazıyorsa onu girin. Nintendo sunucularındaki Wii Menü içeriklerinin şifresini kıracak bir anahtar oluşturulacaktır.
4. Dosya seçme kutusu size .app dosyasının (Wii Menü içeriklerinin yüklendiği dosya) nereye kaydedileceğini soracak. ThemeMii'nin bulunduğu konuma kaydedin.
5. `Options` > `Standard System Menu` > Version of your Wii Menu > Region of your Wii Menu kısmına gidin.
6. `File` > `Open` gidin ve .mym dosyanızın nerede olduğunu bulun.
7. `Create csm` deyip temayı nereye kaydetmek istediğinizi belirleyin. Temayı yapması için biraz bekleyin.
8. İletişim penceresi, umarız ki size tema yapımının başarılı olduğunu söyleyecek ve .mym dosyasını kaydetmek isteyip istemediğinizi soracak. `No` seçeneğini seçin.

##### Bölüm III - Tema Yükleme

1. MyMenuify Mod’u çıkartın ve SD Kart ya da USB sürücünüzdeki `apps` klasörüne koyun.
2. Kaydettiğiniz .csm dosyasını SD Kart ya da USB sürücünüzdeki `modthemes` klasörüne koyun.
3. SD Kartınızı veya USB sürücünüzü Wii’nize takın.
4. Homebrew Channel’dan MyMenuify Mod’u başlatın.
5. Giriş mesajından sonra, size uygulama için hangi IOS'u kullanmak istediğinizi soracak. Eğer [yüklü cIOS'unuz](cios) varsa `IOS249'u` veya `IOS58'i` seçin. Eğer `Exception DSI occurred!` hatasını alırsanız, RESET'e basın ve uygulamayı tekrardan başlatıp bu sefer `IOS250'yi` deneyin.
6. Yüklemek istediğiniz temayı seçip A'ya basın. Temanın yüklenmesi için biraz bekleyin, ardından herhangi bir tuşa basarak Wii Menü'ye dönün. Umarız, tema doğru olarak yüklenmiştir.

Eğer ''Sistem dosyaları bozuk'' adlı bir uyarı aldıysanız, Priiloader yüklediğinizden dolayı panik yapmanıza gerek yok. Wii'nizi kapatın ve RESET tuşuna basılı tutun ve Wii'nizi açın. Wii Menü'nüzü düzeltebileceğiniz Priiloader menüsünü açmış olmanız gerekir. Seçeneklerden biri MyMenuify Mod'u başlatıp a tuşuna basarak Wii Menü temasını yükleyeceğiniz Homebrew Channel'ı Başlat olacaktır.
{: .notice--info}
