# Büyük Ölçekli Kullanıcı Verileri Üzerinden Telekomünikasyon Sektöründe Marka Algısı ve Dijital İtibar Analizi: Turkcell
*(Web Madenciliği & Duygu Analizi Projesi)*

---

## 1. GİRİŞ VE ARAŞTIRMA PROBLEMİ
Günümüzde telekomünikasyon sektörü, dijital dönüşümün merkezinde yer almakta; kullanıcı deneyimleri ve marka algıları sosyal medya ve çevrimiçi platformlar aracılığıyla anlık olarak kamusal hale gelmektedir. Bu çalışma, Türkiye telekomünikasyon sektörünün önde gelen markalarından biri olan **Turkcell**’in dijital ekosistemdeki itibarını; yapılandırılmamış kullanıcı yorumları üzerinden, veri madenciliği ve duygu analizi teknikleriyle incelemeyi amaçlamaktadır.

Araştırma, işletme stratejileri ve pazarlama iletişimi açısından kritik öneme sahip aşağıdaki üç temel soruya odaklanmaktadır:

- **Pazar Psikolojisi:** Makro düzeyde tüketici güveni, yeni bir ürün veya hizmet lansmanı için uygun bir psikolojik zemin sunmakta mıdır?

- **Söylemsel Konumlandırma:** Marka algısı dijital medya anlatılarında ağırlıklı olarak fırsat ve inovasyon ekseninde mi, yoksa risk ve kriz ekseninde mi kümelenmektedir?

- **Kullanıcı Kaygıları:** Tüketici zihninde öne çıkan temel algısal bariyerler nelerdir ve bu bariyerler etkili iletişim stratejileri aracılığıyla nasıl güvene dönüştürülebilir?
---

## 2. METODOLOJİK ÇERÇEVE VE VERİ SETİNİN OLUŞTURULMASI

Bu çalışmada, Turkcell markasının dijital itibarını çok boyutlu bir perspektiften ölçümlemek amacıyla Çoklu Kanal Veri Madenciliği yaklaşımı benimsenmiştir. Analiz süreci, tek bir platforma dayalı incelemelerin yol açabileceği örneklem yanlılığını minimize etmek amacıyla, kullanıcıların marka ile etkileşime geçtiği farklı dijital ekosistemleri kapsayacak şekilde tasarlanmıştır.

Bu bağlamda, marka algısının yalnızca sorun bildirimi üzerinden değil; aynı zamanda medya söylemi ve fiziksel hizmet deneyimi boyutlarıyla birlikte ele alınması hedeflenmiştir.

### 2.1 Veri Kaynakları ve Temsil Kabiliyeti

Araştırma kapsamında seçilen veri kaynakları, Turkcell markasının dijital varlığını üç temel algısal boyutta temsil edecek şekilde belirlenmiştir:

- **Şikayetvar (8.875 Yorum):**
Kullanıcıların doğrudan hizmet aksaklıklarını raporladığı bu platform, markanın operasyonel zayıflıklarını ve kriz noktalarını tespit etmek amacıyla kriz odaklı örneklem grubu olarak değerlendirilmiştir.

- **Ekşi Sözlük (8.401 Yorum):**
Kullanıcıların deneyimlerini daha serbest, eleştirel ve çoğu zaman ironik bir dil ile aktardıkları bu mecra, markanın kurumsal imajı ve toplumsal söylem içerisindeki konumunu analiz etmek için kullanılmıştır.

- **Google Maps (4.421 Yorum):**
Fiziksel hizmet noktalarına (bayiler ve iletişim merkezleri) yönelik kullanıcı deneyimlerini yansıtan bu platform, dijital algının saha operasyonları ve yüz yüze hizmet kalitesiyle ne ölçüde örtüştüğünü incelemek amacıyla analiz kapsamına alınmıştır.

Bu çok kaynaklı yapı sayesinde, Turkcell markasına yönelik algı yalnızca dijital şikâyet perspektifiyle sınırlı kalmamış; algı, söylem ve deneyim boyutları birlikte değerlendirilmiştir.

### 2.2 Veri Ön İşleme (Data Preprocessing) ve Normalizasyon

Toplanan ham veriler, analiz sürecine geçilmeden önce sistematik bir ön işleme sürecinden geçirilmiştir. Bu süreçte uygulanan adımlar aşağıda özetlenmiştir:

- **Metin Temizleme:**   
URL bağlantıları, kullanıcı etiketleri (@mention), emoji-only içerikler ve anlamsız karakter dizileri veri setinden temizlenmiştir.

- **Gürültü Azaltma:**    
Bağlamsal anlam taşımayan çok kısa yorumlar ile yinelenen (duplicate) içerikler veri setinden ayıklanmıştır.

- **Veri Kaybı Kontrolü:**    
Temizleme süreci agresif bir filtreleme yaklaşımıyla yürütülmemiş; yorumların temel duygu ve anlam yapısını bozmayacak şekilde yalnızca teknik gürültü giderilmiştir.

Bu yaklaşım sayesinde, analiz sürecinde kullanılacak verinin hem kalitesi artırılmış, hem de istatistiksel temsil gücü korunmuştur.

### 2.3 Nicel Veri Dağılımı ve Analize Hazırlık

Veri madenciliği ve ön işleme süreçleri sonucunda, toplam 21.697 ham yorum içerisinden 20.556 temiz ve analiz edilebilir yorum elde edilmiştir. Bu hacim, gerçekleştirilen duygu analizi ve tematik incelemelerin istatistiksel açıdan güvenilir sonuçlar üretmesine olanak sağlamaktadır.

Elde edilen temiz veri seti, duygu analizi, kriz–güven dengesi ölçümü ve stratejik performans değerlendirmeleri için analize hazır hale getirilmiştir.  

<img width="889" height="490" alt="temiz veriler" src="https://github.com/user-attachments/assets/9c09b596-d83a-44b6-a419-ca9949cee247" />
  
 > *Şekil 1 : Bu tablo, veri ön işleme sürecinde gerçekleştirilen filtreleme adımlarının veri hacmi üzerindeki etkisini göstermektedir.Temizleme süreci, duygu ve bağlam kaybına yol açmayacak şekilde kontrollü olarak uygulanmıştır.*

---
## 3. ARAŞTIRMA BULGULARI VE STRATEJİK ANALİZ

Bu bölümde, ön işlemesi tamamlanmış 20.554 temiz yorum üzerinden elde edilen bulgular; pazar psikolojisi, kriz–güven dengesi ve marka algısı ekseninde analiz edilmiştir. Bulgular, yalnızca betimleyici istatistiklerle sınırlı kalmayıp, stratejik çıkarımlar üretmeyi amaçlamaktadır.

### 3.1 Genel Duygu Dağılımı ve Pazar Psikolojisi

İlk aşamada, analiz kapsamındaki yorumların genel duygu dağılımı incelenerek, Turkcell markasına yönelik makro düzeydeki tüketici psikolojisi ölçümlenmiştir.

Yapılan duygu analizi sonucunda elde edilen dağılım aşağıda sunulmaktadır:

- Negatif: 10.430 yorum

- Nötr: 5.762 yorum

- Pozitif: 4.362 yorum

Bu dağılım, yorumların önemli bir kısmının negatif eğilimli olduğunu göstermektedir. Nötr yorumların yüksek oranı ise kullanıcıların önemli bir bölümünün kararsız veya beklenti içinde olduğunu ortaya koymaktadır.
> *Bu durum, pazarda mutlak bir memnuniyetsizlikten ziyade, çözüm bekleyen bir kullanıcı kitlesinin varlığına işaret etmektedir.*
<img width="1653" height="1779" alt="duygu_donut" src="https://github.com/user-attachments/assets/ba125dd7-0677-426c-8272-e4e7ea5793e2" />

> *Şekil 2 : Turkcell markasına ilişkin kullanıcı yorumlarının pozitif, nötr ve negatif dağılımını göstermektedir.*

### 3.2 Güven – Kriz Endeksi Analizi

Genel duygu dağılımının ötesine geçebilmek amacıyla, pozitif ve negatif yorumlar arasındaki dengeyi yansıtan Güven–Kriz Endeksi hesaplanmıştır. Bu endeks, markanın mevcut psikolojik atmosferinin hangi eksende konumlandığını göstermek amacıyla geliştirilmiştir.

Endeks hesaplamasında, pozitif ve negatif yorumların toplam içindeki farkı esas alınmıştır. Elde edilen skor, Turkcell markasının algısal olarak kriz bölgesine daha yakın bir konumda bulunduğunu göstermektedir.

<img width="2079" height="578" alt="guven_kriz_endeksi" src="https://github.com/user-attachments/assets/2b5441c7-68e8-4681-8a0f-5d12606ee765" />

> *Şekil 3 : Endeks değeri, markanın tamamen bir kriz atmosferinde olmadığını; ancak güven üretmek için iletişim ve hizmet tarafında yapısal iyileştirmelere ihtiyaç duyduğunu göstermektedir.*

### 3.3 Kategori Bazlı Algı Analizi

Genel duygu skorları, kullanıcıların hangi konularda memnun veya rahatsız olduğunu tek başına açıklamakta yetersiz kalmaktadır. Bu nedenle analiz, kategori bazlı bir yaklaşımla derinleştirilmiştir.

Bu kapsamda Turkcell markası beş temel performans kriteri üzerinden değerlendirilmiştir:

**1.** Hız / Fiber Erişimi

**2.** Fiyat / Tarife Politikası

**3.** Şebeke / Kapsama Alanı

**4.** Müşteri İlişkileri

**5.** Dijital Servisler

Her kategoriye ilişkin kullanıcı yorumları analiz edilerek algısal performans skorları hesaplanmıştır. 
   
<img width="706" height="677" alt="karnesi" src="https://github.com/user-attachments/assets/5266dc40-1342-4b44-ae5d-8b5064049b19" />

> *Şekil 4 : Kullanıcı yorumları üzerinden elde edilen kategori bazlı algı skorlarını göstermektedir.*

### 3.4 Halkın Gündemindeki Temel Korkular ve Algısal Bariyerler

Negatif yorumlar üzerinde yapılan derinlemesine tematik analiz (Topic Modeling), kullanıcıların Turkcell markasına karşı geliştirdiği direncin temelinde yatan üç ana "korku" odağını ortaya koymaktadır:

- **Ekonomik Öngörülemezlik Korkusu:** Fiyat artışlarının ve taahhüt yenileme süreçlerinin şeffaf olmaması, kullanıcıda "istismar edilme" kaygısı yaratmaktadır.

- **Dijital Yalnızlık (Muhatapsızlık) Korkusu:** Müşteri hizmetlerine erişimde yaşanan zorluklar, bir sorun yaşandığında "karşısında insan bulamama" korkusunu tetiklemektedir.

- **Hizmet Sürekliliği Kaygısı:** Şebeke ve kapsama alanı sorunları, dijital dünyadan kopma ve "yarı yolda kalma" korkusuyla eşleşmektedir.  

<img width="1149" height="697" alt="wordcloud" src="https://github.com/user-attachments/assets/e2222d5a-0e3d-489a-9519-0672f141c797" />

      
> *Şekil 5 :  Turkcell markasına ilişkin kullanıcı söyleminde öne çıkan kavramları göstermektedir.*
---

## 4. STRATEJİK YORUM VE YÖNETİMSEL ÇIKARIMLAR
Bu bölümde, önceki analizlerde elde edilen bulgular ışığında, Turkcell markasının mevcut algısal konumu değerlendirilmiş ve tespit edilen tüketici kaygılarının yönetimsel ve iletişimsel stratejilerle nasıl güvene dönüştürülebileceği ele alınmıştır. Amaç, yalnızca mevcut durumu betimlemek değil; aynı zamanda veriye dayalı stratejik öneriler sunmaktır.

### 4.1 Tüketici Algısında Baskın Korkuların Yorumu

Yapılan duygu analizi, kelime bulutu ve bağlamsal frekans analizleri; tüketici söylemlerinin belirli temalar etrafında yoğunlaştığını göstermektedir. Özellikle negatif yorumlarda öne çıkan kavramlar, kullanıcıların temel endişe alanlarını net biçimde ortaya koymaktadır.

Analiz sonuçlarına göre Turkcell özelinde öne çıkan başlıca algısal risk alanları şunlardır:

- **Hizmet Kalitesi ve Süreklilik Kaygısı** (çekmiyor, yavaş, kesinti)

- **Fiyatlama ve Tarife Politikaları** (pahalı, zam, fatura)

- **Müşteri Hizmetlerine Erişim ve Çözüm Eksikliği**

- **Dijital Servislerde Beklenti–Gerçeklik Uyumsuzluğu**

Bu bulgular, kullanıcıların markayı tamamen reddetmediğini; ancak belirli hizmet başlıklarında tatmin olmamış ve temkinli bir tutum sergilediğini göstermektedir. Özellikle nötr duygu grubunun büyüklüğü, bu kitlenin ikna edilebilir ve güven inşasına açık olduğunu ortaya koymaktadır.

### 4.2 Kriz–Güven Dengesi ve Algısal Konumlandırma

Bu çalışmada oluşturulan **Güven–Kriz Endeksi**, markanın dijital algısının mutlak bir kriz durumunda olmadığını; ancak güçlü bir güven atmosferi de üretmediğini göstermektedir.

Endeksin orta banda yakın konumlanması şu şekilde yorumlanabilir:

- Marka, kullanıcı zihninde “vazgeçilmez ama sorunlu” bir konumdadır.

- Algı, ani bir krizden ziyade birikimli memnuniyetsizlik üzerinden şekillenmektedir.

- Bu durum, yanlış iletişim stratejileriyle krize dönüşme riski taşırken; doğru yönetildiğinde sadakat fırsatına dönüşebilir.

 ***Bu bağlamda Turkcell için asıl risk, olumsuz söylemlerin kendisinden ziyade, bu söylemlerin cevapsız kalmasıdır.***

### 4.3 Reklam ve İletişim Stratejileri: Korkuyu Güvene Dönüştürmek

Analiz bulguları doğrultusunda, Turkcell’in iletişim stratejilerinde aşağıdaki yaklaşımları benimsemesi önerilmektedir:

**Şeffaflık ve Hesap Verebilirlik Vurgusu**

Kullanıcıların önemli bir kısmı, sorunların varlığından ziyade bu sorunlara verilen tepkilerden memnuniyetsizdir. Bu nedenle iletişim dilinde:

- *Açık problem kabulü*

- *Net çözüm süreleri*

- *Somut iyileştirme verileri*

öne çıkarılmalıdır.

**İnsan Odaklı Hizmet Anlatısı**

Müşteri hizmetleri ve bayi deneyimi, analizde en çok eleştirilen alanlardan biridir. Bu durum, iletişimde:

- Gerçek çalışan hikâyeleri

- Saha operasyonlarından örnekler

- “Gerçek insan, gerçek çözüm” vurgusu

ile dengelenmelidir.

**Dijital Servislerin Yeniden Konumlandırılması**

Dijital servisler (BiP, Salla Kazan vb.) kullanıcılar tarafından tamamen reddedilmemekte; ancak beklenti yönetimi zayıf kalmaktadır. Bu nedenle:

- Abartılı vaatlerden kaçınılmalı

- Net fayda anlatımı yapılmalı

- Kullanıcı deneyimi sadeleştirilmelidir

### 4.4 Yönetimsel Değerlendirme

Bu çalışma, büyük ölçekli kullanıcı verilerinin yalnızca teknik analizler için değil; aynı zamanda stratejik karar destek mekanizması olarak da kullanılabileceğini göstermektedir.

Elde edilen bulgular, Turkcell için şu temel çıkarımı ortaya koymaktadır:

> *Marka, güven kaybetmiş değil; ancak güven üretmek zorundadır.*

Bu nedenle yeni ürün lansmanları ve iletişim kampanyaları, agresif büyüme söylemlerinden ziyade; **istikrar, şeffaflık ve kullanıcıyı merkeze alan** bir anlatı üzerine inşa edilmelidir.
## 5. SONUÇ
Bu çalışma, Turkcell markasının dijital ekosistemdeki algısını Şikayetvar, Ekşi Sözlük ve Google Maps platformlarından toplanan büyük ölçekli kullanıcı verileri üzerinden incelemiştir. Veri madenciliği ve duygu analizi teknikleri kullanılarak elde edilen bulgular, markanın dijital itibarının karmaşık bir yapı sergilediğini göstermektedir.

Analiz sonuçları, genel bir kriz veya güven durumu beklentisinin aksine, negatif söylemlerin belirli tematik alanlarda yoğunlaştığını ve nötr duygu grubunun baskın olduğunu ortaya koymuştur. Bu durum, tüketicilerin markaya karşı kesin bir olumsuzluk beslemediğini; ancak deneyimlerini gözlemleyerek karar vermeyi tercih ettiğini işaret etmektedir.

Markanın algısal konumu orta bantta yer almakta olup, ani bir krizden ziyade birikimli memnuniyetsizlik riski taşımaktadır. İletişim stratejilerinin büyüme odaklı söylemler yerine güven inşa etmeye yönelik yaklaşımlara öncelik vermesi önerilmektedir.

Kullanıcı algısı özellikle fiyatlandırma, müşteri hizmetleri ve şebeke deneyimi gibi alanlarda dalgalanma gösterirken, dijital servisler ve hız/fiber altyapısı potansiyel fırsatlar sunmaktadır. Tüketiciler, sorunların kabul edilmesini ve şeffaf bir iletişimle çözüme yönelik adımlar atılmasını talep etmektedir.

Sonuç olarak, bu çalışma, büyük ölçekli kullanıcı verilerinin stratejik yönetim kararlarını destekleyen değerli bir kaynak olduğunu göstermektedir. Elde edilen bulgular, telekomünikasyon sektöründeki diğer markalar için de dijital itibar yönetimi süreçlerinde yol gösterici niteliktedir.

**Öneriler: Turkcell'in güven inşa etme zorunluluğu bulunmaktadır. Yeni ürün ve hizmetlerin pazarlanmasında kullanıcı deneyimini merkeze alan, şeffaflık vurgusu yüksek ve çözüm odaklı bir iletişim stratejisinin benimsenmesi önemlidir.**


## 👩🏻‍💻 Proje Sahibi

**Hazırlayan :** Ülkü Aydın  
  
**Metodoloji:** Multi-Source Data Mining, Selenium-Based Web Scraping, Lexicon-Assisted Sentiment Analysis, Contextual Keyword Analysis, Visual Analytics
    
**Ödev Tarihi:** 2025-2026
