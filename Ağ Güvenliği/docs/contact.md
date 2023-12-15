### Profil

XYZ Şirketi, küçük ve orta ölçekli bir kuruluştur. Ancak, şirketin iş sürekliliği ve müşteri verilerinin güvenliği konusunda ciddi endişeler bulunmaktadır. Şirket, müşteri bilgilerini barındıran bir ağa sahiptir ve bu nedenle ağ güvenliği, şirketin başarı ve güvenilirliği için kritik bir rol oynamaktadır.

### Ağ Güvenliği Sorunları

1.Eksik Temel Güvenlik Uygulamaları

Güvenlik duvarları, IDS/IPS, antivirüs yazılımları gibi temel güvenlik uygulamaları yetersiz veya güncelliğini yitirmiştir.

2.Belirsiz Ağ Güvenliği Politikaları

Şirket, ağ güvenliği konusunda net bir politikaya sahip değildir. Çalışanlar arasında güvenlik bilinci düşüktür.

### Çözüm Yolları

1.Güvenlik duvarları

Gelen ve giden trafiği filtrelemek için ağ çevresine sağlam bir güvenlik duvarı uygulanmalıdır.

Güvenlik duvarını varsayılan olarak tüm trafiği reddedecek ve yalnızca gerekli hizmetlere izin verecek şekilde yapılandırılmalıdır.

Değişen ağ gereksinimlerine ve ortaya çıkan tehditlere göre güvenlik duvarı kurallarını düzenli olarak güncellemek gerekir.

2.Saldırı Tespit Sistemi (IDS) / Saldırı Önleme Sistemi (IPS)

Ağ ve/veya sistem etkinliklerini kötü amaçlı etkinliklere veya güvenlik politikası ihlallerine karşı izlemek için bir IDS(Snort, Nmap) kurulmalıdır.

IDS şüpheli davranış tespit edildiğinde uyarı oluşturacak veya önceden tanımlanmış eylemleri gerçekleştirecek şekilde yapılandırılmalıdır.

Kötü amaçlı etkinlikleri yalnızca tespit etmekle kalmayıp aynı zamanda etkin bir şekilde önleyen ve engelleyen bir IPS'ye yükseltme yapılması gerekebilir.

3.Ağ İzleme ve Günlük Kaydı:

Ağ trafiğini takip etmek ve anormal davranış kalıplarını belirlemek için ağ izleme araçları kullanılmalıdır.

Analiz amacıyla etkinliklerin kaydını tutmak için ağ aygıtlarında ve sunucularda oturum açılması gerekir.

Günlükleri anormalliklere karşı düzenli olarak incelenmeli ve olağandışı kalıplar veya olaylar araştırılmalıdır.

4.Güvenlik Açığı Taraması

Potansiyel güvenlik zayıflıklarını belirlemek için ağ cihazları ve sistemleri üzerinde düzenli güvenlik açığı taramaları gerçekleştirilmelidir.

Kötüye kullanım riskini azaltmak için tespit edilen güvenlik açıkları belirlenmeli, önceliklendirilmeli ve çözülmelidir.

5.Güvenlik Bilgileri ve Olay Yönetimi (SIEM):

Çeşitli güvenlik araçlarından gelen bilgileri toplamak ve ilişkilendirmek için bir SIEM çözümü oluşturulmalıdır.

Ağ genelindeki güvenlik olaylarının merkezi bir görünümünü sağlayan uyarılar ve raporlar oluşturmak için SIEM kullanılabilir.

6.Antivirüs ve Kötü Amaçlı Yazılımdan Koruma Çözümleri:

Tüm ağ cihazlarına antivirüs ve kötü amaçlı yazılımdan koruma yazılımları yüklenmeli ve düzenli olarak güncellenmelidir.

Kötü amaçlı yazılımları tespit etmek ve kaldırmak için düzenli taramalar yapılmalıdır.

7.Kullanıcı Eğitimi ve Farkındalığı

Kullanıcılar kötü amaçlı yazılımlara, sahte adreslere ve postalara karşı uyarılmalıdır.

Kullanıcılar kimlik avına karşı bilgilendirilmelidir.

8.Yama Yönetimi

Tüm yazılım ve sistemlerin en son güvenlik yamalarıyla güncel olmasını sağlamak için bir yama yönetimi süreci oluşturulmalıdır.

9.Ağ Segmentasyonu

Kritik sistemleri izole etmek ve bir güvenlik ihlalinin potansiyel etkisini sınırlamak için ağ bölümlendirmesini uygulanması savunmayı arttırır.

10.Şifreleme

Aktarılan verileri güvence altına almak için şifreleme protokolleri (ör. TLS/SSL) kullanılabilir.

Sunucularda ve diğer cihazlarda depolanan hassas bilgileri şifrelenmelidir.

11.Sürekli İzleme

Güvenlik devam eden bir süreçtir. Ağ ortamında ortaya çıkan tehditlere ve değişikliklere göre güvenlik önlemlerini düzenli olarak yeniden değerlendirmek ve alınan verilere göre sistemleri güncellemek gereklidir. 

## Kullanılabilecek Araçlar

Snort, Nmap, Wireshark sistem ağını takip etmek, paketleri incelemek, izinsiz girişleri tespit etmek için kullanılabilir.

Cisco NGIPS veya OSSEC(open-source) IDS sistemler ile sisteme dışardan yapılan hareketlere müdahale edilebilir.

SIEM için SolarWinds kullanılabilir.


## Kaynakça

https://www.comparitech.com/

https://www.infosectrain.com/

https://www.cisco.com/