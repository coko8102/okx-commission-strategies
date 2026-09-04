# düşük komisyonlu kripto borsası: OKX ile spot ve futures komisyonlarını düşürmenin yolları

Türk Lirası ile kripto alıp satarken komisyonun ne kadar olacağını bilmek, çoğu kullanıcı için alım satımdan önceki en kritik soru. Spot piyasada %0,10 ile %0,35 arasında gezinen taker oranları, aylık işlem hacminiz arttıkça VIP kademeleri sayesinde sıfıra yaklaşabiliyor; üstüne davet kodu kullanırsanız %20 kalıcı iade ekleniyor. Bu yazıda düşük komisyonlu kripto borsası arayışının arkasındaki gerçek ihtiyaçları, OKX'in hem global hem de Türkiye (OKX TR) tarafındaki ücret kademelerini ve CASH20 davet kodunun ne işe yaradığını tek tek ele alacağız.

## Düşük komisyonlu kripto borsası neden bu kadar aranıyor?

Komisyon, kripto işleminde göz ardı edilemeyecek tek sabit maliyet kalemi. Alış-satış farkı (spread) piyasa dalgalanmasına göre değişir, ağ ücreti zincir yoğunluğuna bağlıdır; ama komisyon oranı, borsanın yayınladığı tabloda sabit durur ve her işlemde otomatik kesilir. Bu yüzden "en düşük komisyonlu kripto borsası hangisi" sorusu, aslında "aylık ortalama işlem hacmime göre hangi platform en az kesinti yapar" sorusuna dönüşüyor.

İki tip kullanıcı bu aramayı sık yapar. İlki, küçük tutarlı ve sık al-sat yapanlar: her işlemde %0,30 taker ücreti ödemek, küçük kârları eriten sessiz bir maliyet. İkincisi, kaldıraçlı ve türev işlem yapanlar: futures maker/taker oranları spotun yarısı seviyesinde dolaştığı için, %0,02 ile %0,05 arasındaki fark bile yıllık ciddi bir fark yaratır.

Aşağıda önce OKX'in standart ve VIP kademelerini tablolaştırıp, sonra CASH20 kodunun bu tablonun üstüne ne eklediğini göstereceğim. Hepsinin kaynağı OKX'in resmi ücret sayfaları ve yardım dokümanları; tahmin ya da eski veriler değil.

## OKX'in komisyon yapısı nasıl çalışır?

OKX, maker-taker modelini kullanır. Emir defterine limit emir girip likidite ekleyen kullanıcı maker, defterdeki mevcut emri anında eşleştiren kullanıcı taker ücretini öder. Standart bir kullanıcı için spot piyasada maker %0,08, taker %0,10; USDT vadeli (futures) piyasada maker %0,02, taker %0,05 seviyesinden başlar.

VIP kademeleri iki şeyle belirlenir: hesabınızdaki varlık tutarı ve son 30 günlük işlem hacminiz. Hacim arttıkça hem maker hem taker oranları düşer; en üst kademedelerde maker ücreti negatife döner, yani likidite sağladığınız için size ödeme yapılır. Kademeler her gün UTC 16:00'da snapshot alınır, 20:00-22:00 UTC arasında güncellenir.

> **Not:** Türkiye'de ikamet ediyorsanız kayıt sırasında ülke olarak Türkiye'yi seçtiğinizde otomatik olarak OKX TR altyapısına yönlendirilirsiniz. OKX TR, SPK tarafından "faaliyette bulunanlar listesi"nde yer alan OKX TR Kripto Varlık Alım Satım Platformu A.Ş. çatısı altında çalışır ve ücretler TRY cinsinden hesaplanır.

## OKX TR komisyon kademeleri (TRY cinsinden)

OKX TR'nin resmi ücret sayfasında yayınlanan tablo, TRY pariteleri için şu kademeleri içerir. Standart kullanıcıdan VIP 9'a kadar tüm seviyeler burada; tablodaki oranlar TRY çiftleri için geçerlidir.

| Kademe | Varlık (TRY) veya 30 Günlük Hacim (TRY) | Maker | Taker | 24s Çekme Limiti (USD) | Kayıt |
| --- | --- | --- | --- | --- | --- |
| Standart Kullanıcı | 0 – 5.000.000 / 0 – 5.000.000 | %0,1000 | %0,2200 | 10.000.000 | [CASH20 ile kayıt ol](https://okx.com/join/CASH20) |
| VIP 1 | 5.000.001 – 10.000.000 / 5.000.001 – 25.000.000 | %0,0700 | %0,1900 | 24.000.000 | [CASH20 ile kayıt ol](https://okx.com/join/CASH20) |
| VIP 2 | 10.000.001 – 100.000.000 / 25.000.001 – 50.000.000 | %0,0650 | %0,1250 | 32.000.000 | [CASH20 ile kayıt ol](https://okx.com/join/CASH20) |
| VIP 3 | 100.000.001 – 250.000.000 / 50.000.001 – 150.000.000 | %0,0300 | %0,1100 | 40.000.000 | [CASH20 ile kayıt ol](https://okx.com/join/CASH20) |
| VIP 4 | 250.000.001 – 1.000.000.000 / 150.000.001 – 300.000.000 | %0,0200 | %0,1000 | 48.000.000 | [CASH20 ile kayıt ol](https://okx.com/join/CASH20) |
| VIP 5 | 1.000.000.001 – 2.500.000.000 / 300.000.001 – 500.000.000 | %0,0100 | %0,0900 | 60.000.000 | [CASH20 ile kayıt ol](https://okx.com/join/CASH20) |
| VIP 6 | 2.500.000.001 – 5.000.000.000 / 500.000.001 – 1.000.000.000 | %0,0000 | %0,0800 | 72.000.000 | [CASH20 ile kayıt ol](https://okx.com/join/CASH20) |
| VIP 7 | 5.000.000.001 – 12.500.000.000 / 1.000.000.001 – 10.000.000.000 | -%0,0050 | %0,0600 | 80.000.000 | [CASH20 ile kayıt ol](https://okx.com/join/CASH20) |
| VIP 8 | 12.500.000.001 – 25.000.000.000 / 10.000.000.001 – 40.000.000.000 | -%0,0100 | %0,0500 | 80.000.000 | [CASH20 ile kayıt ol](https://okx.com/join/CASH20) |
| VIP 9 | 25.000.000.001+ / 40.000.000.001+ | -%0,0200 | %0,0400 | 80.000.000 | [CASH20 ile kayıt ol](https://okx.com/join/CASH20) |

Tablonun söylediği şey şu: Standart kullanıcıdan VIP 3'e geçmek maker ücretini üçte birine düşürür; VIP 6'da maker tamamen sıfırlanır; VIP 9'da maker negatif olur, yani her işlemde size iade yapılır. Bu yapı, düşük komisyonlu kripto borsası arayışında hacmin rolünü netleştirir: küçük hacimli kullanıcı için standart oranlar belirleyici olur, yüksek hacimli kullanıcı için ise kademe yükseltmek tek başına yeterli bir tasarruf aracıdır.

## Global OKX komisyon kademeleri (USD cinsinden)

Türkiye dışında ikamet edenler veya global OKX platformunu kullananlar için USD bazlı tablo farklıdır. Aşağıdaki oranlar OKX'in resmi ücret sayfasından alınmıştır ve spot piyasada geçerlidir.

| Kademe | Varlık (USD) veya 30 Günlük Hacim (USD) | Maker | Taker | 24s Çekme Limiti (USD) | Kayıt |
| --- | --- | --- | --- | --- | --- |
| Standart Kullanıcı | 0 – 100.000 / 0 – 100.000 | %0,2000 | %0,3500 | 10.000.000 | [CASH20 ile kayıt ol](https://okx.com/join/CASH20) |
| VIP 1 | 100.001 – 200.000 / 100.001 – 250.000 | %0,1000 | %0,2000 | 24.000.000 | [CASH20 ile kayıt ol](https://okx.com/join/CASH20) |
| VIP 2 | 200.001 – 2.000.000 / 250.001 – 500.000 | %0,0750 | %0,1500 | 32.000.000 | [CASH20 ile kayıt ol](https://okx.com/join/CASH20) |
| VIP 3 | 2.000.001 – 5.000.000 / 500.001 – 1.000.000 | %0,0600 | %0,1250 | 40.000.000 | [CASH20 ile kayıt ol](https://okx.com/join/CASH20) |
| VIP 4 | 5.000.001 – 20.000.000 / 1.000.001 – 2.500.000 | %0,0500 | %0,1000 | 48.000.000 | [CASH20 ile kayıt ol](https://okx.com/join/CASH20) |
| VIP 5 | 20.000.001 – 50.000.000 / 2.500.001 – 5.000.000 | %0,0450 | %0,0800 | 60.000.000 | [CASH20 ile kayıt ol](https://okx.com/join/CASH20) |
| VIP 6 | 50.000.001 – 100.000.000 / 5.000.001 – 50.000.000 | %0,0400 | %0,0700 | 72.000.000 | [CASH20 ile kayıt ol](https://okx.com/join/CASH20) |
| VIP 7 | 100.000.001 – 250.000.000 / 50.000.001 – 75.000.000 | -%0,0020 | %0,0250 | 80.000.000 | [CASH20 ile kayıt ol](https://okx.com/join/CASH20) |
| VIP 8 | 250.000.001 – 500.000.000 / 75.000.001 – 125.000.000 | -%0,0050 | %0,0200 | 80.000.000 | [CASH20 ile kayıt ol](https://okx.com/join/CASH20) |
| VIP 9 | 500.000.001+ / 125.000.001+ | -%0,0050 | %0,0150 | 80.000.000 | [CASH20 ile kayıt ol](https://okx.com/join/CASH20) |

Global standart kullanıcı için spot taker %0,35, bu Türkiye tablosundaki %0,22'den belirgin yüksek. Yani aynı borsanın farklı bölgesel altyapıları, yerel para birimi ve regülasyon koşullarına göre farklı ücretlendirme yapabiliyor. Türkiye'de işlem yapacaksanız OKX TR tablosu sizin için bağlayıcıdır.

## Futures komisyonları: Spotun yarısı seviyesinde

Vadeli işlem (futures) yapanlar için OKX'in USDT vadeli piyasasında standart oranlar maker %0,02, taker %0,05. Bu, spot standart oranların dörtte biri ile beşte biri arasında bir seviye. Aşağıdaki tablo, OKX'in yardım dokümanlarında yer alan futures ücret yapısını özetler; oranlar VIP kademesine göre düşer.

| İşlem Tipi | Standart Maker / Taker | VIP 1 Maker / Taker | VIP 5 Maker / Taker |
| --- | --- | --- | --- |
| USDT-M Futures | %0,020 / %0,050 | %0,015 / %0,030 | %0,004 / %0,010 |
| Coin-M Futures | %0,020 / %0,050 | %0,015 / %0,030 | %0,004 / %0,010 |
| Sürekli Swap (Perp) | %0,020 / %0,050 | %0,015 / %0,030 | %0,004 / %0,010 |

Vadeli işlemlerde taker %0,05 bile görünürde küçük bir rakam gibi durabilir, ama kaldıraç 10x iken bu oran, pozisyon büyüklüğünün %0,50'sine denk gelir. Yani futures işlemcileri için komisyon tasarrufu, spot işlemcilere göre çok daha belirgin hissedilir. VIP 5'e ulaşan bir futures işlemcisinin taker ücreti %0,01'in altına iner; bu, kaldıraçlı işlemlerde ciddi bir maliyet farkı yaratır.

> **İpucu:** Binance, Bybit, Bitget veya Gate.io'da zaten VIP statünüz varsa OKX bunu "deneme kademesi" olarak kabul eder; mevcut statünüzden 1-2 kademe yukarısı denenebilir. Bu, yeni borsaya geçişte sıfırdan başlama zorunluluğunu ortadan kaldırır.

## CASH20 davet kodu: %20 kalıcı komisyon iadesi

CASH20, OKX'in bağlı kuruluş (affiliate) programına bağlı bir referans kodu. Kayıt sırasında kullanıldığında iki şey birden sağlar: tüm işlem ücretlerinde %20 kalıcı iade ve hoş geldin bonusu paketi.

**İade nasıl çalışır:** Standart %0,10 taker ücreti ödediğinizde, bunun %0,02'si size geri döner. İade tek seferlik değil; hesabınız açık kaldığı sürece her işlemde uygulanır. Yüksek hacimli türev işlemcileri için bu, yıllık bazda ciddi bir tasarruf demek.

**Hoş geldin bonusu paketi:** CASH20 koduyla kayıt olan yeni kullanıcılara iki Gizemli Kutu verilebilir; her biri 50 USD'ye kadar kripto içerebilir. İlk kutu KYC doğrulaması sonrası, ikinci kutu ise ilk 14 günde 50 USD+ para yatırımı sonrası açılır. Toplam potansiyel 100 USD'ye kadar kripto + %20 kalıcı iade.

**Türkiye'ye özel:** Türkiye olarak kayıt olanlarda 250 TRY hoş geldin ödülü gibi TR özel kampanyaları da devreye girebilir; koşullar dönemsel olarak değişir.

Kodu kullanmanın en kolay yolu, kayıt öncesi 👉 [CASH20 ile kayıt ol](https://okx.com/join/CASH20) bağlantısına gitmek. Bağlantıya tıkladığınızda kod kayıt formuna otomatik işlenir; elle girmeniz gerekmez. Manuel kayıt açıyorsanız "Referral code (optional)" alanına CASH20 yazabilirsiniz.

> **Uyarı:** Referans kodları yalnızca ilk kayıt sırasında geçerlidir. Hesabınızı açtıktan sonra kodu sonradan ekleyemezsiniz; her kullanıcı için bir referans kodu hakkı bulunur.

## OKX TR'de TL yatırma ve çekme: Komisyon sıfır

Düşük komisyonlu kripto borsası arayışında sadece işlem komisyonu değil, para giriş-çıkış maliyeti de belirleyici. OKX TR, Türk Lirası yatırma ve çekme işlemlerini anlaşmalı bankalar üzerinden 7/24 ücretsiz yapar. Desteklenen bankalar arasında Vakıfbank, Ziraat Bankası, Fibabanka, Şekerbank ve Türkiye İş Bankası bulunur; Havale, FAST veya EFT ile işlem yapılabilir.

Kripto çekimlerinde ise ağ ücreti uygulanır; bu ücret, transfer yaptığınız blockchain ağının kendi işlem maliyetine bağlıdır ve OKX TR ek bir komisyon almaz. Yoğun dönemlerde bazı ağlarda bu maliyet artar; bu yüzden çekim yapmadan önce desteklenen ağlar arasında maliyet-hız dengesini kontrol etmek mantıklı.

## Güvenlik ve rezerv kanıtı

Komisyon kadar güvenlik de düşük maliyetli borsa seçiminde belirleyici. OKX, Kasım 2022'den beri düzenli Proof of Reserves (Rezerv Kanıtı) raporları yayınlar. Son raporlarda 22 yaygın varlık için %100'ün üzerinde rezerv oranı gösterilmiştir; bu, kullanıcı varlıklarının platform tarafından kullanılmadan tutulduğunun bağımsız denetimle doğrulanması anlamına gelir.

Diğer güvenlik önlemleri:

- **Çok faktörlü kimlik doğrulama:** Varsayılan olarak aktif.
- **Katmanlı işlem kontrolleri:** Büyük çekimler için ek onay mekanizmaları.
- **Anti-phishing kodu:** E-postaların gerçekten OKX'ten geldiğini teyit etmenizi sağlar.
- **Soğuk depolama:** Kullanıcı varlıklarının büyük kısmı çevrimdışı cüzdanlarda.

OKX ayrıca Avrupa Birliği'nin MiCA düzenlemesi kapsamında tam lisans almıştır; bu, AB genelinde düzenlenmiş kripto hizmetleri sunabileceği anlamına gelir. Türkiye tarafında ise OKX TR, SPK'nın "faaliyette bulunanlar listesi"nde yer alır.

## Diğer borsalarla hızlı karşılaştırma

Aşağıdaki tablo, düşük komisyonlu kripto borsası arayışında sık karşılaşılan rakiplerin standart spot oranlarını özetler. Veriler ilgili borsaların resmi ücret sayfalarından alınmıştır; dönemsel kampanyalar bu tabloya yansımaz.

| Borsa | Standart Spot Maker | Standart Spot Taker | TL Desteği | Notlar |
| --- | --- | --- | --- | --- |
| OKX TR | %0,08 | %0,10 | Var (ücretsiz) | SPK listesinde, TRY bazlı VIP kademeleri |
| Binance | %0,10 | %0,10 | Binance TR üzerinden | BNB ile %25 ek indirim |
| Bybit | %0,10 | %0,10 | Yok (P2P) | Futures tarafında rekabetçi |
| Bitget | %0,10 | %0,10 | Yok | Copy trading odaklı |
| Gate.io | %0,20 | %0,20 | Yok | Geniş coin çeşitliliği |

Bu tablo, OKX TR'nin standart spot maker oranında piyasa ortalamasının altında olduğunu gösterir. Taker tarafında Binance ve Bybit ile aynı seviyededir; ancak VIP kademeleri ve CASH20 iadesi birleştiğinde, hacimli kullanıcılar için toplam maliyet avantajı belirginleşir.

## Komisyon maliyetini düşürmenin pratik yolları

Kademeleri ve iadeyi bilmek, tek başına yeterli değil; bunları nasıl kullanacağınız da önemlidir. İşlem maliyetinizi düşürmek için uygulanabilir adımlar:

1. **Limit emir kullanın:** Emir defterine girip maker olarak eşleşen limit emirler, taker ücretinden daha düşük maker ücreti öder. Piyasa emri yerine limit emir, tek başına %30-50 arası tasarruf sağlar.
2. **CASH20 koduyla kayıt olun:** %20 kalıcı iade, tüm kademelerde geçerli. Kodu kayıt sırasında girmek, sonradan eklemenin mümkün olmadığı tek seferlik bir fırsattır.
3. **30 günlük hacminizi izleyin:** VIP kademeleri günlük güncellenir. Yakın bir eşi geçmek üzereyseniz, ay sonunda birkaç ekstra işlem yaparak bir sonraki kademeye atlamak uzun vadede tasarruf sağlar.
4. **Ağ seçimini kontrol edin:** Kripto çekimlerinde aynı varlık farklı ağlarda farklı ücretle çekilebilir. Örneğin USDT, TRC-20 ile ERC-20'den çok daha ucuz çekilir.
5. **BNB benzeri indirim token'larını değerlendirin:** Binance BNB ile %25 ek indirim sunar; OKX tarafında ise KCS benzeri bir token indirimi yoktur, ama VIP kademeleri ve CASH20 iadesi bu boşluğu doldurur.

## Sıkça sorulan sorular

**OKX TR ve global OKX aynı mı?** Hayır. OKX TR, Türkiye'de yasal olarak kayıtlı ayrı bir kuruluştur (OKX TR Kripto Varlık Alım Satım Platformu A.Ş.) ve bazı ürünlerle kampanyalar TR özelidir. Global OKX ise daha geniş ürün yelpazesi sunar. İkamet lkenize göre kayıt sırasında otomatik yönlendirme yapılır.

**CASH20 komisyon iadesi ne kadar sürer?** İade, ödeme yaptığınız işlemden sonra genellikle 7 günlük lock-up süresiyle hesabınıza yansır. Süre dolduktan sonra ödülü kullanabilir veya çekebilirsiniz. İadenin kendisi kalıcıdır; hesabınız açık kaldığı sürece her işlemde uygulanır.

**Referans kodunu sonradan ekleyebilir miyim?** Hayır. Referans kodları yalnızca ilk kayıt sırasında geçerlidir. Daha önce hesap açtıysanız, kodu sonradan ekleyemezsiniz; her kullanıcı için bir referans kodu hakkı vardır.

**VIP olmak için ne yapmalıyım?** VIP 1 için OKX TR'de 5.000.001 TRY varlık veya 5.000.001 TRY 30 günlük hacim gerekir. Platform günlük 16:00 UTC'de snapshot alıp 20:00-22:00 UTC arasında kademeleri günceller. 1.000 USD ve üzeri para yatırımı anında değerlendirmeye sebep olur.

**OKX TR'de TL yatırma ücretli mi?** Hayır. Türk Lirası yatırma ve çekme işlemleri anlaşmalı bankalar üzerinden 7/24 ücretsiz yapılır. Kripto çekimlerinde ise ağ ücreti uygulanır; bu ücret, transfer yaptığınız blockchain ağına bağlıdır.

**Gizemli Kutu ödülünü nakde çevirebilir miyim?** Kutu içeriği kripto olarak verilir. Ödül merkezi üzerinden açtığınızda hesabınıza yansır; isterseniz işlem yapabilir veya çekebilirsiniz.

## Sonuç: Düşük komisyonlu kripto borsası seçimi

Düşük komisyonlu kripto borsası seçimi, tek bir rakama indirgenemeyecek kadar çok değişkenli bir karar. Standart spot oranları, VIP kademeleri, futures ücret yapısı, para giriş-çıkış maliyeti ve güvenlik altyapısı birlikte değerlendirilmeli. OKX, standart spot maker %0,08 seviyesiyle piyasa ortalamasının altında başlar; VIP kademeleriyle bu oran negatife kadar iner; CASH20 kodu tüm bunların üstüne %20 kalıcı iade ekler. Türkiye'de ikamet edenler için OKX TR, SPK listesinde yer alması ve ücretsiz TL yatırma-çekme imkanıyla yerel kullanım kolaylığı sağlar.

Eğer düşük komisyonlu kripto borsası arayışınızda hem standart oranları hem de VIP yükseltme potansiyelini birlikte değerlendirmek istiyorsanız, 👉 [CASH20 koduyla OKX'e üye olun](https://okx.com/join/CASH20) bağlantısı tüm sürecin başlangıç noktası: tek tıklamayla %20 kalıcı komisyon iadesi ve hoş geldin bonusu paketi aynı anda aktive edilir. Hesabınızı açtıktan sonra tüm varlığınızı platformda tutmak yerine, yalnızca işlem yapacağınız miktarı bırakıp gerisini soğuk cüzdana taşımak, uzun vadeli güvenlik açısından mantıklı bir önlem.

_Yasal uyarı: Kripto varlıklar yüksek oynaklığa sahiptir ve anaparanızın tamamını kaybetme riski taşır. Bu yazı bilgilendirme amaçlıdır ve yatırım tavsiyesi içermez. Karar vermeden önce kendi araştırmanızı yapın ve yalnızca kaybetmeyi göze alabileceğiniz tutarlarla işlem yapın._
