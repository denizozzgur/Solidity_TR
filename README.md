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

>Yazılımlar insanlar tarafından yazıldığından hatalar içerebilirler. Akıllı sözleşmelerinizi yazarken kabul görmüş yazılım geliştirme kurallarına uymanız tavsiye edilir; buna kod incelemesi, testler, denetimler ve doğruluk kanıtları da dahildir. Akıllı sözleşme kullanıcıları bazen kodlara yazarlarından daha fazla güven duyarlar. Blockchain ve akıllı sözleşmelerde özellikle dikkat edilmesi gereken özel konular olduğundan; geliştirici olarak herhangi bir kod üzerinde çalışmaya başlamadan önce **Güvenlikle İlgili Hususlar** bölümünü okuduğunuzdan emin olunuz.

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
  - Gizli Açık Arttırma
  - Güvenli Uzaktan Satın Alım
  - Mikro Ödeme Kanalı
+ Derinlemesine Solidty
  - Bir Solidity Kaynak Dosyasının Yapısı
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

Aşağıdaki sözleşme, en basit şekilde bir kripto para oluşturmak amacıyla yazılmıştır. Ethereum akıllı sözleşmeleri ile kripto para üretmek mümkündür, ancak bunu yalnızca sözleşmeyi oluşturan kişi yapabilir (farklı bir düzenleme planı uygulamak mümkündür). Ağdaki herkes, kullanıcı adı ve şifre ile bir yere kaydolmaya gerek duymadan birbirlerine para gönderebilir ve ödeme alabilirler - bunu yaparken tek ihtiyaçları olan bir Ethereum anahtar çiftidir.

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

`address public minter;` satırı, genel olarak erişilebilir bir `adres` tipi durum değişkenini bildirir. `Adres` türü, aritmetik işlemlere izin vermeyen 160 bitlik bir değerdir. Bu tür, sözleşmedeki adreslerinin veya dış kişilere ait anahtar çiftlerinin depolanması için uygundur. `Public` anahtar sözcüğü, durum değişkeninin geçerli değerine sözleşmenin dışından erişilmesine olanak sağlayan bir işleve sahiptir. Bu anahtar kelime kullanılmadığı takdirde, diğer sözleşmelerden bu değişkene erişmeye izin verilmez. Derleyici veya geliştirici tarafından oluşturulan fonksiyonun kodu kabaca aşağıdaki gibidir (şimdilik `ignore` ve `view` i görmezden gelelim):

```
function minter() external view returns (address) { return minter; }
```
Elbette, tam olarak bunun gibi bir fonksiyon eklemek kodun çalışmamasına sebep olabilir. Çünkü bu durumda aynı isme sahip bir fonksiyonumuz ve yine aynı isimde bir durum değişkenimiz olacaktır. Ama umarım, siz mantığı anladınız - derleyici sizin için bunu farkedecektir. 

Bir sonraki satırda bulunan `mapping (address => uint) public balances;` yine bir public durum değişkeni yaratır, ancak bu daha karmaşık bir veri türüdür. Bu tür, sözleşmedeki adresleri, işaretsiz tamsayılarla eşleştirmek için kullanılır. Bu eşlemeleri fiziksel olarak betimlemeye çalışalım: Olası her anahtarın, başlangıçtan itibaren var olan ve bayt değerinin tümü sıfıra eşit bir değere atandığı hash tabloları düşünebiliriz . Bu benzetme üzerine çok kafa yormayın, çünkü bir eşlemenin tüm anahtarlarının bir listesini ya da tüm değerlerin bir listesini elde etmek mümkün değildir. Bu nedenle, genel kavramı  aklınızda bulundurmak (ya da daha iyisi bir liste yaparak gelişmiş bir veri eşleme türü kullanmak) ya da bunun gerekmediği bir sistem oluşturmak daha iyi bir çözümdür. Public anahtar kelimesi tarafından oluşturulan getter fonksiyonu bu durumda biraz daha karmaşıktır. Bu fonksiyon kabaca aşağıdaki gibi görünür:

```
function balances(address _account) external view returns (uint) {
    return balances[_account];
}
```

Gördüğünüz gibi, tek bir hesabın bakiyesini kolayca sorgulamak için bu fonksiyonu kullanabilirsiniz.


`event Sent(address from, address to, uint amount);` satırı, gönderme fonksiyonunun son satırında yayınlanan “olay(event)” olarak adlandırılır. Kullanıcı arayüzleri (tabii ki sunucu uygulamalarında olduğu gibi) blok zincirinde yayınlanan olayları fazla maliyet olmadan dinleyebilir. Yayınlandığı anda dinleyici, işlemlerin izlenmesini kolaylaştıran, miktar, zaman ve sözleşme argümanları gibi bilgilere de sahip olur. Bu olayı dinlemek için, aşağıdaki JavaScript kodunu kullanmanız gerekir ( Burada Coin'in web3.js veya benzeri bir modül üzerinden yaratılmış bir sözleşme nesnesi olduğu varsayılmaktadır):

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

Constructer fonksiyonu,yalnızca sözleşmenin oluşturulması sırasında belirtilen ve daha sonra çağrılamayan özel bir fonksiyondur. Sözleşmeyi oluşturan kişinin adresini kalıcı olarak saklar: `msg` (`tx` ve `block` ile birlikte), blok zincirine erişime izin veren bazı özellikleri içeren özel bir global değişkendir. `msg.sender` ise her zaman geçerli (harici) fonksiyon çağrısının geldiği adrestir.

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

Her hesap, fonksiyon çağrıları ve işlemler arasında kalıcı olan, **depolama** adı verilen bir veri alanına sahiptir. Depolama, 256-bit kelimeleri 256-bit kelimelere eşleyen anahtar-değer ikilisini barındırır. Depolamayı bir sözleşme içinde belirtmek mümkün değildir. Depolamayı okumak pahalı bir işlemken değiştirmek çok daha büyük maliyetlere sebep olabilir. Bir sözleşme, kendisinden başka hiçbir depolamayı okuyamaz veya müdahale edemez.

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

Sözleşmelerinizi devre dışı bırakmak istiyorsanız, bunun yerine tüm fonksiyonların geri alınmasına neden olan bazı iç durumları değiştirerek bunları devre dışı bırakmalısınız. Bu, Ether'i derhal iade ettiğinden sözleşmeyi kullanmayı imkansız kılar.

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
Solidity derleyicisini, kaynak kodlu bir sürüm olarak Homebrew aracılığıyla da indirebilirsiniz. Önceden oluşturulmuş dosyalar şu anda desteklenmiyor olabilir.

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

MacOS için, en son Xcode sürümünün yüklü olduğundan emin olun. Bu, Clang C ++ derleyicisini, Xcode IDE'yi ve OS X'te C ++ uygulamaları oluşturmak için gerekli olan diğer Apple geliştirme araçlarını içerir. İlk kez Xcode yüklüyorsanız veya yeni bir sürüm yüklediyseniz önce lisansı onaylamanız gerekir. Komut satırına şu komutu girmelisiniz:

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

Gerekli tüm dış bağımlılıkları macOS, Windows ve sayısız Linux dağıtımına yükleyen bir yardımcı programımıza erişmek için:

```
./scripts/install_deps.sh
```
Veya Windows için:

```
scripts\install_deps.bat
```

### Komut Satırı Oluşturma

Buraya geçmeden önce bir önceki başlıkta açıklanan (bknz. Dış Bağımlılıklar) ön koşulların kurulmuş olduğundan emin olun.

Solidity projeleri yapıyı sağlamlaştırmak için CMake'i kullanır. Tekrarlanan yapıları hızlandırmak için Ccache yüklemek isteyebilirsiniz. CMake, Ccache'i otomatik olarak yükleyecektir. Solidity dilinde kodlama yapmak Linux, macOS ve diğer işletim sistemleri için ile oldukça benzer yapıdadır:

```
mkdir build
cd build
cmake .. && make
```

Daha da kolay olsun derseniz:

```
./scripts/build.sh
```
Windows İçin;
```
mkdir build
cd build
cmake -G "Visual Studio 15 2017 Win64" ..
```

Bu ikinci komut dizisi, o derleme dizininde solidity.sln oluşturulmasına neden olur. Bu dosyaya çift tıklamak, Visual Studio'nun açılmasına yol açacaktır. **Release** yapılandırma sistemini kullanmanızı öneririz, ancak diğerleri de sorunsuz çalışacaktır.

```
cmake --build . --config Release
```
## CMake Seçenekleri

Hangi CMake seçeneklerinin mevcut olduğunu merak ediyorsanız basitçe  `cmake .. -LH` komutunu çalıştırabilirsiniz.

### SMT Çözücüleri

Solidity programları, SMT çözücülerine dirençli geliştirilebilir hatta eğer sistemde bulunurlarsa bunu varsayılan olarak yaparlar. Yine de her çözücü Cmake ile devre dışı bırakılabilir yapıdadır.

Not: Bazı durumlarda, derleme hataları için olası bir geçici çözüm de kullanılabilir.

Yapılması gereken, oluşturma klasörü içinde, varsayılan olarak aktif olan çözücüleri devre dışı bırakmaktır:

```
# Sadece Z3 SMT çözücüsünü devre dışı bırakır.
cmake .. -DUSE_Z3=OFF

# Sadece CVC4 SMT çözücüsünü devre dışı bırakır.
cmake .. -DUSE_CVC4=OFF

# Z3 & CVC4 çözücülerini devre dışı bırakır
cmake .. -DUSE_CVC4=OFF -DUSE_Z3=OFF

```

### Sürüm Dizgisi Detayları

Solidity sürüm dizgisi dört bölümden oluşur:

+ Sürüm numarası
+ Sürüm öncesi etiketi (genellikle `develop.YYYY.MM.DD` veya `night..YYYY.MM.DD` olarak ayarlanır)
+ İşlem biçiminde `commit.GITHASH`
+ Platform ve derleyici ile ilgili ayrıntıları içeren, rasgele sayıda öğeye sahip platform

Yerel değişiklikler varsa, işleme `.mod` ile eklenir.

Tüm değişiklikler, Semver'in gerektirdiği şekilde, Solidity yayınlanma öncesi sürümün Semver yayınlanma öncesi sürümüne eşit olduğu ve Solidity'de bir işlem yapıldığında Semver'deki meta verilerinin de değiştiği bir şekilde gerçekleşir. 

Bir yayın örneği: `0.4.8 + commit.60cc1668.Emscripten.clang`.

Bir yayın öncesi örneği: `0.4.9-nightly.2017.1.17+commit.6ecb4aa3.Emscripten.clang`.

### Sürüm Oluşturma Hakkında Önemli Bilgiler

Bir versiyon değişikliği yapıldığında, sadece yama seviyesi değişikliklerinin yapıldığını varsaydığımız için yama sürümü seviyesi teste tabi tutulur. Değişiklikler ana branş ile birleştirildiğinde, sürüm semver ve değişimin ciddiyetine göre test edilmelidir. Son olarak, yeni sürüm her zaman gecelik derleme değişiklikleri gözetilerek yayınlanır, ancak diğerlerinden farklı olarak bu sürümlerde `prerelease` belirteci yoktur.

**Örnek:**

+ 0.4.0 sürümü çıktı.
+ Gecelik derleme(nightly build) sonucu 0.4.1 versiyonu çıktı.
+ İşleyişi bozmayan değişiklikler tanıtıldı - sürümde değişiklik yok.
+ Büyük bir değişikliği duyuruldu - sürüm 0.5.0'a yükseltilmeye hazırlanıyor.
+ 0.5.0 sürüm çıktı.

Bu durum [pragma sürüm sistemi](https://solidity.readthedocs.io/en/v0.5.4/layout-of-source-files.html#version-pragma) ile iyi çalışmaktadır.


# Solidity Örnekleri

## Oylama

Aşağıdaki sözleşme oldukça karmaşık olmakla birlikte, Solidity'e ait birçok özelliği de inceleme fırsatı vermektedir. Aşağıdaki, bir oylama sözleşmesidir. Elektronik oylamada karşılaşılan temel problemler; doğru kişilere nasıl oy hakkı verileceği ve manipülasyonun nasıl önleneceğidir. Aşağıdaki sözleşme ile bu sorunların tümünü çözmeyeceğiz, ancak en azından temsil edilen oylamanın nasıl yapılabileceğini göstereceğiz, böylece oy sayımı eş zamanlı, otomatik ve tamamen şeffaf olabilecek.

Fikir, kullanılan her oy başına bir sözleşme oluşturmak ve her sözleşme için kısa bir isim oluşturmaktır. Daha sonra başkan olarak görev yapan sözleşmenin yaratıcısı her bir adrese ayrı ayrı oy kullanma hakkı tanıyacaktır.

Adreslerin arkasındaki kişiler oylama sırasında kendilerini oylayabilir veya oylarını güvendikleri bir kişiye devredebilirler.

Oylama süresinin sonunda, winningProposal() fonksiyonu ile en yüksek oyu alan belirlenecek ve bu kişi oylamayı kazanacaktır.

```
pragma solidity >=0.4.22 <0.6.0;

/// @title Voting with delegation.
contract Ballot {
    // This declares a new complex type which will
    // be used for variables later.
    // It will represent a single voter.
    struct Voter {
        uint weight; // weight is accumulated by delegation
        bool voted;  // if true, that person already voted
        address delegate; // person delegated to
        uint vote;   // index of the voted proposal
    }

    // This is a type for a single proposal.
    struct Proposal {
        bytes32 name;   // short name (up to 32 bytes)
        uint voteCount; // number of accumulated votes
    }

    address public chairperson;

    // This declares a state variable that
    // stores a `Voter` struct for each possible address.
    mapping(address => Voter) public voters;

    // A dynamically-sized array of `Proposal` structs.
    Proposal[] public proposals;

    /// Create a new ballot to choose one of `proposalNames`.
    constructor(bytes32[] memory proposalNames) public {
        chairperson = msg.sender;
        voters[chairperson].weight = 1;

        // For each of the provided proposal names,
        // create a new proposal object and add it
        // to the end of the array.
        for (uint i = 0; i < proposalNames.length; i++) {
            // `Proposal({...})` creates a temporary
            // Proposal object and `proposals.push(...)`
            // appends it to the end of `proposals`.
            proposals.push(Proposal({
                name: proposalNames[i],
                voteCount: 0
            }));
        }
    }

    // Give `voter` the right to vote on this ballot.
    // May only be called by `chairperson`.
    function giveRightToVote(address voter) public {
        // If the first argument of `require` evaluates
        // to `false`, execution terminates and all
        // changes to the state and to Ether balances
        // are reverted.
        // This used to consume all gas in old EVM versions, but
        // not anymore.
        // It is often a good idea to use `require` to check if
        // functions are called correctly.
        // As a second argument, you can also provide an
        // explanation about what went wrong.
        require(
            msg.sender == chairperson,
            "Only chairperson can give right to vote."
        );
        require(
            !voters[voter].voted,
            "The voter already voted."
        );
        require(voters[voter].weight == 0);
        voters[voter].weight = 1;
    }

    /// Delegate your vote to the voter `to`.
    function delegate(address to) public {
        // assigns reference
        Voter storage sender = voters[msg.sender];
        require(!sender.voted, "You already voted.");

        require(to != msg.sender, "Self-delegation is disallowed.");

        // Forward the delegation as long as
        // `to` also delegated.
        // In general, such loops are very dangerous,
        // because if they run too long, they might
        // need more gas than is available in a block.
        // In this case, the delegation will not be executed,
        // but in other situations, such loops might
        // cause a contract to get "stuck" completely.
        while (voters[to].delegate != address(0)) {
            to = voters[to].delegate;

            // We found a loop in the delegation, not allowed.
            require(to != msg.sender, "Found loop in delegation.");
        }

        // Since `sender` is a reference, this
        // modifies `voters[msg.sender].voted`
        sender.voted = true;
        sender.delegate = to;
        Voter storage delegate_ = voters[to];
        if (delegate_.voted) {
            // If the delegate already voted,
            // directly add to the number of votes
            proposals[delegate_.vote].voteCount += sender.weight;
        } else {
            // If the delegate did not vote yet,
            // add to her weight.
            delegate_.weight += sender.weight;
        }
    }

    /// Give your vote (including votes delegated to you)
    /// to proposal `proposals[proposal].name`.
    function vote(uint proposal) public {
        Voter storage sender = voters[msg.sender];
        require(sender.weight != 0, "Has no right to vote");
        require(!sender.voted, "Already voted.");
        sender.voted = true;
        sender.vote = proposal;

        // If `proposal` is out of the range of the array,
        // this will throw automatically and revert all
        // changes.
        proposals[proposal].voteCount += sender.weight;
    }

    /// @dev Computes the winning proposal taking all
    /// previous votes into account.
    function winningProposal() public view
            returns (uint winningProposal_)
    {
        uint winningVoteCount = 0;
        for (uint p = 0; p < proposals.length; p++) {
            if (proposals[p].voteCount > winningVoteCount) {
                winningVoteCount = proposals[p].voteCount;
                winningProposal_ = p;
            }
        }
    }

    // Calls winningProposal() function to get the index
    // of the winner contained in the proposals array and then
    // returns the name of the winner
    function winnerName() public view
            returns (bytes32 winnerName_)
    {
        winnerName_ = proposals[winningProposal()].name;
    }
}

```
### Muhtemel İyileştirmeler

Şu anda, tüm katılımcılara oy kullanma hakkı atamak için birçok işleme ihtiyaç var. Daha iyi bir yol düşünebilir misiniz?


## Gizli Açık Arttırma

Bu bölümde, Ethereum'da tamamen gizli bir açık artırma sözleşmesi oluşturmanın ne kadar kolay olduğunu göstereceğiz. Herkesin verilen teklifleri görebileceği gizli olmayan bir açık artırmayla başlayacağız ve daha sonra bu sözleşmeyi teklif süresi sona erene kadar gerçek teklifi görmenin mümkün olmadığı gizli bir açık artırmaya çevireceğiz.

### Gizli Olmayan Bir Açık Arttırma

Aşağıdaki basit ve gizli olmayan açık artırma sözleşmesinin genel fikri, herkesin ihale sürecinde açık olarak teklif verebilmesidir. Teklifi verenler, tekliflerine vadettikleri para/Ether ile bağlanırlar. En yüksek teklifin bir başkasının teklifi ile aşılması durumunda, eski en yüksek teklif bozulmuş olur. İhale süresinin bitmesinin ardından, geçerli teklifi veren ve satıcı manuel olarak sözleşmeyi onaylayarak ürün veya servis alışverişini tamamlarlar - sözleşmeler bu süreç olmadan aktif hale gelemezler.

```
pragma solidity >=0.4.22 <0.6.0;

contract SimpleAuction {
    // Parameters of the auction. Times are either
    // absolute unix timestamps (seconds since 1970-01-01)
    // or time periods in seconds.
    address payable public beneficiary;
    uint public auctionEndTime;

    // Current state of the auction.
    address public highestBidder;
    uint public highestBid;

    // Allowed withdrawals of previous bids
    mapping(address => uint) pendingReturns;

    // Set to true at the end, disallows any change.
    // By default initialized to `false`.
    bool ended;

    // Events that will be emitted on changes.
    event HighestBidIncreased(address bidder, uint amount);
    event AuctionEnded(address winner, uint amount);

    // The following is a so-called natspec comment,
    // recognizable by the three slashes.
    // It will be shown when the user is asked to
    // confirm a transaction.

    /// Create a simple auction with `_biddingTime`
    /// seconds bidding time on behalf of the
    /// beneficiary address `_beneficiary`.
    constructor(
        uint _biddingTime,
        address payable _beneficiary
    ) public {
        beneficiary = _beneficiary;
        auctionEndTime = now + _biddingTime;
    }

    /// Bid on the auction with the value sent
    /// together with this transaction.
    /// The value will only be refunded if the
    /// auction is not won.
    function bid() public payable {
        // No arguments are necessary, all
        // information is already part of
        // the transaction. The keyword payable
        // is required for the function to
        // be able to receive Ether.

        // Revert the call if the bidding
        // period is over.
        require(
            now <= auctionEndTime,
            "Auction already ended."
        );

        // If the bid is not higher, send the
        // money back.
        require(
            msg.value > highestBid,
            "There already is a higher bid."
        );

        if (highestBid != 0) {
            // Sending back the money by simply using
            // highestBidder.send(highestBid) is a security risk
            // because it could execute an untrusted contract.
            // It is always safer to let the recipients
            // withdraw their money themselves.
            pendingReturns[highestBidder] += highestBid;
        }
        highestBidder = msg.sender;
        highestBid = msg.value;
        emit HighestBidIncreased(msg.sender, msg.value);
    }

    /// Withdraw a bid that was overbid.
    function withdraw() public returns (bool) {
        uint amount = pendingReturns[msg.sender];
        if (amount > 0) {
            // It is important to set this to zero because the recipient
            // can call this function again as part of the receiving call
            // before `send` returns.
            pendingReturns[msg.sender] = 0;

            if (!msg.sender.send(amount)) {
                // No need to call throw here, just reset the amount owing
                pendingReturns[msg.sender] = amount;
                return false;
            }
        }
        return true;
    }

    /// End the auction and send the highest bid
    /// to the beneficiary.
    function auctionEnd() public {
        // It is a good guideline to structure functions that interact
        // with other contracts (i.e. they call functions or send Ether)
        // into three phases:
        // 1. checking conditions
        // 2. performing actions (potentially changing conditions)
        // 3. interacting with other contracts
        // If these phases are mixed up, the other contract could call
        // back into the current contract and modify the state or cause
        // effects (ether payout) to be performed multiple times.
        // If functions called internally include interaction with external
        // contracts, they also have to be considered interaction with
        // external contracts.

        // 1. Conditions
        require(now >= auctionEndTime, "Auction not yet ended.");
        require(!ended, "auctionEnd has already been called.");

        // 2. Effects
        ended = true;
        emit AuctionEnded(highestBidder, highestBid);

        // 3. Interaction
        beneficiary.transfer(highestBid);
    }
}

```
### Gizli Açık Arttırma

Aşağıdaki gibi bir gizli açık arttırma sözleşmesi elde etmek için bir önceki açık artırma sözleşmesine eklemeler yapalım. Gizli bir açık artırmanın avantajı, ihale süresinin sonuna doğru zaman baskısı olmamasıdır. Blockchain gibi şeffaf bir işlem platformunda gizli bir açık artırma oluşturmak, çelişkili bir durum gibi görünebilir; ancak kriptografi bu durumda yardımımıza yetişiyor.

İhale süreci boyunca, teklif veren kişi teklifini gerçekten göndermez, teklif şifrelenmiş(hashed) şekilde gönderilir. Yeterince uzun iki teklifin şifrelenince aynı değere tekabül etmesi pratik olarak imkansıza yakın kabul edildiğinden, teklif sahipleri için sakıncalı bir durum yoktur. İhale süresinin bitmesinin ardından, teklif verenlerin tekliflerini açıklamaları istenir: Şifrelenmemiş olarak gönderdikleri tekliflerin, burada açıkladıkları değerler ile aynı olup olmadığını kontrol eden bir sözleşme yardımı ile en yüksek teklifi veren ihaleyi kazanmış olur. 

Karşılaşılabilecek bir sorun, gizli açık arttırmada teklif veren için teklifin aynı anda **bağlayıcı ve gizli** hale nasıl getirileceğidir: Teklif verenin, açık artırmayı kazandıktan sonra para göndermemesini önlemenin tek yolu, bu parayı teklifini yaptığı sırada ondan temin etmektir. Para transferleri Ethereum'da gizlenemediğinden, herkes gönderilen değeri görebilir.

Aşağıdaki sözleşme, bu sorunu en yüksek tekliften daha büyük olan herhangi bir değeri kabul ederek çözmektedir. Tabii ki bu sadece tekliflerin ifşası aşamasında kontrol edilebileceğinden, bazı tekliflerin kasıtlı olarak geçersiz şekilde gönderilmesine sebep olabilir. Bu sayede ihaleye katılanlar birkaç tane çok yüksek veya çok alçak geçersiz teklifle rekabeti kızıştırabilirler.

```
pragma solidity >0.4.23 <0.6.0;

contract BlindAuction {
    struct Bid {
        bytes32 blindedBid;
        uint deposit;
    }

    address payable public beneficiary;
    uint public biddingEnd;
    uint public revealEnd;
    bool public ended;

    mapping(address => Bid[]) public bids;

    address public highestBidder;
    uint public highestBid;

    // Allowed withdrawals of previous bids
    mapping(address => uint) pendingReturns;

    event AuctionEnded(address winner, uint highestBid);

    /// Modifiers are a convenient way to validate inputs to
    /// functions. `onlyBefore` is applied to `bid` below:
    /// The new function body is the modifier's body where
    /// `_` is replaced by the old function body.
    modifier onlyBefore(uint _time) { require(now < _time); _; }
    modifier onlyAfter(uint _time) { require(now > _time); _; }

    constructor(
        uint _biddingTime,
        uint _revealTime,
        address payable _beneficiary
    ) public {
        beneficiary = _beneficiary;
        biddingEnd = now + _biddingTime;
        revealEnd = biddingEnd + _revealTime;
    }

    /// Place a blinded bid with `_blindedBid` =
    /// keccak256(abi.encodePacked(value, fake, secret)).
    /// The sent ether is only refunded if the bid is correctly
    /// revealed in the revealing phase. The bid is valid if the
    /// ether sent together with the bid is at least "value" and
    /// "fake" is not true. Setting "fake" to true and sending
    /// not the exact amount are ways to hide the real bid but
    /// still make the required deposit. The same address can
    /// place multiple bids.
    function bid(bytes32 _blindedBid)
        public
        payable
        onlyBefore(biddingEnd)
    {
        bids[msg.sender].push(Bid({
            blindedBid: _blindedBid,
            deposit: msg.value
        }));
    }

    /// Reveal your blinded bids. You will get a refund for all
    /// correctly blinded invalid bids and for all bids except for
    /// the totally highest.
    function reveal(
        uint[] memory _values,
        bool[] memory _fake,
        bytes32[] memory _secret
    )
        public
        onlyAfter(biddingEnd)
        onlyBefore(revealEnd)
    {
        uint length = bids[msg.sender].length;
        require(_values.length == length);
        require(_fake.length == length);
        require(_secret.length == length);

        uint refund;
        for (uint i = 0; i < length; i++) {
            Bid storage bidToCheck = bids[msg.sender][i];
            (uint value, bool fake, bytes32 secret) =
                    (_values[i], _fake[i], _secret[i]);
            if (bidToCheck.blindedBid != keccak256(abi.encodePacked(value, fake, secret))) {
                // Bid was not actually revealed.
                // Do not refund deposit.
                continue;
            }
            refund += bidToCheck.deposit;
            if (!fake && bidToCheck.deposit >= value) {
                if (placeBid(msg.sender, value))
                    refund -= value;
            }
            // Make it impossible for the sender to re-claim
            // the same deposit.
            bidToCheck.blindedBid = bytes32(0);
        }
        msg.sender.transfer(refund);
    }

    // This is an "internal" function which means that it
    // can only be called from the contract itself (or from
    // derived contracts).
    function placeBid(address bidder, uint value) internal
            returns (bool success)
    {
        if (value <= highestBid) {
            return false;
        }
        if (highestBidder != address(0)) {
            // Refund the previously highest bidder.
            pendingReturns[highestBidder] += highestBid;
        }
        highestBid = value;
        highestBidder = bidder;
        return true;
    }

    /// Withdraw a bid that was overbid.
    function withdraw() public {
        uint amount = pendingReturns[msg.sender];
        if (amount > 0) {
            // It is important to set this to zero because the recipient
            // can call this function again as part of the receiving call
            // before `transfer` returns (see the remark above about
            // conditions -> effects -> interaction).
            pendingReturns[msg.sender] = 0;

            msg.sender.transfer(amount);
        }
    }

    /// End the auction and send the highest bid
    /// to the beneficiary.
    function auctionEnd()
        public
        onlyAfter(revealEnd)
    {
        require(!ended);
        emit AuctionEnded(highestBidder, highestBid);
        ended = true;
        beneficiary.transfer(highestBid);
    }
}

```

## Güvenli Uzaktan Satın Alım

```
pragma solidity >=0.4.22 <0.6.0;

contract Purchase {
    uint public value;
    address payable public seller;
    address payable public buyer;
    enum State { Created, Locked, Inactive }
    State public state;

    // Ensure that `msg.value` is an even number.
    // Division will truncate if it is an odd number.
    // Check via multiplication that it wasn't an odd number.
    constructor() public payable {
        seller = msg.sender;
        value = msg.value / 2;
        require((2 * value) == msg.value, "Value has to be even.");
    }

    modifier condition(bool _condition) {
        require(_condition);
        _;
    }

    modifier onlyBuyer() {
        require(
            msg.sender == buyer,
            "Only buyer can call this."
        );
        _;
    }

    modifier onlySeller() {
        require(
            msg.sender == seller,
            "Only seller can call this."
        );
        _;
    }

    modifier inState(State _state) {
        require(
            state == _state,
            "Invalid state."
        );
        _;
    }

    event Aborted();
    event PurchaseConfirmed();
    event ItemReceived();

    /// Abort the purchase and reclaim the ether.
    /// Can only be called by the seller before
    /// the contract is locked.
    function abort()
        public
        onlySeller
        inState(State.Created)
    {
        emit Aborted();
        state = State.Inactive;
        seller.transfer(address(this).balance);
    }

    /// Confirm the purchase as buyer.
    /// Transaction has to include `2 * value` ether.
    /// The ether will be locked until confirmReceived
    /// is called.
    function confirmPurchase()
        public
        inState(State.Created)
        condition(msg.value == (2 * value))
        payable
    {
        emit PurchaseConfirmed();
        buyer = msg.sender;
        state = State.Locked;
    }

    /// Confirm that you (the buyer) received the item.
    /// This will release the locked ether.
    function confirmReceived()
        public
        onlyBuyer
        inState(State.Locked)
    {
        emit ItemReceived();
        // It is important to change the state first because
        // otherwise, the contracts called using `send` below
        // can call in again here.
        state = State.Inactive;

        // NOTE: This actually allows both the buyer and the seller to
        // block the refund - the withdraw pattern should be used.

        buyer.transfer(value);
        seller.transfer(address(this).balance);
    }
}

```
## Mikro Ödeme Kanalı

In this section we will learn how to build an example implementation of a payment channel. It uses cryptographic signatures to make repeated transfers of Ether between the same parties secure, instantaneous, and without transaction fees. For the example, we need to understand how to sign and verify signatures, and setup the payment channel.

Bu bölümde, örnek bir ödeme kanalı uygulamasının nasıl geliştirileceğini öğreneceğiz. Aynı taraflar arasında tekrarlanan Ether transferini güvenli, hızlı ve işlem ücreti ödemeden yapmak için kriptografik imzalar kullanır. Vereceğimiz örnek için imzayı nasıl oluşturacağımızı, doğrulayacağımızı ve ödeme kanalını nasıl kuracağımızı anlamamız gerekiyor.

### İmza Oluşturma ve Doğrulama

Alice'in Bob'a bir miktar Ether göndermek istediğini düşünün, yani Alice gönderen, Bob ise alıcıdır.

Alice'in kriptografik olarak imzalanmış mesajları zincir dışında (örneğin, e-posta yoluyla) Bob'a göndermesi gerekir ve bu bir bakıma çek yazmaya benzer.

Alice ve Bob, Ethereum ile yapılan akıllı sözleşmedeki işlemleri onaylamak için imzalarını kullanırlar. Burada Alice, Ether'i aktarmasına izin veren basit bir akıllı sözleşme oluştursa da, ödeme başlatmak için bu sözleşmeden bir fonksiyon çağırmak yerine, Bob'un bunu yapmasını ve böylece işlem ücretini ödemesini sağlayabilir.

Sözleşme aşağıdaki şekilde çalışacaktır:

1. Alice, yapılacak ödemeleri karşılayacak kadar Ether'i ekleyerek, `ReceiverPays` sözleşmesini oluşturur.
2. Alice, özel anahtarıyla bir mesaj imzalayarak sözleşmeye onay verir.
3. Alice, kriptografik olarak imzalanmış mesajı Bob'a gönderir. Mesajın gizli tutulması gerekmez (daha sonra açıklanır) ve onu gönderme mekanizması veya yöntemi önemli değildir.
4. Bob, imzalı mesajı akıllı sözleşmeye sunarak ödemelerini talep eder, iletinin gerçekliğini doğrular ve ardından ödemesini alır.


#### İmza Oluşturma

Alice'in işlemi imzalamak için Ethereum ağı ile etkileşime girmesi gerekmez, süreç tamamen çevrimdışı gerçekleşir. Bu dökümantasyonda vereceğimiz örnekte, [EIP-762'de](https://github.com/ethereum/EIPs/pull/712) açıklanan yöntemi kullanarak, bir dizi başka güvenlik avantajı sağladığı için, [web3.js](https://github.com/ethereum/web3.js) ve [MetaMask](https://metamask.io/) kullanarak tarayıcıdaki mesajları imzalayacağız.

```
/// Hashing first makes things easier var hash = web3.utils.sha3(“message to sign”); web3.eth.personal.sign(hash, web3.eth.defaultAccount, function () { console.log(“Signed”); });

```
### [Uyarı](#)

> `Web3.eth.personal.sign` iletinin uzunluğunu imzalanan verilerin önüne ekler. İlk önce şifreleme yapılacağında, elde edilen mesaj her şekilde tam olarak 32 byte uzunluğunda olurken ve önek olarak eklenen uzunluk da her zaman aynı olacaktır.

#### Ne İmzalanmalı?

Ödeme komutları içeren bir sözleşme için imzalı mesaj şunları içermelidir:

+ Alıcının adresi
+ Aktarılacak miktar
+ Tekrarlama saldırılarına karşı koruma

Bir tekrarlama saldırısı, imzalı bir mesajın ikinci bir işlem için yetki talebinde bulunmak üzere yeniden kullanılmasıdır. Tekrarlama saldırılarından kaçınmak için, Ethereum işlemleri için kullandığımız şeyin aynısını, nonce adı verilen ve hesap tarafından gönderilen işlem sayısını ifade eden bir sayıyı kullanıyoruz . Akıllı sözleşme, nonce sayısının birden çok kez kullanılıp kullanılmadığını kontrol ederek, bu saldırıların önüne geçer.

Tekrarlama saldırısının gerçekleşmesinin bir başka yolu da, sözleşme sahibinin `RecieverPays` akıllı sözleşmesi başlatması ve ardından sözleşmeyi yoketmek istemesi durumudur. Sonrasında, `RecipientPays` sözleşmesini yeniden başlatmak istediklerinde, önceki nonce sayısını bilmeyen bu yeni sözleşme dışarıdan eski mesaj kullanılarak yapılacak saldırılara açık olacaktır.

Alice, sözleşmenin adresini iletiye ekleyerek bu saldırıya karşı koruma sağlayabilir ve yalnızca sözleşmenin adresini içeren iletiler kabul edilirse bu saldırıdan korunabilir. Bunun bir örneğini, bu bölümün sonundaki detaylı sözleşmenin `claimPAyment ()` fonksiyonunun ilk iki satırında bulabilirsiniz.

#### Paket Argümanları

Şimdi imzalı mesaja hangi bilgileri dahil edeceğimizi belirlediğimize göre, mesajı bir araya getirmeye, iletmeye ve imzalamaya hazırız. Basit olması için, verileri birleştiriyoruz. [Ethereumjs-abi kütüphanesi](https://github.com/ethereumjs/ethereumjs-abi), Solidity’nin `abi.encodePacked` kullanarak kodlanan argümanlara uygulanan `keccak256` fonksiyonunun davranışını taklit eden `soliditySHA3` adlı bir fonksiyon sunar. İşte `ReceiverPays` örneği için uygun imzayı oluşturan bu JavaScript fonksiyonu:

```
// recipient is the address that should be paid.
// amount, in wei, specifies how much ether should be sent.
// nonce can be any unique number to prevent replay attacks
// contractAddress is used to prevent cross-contract replay attacks
function signPayment(recipient, amount, nonce, contractAddress, callback) {
    var hash = "0x" + abi.soliditySHA3(
        ["address", "uint256", "uint256", "address"],
        [recipient, amount, nonce, contractAddress]
    ).toString("hex");

    web3.eth.personal.sign(hash, web3.eth.defaultAccount, callback);
}
```
#### Solidity'de İmza Kurtarmak

Genel olarak, ECDSA imzaları `r` ve `s` olmak üzere iki parametreden oluşur. Ethereum'daki imzalar, mesajı imzalamak için hangi hesabın özel anahtarının kullanıldığını ve işlemin göndereni olduğunu doğrulamak için kullanabileceğiniz, `v` adı verilen üçüncü bir parametre içerir. Solidity, `r`, `s` ve `v` parametreleriyle birlikte bir mesajı kabul eden ve mesajı imzalamak için kullanılan adresi döndüren yerleşik bir fonksiyon çıkarır.

#### İmza Parametrelerini Çıkarma

Web3.js tarafından üretilen imzalar, `r`, `s` ve `v`'nin birleştirilmesidir, bu nedenle ilk adım bu parametreleri birbirinden ayırmaktır. Bunu müşteri tarafında yapabilirsiniz, ancak akıllı sözleşmeye tarafında yapmak, üç yerine yalnızca bir imza parametresi göndermeniz gerektiği anlamına gelir. Bir bayt dizisini bileşen parçalarına bölmek karmaşık bir işlemdir. Bu yüzden işi `splitSignature` fonksiyonu(bu bölümün sonunda yapılan sözleşmedeki üçüncü fonksiyondaki gibi) ile yapmak için satır içi derleme kullanırız.

#### Mesaj Hash'inin Hesaplanması

Akıllı sözleşme tam olarak hangi parametrelerin imzalandığını bilmeli ve asıl mesajı kullanılan parametreler yardımıyla yeniden yaratarak sonucu imza doğrulaması için kullanmalıdır. `Prefixed` ve `recoverSigner` fonksiyonları, `claimPayment` fonksiyonunda bunu yapar.

##### Detaylı Bir Sözleşme

```
pragma solidity >=0.4.24 <0.6.0;

contract ReceiverPays {
    address owner = msg.sender;

    mapping(uint256 => bool) usedNonces;

    constructor() public payable {}

    function claimPayment(uint256 amount, uint256 nonce, bytes memory signature) public {
        require(!usedNonces[nonce]);
        usedNonces[nonce] = true;

        // this recreates the message that was signed on the client
        bytes32 message = prefixed(keccak256(abi.encodePacked(msg.sender, amount, nonce, this)));

        require(recoverSigner(message, signature) == owner);

        msg.sender.transfer(amount);
    }

    /// destroy the contract and reclaim the leftover funds.
    function kill() public {
        require(msg.sender == owner);
        selfdestruct(msg.sender);
    }

    /// signature methods.
    function splitSignature(bytes memory sig)
        internal
        pure
        returns (uint8 v, bytes32 r, bytes32 s)
    {
        require(sig.length == 65);

        assembly {
            // first 32 bytes, after the length prefix.
            r := mload(add(sig, 32))
            // second 32 bytes.
            s := mload(add(sig, 64))
            // final byte (first byte of the next 32 bytes).
            v := byte(0, mload(add(sig, 96)))
        }

        return (v, r, s);
    }

    function recoverSigner(bytes32 message, bytes memory sig)
        internal
        pure
        returns (address)
    {
        (uint8 v, bytes32 r, bytes32 s) = splitSignature(sig);

        return ecrecover(message, v, r, s);
    }

    /// builds a prefixed hash to mimic the behavior of eth_sign.
    function prefixed(bytes32 hash) internal pure returns (bytes32) {
        return keccak256(abi.encodePacked("\x19Ethereum Signed Message:\n32", hash));
    }
}
```

### Basit Bir Ödeme Kanalı Yazmak

Alice şimdi de bir ödeme kanalını basit fakat tamanlanmış bir şekilde oluşturmak istemektedir. Ödeme kanalları, tekrar tekrar Ether transferini güvenli, anında ve işlem ücreti ödemeden yapmak için kriptografik imzalar kullanır.

#### What is a Payment Channel?

Ödeme kanalları, katılımcıların işlem yapmaksızın tekrar tekrar Ether transferi yapabilmelerini sağlar. Bu, işlemlerle ilgili gecikmelerden ve ücretlerden kaçınabileceğiniz anlamına gelir. İki taraf (Alice ve Bob) arasındaki tek yönlü basit bir ödeme kanalını keşfedeceğiz. Bu süreç üç adımdan oluşur:

+ Alice, bir akıllı sözleşmeye Ether gönderir. Bu ödeme kanalını “açar”.
+ Alice, bu Ether'in ne kadarını alıcıya iletmek istediğini belirten mesajları imzalar. Bu adım her ödeme için tekrarlanır.
+ Bob, ödeme kanalında kendisine teslim edilecek “Ether”i alarak ve kalanı gönderene geri gönderir ve kanalı “kapatır”.

#### [Uyarı](#)

> Yalnızca 1. ve 3. adımlar, Ethereum üzerinde işlem gerçekleştirir, 2. adım, gönderenin alıcıya zincir dışı yöntemlerle (ör. E-posta) şifreli olarak imzalanmış bir mesaj ilettiğini gösterir. Bu, herhangi bir sayıda aktarımı desteklemek için yalnızca iki işlem yapılması gerektiği anlamına gelir.

Bob'un ödemesini alması garantilidir, çünkü akıllı sözleşme Ether'i kabul eder ve geçerli bir imzalı mesaj karşılığında teslimi gerçekleştirir. Akıllı sözleşme ayrıca bir zaman aşımı da barındırır. Bu sayede alıcı kanalı kapatmayı reddetse bile Alice'in fonlarını geri alması garanti edilir. Kanalı ne kadar süre açık tutacaklarına karar vermek, ödeme kanalındaki katılımcılara bağlıdır. Dakika başına ödeme yaptığımız bir internet kafe gibi kısa vadeli işlemlerden, bir çalışanımızın aylık maaşını ödediğimiz uzun vadeli işlemlere kadar dilediğimiz vadede kanallar yaratabiliriz.

### Bir Ödeme Kanalı Açmak

Ödeme kanalını açmak için, Alice, gönderilmek istenen Eter'i, alıcıyı ve kanalın varolması için maksimum süreyi belirleyerek akıllı sözleşmeyi oluşturur. Bu işlem, bölümün sonundaki sözleşmeden bulunan `SimplePaymentChannel` fonksiyonunda gösterilmiştir.

### Ödeme Yapmak

Alice, Bob'a imzalı mesajlar göndererek ödeme yapar. Bu adım tamamen Ethereum ağının dışında gerçekleştirilir. Mesajlar gönderen tarafından şifreli olarak imzalanır ve daha sonra doğrudan alıcıya iletilir.

Her mesaj aşağıdaki bilgileri içerir:

+ Akıllı sözleşmenin adresi, sözleşmeler arası tekrarlama saldırılarını önlemek için kullanılır.
+ Alıcıya borçlu olunan toplam Ether miktarı.

Bir ödeme kanalı, bir dizi transferin sonunda yalnızca bir kez kapatılır. Bu nedenle, gönderilen mesajlardan yalnızca biri için ödeme yapılır. Her bir mesajın, ayrı ayrı mikro ödeme miktarı içermemesi bunun yerine toplam toplam Ether borcu belirtmesi işte bu yüzdendir. Alıcı, doğal olarak en son mesajı ödemeyi seçecektir, çünkü toplamda en yüksek fiyat bu mesaja aittir. Akıllı sözleşme temelde yalnızca bir mesajla çalıştırıldığından, nonce numarası burada gerekli değildir. Bunun yerine akıllı sözleşmenin adresi, bir ödeme kanalı için amaçlanan bir iletinin farklı bir kanal tarafından kullanılmasını önlemeye devam eder.

Önceki bölümden bir mesajı kriptografik olarak imzalamak için değiştirilmiş JavaScript kodu:

```
function constructPaymentMessage(contractAddress, amount) {
    return abi.soliditySHA3(
        ["address", "uint256"],
        [contractAddress, amount]
    );
}

function signMessage(message, callback) {
    web3.eth.personal.sign(
        "0x" + message.toString("hex"),
        web3.eth.defaultAccount,
        callback
    );
}

// contractAddress is used to prevent cross-contract replay attacks.
// amount, in wei, specifies how much Ether should be sent.

function signPayment(contractAddress, amount, callback) {
    var message = constructPaymentMessage(contractAddress, amount);
    signMessage(message, callback);
}

```
### Bir Ödeme Kanalını Kapatmak

Bob tüm ödemeleri teslim aldığında, akıllı sözleşmedeki kapatma işlevini çağırarak ödeme kanalını kapatmalıdır. `Close` fonksiyonu alıcıya borçlu olunan Ether'in tamamını ödeyerek ve sözleşmeyi imha eder; kalan Ether'i ise Alice'e geri gönderir. Kanalı kapatmak için Bob'un Alice tarafından imzalanmış bir mesaj vermesi gerekir.

Akıllı sözleşme bu mesajın, Alice'e ait geçerli bir imza içerdiğini doğrulamalıdır. Bu doğrulamayı yapma işlemi, alıcının kullandığı işlemle aynıdır. `ReceiverPays` sözleşmesinden ödünç alınan Solidity fonksiyonları `isValidSignature` ve `recoverSigner`, önceki bölümdeki JavaScript benzerleri gibi çalışır.

Sadece ödeme kanalı alıcısı, doğal olarak en son mesajı aldığı için, `close` fonksiyonunu çağırabilir. Gönderenin bu işlevi çağırmasına izin verilirse, daha az miktar ödeyerek bir mesaj vermeyi tercih edebilir ve alıcıya borçlu olduğu tüm Ether miktarını vermeden kanalı kapatır.

`close` fonksiyonu, imzalanan iletinin verilen parametrelerle eşleştiğini doğrular. Her şeyi kontrol eder, alıcıya Ether'in ona ait kısmını gönderir ve geri kalan Ether miktarını gönderene geri iletir. `selfdestruct` fonksiyonunu aşağıdaki detaylı sözleşmede görebilirsiniz.

### Ödeme Kanalının Sonlandırılması

Bob, ödeme kanalını dilediği zaman kapatabilir, ancak başaramazsa, Alice'in sözleşme sonunda geri alacağı Ether'i almak için bir yola ihtiyacı vardır. Sözleşme devri sırasında bir zaman aşımı süresi belirlenir. Bu süreye ulaşıldığında, Alice fonlarını geri almak için hak talebinde bulunabilir. `ClaimTimeout` işlevini aşağıdaki detaylı sözleşmede görebilirsiniz.

#### Detaylı Sözleşme

```
pragma solidity >=0.4.24 <0.6.0;

contract SimplePaymentChannel {
    address payable public sender;      // The account sending payments.
    address payable public recipient;   // The account receiving the payments.
    uint256 public expiration;  // Timeout in case the recipient never closes.

    constructor (address payable _recipient, uint256 duration)
        public
        payable
    {
        sender = msg.sender;
        recipient = _recipient;
        expiration = now + duration;
    }

    function isValidSignature(uint256 amount, bytes memory signature)
        internal
        view
        returns (bool)
    {
        bytes32 message = prefixed(keccak256(abi.encodePacked(this, amount)));

        // check that the signature is from the payment sender
        return recoverSigner(message, signature) == sender;
    }

    /// the recipient can close the channel at any time by presenting a
    /// signed amount from the sender. the recipient will be sent that amount,
    /// and the remainder will go back to the sender
    function close(uint256 amount, bytes memory signature) public {
        require(msg.sender == recipient);
        require(isValidSignature(amount, signature));

        recipient.transfer(amount);
        selfdestruct(sender);
    }

    /// the sender can extend the expiration at any time
    function extend(uint256 newExpiration) public {
        require(msg.sender == sender);
        require(newExpiration > expiration);

        expiration = newExpiration;
    }

    /// if the timeout is reached without the recipient closing the channel,
    /// then the Ether is released back to the sender.
    function claimTimeout() public {
        require(now >= expiration);
        selfdestruct(sender);
    }

    /// All functions below this are just taken from the chapter
    /// 'creating and verifying signatures' chapter.

    function splitSignature(bytes memory sig)
        internal
        pure
        returns (uint8 v, bytes32 r, bytes32 s)
    {
        require(sig.length == 65);

        assembly {
            // first 32 bytes, after the length prefix
            r := mload(add(sig, 32))
            // second 32 bytes
            s := mload(add(sig, 64))
            // final byte (first byte of the next 32 bytes)
            v := byte(0, mload(add(sig, 96)))
        }

        return (v, r, s);
    }

    function recoverSigner(bytes32 message, bytes memory sig)
        internal
        pure
        returns (address)
    {
        (uint8 v, bytes32 r, bytes32 s) = splitSignature(sig);

        return ecrecover(message, v, r, s);
    }

    /// builds a prefixed hash to mimic the behavior of eth_sign.
    function prefixed(bytes32 hash) internal pure returns (bytes32) {
        return keccak256(abi.encodePacked("\x19Ethereum Signed Message:\n32", hash));
    }
}
```
#### [Uyarı](#)

> `SplitSignature` fonksiyonu gerekli tüm güvenlik tedbirlerini kullanmaz. Gerçek bir uygulama, openzepplin’in [bu sürümü](https://github.com/OpenZeppelin/openzeppelin-solidity/blob/master/contracts/ECRecovery.sol) gibi daha titizlikle test edilmiş bir kütüphane kullanmalıdır.

### Ödemeleri Onaylama

Önceki bölümden farklı olarak, bir ödeme kanalındaki iletiler için hemen ödeme yapılmaz. Alıcı en son iletiyi takip eder ve ödeme kanalını kapatma zamanı geldiğinde onu kapatma talebinde bulunur. Bu, alıcının her iletiyi kendi kendine doğrulamasının kritik olduğu anlamına gelir. Aksi halde, alıcının sonunda ödemesini alabileceğinin garantisi yoktur.

Alıcı, aşağıdaki her mesaj için aşağıdaki bilgileri doğrulamalıdır:

+ Mesajdaki irtibat adresinin ödeme kanalıyla eşleştiği
+ Yeni toplamın beklenen miktar olduğu
+ Yeni toplamın, beklenilen Ether miktarını aşmadığı
+ İmzanın geçerli olduğunu ve ödeme kanalı göndericisinden geldiği

Bu doğrulamayı yazmak için `ethereumjs-util` kütüphanesini kullanacağız. Son adım birkaç şekilde yapılabilir ancak biz JavaScript kullanacağız. Aşağıdaki kod, `constructMessage` fonksiyonunu yukarıdaki `JavaScript'te İmzalama` kodundan alınmıştır:

```
// this mimics the prefixing behavior of the eth_sign JSON-RPC method.
function prefixed(hash) {
    return ethereumjs.ABI.soliditySHA3(
        ["string", "bytes32"],
        ["\x19Ethereum Signed Message:\n32", hash]
    );
}

function recoverSigner(message, signature) {
    var split = ethereumjs.Util.fromRpcSig(signature);
    var publicKey = ethereumjs.Util.ecrecover(message, split.v, split.r, split.s);
    var signer = ethereumjs.Util.pubToAddress(publicKey).toString("hex");
    return signer;
}

function isValidSignature(contractAddress, amount, signature, expectedSigner) {
    var message = prefixed(constructPaymentMessage(contractAddress, amount));
    var signer = recoverSigner(message, signature);
    return signer.toLowerCase() ==
        ethereumjs.Util.stripHexPrefix(expectedSigner).toLowerCase();
}
```

# Derinlemesine Solidity

## Bir Solidity Kaynak Dosyasının Yapısı

Kaynak dosyaları, isteğe bağlı sayıda *sözleşme tanımı, import ve pragma yönergeleri* içerebilir.

## Pragmalar

`Pragma` anahtar sözcüğü, belirli derleyici özelliklerini veya denetimlerini etkinleştirmek için kullanılır. Bir pragma yönergesi bir kaynak dosyasında her zaman yereldir, bu nedenle tüm projenizde etkinleştirmek istiyorsanız pragmayı tüm dosyalarınıza eklemeniz gerekir. Başka bir dosya alırsanız, o dosyadan gelen pragma içe aktarılan dosyaya otomatik olarak uygulanmaz.

### Pragma Sürümü

Kaynak dosyaları, uyumsuz değişiklikler getirebilecek veya dosyanın çalışmasını engelleyebilecek yeni derleyici sürümleriyle karşılaştıklarında bozulmamaları için yazıldıkları pragma sürümünün kodun başında açıklanması gerekir. Bu sayede yeni pragma versiyonları ile gelecek değişiklikleri mutlak bir asgari seviyede tutmaya çalışıyoruz ve semantic değişikliklerini sözdiziminde de değişiklik yaparak düzenlemeye çalışıyoruz, ancak bu elbette her zaman mümkün değildir. Özellikle  `0.x.0` veya `x.0.0` şeklinde görünen ve büyük değişiklikler içeren sürümler için değişiklik listesini incelemenin gerekli olduğunu hatırlatalım.

Pragma sürümü aşağıdaki gibi görünür:

```
pragma solidity ^0.5.2;

```

Yukarıdaki kodu içeren kaynak dosya, 0.5.2 sürümünden önceki bir derleyici ile derlenmeyecek ve ayrıca 0.6.0 sürümünden başlayan bir derleyici üzerinde çalışmayacaktır (bu ikinci koşul ^ kullanılarak eklenir). Bunun arkasındaki fikir, 0.6.0 sürümüne kadar herhangi bir kırılma değişikliği yaşanmayacağından, kodumuzun istediğimiz şekilde derleyeceğinden her zaman emin olabileceğimizdir. Çıkan hata düzeltme sürümleri ise kaynak kodumuzda sorunsuz çalışacaktır.

Derleyici sürümü için çok daha karmaşık kurallar belirtmek mümkündür. Bu durumlarda kodumuzu, npm tarafından kullanılan ifadeler takip eder.

### [Uyarı](#)

> Pragma sürümünü kullanmak, derleyicinin sürümünü değiştirmeyecektir. Ayrıca derleyicinin özelliklerini de etkinleştirmez veya devre dışı bırakmaz. Sadece derleyiciye, sürümünün pragmanın gerektirdiği ile uyuşup uyuşmadığını kontrol etmesi talimatını verecektir. Eşleşmezse, derleyici bir hata verecektir.

### Deneysel Pragmalar

Bir diğer pragma türü deneysel pragma olarak bilinir. Derleyici veya dilin henüz varsayılan olarak etkin olmayan özelliklerini denemek için kullanılabilir. Aşağıdaki örnek deneysel pragmalar şu anda desteklenmektedir:

#### ABIEncoderV2

Yeni ABI kodlayıcı, rasgele iç içe dizileri ve yapıları kodlama ve kodunu çözme özelliklerini içerir. Daha az optimal kod üretir (kodun bu kısmı için optimize edici hala geliştirilme aşamasındadır) ve eski kodlayıcı kadar test edilmemiştir. Bu deneysel versiyonu `pragma experimental ABIEncoderV2` komutu ile kullanabilirsiniz.

#### SMTChecker

Bu bileşen, Solidity derleyicisi kurulurken etkin olmalıdır ve bu nedenle tüm Solidity ikili dosyalarında mevcut değildir. *Yapı talimatları* başlığında, bu seçeneğin nasıl etkinleştirileceğini açıklayacağız. Çoğu sürümde Ubuntu PPA sürümleri için etkinleştirilmesi gerekse bile; solc-j'ler, Docker görüntüleri, Windows ikili dosyaları veya statik olarak oluşturulmuş Linux ikili dosyaları için etkinleştirmeye gerek kalmaz.

Eğer `pragma experimental SMTChecker;` kodunu dosyanıza eklerseniz, o zaman muhtemel bir SMT çözücünün varlığından kuşkulanan ek güvenlik uyarıları alırsınız. Bileşen henüz Solidity dilinin tüm özelliklerini desteklemediğinden ve birçok uyarı verebilir. Desteklenmeyen özellikleri rapor etmesi durumunda, belirtilen sebepler henüz tatmin edici olmayabilir.

## Diğer Kaynak Dosyaları İçe Aktarma

### Syntax & Semantic

Solidity, varsayılan `export` ifadesini tam olarak bilmese de, JavaScript’te (ES6’dan itibaren) bulunana benzer `import` ifadesini destekler.

Global düzeyde, aşağıdaki koddakine benzer `import` ifadesini projelerinizde kullanabilirsiniz:

```
import "filename";

```

Bu ifade, tüm global sembolleri “filename” belgesinden (ve orada içe aktarılan semboller) mevcut global kapsamın içine (ES6’dan farklı, ancak Solidity için geriye dönük olarak uyumlu) çalışmakta olduğumuz dosyanın içe aktarır. Yine de yukarıdaki kullanım pratikte çok önerilmez, çünkü ad alanını tahmin edilemez bir şekilde kirletir: “filename” belgesi içine yeni üst düzey öğeler eklerseniz bu değişiklik, “filename” dosyasından yukarıdaki şekilde içe aktarılan tüm dosyalara otomatik olarak yansıtılır. İçe aktarım sırasında kullanılan açıklamada daha spesifik ifadeler kullanmanız tavsiye edilir.

Aşağıdaki örnekte "filename" belgesindeki tüm global sembolleri içeren "symbolName" isimli yeni bir global sembol oluşturulmuştur.

```
import * as symbolName from "filename";

```
Bir ad çakışması varsa, içe aktarırken sembolleri de yeniden adlandırabilirsiniz. Bu kod, "filename" belgesi içindeki "symbol1" ve "symbol2" isimli iki global sembole kendi dosyamız içinde sırasıyla "alias" ve "symbol2" isimli iki yeni global sembol tanımlar.

```
import {symbol1 as alias, symbol2} from "filename";

```
ES6'nın bir parçası olmayan ama yine de yeterli olabilecek bir başka kullanım;

```
import "filename" as symbolName;

```

Yukarıdaki kod `import * as symbolName from "filename";` 'e eşdeğerdir.

### [Not](#)

> Eğer `moduleName` olarak “filename.sol” belgesini import ederseniz; “filename.sol” isimli belgede bulunann `C` isimli sözleşmeye `modeleName.C` yazarak erişebilirsiniz. Doğrudan `C` yazmanız durumunda erişim mümkün olmaz.

### Dosya Konumu

Diğer kodlama dillerindeki gibi, içe aktarılmak istenen dosya adı her zaman dizin ayırıcı olan `/` ile hedefe yönlendirilerek elde edilir. Geçerli olan dosya konumu `.` ile belirtilirken `..` ana dizin dosyasını işaret eder. `.` veya `..`kendisinden sonra `/` dışında bir karakter tarafından takip ediliyorsa, geçerli dosya komutu veya ana dizin kastedilmiyor demektir. `.` veya `..` ile başlamadıkça tüm dosya komutları geçerli olan dizin referans kabul edilerek direk yönlendirme olarak kabul edilir.

Geçerli dosyayla aynı dizinden almak bir x dosyası almak için, `import ./x as x` ifadesini kullanın. Eğer `import "x" as x` ifadesini kullanırsanız farklı bir dosyaya başvurulabilir (genel bir "`include` dizininde").

Derleyicinizin (aşağıya bakınız) dosya komutlarını gerçekte nasıl çözdüğüne bağlı olarak bazı değişiklikler gözlemlenebilir. Genel olarak, dizin hiyerarşisinin yerel dosya sisteminiz üzerinde kesin olarak konumlandırılması gerekmez; ipfs, http veya git üzerinde de konumlandırılmış olabilir.

### [Uyarı](#)

> Her zaman `import "./filename.sol";` gibi göreceli komutları kullanmayı tercih edin ve `..` gibi konum belirticilerinde kullanmaktan kaçının. İkinci yöntemi kullanmanız durumunda, global konum belirteçlerini kullanmak ve aşağıda açıklandığı gibi yeniden konumlandırma ayarları yapmak muhtemelen daha iyi sonuç verecektir.

### Gerçek Derleyici Kullanımı 

Derleyiciyinizi, bir dosya konumunun nasıl ifade edilmesi gerektiği konusunda dilediğiniz gibi ayarlayabilirsiniz. Örneğin, `github.com/ethereum/dapp-bin/library` sanal dizininden içe aktarılan her şeyin aslında yerel dizininiz olan `/ usr / local / dapp-bin / library` üzerinden okunması için bir derleyicinizde yeniden düzenleme yapabilirsiniz. Birden fazla remapping uygulanırsa, önce en uzun anahtara sahip olan denenir. Boş bir ön eke izin verilmez. Kullandığınız ortam, aynı adı taşıyan bir kütüphanenin farklı sürümlerini içe aktarmak için paketleri yapılandırmanıza izin veren bir fonksiyona sahip olabilir.

**solc:**

Solc(komut satırı derleyicisi) için, `context:prefix=target arguments;` komutu kullanılarak hem `context` hem de `=target` dosyasının isteğe bağlı çağrıldığı bir remapping sağlanabilir.  Bu durumda, normal dosya halindeki tüm remapping değerleri yeniden derlenir (bağımlılıkları dahil).

Bu mekanizma geriye doğru da uyumludur (hiçbir dosya adı `=` veya `:` bulundurmadığı sürece) ve hiç bir temel değişikliğe sebep olmaz. Kapsam dahilindeki dosyalar ve `context` altındakiler, `prefix` ile başlayan bir dosya içe aktarıldığında bu `prefix`i `target` ile değiştirirler.

Örneğin, `github.com/ethereum/dapp-bin/` dosyasını yerel olarak `/ usr / local / dapp-bin` dizinine klonlarsanız, kaynak dosyanızda aşağıdakileri kullanabilirsiniz:

```
import "github.com/ethereum/dapp-bin/library/iterable_mapping.sol" as it_mapping;

```
Burada düzenleyicinizi tekrar çalıştırsınız:

```
solc github.com/ethereum/dapp-bin/=/usr/local/dapp-bin/ source.sol
```

Daha karmaşık bir örnek olarak, eski bir dapp-bin sürümünü kullanan bir modüle dayanan `/ usr / local / dapp-bin_old` dosyasını kullandığınızı varsayalım.

```
solc module1:github.com/ethereum/dapp-bin/=/usr/local/dapp-bin/ \
     module2:github.com/ethereum/dapp-bin/=/usr/local/dapp-bin_old/ \
     source.sol
     
```
Bu, `modül2`'deki tüm içe aktarma işlemleri eski sürüme işaret ederken, `modül1`'deki içe aktarmanın yeni bir sürüme işaret ettiği anlamına gelir.


### [Not](#)

> `Solc`, yalnızca belirli dizinlerden dosya eklemenize izin verir. Bu dosyaların açıkça belirtilen kaynak dosyalardan birinin dizininde (veya alt dizininde) veya yeniden yapılanma hedefinin dizininde (veya alt dizininde) bulunmaları gerekir. Doğrudan mutlak içeriğe izin vermek istiyorsanız, `/ = /` işaretini eklemelisiniz.

Geçerli bir dosyaya yol açan birden fazla remapping varsa, en uzun genel `prefix`i içeren remapping kabul edilir.

**Remix:**

[Remix](https://remix.ethereum.org/) GitHub için otomatik bir remapping sağlar ve dosyayı ağ üzerinden otomatik olarak alır. Yinelenebilir eşlemeyi yukarıdaki örnekteki gibi içe aktarabilirsiniz. Örneğin:

```
::
import “github.com/ethereum/dapp-bin/library/iterable_mapping.sol” as it_mapping;

```
Remix gelecekte başka dosya içeri aktarma yöntemleri de sunabilir.

### Yorumlar

Tek satır yorumları (//) ve çoklu satır yorumları (/*...*/) mümkündür.

```
// This is a single-line comment.

/*
This is a
multi-line comment.
*/

```
### [Uyarı](#)

> Tek satırlı bir yorum utf8 kodlamasında herhangi bir unicode satır sonlandırıcısı (LF, VF, FF, CR, NEL, LS veya PS) tarafından sonlandırılır. Sonlandırıcı, yorumdan sonra hala kaynak kodun bir parçasıdır, bu nedenle bir ascii sembolü değilse (bunlar NEL, LS ve PS), ayrıştırıcı hatasına yol açar.

Ek olarak, [stil kılavuzunda](https://solidity.readthedocs.io/en/latest/style-guide.html#natspec) ayrıntılandırılan natspec yorumu adı verilen başka bir yorum türü de mevcuttur. Üçlü eğik çizgi (///) veya çift yıldız işareti (/ ** ... * /) ile yazılır ve doğrudan işlev bildirimlerinin veya ifadelerinin üzerinde kullanılır. İşlevleri belgelemek, resmi doğrulama için koşulları açıklamak ve bir işlevi çağırmaya çalıştıklarında kullanıcılara gösterilen bir **onay metni** sağlamak için bu yorumlar içindeki [Doxygen](https://en.wikipedia.org/wiki/Doxygen) stili etiketleri ile kullanılabilir.

Aşağıdaki örnek sözleşmenin başlığını, iki işlev parametresinin ve iki dönüş değişkeninin açıklamasını içeriyor.

```
pragma solidity >=0.4.0 <0.6.0;

/** @title Shape calculator. */
contract ShapeCalculator {
    /** @dev Calculates a rectangle's surface and perimeter.
      * @param w Width of the rectangle.
      * @param h Height of the rectangle.
      * @return s The calculated surface.
      * @return p The calculated perimeter.
      */
    function rectangle(uint w, uint h) public pure returns (uint s, uint p) {
        s = w * h;
        p = 2 * (w + h);
    }
}
```
## Sözleşmenin Yapısı

Solidity'de yazılan sözleşmeler, nesne yönelimli dillerdeki sınıflara benzer. Her sözleşme, **durum değişkenleri, fonksiyonlar, fonksiyon düzenleyicileri, olaylar, yapı tipleri ve enum tipleri** bildirimlerini içerebilir. Ayrıca, sözleşmeler bu bileşenleri diğer sözleşmelerden de alabilir.

**Kütüphaneler ve arayüzler** olarak adlandırılan özel tür sözleşmeler de bulunur.

*Sözleşmeler* ile ilgili bölüm, hızlı bir genel bakış sunmaya yarayan bu bölümden daha fazla ayrıntı içermektedir.

### Durum Değişkenleri

Durum değişkenleri, değerleri kalıcı olarak sözleşme deposunda saklanan değişkenlerdir.

```
pragma solidity >=0.4.0 <0.6.0;

contract SimpleStorage {
    uint storedData; // State variable
    // ...
}
```

### Fonksiyonlar

İşlevler, bir sözleşmedeki yürütülebilir kod birimleridir.

```
pragma solidity >=0.4.0 <0.6.0;

contract SimpleAuction {
    function bid() public payable { // Function
        // ...
    }
}
```
Fonksiyonlar *dahili veya harici* olarak kullanılabilir. Bunun yanında diğer sözleşmelere karşı farklı görünürlük seviyelerine sahip olabilirler. Son olarak fonksiyonlar **parametreleri ve return değerlerini** kabul ederler.

### Fonksiyon Düzenleyicileri

Fonksiyon değiştiricileri, fonksiyonları semantiğini bildirimsel bir şekilde değiştirmek için kullanılırlar (sözleşmeler bölümündeki fonksiyon düzenleyicileri başlığını inceleyiniz). 
```
pragma solidity >=0.4.22 <0.6.0;

contract Purchase {
    address public seller;

    modifier onlySeller() { // Modifier
        require(
            msg.sender == seller,
            "Only seller can call this."
        );
        _;
    }

    function abort() public view onlySeller { // Modifier usage
        // ...
    }
}
```

### Olaylar

*Olaylar*, EVM kayıt sistemleri için kolaylık sağlayan arayüzlerdir.

```
pragma solidity >=0.4.21 <0.6.0;

contract SimpleAuction {
    event HighestBidIncreased(address bidder, uint amount); // Event

    function bid() public payable {
        // ...
        emit HighestBidIncreased(msg.sender, msg.value); // Triggering event
    }
}
```
Olayların nasıl bildirildiği ve bir dapp içinde nasıl kullanılabileceği hakkında detaylı bilgi için "Sözleşmelerdeki Olaylar" bölümüne bakın.

### Yapı Tipleri

*Yapılar*, çeşitli değişkenleri gruplayabilen özel tanımlanmış türlerdir (bkz. *Yapılar* bölümü).

```
pragma solidity >=0.4.0 <0.6.0;

contract Ballot {
    struct Voter { // Struct
        uint weight;
        bool voted;
        address delegate;
        uint vote;
    }
}

```
### Enum Türleri

*Enumlar*, sonlu bir "sabit değer" kümesine sahip özel türler oluşturmak için kullanılabilir.

```
pragma solidity >=0.4.0 <0.6.0;

contract Purchase {
    enum State { Created, Locked, Inactive } // Enum
}

```
## Sözleşme Türleri

Solidity, statik olarak yazılmış bir dildir; bu, her değişkenin (global ve yerel) türünün belirtilmesi gerektiği anlamına gelir. Solidity, karmaşık tipler oluşturmak için birleştirilebilecek birkaç temel sözleşme tipi sağlar.

Ek olarak, türler operatör içeren ifadelerde birbirleriyle etkileşime girebilir. Çeşitli operatörlerin hızlı bir referansı için, bkz. [Operatör Öncelik Sırası](#).

“Undefined” veya “null” değerleri kavramı, Solidity dilinde yoktur, bunun yerine yeni bildirilen değişkenler her zaman türüne bağlı olarak [varsayılan](#) bir değere sahiptir. Beklenmeyen değerleri işlemek için, tüm işlemi geri döndürecek `revert` fonksiyonunu kullanmalı veya başarıyı gösteren ikinci bir *bool* değeri olan bir *tuple* döndürmelisiniz.

### Değer Türleri

Aşağıdaki türlere değer türleri de denir, çünkü bu türlerin değişkenleri her zaman değere göre belirlenir, yani fonksiyon argümanları olarak veya atamalarda kullanıldığında her zaman eşitlendikleri değerin kopyalandığı gözlenir.

#### Boolean

`bool`: `True` veya `False` sabit değerini alır.

Operatörler:

+ ! (mantıksal olumsuzlama)
+ && (mantıksal bağlantı, “ve”)
+ || (mantıksal bağlantı kesilmesi, “veya”)
+ == (eşitlik)
+ ! = (eşitsizlik)



```
```
```
```
```
```
```
```
```
```
```
```
```




 - 
  - 
  - 
  - Birimler ve Global Olarak Mevcut Değişkenler
  - İfadeler ve Kontrol Yapıları
  - Sözleşmeler
  - Solidity Assembly
  - Çeşitli
  - Solidity v0.5.0 Değişiklikleri
