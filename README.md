# Solidity

<img src="logo.svg" alt="drawing" width="200"/>

Solidity, akıllı sözleşmelerin uygulanması için geliştirilen nesne yönelimli, üst düzey bir programlama dilidir. Akıllı sözleşmeler, Ethereum ağındaki işlemlerin davranışını yöneten programlardır.

Solidity, C ++, Python ve JavaScript'ten etkilenerek oluşturulmuş ve Ethereum Sanal Makines (ESM)'i hedef alarak tasarlanmıştır.

Solidity statik olarak yazılmıştır. Diğer tüm özelliklerinin yanında, nesneler arası miras ilişkisini, kütüphaneleri ve kullanıcı tanımlı karmaşık türleri desteklemektedir.

Bu dil yardımı ile oylama, kitle fonlaması, açık artırma ve çoklu imza cüzdanları gibi kullanımlar için sözleşmeler oluşturabilirsiniz.

Sözleşmelerin dağıtımını yaparken, en son yayınlanan Solidity sürümünü kullanmalısınız. Bunun nedeni, değişikliklerin yanı sıra yeni özellikler ve hata düzeltmelerinin de düzenli olarak sunulmasıdır. Bu hızlı [değişim ve geliştirmeler sırasında kullandığımız versiyonu belirtmek için](https://semver.org/#spec-item-4) 0.x sürüm numarasını kullanıyoruz.

## Dil Dökümantasyonları

Akıllı sözleşmeler kavramında yeniyseniz, Solidity ile yazılmış bir akıllı sözleşmeyle başlamanızı öneririz. Daha fazla ayrıntıya hazır olduğunuzda, dilin temel kavramlarını öğrenmek için “Solidity Örnekleri” ve “Derinlemesine Solidity” bölümlerini okumanızı öneriyoruz.

Daha fazla bilgi için, blockchain temellerini ve Ethereum Sanal Makinesi'nin detaylarını inceleyebilirsiniz.

### [İpucu](#)

>Tarayıcınızdaki kod örneklerini her zaman Remix IDE ile deneyebilirsiniz. Remix, Solidity ile akıllı sözleşmeler yazmanıza, ardından akıllı sözleşmeleri çalıştırmanıza ve yönetmenize izin veren web tarayıcısı tabanlı bir IDE'dir. Yüklenmesi biraz zaman alabilir, bu yüzden lütfen sabırlı olun.

### [Uyarı](#)

>Yazılımlar insanlar tarafından yazıldığından hatalar içerebilirler. Akıllı sözleşmelerinizi yazarken kabul görmüş yazılım geliştirme kurallarına uymanız tavsiye edilir; buna kod incelemesi, testler, denetimler ve doğruluk kanıtları da dahildir. Akıllı sözleşme kullanıcıları bazen kodlara yazarlarından daha fazla güven duyarlar. Blockchain ve akıllı sözleşmelerde özellikle dikkat edilmesi gereken özel konular olduğundan; geliştirici olarak herhangi bir kod üzerinde çalışmaya başlamadan önce Güvenlikle İlgili Hususlar bölümünü okuduğunuzdan emin olunuz.

Herhangi bir sorunuz varsa, cevap için online kaynaklarda arama yapabilir arayabilir, [Ethereum Stackexchange' de ](https://ethereum.stackexchange.com/) sorabilir veya [glitter kanalımızı](https://gitter.im/ethereum/solidity/) deneyebilirsiniz.

Solidity veya bu dokümantasyonun iyileştirilmesine yönelik fikirler her zaman memnuniyetle karşılanmaktadır Bu konuda daha fazla ayrıntı için [katkıda bulunanlar rehberimizi](https://solidity.readthedocs.io/en/v0.5.3/contributing.html) okuyun.

## Çeviriler

Topluluktan bazı gönüllüler bu belgeyi farklı dillere çevirmekte bizlere yardımcı oluyor. Bu sebeple çeviriler, değişken derecelerde bütünlük ve güncelliğe sahiptir. İngilizce versiyonu ise referans olarak kullanılır.

+ [Simplified Chinese](https://solidity-cn.readthedocs.io/zh/develop/) (yapım aşamasında)
+ [Spanish](https://solidity-es.readthedocs.io/)
+ [Russian](https://github.com/ethereum/wiki/wiki/%5BRussian%5D-%D0%A0%D1%83%D0%BA%D0%BE%D0%B2%D0%BE%D0%B4%D1%81%D1%82%D0%B2%D0%BE-%D0%BF%D0%BE-Solidity) (Süresi Geçmiş)
+ [Korean](http://solidity-kr.readthedocs.io/) (yapım aşamasında)
+ [French](http://solidity-fr.readthedocs.io/) (yapım aşamasında)

## İçerik

+ Akıllı Sözleşmelere Giriş
  - Basit Bir Akıllı Sözleşme
  - Blockchain Temelleri
  - Ethereum Sanal Makinesi
+ Solidity Derleyicisini Yükleme
  - Sürüm
  - Remix
  - Npm / Node.js
  - Docker
  - İkili Paketler
  - Kaynağından Kurulum
  - CMake Seçenekleri
  - Ayrıntılı Sürüm Dizgisi
  - Sürüm Oluşturma Hakkında Önemli Bilgiler
+ Solidty Örnekleri
  - Oylama
  - Kapalı Açık Arttırma
  - Güvenli Uzaktan Satın Alım
  - Mikro Ödeme Kanalı
+ Derinlemesine Solidty
  - Bir Solidity Kaynak Dosyasının Düzeni
  - Sözleşmenin Yapısı
  - Sözleşme Türleri
  - Birimler ve Global Olarak Mevcut Değişkenler
  - İfadeler ve Kontrol Yapıları
  - Sözleşmeler
  - Solidity Assembly
  - Çeşitli
  - Solidity v0.5.0 Değişiklikleri
+ Güvenlik Hususları
  - Tuzaklar
  - Öneriler
  - Resmi Doğrulama
+ Kaynaklar
  - Genel
  - Solidity Entegrasyonları
  - Solidity Araçları
  - Üçüncü Parti Solidity Parserleri ve Terimleri
+ Derleyiciyi Kullanımı
  - Komut Satırı Derleyicisi Kullanımı
  - EVM Sürümünü Hedefe Ayarlama
  - Derleyici Giriş ve Çıkış JSON Açıklaması
+ Sözleşme Meta Verileri
  - Byte Kodunda Meta Veri Hash'in Kodlanması
  - Otomatik Arayüz Üretimi ve NatSpec Kullanımı
  - Kaynak Kod Doğrulama Kullanımı
+ Sözleşme ABI Spesifikasyonları
  - Temel Tasarım
  - Fonksiyon Seçimi
  - Argüman Kodlama
  - Türleri
  - Kodlama için Tasarım Kriterleri
  - Kodlamanın Resmi Olarak Belirtilmesi
  - Fonksiyon Seçimi ve Argüman Kodlaması
  - Örnekler
  - Dinamik Türlerin Kullanımı
  - Olaylar
  - JSON
  - Sıkı Kodlama Modu
  - Standart Dışı Paketlenme Modu
+ Yul
  - Yul şartname
  - Yul Nesnesinin Özellikleri
+Stil Rehberi
  - Giriş
  - Kod Düzeni
  - Düzen Sırası
  - Adlandırma Kuralları
  - NatSpec
+ Ortak Desenler
  - Sözleşmelerden Çekilme
  - Erişimi Kısıtlamak
  - Durum Mekanizması
+ Bilinen Hataların Listesi
+ Katkı Sağlama
  - Sorunlar Nasıl Bildirilir?
  - Pull & Push İstekleri İçin İş Akışı
  - Derleyici Testleri
  - Fuzzer'i AFL İle Çalıştırmak
  - Whiskers
+ Sık Sorulan Sorular
  - Temel sorular
  - Gelişmiş Sorular
+ LLL

# Akıllı Sözleşmelere Giriş

## Basit Bir Akıllı Sözleşme

Temel bir örnekle başlayalım. Bir değişkene değer verelim ve bir diğer sözleşme ile bu değişkene erişmeye çalışalım. Şu anda her şeyi anlamıyorsanız sorun değil, bu konuları daha sonra ayrıntılı olarak ele alacağız.

```
pragma solidity >=0.4.0 <0.6.0;

contract SimpleStorage {
    uint storedData;

    function set(uint x) public {
        storedData = x;
    }

    function get() public view returns (uint) {
        return storedData;
    }
}
```
İlk satır basitçe kaynak kodun Solidity versiyon 0.4.0 ya da işlevselliği bozmayan daha yeni bir versiyon için yazıldığını söyler (0.6.0 sürümüne kadar olanları içermez). Bu, sözleşmenin farklı davranabileceği, veya bozulabileceği, yeni bir (derleyici) derleyici sürümüyle uyumlu olmamasını sağlamak için kullanılır. Sözde pragmalar, kaynak kodun nasıl ele alınacağına ilişkin derleyiciler için genel talimatlardır (Örneğin [pragma once](https://en.wikipedia.org/wiki/Pragma_once)).

Solidity kapsamında bir sözleşme, Ethereum ağı üzerindeki belirli bir adreste bulunan kod (işlevselliği sağlayan fonksiyonlar) ve verilerin (durum) toplamıdır. `uint storedData` satırı, `unit` türünde (256 bitlik tamsayı) `storedDate` isimli bir durum değişkeni tanımlar. Bunu, sözleşme içerisinde kullanılan fonksiyonlarla sogulanıp değiştirilebilen bir veritabanı bilgisi olarak düşünebilirsiniz. Ethereum söz konusu olduğunda, bu her zaman sahip olma sözleşmesidir. Ve bu durumda, `set` ve `get` fonksiyonları değişkenin değerini değiştirmek veya değişkeni çağırmak için kullanılabilir.

Bir durum değişkenine erişmek için, `this.` ön ekine ihtiyacınız yoktur. Diğer dillerde olduğu gibi.

Bu sözleşme henüz, Ethereum tarafından oluşturulan altyapıdan dolayı, atadığınız bu değişkene Dünya üzerinde herhangi birinin erişimini sağlamaktan başka bir işleve sahip değil. Elbette, herkes bunun gibi farklı bir değere eşitlenmiş bir değişken içeren sözleşme yayınlayabilir veya sizin değişkeninizin değerini değiştirmek isteyebilir, ancak size ait sözleşme ve değişken değeri blok zincirinde tarihi ile birlikte saklanır. Daha sonra, erişim kısıtlamaları nasıl uygulayabileceğinizi göreceğiz, bu sayede kendi değişkeninizi yalnızca siz değiştirebileceksiniz.

### [Not](#)

> Sözleşmenizin tüm tanımlayıcı değerleri (sözleşme isimleri, fonksiyon isimleri ve değişken isimleri) ASCII karakter seti ile sınırlıdır. UTF-8 ile kodlanmış verileri string değişkenlerinde saklamak mümkündür.

### [Uyarı](#)

>Unicode metni kullanırken dikkatli olunması gerekir, çünkü benzer görünümlü (hatta aynı) karakterler farklı kod işlevlerine sahip olabilir ve farklı bir bayt dizisi olarak kodlanabilirler.

## Alt Para Birimi Örneği

Aşağıdaki sözleşme, bir kripto para biriminin en basit şeklini oluşturmak amacıyla yazılmıştır. Ethereum akıllı sözleşmeleri ile kripto para üretmek mümkündür, ancak bunu yalnızca sözleşmeyi oluşturan kişi yapabilir (farklı bir düzenleme planı uygulamak mümkündür). Ağdaki herkes, kullanıcı adı ve şifre ile bir yere kaydolmaya gerek duymadan birbirlerine para gönderebilir ve ödeme alabilirler - bunu yaparken tek ihtiyaçları olan bir Ethereum anahtar çiftidir.

```
pragma solidity ^0.5.0;

contract Coin {
    // The keyword "public" makes those variables
    // easily readable from outside.
    address public minter;
    mapping (address => uint) public balances;

    // Events allow light clients to react to
    // changes efficiently.
    event Sent(address from, address to, uint amount);

    // This is the constructor whose code is
    // run only when the contract is created.
    constructor() public {
        minter = msg.sender;
    }

    function mint(address receiver, uint amount) public {
        require(msg.sender == minter);
        require(amount < 1e60);
        balances[receiver] += amount;
    }

    function send(address receiver, uint amount) public {
        require(amount <= balances[msg.sender], "Insufficient balance.");
        balances[msg.sender] -= amount;
        balances[receiver] += amount;
        emit Sent(msg.sender, receiver, amount);
    }
}
```

Bu sözleşme bazı yeni konseptler de ortaya koyuyor, tek tek üzerinden geçelim.

`address public minter;` satırı, genel olarak erişilebilir bir `adres` tipi durum değişkenini bildirir. `Adres` türü, aritmetik işlemlere izin vermeyen 160 bitlik bir değerdir. Bu tür, sözleşmedeki adreslerinin veya dış kişilere ait anahtar çiftlerinin depolanması için uygundur. `Public` anahtar sözcüğü, durum değişkeninin geçerli değerine sözleşmenin dışından erişilmesine olanak sağlayan bir işleve sahiptir. Bu anahtar kelime kullanılmadığı takdirde, diğer sözleşmelerden bu değişkene erişmenin yolu yoktur. Derleyici veya geliştirici tarafından oluşturulan işlevin kodu kabaca aşağıdakine eşittir (şimdilik `ignore` ve `view` i görmezden gelelim):

```
function minter() external view returns (address) { return minter; }
```
Elbette, tam olarak bunun gibi bir işlev eklemek kodun çalışmamasına sebep olurdu. Çünkü aynı ada sahip bir işlevimiz ve yine aynı isimde bir durum değişkenimiz olacaktı. Ama umarım, siz mantığı anladınız - derleyici sizin için bunu farkedecektir. 

Bir sonraki satırda bulunan `mapping (address => uint) public balances;` yine bir public durum değişkeni yaratır, ancak bu daha karmaşık bir veri türüdür. Bu tür, sözleşmedeki adresleri, işaretsiz tamsayılarla eşleştirmek için kullanılır. Bu eşlemeleri fiziksel olarak betimlemeye çalışalım: Olası her anahtarın, başlangıçtan itibaren var olan ve bayt değerinin tümü sıfıra eşit bir değere atandığı hash tablolarını düşünebiliriz . Bu benzetme üzerine çok kafa yormayın, çünkü bir eşlemenin tüm anahtarlarının bir listesini ya da tüm değerlerin bir listesini elde etmek mümkün değildir. Bu nedenle, genel kavramı  aklınızda bulundurun (ya da daha iyisi bir liste yapın ya da daha gelişmiş bir veri eşleme türü kullanın) ya da bunun gerekmediği bir sistem oluşturun. Public anahtar kelimesi tarafından oluşturulan getter fonksiyonu bu durumda biraz daha karmaşıktır. Bu fonksiyon kabaca aşağıdaki gibi görünüyor:

```
function balances(address _account) external view returns (uint) {
    return balances[_account];
}
```

Gördüğünüz gibi, tek bir hesabın bakiyesini kolayca sorgulamak için bu işlevi kullanabilirsiniz.


`event Sent(address from, address to, uint amount);` satırı, gönderme fonksiyonunun son satırında yayınlanan “event(olay)” olarak adlandırılır. Kullanıcı arayüzleri (tabii ki sunucu uygulamalarında olduğu gibi) blok zincirinde yayınlanan olayları fazla maliyet olmadan dinleyebilir. Yayınlandığı anda dinleyici, işlemlerin izlenmesini kolaylaştıran, miktar, zaman ve sözleşme argümanları gibi bilgilere de sahip olur. Bu olayı dinlemek için, aşağıdaki JavaScript kodunu kullanmanız gerekir ( Burada Coin'in web3.js veya benzeri bir modül üzerinden yaratılmış bir sözleşme nesnesi olduğu varsayılmaktadır):

```
Coin.Sent().watch({}, '', function(error, result) {
    if (!error) {
        console.log("Coin transfer: " + result.args.amount +
            " coins were sent from " + result.args.from +
            " to " + result.args.to + ".");
        console.log("Balances now:\n" +
            "Sender: " + Coin.balances.call(result.args.from) +
            "Receiver: " + Coin.balances.call(result.args.to));
    }
})
```
Burada otomatik olarak üretilen `balances` fonksiyonunun kullanıcı arayüzü tarafından nasıl çağrıldığına lütfen dikkat edin.

Constructer fonksiyonu,yalnızca sözleşmenin oluşturulması sırasında belirtilen ve daha sonra çağrılamayan özel bir fonksiyondur. Sözleşmeyi oluşturan kişinin adresini kalıcı olarak saklar: `msg` (`tx` ve `block` ile birlikte), blok zincirine erişime izin veren bazı özellikleri içeren özel bir global değişkendir. `msg.sender` ise her zaman geçerli (harici) işlev çağrısının geldiği adresdir.

Son olarak, sözleşmenin sonunda belirtilip sonrasında kullanıcılar ve diğer sözleşmeler tarafından çağrılabilecek fonksiyonlar `mint` ve `send` fonksiyonlarıdır. `Mint` fonksiyonu sözleşmeyi oluşturan dışında herhangi biri tarafından çağrılırsa, hiçbir değişime sebep olmayacaktır. Bu durum `require` isimli argümanının `false` olması durumunda herhangi bir değişikliği geri çeviren özel bir fonksiyon tarafından güvence altına alınmaktadır. İkinci `require` çağrısı ise, daha sonra taşma hatalarına neden olabilecek çok fazla para olmasını engellemek içindir.

Öte yandan, `sent` (zaten bu kripto paraya sahip olan) herhangi biri tarafından ağdaki herhangi başka birine para göndermek kullanılabilir. Gönderilecek yeterli para bulunmaması durumunda, `require` çağrısı başarısız olur ve kullanıcıya uygun bir hata mesajı gönderilir.

### [Not](#)

>Bu sözleşmeyi bir adrese kripto para göndermek için kullanırsanız, ait olduğu blockchain explorer sisteminde adrese ait bir işlem kaydı göremezsiniz, çünkü gönderdiğiniz miktar ve değişen bakiye değerleri yalnızca bu kripto parayı oluşturan akıllı sözleşmeye ait veri deposunda saklanır. `Event`lerin kullanımıyla, yeni paranızın işlemlerini ve bakiyelerini izleyen bir “blokchain explorer” oluşturmak oldukça kolaydır, ancak bunu yaparken üretilen paranın sahiplerinin adreslerini değil, akıllı sözleşme adresini incelemeniz gerekmektedir.

## Blockchain Temelleri

Blockchain programcılar için anlaşılması zor bir kavram değildir. Bunun nedeni, komplikasyonların çoğunun (blockchain madenciliği, hash, eliptik-eğri kriptografisi, bireyler arası ağlar vb. gibi) platformlar için belirli bir dizi özellik ve vaat sağlamak için var olmasıdır. Bu kavramları ve işlevlerini anlayıp kabul ettikten sonra, temel teknoloji hakkında endişelenmenize gerek yok. Düşünce olarak, Amazon’un AWS’sini kullanmak için dahili olarak nasıl çalıştığını bilmek zorunda mısınız? Elbette hayır.

### İşlemler

Blockchain, global olarak paylaşılan, işlemsel bir veritabanıdır. Bu, herkesin sadece ağa katılarak veritabanındaki hareketlilikleri görebileceği anlamına gelir. Veritabanındaki bir şeyi değiştirmek istiyorsanız, diğerleri tarafından kabul edilmesi gereken sözde bir işlem oluşturmanız gerekir. İşlem kelimesi, yapmak istediğiniz değişikliğin (aynı anda iki değeri değiştirmek istediğinizi varsayalım) ya hiç yapılmamasını ya da tamamen uygulanmasını ifade eder. Ayrıca, işleminiz veritabanına uygulanırken başka hiçbir işlem bunu değiştiremez.

Örnek olarak, tüm hesapların bakiyelerini bir kripto para biriminde listeleyen bir tablo düşünün. Bir hesaptan diğerine transfer talep edilirse, veritabanının işlemsel niteliği, tutarın bir hesaptan çıkarılması durumunda, her zaman diğer hesaba eklenmesini sağlar. Sebep ne olursa olsun, tutarı hedef hesaba eklemek mümkün değilse, kaynak hesaptaki miktar da değiştirilmez.

Ayrıca, bir işlem her zaman gönderen (yaratıcı) tarafından şifreli olarak imzalanır. Bu, veritabanındaki belirli değişikliklere erişimi korumayı kolaylaştırır. Kripto para birimi örneğinde, basit bir kontrol, yalnızca anahtarları hesaba katan bir kişinin hesaptan para aktarabilmesini sağlar.

### Blok Kavramı

Üstesinden gelinmesi gereken en büyük engellerden biri (Bitcoin açısından) "çifte harcama saldırısı" olarak adlandırılan bir olaydır: Ağda bir cüzdanı boşaltmak isteyen eşzamanlı iki işlem varsa ne olur? İşlemlerden sadece biri geçerli olabilir, tipik olarak önce kabul edilmiş olanı. Sorun, “ilk” in eşler arası ağda nesnel bir terim olmamasıdır.

Özetle hiçbir kullanıcının, bu konuda endişelenmesine gerek yoktur. Anlaşmazlığın çözümü sırasında kullanıcı için global olarak kabul edilen bir işlem sırası seçilecektir. İşlemler, “blok” olarak adlandırılan birbirine bağlı olaylara ayrılacak ve daha sonra tüm katılımcı düğümler ile paylaşılarak ve eşit şekilde dağıtılacaktır. İki işlem birbiriyle çelişirse, ikinci olan reddedilerek ve bloğun bir parçası olmayacaktır.


Bu bloklar zaman içinde lineer bir sekans oluşturur ve “blockchain” kelimesi işte buradan türemiştir. Zincire oldukça düzenli aralıklarla bloklar eklenir - Ethereum için bu kabaca her 17 saniyede yeni blok eklenir.

“Sipariş seçim mekanizması” nın (“madencilik” olarak da adlandırılan) bir parçası olarak, bloklar zaman zaman geri döndürülebilir, ancak yalnızca zincirin “ucunda” olanlar bu şekilde bir işlem için elverişlidirler. Belirli bir bloğun üstüne ne kadar fazla blok eklenirse, bu bloğun geri döndürülme olasılığı o kadar düşük olur. Bu nedenle, işlemleriniz geri çevrilir ve hatta blok zincirinden kaldırılır, ancak ne kadar uzun süre beklerseniz, işleminizin geri çevrilme ihtimali de o kadar az olacaktır.

### [Not](#)

> İşlemlerin gelecekte hangi blokta belireceği bilinemez ve garanti edilemez, çünkü bir işlemin ağa aktarıldığında blokta belirme süresi, paylaşılma zamanına değil, işlemin hangi blokta yer alacağını belirleyen madencilere bağlıdır.

> Sözleşmenizin gelecekteki aramalarını çağrılmalarını istiyorsanız, [çalar saati](http://www.ethereum-alarm-clock.com/) veya benzer bir sisteme sahip Oracle servisini kullanabilirsiniz.

## The Ethereum Sanal Makinesi

### Genel Bakış

Ethereum Sanal Makinesi veya EVM(Ethereum Virtual Machine), Ethereum'da akıllı sözleşmeler için kullanılan çalışma ortamıdır. Bu alan yalnızca korunaklı değil, aynı zamanda tamamen yalıtılmıştır. Yani EVM içinde çalışan bir kodun ağa, herhangi bir dosya sistemine veya diğer dış işlemlere erişimi yoktur. Burada, akıllı sözleşmelerin diğer akıllı sözleşmelere bile sınırlı erişimi vardır.

### Hesaplar

Ethereum'da aynı adres alanını paylaşan iki tür hesap vardır: Public(erişime açık) anahtar çiftleri(yani insanlar) tarafından kontrol edilen **dış hesaplar** ve hesapla birlikte saklanan kod tarafından kontrol edilen **sözleşme hesapları**.

Bir dış hesabın adresi, genel anahtarlar tarafından belirlenirken, bir sözleşmenin adresi sözleşmenin yapıldığı sırada belirlenir (yaratıcının adresinden ve bu adresten gönderilen işlemlerin adından türetilir, ki bunlara “nonce” da denir).

Hesabın kod saklayıp saklamadığına bakılmaksızın, iki tür EVM tarafından eşit olarak ele alınır.

Her hesap kalıcı nitelikte 256 bit alana sahip anahtar-değer eşlemesine sahiptir. Dahası, her hesabın Ether değerinde bir bakiyesi vardır ve bu bakiye değeri işlemler sonucunda yine Ether cinsinde değişime uğrar.

### İşlemler

İşlem, bir hesaptan diğerine (aynı veya boş olabilir, aşağıya bakınız) gönderilen bir mesajdır. İkili veri (“faydalı yük” olarak adlandırılır) ve Eter içerebilir.

Hedef hesap kod içeriyorsa, bu kod çalıştırılır ve sonucunda elde erilen veri yükü girdi olarak kabul edilir.

Hedef hesap belirtilmemişse (işlemin bir alıcısı yoksa veya alıcı null olarak ayarlanmışsa), işlem yeni bir sözleşme oluşturmak amacını taşıyor demektir. Daha önce de belirtildiği gibi, bu sözleşmenin adresi sıfır adres değil, göndericiden ve gönderilen işlem sayısından (“null”) türetilmiş bir adrestir. Böyle bir sözleşme yaratma işleminin yükü EVM bytecode olarak alınır ve çalıştırılır. Bu uygulamanın çıktı verileri, sözleşmenin kodu olarak kalıcı nitelikte depolanır. Yani denilebilir ki, bir sözleşme oluşturmak için sözleşmenin asıl kodunu göndermemeniz, aslında bu kod yürütüldüğünde ortaya çıkan verinin gönderilmesi anlamına gelir.

### [Uyarı](#)

> Bir sözleşme oluşturulurken içerdiği kodlar henüz aktif olmaz. Bu sebeple, geliştirici sözleşmeyi bitirene kadar sözleşme geri çağırılmamalıdır.

### Gaz

Gerçekleştirilmek istenen her bir işlem, işlemi gerçekleştirmek için gereken iş miktarını sınırlandırmak ve aynı zamanda bu işlem için gereken ödemeyi almak amacıyla belirli miktar gaz ile ücretlendirilir. EVM işlemi gerçekleştirirken, gaz belirli kurallara göre kademeli olarak değişkenlik gösterir.

**Gaz ücreti**, işlemin yaratıcısı tarafından yani gönderen hesabından `gaz_ücreti * gaz` miktarında ödemek zorunda olduğu bir değerdir. Uygulamadan sonra bir miktar gaz kalırsa, kalan gaz miktarına tekabül eden ether aynı şekilde gönderen hesabına iade edilir. 

### Depolama, Bellek & Yığın

Ethereum Sanal Makinesi (EVM), aşağıdaki paragraflarda açıklanacağı üzere verileri depolama, bellek ve yığın isimli üç farklı alanda muhafaza eder.

Her hesap, işlev çağrıları ve işlemler arasında kalıcı olan, **depolama** adı verilen bir veri alanına sahiptir. Depolama, 256-bit kelimeleri 256-bit kelimelere eşleyen anahtar-değer ikilisini barındırır. Depolamayı bir sözleşme içinde belirtmek mümkün değildir. Depolamayı okumak pahalı bir işlemken değiştirmek çok daha büyük maliyetlere sebep olabilir. Bir sözleşme, kendisinden başka hiçbir depolamayı okuyamaz veya müdahale edemez.

İkinci veri alanı ise, bir sözleşmenin aldığı her yeni işlem çağrısı sırasında yeniden elde ettiği **bellek veya hafıza** adını verdiğimiz alandır. Bellek doğrusaldır ve bayt düzeyinde adreslenebilir, ancak yazmalar 8 bit veya 256 bit genişliğinde olabilirken, okumalar 256 bit genişliğiyle sınırlıdır. Önceden dokunulmamış bir bellek alanına erişirken(okurken veya yazarken) bu alan(256-bit) yazıldığı alanın(8 bit) ötesine genişletilebilir. Bu genişleme sırasında ortaya çıkabilecek ekstra gaz maliyeti gönderici tarafından ödenmelidir. Bellek, büyüdükçe daha maliyet de artacaktır(Söz konusu artış miktarın karesi şeklinde olacaktır).

EVM bir kayıt makinesinden çok bir yığın makinesidir, bu nedenle tüm hesaplamalar yığın adı verilen bir veri alanında gerçekleştirilir. Bu alan maksimum 1024 element kapasitesine sahiptir ve 256 bit büyüklüğünde veriler içermektedir. Yığına erişim, aşağıdaki şekilde üst uç ile sınırlıdır: En üstteki 16 öğeden birini yığının üstüne kopyalamak veya en üstteki öğeyi altındaki 16 öğeden biriyle değiştirmek mümkündür. Diğer tüm işlemler yığından en üstteki iki (veya bir veya daha fazla) elemanı alır ve sonucu yığının üzerine iter. Elbette, yığının daha derine erişmesi için yığın elemanlarının depoya veya belleğe taşınması mümkündür, fakat yığının üst kısmı çıkarılmadan daha derine erişilmesi mümkün değildir.

### Yönerge Seti

EVM'nin yönerge seti, fikir birliği sorunlarına neden olabilecek yanlış veya tutarsız uygulamalardan kaçınmak için minimum düzeyde tutulmaktadır. Tüm talimatlar temel veri tipinde, 256 bit kelimelerde veya hafıza dilimlerinde (veya diğer byte dizilerinde) çalışır. Her zamanki aritmetik, bit, mantıksal ve karşılaştırma işlemleri mevcuttur. Koşullu ve koşulsuz atlamalar mümkündür. Ayrıca, sözleşmeler, geçerli bloğun numarası ve zaman damgası gibi ilgili özelliklerine de erişme hakkına sahiptir.

Tam bir liste için lütfen satır içi komutlarının derleme belgesi olan işlem kodu listesine göz atınız.

### Mesaj Çağrıları

Sözleşmeler, diğer sözleşmeleri çağırabilir ya da sözleşmesiz hesaplara mesaj çağrısı ile Ether gönderebilir. Mesaj çağrıları, kaynak, hedef, veri taşıma yükü, Ether, gaz ve iade verilerine sahip olmaları nedeniyle işlemlere benzerler. Bu mantıkla bakıldığında, her işlem sırayla daha fazla çağrı yaratabilen üst düzey bir mesaj çağrısı kümesinden oluşur.

Bir sözleşme, kalan gazın ne kadarının iç mesaj çağrısı ile gönderilmesi gerektiğine ve ne kadarının gönderim sırasında kullanılacağına karar verebilir. İç çağrıda gaz dışı bir istisna olursa(veya herhangi başka bir istisna), bu, yığına eklenen bir hata değeriyle bildirilir. Bu durumda, yalnızca çağrı ile birlikte gönderilen gaz tüketilir. Solidity dilinde, bu gibi istisnaların oluşması varsayılan olarak manuel başka zincirleme istisnalar da yaratmaya meyilli olduğundan totalde yığınını “kabarcıklandıran” durum olarak nitelendirilir.

Çağrılar, 1024 bitlik alanla ile sınırlıdır; bu, daha karmaşık işlemler için tekrarlamalı çağrılar yerine döngüler tercih edileceği anlamına gelir. Ayrıca, bir mesaj çağrısında gazın sadece 63 / 64'ü iletilebilir; bu, pratikte 1000 bit'ten daha az bir alan sınırlamasına neden olur.

### Delegatecall / Çağrı Kodu & Kütüphaneler

Bir mesaj çağrısı ile temelde aynı anlama gelen delegatecall, hedef adresteki kodun arama sözleşmesi bağlamında yürütülmesi ve `msg.sender` ve `msg.value` değerlerinin değiştirilememesi gibi özellikleri ile mesaj çağrısının özel bir çeşidi olarak kabul edilir. Bu, bir sözleşmenin çalışması sırasında  farklı bir adresden dinamik olarak kod yükleyebileceği anlamına gelir. Depolama, geçerli adres ve bakiye hala aranan sözleşmeye atıfta bulunurken, yalnızca kod aranan adresten temin edilir.

İşte, “kütüphane kullanımı” özelliğinin Solidity dilinde uygulanabilir olmasını mümkün kılan budur. Solidity dilinde kütüphanelerin kullanılması komplex data yapısı ile başa çıkmak ve başka projelerde yeniden kullanılabilmek gibi büyük kolaylıklar sağlar.

### Kayıtlar

Verileri tümüyle blok seviyesine kadar haritalayan özel indeksli bir veri yapısında depolamak mümkündür. Kayıt adı verilen bu özellik, kodda değinmiş olduğmuz olayları(events) uygulayabilmek için Solidity tarafından kullanılır. Sözleşmeler, oluşturulduktan sonra kayıt verilerine erişilemez, ancak zincirin dışından etkin bir şekilde erişilebilir. Kayıt verilerinin bir kısmı bloom filtrelerinde saklandığından, bu verileri etkin ve kriptografik olarak güvenli bir şekilde aramak mümkündür, böylece tüm zinciri indirmek zorunda kalmayan ağ elemanları ("hafif istemciler" olarak da bilinirler) bu kayıtlara erişim sağlayabilirler.

### Çağrı Oluşturmak

Sözleşmeler, özel bir opcode kullanarak başka sözleşmeler bile oluşturabilir (bunu, hedef adresi boş bırakarak yaparlar). Bu arama çağrıları ve normal mesaj çağrıları arasındaki tek fark, açığa çıkan veri yükünün yürütülmesi ve sonucun kod olarak saklanarak arayan tarafın(yaratıcının) yığındaki yeni sözleşmenin adresini almasıdır.

### Devre Dışı Bırakma & Kendini İmha

Bir zincirden kodu kaldırmanın tek yolu, söz konusu adresteki bir sözleşmenin `selfdestruct` özelliğini aktif hale getirmesidir. Bu adreste kalan Eter belirlenmiş bir önceden belirtilen bir hedefe gönderilir ve ardından depolama ve kod durumdan çıkarılır. Sözleşmeyi teoride çıkarmak iyi bir fikir gibi görünse bile, birileri kaldırılmış sözleşmelere Ether gönderirse, Ether sonsuza dek kaybedilme tehlikesi ile karşı karşıya kalır.

### [Not](#)

> Bir sözleşmenin kodu, `selfdestruct` çağrısı içermese bile, bu işlemi `delegatecall` veya `callcode` kullanarak yapabilir.

Sözleşmelerinizi devre dışı bırakmak istiyorsanız, bunun yerine tüm işlevlerin geri alınmasına neden olan bazı iç durumları değiştirerek bunları devre dışı bırakmalısınız. Bu, Ether'i derhal iade ettiğinden sözleşmeyi kullanmayı imkansız kılar.

### [Uyarı](#)

>Bir sözleşme `selfdestruct` ile kaldırılsa bile, hala blockchain tarihinin bir parçasıdır ve muhtemelen çoğu Ethereum düğümü tarafından korunmaktadır. Bu nedenle, `selfdestruct` özelliğini kullanmak, sabit diskten veri silmekle aynı şey değildir.

## Solidity Düzenleyicisini Yükleme

### Sürüm

Solidity versiyonları semantic versiyonlamayı takip eder ve yayınların yanı sıra, gecelik geliştirme yapılarını(Nightly Builds olarak da bilinir) da barındırır. Her yapılan çalışmanın garantisi yoktur ve bu çalışmalar en iyi çabalara rağmen belgelenmemiş ve / veya kırılmış değişiklikler içerebilir. Biz yine de en son sürümü kullanmanızı öneririz. Aşağıda belirtilen paket yükleyicileri de en son sürümü kullanacaktır.

### Remix

*Remix'i Solidity dilinde küçük sözleşmeler hazırlamanız ve hızlıca öğrenmeniz için öneririz.*

Çevrimiçi olarak [Remix’e erişebilir](https://remix.ethereum.org/) ve hiçbir şey yüklemeden kullanmaya başlayabilirsiniz. İnternete bağlanmadan kullanmak istiyorsanız, https://github.com/ethereum/remix-live/tree/gh-pages adresine gidebilir ve .zip dosyasını o sayfada açıklandığı şekilde indirebilirsiniz.

Bu sayfadaki diğer seçenekler, Solidity derleyicisini komut satırı ile bilgisayarınıza indirmeniz konusunda detaylara yer vermektedir. Daha büyük bir sözleşme üzerinde çalışıyorsanız veya daha fazla derleme seçeneği istiyorsanız, bu komutlardan
birini seçmenizi öneriyoruz.

### Npm / Node.js

Bir Solidity derleyicisi olan solcjs'i kurmak için uygun ve taşınabilir bir yöntem olarak npm'yi kullanabilirsiniz. Solcjs programı, daha aşağıda  ayrıntılı olarak açıklanan diğer derleyicilere kıyasla daha az özelliğe sahiptir. Komut Satırını kullanma belgelerinde, Solc'u tam özellikli şekilde kullandığınızı varsayılmaktadır. Solcjs kullanımı kendi [deposunda](https://github.com/ethereum/solc-js) belgelenmiştir.

Not: Solc-js projesi, her ikisi de aynı derleyici kaynak kodunu kullandığı anlamına gelen Emscripten kullanılarak C ++ solc'tan türetilmiştir. Solc-js doğrudan JavaScript projelerinde kullanılabilir (Remix gibi). Lütfen talimatlar için solc-js deposuna bakınız.

```
npm install -g solc
```

### [Uyarı](#)

> Çalıştırılabilir komut satırı solc js olarak adlandırılır.
> Stokların komut satırı seçenekleri solc ile uyumlu değildir ve solc'un davranışını bekleyen araçlar (geth gibi) solcjs ile çalışmayacaktır.

### Docker

Düzenleyici için güncel Docker Builder temin ediyoruz. `Stable` depo, sürümlerin hepsini serbest barındırıken, `Nightly` depo geliştirme dalında en son gelişmelerin sürekli paylaşılıp güncellenmesi sebebiyle daha dinamik bir yapıdadır.

```
docker run ethereum/solc:stable --version
```

### İkili Paketler

İkili Solidity paketleri, [bu adreste](https://github.com/ethereum/solidity/releases) mevcuttur.

Ayrıca Ubuntu için PPA'larımız var, aşağıdaki komutları kullanarak en yeni kararlı sürümü edinebilirsiniz:

```
sudo add-apt-repository ppa:ethereum/ethereum
sudo apt-get update
sudo apt-get install solc
```
Nightly versiyonu aşağıdaki komutlar kullanılarak indirilebilir:

```
sudo add-apt-repository ppa:ethereum/ethereum
sudo add-apt-repository ppa:ethereum/ethereum-dev
sudo apt-get update
sudo apt-get install solc
```
Bunlara ek olarak, desteklenen tüm [Linux dağıtımlarına](https://snapcraft.io/docs/core/install) yüklenebilen bir [ek paket](https://snapcraft.io/) yayınlıyoruz. Solc'un en son kararlı sürümünü yüklemek için:

```
sudo snap install solc
```
En son değişikliklerle Solidity'nin en son geliştirme sürümünü test etmeye yardımcı olmak istiyorsanız, lütfen aşağıdakileri kullanın:

```
sudo snap install solc --edge
```
Arch Linux ayrıca en son geliştirme sürümüyle sınırlı olsa da aşağıdaki paketlere sahiptir:

```
pacman -S solidity
```
Solidity derleyicisini, kaynak kodlu bir sürüm olarak Homebrew aracılığıyla da dağıtıyoruz. Önceden oluşturulmuş dosyalar şu anda desteklenmiyor olabilir.

```
brew update
brew upgrade
brew tap ethereum/ethereum
brew install solidity
```

Belirli bir Solidity versiyonuna ihtiyacınız varsa, doğrudan Github'dan bir Homebrew formülü kurabilirsiniz.

Bunun için [solidity.rb commits on Github](https://github.com/ethereum/homebrew-ethereum/commits/master/solidity.rb) adresini incelemeniz gerekiyor.

Belirli bir `solidity.rb` ham dosya bağlantısına sahip oluncaya kadar geçmiş bağlantılarını takip edin.

Brew kullanarak kurun:

```
brew unlink solidity
# Install 0.4.8
brew install https://raw.githubusercontent.com/ethereum/homebrew-ethereum/77cce03da9f289e5a3ffe579840d3c5dc0a62717/solidity.rb
```

Gentoo Linux ayrıca `emerge` kullanılarak kurulabilen bir Soldiity paketi sunuyor:

```
emerge dev-lang/solidity
```

## Kaynağından Kurulum

### Linux - Önkoşullar

Linux'un Solidity sürümleri için aşağıdaki ön koşul dosyalarını kurmanız gerekir:

======================


### MacOS - Önkoşullar

MacOS için, en son Xcode sürümünün yüklü olduğundan emin olun. Bu, Clang C ++ derleyicisini, Xcode IDE'yi ve OS X'te C ++ uygulamaları oluşturmak için gerekli olan diğer Apple geliştirme araçlarını içerir. İlk kez Xcode yüklüyorsanız veya yeni bir sürüm yüklediyseniz, onaylamanız gerekir. Komut satırından işlem yapabilmeniz için önce lisansı onaylamanız gerekir:

```
sudo xcodebuild -license accept
```
OS X sürümlerimiz, harici ön koşul dosyalarını kurmak için [Homebrew paket yöneticisini kurmanızı](http://brew.sh/) gerektirir. İşte yine sıfırdan başlamak istiyorsanız, [Homebrew'ü buradan kaldırabilirsiniz](https://github.com/Homebrew/homebrew/blob/master/share/doc/homebrew/FAQ.md#how-do-i-uninstall-homebrew).

### Windows - Önkoşullar

Windows'un Solidity sürümleri için aşağıdaki ön koşul dosyalarını kurmanız gerekir:

================

Zaten bir IDE'niz varsa ve yalnızca derleyici ve kitaplıklara ihtiyacınız varsa, Visual Studio 2017 Yapı Araçları'nı yükleyebilirsiniz.

Visual Studio 2017 hem IDE hem de gerekli derleyici ve kütüphaneler sunar. Bu yüzden bir IDE'niz yoksa ve sağlamlığı geliştirmeyi tercih ediyorsanız, Visual Studio 2017, her şeyi kolayca kurmanız için bir seçenek olabilir.

Visual Studio 2017 Yapı Araçları veya Visual Studio 2017'de yüklenmesi gereken bileşenlerin listesi:

+ Visual Studio C++ core features
+ VC++ 2017 v141 toolset (x86,x64)
+ Windows Universal CRT SDK
+ Windows 8.1 SDK
+ C++/CLI support

### Depoyu Klonlama

Kaynak kodu klonlamak için aşağıdaki komutu uygulayın:

```
git clone --recursive https://github.com/ethereum/solidity.git
cd solidity
```

Eğer Solidity dilini geliştirmeye yardım etmek istiyorsanız, Solidity üzerinde çatallama yapmalı ve kişisel çatalınızı ikinci bir remote olarak eklemelisiniz:
```
git remote add personal git@github.com:[username]/solidity.git
```

### Dış Bağımlılıklar

Gerekli tüm dış bağımlılıkları macOS, Windows ve sayısız Linux dağıtımına yükleyen bir yardımcı programımız var:

```
./scripts/install_deps.sh
```
Veya Windows için:

```
scripts\install_deps.bat
```

### Komut Satırı Oluştur


```
```



