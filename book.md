# ISTQB® CTFL® Türkçe Deneme Sınavı 1

## Sınav hakkında

Bu çalışma, Türkçe sınav rehberindeki deneme sorularının gözden geçirilmiş Türkçe sürümüdür. 40 soru, dört seçenek ve her soruda tek doğru cevap vardır. Her soru 1 puandır; geçme çizgisi 26/40 (%65), standart süre 60 dakikadır.

**Süreyi doğru seçin.** TTB'nin Türkçe/İngilizce kitapçığıyla sınava giren ana dili Türkçe aday için süre 60 dakikadır. Ana dili Türkçe olmayan aday için TTB 75 dakika belirtir. Ek süre sınav dili ve sağlayıcı koşullarına bağlıdır. Sınava kaydolmadan önce [TTB'nin güncel koşullarını](https://www.turkishtestingboard.org/kayit/foundation-level-certified-tester/) kontrol edin.

| Bilişsel seviye | Soru |
|---|---:|
| K1 — Hatırlama | 8 |
| K2 — Anlama | 24 |
| K3 — Uygulama | 8 |

| Bölüm | Soru |
|---|---:|
| 1 — Yazılım testinin temelleri | 8 |
| 2 — Yaşam döngüsü boyunca test | 6 |
| 3 — Statik test | 4 |
| 4 — Test analizi ve tasarımı | 11 |
| 5 — Test aktivitelerinin yönetimi | 9 |
| 6 — Test araçları | 2 |

### Nasıl kullanılır?

Gerçek sınav provası için 60 dakikalık, kesintisiz bir oturum ayırın. Ek süre hakkınız varsa 75 dakika seçin; 75 dakikayı bir çalışma süresi olarak da kullanabilirsiniz, ancak bunu 60 dakikalık prova sonucuyla aynı ölçüm saymayın. Sorular sınav provası için karışık sıradadır; bölüm başlıklarına göre gruplanmamıştır. Cevaplara bakmadan 40 soruyu tamamlayın, Part 2 ile puanlayın, ardından Part 3 ile yanlışların nedenlerini inceleyin.

Her soru için bir seçenek işaretleyin. Yanlış veya boş cevap 0 puandır; yanlışlar doğruları götürmez. K3 sorular için yaklaşık üçer dakika ayırmak bir çalışma önerisidir; bütün sınavın toplam süresini de gözetin.

### Dört tuzak

- **Kaynak bilgi eksiği:** Ders programındaki bir kavramı, tanımı veya listeyi hatırlayamama. İlgili bölümü yeniden çalışın.
- **Near-miss karışıklığı:** Komşu kavramları birbirinin yerine koyma; örneğin onaylama ve regresyon testi. Ayırt edici amaçlarını karşılaştırın.
- **Prosedür hatası:** Bir tekniği uygularken yanlış adım, varyant veya hesap kullanma. Çözümü adım adım yeniden kurun.
- **Dikkatsiz okuma:** Kökün yönlendirmesini veya verisini kaçırma. **EN İYİ** ve **DEĞİLDİR** gibi yön sözcüklerini kontrol edin.

Bu dört etiket sorunun genel tuzağını gösterir. Kılavuzdaki çeldirici adları ise tek bir yanlış seçeneğin neden cazip olduğunu açıklar; iki sınıflandırma farklı amaçlara hizmet eder.

**Bağımsızlık ve lisans.** ISTQB® ve CTFL® tescilli markalardır. Bu çalışma ISTQB veya TTB tarafından onaylanmamıştır ve bu kuruluşların resmî sınavı değildir. © 2026 Kadir Çamoğlu. Özgün içerik [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) ile paylaşılır; ISTQB'ye ait alıntılar, LO kodları, ilke adları ve markalar bu lisansın dışındadır.


## Part 1 — Sorular

Cevap anahtarını açmadan önce bütün soruları tamamlayın.

### S1–S10

<!-- META
no: 1
kilavuz_no: 1
bolum: 1
lo: FL-1.1.1
k: K1
tip: concept
dogru: b
tuzak: Near-miss karışıklığı
degisiklik: duzeltme
-->

**Soru 1** (1 puan)

Bir ürün sahibi (product owner), geciken bir özelliğin bir sonraki sürüme alınıp alınmayacağına karar verecektir. Test uzmanlarından bulunan hataların (defect) ve kalan risklerin bir özetini ister. Bu istek hangi tipik test hedefine (test objective) hizmet eder?

a) Test nesnesinin (test object) sözleşme ve mevzuat gereksinimlerini karşıladığını doğrulamak (verification)
b) Paydaşlara sürüm hakkında bilinçli karar verebilmeleri için bilgi sağlamak
c) Sağlama (validation) yoluyla test nesnesinin paydaş beklentilerini karşılayıp karşılamadığını kontrol etmek
d) Planlanan test kapsamına (test coverage) ulaşmak için gerekli testleri koşmak

<!-- META
no: 2
kilavuz_no: 9
bolum: 2
lo: FL-2.1.1
k: K2
tip: comparison
dogru: a
tuzak: Near-miss karışıklığı
degisiklik: duzeltme
-->

**Soru 2** (1 puan)

Bir proje, sıralı geliştirme modelinden (sequential development model) iki haftalık döngüsel geliştirme modeline (iterative development model) geçer. Bu değişikliğin test üzerindeki etkisini hangi ifade **EN İYİ** açıklar?

a) Yeni artımlar teslim edildikçe test aktiviteleri her döngüde tekrarlanır.
b) Biriken değişiklikler için regresyon testi (regression testing) son döngüye ertelenir.
c) Sistem testi (system testing), artımlar küçüldüğü için tek tek bileşenlerin doğrulanmasına odaklanır.
d) Test seviyelerinin (test level) farklı hedefleri, kısa döngüler için tek bir ortak hedefle değiştirilir.

<!-- META
no: 3
kilavuz_no: 19
bolum: 4
lo: FL-4.1.1
k: K2
tip: comparison
dogru: c
tuzak: Near-miss karışıklığı
degisiklik: yok
-->

**Soru 3** (1 puan)

Bir test uzmanı, kodu bilmeden, spesifikasyondaki durum diyagramından (state diagram) test senaryoları (test case) türetir. Başka bir test uzmanı, kaynak koddaki dal kapsamı (branch coverage) boşluklarını analiz ederek ek testler tasarlar. Kara kutu (black-box), beyaz kutu (white-box) ve tecrübeye dayalı (experience-based) test teknikleri açısından bu iki yaklaşım nasıl sınıflandırılır?

a) İkisi de beyaz kutu test tekniğidir.
b) Birincisi tecrübeye dayalı, ikincisi kara kutudur.
c) Birincisi kara kutu, ikincisi beyaz kutudur.
d) Birincisi beyaz kutu, ikincisi tecrübeye dayalıdır.

<!-- META
no: 4
kilavuz_no: 30
bolum: 5
lo: FL-5.1.3
k: K2
tip: comparison
dogru: b
tuzak: Near-miss karışıklığı
degisiklik: duzeltme
-->

**Soru 4** (1 puan)

Bir bordro sürümü için sistem testini (system testing) planlayan test yöneticisi iki liste hazırlar:

- Liste 1: Sistem testine başlanabilmesi için 500 çalışanlık test verisi (test data) hazır olmalı ve sistem testi senaryoları (test case) gözden geçirilmiş olmalıdır.
- Liste 2: Sistem testinin tamamlanmış sayılması için bu seviyede ölçülen vergi modülü dal kapsamı (branch coverage) en az %85 olmalı ve açık kritik hata (defect) kalmamalıdır.

Bu listelerle ilgili hangi ifade **DOĞRUDUR**?

a) Liste 1 çıkış kriterlerini (exit criteria), Liste 2 giriş kriterlerini (entry criteria) tanımlar.
b) Liste 1 giriş kriterlerini, Liste 2 çıkış kriterlerini tanımlar.
c) İki liste de test başlamadan yazıldığı için giriş kriterlerini tanımlar.
d) İki liste de sürümün karşılaması gereken koşullar olduğu için kabul kriterlerini (acceptance criteria) tanımlar.

<!-- META
no: 5
kilavuz_no: 15
bolum: 3
lo: FL-3.1.1
k: K1
tip: concept
dogru: d
tuzak: Near-miss karışıklığı
degisiklik: duzeltme
-->

**Soru 5** (1 puan)

Bir test yöneticisi statik testi (static testing), kaynak kodun ve gereksinim spesifikasyonlarının (requirement specification) ötesine taşımak istiyor. Ekip aşağıdakilerden hangisini statik testle inceleyebilir?

a) Devreye alınmış ödeme hizmetinin yoğun yük altındaki yanıt sürelerini
b) Mobil uygulamanın uzun bir kullanıcı oturumu boyunca bellek tüketimini
c) Ağ bağlantısı koptuğunda ödeme ekranının çalışma anındaki davranışını
d) Tedarikçi sözleşmesini ve test başlatma belgelerini (test charter)

<!-- META
no: 6
kilavuz_no: 20
bolum: 4
lo: FL-4.2.1
k: K3
tip: calculation
dogru: d
tuzak: Prosedür hatası
degisiklik: duzeltme
-->

**Soru 6** (1 puan)

Bir çevrim içi bilet gişesinde sipariş edilen bilet miktarı tam sayı olarak girilir. Sistem sipariş başına 1 ile 100 arasında bilet kabul eder:

- 1–9 bilet standart fiyattan ücretlendirilir.
- 10–49 bilet için %10 indirim uygulanır.
- 50–100 bilet için %20 indirim uygulanır.
- 1'in altındaki miktarlar “Sipariş çok küçük” hata mesajıyla reddedilir.
- 100'ün üstündeki miktarlar “Sipariş sınırı aşıldı” hata mesajıyla reddedilir.

Bilet miktarına denklik paylarına ayırma (equivalence partitioning) uygulandığında, geçerli ve geçersiz toplam kaç denklik payı (equivalence partition) belirlenmelidir?

a) 3
b) 4
c) 6
d) 5

<!-- META
no: 7
kilavuz_no: 2
bolum: 1
lo: FL-1.2.3
k: K2
tip: comparison
dogru: c
tuzak: Near-miss karışıklığı
degisiklik: duzeltme
-->

**Soru 7** (1 puan)

Bir uçuş rezervasyon şirketi, yeni bir geliştiriciye kalkış saatlerinin Eşgüdümlü Evrensel Zaman (UTC) olarak saklandığını söylemez. Geliştirici saatlerin yerel saat olduğunu varsayar ve onları dönüştürmeden saklayan kodu yazar. Sürümden bir hafta sonra bir yolcunun biniş hatırlatması, uçuş kalktıktan bir saat sonra gelir.

İnsan hatası (error), hata (defect), arıza (failure) ve kök neden (root cause) ayrımına göre hangi ifade **DOĞRUDUR**?

a) Eksik bilgilendirme insan hatasıdır; yerel saatleri saklayan kod ise arızadır.
b) Geliştiricinin yanlış varsayımı kök nedendir; saklanan yerel saatler ise arızadır.
c) Yanlış varsayım insan hatasıdır; geç gelen biniş hatırlatması ise arızadır.
d) Yerel saatleri saklayan kod kök nedendir; eksik bilgilendirme ise hatadır.

<!-- META
no: 8
kilavuz_no: 10
bolum: 2
lo: FL-2.1.2
k: K1
tip: concept
dogru: c
tuzak: Near-miss karışıklığı
degisiklik: duzeltme
-->

**Soru 8** (1 puan)

Hibrit bir projede test uzmanları, kullanıcı hikâyelerini (user story) ancak kod tamamlanıp hikâyeler “teste hazır” olarak işaretlendiğinde alır. Bu yüzden hikâyelerdeki hatalar (defect) geç bulunur. Her yazılım geliştirme yaşam döngüsünde (software development lifecycle) geçerli olan hangi iyi test uygulaması bu sorunu **EN İYİ** şekilde giderir?

a) Her test seviyesine (test level), diğer seviyelerin hedeflerinden farklı hedefler atamak
b) Test koşumuna (test execution), kodun planlanan bütün özellikleri tamamlandığında başlamak
c) Hikâye taslakları hazır olduğunda gözden geçirmeye (review) katılmak
d) Hikâyelerin kabul kriterlerini (acceptance criteria), iş temsilcilerinin yerine test uzmanlarına yazdırmak

<!-- META
no: 9
kilavuz_no: 31
bolum: 5
lo: FL-5.1.6
k: K1
tip: concept
dogru: d
tuzak: Kaynak bilgi eksiği
degisiklik: duzeltme
-->

**Soru 9** (1 puan)

İki ekip test piramitlerini (test pyramid) farklı çizer. Bir ekip katmanları birim testleri (unit testing), servis testleri (service testing) ve kullanıcı arayüzü testleri (UI testing) olarak adlandırır. Diğeri bileşen testleri (component testing), entegrasyon testleri (integration testing) ve uçtan uca testler (end-to-end testing) adlarını kullanır. Test piramidi hakkında hangi ifade **DOĞRUDUR**?

a) İlk çizim geçerlidir; piramit, adları birim, servis ve kullanıcı arayüzü olan üç katmanla tanımlanır.
b) İki çizimde de üst katmanlara çıkıldıkça test yalıtımı (test isolation) artar.
c) Katman adları farklılaşsa da model, her katmanda kullanılacak test tekniğini (test technique) belirler.
d) Katmanların sayısı ve adları değişebilir; iki çizim de geçerli olabilir.

<!-- META
no: 10
kilavuz_no: 24
bolum: 4
lo: FL-4.3.1
k: K2
tip: concept
dogru: d
tuzak: Near-miss karışıklığı
degisiklik: duzeltme
-->

**Soru 10** (1 puan)

Bir regresyon testi (regression testing) koşumunun ardından döviz çevirme bileşeninin komut kapsamı (statement coverage) %92 olarak raporlanır. Hiç çalıştırılmamış üç komut, döviz kuru hizmetine ulaşılamadığı durumu ele alan bloktadır. Koşulan bütün testler geçmiştir. Bu bilgilerden hangi sonuç çıkarılabilir?

a) Bu üç komut testlerde çalıştırılmadığı için ölü koddur (dead code) ve bileşenden kaldırılabilir.
b) Komut kapsamıyla aynı koddan ölçüldüğü için bileşenin dal kapsamı (branch coverage) da %92'dir.
c) Testlerin geçmesi, döviz kuru hizmetine ulaşılamadığında hata ele alma bloğunun doğru çalıştığını gösterir.
d) Bu üç komutu kapsamak için hizmete ulaşılamayan durum test edilmelidir.


### S11–S20

<!-- META
no: 11
kilavuz_no: 3
bolum: 1
lo: FL-1.3.1
k: K2
tip: concept
dogru: d
tuzak: Near-miss karışıklığı
degisiklik: duzeltme
-->

**Soru 11** (1 puan)

Bir sürümde, kod yazılmadan önce bir kullanıcı hikâyesindeki (user story) çelişki gözden geçirmede (review) bulunur ve on dakikada düzeltilir. Sonraki sürümde benzer bir çelişki gözden kaçar; tasarıma, koda ve test senaryolarına (test case) yayılır. Canlı ortamda bulunan bu hata (defect), bütün bu iş ürünlerinin (work product) değiştirilmesini ve acil yama hazırlanmasını gerektirir. Bu karşılaştırmayı hangi test prensibi (testing principle) **EN İYİ** açıklar?

a) Hatalar yazılımın belli alanlarında yoğunlaşır (defects cluster together).
b) Testler hataların varlığını gösterir; yokluğunu kanıtlamaz (testing shows the presence, not the absence of defects).
c) Hatasızlık yanılgısı (absence-of-defects fallacy): hata bulamamak, ürünün ihtiyaca uygun olduğunu göstermez.
d) Erken test, zaman ve para tasarrufu sağlar (early testing saves time and money).

<!-- META
no: 12
kilavuz_no: 11
bolum: 2
lo: FL-2.1.3
k: K1
tip: concept
dogru: b
tuzak: Kaynak bilgi eksiği
degisiklik: duzeltme
-->

**Soru 12** (1 puan)

Önce test yaklaşımları (test-first approaches) arasında test güdümlü yazılım geliştirme (test-driven development, TDD), kabul testi güdümlü yazılım geliştirme (acceptance test-driven development, ATDD) ve davranış güdümlü yazılım geliştirme (behavior-driven development, BDD) bulunur. Bu yaklaşımlar hakkında hangi ifade **DOĞRUDUR**?

a) ATDD testleri, ilgili bileşen tamamlandıktan sonra kaynak kodun yapısından türetilir.
b) Üç yaklaşımda da testler sonraki değişiklikler için otomatik testler olarak korunabilir.
c) BDD testleri, paydaş görüşmeleri yerine geliştiricilerin seçtiği kod yapısından türetilir.
d) TDD testlerini iş temsilcileri kullanıcı hikâyelerinin kabul kriterlerinden (acceptance criteria) türetir.

<!-- META
no: 13
kilavuz_no: 21
bolum: 4
lo: FL-4.2.2
k: K3
tip: calculation
dogru: a
tuzak: Prosedür hatası
degisiklik: yok
-->

**Soru 13** (1 puan)

Bir kayıt formu 8 ile 20 karakter uzunluğundaki parolaları kabul eder; bu aralığın dışındaki uzunlukları reddeder. Parola uzunluğuna **2 değerli** sınır değer analizi (2-value boundary value analysis) uygulandığında kaç farklı uzunluk değeri test edilmelidir?

a) 4
b) 2
c) 6
d) 8

<!-- META
no: 14
kilavuz_no: 32
bolum: 5
lo: FL-5.1.7
k: K2
tip: comparison
dogru: a
tuzak: Near-miss karışıklığı
degisiklik: duzeltme
-->

**Soru 14** (1 puan)

Bir ekip testlerini test çeyreklerine (testing quadrants) yerleştiriyor. Aşağıdaki yerleştirmelerden hangisi **DOĞRUDUR**?

a) Oturum açma hizmetinin güvenlik testleri (security testing): Q4, teknolojiye dönük ve ürünü eleştiren.
b) Gerçek kullanıcılarla kullanılabilirlik testleri (usability testing): Q4, teknolojiye dönük ve ürünü eleştiren.
c) Sürekli entegrasyondaki (continuous integration) bileşen entegrasyon testleri (component integration testing): Q3, işe dönük ve ürünü eleştiren.
d) Keşif testi (exploratory testing) oturumları: Q2, işe dönük ve ekibi destekleyen.

<!-- META
no: 15
kilavuz_no: 17
bolum: 3
lo: FL-3.2.3
k: K1
tip: concept
dogru: a
tuzak: Near-miss karışıklığı
degisiklik: yok
-->

**Soru 15** (1 puan)

Bir veri taşıma spesifikasyonunun gözden geçirmesinde (review), katılımcılar on bir hata (defect) saptandığı konusunda uzlaşır. Spesifikasyondaki bu hataları düzeltmekten hangi rol sorumludur?

a) Yazar (author)
b) Gözden geçirme lideri (review leader)
c) Katip (scribe)
d) Moderatör (moderator)

<!-- META
no: 16
kilavuz_no: 25
bolum: 4
lo: FL-4.3.3
k: K2
tip: comparison
dogru: b
tuzak: Near-miss karışıklığı
degisiklik: duzeltme
-->

**Soru 16** (1 puan)

Beyaz kutu testi (white-box testing), kara kutu testine (black-box testing) göre hangi güçlü yönü sağlar?

a) Koddaki kontrol akışını inceleyerek paydaşların bütün iş ihtiyaçlarının karşılandığını doğrular.
b) Spesifikasyonda belirtilmeyen gerçekleştirim kısımları için kapsam sağlar.
c) Testleri gereksinimlerden türeterek gerçekleştirimden bağımsız iş davranışı kapsamı sağlar.
d) Spesifikasyondaki her gereksinimin gerçekleştirimde bulunmasını kod kapsamı ölçümüyle güvenceye alır.

<!-- META
no: 17
kilavuz_no: 4
bolum: 1
lo: FL-1.4.1
k: K2
tip: concept
dogru: d
tuzak: Near-miss karışıklığı
degisiklik: yok
-->

**Soru 17** (1 puan)

Bir test uzmanı, sadakat puanı özelliğinin önceliklendirilmiş test koşullarını (test condition) test senaryolarına (test case) dönüştürür ve kapsam öğelerini (coverage item) belirler. Gerekli test verisini (test data) ve test ortamının (test environment) sağlaması gereken özellikleri de tanımlar. Hangi test aktivitesini (test activity) yürütmektedir?

a) Test analizi (test analysis)
b) Test uyarlama (test implementation)
c) Test planlama (test planning)
d) Test tasarımı (test design)

<!-- META
no: 18
kilavuz_no: 33
bolum: 5
lo: FL-5.2.4
k: K2
tip: concept
dogru: d
tuzak: Near-miss karışıklığı
degisiklik: yok
-->

**Soru 18** (1 puan)

Risk analizi (risk analysis), yeni ödeme sağlayıcısı entegrasyonunu ilk yoğun satış hafta sonu için yüksek ürün riski (product risk) olarak değerlendirir. Ekip, testlere ek olarak, entegrasyon canlı ortamda başarısız olursa bütün ödemeleri 15 dakika içinde önceki sağlayıcıya döndürecek bir prosedür hazırlar ve prova eder. Bu prosedür neyi temsil eder?

a) Risk kabulü (risk acceptance)
b) Risk transferi (risk transfer)
c) Test yoluyla risk azaltma (risk mitigation)
d) Acil durum planı (contingency plan)

<!-- META
no: 19
kilavuz_no: 22
bolum: 4
lo: FL-4.2.3
k: K3
tip: calculation
dogru: b
tuzak: Prosedür hatası
degisiklik: duzeltme
-->

**Soru 19** (1 puan)

Bir araç kiralama fiyat kuralı üç koşula bağlıdır:

- Sürücünün yaş grubu: 25 yaş altı, 25–69 veya 70 ve üstü.
- Sadakat kartı: var veya yok.
- Havalimanından teslim alma: evet veya hayır.

Ekip genişletilmiş giriş karar tablosunu (extended-entry decision table), hiçbir sütunu çıkarmadan veya birleştirmeden oluşturacaktır. Tam tablo kaç sütun içerir?

a) 18
b) 12
c) 24
d) 6

<!-- META
no: 20
kilavuz_no: 39
bolum: 6
lo: FL-6.1.1
k: K2
tip: concept
dogru: b
tuzak: Near-miss karışıklığı
degisiklik: duzeltme
-->

**Soru 20** (1 puan)

Bir araç her kod değişikliği kaydında otomatik test gruplarını (test suite) koşar, sonuçlarını toplar ve kodun ne kadarının çalıştırıldığını ölçer. Ana işlevine göre hangi araç kategorisine girer?

a) Test yönetimi araçları (test management tools)
b) Test koşumu ve kapsam araçları (test execution and test coverage tools)
c) Statik test araçları (static testing tools)
d) Test tasarımı ve test uyarlama araçları (test design and test implementation tools)


### S21–S30

<!-- META
no: 21
kilavuz_no: 5
bolum: 1
lo: FL-1.4.3
k: K2
tip: concept
dogru: b
tuzak: Near-miss karışıklığı
degisiklik: yok
-->

**Soru 21** (1 puan)

Bir test uzmanı, kullanıcı hikâyesinden (user story) test koşulları (test condition) türetirken iki kabul kriterinin (acceptance criteria) çeliştiğini fark eder. Ürün sahibi hikâyeyi hemen düzeltemediği için test uzmanı bir hata raporu (defect report) oluşturur. Bu rapor hangi test aktivitesinin (test activity) iş ürünü (work product) olarak ortaya çıkar?

a) Test koşumu (test execution)
b) Test analizi (test analysis)
c) Test tasarımı (test design)
d) Test tamamlama (test completion)

<!-- META
no: 22
kilavuz_no: 12
bolum: 2
lo: FL-2.1.5
k: K2
tip: concept
dogru: d
tuzak: Near-miss karışıklığı
degisiklik: yok
-->

**Soru 22** (1 puan)

Bir mobil bankacılık ekibi, eksiksiz sistemin temsili ortamda hazır olmasını beklemek yerine her bileşen geliştirilir geliştirilmez performans testleri (performance testing) ve güvenlik testleri (security testing) koşar. Bu uygulamayı hangi kavram **EN İYİ** açıklar?

a) Test güdümlü yazılım geliştirme (test-driven development)
b) Onaylama testi (confirmation testing)
c) Risk bazlı test (risk-based testing)
d) Sola alma (shift left)

<!-- META
no: 23
kilavuz_no: 23
bolum: 4
lo: FL-4.2.4
k: K3
tip: application
dogru: c
tuzak: Prosedür hatası
degisiklik: duzeltme
-->

**Soru 23** (1 puan)

Bir medya oynatıcının yalnız aşağıdaki durum geçişleri (state transition) tanımlıdır; listede bulunmayan geçişler geçersizdir:

| Kaynak durum | Olay | Hedef durum |
|---|---|---|
| Boşta | başlat | Oynatılıyor |
| Oynatılıyor | duraklat | Duraklatıldı |
| Duraklatıldı | sürdür | Oynatılıyor |
| Oynatılıyor | durdur | Durduruldu |
| Duraklatıldı | durdur | Durduruldu |

Oynatıcı Boşta durumunda başlar. Hangi olay dizisi geçerli bir test senaryosudur (test case)?

a) başlat, sürdür, durdur
b) başlat, duraklat, duraklat, durdur
c) başlat, duraklat, sürdür, durdur
d) başlat, durdur, sürdür

<!-- META
no: 24
kilavuz_no: 34
bolum: 5
lo: FL-5.1.4
k: K3
tip: calculation
dogru: b
tuzak: Prosedür hatası
degisiklik: yok
-->

**Soru 24** (1 puan)

Benzer bir önceki projede geliştirme eforunun test eforuna oranı 4:3'tür. Yeni projenin geliştirme eforu 720 kişi-gün olarak tahmin edilmektedir. Oranlara dayalı tahminleme (estimation based on ratios) ile tahmini test eforu kaç kişi-gündür?

a) 180 kişi-gün
b) 540 kişi-gün
c) 960 kişi-gün
d) 1.260 kişi-gün

<!-- META
no: 25
kilavuz_no: 16
bolum: 3
lo: FL-3.1.3
k: K2
tip: comparison
dogru: b
tuzak: Near-miss karışıklığı
degisiklik: duzeltme
-->

**Soru 25** (1 puan)

Statik test (static testing) ve dinamik test (dynamic testing) arasındaki farklar hakkında hangi ifade **DOĞRUDUR**?

a) Dinamik test, gereksinim spesifikasyonları gibi çalıştırılamayan iş ürünlerini (work product) değerlendirebilir.
b) Statik test, kodun çalıştırılmasına bağlı olmayan sürdürülebilirlik (maintainability) gibi özellikleri değerlendirebilir.
c) Statik test, yük altında çalışan hizmetin yanıt sürelerini ölçerek performans verimliliğini (performance efficiency) değerlendirir.
d) Dinamik test, bir kabul kriteri için eksik test gibi test esası (test basis) kapsam boşluklarını statik testten daha kolay bulur.

<!-- META
no: 26
kilavuz_no: 26
bolum: 4
lo: FL-4.4.1
k: K2
tip: concept
dogru: b
tuzak: Near-miss karışıklığı
degisiklik: yok
-->

**Soru 26** (1 puan)

Bir bordro test uzmanı, önceki sürümlerde ay ortasında işe başlayan çalışanlar ve sıfır saat kaydı olan çalışanlar için arızalar (failure) yaşandığını hatırlar. Yeni fazla mesai özelliğinde bu geçmiş arızalara dayanarak aynı tür çalışanlarla testler tasarlar. Hangi tekniği kullanmaktadır?

a) Keşif testi (exploratory testing)
b) Hata tahminleme (error guessing)
c) Kontrol listesine dayalı test etme (checklist-based testing)
d) Sınır değer analizi (boundary value analysis)

<!-- META
no: 27
kilavuz_no: 6
bolum: 1
lo: FL-1.4.4
k: K2
tip: concept
dogru: a
tuzak: Near-miss karışıklığı
degisiklik: duzeltme
-->

**Soru 27** (1 puan)

Bir denetçi, sürümdeki her gereksinimin en az bir koşulmuş testle kapsandığını gösteren kanıt ister. Test çalışma ürünlerinin (testware) hangi özelliği bu kanıtın verimli biçimde hazırlanmasını sağlar?

a) Test esası (test basis) ile test çalışma ürünleri arasındaki izlenebilirlik (traceability)
b) Test ekibinin geliştirme ekibinden ayrı çalışmasını sağlayan test bağımsızlığı (independence of testing)
c) Regresyon testi (regression testing) grubunun kısa sürede koşulmasını sağlayan test otomasyonu (test automation)
d) Test seviyelerinin (test level) başlaması için gereken kaynakları belirleyen giriş kriterleri (entry criteria)

<!-- META
no: 28
kilavuz_no: 13
bolum: 2
lo: FL-2.2.1
k: K2
tip: concept
dogru: a
tuzak: Near-miss karışıklığı
degisiklik: yok
-->

**Soru 28** (1 puan)

Bir hastanenin randevu sistemi canlıya alınmadan önce BT operasyon ekibi, canlıya benzer ortamda yedekleme, geri yükleme, felaket kurtarma ve kullanıcı hesabı yönetimini test eder. Amaç, ekibin sistemi canlı ortamda işletebileceğini ve sistemin dağıtıma hazır olduğunu değerlendirmektir. Bu hangi test seviyesidir (test level)?

a) Kabul testi (acceptance testing)
b) Sistem testi (system testing)
c) Sistem entegrasyon testi (system integration testing)
d) Bileşen entegrasyon testi (component integration testing)

<!-- META
no: 29
kilavuz_no: 35
bolum: 5
lo: FL-5.1.5
k: K3
tip: calculation
dogru: d
tuzak: Prosedür hatası
degisiklik: yok
-->

**Soru 29** (1 puan)

Bir bileşenin S1–S10 adlı on çalıştırılabilir komutu (executable statement) vardır. Ekip, aşağıdaki test senaryolarını (test case) **ek kapsama dayalı önceliklendirme** (additional coverage prioritization) ile sıralayacaktır:

| Test senaryosu | Çalıştırılan komutlar |
|---|---|
| TC1 | S1, S2, S3, S4, S5, S6 |
| TC2 | S1, S2, S3, S4, S5 |
| TC3 | S7, S8, S9 |
| TC4 | S6, S10 |

Hangi koşum sırası **DOĞRUDUR**?

a) TC1, TC2, TC3, TC4
b) TC1, TC3, TC2, TC4
c) TC4, TC3, TC2, TC1
d) TC1, TC3, TC4, TC2

<!-- META
no: 30
kilavuz_no: 27
bolum: 4
lo: FL-4.4.3
k: K2
tip: concept
dogru: c
tuzak: Near-miss karışıklığı
degisiklik: duzeltme
-->

**Soru 30** (1 puan)

Kontrol listesine dayalı test etme (checklist-based testing) hakkında hangi ifade **DOĞRUDUR**?

a) Kontrol listesi, tutarlılık sağlamak için her kontrolün ayrıntılı koşum adımlarını tanımlar.
b) Bir sürümde başarıyla geçen kontrol maddeleri, sonraki sürümde listeden çıkarılarak liste güncellenir.
c) Ayrıntılı test senaryoları (test case) yoksa kontrol listesi yol gösterebilir ve tutarlılık sağlar.
d) Kontrol listesi maddeleri, kodun dallarından (branch) türetildiği için beyaz kutu kapsamı ölçüsüdür.


### S31–S40

<!-- META
no: 31
kilavuz_no: 7
bolum: 1
lo: FL-1.5.2
k: K1
tip: concept
dogru: c
tuzak: Kaynak bilgi eksiği
degisiklik: duzeltme
-->

**Soru 31** (1 puan)

Bir departman yöneticisi, tüm ekip yaklaşımının (whole team approach) sağlayacağı bir avantajı sorar. Aşağıdaki yanıtlardan hangisi bu yaklaşımın avantajını belirtir?

a) Uzmanların diğer ekip aktivitelerine katılmadan kendi görevlerinde uzmanlaşmasını sağlar.
b) Harici test ekipleriyle yüksek test bağımsızlığı (independence of testing) düzeyini sağlar.
c) Ekipteki farklı bilgi ve becerilerin projenin yararına kullanılmasını sağlar.
d) Ürün kalitesinin sorumluluğunu geliştiricilerden ayrı çalışan bir kalite ekibine devreder.

<!-- META
no: 32
kilavuz_no: 14
bolum: 2
lo: FL-2.2.3
k: K2
tip: comparison
dogru: b
tuzak: Near-miss karışıklığı
degisiklik: duzeltme
-->

**Soru 32** (1 puan)

Bir otel uygulamasında ay sonunu aşan konaklamalar için gece sayısı yanlış hesaplanmaktadır. Düzeltmeden sonra test uzmanı arızayı (failure) ortaya çıkaran 30 Nisan–2 Mayıs testini tekrarlar. Ardından ödeme, sadakat puanı ve iptal için önceki koşumlarda geçen otomatik test gruplarını (test suite) yeni sürüm üzerinde yeniden koşar. Onaylama testi (confirmation testing) ve regresyon testi (regression testing) açısından bu iki aktiviteyi hangi ifade **EN İYİ** açıklar?

a) İlk aktivite değişen hesaplamanın yan etkilerini, ikinci aktivite de diğer özelliklerdeki yan etkileri arar.
b) İlk aktivite hatanın (defect) giderildiğini kontrol eder; ikinci aktivite değişikliğin olumsuz etkilerini arar.
c) İlk aktivite hatanın giderildiğini kontrol eder; ikinci aktivite dokunulmayan alanlarda sonuçları belgeleyen bir formalitedir.
d) İlk aktivite kullanıcı ihtiyaçlarına uygunluğu değerlendirir; ikinci aktivite uygulamanın test kapsamını (test coverage) ölçer.

<!-- META
no: 33
kilavuz_no: 28
bolum: 4
lo: FL-4.5.2
k: K2
tip: comparison
dogru: c
tuzak: Near-miss karışıklığı
degisiklik: duzeltme
-->

**Soru 33** (1 puan)

Kargo ücretine ilişkin kabul kriterleri (acceptance criteria) aşağıdaki gibi yazılmıştır:

| Üyelik | Sipariş toplamı | Kargo ücreti |
|---|---|---|
| Standart | 50'nin altında | 4,99 |
| Standart | 50 veya üstü | 0,00 |
| Altın | Herhangi bir tutar | 0,00 |

Bu tablo hangi kabul kriteri yazma biçimini örnekler?

a) Senaryo odaklı (scenario-oriented): her satır, bir olayın ardından gerçekleşen sonucu anlatır.
b) Yapı odaklı: satırlar, kargo hesaplayan kodun dallarını ve bu dalların çalıştırılma sırasını anlatır.
c) Kural odaklı (rule-oriented): koşullar ile beklenen ücret arasındaki eşlemeyi belirtir.
d) Senaryo odaklı: tablodaki satır sırası, bir müşterinin ardışık siparişlerde izleyeceği işlem adımlarını belirtir.

<!-- META
no: 34
kilavuz_no: 36
bolum: 5
lo: FL-5.3.2
k: K2
tip: concept
dogru: a
tuzak: Near-miss karışıklığı
degisiklik: duzeltme
-->

**Soru 34** (1 puan)

Sistem testi (system testing) sürerken haftalık test ilerleme raporu (test progress report), planlanan testlerin %30'unun kararsız test ortamı (test environment) nedeniyle engellendiğini gösterir. Bu bilginin raporlanmasının temel amacı nedir?

a) Test takviminin, kaynakların veya test planının (test plan) ayarlanmasına bilgi sağlamak.
b) Test bittikten sonra kullanılacak alınan dersler listesini, süreç iyileştirmesine girdi olarak tamamlamak.
c) Ortama ait hata raporlarının (defect report) yerine geçecek ayrıntılı yeniden üretme adımlarını belgelemek.
d) Ürün kalitesinin çıkış kriterlerine (exit criteria) göre son değerlendirmesini tamamlayıp testi kapatmak.

<!-- META
no: 35
kilavuz_no: 18
bolum: 3
lo: FL-3.2.4
k: K2
tip: comparison
dogru: b
tuzak: Near-miss karışıklığı
degisiklik: duzeltme
-->

**Soru 35** (1 puan)

Bir ekip, demiryolu sinyalizasyon tasarımı için genel gözden geçirme sürecinin (review process) tamamını izler. Katılımcılar bireysel hazırlanır; bulunan anomali (anomaly) sayısı ve hazırlık süresi gibi metrikler süreç iyileştirmede kullanılır. Yazar katılır ancak gözden geçirme lideri veya katip olamaz. Temel amaç olabildiğince çok anomali bulmaktır. Bu hangi gözden geçirme çeşididir?

a) Teknik gözden geçirme (technical review)
b) Teftiş (inspection)
c) Üzerinden geçme (walkthrough)
d) Gayri resmi gözden geçirme (informal review)

<!-- META
no: 36
kilavuz_no: 29
bolum: 4
lo: FL-4.5.3
k: K3
tip: application
dogru: a
tuzak: Prosedür hatası
degisiklik: duzeltme
-->

**Soru 36** (1 puan)

Bir kullanıcı hikâyesi (user story), uygun siparişlerde ücretsiz kargo ister. Kabul kriteri (acceptance criteria) şöyledir: “Üyelerin verdiği 500'ün üzerindeki siparişlerde kargo ücretsizdir.” Kabul testi güdümlü yazılım geliştirme (acceptance test-driven development, ATDD) ile hangi test senaryosu (test case) bu kriterden doğru türetilmiştir?

a) Girdi: toplam 520, müşteri üye. Beklenen sonuç (expected result): kargo ücreti sıfır.
b) Girdi: toplam 520, müşteri üye. Beklenen sonuç: sipariş veritabanında yeni bir kayıt olarak saklanır.
c) Girdi: toplam 480, müşteri üye değil. Beklenen sonuç: kargo ücreti sıfır.
d) Girdi: müşteri üye, sipariş tutarı belirtilmemiş. Beklenen sonuç: her siparişte kargo ücreti sıfır.

<!-- META
no: 37
kilavuz_no: 8
bolum: 1
lo: FL-1.5.3
k: K2
tip: comparison
dogru: c
tuzak: Near-miss karışıklığı
degisiklik: duzeltme
-->

**Soru 37** (1 puan)

Bir şirket mobil uygulamasını harici bir test laboratuvarına test ettirir. İki sürümden sonra aşağıdaki gözlemler kaydedilir. Hangisi yüksek test bağımsızlığının (independence of testing) tipik bir sakıncasını gösterir?

a) Laboratuvarın varsayımları sorgulaması, gereksinimlerdeki çelişkilerin onaydan önce giderilmesini sağladı.
b) Laboratuvar, geliştiricilerden farklı varsayımlarla çalışarak onların kaçırdığı arızaları (failure) buldu.
c) Laboratuvar günlük ekip iletişiminin dışında kaldığı için gereksinim değişikliklerini geç öğrendi.
d) Geliştiriciler kendi bileşen testlerini (component testing) tamamlayıp laboratuvara test edilebilir sürüm teslim etti.

<!-- META
no: 38
kilavuz_no: 37
bolum: 5
lo: FL-5.4.1
k: K2
tip: concept
dogru: c
tuzak: Near-miss karışıklığı
degisiklik: duzeltme
-->

**Soru 38** (1 puan)

Bir test tamamlama raporu (test completion report), “Regresyon test grubu (regression test suite) sürüm adayı üzerinde başarıyla koşuldu” der. Ancak rapor sürüm adayının derleme numarasını ve test grubu sürümünü belirtmez. Denetçi kanıtı yetersiz bulur. Hangi uygulama bu eksikliği giderir?

a) Daha fazla testi otomatikleştirerek her koşumda ayrıntılı sonuç raporlarının oluşturulmasını sağlamak.
b) Sistem testi (system testing) için çıkış kriterlerini (exit criteria) sıkılaştırarak kabul eşiğini yükseltmek.
c) Yapılandırma yönetimiyle (configuration management) test edilen sürümleri tanımlayıp raporda belirtmek.
d) Hata raporlarına (defect report), hatalı işlemin yeniden üretilmesini sağlayan ayrıntılı adımları eklemek.

<!-- META
no: 39
kilavuz_no: 38
bolum: 5
lo: FL-5.5.1
k: K3
tip: calculation
dogru: a
tuzak: Prosedür hatası
degisiklik: duzeltme
-->

**Soru 39** (1 puan)

Bir test uzmanı aşağıdaki hata raporu (defect report) taslağını hazırlar:

- Kimlik: DR-2107. Başlık: Üye siparişlerinde sadakat puanı verilmiyor.
- Tarih: 8 Haziran 2026. Yazan: J. Marsh.
- Test nesnesi (test object): ödeme hizmeti v2.3. Ortam: ön üretim, derleme 5511.
- Test esası (test basis): Üyeler, sipariş toplamının her tam 10,00 birimi için bir sadakat puanı kazanır.
- Adımlar: Üye olarak oturum açın; toplamı 527,40 olan ürünler ekleyin; siparişi tamamlayın; onay sayfasını açın.
- Gerçekleşen sonuç (actual result): Sayfada “Kazanılan sadakat puanı: 0” yazıyor.
- Beklenen sonuç (expected result): Henüz yazılmadı.
- Önem derecesi (severity): büyük. Öncelik (priority): yüksek.

Bu testin beklenen sonucunu, gerçekleşen sonuçla doğrudan karşılaştırılabilecek somut bir gözlem olarak hangi ifade **EN İYİ** tanımlar?

a) Sipariş onay sayfasında “Kazanılan sadakat puanı: 52” yazmalıdır.
b) Sipariş onay sayfasında “Kazanılan sadakat puanı: 53” yazmalıdır.
c) Sipariş onay sayfası, üye siparişi için gereksinimde tanımlanan doğru sadakat puanı sayısını göstermelidir.
d) Ödeme hizmetindeki sadakat puanı hesaplaması, üye siparişlerine puan verilecek biçimde düzeltilmelidir.

<!-- META
no: 40
kilavuz_no: 40
bolum: 6
lo: FL-6.2.1
k: K1
tip: concept
dogru: d
tuzak: Kaynak bilgi eksiği
degisiklik: yok
-->

**Soru 40** (1 puan)

Kullanıcı arayüzünden regresyon testi (regression testing) otomasyonu kuran bir ekip, altı ay sonra her ekran değişikliğinin onlarca betiği bozduğunu görür. Betikleri güncellemek, bütün otomasyon projesi için planlanandan daha fazla efor gerektirmektedir. Hangi test otomasyonu (test automation) riski gerçekleşmiştir?

a) Aracı kullanımdan kaldırabilecek bir tedarikçiye bağımlı kalınması
b) Manuel testin daha uygun olduğu bir işte test aracının kullanılması
c) Araç sonuçlarına fazla güvenilerek insanın eleştirel düşünmesinin ihmal edilmesi
d) Test betiklerini sürdürmek için gereken bakım eforunun eksik tahmin edilmesi


## Part 2 — Cevap anahtarı ve skor değerlendirmesi

### Cevap anahtarı

| Soru | Cevap | Bölüm | LO | K |
|---|---|---|---|---|
| 1 | b | 1 | FL-1.1.1 | K1 |
| 2 | a | 2 | FL-2.1.1 | K2 |
| 3 | c | 4 | FL-4.1.1 | K2 |
| 4 | b | 5 | FL-5.1.3 | K2 |
| 5 | d | 3 | FL-3.1.1 | K1 |
| 6 | d | 4 | FL-4.2.1 | K3 |
| 7 | c | 1 | FL-1.2.3 | K2 |
| 8 | c | 2 | FL-2.1.2 | K1 |
| 9 | d | 5 | FL-5.1.6 | K1 |
| 10 | d | 4 | FL-4.3.1 | K2 |
| 11 | d | 1 | FL-1.3.1 | K2 |
| 12 | b | 2 | FL-2.1.3 | K1 |
| 13 | a | 4 | FL-4.2.2 | K3 |
| 14 | a | 5 | FL-5.1.7 | K2 |
| 15 | a | 3 | FL-3.2.3 | K1 |
| 16 | b | 4 | FL-4.3.3 | K2 |
| 17 | d | 1 | FL-1.4.1 | K2 |
| 18 | d | 5 | FL-5.2.4 | K2 |
| 19 | b | 4 | FL-4.2.3 | K3 |
| 20 | b | 6 | FL-6.1.1 | K2 |
| 21 | b | 1 | FL-1.4.3 | K2 |
| 22 | d | 2 | FL-2.1.5 | K2 |
| 23 | c | 4 | FL-4.2.4 | K3 |
| 24 | b | 5 | FL-5.1.4 | K3 |
| 25 | b | 3 | FL-3.1.3 | K2 |
| 26 | b | 4 | FL-4.4.1 | K2 |
| 27 | a | 1 | FL-1.4.4 | K2 |
| 28 | a | 2 | FL-2.2.1 | K2 |
| 29 | d | 5 | FL-5.1.5 | K3 |
| 30 | c | 4 | FL-4.4.3 | K2 |
| 31 | c | 1 | FL-1.5.2 | K1 |
| 32 | b | 2 | FL-2.2.3 | K2 |
| 33 | c | 4 | FL-4.5.2 | K2 |
| 34 | a | 5 | FL-5.3.2 | K2 |
| 35 | b | 3 | FL-3.2.4 | K2 |
| 36 | a | 4 | FL-4.5.3 | K3 |
| 37 | c | 1 | FL-1.5.3 | K2 |
| 38 | c | 5 | FL-5.4.1 | K2 |
| 39 | a | 5 | FL-5.5.1 | K3 |
| 40 | d | 6 | FL-6.2.1 | K1 |

### Skor bantları

- **35–40:** Sınava çok hazırsınız.
- **30–34:** Rahat geçme bölgesi.
- **26–29:** Geçer; zayıf bölümlerinizi güçlendirin.
- **0–25:** Henüz hazır değilsiniz; bölüm skor kartına göre çalışma rotası belirleyin.

Bu bantlar çalışma önerisidir; tek bir deneme sonucu gerçek sınav başarısını garanti etmez. Çalışma modunda açıklamaları görerek alınan puanı süreli prova puanıyla karşılaştırmayın.

### Bölüm skor kartı

Hedef, her bölümde en az %65 için gereken doğru sayısıdır; kesirli sonuç yukarı yuvarlanır. Bu bölüm hedefleri resmî bölüm bazında geçme barajı değildir. Resmî geçme ölçütü toplam 26/40'tır.

| Bölüm | Soru sayısı | Doğru sayınız | Hedef (%65) | Çalışma önerisi |
|---|---:|---|---|---|
| 1 — Temeller | 8 | | 6/8 | Hedefleri, aktiviteleri ve temel kavram ayrımlarını tekrar edin. |
| 2 — Yaşam döngüsü | 6 | | 4/6 | Test seviyelerini, önce test ve sola alma yaklaşımlarını karşılaştırın. |
| 3 — Statik test | 4 | | 3/4 | Statik/dinamik ayrımı, roller ve gözden geçirme türlerini çalışın. |
| 4 — Analiz ve tasarım | 11 | | 8/11 | Teknikleri veri üzerinde uygulayın, yanlış varyantları karşılaştırın. |
| 5 — Yönetim | 9 | | 6/9 | Planlama, tahmin, önceliklendirme, raporlama ve hata yönetimini çalışın. |
| 6 — Araçlar | 2 | | 2/2 | Araç işlevlerini ve otomasyon risklerini tekrar edin. |


## Part 3 — Açıklamalar

### S1–S10

**Soru 1 — Doğru cevap: b**

**Neden doğru:** Testin hedeflerinden biri, paydaşların bilinçli karar vermesi için bilgi sağlamaktır. Ürün sahibi hata ve risk özetini, özelliği sürüme alma kararına girdi olarak istemektedir.

**En cazip yanlış (near-miss) — c:** Paydaş beklentilerini karşılamak da geçerli bir test hedefidir ve burada da bir paydaş vardır. Ancak istenen, ürünün beklentilere uygunluğunu değerlendirmekten çok sürüm kararını bilgilendirmektir.

**Diğer şıklar:** a) Sözleşme ve mevzuata uygunluk, senaryoda belirtilen kararın dayanağı değildir. · d) Kapsama ulaşmak testin yeterliliğiyle ilgilidir; istenen risk özetinin karar desteği amacını açıklamaz.

*Kaçırdıysanız tekrar edin: Test nedir? | Tuzak: Near-miss karışıklığı | LO: FL-1.1.1 (K1)*

[Kılavuzda tekrar edin: Test nedir?](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-1-1)

**Soru 2 — Doğru cevap: a**

**Neden doğru:** Döngüsel geliştirmede her döngü yeni bir artım üzerinde geliştirme ve test aktiviteleri içerir. Yeni artımlar önceki işlevleri de etkileyebildiğinden test tek bir son aşama olarak ele alınmaz.

**En cazip yanlış (near-miss) — d:** Kısa döngü, farklı test seviyelerinin yakın zamanlarda yürütülmesini çağrıştırır. Bu yakınlık, seviyelerin farklı hedeflerinin tek hedefe dönüşmesi anlamına gelmez.

**Diğer şıklar:** b) Regresyonu son döngüye ertelemek, ara artımların mevcut davranış üzerindeki etkilerini test etmeden bırakır. · c) Sistem testi bütün sistemin davranışına odaklanır; küçük artımlar onu bileşen testine dönüştürmez.

*Kaçırdıysanız tekrar edin: Yaşam döngüsü bağlamında test | Tuzak: Near-miss karışıklığı | LO: FL-2.1.1 (K2)*

[Kılavuzda tekrar edin: Yaşam döngüsü bağlamında test](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-2.html#fl-2-1-1)

**Soru 3 — Doğru cevap: c**

**Neden doğru:** Teknik sınıfını belirleyen, testlerin türetildiği kaynaktır. Spesifikasyondaki durum diyagramı kara kutu, kodun dal kapsamı boşlukları beyaz kutu testine temel oluşturur.

**En cazip yanlış (near-miss) — a:** Durum diyagramı teknik bir model olduğundan kod yapısı gibi algılanabilir. Burada diyagram spesifikasyonun parçasıdır; kod yapısına dayanmayan ilk yaklaşım beyaz kutu değildir.

**Diğer şıklar:** b) İlk testler tecrübeye değil spesifikasyona, ikinci testler ise kara kutu kaynağına değil koda dayanır. · d) İlk yaklaşımın beyaz kutu, ikincinin tecrübeye dayalı olduğu sınıflandırması iki kaynağı da yanlış eşler.

*Kaçırdıysanız tekrar edin: Test tekniklerine genel bakış | Tuzak: Near-miss karışıklığı | LO: FL-4.1.1 (K2)*

[Kılavuzda tekrar edin: Test tekniklerine genel bakış](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-1-1)

**Soru 4 — Doğru cevap: b**

**Neden doğru:** Giriş kriterleri bir aktiviteye başlayabilmek için gereken ön koşulları belirtir. Liste 1 sistem testine başlama koşullarını verir. Çıkış kriterleri aktiviteyi tamamlanmış saymak için ulaşılması gereken durumu tanımlar; Liste 2 aynı test seviyesinin tamamlanma koşullarını verir.

**En cazip yanlış (near-miss) — c:** İki liste de test başlamadan hazırlanabilir; bu nedenle ikisini de giriş kriteri sanmak mümkündür. Türü belirleyen yazılma zamanı değil, başlama veya bitirme kararını yönetmesidir.

**Diğer şıklar:** a) Başlama ön koşulları ile tamamlanma ölçütlerinin etiketlerini ters çevirir. · d) Kabul kriterleri ürünün kabul edilebilir davranışını tanımlar; test seviyesinin başlangıç ve bitiş kapılarıyla aynı şey değildir.

*Kaçırdıysanız tekrar edin: Test planlama | Tuzak: Near-miss karışıklığı | LO: FL-5.1.3 (K2)*

[Kılavuzda tekrar edin: Test planlama](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-1-3)

**Soru 5 — Doğru cevap: d**

**Neden doğru:** Statik test, iş ürünlerini çalıştırmadan inceleyebilir. Sözleşmeler ve test başlatma belgeleri, syllabus tarafından incelenebilir iş ürünleri arasında sayılır.

**En cazip yanlış (near-miss) — c:** Ağ kesilmesiyle ilgili bir tasarım belgesi gözden geçirilebilir. Ancak seçenek belgeyi değil, çalışan ekranın ağ kesildiğinde gösterdiği davranışı sorar; bu dinamik test gerektirir.

**Diğer şıklar:** a) Gerçek yük altındaki yanıt süreleri, hizmet çalıştırılarak ölçülür. · b) Bir oturum boyunca gerçek bellek tüketimi, uygulama çalıştırılarak gözlenir.

*Kaçırdıysanız tekrar edin: Statik testin temelleri | Tuzak: Near-miss karışıklığı | LO: FL-3.1.1 (K1)*

[Kılavuzda tekrar edin: Statik testin temelleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-3.html#fl-3-1-1)

**Soru 6 — Doğru cevap: d**

**Neden doğru:** Denklik payları, aynı tür davranış beklenen girdileri gruplar. Adım adım: 1–9, 10–49 ve 50–100 üç geçerli pay; 1 altı ve 100 üstü iki ayrı geçersiz paydır. Toplam 3 + 2 = 5 pay vardır.

**En cazip yanlış (near-miss) — b:** Dört cevabı, iki reddetme aralığını tek geçersiz payda birleştirerek elde edilebilir. Burada aralıklar ayrıdır ve farklı hata mesajları üretir; iki geçersiz pay olarak ele alınmalıdır.

**Diğer şıklar:** a) Yalnız üç geçerli fiyat aralığını sayar, reddedilen girdileri dışarıda bırakır. · c) Altı, pay sayısı değildir; sınırları veya bir payı fazladan saymak aynı davranış gruplamasını bozmuş olur.

*Kaçırdıysanız tekrar edin: Kara kutu test teknikleri | Tuzak: Prosedür hatası | LO: FL-4.2.1 (K3)*

[Kılavuzda tekrar edin: Kara kutu test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-2-1)

**Soru 7 — Doğru cevap: c**

**Neden doğru:** İnsan hatası kişinin yanlış eylemi veya kararıdır; yanlış saat varsayımı buna örnektir. Arıza, çalışma sırasında beklenenden sapmadır; uçuş sonrasındaki hatırlatma buna örnektir. Bu senaryoda bilgilendirme eksikliği daha derindeki örgütsel neden, yanlış kod ise iş ürünündeki hatadır.

**En cazip yanlış (near-miss) — b:** Yanlış varsayım zincirin başına yakın olduğundan kök neden gibi görünebilir. Ancak seçenek varsayımı insan hatasıyla karıştırır; ayrıca saklanan yanlış veriyi gözlenen arıza yerine koyar.

**Diğer şıklar:** a) Kodda bulunan kusuru arıza olarak adlandırır; arıza kullanıcıya yansıyan çalışma davranışıdır. · d) Yanlış kod bu senaryoda hata, bilgilendirme eksikliği ise kök neden olarak verilmiştir; seçenek rolleri yanlış eşler.

*Kaçırdıysanız tekrar edin: Test neden gereklidir? | Tuzak: Near-miss karışıklığı | LO: FL-1.2.3 (K2)*

[Kılavuzda tekrar edin: Test neden gereklidir?](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-2-3)

**Soru 8 — Doğru cevap: c**

**Neden doğru:** Her yaşam döngüsünde geçerli iyi uygulamalar arasında, taslaklar hazır olur olmaz test uzmanlarının gözden geçirmelere katılması bulunur. Bu uygulama, hikâye hatalarını kodlama sonrasına kalmadan bulmaya yardım eder.

**En cazip yanlış (near-miss) — a:** Farklı test seviyelerine farklı hedefler vermek de geçerli bir iyi uygulamadır. Ancak test uzmanlarının hikâye taslaklarını geç görmesi sorununu doğrudan gidermez.

**Diğer şıklar:** b) Kodun bütün özelliklerinin tamamlanmasını beklemek, erken hikâye incelemesinin yerini tutmaz. · d) İş temsilcileriyle iş birliği yapmak yerine onların sorumluluğunu test uzmanına devretmek belirtilen iyi uygulama değildir.

*Kaçırdıysanız tekrar edin: Yaşam döngüsü bağlamında test | Tuzak: Near-miss karışıklığı | LO: FL-2.1.2 (K1)*

[Kılavuzda tekrar edin: Yaşam döngüsü bağlamında test](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-2.html#fl-2-1-2)

**Soru 9 — Doğru cevap: d**

**Neden doğru:** Test piramidinin katman sayısı ve adları farklı modellerde değişebilir. Ortak eğilim, tabanda çok sayıda hızlı ve yalıtılmış test, üstte daha az sayıda geniş kapsamlı test bulunmasıdır.

**En cazip yanlış (near-miss) — a:** Birim, servis ve kullanıcı arayüzü adları bilinen bir piramit modeline aittir. Ancak bu varyantı bütün geçerli piramitlerin sabit tanımı saymak yanlıştır.

**Diğer şıklar:** b) Üst katmanlarda daha çok parça birlikte çalıştığı için yalıtım artmaz, azalır. · c) Piramit testlerin ayrıntı ve bütünleşme düzeyleriyle ilgilidir; her katmana zorunlu bir test tekniği atamaz.

*Kaçırdıysanız tekrar edin: Test planlama | Tuzak: Kaynak bilgi eksiği | LO: FL-5.1.6 (K1)*

[Kılavuzda tekrar edin: Test planlama](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-1-6)

**Soru 10 — Doğru cevap: d**

**Neden doğru:** Komut kapsamı, hangi çalıştırılabilir komutların testlerde çalıştırıldığını gösterir. Verilen blok hizmete ulaşılamadığında devreye girdiği için bu durumu çalıştıran bir test, eksik kapsamı hedefler.

**En cazip yanlış (near-miss) — c:** Bütün testlerin geçmesi, çalıştırılmış davranış için olumlu bir sonuçtur. Fakat bu üç komut çalıştırılmadığından, geçen testler o bloğun doğruluğu için kanıt oluşturmaz.

**Diğer şıklar:** a) Bir komutun mevcut testlerle çalıştırılmaması, hiçbir mümkün girdide çalıştırılamayacağını kanıtlamaz. · b) Komut ve dal kapsamının kapsam öğeleri farklıdır; aynı kod üzerinde ölçülmeleri oranlarının eşit olmasını gerektirmez.

*Kaçırdıysanız tekrar edin: Beyaz kutu test teknikleri | Tuzak: Near-miss karışıklığı | LO: FL-4.3.1 (K2)*

[Kılavuzda tekrar edin: Beyaz kutu test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-3-1)


### S11–S20

**Soru 11 — Doğru cevap: d**

**Neden doğru:** Erken test prensibi, hataların erken bulunmasının sonraki iş ürünlerine yayılmayı azaltacağını açıklar. İlk çelişki yalnız hikâyede düzeltilirken ikincisi tasarım, kod, testler ve acil yama üzerinde çalışma gerektirmiştir.

**En cazip yanlış (near-miss) — a:** Her iki hata da kullanıcı hikâyesinde olduğundan bir yoğunlaşma görülüyormuş gibi düşünülebilir. Ancak karşılaştırmanın odak noktası hata sayısının dağılımı değil, bulunma zamanının düzeltme eforuna etkisidir.

**Diğer şıklar:** b) Testin hataların yokluğunu kanıtlayamaması doğru bir prensiptir; senaryo bu kanıt sınırını örneklemiyor. · c) Hatasızlık yanılgısı, hata bulunmamasını iş ihtiyacına uygunlukla eşitlemekle ilgilidir; burada iki düzeltme maliyeti karşılaştırılıyor.

*Kaçırdıysanız tekrar edin: Test prensipleri | Tuzak: Near-miss karışıklığı | LO: FL-1.3.1 (K2)*

[Kılavuzda tekrar edin: Test prensipleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-3-1)

**Soru 12 — Doğru cevap: b**

**Neden doğru:** TDD, ATDD ve BDD, uygulama geliştirilmeden önce testlerin oluşturulmasını destekleyen yaklaşımlardır. Bu testler daha sonraki değişiklikler ve yeniden düzenlemeler sırasında kaliteyi koruyan otomatik testler olarak sürdürülebilir.

**En cazip yanlış (near-miss) — d:** Kabul kriterleri ve iş temsilcileri önce test yaklaşımlarıyla ilişkilidir. Ancak kabul kriterlerinden kabul testleri türetme ATDD bağlamıdır; bu özellikleri TDD tanımı gibi sunmak yaklaşımları karıştırır.

**Diğer şıklar:** a) ATDD testleri, tamamlanmış kod yapısından değil kabul kriterlerinden ve gerçekleştirim öncesinde türetilir. · c) BDD, beklenen davranışı paydaşların anlayabildiği doğal dil örnekleriyle ifade eder; kod yapısını davranışın kaynağı yapmaz.

*Kaçırdıysanız tekrar edin: Yaşam döngüsü bağlamında test | Tuzak: Kaynak bilgi eksiği | LO: FL-2.1.3 (K1)*

[Kılavuzda tekrar edin: Yaşam döngüsü bağlamında test](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-2.html#fl-2-1-3)

**Soru 13 — Doğru cevap: a**

**Neden doğru:** İki değerli SDA, sınır değerlerini bitişik paydaki en yakın komşularıyla ele alır. Adım adım: alt uçta 7 ve 8, üst uçta 20 ve 21 seçilir. Birleşim dört farklı uzunluktur.

**En cazip yanlış (near-miss) — d:** Sekiz, aynı paylar için tam üç değerli SDA uygulandığında ortaya çıkan sayıdır. Soru iki değerli varyantı istediği için 6,7,8,9,19,20,21,22 kümesi bu soruya uygulanmaz.

**Diğer şıklar:** b) İki, yalnız iki uç değeri sayar; bitişik paylardaki komşuları atlar. · c) Altı, üç değerli yaklaşımı yalnız geçerli payın uçlarına uygulayan eksik sayımdır; istenen iki değerli yaklaşım değildir.

*Kaçırdıysanız tekrar edin: Kara kutu test teknikleri | Tuzak: Prosedür hatası | LO: FL-4.2.2 (K3)*

[Kılavuzda tekrar edin: Kara kutu test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-2-2)

**Soru 14 — Doğru cevap: a**

**Neden doğru:** Q4 teknolojiye dönüktür ve ürünü eleştiren testleri içerir. Güvenlik testleri, kullanılabilirlik dışındaki fonksiyonel olmayan testlerle birlikte bu çeyrekte yer alır.

**En cazip yanlış (near-miss) — b:** Kullanılabilirlik fonksiyonel olmayan bir özellik olduğu için Q4 makul görünebilir. Ancak çeyrek modelinde kullanılabilirlik kullanıcıya dönüktür ve ürünü eleştirir; Q3 içinde ele alınır.

**Diğer şıklar:** c) Bileşen entegrasyon testleri teknolojiye dönük ve ekibi destekleyicidir; Q3 yerine Q1 içindedir. · d) Keşif testi işe dönük olup ürünü eleştirir; Q2 yerine Q3 içinde yer alır.

*Kaçırdıysanız tekrar edin: Test planlama | Tuzak: Near-miss karışıklığı | LO: FL-5.1.7 (K2)*

[Kılavuzda tekrar edin: Test planlama](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-1-7)

**Soru 15 — Doğru cevap: a**

**Neden doğru:** Gözden geçirilen iş ürününü oluşturan ve gerekli düzeltmeleri yapan rol yazardır. Gözden geçirme diğer rollerle sorunları belirlese de düzeltme sorumluluğu bu roldedir.

**En cazip yanlış (near-miss) — b:** Gözden geçirme lideri gözden geçirmenin genel organizasyonundan sorumludur. Bu genel sorumluluk, spesifikasyondaki hataları bizzat düzeltme görevini üstlenmesi anlamına gelmez.

**Diğer şıklar:** c) Katip, anomalileri ve kararları kaydeder; iş ürününün düzeltmesini yapmak onun rol tanımı değildir. · d) Moderatör, toplantının etkili yürütülmesini ve katılımı kolaylaştırır; belgeyi düzeltme rolü yazarındır.

*Kaçırdıysanız tekrar edin: Geri bildirim ve gözden geçirme süreci | Tuzak: Near-miss karışıklığı | LO: FL-3.2.3 (K1)*

[Kılavuzda tekrar edin: Geri bildirim ve gözden geçirme süreci](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-3.html#fl-3-2-3)

**Soru 16 — Doğru cevap: b**

**Neden doğru:** Beyaz kutu testi testlerin türetilmesinde gerçekleştirim yapısını kullanır. Böylece spesifikasyonda belirtilmemiş gerçekleştirim kısımlarının da çalıştırılmasını ve kapsamının ölçülmesini destekler.

**En cazip yanlış (near-miss) — c:** Gerçekleştirimden bağımsız iş davranışını test etmek değerli bir yaklaşımdır. Ancak seçenek, testleri gereksinimlerden türeten kara kutu yaklaşımını beyaz kutunun güçlü yönü gibi sunar.

**Diğer şıklar:** a) Kodun kontrol akışını incelemek, paydaşların bütün iş ihtiyaçlarının karşılandığını doğrulamaz. · d) Kod kapsamı yalnız mevcut gerçekleştirimi ölçer; yazılmamış her gereksinimin koda eklendiğini güvenceye almaz. Syllabus, eksik işlevlerin beyaz kutuyla fark edilmeyebileceğini belirtir.

*Kaçırdıysanız tekrar edin: Beyaz kutu test teknikleri | Tuzak: Near-miss karışıklığı | LO: FL-4.3.3 (K2)*

[Kılavuzda tekrar edin: Beyaz kutu test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-3-3)

**Soru 17 — Doğru cevap: d**

**Neden doğru:** Test tasarımı, test koşullarından test senaryoları ve kapsam öğeleri türetir. Gerekli veri ve ortam özelliklerini tanımlamak da bu aktivitenin parçasıdır; henüz verinin oluşturulduğu veya ortamın kurulduğu söylenmemektedir.

**En cazip yanlış (near-miss) — b:** Veri ve ortam sözcükleri test uyarlamayı çağrıştırır. Ancak uyarlama bunları oluşturma ve kurma işidir; burada gereksinimleri tanımlama ve tasarlama anlatılmaktadır.

**Diğer şıklar:** a) Test analizi test koşullarını belirler ve önceliklendirir; soruda bu koşullar zaten girdi olarak hazırdır. · c) Test planlama hedefleri ve yaklaşımı belirler; verilen faaliyet tek tek senaryoların tasarlanmasıdır.

*Kaçırdıysanız tekrar edin: Test aktiviteleri, test çalışma ürünleri ve roller | Tuzak: Near-miss karışıklığı | LO: FL-1.4.1 (K2)*

[Kılavuzda tekrar edin: Test aktiviteleri, test çalışma ürünleri ve roller](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-4-1)

**Soru 18 — Doğru cevap: d**

**Neden doğru:** Acil durum planı, risk gerçekleştiğinde uygulanacak önceden hazırlanmış yanıtı tanımlar. Önceki sağlayıcıya 15 dakika içinde dönme prosedürü, canlı ortamda arıza oluşursa hizmeti sürdürebilmeye yöneliktir.

**En cazip yanlış (near-miss) — c:** Ekip entegrasyonu test ettiği için bütün çalışmayı test yoluyla risk azaltma saymak caziptir. Sorulan işlem test koşmak değil, risk gerçekleştiğinde devreye girecek geri dönüş planını hazırlamaktır.

**Diğer şıklar:** a) Risk kabulü, belirtilen riskle yaşamayı seçmektir; burada risk gerçekleştiğinde uygulanacak somut bir prosedür hazırlanmıştır. · b) Risk transferi, riskin sonuçlarını başka tarafa aktarır; önceki sağlayıcıya dönme prosedürü böyle bir aktarım tanımlamıyor.

*Kaçırdıysanız tekrar edin: Risk yönetimi | Tuzak: Near-miss karışıklığı | LO: FL-5.2.4 (K2)*

[Kılavuzda tekrar edin: Risk yönetimi](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-2-4)

**Soru 19 — Doğru cevap: b**

**Neden doğru:** Tam karar tablosunda her farklı koşul birleşimi bir sütun oluşturur. Adım adım: üç yaş grubu × iki kart durumu × iki teslim alma durumu = 3 × 2 × 2 = 12 sütundur. Sütun azaltma yapılmadığı açıkça belirtilmiştir.

**En cazip yanlış (near-miss) — d:** Altı, 3 × 2 hesabıyla elde edilir ve koşullardan birini atlamış olur. İkinci ikili koşul da bağımsız olduğundan her birleşimi ikiye katlar.

**Diğer şıklar:** a) On sekiz, ikili koşullardan birini üç değerli sayarak 3 × 3 × 2 uygulamaktan doğar; verilen koşulda üçüncü değer yoktur. · c) Yirmi dört, 12 birleşimi gerek olmadığı halde bir kez daha ikiye katlamaktan doğar; üç koşulun bütün değerleri zaten 3 × 2 × 2 hesabına dahildir.

*Kaçırdıysanız tekrar edin: Kara kutu test teknikleri | Tuzak: Prosedür hatası | LO: FL-4.2.3 (K3)*

[Kılavuzda tekrar edin: Kara kutu test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-2-3)

**Soru 20 — Doğru cevap: b**

**Neden doğru:** Test koşumu ve kapsam araçları, otomatik testleri çalıştırmayı ve kod kapsamını ölçmeyi destekler. Sonuçların toplanması bu ana işlevlerin yanında gerçekleşmektedir.

**En cazip yanlış (near-miss) — a:** Sonuç toplamak test yönetimi işlevini çağrıştırır. Ancak araç mevcut testleri bizzat koşuyor ve çalıştırılan kodu ölçüyor; belirleyici işlevler koşum ve kapsamdır.

**Diğer şıklar:** c) Statik test araçları iş ürünlerini çalıştırmadan incelemeyi destekler; bu araç testleri çalıştırmaktadır. · d) Test tasarımı ve uyarlama araçları test senaryoları, veri ve prosedürlerin hazırlanmasını destekler; burada hazır testlerin koşumu anlatılmaktadır.

*Kaçırdıysanız tekrar edin: Test için araç desteği | Tuzak: Near-miss karışıklığı | LO: FL-6.1.1 (K2)*

[Kılavuzda tekrar edin: Test için araç desteği](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-6.html#fl-6-1-1)


### S21–S30

**Soru 21 — Doğru cevap: b**

**Neden doğru:** Test analizinin iş ürünleri arasında test koşulları ve doğrudan düzeltilmeyen test esası hatalarının raporları bulunur. Test uzmanı hikâyeden koşul türetirken çelişkiyi bulduğu için rapor bir analiz çıktısıdır.

**En cazip yanlış (near-miss) — a:** Hata raporu denince test koşumunda görülen arızaların raporlanması akla gelebilir. Ancak bu rapor bir koşumdan değil, test esasındaki çelişkinin analiz sırasında bulunmasından doğmuştur.

**Diğer şıklar:** c) Test tasarımı senaryoları ve veri/ortam gereksinimlerini türetir; soruda koşullar türetilmektedir. · d) Test tamamlama raporlama ve kapanış işlerini içerir; burada analiz sürmektedir.

*Kaçırdıysanız tekrar edin: Test aktiviteleri, test çalışma ürünleri ve roller | Tuzak: Near-miss karışıklığı | LO: FL-1.4.3 (K2)*

[Kılavuzda tekrar edin: Test aktiviteleri, test çalışma ürünleri ve roller](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-4-3)

**Soru 22 — Doğru cevap: d**

**Neden doğru:** Sola alma, test aktivitelerinin yaşam döngüsünde daha erken yapılmasını ifade eder. Sistem tamamlanmadan bileşenlerde performans ve güvenlik testi koşmak bu yaklaşımı örnekler.

**En cazip yanlış (near-miss) — a:** TDD de erken testle ilişkili olduğundan caziptir. Ancak TDD, testleri koddan önce oluşturarak geliştirmeyi yönlendirir; burada bileşenler geliştirilmiş, testlerin seviyesi ve zamanı öne alınmıştır.

**Diğer şıklar:** b) Onaylama testi belirli bir hata düzeltmesinin işe yaradığını kontrol eder; senaryoda böyle bir düzeltme yoktur. · c) Risk bazlı test, risk düzeyine göre kapsam ve öncelik seçimini anlatır; kök bu seçimi değil zamanlamayı açıklamaktadır.

*Kaçırdıysanız tekrar edin: Yaşam döngüsü bağlamında test | Tuzak: Near-miss karışıklığı | LO: FL-2.1.5 (K2)*

[Kılavuzda tekrar edin: Yaşam döngüsü bağlamında test](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-2.html#fl-2-1-5)

**Soru 23 — Doğru cevap: c**

**Neden doğru:** Geçerli dizide her olay, o andaki durumdan tanımlı bir geçişi izler. Adım adım: Boşta → Oynatılıyor → Duraklatıldı → Oynatılıyor → Durduruldu. Bu yol sırasıyla başlat, duraklat, sürdür, durdur olaylarıyla oluşur.

**En cazip yanlış (near-miss) — b:** Dizinin başı ve sonu geçerli göründüğünden aradaki ikinci duraklat gözden kaçabilir. İlk duraklat sonrasında durum Duraklatıldı olur; bu durumdan yeniden duraklat geçişi tanımlı değildir.

**Diğer şıklar:** a) Başlat sonrasında durum Oynatılıyor olur; bu durumdan sürdür geçişi yoktur. · d) Durdur sonrasında Durduruldu durumuna gelinir; bu durumdan sürdür geçişi yoktur.

*Kaçırdıysanız tekrar edin: Kara kutu test teknikleri | Tuzak: Prosedür hatası | LO: FL-4.2.4 (K3)*

[Kılavuzda tekrar edin: Kara kutu test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-2-4)

**Soru 24 — Doğru cevap: b**

**Neden doğru:** Oranlara dayalı tahminleme, benzer projedeki efor ilişkisini yeni geliştirme eforuna uygular. Adım adım: geliştirme:test = 4:3 olduğundan test eforu 720 × 3/4 = 540 kişi-gündür.

**En cazip yanlış (near-miss) — c:** 960, oran fikrini koruyor gibi görünür ancak 720 × 4/3 ile oranı ters uygular. Verilen ilişkide test eforu geliştirme eforunun dörtte üçüdür.

**Diğer şıklar:** a) 180, 720/4 ile yalnız bir oran birimini hesaplar; test tarafı bu birimden üç tane içerir. · d) 1.260, 720 + 540 ile geliştirme ve test eforlarının toplamıdır; soru yalnız test eforunu sorar.

*Kaçırdıysanız tekrar edin: Test planlama | Tuzak: Prosedür hatası | LO: FL-5.1.4 (K3)*

[Kılavuzda tekrar edin: Test planlama](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-1-4)

**Soru 25 — Doğru cevap: b**

**Neden doğru:** Statik test kodu çalıştırmadan uygulanır ve çalıştırmaya bağlı olmayan kalite özelliklerini değerlendirebilir. Sürdürülebilirlik buna bir örnektir; çalışma anındaki performans ölçümleri ise dinamik test gerektirir.

**En cazip yanlış (near-miss) — c:** Statik analiz bazı kalite özelliklerini değerlendirebildiğinden performansı da ölçebileceği düşünülebilir. Ancak yük altındaki gerçek yanıt süresi, hizmetin çalıştırılmasına bağlıdır.

**Diğer şıklar:** a) Dinamik test için çalıştırılabilir bir test nesnesi gerekir; gereksinim belgesini inceleme statik testtir. · d) Kabul kriteri için test eksikliği gibi kapsam boşluklarını gözden geçirmede saptamak statik testin güçlü yönlerindendir; seçenek ilişkiyi ters çevirir.

*Kaçırdıysanız tekrar edin: Statik testin temelleri | Tuzak: Near-miss karışıklığı | LO: FL-3.1.3 (K2)*

[Kılavuzda tekrar edin: Statik testin temelleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-3.html#fl-3-1-3)

**Soru 26 — Doğru cevap: b**

**Neden doğru:** Hata tahminleme, test uzmanının geçmiş insan hataları, hatalar ve arızalar hakkındaki bilgisini kullanır. Buradaki girdiler geçmiş sürümlerde sorun oluşturdukları için seçilmiştir.

**En cazip yanlış (near-miss) — d:** Sıfır saat, sayısal bir sınır gibi görünebilir. Ancak girdinin seçilme nedeni belirtilmiş payların sınırları değil, geçmişte gözlenmiş arızadır.

**Diğer şıklar:** a) Keşif testinde öğrenme, tasarım ve koşum birbirini yönlendirir; burada önceden hatırlanan arızalardan test tasarlanıyor. · c) Kontrol listesine dayalı testte hazırlanmış kontrol maddeleri kullanılır; senaryo böyle bir liste vermiyor.

*Kaçırdıysanız tekrar edin: Tecrübeye dayalı test teknikleri | Tuzak: Near-miss karışıklığı | LO: FL-4.4.1 (K2)*

[Kılavuzda tekrar edin: Tecrübeye dayalı test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-4-1)

**Soru 27 — Doğru cevap: a**

**Neden doğru:** İzlenebilirlik, gereksinimlerle bunları kapsayan testler ve sonuçları arasındaki bağlantıları görünür kılar. Denetçinin hangi gereksinimin koşulmuş hangi testle kapsandığını bulması bu bağlantılarla kolaylaşır.

**En cazip yanlış (near-miss) — c:** Otomasyon testleri hızlı koşabilir ve ayrıntılı kayıt üretebilir. Ancak gereksinim-test bağlantıları yoksa bu kayıtlar istenen gereksinim kapsamını kendiliğinden kanıtlamaz.

**Diğer şıklar:** b) Bağımsızlık, değerlendirmedeki farklı bakış açılarını destekler; gereksinimleri koşulmuş testlerle eşleştirmez. · d) Giriş kriterleri testin başlayabilmesini yönetir; gereksinim kapsamının kanıtını oluşturan bağlantılar değildir.

*Kaçırdıysanız tekrar edin: Test aktiviteleri, test çalışma ürünleri ve roller | Tuzak: Near-miss karışıklığı | LO: FL-1.4.4 (K2)*

[Kılavuzda tekrar edin: Test aktiviteleri, test çalışma ürünleri ve roller](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-4-4)

**Soru 28 — Doğru cevap: a**

**Neden doğru:** Kabul testi, sistemin kullanıma ve dağıtıma hazır olmasını değerlendirmeye odaklanır. Sistemi işletecek ekibin yedekleme, geri yükleme ve operasyon görevlerini kontrol etmesi operasyonel kabul testi bağlamıdır.

**En cazip yanlış (near-miss) — b:** Sistem testi de bütün sistemi temsili ortamda değerlendirebilir. Ancak burada belirleyici olan, operasyon ekibinin sistemi canlıda işletebilme ve dağıtıma hazır olma amacıdır.

**Diğer şıklar:** c) Sistem entegrasyon testi, farklı sistemler ve harici hizmetler arasındaki arayüzlere odaklanır. · d) Bileşen entegrasyon testi, sistem içindeki bileşenler arasındaki etkileşimlere odaklanır; dağıtıma hazırlık değerlendirmesi değildir.

*Kaçırdıysanız tekrar edin: Test seviyeleri ve test çeşitleri | Tuzak: Near-miss karışıklığı | LO: FL-2.2.1 (K2)*

[Kılavuzda tekrar edin: Test seviyeleri ve test çeşitleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-2.html#fl-2-2-1)

**Soru 29 — Doğru cevap: d**

**Neden doğru:** Ek kapsama dayalı önceliklendirme, her adımda henüz kapsanmamış en çok öğeyi ekleyen testi seçer. Adım adım: TC1 altı komutla ilk; ardından TC3 üç yeni komutla ikinci; TC4 S10 ile üçüncü; yeni öğe eklemeyen TC2 sondadır.

**En cazip yanlış (near-miss) — a:** TC1,TC2,TC3,TC4 sırası, testleri kendi toplam kapsamlarına göre 6,5,3,2 diye dizer. Ancak ek kapsamda TC1 sonrasında TC2 hiçbir yeni öğe eklemez; hesap her seçimden sonra yenilenmelidir.

**Diğer şıklar:** b) TC3 sonrasında TC4 bir yeni komut eklerken TC2 sıfır ekler; üçüncü sıraya TC2 konamaz. · c) İlk sıraya en az kapsamlı testi koyar; verilen en çok ek kapsam ölçütünü başlangıçta ihlal eder.

*Kaçırdıysanız tekrar edin: Test planlama | Tuzak: Prosedür hatası | LO: FL-5.1.5 (K3)*

[Kılavuzda tekrar edin: Test planlama](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-1-5)

**Soru 30 — Doğru cevap: c**

**Neden doğru:** Kontrol listesi, ayrıntılı test senaryoları bulunmadığında neyin kontrol edileceğine yol gösterir. Kontrollerin tam uygulanışında test uzmanına muhakeme alanı bırakırken bir ölçüde tutarlılık sağlar.

**En cazip yanlış (near-miss) — a:** Tutarlılık isteği, her maddenin ayrıntılı koşum adımlarına dönüştürülmesini makul gösterebilir. Ancak kontrol listesi, ayrıntılı test prosedüründen farklı olarak üst düzey hatırlatmalarla çalışır.

**Diğer şıklar:** b) Bir testin bir sürümde geçmesi, ilgili kontrolün gelecek sürümler için gereksiz olduğunu göstermez. · d) Kontrol listeleri tecrübeye dayalı teknik kapsamındadır; kod dalları kapsamının ölçüsü değildir.

*Kaçırdıysanız tekrar edin: Tecrübeye dayalı test teknikleri | Tuzak: Near-miss karışıklığı | LO: FL-4.4.3 (K2)*

[Kılavuzda tekrar edin: Tecrübeye dayalı test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-4-3)


### S31–S40

**Soru 31 — Doğru cevap: c**

**Neden doğru:** Tüm ekip yaklaşımı, ekip üyelerinin farklı bilgi ve becerilerini projenin yararına kullanmasını destekler. Kalite sorumluluğu ortak tutulur; bu yaklaşım uzmanları birbirinden ayırmaya dayanmaz.

**En cazip yanlış (near-miss) — b:** Bağımsız test, özellikle bazı emniyet kritik bağlamlarda değerli olabilir. Ancak yüksek bağımsızlık, yakın iş birliğine dayanan tüm ekip yaklaşımının tanımlayıcı avantajı değildir.

**Diğer şıklar:** a) Diğer ekip aktivitelerinden uzaklaşmak, iş birliği ve ortak sorumluluk yaklaşımına aykırıdır. · d) Kalite sorumluluğunu ayrı ekibe devretmek, bütün ekibin kaliteye katkısı ilkesini tersine çevirir.

*Kaçırdıysanız tekrar edin: Testte temel beceriler ve iyi uygulamalar | Tuzak: Kaynak bilgi eksiği | LO: FL-1.5.2 (K1)*

[Kılavuzda tekrar edin: Testte temel beceriler ve iyi uygulamalar](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-5-2)

**Soru 32 — Doğru cevap: b**

**Neden doğru:** Onaylama testi, belirli hatanın giderilip giderilmediğini kontrol eder. Regresyon testi ise değişikliğin olumsuz sonuçlarını arar; bunlar değişen bölümde, diğer bölümlerde veya bağlı sistemlerde görülebilir. Sorudaki iki aktivitenin amaçları bu sırayla verilmiştir.

**En cazip yanlış (near-miss) — a:** İkinci aktivitenin yan etki araması doğru anlatıldığı için bütün seçenek doğru görünebilir. Ancak ilk aktivite arızayı ortaya çıkaran örneği yeniden koşarak yan etkiden çok bilinen hatanın giderilmesini doğrular.

**Diğer şıklar:** c) Değişmeyen alanlarda da olumsuz sonuçlar olabilir; regresyon koşumunu formalite saymak yanlıştır. · d) Kullanıcı ihtiyaçlarını sağlama ve kapsam ölçme, kökte açıkça verilen iki yeniden koşum amacını karşılamaz.

*Kaçırdıysanız tekrar edin: Test seviyeleri ve test çeşitleri | Tuzak: Near-miss karışıklığı | LO: FL-2.2.3 (K2)*

[Kılavuzda tekrar edin: Test seviyeleri ve test çeşitleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-2.html#fl-2-2-3)

**Soru 33 — Doğru cevap: c**

**Neden doğru:** Kural odaklı kabul kriterleri, koşullar ile çıktılar arasındaki eşlemeyi liste veya tablo biçiminde belirtebilir. Bu tabloda üyelik ve sipariş toplamı, uygulanacak kargo ücretine eşlenmektedir.

**En cazip yanlış (near-miss) — a:** Her satır örnek gibi okunabildiğinden senaryo odaklı biçim sanılabilir. Ancak tablo bir olayın ardından gelişen akışı değil, koşul-çıktı kurallarını ifade etmektedir.

**Diğer şıklar:** b) Tablo kargo kodunun yapısını veya hangi dalın önce koşulduğunu göstermez. · d) Satırlar aynı müşterinin ardışık işlem adımları değildir; farklı koşullar için bağımsız ücret kurallarıdır.

*Kaçırdıysanız tekrar edin: İş birliğine dayalı test yaklaşımları | Tuzak: Near-miss karışıklığı | LO: FL-4.5.2 (K2)*

[Kılavuzda tekrar edin: İş birliğine dayalı test yaklaşımları](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-5-2)

**Soru 34 — Doğru cevap: a**

**Neden doğru:** Test ilerleme raporu, test sürerken durumun anlaşılmasını ve gerektiğinde kontrol kararları alınmasını destekler. Engellenen testler hakkında bilgi, takvim, kaynak veya plan değişikliğine temel sağlar.

**En cazip yanlış (near-miss) — d:** İlerleme raporları da çıkış kriterlerine doğru ilerlemeyi gösterebilir; bu yüzden seçenek yakın görünür. Ancak son kalite değerlendirmesiyle testi kapatma, sürmekte olan testte ortam engelini raporlamanın amacı değildir.

**Diğer şıklar:** b) Alınan derslerin kapanışta derlenmesi başka bir amaçtır; buradaki bilgi devam eden testi yönlendirmek içindir. · c) İlerleme raporu tek tek hata raporlarının ve yeniden üretme adımlarının yerine geçmez.

*Kaçırdıysanız tekrar edin: Test gözetimi, kontrolü ve tamamlama | Tuzak: Near-miss karışıklığı | LO: FL-5.3.2 (K2)*

[Kılavuzda tekrar edin: Test gözetimi, kontrolü ve tamamlama](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-3-2)

**Soru 35 — Doğru cevap: b**

**Neden doğru:** Teftiş, genel gözden geçirme sürecini tümüyle uygulayan en resmî gözden geçirme çeşididir. Çok sayıda anomali bulma amacı, süreç iyileştirme metrikleri ve yazarın lider/katip olamaması birlikte bu türe işaret eder.

**En cazip yanlış (near-miss) — a:** Teknik gözden geçirmede de bireysel hazırlık ve uzman katılımı bulunabilir. Ancak bütün verilen özellikler birlikte değerlendirildiğinde odak, teknik karar üzerinde uzlaşmadan çok teftişe özgü sistemli anomali bulmadır.

**Diğer şıklar:** c) Üzerinden geçme yazarın yönlendirdiği incelemedir; kökte verilen bütün süreç özellikleri ve amaç bu türün yerine teftişi tanımlar. · d) Gayri resmi gözden geçirme tanımlı tam süreç gerektirmez; kökte süreç ve metrikler açıkça verilmiştir.

*Kaçırdıysanız tekrar edin: Geri bildirim ve gözden geçirme süreci | Tuzak: Near-miss karışıklığı | LO: FL-3.2.4 (K2)*

[Kılavuzda tekrar edin: Geri bildirim ve gözden geçirme süreci](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-3.html#fl-3-2-4)

**Soru 36 — Doğru cevap: a**

**Neden doğru:** ATDD testleri, uygulama geliştirilmeden önce kabul kriterlerinden türetilir. Adım adım: kriterde üyelik ve 500 üzerinde tutar koşullarını belirleyin; 520 ve üye girdilerinin ikisini de karşıladığını kontrol edin; vaat edilen çıktıyı sıfır kargo ücreti olarak yazın.

**En cazip yanlış (near-miss) — d:** Üyelik gerçekten kriterin koşullarından biri olduğu için seçenek makuldür. Ancak 500 üzerinde tutar koşulunu düşürerek ücretsiz kargo kuralını bütün siparişlere genişletir.

**Diğer şıklar:** b) Veritabanına kayıt, kriterde vaat edilen sonuç değildir; uygulamanın bir yan etkisini test eder. · c) Ne üyelik ne tutar koşulu sağlanır; bu kriter bu girdiler için ücretsiz kargo vaat etmez.

*Kaçırdıysanız tekrar edin: İş birliğine dayalı test yaklaşımları | Tuzak: Prosedür hatası | LO: FL-4.5.3 (K3)*

[Kılavuzda tekrar edin: İş birliğine dayalı test yaklaşımları](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-5-3)

**Soru 37 — Doğru cevap: c**

**Neden doğru:** Yüksek bağımsızlık, test uzmanlarının ekip iletişiminden yalıtılmasına yol açabilir. Gereksinim değişikliklerini geç öğrenmek, bu yalıtılmanın somut olumsuz sonucudur.

**En cazip yanlış (near-miss) — a:** Varsayımları sorgulamak işin ilerlemesini etkileyebileceği için sakınca sanılabilir. Ancak seçenek çelişkilerin onaydan önce giderilmesini anlatıyor; bu bağımsız bakışın bir faydasıdır.

**Diğer şıklar:** b) Farklı varsayımlar sayesinde farklı arızaları bulmak bağımsızlığın faydasıdır. · d) Geliştiricilerin kendi testlerini yapması, daha sonraki bağımsız testle birlikte kullanılabilen bir uygulamadır; burada bir iletişim sakıncası yoktur.

*Kaçırdıysanız tekrar edin: Testte temel beceriler ve iyi uygulamalar | Tuzak: Near-miss karışıklığı | LO: FL-1.5.3 (K2)*

[Kılavuzda tekrar edin: Testte temel beceriler ve iyi uygulamalar](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-5-3)

**Soru 38 — Doğru cevap: c**

**Neden doğru:** Yapılandırma yönetimi, test öğeleri ve test çalışma ürünlerinin benzersiz tanımlanmasını, sürümlerinin yönetilmesini ve açıkça referans verilmesini destekler. Rapor test edilen derlemeyi ve kullanılan test grubu sürümünü belirttiğinde kanıt izlenebilir hale gelir.

**En cazip yanlış (near-miss) — a:** Otomatik araçlar ayrıntılı koşum raporları üretebildiği için daha fazla otomasyon çözüm gibi görünebilir. Ancak sürüm kimlikleri kaydedilmiyorsa ayrıntılı rapor da hangi sürümlerin test edildiği boşluğunu gidermez.

**Diğer şıklar:** b) Daha sıkı çıkış kriterleri kalite eşiğini değiştirir; eksik sürüm kimliklerini rapora eklemez. · d) Yeniden üretme adımları tekil bir hata raporuna hizmet eder; başarılı regresyon koşumunun hangi sürümlerle yapıldığını belgelemekten farklıdır.

*Kaçırdıysanız tekrar edin: Yapılandırma yönetimi | Tuzak: Near-miss karışıklığı | LO: FL-5.4.1 (K2)*

[Kılavuzda tekrar edin: Yapılandırma yönetimi](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-4-1)

**Soru 39 — Doğru cevap: a**

**Neden doğru:** Beklenen sonuç, test esasından bu girdilere uygulanarak türetilmiş somut gözlem olmalıdır. Adım adım: 527,40 / 10 = 52,74; yalnız tam onluklar sayıldığı için 52 puan kazanılır. Kalan 7,40 yeni bir puan oluşturmaz.

**En cazip yanlış (near-miss) — b:** 53, 52,74 sonucunu yukarı yuvarlayarak bulunur. Gereksinim yuvarlama değil her tam 10,00 birimini saymayı istediği için bu sonuç yanlıştır.

**Diğer şıklar:** c) Doğru puan sayısı ifadesi genel beklentiyi anlatır, ancak sorunun istediği doğrudan karşılaştırılabilir somut gözlemi vermez. Bu girdiler için beklenen 52 puan açıkça yazılmalıdır. · d) Hesaplamanın düzeltilmesi bir çözüm önerisidir; kullanıcıya görünmesi gereken beklenen sonuç değildir.

*Kaçırdıysanız tekrar edin: Hata yönetimi | Tuzak: Prosedür hatası | LO: FL-5.5.1 (K3)*

[Kılavuzda tekrar edin: Hata yönetimi](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-5-1)

**Soru 40 — Doğru cevap: d**

**Neden doğru:** Test otomasyonu başlangıç geliştirmesinin yanında bakım eforu da gerektirir. Ekran değişiklikleri sonrası betiklerin sürdürülmesi için gereken eforun planı aşması, bu eforun eksik tahmin edilmesi riskini gösterir.

**En cazip yanlış (near-miss) — b:** Kırılgan betikler, otomasyon seçiminin yanlış olduğu izlenimini verebilir. Ancak regresyon testi otomasyonun uygun kullanım alanlarından olabilir; kök, manuel testin daha uygun olduğunu değil bakım planının yetersizliğini göstermektedir.

**Diğer şıklar:** a) Senaryoda tedarikçinin kapanması veya aracı bırakmasıyla ilgili bir bilgi yoktur. · c) Araç sonuçlarına eleştirmeden güvenmek ayrı bir risktir; burada ekip kırılan betikleri fark etmekte, bakım eforuyla karşılaşmaktadır.

*Kaçırdıysanız tekrar edin: Test otomasyonunun faydaları ve riskleri | Tuzak: Kaynak bilgi eksiği | LO: FL-6.2.1 (K1)*

[Kılavuzda tekrar edin: Test otomasyonunun faydaları ve riskleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-6.html#fl-6-2-1)


## Sınav günü kontrol listesi

- Sağlayıcınızın güncel sınav dilini, süreyi ve varsa ek süre hakkınızı kontrol edin.
- Kimlik ve teknik hazırlık koşullarını, bağlantı ve kamera gereksinimlerini tamamlayın.
- Başlamadan önce soru ve puanlama talimatlarını okuyun.
- Tek seçimli ve varsa çok seçimli sorularda istenen seçenek sayısına dikkat edin; bu denemenin bütün soruları tek seçimlidir.
- Uzayan soruyu işaretleyip süre izin veriyorsa geri dönün.
- Teslimden önce boş soruları ve işaretlediğiniz cevapları kontrol edin.

## Kaynakça

- ISTQB®, *Certified Tester Foundation Level Syllabus v4.0.1*, 15 Eylül 2024. Telif: ISTQB ve belgede belirtilen yazarlar. [Resmî CTFL sayfası](https://www.istqb.org/certifications/certified-tester-foundation-level-ctfl-v4-0/).
- ISTQB®, *Exam Structure Tables v1.18*, 27 Mayıs 2026; CTFL v4.0 tablosu. [ISTQB sınav belgeleri](https://www.istqb.org/).
- ISTQB®, *Exam Structures and Rules v1.2*, 2 Mayıs 2025. [ISTQB](https://www.istqb.org/).
- TTB, *Temel Seviye Ders Programı v4.0.1* Türkçe çevirisi ve *Yazılım Testi Terimler Sözlüğü v2*. [TTB hazırlık belgeleri](https://www.turkishtestingboard.org/foundation-level/).
- Kadir Çamoğlu, *ISTQB® CTFL® v4.0 Sınav Rehberi: Sıfırdan Sınava Hazır Seviyeye*, Deneme Sınavı 1. [Türkçe kılavuz](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/).

CTFL v4.0.1 ders programı yazarları: Renzo Cerquozzi, Wim Decoutere, Jean-François Riverin, Arnika Hryszko, Martin Klonk, Meile Posthuma, Eric Riou du Cosquer, Adam Roman, Lucjan Stapp, Stephanie Ulrich ve Eshraka Zakaria. v4.0 yazarları ayrıca Klaudia Dussa-Zieger, Michaël Pilaeten ve Stuart Reid'i içerir. Ders programı ve bu belgeden kullanılan kavram adları ISTQB'nin hakları saklı materyalidir.

Sürüm: 19 Ekim 2026 · Geri bildirim: [kadir.camoglu@gmail.com](mailto:kadir.camoglu@gmail.com).

