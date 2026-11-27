# ENGG434 Mühendislik Etiği Dönem Projesi — Vaka 2 ve Vaka 7

Bu depo, Lefke Avrupa Üniversitesi Mühendislik Fakültesi'nde 2025–2026 Bahar döneminde aldığım ENGG434 Engineering Ethics dersinin grup dönem projesini içerir. 15. gruptuk. Dokuz vaka arasından ikisini seçtik: Vaka 2 (yol şeridi genişliği ve kamu güvenliği) ve Vaka 7 (güvenlik yazılımının yurt dışına gönderilmesi).

Bu herkese açık kopyada öğrenci numaraları, diğer grup arkadaşlarının adları ve toplantı fotoğrafları ile ekran görüntüleri çıkarılmıştır. Ders brifi ve kullanmadığımız diğer vaka dosyaları da buraya konmadı.

## Benim katkım

Rapordaki görev dağılımına göre Case 2 için etik kod ve standart araştırmasını ben yaptım. NSPE Code of Ethics maddelerini vakaya uyguladım, ilgili teknik standartları (AASHTO Green Book, MUTCD, Highway Capacity Manual) ve Türkiye'deki karşılıklarını (KGM, TSE, TMMOB) derledim. Bu çalışmanın ayrı dosyası `codes/` klasöründe.

Projenin geri kalanı (vaka araştırması, tartışma ve sonuç yazımı, Case 7 analizi, sunum ve düzenleme) grup çalışmasıdır.

## Vaka 2 — Yol şeridi standartları ve kamu güvenliği

Kaynak, NSPE Board of Ethical Review Case No. 15-11: [Public Health and Safety — Engineer’s Duty to Adhere to Codes, Standards and Guidelines](https://www.nspe.org/career-growth/ethics/board-ethical-review-cases/public-health-safety-engineer-s-duty-adhere-codes). Ders metninde ölçü birimleri metreye çevrilmiş: mevcut şerit 3.35 m, önerilen 3.65 m. Orijinal BER vakasında bu değerler 11 ft ve 12 ft.

Özet: Greenhaven şehrinin mühendisi Engineer A, trafik verisi, kaza geçmişi ve mühendislik standartlarına bakarak şeritlerin 3.35 metreden 3.65 metreye çıkarılmasını öneriyor. Bunun için kamulaştırma (right of way) da gerekiyor. Belediye meclisi öneriyi reddedip mevcut şerit düzeniyle devam etmesini istiyor. Soru: Engineer A'nın bu durumda etik yükümlülüğü nedir?

Temel sorun, kamu güvenliği ile işverenin talimatı arasındaki çatışma.

Analizde kullanılan NSPE maddeleri şunlar:

- I.1 / II.1 — Kamu güvenliği, sağlığı ve refahı her şeyin üzerindedir.
- II.1.a — Mühendisin teknik kararı, hayat veya malı tehlikeye atan şekilde bozulursa işveren ve gerektiğinde yetkili makam bilgilendirilir.
- II.1.b — Yalnızca geçerli standartlara uyan belgeler onaylanır.
- II.3.a — Raporlarda objektif ve doğru olunur; ilgili tüm bilgi yazılır.
- II.4 — İşverene sadık temsilci olunur. Bu, sessizce uymak demek değildir.
- III.2.b — Standarta uymayan plan tamamlanmaz, imzalanmaz veya mühürlenmez. İşveren ısrar ederse yetkili makama bildirilir ve projeden çekilinir.

Teknik dayanak olarak AASHTO Green Book kullanıldı: kentsel arterler için yaklaşık 3.6 m şerit önerilir, 3.3 m ancak düşük hızlı veya kısıtlı koşullarda kabul edilir. Analizde 3.35 m'nin mevcut iyi uygulamanın altında kaldığı belirtiliyor. Ayrıca MUTCD, Highway Capacity Manual, ASCE Code of Ethics, ITE Canons of Ethics ve Türkiye'den KGM Karayolu Tasarım El Kitabı, TSE ve TMMOB mesleki davranış kuralları anıldı.

Sonuç: Engineer A meclise yazılı ve resmi uyarı vermeli, 3.35 m'lik düzeni onaylamamalı veya mühürlememeli, meclis ısrar ederse üst makamlara (ulaştırma kurumu veya mühendislik kurulu gibi) bildirmeli ve gerekirse projeden çekilmelidir. Maliyet veya siyasi gerekçe, kanıta dayanan güvenlik riskinin önüne geçemez. Mühendis yalnızca bir çalışan değil, kamu güvenliğini korumakla yükümlü bir meslek mensubudur.

## Vaka 7 — Güvenlik yazılımı ve ihracat kısıtlamaları

Kaynak, NSPE Board of Ethical Review Case No. 08-1: [Public Welfare — Software Security](https://www.nspe.org/career-growth/ethics/board-ethical-review-cases/public-welfare-software-security).

Özet: Yeni işe alınmış yazılım mühendisi Engineer A, küresel bir şirket olan HyTechCo için şirket içi e-posta belgelerini koruyan bir güvenlik yazılımı yazar. Benzer yazılımı yurt dışına gönderen birinin ulusal güvenlik gerekçesiyle soruşturulduğunu okur. Kendi yazılımının da şirketin yurt dışı ofislerine gönderildiğini öğrenir. Amiri Engineer B, hukuk birimine danışmadan “şirket ABD merkezli, yazılım satılmıyor, yalnızca iç kullanım var, sorun yok” der. Engineer A önce bunu kabul eder, sonra yurt dışı ofislerden birinin müteahhitlere de yazılımı kullandırdığı ortaya çıkar. Soru: Engineer A ve Engineer B'nin etik sorumlulukları nedir?

Bu vaka hem siber güvenlik hem hukuk tarafını bir araya getiriyor. Güçlü güvenlik yazılımı bilgiyi korur, ama bazı ülkelerde şifreleme ve güvenlik yazılımlarının yurt dışına gönderilmesi ihracat kurallarına tabidir. Müteahhit kullanımı başlayınca yazılım artık yalnızca şirket çalışanlarıyla sınırlı kalmaz.

Analizde kullanılan NSPE maddeleri şunlar:

- I.1 — Kamu yararını önde tutmak
- I.6 — Onurlu, sorumlu, etik ve yasal davranış
- II.1.a — Teknik hükmün bozulması halinde bildirim
- II.1.b — Geçerli kurallara uymayan işi onaylamamak
- II.1.e — Hukuka aykırı mühendislik uygulamasına yardım etmemek
- II.4 — İşverene sadık temsilcilik (şirketi hukuki riskten korumak da buna girer)
- III.1.b — Projenin başarısız olabileceğini düşünüyorsa uyarmak
- III.2.b — Bildirim ve gerekirse çekilme
- III.4 — Gizlilik (doğru kanallardan bildirim)
- III.9 — Başkalarının mülkiyet haklarına saygı

Hukuki çerçeve olarak ABD ihracat ve şifreleme kontrolleri (Bureau of Industry and Security ve Encryption Items düzenlemeleri) anıldı.

Sonuç: Engineer A başta iyi niyetle davranmış olsa da yurt dışı ve müteahhit kullanımını öğrendikten sonra susmak etik bir seçenek değildir. Hukuki görüş almadan amirin sözlü güvencesini kabul etmemeli, konuyu üst yönetime veya hukuk birimine taşımalıdır. Engineer B, hukuk danışmanlığı almadan konuyu kapatarak ihmalkar davranmıştır. Yazılım mühendisinin işi yalnızca kod yazmakla bitmez; yazılımın sonradan nasıl kullanıldığı da sorumluluğun parçasıdır.

Her iki vakadaki ortak nokta aynı: mesleki sadakat, güvenlik, hukuk veya standartlarla çelişen bir talimata sessizce uymak anlamına gelmez.

## Dosyalar

- `report/ENGG434-Group15-Case2-Case7-Report.pdf` — Grup raporu. Bu kamu kopyasında öğrenci numaraları, grup arkadaşlarının adları, Microsoft Teams ekran görüntüsü, WhatsApp grup sayfası ve yüzlerin göründüğü toplantı fotoğrafı çıkarılmıştır.
- `presentation/ENGG434-Group15-Case2-Case7-Presentation.pdf` — Grup sunumu. Kapak slaydındaki adlar ve öğrenci numaraları çıkarılmıştır.
- `codes/Case2-Codes-and-Standards.pdf` — Case 2 için hazırladığım kod ve standart analizi. Öğrenci numarası çıkarılmıştır.

Kaynak vakaların tam metni NSPE sitesinde açık:

- Vaka 2 / BER 15-11: https://www.nspe.org/career-growth/ethics/board-ethical-review-cases/public-health-safety-engineer-s-duty-adhere-codes
- Vaka 7 / BER 08-1: https://www.nspe.org/career-growth/ethics/board-ethical-review-cases/public-welfare-software-security

## English

This repository holds my ENGG434 Engineering Ethics term project from the 2025–2026 Spring semester at the European University of Lefke, Faculty of Engineering. I was in Group 15. We analysed two cases taken from the NSPE Board of Ethical Review: Case 15-11 (lane width, design standards, and public safety) and Case 08-1 (security software sent overseas, and later used by contractors).

My own part was the Case 2 codes and standards research: applying the relevant NSPE Code of Ethics sections, and setting out the technical references (AASHTO Green Book, MUTCD, Highway Capacity Manual) together with Turkish counterparts (KGM, TSE, TMMOB). The rest of the report, the Case 7 analysis, and the presentation were group work.

In both cases the conclusion is that loyalty to an employer does not mean silent compliance when safety, the law, or applicable standards are at risk. For Case 2, Engineer A should warn the city council in writing, refuse to approve a nonconforming 3.35 m lane design, and escalate or withdraw if the council insists. For Case 7, Engineer A should not accept informal reassurance without legal review, and Engineer B should not have dismissed the concern without consulting counsel.

Classmate names, student numbers, and meeting photographs have been removed from this public copy.
