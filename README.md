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

**Operatörler:**

+ `!` (mantıksal olumsuzlama)
+ `&&` (mantıksal bağlantı, “ve”)
+ `||` (mantıksal bağlantı kesilmesi, “veya”)
+ `==` (eşitlik)
+ `! =` (eşitsizlik)

`||` ve `& &` operatörleri ortak kısa devre kurallarını uygular. Bunun anlamı `f (x) || g (y)` işleminde, `f (x)` doğru olarak değerlendirilirse, yan etkileri olsa bile `g (y)` değerlendirilmez.

#### Tam Sayılar

`int / uint`: Çeşitli boyutlarda işaretli ve işaretsiz tam sayıları tanımalamak için kullanılır. `uint` ve `int`, sırasıyla `uint256` ve `int256`'nın yerine de kullanılabilir.

**Operatörler:**

+ Karşılaştırmalar: <=, <, ==,! =,> =,> (Bool olarak değerlendir)
+ Bit operatörleri: &, |, ^ (bitsel özel ya da), ~ (bitsel olumsuzlama)
+ Vardiya operatörleri: << (sola kaydırma), >> (sağa kaydırma)
+ Aritmetik operatörler: +, -, unary -, *, /,% (modulo), ** (üstelleştirme)

#### [Uyarı]()

> Solidity'de kullanılan tam sayılar belirli bir aralıkla sınırlandırılmıştır. Örneğin, `uint32` ile bu, `0`dan `2 ** 32 - 1` e kadardır. Bu sayılardaki bazı işlemlerin sonucu bu aralığa uymuyorsa, işlem yarıda kesilir. Bu kısaltmalar, farkında olmanız ve sonuçlarına karşı önlem almanız gereken ciddi sorunlara sebep olabilir.


#### Karşılaştırmalar

Bir karşılaştırmanın değeri, tamsayı değerini karşılaştırarak elde edilen değerdir.

#### Bir İşlemleri

Bit işlemleri, bir sayının iki farklı tamamlayıcı temsili değeri üzerinde yapılan işlemlerdir. Örneğin `~int256(0) == int256(-1)`.

#### Vardiya Operatörleri

Bir vardiya işleminin sonucu, sol işlenenin türüne sahiptir. `X << y` ifadesi, `x * 2 ** y`'ye eşittir ve pozitif tamsayılar için, `x >> y`, `x / 2 ** y`'ye eşittir. Negatif bir `x` için, `x >> y`, değeri yuvarlama sırasında (negatif sonsuzluğa doğru) bu değeri karesiyle bölmeye eşdeğerdir. Negatif miktarda vardiya işlemi uygulamak bir zaman aşımı hatası oluşturur.

#### [Uyarı]()

> `0.5.0` versiyonundan önce, negatif `x` için bir `x> y` vardiyası, `x / 2 ** y`'ye eşdeğerdi, yani sağa kaymalar, negatif sonsuzluğa yuvarlama yerine sıfıra doğru yuvarlama anlamına geliyordu.

#### Toplama, Çıkarma ve Çarpma

Toplama, çıkarma ve çarpma işlemlerinde standart semantic kullanılır. Bu işlemler, tam sayıların tamamlayıcı temsil değeri için de geçerlidir. Örneğin `uint256 (0) - uint256 (1) == 2 ** 256 - 1`. Güvenli akıllı sözleşmeler tasarlarken bu kullanımları ve sonuçlarını hesaba katmanız gerekir.

`-X` ifadesi, `(T (0) - x)` ifadesine eş değerdir, burada `T`, `x`'in bir türüdür. Bu, eğer x'in türü eğer işaretsiz bir tamsayı ise `-x`'in negatif olmayacağı anlamına gelir. Beklenildiği üzere, `x` negatifse `-x` pozitif olabilir. İkisinin tamamlayıcı temsilinden kaynaklanan başka bir uyarı daha yapalım:

```
int x = -2**255;
assert(-x == x);

```
Bu, bir sayı negatif olsa bile, olumsuzluğunun her zaman pozitif olacağını varsayamayacağınız anlamına gelir.

#### Bölme

Bir işlemin sonucunun türü her zaman işlenenlerden birinin türü olacağından, tam sayıların bölünmesi her zaman bir tam sayı ile sonuçlanır. Solidity dilinde, bölme sıfıra doğru yuvarlar. Bu, `int256 (-5) / int256 (2) == int256 (-2)` anlamına gelir.


#### [Not]()

> Sıfıra bölme hataya neden olur.

#### Modül İşlemi

Bir modül işlemi olan `a % n`, `a`'nın `n` tarafından bölünmesinden sonra kalan `r`'yi verir; burada `q = int (a / n)` ve `r = a - (n * q)` olarak kabul edilir. Modül işlemi, sol işleneniyle (veya sıfır) aynı işaretle sonuçlanır ve `a % n == - (abs (a)% n)`nın negatif a için geçerli olduğu anlamına gelir:

+ int256(5) % int256(2) == int256(1)
+ int256(5) % int256(-2) == int256(1)
+ int256(-5) % int256(2) == int256(-1)
+ int256(-5) % int256(-2) == int256(-1)

#### Üstsel İfadeler

Üstel yalnızca atanmamış türler için kullanılabilir. Lütfen kullandığınız türlerin sonucu içerecek kadar büyük olmasına ve potansiyel wrap hatası için önlem aldığınıza emin olun.

#### [Uyarı]()

> EVM tarafından 0 ** 0 değerinin 1 olarak tanımlandığını unutmayın.

#### Sabit Nokta Numaraları

Sabit nokta numaraları henüz Solidity tarafından tam olarak desteklenmiyor. Buna rağmen beyan edilebilirler, ancak atamanamaz veya bir başka bileşen tarafından atanmazlar.

`Fixed / ufixed`: Çeşitli boyutlarda imzalı ve imzasız sabit nokta sayısı. `UfixedMxN` ve `fixedMxN` anahtar sözcükleri için; `M`, tip tarafından alınan bit sayısını temsil eder ve `N`, kaç ondalık sayı kullanılabilir olduğunu gösterir. `M` 8 ile bölünebilir olmalı ve `8 - 256 bit` arasında değişmelidir. `N`, 0 ile 80 arasında olmalıdır. `fixed` ve `ufixed`, sırasıyla `ufixed128x18` ve `ufixed128x18` anlamına da gelir.

**Operatörler:**

+ Karşılaştırmalar: <=, <, ==,! =,> =,> (Bool olarak değerlendir)
+ Aritmetik operatörler: +, -, unary -, *, /,% (modulo)

#### [Not]()

> Floating nokta (birçok dilde float ve double, veya IEEE 754 sayıları) ve sabit nokta sayıları arasındaki temel fark, tamsayı ve kesirli kısım için kullanılan bit sayısının (ondalık noktadan sonraki kısım) ilkinde esnek, ikincisinde ise kesin tanımlı olmasıdır. Genel olarak, floating noktalarındaki hemen hemen tüm alan sayıyı temsil etmek için kullanılırken, yalnızca .ok küçük bir bit sayısı ondalık noktasının nerede olduğunu tanımlar.

#### Adres

Adres türü, büyük ölçüde özdeş olan iki farklı şekilde karşımıza çıkar:

+ Address: 20 baytlık bir değer (bir Ethereum adresinin boyutu) tutar.
+ Ödeme Adresi: Adresle aynı, ancak ek üyelerle transfer veya gönderme amacıyla kullanılır.

Bu ayrımın ardındaki fikir, `ödeme adresi` Ether gönderebileceğiniz bir adres olduğu halde düz bir `adres` Ether gönderilemez.

Tür Dönüşümleri:

Ödeme adresinden normal adrese örtülü dönüşümlere izin verilirken, normal adresten ödeme adresine yapılan işlemlerde dönüşüm mümkün değildir (böyle bir dönüşümü gerçekleştirmenin tek yolu `uint160`'a kadar aracı dönüştürücü kullanmaktır).

Herhangi bir adres, dolaylı olarak ödeme adresine dönüştürülebilir.

Değişken ve sabit tamsayı değerleri, bayt20 ve sözleşme türleri için normal adreslerden (veya normal adreslere) dönüşümlere izin verilirken: Ödenecek form adresinin dönüşümlerine izin verilmez. Bunun yerine, form adresinin (x) dönüşümünün sonucu bir ödeme adresiyken, eğer x tam sayı veya sabit bayt tipinde ise değişmez bir sözleşme adresine dönüşür. Eğer x, geri dönüş fonksiyonu olmayan bir sözleşme ise, adres (x) adres tipi olacaktır. Harici fonksiyonlarda imzalar adres ve ödeme adresi türü için kullanılır.

#### [Not]()

> Ödeme adresi ile normal adres arasındaki farkı çok fazla umursamadan ve sadece her yerde adres kullanmanız sizin için daha iyi bir seçenek olabilir. Örneğin, para çekme düzenini kullanıyorsanız, adresin kendisini adres olarak saklayabilirsiniz (çünkü aktarma işlevini msg.sender'da çağırırsınız ve bu aynı zamanda ödeme adresidir).

**Operators:**

`<=`, `<`, `==`, `!=`, `>=` ve `>`.

#### [Uyarı]()

>Daha büyük bir bayt boyutu kullanan bir türü bir adrese, örneğin bytes32'ye dönüştürürseniz, işlem yarıda kesilir. Dönüşüm belirsizliğini `0.4.24` sürümünden ve derleyici kuvvetinden daha yükseğe çıkarmak için, kısaltmayı dönüşümde açık yapabilirsiniz. Örneğin, `0x111122223333444455556666777788889999AAAABBBBCCCCDDDDEEEEFFFFCCCC` adresini ele alalım.

>`0x111122223333444455556666777788889999aAa` ile sonuçlanan `address(uint160 (bytes20 (b)))` kullanabilirsiniz ya da `0x777788889999AaAAbBbbCcccddDdeeeEfFFfCcCc` ile sonuçlanacak `address(uint160(uint256(b)))` i tercih edebilirsiniz.

#### [Not]()

> `Adres` ile `ödeme adresi`, arasındaki fark, 0.5.0 sürümü ile tanıtıldı. Ayrıca bu versiyondan başlayarak, sözleşmeler adres türünden gelmez, ancak ödenebilir bir geri dönüş işlevi varsa, açıkça adrese veya ödeme adresine dönüştürülebilir.

#### Adresin Organları

> Adresin tüm üyelerine dair hızlı bir bilgilendirme için, bkz. Adres Türlerinin Üyeleri.

+ `balance` ve `transfer`

`Balance` özelliğini kullanarak bir adresin bakiyesini sorgulamak ve `transfer` işlevini kullanarak ödenebilir bir adrese  Ether (wei birimlerinde) göndermek mümkündür:

```
address payable x = address(0x123);
address myAddress = address(this);
if (x.balance < 10 && myAddress.balance >= 10) x.transfer(10);

```
Cari sözleşmenin bakiyesi yeterince büyük değilse veya Eter transferi alıcı hesap tarafından reddedilirse transfer işlevi başarısız olur. Aktarma işlemi hata olarak geri döndürülür.

#### [Not]()

> Eğer x bir sözleşme adresiyse, kodu transfer çağrısı ile birlikte yürütülür (bu, EVM'nin bir özelliğidir ve önlenemez). Bu uygulamanın gazının tükenmesi veya herhangi bir şekilde başarısız olması durumunda, Ether devri geri alınacak ve mevcut sözleşme bir istisna ile sona erecektir.

+ `send`

`send`, düşük seviyede `transfer`le aynı işleve sahiptir. Yürütme başarısız olursa, mevcut sözleşme bir istisna sebebiyle durmayacak, ancak gönderme `false` döndürecektir.

#### [Uyarı]()

Gönderme kullanımında bazı tehlikeler mevcuttur: Çağrı yığını derinliği 1024'te ise (ki bu her zaman arayanlar tarafından zorunlu tutulabilir) aktarım başarısız olabilir veya alıcı gazın bitmesi durumuyla karşılaşılabilir. Bu nedenle, güvenli Ether transferlerini yapmak için, her zaman `send` döngü değerini kontrol edin, `transfer` kullanın veya daha iyisi: alıcının para çekme isteği göndereceği bir yöntem kullanın.

+ `call`, `delegatecall` ve `staticcall`

ABI'ye uymayan sözleşmelerle arayüz oluşturmak veya kodlama üzerinde daha doğrudan kontrol sahibi olmak için, `call`, `delegatecall` ve `staticcall` fonksiyonları sağlanır. Hepsi tek baytlık bir bellek parametresi alır ve başarı koşulunu (`bool` olarak) ve döndürülen verileri (byte belleği) döndürür. `Abi.encode`, `abi.encodePacked`, `abi.encodeWithSelector` ve `abi.encodeWithSignature` fonksiyonları yapılandırılmış verileri kodlamak için kullanılabilir.

**Örnek:**

```
bytes memory payload = abi.encodeWithSignature("register(string)", "MyName");
(bool success, bytes memory returnData) = address(nameReg).call(payload);
require(success);

```
#### [Uyarı]()

> Bütün bu fonksiyonlar düşük seviyeli fonksiyonlardır ve dikkatli kullanılmalıdır. Özellikle, bilinmeyen herhangi bir sözleşme kötü amaçlı olabilir ve eğer kullanırsanız, sözleşmenizi geri döndürebilecek bir sonuca sebebiyet verebilirsiniz. Bu nedenle işleminiz geri döndüğünde durum değişkenlerinizdeki değişikliklere hazırlıklı olursunuz. Diğer sözleşmelerle etkileşimin en iyi yolu, sözleşmede bulunan bir nesne(x.f ()) üzerinde bir fonksiyon çağırmaktır.

#### [Not]()

> Daha önceki Solidity sürümleri bu fonksiyonların keyfi argümanlar almasına izin veriyordu ve ayrıca bytes4 türünün ilk argümanını farklı şekilde ele alacaktı. Bu tartışmalı kullanımlar 0.5.0 versiyonunda kaldırılmıştır.

Verilen gazı `.gas ()` değiştiricisi ile ayarlamak mümkündür:

```
address(nameReg).call.gas(1000000)(abi.encodeWithSignature("register(string)", "MyName"));

```
Benzer şekilde, verilen Ether değeri de kontrol edilebilir:

```
address(nameReg).call.value(1 ether)(abi.encodeWithSignature("register(string)", "MyName"));

```
Son olarak, bu değiştiriciler birleştirilebilir. Onların sırası önemli değildir:

```
address(nameReg).call.gas(1000000).value(1 ether)(abi.encodeWithSignature("register(string)", "MyName"));

```
Benzer şekilde, `delegatecall` işlevi kullanılabilir: fark, verilen adresin yalnızca kodunun kullanılması, diğer tüm hususların (depolama, denge,…) mevcut sözleşmeden alınmasıdır. `Delegatecall`’in amacı başka bir sözleşmede saklanan kütüphane kodunu kullanmaktır. Kullanıcı, her iki sözleşmedeki depolama düzeninin kullanılacak `delegatecall` için uygun olmasını sağlamalıdır.

#### [Not]()

> Geçmişte, yalnızca orijinal `msg.sender` ve `msg.value` değerlerine erişim sağlamayan `callcode` denilen sınırlı bir varyant mevcuttu. Bu fonksiyon 0.5.0 sürümünde kaldırılmıştır.

Byzantium'den bu yana `staticcall` da kullanılabilir. Bu temelde `call` ile aynıdır, fakat çağrılan fonksiyon durumu herhangi bir şekilde değiştirirse işlemi geri dönecektir.

`call`, `delegatecall` ve `staticcall` fonksiyonlarının üçü de çok düşük seviyeli fonksiyonlardır ve sadece Solidity sözleşmelerinde güvenliğini kırdıkları için son çare olarak kullanılmalıdırlar.

`.Gas ()` seçeneği, üç yöntemin hepsinde bulunurken, `.value ()` seçeneği `delegatecall` için desteklenmez.

#### [Not]()

> Tüm sözleşmeler `adress` türüne dönüştürülebilir, bu nedenle `adress(this).balance` kullanarak mevcut sözleşmenin bakiyesini sorgulamak mümkündür.

### Sözleşme Türleri

Her sözleşme kendi türünü tanımlar. Sözleşmeleri dolaylı olarak devralındıkları sözleşmelere dönüştürebilirsiniz. Sözleşmeler açıkça diğer tüm sözleşme türlerine ve adres türüne dönüştürülebilir.

`adress payable` ve adresinden açıkça dönüşme ancak sözleşmeli türün geri ödenebilir bir geri dönüş işlevi varsa mümkündür. Dönüşüm hala `adress(x)` kullanılarak yapılır ancak ödeme adresi `(x)` kullanılarak yapılamaz. 

#### [Not]()

> 0.5.0 sürümünden önce, doğrudan adres türünden türetilen sözleşmeler de yapılabiliyordu ve ödeme adresi ile adres arasında bir fark yoktu.

Yerel bir sözleşme tipi değişkeni *(MyContract c)* bildirirseniz, bu sözleşmedeki fonksiyonları çağırabilirsiniz. Aynı sözleşme türüne sahip bir yerden fonksiyon çağırmaya özen gösterin.

Ayrıca sözleşmeleri de başlatabilirsiniz (yani, yeni yaratabilirsiniz). Daha fazla ayrıntıyı "Yeni sözleşmeler" bölümünde bulabilirsiniz.

Bir sözleşmenin veri temsili, `adress` tipiyle aynıdır ve bu tip **ABI**'da da kullanılır.

Sözleşmeler hiçbir operatörü desteklemez.

Sözleşme türlerinin bileşenleri, durum değişkenleri de dahil olmak üzere sözleşmenin dış fonksiyonları kabul edilir.

Bir sözleşme `C` için, sözleşme hakkında tip bilgisine erişmek için `type(C)` kullanabilirsiniz.

#### Sabit Boyutlu Bayt Dizileri

Bayt1, bayt2, bayt3,…, bayt32 değer türleri bir ila 32 arasında bir bayt dizisini tutar. Bayt, bayt1 için bir diğer addır.

Operatörler:

+ Karşılaştırmalar: `<=`, `<`, `==`,`! =`,`> =`,`>` (Bool olarak değerlendir)
+ Bit operatörleri: `&`, `|`,` ^` (bitsel özel ya da), `~` (bitsel olumsuzlama)
+ Vardiya operatörleri: `<<` (sola kaydırma), `>>` (sağa kaydırma)
+ Dizin erişimi: `x`, `bytesI` türünde ise, `0 <= k < I` için x[k], k bayt değerini döndürür (salt okunur).

Vardiya operatörü, herhangi bir tamsayı tipinde sağ işlenen (ancak sol işlenenin türünü döndürür) ile çalışır. Bu, kaydırılacak bit sayısını gösterir. Negatif bir miktarda kaydırmak, bir zaman aşımı istisnasına neden olur.

Bileşenler:

`.length`, bayt dizisinin sabit uzunluğunu verir (salt okunur).

#### [Not]()

> `Byte[]` türü bir bayt dizisidir, ancak dolgu kuralları nedeniyle her öğe için 31 baytlık alanı boşa harcar (depolama alanı hariç). Bunun yerine `bytes` türünü kullanmak daha iyidir.


### Dinamik Boyutlu Bayt Dizisi

+ bytes:
    Dinamik boyutlu bayt dizisi, *Diziler* bölümüne bakınız. Değer tipi değildir!
+ string:
    Dinamik olarak ölçülen UTF-8 kodlu dize, *Diziler* bölümüne. Değer tipi değildir!
    
### Adres Değişmezleri

Adres sağlama toplamı testini geçen onaltı karakterli değişmezler, örneğin `0xdCad3a6d3569DF655070DEd06cb7A1b2Ccd1D3AF`, `adress payable` türündedir. 39 ila 41 rakam uzunluğunda olan ve sağlama toplamı testini geçmeyen onaltı karakterli değişmezler bir uyarı verir ve normal rasyonel sayı değişmezleri olarak değerlendirilirler.

#### [Uyarı]()

> Karma harf adresi sağlama toplamı biçimi, `EIP-55`'te tanımlanmıştır.

### Rasyonel ve Tamsayı Değerleri

Tamsayı değişmezleri 0-9 aralığında bir sayılar dizisinden oluşur. Ondalık olarak yorumlanırlar. Örneğin, `69` altmış dokuz anlamına gelir. Solidity dilinde sekizli değişmezler yoktur ve baştaki sıfırlar geçersizdir.

Ondalık kesir değişmezleri a. ile oluşturulurlar ve bu ifadenin bir tarafında mutlaka bir sayı olması gerekir. Örnek olarak `1., .1 `ve` 1.3` bulunmaktadır.

Üsün kesir içeremediği durumlarda, tabanın kesir içerebileceği bilimsel gösterimler de desteklenir. Örnekler arasında `2e10`, `-2e10`, `2e-10`, `2.5e1` bulunur.

Okunabilirliğe yardımcı olmak ve sayısal bir harfin rakamlarını ayırmak için alt çizgiler kullanılabilir. Örneğin, `123_000` ondalık, onaltılık `0x2eff_abde` veya bilimsel ondalık gösterimi olan `1_2e345_678`'in tümü geçerlidir. Alt çizgilere yalnızca iki rakam arasında izin verilir ve arka arkaya yalnızca bir alt çizgiye izin verilir. Alt çizgi içeren bir sayı değişmezine ek bir anlam yüklemez, alt çizgiler yoksayılır.

Değişmez sayı ifadeleri değişmez olmayan bir türe dönüştürülünceye kadar keyfi bir kesinliğe sahip olur (yani, değişmez bir ifade ile birlikte veya açık bir dönüştürme ile birlikte kullanılır). Bu durum, hesaplamaların taşmadığı ve bölmelerin sayı değişmez ifadelerinde kısaltılmadığı anlamına gelir.

Örneğin, `(2 ** 800 + 1) - 2 ** 800` sabit `1` ile sonuçlanır (uint8 türünde), ancak ara sonuçlar belirlenen boyutuna bile uymaz. Dahası, `.5 * 8` tamsayıyla `4` sonuçlanır (tam sayı olmayanlar arasında kullanılmasına rağmen).

Tamsayılara uygulanabilen herhangi bir işlem, işlenenler tamsayı olduğu sürece, sayı ifadelerinin tamamına da uygulanabilir. İkisinden herhangi birinin kesirli olması durumunda, bit işlemlerine izin verilmez ve üs, kesirli ise (üstelik rasyonel olmayan bir sayıyla sonuçlanabileceği için) üstele izin verilmez.
    
#### [Not]()

> Her bir rasyonel sayı için Solidity dili bir sayı değişmez türüne sahiptir. Tamsayı değişmezleri ve rasyonel sayı değişmezleri sayı değişmez türlerine aittir. Ayrıca, tüm sayı değişmez ifadeleri (yani yalnızca sayı değişmezleri ve sayısal işlemleri içeren ifadeler) sayı değişmez türlerine aittir. Bu nedenle, `1 + 2` ve `2 + 1` sayı ifadelerinin her ikisi de rasyonel sayı 3 için aynı sayı hazır bilgi türüne aittir.

    
#### [Uyarı]()

> Tamsayı değişmezleri bölümü, `0.4.0` sürümünden önce Solidity'de işlemin sonucunu yuvarlamak için kullanılırdı, ancak şimdi rasyonel bir sonuç, örneğin `5/2`, `2`'ye eşit değil, `2.5`'e eşitlenebiliyor.

#### [Not]()

> Sayı değişmez ifadeleri başka türde değişmez ifadelerle birlikte kullanılır kullanılmaz değişebilir bir biçime dönüştürülür. Aşağıdaki örnekte `b`'ye verilen ifadenin değeri bir tamsayı olarak gözlenir. A, uint128 türünde olduğu için, `2.5 + a` ifadesinin uygun bir türü sonuç vermesi gerekir. `2.5 `ve` uint128` tipi için ortak bir tip olmadığından, Solidity derleyicisi bu kodu kabul etmemektedir.
    
```
uint128 a = 1;
uint128 b = 2.5 + a + 0.5;
```
#### String değişmezleri ve Türleri

String değişmezleri, çift veya tek tırnak ("foo" veya "bar") ile yazılır. C'deki gibi sıfıra giden sonuçları ima etmeyen bu ifadelerden "foo", dört değil, üç baytı temsil eder. Tamsayı değişmezlerinde olduğu gibi, türleri değişebilir, ancak örtük olarak `bytes1,… bytes32`'ye, sığarlarsa `bytes` ve `string` olarak dönüşürler.

Örneğin, `bytes32 samevar = "stringliteral"` bir string değişmezi olan `bytes32` türüne atandığında ham bayt biçiminde yorumlanır.

Dize değişmezleri aşağıdaki kaçış karakterlerini destekler:

+ `\`   <newline> (gerçek bir yeni satırdan kaçar)
+ `\\` (ters eğik çizgi)
+ `\'` (tek alıntı)
+ `\"` (çift alıntı)
+ `\b` (geri al)
+ `\f` (form beslemesi)
+ `\n` (yeni satır)
+ `\r` (satır başı)
+ `\t` (sekme)
+ `\v` (dikey sekme)
+ `\xNN`    (altıgen kaçış, aşağıya bakınız)
+ `\uNNNN`  (unicode kaçış, aşağıya bakın)
  
`\xNN` onaltılık bir değer alır ve uygun baytı ekler. `\uNNNN` ise bir Unicode kod noktası alır ve bir UTF-8 dizisi ekler.

Aşağıdaki örnekteki dize on bayt uzunluğundadır. Bir yeni satır byte ile başlar, bunu bir çift alıntı, tek bir alıntı bir ters eğik çizgi karakteri ve ardından (ayırıcı olmadan) `abcdef` karakter dizisi izler.

```
"\n\"\'\\abc\
def"
```
Yeni bir satır olmayan herhangi bir unicode line terminator (yani LF, VF, FF, CR, NEL, LS, PS), değişmez dizgeyi sonlandırır. Yeni satır, yalnızca bir `\` tarafından gelmemişse, dizgiyi hazırlar.

#### Onaltılık Değişmeyenler

Onaltılık değişmeyenler başına "hex" eki gelen ve çift veya tek tırnak içinde gösterilen değerlerdir( örneğin `hex"001122FF"`). Sekiz sayı ve harf değerinden meydana gelen bu değerlerin içerdikleri ifadelerin her biri iki başka ifadeyi temsilen yazılır.

Onaltılık değişmeyenler `string` değişmezleri gibi davranır ve aynı dönüştürülebilirlik sınırlamalarına sahiptir.

#### Enumlar

Enumlar, Solidity'de kullanıcı tanımlı bir tür oluşturmanın bir yoludur. Açıkça tüm tam sayı türlerine dönüştürülebilirler ancak örtük dönüştürmelere izin verilmez. Tamsayıdan açıkça yapılan dönüştürme, çalışma zamanında değerin enum aralığının içinde olup olmadığını kontrol eder; eğer değilse başarısızlığa neden olur. Enumlar en az bir üyeye ihtiyaç duyar.

Veri gösterimi, C'deki enums'lerle aynıdır: Seçenekler, 0'dan başlayan işaretsiz tamsayı değerleri ile temsil edilir.

```
pragma solidity >=0.4.16 <0.6.0;

contract test {
    enum ActionChoices { GoLeft, GoRight, GoStraight, SitStill }
    ActionChoices choice;
    ActionChoices constant defaultChoice = ActionChoices.GoStraight;

    function setGoStraight() public {
        choice = ActionChoices.GoStraight;
    }

    // Since enum types are not part of the ABI, the signature of "getChoice"
    // will automatically be changed to "getChoice() returns (uint8)"
    // for all matters external to Solidity. The integer type used is just
    // large enough to hold all enum values, i.e. if you have more than 256 values,
    // `uint16` will be used and so on.
    function getChoice() public view returns (ActionChoices) {
        return choice;
    }

    function getDefaultChoice() public pure returns (uint) {
        return uint(defaultChoice);
    }
}
```
### Fonksiyon Türleri

Fonksiyon türleri, sözleşmede uygulanilecek işlemlerin çeşitleridir . Fonksiyon türündeki değişkenler yine fonksiyonlar tarafından atanabilir. Fonksiyonlardaki parametreler, fonksiyonlar arasında bilgi veya komut geçişi yapmak kadar başka kaynaklardan bilgiyi döndürmek için de kullanılır. Temelde iki farklı fonksiyon türü vardır - *dahili* ve *harici* fonksiyonlar:

*Dahili fonksiyonlar*, yalnızca geçerli sözleşmenin içinde (daha özel olarak, iç kütüphane fonksiyonlarını ve miras alınan fonksiyonları de içeren geçerli kod ünitesinin içinde) çağrılabilir, çünkü mevcut sözleşmenin kapsamı dışında yürütülemezler. Bir iç fonksiyon çağrısı, iç sözleşmedeki bir fonksiyonun çağrılması gibi, giriş etiketine atlayarak gerçekleştirilir.

*Harici fonksiyonlar* bir adres ve fonksiyon imzasından oluşur ve harici fonksiyon çağrılarından iletilebilir ve geri çağrılabilirler.

Fonksiyon türleri aşağıdaki şekilde belirtilmiştir:
```
function (<parameter types>) {internal|external} [pure|view|payable] [returns (<return types>)]
```

Parametre türlerinin aksine, dönüş tipleri boş olamaz - fonksiyon hiçbir şey döndürmezse, `returns (<return types>)` kısmı tamamen çıkarılmalıdır.

Varsayılan olarak, fonskiyon türleri dahilidir, böylece `internal` anahtar kelimesinin kullanılmasına ihtiyaç duyulmaz. Bunun sadece fonksiyon tipleri için geçerli olduğuna dikkat ediniz. Sözleşmelerde tanımlanan fonksiyonlar için görünürlük açıkça belirtilmelidir, varsayılanları yoktur.

#### Dönüşümler:

Harici fonksiyon türünün bir değeri açıkça fonksiyon sözleşmesinin `adress` türüne dönüştürülebilir.

A fonksiyon tipi, sadece ve sadece parametre tipleri, return tipleri, iç / dış özellikleri aynı olan ve kendinden daha az kısıtlayıcı olan başka bir B fonksiyonuna dönüştürülebilir. Detaylandırırsak:

+ `pure` fonksiyonları, `view` ve `non-payable` fonksiyonlarına dönüştürülebilir.
+ `view` fonksiyonları, `non-payable` fonksiyonlarına dönüştürülebilir.
+ `payable` fonskiyonları, `non-payable` fonksiyonlarına dönüştürülebilir.

Fonksiyon türleri arasında başka hiçbir dönüşüm mümkün değildir.

`payable` ve `non-payable` fonksiyonları hakkındaki kural biraz kafa karıştırıcı olabilir, fakat esasen, eğer bir fonksiyon `payable` ise, bu da sıfır Ether ödemesini kabul ettiği anlamına gelir, bu yüzden ödenmesi de mümkün değildir. Öte yandan, `non-payable` bir fonksiyon kendisine gönderilen Ether'i reddeder, bu yüzden `non-payable` işlevler `payable` fonksiyonlara dönüştürülemez.

Bir fonksiyon tipi değişkeni başlatılmadıysa, çağırılması başarısız bir iddiaya neden olur. Aynı fonksiyonu, `delete` işlevini kullandıktan sonra çağırırsanız aynı sonuç ile karşılaşırsınız.

Harici fonksiyon türleri, Solidity bağlamı dışında kullanılırsa, fonksiyon tanımlayıcısı tarafından izlenen adresi tek bir `bytes24` türünde kodlayan bir `function` olarak işlem görürler.

Mevcut sözleşmelerde `public` fonksiyonunun hem iç hem de dış fonksiyon olarak kullanılabileceğini unutmayın. Fonskiyonu bir iç fonksiyon olarak kullanmak için `f`yi, yalnızca dış biçimini kullanmak için `this.f` öğesini kullanın.

`public` (veya harici) fonksiyonlar aşağıdaki üyelere sahiptir:

+ `.selector` ABI fonksiyon seçicisini döndürür
+ `.gas (uint)` çağrıldığında, belirtilen gaz miktarını hedef fonksiyona gönderecek olan çağrılabilen bir fonksiyon nesnesi döndürür. Daha fazla bilgi için *Harici Fonksiyon Çağrıları* bölümüne bakınız.
+ `.value (uint)` çağrıldığında, belirtilen miktardaki wei'yi hedef fonksiyona gönderecek olan çağrılabilir bir fonksiyon nesnesi döndürür. Daha fazla bilgi için *Harici Fonksiyon Çağrıları* bölümüne bakınız.

Öğelerin nasıl kullanılacağını gösteren örnek:

```
pragma solidity >=0.4.16 <0.6.0;

contract Example {
  function f() public payable returns (bytes4) {
    return this.f.selector;
  }
  function g() public {
    this.f.gas(10).value(800)();
  }
}
```
Dahili işlev türlerinin nasıl kullanılacağını gösteren örnek:

```
pragma solidity >=0.4.16 <0.6.0;

library ArrayUtils {
  // internal functions can be used in internal library functions because
  // they will be part of the same code context
  function map(uint[] memory self, function (uint) pure returns (uint) f)
    internal
    pure
    returns (uint[] memory r)
  {
    r = new uint[](self.length);
    for (uint i = 0; i < self.length; i++) {
      r[i] = f(self[i]);
    }
  }
  function reduce(
    uint[] memory self,
    function (uint, uint) pure returns (uint) f
  )
    internal
    pure
    returns (uint r)
  {
    r = self[0];
    for (uint i = 1; i < self.length; i++) {
      r = f(r, self[i]);
    }
  }
  function range(uint length) internal pure returns (uint[] memory r) {
    r = new uint[](length);
    for (uint i = 0; i < r.length; i++) {
      r[i] = i;
    }
  }
}

contract Pyramid {
  using ArrayUtils for *;
  function pyramid(uint l) public pure returns (uint) {
    return ArrayUtils.range(l).map(square).reduce(sum);
  }
  function square(uint x) internal pure returns (uint) {
    return x * x;
  }
  function sum(uint x, uint y) internal pure returns (uint) {
    return x + y;
  }
}
```
Harici işlev türlerini kullanan başka bir örnek:
```
pragma solidity >=0.4.22 <0.6.0;

contract Oracle {
  struct Request {
    bytes data;
    function(uint) external callback;
  }
  Request[] requests;
  event NewRequest(uint);
  function query(bytes memory data, function(uint) external callback) public {
    requests.push(Request(data, callback));
    emit NewRequest(requests.length - 1);
  }
  function reply(uint requestID, uint response) public {
    // Here goes the check that the reply comes from a trusted source
    requests[requestID].callback(response);
  }
}

contract OracleUser {
  Oracle constant oracle = Oracle(0x1234567); // known contract
  uint exchangeRate;
  function buySomething() public {
    oracle.query("USD", this.oracleResponse);
  }
  function oracleResponse(uint response) public {
    require(
        msg.sender == address(oracle),
        "Only oracle can call this."
    );
    exchangeRate = response;
  }
}

```
#### [Not]()

> Lambda veya satır içi fonksiyonları kullanımı planlanıyor, ancak henüz desteklenmiyor.

## Referans Türleri

Referans türünün değerleri, birden fazla farklı isim üzerinden değiştirilebilir. Bu durumu, her değişken tipi kullanıldığında bağımsız bir kopya aldığınız değer tipleriyle karşılaştırın. Bu özellik sebebiyle, referans türlerinin değer türlerinden daha dikkatli ele alınması gerekir. Şu anda, referans türleri yapılar, diziler ve eşlemeler içermektedir. Bir referans türü kullanıyorsanız, daima türün depolandığı veri alanını açıkça belirtmeniz gerekir: `memory` (ömrü bir fonksiyonu çağrısı ile sınırlıdır), `storage` (durum değişkenlerinin saklandığı konum) veya `calldata` (özel veriler fonksiyon argümanlarını içeren konum, yalnızca harici işlev çağrısı parametreleri için kullanılabilir).

Veri konumunu değiştiren bir atama veya tür dönüşümü her zaman otomatik bir kopyalama işlemine tabi tutulurken, aynı veri konumunun içindeki atamalar yalnızca bazı durumlarda depolama türleri için kopyalanır.

### Veri Konumu

Her referans türü, yani diziler ve yapılar, depolandığı yer hakkında “veri konumu” isimli bir ek açıklamaya sahiptir. Üç veri konumu vardır: `memory`, `storage` ve `calldata`. `Calldata`, yalnızca harici sözleşme fonksiyonlarının parametreleri için geçerli ve bu parametre türü için gereklidir. `Calldata`, fonksiyon argümanlarının saklandığı ve çoğunlukla `memory` gibi davrandığı değiştirilemez, kalıcı olmayan bir alandır.

### [Not]()

> 0.5.0 sürümünden önce, veri konumu atlanabilir ve değişken türüne, fonksiyon türüne vb. bağlı olarak varsayılan konumlar kullanılabilirdi Şuan ise tüm karmaşık türleri için açık bir veri konumu verilmesi gerekir.

#### Veri Konumu Ve Atama Davranışı

Veri yerleri sadece verilerin kalıcılığıyla değil aynı zamanda atandıkları değerlerin semanticleri ile ilgilidir:

+ `Memory` ve `storage` (veya `calldata`) arasındaki atamalar her zaman bağımsız bir kopya oluşturur.
+ `Memory`den `memory`e yapılan atamalar yalnızca referans oluşturur. Bu, bir `memory` değişkeninde yapılan değişikliklerin aynı verilere başvuran tüm diğer `memory` değişkenlerinde de görülebileceği anlamına gelir.
+ `Storage`dan yerel `storage` değişkenine yapılan atamalar da yalnızca bir referans atar.

```
pragma solidity >=0.4.0 <0.6.0;

contract C {
    uint[] x; // the data location of x is storage

    // the data location of memoryArray is memory
    function f(uint[] memory memoryArray) public {
        x = memoryArray; // works, copies the whole array to storage
        uint[] storage y = x; // works, assigns a pointer, data location of y is storage
        y[7]; // fine, returns the 8th element
        y.length = 2; // fine, modifies x through y
        delete x; // fine, clears the array, also modifies y
        // The following does not work; it would need to create a new temporary /
        // unnamed array in storage, but storage is "statically" allocated:
        // y = memoryArray;
        // This does not work either, since it would "reset" the pointer, but there
        // is no sensible location it could point to.
        // delete y;
        g(x); // calls g, handing over a reference to x
        h(x); // calls h and creates an independent, temporary copy in memory
    }

    function g(uint[] storage) internal pure {}
    function h(uint[] memory) public pure {}
}

```
## Diziler

Diziler, derleme zamanı sabit veya dinamik bir boyuta sahip olabilirler.

Sabit boyutlu bir `k` dizisinin ve `T` öğe türünün ikisi birleşerek `T[k]`i oluştururlar. `T[]` normalde dinamik bir boyutlu bir diziyi ifade eder.

Örneğin, 5 dinamik `uint` dizisinden oluşan bir dizi uint `[][5]` olarak yazılır. Gösterim diğer bazı dillere göre tersine çevrilmiştir. Solidity dilince, `X[3]`, `X`'in kendisi bir dizi olsa bile, her zaman `X` türünde üç öğe içeren bir dizidir. `C` gibi diğer dillerde durum böyle değildir.

Endeksler sıfır tabanlıdır ve erişim bildirimin tersi yöndedir.

Örneğin, değişken bir uint `[][5]` `x` belleğiniz varsa, üçüncü dinamik dizideki ikinci `uint`'e `x[2][1]` kullanarak erişirsiniz ve üçüncü dinamik diziye erişmek için `x[3]` kullanırsınız. Yine, bir dizi de olabilen `T` tipi için `T[5] a`  diziniz varsa, o zaman `[2]` her zaman T tipine sahiptir.

Dizi öğeleri, eşleme veya yapı dahil olmak üzere herhangi bir türde olabilir. Tipler için genel kısıtlamalar geçerlidir, çünkü bu eşlemeler yalnızca `storage` verileri konumunda saklanabilir ve herkes tarafından görülebilen fonksiyonlar ABI türleri olan parametrelere ihtiyaç duyar.

Durum değişkeni dizileri `public` olarak dönüştürmek ve Solidity'nin bir alıcı oluşturmasını sağlamak mümkündür. Sayısal endeks alıcı için gerekli bir parametre haline gelir.

Sonundan bir diziye erişilmesi başarısız bir iddiaya neden olur. Sonunda yeni bir öğe eklemek için `.push()` yöntemini kullanabilir veya boyutunu değiştirmek için `.length` yöntemine başvurabilirsiniz (uyarılar için aşağıya bakın). `.lenght` yöntemini daha çok öğe eklemek için de kullanabilirisniz.

## Diziler Olarak `Byte` ve `String`

`Byte` ve `String` değişken türleri özel dizilerdir. Bir bayt `byte[]`e benzer, ancak `calldata` ve `memory`de daha sıkı paketlenmiştir. `String` `byte`a eşittir, ancak uzunluk veya indeks erişimine izin vermez.

Solidity dilinin dizi düzenleme fonksiyonu yoktur, ancak üçüncü taraf dizi kütüphaneleri vardır. Ayrıca `keccak256 (abi.encodePacked (s1)) == keccak256 (abi.encodePacked (s2))` kullanarak iki dizgiyi karşılaştırabilir ve `abi.encodePacked (s1, s2)` kullanarak iki dizgiyi birleştirebilirsiniz.

`Byte[]` yerine `bytes` kullanmalısınız çünkü daha ucuzdur, çünkü `byte[]` elemanlar arasında 31 doldurma baytı ekler. Genel bir kural olarak, isteğe bağlı uzunluktaki ham bayt verileri için bayt ve isteğe bağlı uzunluktaki dize (UTF-8) verileri için `string` kullanın. Uzunluğu belirli sayıda bayt ile sınırlandırabilirseniz, her zaman çok daha ucuz oldukları için `bayt1` ile `bayt32` arasındaki değer türlerinden birini kullanın.

`S` dizgisinin bayt temsiline erişmek istiyorsanız, `bytes(s).length / bytes(s)[7] = 'x';` kullanın. Bunu yaparak, tek tek karakterlere değil de, UTF-8 gösteriminin düşük seviye baytlarına eriştiğinizi unutmayın.

## Bellek Dizilerini Ayırma

Çalışma zamanına bağlı uzunluktaki bellekte(memory) diziler oluşturmak için 'new' anahtar sözcüğünü kullanmanız gerekir. Depolama dizilerinin aksine, bellek dizilerini yeniden boyutlandırmak mümkün değildir (örneğin '.onth' üyesini atayarak). İstenilen boyutu önceden hesaplamanız veya yeni bir bellek dizisi yaratmanız ve her öğeyi kopyalamanız gerekir.

```
pragma solidity >=0.4.16 <0.6.0;

contract C {
    function f(uint len) public pure {
        uint[] memory a = new uint[](7);
        bytes memory b = new bytes(len);
        assert(a.length == 7);
        assert(b.length == len);
        a[6] = 8;
    }
}
```
Dizi Değişmezleri

Bir dizi değişmezi, köşeli parantez `([...])` içine alınmış bir veya daha fazla ifadenin virgülle ayrılmış listesi şeklinde görünür. Örneğin `[1, a, f (3)]`. Tüm öğelerin örtük olarak dönüştürülebileceği ortak bir tür olması gerekir. Bu, dizinin temel türüdür.

Dizi değişmezleri her zaman statik boyutlu bellek dizileridir.

Aşağıdaki örnekte, `[1, 2, 3]` türü `uint8[3] memory` türündedir. Bu sabitlerin her birinin tipi `uint8` olduğundan, sonucun bir `[3] memory`olmasını istiyorsanız, ilk öğeyi `uint`'e dönüştürmeniz gerekir.

```
pragma solidity >=0.4.16 <0.6.0;

contract C {
    function f() public pure {
        g([uint(1), 2, 3]);
    }
    function g(uint[3] memory) public pure {
        // ...
    }
}

```
Sabit boyutlu bellek dizileri, dinamik boyutlu bellek dizilerine atanamaz, yani aşağıdakiler mümkün değildir:
```
pragma solidity >=0.4.0 <0.6.0;

// This will not compile.
contract C {
    function f() public {
        // The next line creates a type error because uint[3] memory
        // cannot be converted to uint[] memory.
        uint[] memory x = [uint(1), 3, 4];
    }
}
```
Gelecekte bu kısıtlamanın kaldırılması planlanıyor, ancak ABI’de dizilerin nasıl iletildiğinden dolayı bazı komplikasyonlar yaratıyor.

## Dizi Öğeleri

**Uzunluk:**

Dizilerin, eleman sayılarını içeren bir `.lenght` öğesi vardır. Bellek dizilerinin uzunluğu (ancak dinamiktir, yani çalışma zamanı parametrelerine bağlı olabilir) oluşturulduktan sonra sabittir. Dinamik boyutlu dizilerde (yalnızca depolama için kullanılabilir), bu öğe diziyi yeniden boyutlandırmak için atanabilir. Geçerli uzunluk dışındaki öğelere erişmek, diziyi otomatik olarak yeniden boyutlandırmaz; bunun yerine başarısız bir iddiaya neden olur. Uzunluğun arttırılması, diziye sıfırdan başlatılmış yeni öğeler ekler. Uzunluğu azaltmak, örtük bir işlem gerçekleştirir. Ref: kaldırılan öğelerin her birini `delete` yöntemi ile silin. Depoda bulunmayan dinamik olmayan bir diziyi yeniden boyutlandırmayı denerseniz, almanız gereken `Value must be an lvalue` hatası olmalıdır.

**push**:

Dinamik depolama dizileri ve baytlar (string değil), dizinin sonuna bir eleman eklemek için kullanabileceğiniz `.push` adlı bir fonksiyona sahiptir. Öğe sıfırda başlatılır. Fonksiyon yeni uzunluğu döndürür.

**pop:**

Dinamik depolama dizileri ve baytlar (string değil), bir elemanı dizinin sonundan çıkarmak için kullanabileceğiniz `.pop` adlı bir fonksiyona sahiptir. Bu aynı zamanda dolaylı olarak kaldırılan öğe için `.delete`i çağırır.

### [Uyarı]()

>`.Length--` öğesini boş bir dizide kullanırsanız, aşağı akışa neden olur ve bu nedenle uzunluğu `2 ** 256-1` olarak ayarlar.

### [Not]()

>Bir depolama dizisinin uzunluğunun arttırılması sabit gaz maliyetlerine sahiptir, çünkü depolamanın sıfırlandığı varsayılır, uzunluğu düşürürken en yine bu sabit maliyete sahiptir. Kaldırılan elemanların açıkça temizlenmesini içerir ve `delete` yöntemini çağırır.

### [Not]()

>Dizilerin harici fonksiyonlarda kullanılması henüz mümkün değildir (ancak ortak fonksiyonlarda desteklenirler).

### [Not]()

>`Byzantium`'dan önceki EVM versiyonlarında, fonksiyon çağrılarından dönen dinamik dizilere erişmek mümkün değildi. Dinamik dizileri döndüren fonksiyonları çağırırsanız, `Byzantium` moduna ayarlanmış bir EVM kullandığınızdan emin olun.

```
pragma solidity >=0.4.16 <0.6.0;

contract ArrayContract {
    uint[2**20] m_aLotOfIntegers;
    // Note that the following is not a pair of dynamic arrays but a
    // dynamic array of pairs (i.e. of fixed size arrays of length two).
    // Because of that, T[] is always a dynamic array of T, even if T
    // itself is an array.
    // Data location for all state variables is storage.
    bool[2][] m_pairsOfFlags;

    // newPairs is stored in memory - the only possibility
    // for public contract function arguments
    function setAllFlagPairs(bool[2][] memory newPairs) public {
        // assignment to a storage array performs a copy of ``newPairs`` and
        // replaces the complete array ``m_pairsOfFlags``.
        m_pairsOfFlags = newPairs;
    }

    struct StructType {
        uint[] contents;
        uint moreInfo;
    }
    StructType s;

    function f(uint[] memory c) public {
        // stores a reference to ``s`` in ``g``
        StructType storage g = s;
        // also changes ``s.moreInfo``.
        g.moreInfo = 2;
        // assigns a copy because ``g.contents``
        // is not a local variable, but a member of
        // a local variable.
        g.contents = c;
    }

    function setFlagPair(uint index, bool flagA, bool flagB) public {
        // access to a non-existing index will throw an exception
        m_pairsOfFlags[index][0] = flagA;
        m_pairsOfFlags[index][1] = flagB;
    }

    function changeFlagArraySize(uint newSize) public {
        // if the new size is smaller, removed array elements will be cleared
        m_pairsOfFlags.length = newSize;
    }

    function clear() public {
        // these clear the arrays completely
        delete m_pairsOfFlags;
        delete m_aLotOfIntegers;
        // identical effect here
        m_pairsOfFlags.length = 0;
    }

    bytes m_byteData;

    function byteArrays(bytes memory data) public {
        // byte arrays ("bytes") are different as they are stored without padding,
        // but can be treated identical to "uint8[]"
        m_byteData = data;
        m_byteData.length += 7;
        m_byteData[3] = 0x08;
        delete m_byteData[2];
    }

    function addFlag(bool[2] memory flag) public returns (uint) {
        return m_pairsOfFlags.push(flag);
    }

    function createMemoryArray(uint size) public pure returns (bytes memory) {
        // Dynamic memory arrays are created using `new`:
        uint[2][] memory arrayOfPairs = new uint[2][](size);

        // Inline arrays are always statically-sized and if you only
        // use literals, you have to provide at least one type.
        arrayOfPairs[0] = [uint(1), 2];

        // Create a dynamic byte array:
        bytes memory b = new bytes(200);
        for (uint i = 0; i < b.length; i++)
            b[i] = byte(uint8(i));
        return b;
    }
}

```
### Yapılar

Aşağıdaki şekilde gösterildiği gibi, Solidity yeni bir türü `struct` biçiminde tanımlama imkanı sunar:

```
pragma solidity >=0.4.11 <0.6.0;

contract CrowdFunding {
    // Defines a new type with two fields.
    struct Funder {
        address addr;
        uint amount;
    }

    struct Campaign {
        address payable beneficiary;
        uint fundingGoal;
        uint numFunders;
        uint amount;
        mapping (uint => Funder) funders;
    }

    uint numCampaigns;
    mapping (uint => Campaign) campaigns;

    function newCampaign(address payable beneficiary, uint goal) public returns (uint campaignID) {
        campaignID = numCampaigns++; // campaignID is return variable
        // Creates new struct in memory and copies it to storage.
        // We leave out the mapping type, because it is not valid in memory.
        // If structs are copied (even from storage to storage), mapping types
        // are always omitted, because they cannot be enumerated.
        campaigns[campaignID] = Campaign(beneficiary, goal, 0, 0);
    }

    function contribute(uint campaignID) public payable {
        Campaign storage c = campaigns[campaignID];
        // Creates a new temporary memory struct, initialised with the given values
        // and copies it over to storage.
        // Note that you can also use Funder(msg.sender, msg.value) to initialise.
        c.funders[c.numFunders++] = Funder({addr: msg.sender, amount: msg.value});
        c.amount += msg.value;
    }

    function checkGoalReached(uint campaignID) public returns (bool reached) {
        Campaign storage c = campaigns[campaignID];
        if (c.amount < c.fundingGoal)
            return false;
        uint amount = c.amount;
        c.amount = 0;
        c.beneficiary.transfer(amount);
        return true;
    }
}
```
Sözleşme, kitle fonlaması sözleşmesinin tam işlevselliğini sağlamaz, ancak yapıları anlamak için gereken temel kavramları içerir. Yapısal türler, eşleme ve dizilerin içinde kullanılabilir; eşleme ve diziler içerebilir.

Bir yapının kendi türünde bir öğe içermesi mümkün değildir, ancak yapının kendisi bir eşleme öğesinin değer türü olabilir veya türünde dinamik olarak boyutlandırılmış bir dizi içerebilir. Yapının boyutunun sonlu olması gerektiğinden, bu kısıtlama gereklidir.

Tüm fonksiyonlarda, bir yapı türünün veri konumu `storage` olan bir yerel değişkene nasıl atandığını not ediniz. Bu yapıyı kopyalamaz, ancak yalnızca bir referansı saklar, böylece yerel değişken üyelerine yapılan atamalar aslında duruma yazabilir.

Tabii ki, `campaigns[campaignID].amount = 0` ifadesindeki gibi, yerel bir değişkene atamadan yapı üyelerine doğrudan erişebilirsiniz.

## Eşleme Türleri

Eşleme türlerini syntax ile `mapping(_KeyType => _ValueType)` şeklinde gösterebilirsiniz. `_KeyType` herhangi bir temel tür olabilir. Bu, yerleşik değer türlerinden herhangi biri artı `byte` ve `string` olabileceği anlamına gelir. Sözleşme türleri, numaralandırmalar, eşlemeler, yapılar ve bayt ve dizgiler dışında herhangi bir dizi türü gibi kullanıcı tanımlı veya karmaşık türlere izin verilmez. `_ValueType` eşleme dahil olmak üzere herhangi bir tür olabilir.

Eşleme, her olası anahtarın var olacağı ve bayt temsilinin tümü sıfır olan bir türün varsayılan değeri olan bir değere eşlenecek şekilde başlatılan hash tabloları olarak düşünebilirsiniz. Benzerlik burada biter, anahtar veriler bir eşlemede depolanmaz, değere bakmak için sadece `keccak256` hash kullanılır.

Bu nedenle, eşlemelerin ayarlanan bir anahtar veya değer için bir uzunluğu veya kavramı yoktur.

Eşlemeler yalnızca bir veri `storage` konumuna sahip olabilir ve bu nedenle durum değişkenleri için, fonksiyonlardaki depolama referans türleri veya kütüphane işlevleri parametreler olarak kullanılır. Ancak bunlar, `public` durumdaki sözleşme fonksiyonları veya iade parametreleri olarak kullanılamazlar.

Eşleme türündeki değişkenleri genel olarak işaretleyebilirsiniz ve Solidity sizin için bir alıcı oluşturur. `_KeyType`, alıcı için bir parametre haline gelir. `_ValueType` bir değer türü veya yapı ise, alıcı `_ValueType` değerini döndürür. `_ValueType` bir dizi veya eşleme ise, alıcıda her `_KeyType` için bir parametre tekrarlanır. Örneğin bir eşleme ile:

```
pragma solidity >=0.4.0 <0.6.0;

contract MappingExample {
    mapping(address => uint) public balances;

    function update(uint newBalance) public {
        balances[msg.sender] = newBalance;
    }
}

contract MappingUser {
    function f() public returns (uint) {
        MappingExample m = new MappingExample();
        m.update(100);
        return m.balances(address(this));
    }
}

```

### [Not]()

> Eşlemeler yinelenemez, ancak bunların üstüne bir veri yapısı uygulamak mümkündür. Bir örnek için, *Yinelenebilir Eşlemeye* bakın.

## LValues İçeren Operatörler

A bir LValue ise (yani bir değişken veya atanabilecek bir şey), aşağıdaki operatörler kısayol olarak kullanılabilir:

`a + = e`, `a = a + e` değerine eşittir. İşleçler `- =`, `* =`, `/ =`,`% =`, `| =`,` & =` ve `^ =` buna göre tanımlanmıştır. `a ++` ve `a--`, `+ = 1 / a - = 1` değerlerine eşittir, ancak ifadenin kendisi hala önceki `a` değerine sahiptir. Benzer şekilde, `--a` ve `++ a`, `a` üzerinde ters etkiye sahiptir, ancak değişiklikten sonra orjinale geri döndürür.

**Silmek**

`delete a`, türün başlangıç değerini a olarak atar. Yani tamsayılar için `a = 0`'a eşdeğerdir, ancak aynı zamanda, sıfır değerine sahip dinamik bir dizi dizisi veya tüm değerlerini başlangıç değerlerine ayarlanan aynı uzunluktaki statik diziyi atadığı dizilerde de kullanılabilir. `delete a[x]`, dizinin x dizinindeki öğeyi siler ve diğer tüm öğeleri ve dizinin uzunluğunu el değmemiş halde bırakır. Bu, özellikle dizide bir boşluk bıraktığı anlamına gelir. Öğeleri kaldırmayı planlıyorsanız, `mapping` muhtemelen daha iyi bir seçimdir.

Yapılar için `delete`, tüm üyelerin sıfırlanmasıyla bir yapı atanmasını sağlar. Başka bir deyişle, bir `delete` sonrası a'nın değeri a ile atama yapılmadan bildirilen ile aynıdır.

`delete` , eşlemeler üzerinde hiçbir etkiye sahip değildir (eşlemelerin anahtarları isteğe bağlı olabileceği ve genellikle bilinmediği için). Bu nedenle, bir yapıyı silerseniz, eşleme olmayan tüm üyeleri sıfırlar ve eşleme olmadıkça üyelere tekrar girer. Ancak, ayrı ayrı tuşlar ve eşlenecekleri değerler silinebilir: `a` bir eşleme ise, `delete a[x]` x'te depolanan değeri siler.

`delete a` işleminin gerçekten atama gibi davrandığını, yani a'da yeni bir nesneyi sakladığını not etmek önemlidir. Bu durum `a` referans değişken olduğunda da görülebilir: Önceden bahsettiği değeri değil, sadece kendini sıfırlar.

```
pragma solidity >=0.4.0 <0.6.0;

contract DeleteExample {
    uint data;
    uint[] dataArray;

    function f() public {
        uint x = data;
        delete x; // sets x to 0, does not affect data
        delete data; // sets data to 0, does not affect x
        uint[] storage y = dataArray;
        delete dataArray; // this sets dataArray.length to zero, but as uint[] is a complex object, also
        // y is affected which is an alias to the storage object
        // On the other hand: "delete y" is not valid, as assignments to local variables
        // referencing storage objects can only be made from existing storage objects.
        assert(y.length == 0);
    }
}
```
## Temel Tipler Arasındaki Dönüşümler

### Örtük Dönüşümler

Bir operatör farklı türlere uygulanırsa, derleyici işlenenlerden birini diğerinin türüne örtük olarak dönüştürmeye çalışır (aynısı atamalar için de geçerlidir). Genel olarak, anlamsal olarak anlam ifade ediyorsa ve hiçbir bilgi kaybedilmezse, değer türleri arasında örtük bir dönüşüm mümkündür: `uint8`, `uint16` ve `int128`'den `int256`'ya dönüştürülebilir, ancak `int8`, `uint256`'ya dönüştürülemez (çünkü `uint256`, örn. -1'i tutamaz).

Daha fazla ayrıntı için lütfen türlerle ilgili bölümlere bakın.

### Açık Dönüşümler

Derleyici örtük dönüştürmeye izin vermiyorsa, ancak ne yaptığınızı biliyorsanız, açık bir tür dönüştürmesi bazen mümkündür. Bunun size beklenmeyen bir davranış verebileceğini ve derleyicinin bazı güvenlik özelliklerini atlamanıza izin verdiğini unutmayın; bu nedenle, sonucun istediğiniz gibi olduğunu test ettiğinizden emin olun! Aşağıdaki örnekte negatif bir `int8`'i bir `uint`'e dönüştürüyoruz:

```
int8 y = -3;
uint x = uint(y);
```
Bu kod snippet'inin sonunda, `x`, iki bitin 256 bitlik tamamlayıcı gösteriminde -3 olan `0xfffff..fd` (64 hex karakter) değerine sahip olacaktır.

Bir tamsayı açıkça daha küçük bir türe dönüştürülürse, yüksek dereceli bitler kesilir:
```
uint32 a = 0x12345678;
uint16 b = uint16(a); // b will be 0x5678 now
```
Bir tamsayı açıkça daha büyük bir türe dönüştürülürse, sol tarafa doldurulur (yani, üst mertebe sonuna). Dönüşümün sonucu, orijinal tam sayıya eşit olarak karşılaştırılır:

```
uint16 a = 0x1234;
uint32 b = uint32(a); // b will be 0x00001234 now
assert(a == b);
```
Sabit boyutlu bayt türleri, dönüşümler sırasında farklı davranır. Tek tek bayt dizileri olarak düşünülebilir ve daha küçük bir türe dönüştürmek diziyi keser:

```
bytes2 a = 0x1234;
bytes1 b = bytes1(a); // b will be 0x12
```
Sabit boyutlu bir bayt türü açıkça daha büyük bir türe dönüştürülürse, sağ tarafa doldurulur. Bayt'a sabit bir dizinde erişmek, dönüşümden önce ve sonra aynı değere neden olur (dizin hala aralıktaysa):

```
bytes2 a = 0x1234;
bytes4 b = bytes4(a); // b will be 0x12340000
assert(a[0] == b[0]);
assert(a[1] == b[1]);
```

Tamsayılar ve sabit boyutlu bayt dizileri, kesme ya da doldurma sırasında farklı davrandıklarından, tamsayılar ve sabit boyutlu bayt dizileri arasındaki açık dönüşümlere yalnızca her ikisinin de aynı boyuta sahip olması durumunda izin verilir. Tamsayılar ve farklı büyüklükteki sabit boyutlu bayt dizileri arasında dönüşüm yapmak istiyorsanız, istenen kesme ve doldurma kurallarını açık yapan ara dönüşümleri kullanmanız gerekir:

```
bytes2 a = 0x1234;
uint32 b = uint16(a); // b will be 0x00001234
uint32 c = uint32(bytes4(a)); // c will be 0x12340000
uint8 d = uint8(uint16(a)); // d will be 0x34
uint8 e = uint8(bytes1(a)); // e will be 0x12
```
### Değişmezler ve Temel Türler Arasındaki Dönüşümler

#### Tamsayı Türleri
Ondalık ve onaltılık sayı değişmezleri örtük olarak, kesmeden gösterebilecek kadar büyük olan herhangi bir tam sayı türüne dönüştürülebilir:
```
uint8 a = 12; // fine
uint32 b = 1234; // fine
uint16 c = 0x123456; // fails, since it would have to truncate to 0x3456
```
#### Sabit Boyutlu Bayt Dizileri

Ondalık sayı değişmezleri örtük olarak sabit boyutlu bayt dizilerine dönüştürülemez. Onaltılık sayı değişmezleri olabilir, ancak yalnızca onaltılık basamak sayısı bayt türünün boyutuna tam olarak uyarsa bu durum kabul edilebilir. İstisna olarak, sıfır değerine sahip hem ondalık hem de onaltılık değişmezler herhangi bir sabit boyutlu bayt türüne dönüştürülebilir:

```
bytes2 a = 54321; // not allowed
bytes2 b = 0x12; // not allowed
bytes2 c = 0x123; // not allowed
bytes2 d = 0x1234; // fine
bytes2 e = 0x0012; // fine
bytes4 f = 0; // fine
bytes4 g = 0x0; // fine
```

String değişmezleri ve onaltılı dize değişmezleri, karakter sayısı bayt türünün boyutuyla eşleşiyorsa, örtük olarak sabit boyutlu bayt dizilerine dönüştürülebilir:

```
bytes2 a = hex"1234"; // fine
bytes2 b = "xy"; // fine
bytes2 c = hex"12"; // not allowed
bytes2 d = hex"123"; // not allowed
bytes2 e = "x"; // not allowed
bytes2 f = "xyz"; // not allowed
```
### Adresler

Açıklandığı üzere, sağlama toplamı testini geçen doğru boyutta hex değişmezleri adres türündedir. Başka hiçbir değişmez, dolaylı olarak adres türüne dönüştürülemez.

`address payable` ile sonuçlanması için `bytes20` veya herhangi bir tamsayı türündeki açık dönüşümler uygulanmalıdır.

# Birimler ve Global Olarak Mevcut Değişkenler

## Ether Birimleri

Bir sabit sayı, Ether'in alt sınıfını ifade etmek için bir `wei`, `finney`, `szabo` veya `Ether` eki alabilir; bir postfix olmadan kullanılan Ether sayılarının Wei olduğu varsayılır.

```
assert(1 wei == 1);
assert(1 szabo == 1e12);
assert(1 finney == 1e15);
assert(1 ether == 1e18);

```
Alt sınıf eki aslında, onluk bir gücün çarpanı işlevini görür.

## Zaman Birimleri

Gerçek sayılardan sonraki `seconds`, `minutes`, `hours`, `days` ve `weeks` gibi son ekler, saniyelerin temel kabul edildiği bir düzende zaman birimlerini belirlemek için kullanılabilir:

+ 1 == 1 saniye
+ 1 dakika == 60 saniye
+ 1 saat == 60 dakika
+ 1 gün == 24 saat
+ 1 hafta == 7 gün

Bu birimleri kullanarak takvim hesaplamaları yaparken dikkat edin, çünkü her yıl 365 güne eşit değildir. Yine aynı sebeple, her gün tam olarak 24 saat de değildir. Artık saniyelerin tahmin edilememesi nedeniyle, kesin bir takvim kütüphanesinin harici bir oracle tarafından güncellenmesi gerekir.

### [Not]()

> Yukarıdaki nedenlerden dolayı `years` eki 0.5.0 versiyonunda kaldırılmıştır.

Bu sonekler değişkenlere uygulanamaz. Örneğin, bir fonksiyon parametresini gün cinsinden yorumlamak istiyorsanız, aşağıdaki şekilde yapabilirsiniz:

```
function f(uint start, uint daysAfter) public {
    if (now >= start + daysAfter * 1 days) {
      // ...
    }
}
```
## Özel Değişkenler ve Fonksiyonlar

Her zaman global isim olarak var olan ve genellikle blockchain hakkında bilgi sağlamak için kullanılan ya da genel kullanım yardımcı program fonksiyonları olarak işlev gören özel değişkenler ve fonksiyonlar vardır.

### Blok ve İşlem Özellikleri

`blockhash (uint blockNumber) returns (bytes32)`: verilen bloğun hash değeri - geçerli bloklar hariç yalnızca en yeni 256 adet blok için çalışır.
`block.coinbase (payable address)`: mevcut blok madenci adresi
`block.difficulty (uint)`: geçerli blok zorluğu
`block.gaslimit (uint)`: geçerli blok
`block.number (uint)`: geçerli blok numarası
`block.timestamp (uint)`: unix döneminden bu yana saniye olarak geçerli blok zaman damgası
`gasleft () returns (uint256)`: kalan gaz
`msg.data (byte calldata)`: tamamlanmış call verisi
`msg.sender (payable address)`: mesajın göndereni (mevcut çağrı)
`msg.sig (bytes4):` calldata'nın ilk dört baytı (yani fonksiyon tanımlayıcısı)
`msg.value (uint):` mesaj ile gönderilen wei sayısı
`now (uint):` geçerli blok zaman damgası (`block.timestamp` için diğer ad)
`tx.gasprice (uint):` işlemin gaz fiyatı
`tx.origin (payable address):` işlemin göndereni (tam çağrı zinciri)

### [Not]()

>`Msg.sender` ve `msg.value` dahil tüm `msg` üyelerinin değerleri her harici fonksiyon çağrısı için değişebilir. Buna kütüphane fonksiyonlarına yapılan çağrılar da dahildir.

### [Not]()

Ne yaptığınızı bilmiyorsanız, `blockhash`, `now`ve `block.timestamp`'a birer rastgele kaynak olarak güvenmemenizi öneriyoruz.

Hem `timestamp` hem de `blockhash` madencilerden bir dereceye kadar etkilenebilir. Madencilik topluluğundaki kötü aktörler, örneğin, seçilen bir hash için bir kumarhane ödeme işlevi çalıştırabilir ve eğer para alamazlarsa, farklı bir hash ile yeniden deneme yapabilir.

Geçerli `timestamp`, son bloğun zaman damgasından kesinlikle daha büyük olmalıdır. Daha garantili yol ise bu değerin kanonik zincirde iki ardışık bloğun zaman damgaları arasında bir yerde olacağıdır.

### [Not]()

Blok hashleri, ölçeklenebilirlik nedeniyle tüm bloklar için mevcut değildir. Yalnızca en yeni 256 bloğun karma değerlerine erişebilirsiniz, diğer tüm değerler sıfır olacaktır.

### [Not]()

`Blockhash` fonksiyonu daha önce `block.blockhash` olarak bilinmekteydi. 0.4.22 sürümünde kullanımı azaltıldı ve 0.5.0 sürümünden tamamen kaldırılmıştır.

### [Not]()

`gasLeft` işlevi daha önce `msg.gas` olarak bilinmekteydi. 0.4.21 sürümünde kullanımı azaltılmış ve 0.5.0'da ise sürümden tamamen kaldırılmıştır.

## ABI Kodlama ve Kod Çözme Fonksiyonları

+ `abi.decode(bytes memory encodedData, (...)) returns (...):` ABI, verilen verilerin kodunu çözerken, türleri parantez içinde ikinci argüman olarak verilir. Örnek: (`uint a, uint[2] memory b, bytes memory c) = abi.decode(data, (uint, uint[2], bytes`))
+ `abi.encode(...) returns (bytes memory)`: ABI verilen argümanları kodlar
+ `abi.encodePacked(...) returns (bytes memory)`: Verilen bağımsız değişkenlerin paketlenmiş kodlamasını gerçekleştirir. Paketlenmiş kodlamanın belirsiz olabileceğini unutmayın!
+ `abi.encodeWithSelector(bytes4 selector, ...) returns (bytes memory)`: ABI, ikinci değerden başlayarak verilen argümanları kodlar ve verilen dört bayt seçiciyi hazırlar
+ `abi.encodeWithSignature(string memory signature, ...) returns (bytes memory)`: `abi.encodeWithSelector` ile eşdeğer `(abi.encodeWithSelector(bytes4(keccak256(bytes(signature))), ...)`

### [Not]()

Bu kodlama fonksiyonları, harici bir fonksiyon çağırmadan harici fonksiyon çağrıları için veri oluşturmak için kullanılabilir. Dahası, `keccak256 (abi.encodePacked (a, b))`, yapılandırılmış verinin hash değerini hesaplamanın bir yoludur (farklı fonksiyon parametre tipleri kullanarak bir "`hash collusion` yapmanın mümkün olduğunu unutmayın).

Kodlamayla ilgili ayrıntılar için ABI ve paketlenmiş kodlamayla ilgili bölümlere bakın.

## Hata Yönetimi

Hata yönetimi ve ne zaman hangi fonksiyonun kullanılacağı hakkında daha fazla bilgiyi ilgili açıklamanın bulunduğu bölümden edinebilirsiniz.

+ `assert(bool koşulu)`: geçersiz bir opcode'a neden olur ve koşulun karşılanmadığı durumlarda değişikliklerin tersine çevrilmesi durumunda - dahili hatalar için kullanılır.
+ r`equire(bool koşulu)`: koşul karşılanmadığında geri döner - girişlerdeki veya harici bileşenlerdeki hatalar için kullanılır.
+ `require(bool koşulu, string memory mesajı)`: koşul karşılanmadığında geri döner - girişlerdeki veya harici bileşenlerdeki hatalar için kullanılır. Ayrıca bir hata mesajı veriyor.
+ r`evert()`: yürütmeyi durdur ve durum değişikliklerini geri alır.
+ `revert(string memory mesajı)`: açıklayıcı bir dizi sağlayarak yürütmeyi iptal etmek ve durum değişikliklerini geri almak için kullanılır.

## Matematiksel ve Şifreleme Fonksiyonları

+ `addmod(uint x, uint y, uint k) returns (uint)`: Hesaplamanın (x + y)% k olduğu yerde ilavenin keyfi bir hassasiyetle yapıldığı ve 2 ** 256 civarında sarılmadığı hesaplanır. 0.5.0 sürümünden itibaren k! = 0 olduğunu kabul edin.
+ `mulmod(uint x, uint y, uint k) returns (uint)`: (x * y)% k değerini hesaplayın, burada çarpma işlemi keyfi bir şekilde yapılır ve 2 ** 256 değerinde sarmaz. 0.5.0 sürümünden itibaren k! = 0 olduğunu kabul edin.
+ `keccak256(bytes memory) returns (bytes32)`: Giren değerin(input) Keccak-256 hash değerini hesaplar.
+ `sha256(bytes memory) returns (bytes32)`:Giren değerin SHA-256 değerini hesaplar.
+ `ripemd160(bytes memory) returns (bytes20)`: RIPEMD-160 giren değerinin hash değerini hesaplar
+ `ecrecover(bytes32 hash, uint8 v, bytes32 r, bytes32 s) returns (address)`: genel anahtarla ilişkilendirilmiş adresi eliptik eğri imzasından kurtarır veya hata durumunda sıfır döndürür ([örnek kullanım](https://ethereum.stackexchange.com/questions/1777/workflow-on-signing-a-string-with-private-key-followed-by-signature-verificatio))

### [Not]()

`Ecrecover` fonksiyonu bir adres döndürür, bu adres `non-payable` türündedir. Kurtarılan adrese para aktarmanız gerekebilir diye, dönüşüm için `payable` türünde bir adres kullanılması gerekir.

`Sha256` ve `ripemd160` için *Out-Of-Gas* ile karşılaşıyor olabilirsiniz veya **özel bir blokchain ağı** üzerinde `ecrecover`  de aynı sonucu verebilir. Bunun nedeni, önceden derlenmiş sözleşmeler olarak uygulananların ve bu sözleşmelerin yalnızca ilk mesajı aldıktan sonra var olmalarıdır (sözleşme kodları kodlanmış olsa da). Mevcut olmayan sözleşmelere verilen mesajlar daha pahalıdır ve bu nedenle yürütme bir *Out-Of-Gas* hatasıyla sonuçlanır. Bu soruna yönelik bir geçici çözüm ilk önce tüm sözleşmelere örneğin 1 Wei göndermeniz ve daha sonra gerçek sözleşmeye geçmenizdir. Resmi veya test ağında böyle bir sorunla karşılaşmassınız.

### [Not]()

> `Keccak256` 0.5.0 sürümünden önce `sha3` adıyla biliniyordu. Şuanda `sha3` kullanılmıyor.

## Adres Türleri Öğeleri

+ `<adres> .balance (uint256)`: Wei biriminde adres bakiyesi
+ `<address payable>.transfer(uint256 amount)`: Verilen miktarda Wei'yi Adres'e gönderif, başarısızlık durumunda mebla geri döner, ileriye dönük 2300 gaz borusu gönderir.
+ `<address payable>.send(uint256 amount) returns (bool)`: Verilen miktarda Wei'yi Adrese gönderin, başarısızlık durumunda false verir, ileriye dönük 2300 gaz borusu gönderir.
+ `<address>.call(bytes memory) returns (bool, bytes memory)`: Verilen yük ile düşük seviye `CALL` düzenler, başarı durumunu ve iade verilerini geri gönderir.
+ `<address>.delegatecall(bytes memory) returns (bool, bytes memory)`: Verilen yük ile düşük seviye `DELEGATECALL` düzenler, başarı durumu ve iade verilerini iletir.
+ `<address>.staticcall(bytes memory) returns (bool, bytes memory)`: Verilen yük ile düşük seviyeli `STATICCALL` düzenler, başarı durumu ve iade verilerini iletir, mevcut tüm gazları yönlendirir.
  
Daha fazla bilgi için *Adres bölümüne* bakınız.

### [Uyarı]()

> Tür kontrolünü, fonksiyon varlığı kontrolünü ve argüman paketlemesini atladığı için başka bir sözleşme işlevini yürütürken mümkün olduğunda `.call ()` kullanmaktan kaçınmalısınız.

### [Uyarı]()

> `send` kullanımında bazı tehlikeler vardır: Çağrı yığını derinliği 1024'te ise (bu her zaman arayanlar tarafından zorunlu tutulabilir) aktarım başarısız olur veya alıcı gazın bitmesi durumunda da başarısız olur. Bu nedenle, güvenli Ether transferlerini yapmak için, her zaman gönderinin geri dönüş değerini kontrol edin, transfer kullanın veya daha iyisi: Alıcının para çekeceği bir yöntem tercih edin.

### [Not]()

> 0.5.0 sürümünden önce, Solidity, adres üyelerine, örneğin `this.balance` gibi bir sözleşme örneği tarafından erişilmesine izin veriyordu. Bu şimdi yasaktır ve adrese açıkça bir dönüşüm yapılmalıdır: `address (this).balance` gibi.

### [Not]()

> Durum değişkenlerine düşük seviyeli bir temsilci üzerinden erişilirse, çağrılan sözleşmenin, arayan sözleşmenin depolama değişkenlerine ada göre doğru şekilde erişebilmesi için iki sözleşmenin depolama yerleşimi aynı hizada olmalıdır. Tabii ki, depolama işaretçilerinin üst düzey kütüphanelerde olduğu gibi fonksiyon argümanları olarak iletilmesi durumunda geçerli değildir.

### [Not]()

> 0.5.0 sürümünden önce, `.call`, `.delegatecall` ve `.staticcall` yalnızca getiri koşulunu döndürürdü, return verilerini ise döndürmezdi.

### [Not]()

> 0.5.0 versiyonundan önce, `delegatecall`'a benzer fakat biraz farklı bir anlam taşıyan `callcode` adlı bir öğe vardı.

## Sözleşmeyle İlgili

+ `this` (geçerli sözleşmenin türü): Açıkça Adrese çevrilebilir olan mevcut sözleşme
+ `selfdestruct(address payable alıcısı)`: Mevcut sözleşmeyi imha etmek, fonlarını verilen adrese göndermek.

Ayrıca, mevcut sözleşmenin tüm fonksiyonları doğrudan geçerli fonksiyon dahil olmak üzere çağrılabilir.

### [Not]()

0.5.0 sürümünden önce, `selfdestruct` ile aynı semantiklere sahip `suicide` denilen bir fonksiyon vardı.

## Tip Bilgisi

`Type(X)`, X türü hakkında bilgi almak için kullanılabilir. Şu anda, bu özellik için sınırlı destek var, ancak gelecekte genişletilebilir. C tipi bir sözleşme için aşağıdaki özellikler mevcuttur:

+ type(C).creationCode:

Sözleşmenin oluşturma kodunu içeren memory bayt dizisi. Bu, satır içi derlemede, özellikle `create2` opcode kullanılarak, özel oluşturma yordamları için kullanılabilir. Bu özelliğe sözleşmenin kendisinde veya türetilmiş herhangi bir sözleşmede erişilemez. Bayt kodunun çağrı sitesinin bayt koduna dahil edilmesine neden olur ve bu nedenle böyle dairesel referanslar mümkün değildir.

+ `type(C).runtimeCode`:

Sözleşmenin çalışma zamanı kodunu içeren bellek bayt dizisi. Bu, genellikle `C`'nin kurucusu tarafından dağıtılan koddur. `C`, satır içi derleme kullanan bir kurucuya sahipse, bu gerçekte dağıtılan bayt kodundan farklı olabilir. Ayrıca, kitaplıkların düzenli aramalara karşı korunmak için konuşlandırma sırasında çalışma zamanı bayt kodunu değiştirdiğini unutmayın. Bu özellik için `.creationCode` ile aynı kısıtlamalar geçerlidir.



# Güvenlik Hususları

Beklendiği gibi çalışan bir yazılım oluşturmak genellikle oldukça kolay olmakla birlikte, herkesin yazılımı beklendiği şekilde kullanıp kullanmayacağını tahmin etmek çok zordur.

Solidity dili için, bu durum daha da önemlidir çünkü tokenlerle işlem yapmak için akıllı sözleşmeleri yazabiliyor; çok değerli varlıkları bu dille yönetebiliyoruz. Ayrıca, akıllı bir sözleşmenin her uygulaması halka açık olarak geliştirildiğinden kaynak kodu çoğu zaman herkesin erişimine açık durumdadır.

Elbette her zaman ne kadar risk altında olduğunu göz önünde bulundurmanız gerekir: Akıllı bir sözleşmeyi, halka açık bir web servisiyle (ve böylece kötü niyetli aktörlere) ve hatta belki de açık kaynak kodu ile karşılaştırabilirsiniz. Alışveriş listenizi yalnızca bu web hizmetinde saklarsanız, çok fazla dikkat etmeniz gerekmeyebilir, ancak banka hesabınızı bu web hizmetini kullanarak yönetiyorsanız, daha dikkatli olmalısınız.

Bu bölümde bazı tuzaklar ve genel güvenlik önerileri listelenecek ancak elbette asla tamamlanamayacaktır. Ayrıca, akıllı sözleşme kodunuz hatasız olsa bile, derleyicide veya platformda bir hata olabileceğini unutmayın. Derleyicinin halka açık bilinen güvenlikle ilgili bazı hatalarının bir listesi, aynı zamanda makineyle okunabilen bilinen hatalar listesinde bulunabilir. Solidity derleyicisinin kod oluşturucusunu kapsayan bir hata ödül programı olduğunu unutmayın.

Her zaman olduğu gibi, bu bölümü genişletmemize lütfen yardımcı olun (özellikle, bazı örnekler verebilirseniz harika olur)!

## Tuzaklar

### Özel Bilgi ve Rastgelelik

Akıllı bir sözleşmede kullandığınız her şey herkes tarafından görülebilir, hatta özel olarak işaretlenmiş yerel değişkenler ve `private` durum değişkenleri bile.

Madencilerin hile yapmasını istemiyorsanız, akıllı sözleşmelerde rastgele sayılar kullanmak oldukça zordur.

### Yeniden Giriş

Bir sözleşmeden (A) başka bir sözleşmeyle (B) herhangi bir etkileşim ve herhangi bir Ether devresinin kontrolü bu sözleşmeye (B) devretmesi. Bu, B'nin bu etkileşim tamamlanmadan önce A'ya geri dönmesini sağlar. Bir örnek vermek gerekirse, aşağıdaki kod işte bu hatayı içeriyor (bu yalnızca bir snippet ve tam bir sözleşme değil):

```
pragma solidity >=0.4.0 <0.6.0;

// THIS CONTRACT CONTAINS A BUG - DO NOT USE
contract Fund {
    /// Mapping of ether shares of the contract.
    mapping(address => uint) shares;
    /// Withdraw your share.
    function withdraw() public {
        if (msg.sender.send(shares[msg.sender]))
            shares[msg.sender] = 0;
    }
}
```
Sorun, `send` fonksiyonunun bir parçası olarak sınırlı gaz nedeniyle çok ciddi değil, ancak yine de bir zayıflık ortaya koyuyor: Ether transferi her zaman kod yürütmeyi içerebilir, böylece alıcı bir `withdraw` sözleşmesi olabilir. Bu, birden fazla para iadesi almasını ve sözleşmedeki tüm Etherleri geri almasını sağlar. Özellikle, aşağıdaki sözleşme, bir saldırganın varsayılan olarak tüm kalan gazı ileten çağrıyı kullandığı için birden çok kez para iadesine sebep olacaktır:

```
pragma solidity >=0.4.0 <0.6.0;

// THIS CONTRACT CONTAINS A BUG - DO NOT USE
contract Fund {
    /// Mapping of ether shares of the contract.
    mapping(address => uint) shares;
    /// Withdraw your share.
    function withdraw() public {
        (bool success,) = msg.sender.call.value(shares[msg.sender])("");
        if (success)
            shares[msg.sender] = 0;
    }
}
```
Tekrar giriş yapmamak için, aşağıda daha detaylı olarak açıklandığı üzere *Kontroller-Etkiler-Etkileşimler* desenini kullanabilirsiniz:

```
pragma solidity >=0.4.11 <0.6.0;

contract Fund {
    /// Mapping of ether shares of the contract.
    mapping(address => uint) shares;
    /// Withdraw your share.
    function withdraw() public {
        uint share = shares[msg.sender];
        shares[msg.sender] = 0;
        msg.sender.transfer(share);
    }
}
```

Yeniden girişin sadece Ether transferinin değil, başka herhangi bir sözleşmedeki herhangi bir fonksiyon çağrısının bir etkisi olduğunu unutmayın. Ayrıca, çok sözleşmeli durumları da hesaba katmanız gerekir. Bir sözleşme, güvendiğiniz bir başka sözleşmenin durumunu değiştirebilir.

### Gaz Sınırı ve Döngüler

Sabit sayıda yinelemeye sahip olmayan döngüler, örneğin, depolama değerlerine bağlı döngüler, dikkatli bir şekilde kullanılmalıdır: Blok gaz sınırı nedeniyle, işlemler yalnızca belirli miktarda gaz tüketebilir. Açıkça veya sadece normal çalışma nedeniyle, bir döngüdeki yineleme sayısı, kontratın belirli bir noktada durmasına neden olabilecek blok gaz sınırının ötesine geçebilir. Bu, yalnızca blockchain'den veri okumak için yürütülen `view` fonksiyonları için geçerli bir durum olmayabilir. Yine de, bu tür fonksiyonlar zincir içi işlemlerin bir parçası olarak diğer sözleşmelerce çağrılabilir ve bunları durdurur. Lütfen bu tür durumları sözleşmelerinizin belgelerinde açıkça belirtiniz.

### Ether Gönderme ve Alma

Ne kontratlar ne de “dış hesaplar” şu anda birinin Ether göndermesini engelleyememektedir. Sözleşmeler düzenli transferlere tepki verebilir ve reddedebilir, ancak bir mesaj çağrısı oluşturmadan Ether'ı hareket ettirmenin yolları vardır. Bu yollardan biri, sözleşme adresini basitçe “mayınlamak” ve ikinci yol, `selfdestruct(x)` fonksiyonunu kullanmaktır.

Bir sözleşme Ether alırsa (bir işlev çağrılmadan), fallback fonksiyonu yürütülür. Bir fallback fonksiyonuna sahip değilse, Ether (bir istisna atarak) reddedilir. Fallback fonksiyonunun yerine getirilmesi sırasında, sözleşme sadece kendisine verilen “gaz harcına” (2300 gaz) dayanabilir. Bu maaş, depolamayı değiştirmek için yeterli değildir (bunun için verilenleri almayın, maaş gelecekteki sabit çatallarla değişebilir). Sözleşmenizin bu şekilde Ether alabildiğinden emin olmak için, fallback fonksiyonunun gaz gereksinimlerini kontrol edin(örneğin Remix derleyicisi için bu bilgi "detaylar" bölümünde bulunur).

`Addr.call.value (x) ("")` kullanarak alım sözleşmesine daha fazla gaz iletmenin bir yolu vardır. Bu aslında `addr.transfer (x)` ile aynıdır, sadece kalan tüm gazı iletir ve alıcının daha pahalı işlemler yapmasını sağlar (ve hatayı otomatik olarak yaymak yerine bir hata kodu verir). Bu, gönderen sözleşmeye geri arama veya aklınıza gelmeyen diğer durum değişikliklerini içerebilir. Böylece dürüst kullanıcılar için değil aynı zamanda kötü niyetli oyuncular için büyük esneklik sağlar.

`Address.transfer` kullanarak Ether'ı göndermek istiyorsanız, dikkat edilmesi gereken bazı ayrıntılar var:

+ Alıcı bir sözleşme ise, fallback fonksiyonunun yürütülmesine neden olur ve o da gönderen sözleşmeyi geri çağırabilir.

+ Ether'in gönderilmesi, çağrı derinliği 1024'ten fazla olduğu için başarısız olabilir. Arayan, çağrı derinliğini tamamen kontrol ettiğinden, aktarımı başarısız olmaya zorlayabilir; bu olasılığı göz önünde bulundurun veya gönder seçeneğini kullanın ve her zaman iade değerini kontrol ettiğinizden emin olun. En iyi seçenek olarak, sözleşmenizi alıcının Ether'i geri çekebileceği bir kalıp kullanarak yazın.

Ether'in gönderilmesi de başarısız olabilir, çünkü alıcı sözleşmesinin yürütülmesi ayrılan miktardan daha fazla gaz gerektirir (açıkça kullanılması gereken, `require`, `assert`, `revert`, `throw` çok pahalı olduğu için) - “gazın bitmesi” (OOG ). `Transfer`veya `send` fonksiyonu gönderirseniz, bu, alıcının gönderim sözleşmesindeki ilerlemeyi engellemesi için bir yol sağlayabilir. Yine, buradaki en iyi uygulama, "send" deseni yerine "withdraw" deseni tercih etmektir.

### CallStack Derinliği

Harici işlev çağrıları, maksimum 1024 çağrı kümesini aştıkları için herhangi bir zamanda başarısız olabilirler. Bu gibi durumlarda, Solidity bir sıradışı durum bildirir. Kötü niyetli oyuncular kontratınızla etkileşime girmeden önce arama yığınını yüksek bir değere zorlayabilirler.

Çağrı yığını tükenmişse `.send ()` 'in sıradışılık bildirmediğini ancak bu durumda `false` döndürdüğünü unutmayın. Düşük seviyeli işlevler `.call ()`, `.callcode ()`, `.delegatecall ()` ve `.staticcall ()` yine aynı şekilde davranacaktır.

### tx.origin

Asla yetkilendirme için tx.origin kullanmayın. Diyelim ki böyle bir cüzdan sözleşmeniz var:

```
pragma solidity ^0.5.0;

// THIS CONTRACT CONTAINS A BUG - DO NOT USE
contract TxUserWallet {
    address owner;

    constructor() public {
        owner = msg.sender;
    }

    function transferTo(address payable dest, uint amount) public {
        require(tx.origin == owner);
        dest.transfer(amount);
    }
}
```
Şimdi birilerinin bu saldırı cüzdanının adresine eter yollamak için sizi kandırdığı durumu görelim:
```
pragma solidity ^0.5.0;

interface TxUserWallet {
    function transferTo(address payable dest, uint amount) external;
}

contract TxAttackWallet {
    address payable owner;

    constructor() public {
        owner = msg.sender;
    }

    function() external {
        TxUserWallet(msg.sender).transferTo(owner, msg.sender.balance);
    }
}
```
Cüzdanınız yetkilendirme için `msg.sender`’ı kontrol etmiş olsaydı, `owner` adresi yerine saldırı cüzdanının adresini alırdı. Ancak, tx.origin'i kontrol ederek, işlemin başlatan asıl adresini alır, ki bu hala `owner` adresidir. Saldırı cüzdanı bu sayede anında tüm paranızı alabilir.

### İkinin Tamamlayıcısı / Akışı / Taşması

Birçok programlama dilinde olduğu gibi, Solidity’nin tamsayı türleri aslında tamsayı değildir. Değerler küçük olduğunda tam sayılara benzerler, ancak sayılar daha büyükse farklı davranırlar. Örneğin, bu ifade doğrudur: `uint8 (255) + uint8 (1) == 0`. Bu duruma *taşma* denir. Değişken veri türünün aralığının dışındaki bir sayıyı (veya veri parçasını) saklamak için sabit bir boyut değişkeni gerektiren bir işlem gerçekleştirildiğinde gerçekleşir. Bir *akış* ise tersi işlemlerde gerçekleşir: `uint8 (0) - uint8 (1) == 255`.

Genel olarak, karşılaşılablecek özel durumları içeren, iki değerin tamamlayıcı olması için detaylı açıklamaları da okumanız gerekir.

`require` kullanmaya çalışın, girdilerin boyutunu makul bir aralıkta sınırlayın ve olası taşmaları bulmak için SMT denetleyicisini kullanın ya da tüm taşmaların geri dönmesine neden olmak istiyorsanız, SafeMath gibi bir kitaplık kullanın.

`require((balanceOf [_to] + _value)> = balanceOf [_to])` gibi kodlar, değerlerin beklediğiniz gibi olup olmadığını kontrol etmenize yardımcı olabilir.

### Küçük detaylar

Tam 32 baytı işgal etmeyen türler “kirli yüksek dereceli bitler” içerebilir. `Msg.data`'ya erişirseniz bu durum özellikle önemlidir - çünkü bir hassasiyet riski oluşturabilir: `f(uint8 x)` işlevini çağıran işlemleri, `0xff000001` ve `0x00000001` ham bayt argümanıyla oluşturabilirsiniz. Her ikisi de sözleşmeye verilir ve her ikisi de x düşünüldüğünde 1 sayısı gibi görünecektir, ancak `msg.data` farklı olacaktır, bu nedenle bir şey için `keccak256(msg.data`) kullanırsanız, farklı sonuçlar alırsınız.

## Öneriler

### Uyarıları Ciddiye Alın

Derleyici sizi bir şey hakkında uyarırsa, onu değiştirmeniz kodunuz için iyi olacaktır. Bu uyarının güvenlik sorununa neden olacağını düşünmeseniz bile, altına gömülmüş kritik bir soruna neden olabilir. Derleyicinin verdiği uyarılar genellikle kodunuzdaki küçük değişikliklerle susturulabilir.

Yeni tanıtılan tüm uyarılardan haberdar olmak için her zaman derleyicinin en son sürümünü kullanın.

### Ether Miktarını Sınırlayın

Akıllı bir sözleşmede saklanabilecek Ether (veya diğer belirteçler) miktarını sınırlandırın. Kaynak kodunuzda, derleyicide veya platformda bir hata varsa, bu fonlar kaybolabilir. Kaybınızı sınırlamak istiyorsanız, Ether miktarını sınırlandırın.

### Küçük ve Modüler Tutun

Sözleşmelerinizi küçük ve kolayca anlaşılabilir tutun. Diğer sözleşmelerdeki veya kütüphanelerdeki ilgisiz işlevsellikten kurtulun. Elbette kaynak kod kalitesi ile ilgili genel tavsiyeler geçerlidir: Yerel değişkenlerin miktarını, fonksiyonların uzunluğunu vb. sınırlayın. Fonksiyonlarınızı açıkayın, böylece başkalarının kodunuzu anlamasını kolaylaştırın.

### Kontroller-Etkiler-Etkileşimler Örüntüsünü kullanın

Çoğu fonksiyon ilk önce bazı kontroller gerçekleştirir (fonksiyonu çağıran, aralıktaki argümanlar, yeterince Ether göndermişler mi, kişinin belirteçleri var mı, vs.). Bu kontroller önce yapılmalıdır.

İkinci adım olarak, tüm kontroller geçilirse, mevcut sözleşmenin public değişkenlerinde gereken değişiklikler yapılmalıdır. Diğer sözleşmelerle etkileşim, herhangi bir fonksiyondaki en son adım olmalıdır.

İlk dönemlerde, sözleşmeler bazı etkileri geciktirirdi ve harici işlev çağrılarının hatasız bir durumda dönmesini beklerdi. Bu genellikle yukarıda açıklanan yeniden giriş problemi nedeniyle ciddi bir hataya sebep oluyordu.

Ayrıca, bilinen sözleşmelere yapılan aramaların, bilinmeyen sözleşmelere yapılan aramalara neden olabileceğine dikkat edin, bu nedenle, bu modeli her zaman uygulamak muhtemelen daha iyidir.

### Fail-Safe Mod Kullanın

Sisteminizi tamamen merkezi olmayan hale getirirken, herhangi bir aracı aracı ortadan kaldıracak olsa da, özellikle yeni kod için, başarısızlık durumunda çalışacak bir güvenlik mekanizması dahil etmek iyi bir fikir olabilir:

Akıllı sözleşmenize “Ether sızdı mı?”, “Tokenlerin toplamı sözleşmenin bakiyesine eşit mi?” Gibi bazı otomatik kontroller yapan bir fonksiyon ekleyebilirsiniz. Bunun için fazla gaz kullanamayacağınızı aklınızda bulundurun, bu nedenle burada zincir dışı hesaplamalar için yardıma ihtiyacınız olabilir.

Kendi kendini kontrol başarısız olursa, sözleşme otomatik olarak bir tür “arızaya dayanıklı” moduna geçer, örneğin, özelliklerin çoğunu devre dışı bırakır, kontrolü sabit ve güvenilir bir üçüncü tarafa devreder veya sözleşmeyi basit bir *bana paramı geri ver ”sözleşmesine* dönüştürür.

### Başkalarının Kodunuzu Değerlendirmesi isteyin

Bir kod dosyasını ne kadar çok kişi incelerse, o kadar çok sorun bulunur. İnsanlardan kodunuzu incelemelerini istemek de, kodunuzun anlaşılmasının kolay olup olmadığını anlamak için çapraz kontrol olarak yardımcı olur. Bu iyi akıllı sözleşmeler için çok önemli bir kriterdir.

## Resmi Doğrulama

Resmi doğrulama kullanarak, kaynak kodunuzun belirli bir resmi şartnameyi yerine getirdiğine dair otomatik bir kontrol gerçekleştirmek mümkündür. Şartname hala resmi (kaynak kodunda olduğu gibi), ancak genellikle çok daha basit.

Resmi doğrulamanın kendisinin yalnızca yaptığınız (şartname) ile nasıl yaptığınız (gerçek uygulama) arasındaki farkı anlamanıza yardımcı olabileceğini unutmayın. Şartnamenin istediğiniz olup olmadığını kontrol etmenize ve istenmeyen herhangi bir etkiden kaçırmadığınızı kontrol etmeniz gerekir.

# Kaynaklar

## Genel

+ [Ethereum](https://ethereum.org/)
+ [Changelog](https://github.com/ethereum/solidity/blob/develop/Changelog.md)
+ [Kaynak Kodu](https://github.com/ethereum/solidity/)
+ [Ethereum Stackexchange](https://ethereum.stackexchange.com/)
+ [Solidity Kullanıcıları Sohbet](https://gitter.im/ethereum/solidity/)
+ [Compiler Geliştiricileri Sohbet](https://gitter.im/ethereum/solidity-dev/)

## Solidity Entegrasyonları

+ Jenerik:

1. [EthFiddle](https://ethfiddle.com/)
  Tarayıcıdaki Solidity IDE. Solidity kodunuzu yazın ve paylaşın. Sunucu tarafı bileşenleri kullanır.
2. [Remix](https://remix.ethereum.org/)
  Sunucu tarafı bileşenleri olmadan tümleşik derleyici ve Solidity çalışma ortamı içeren tarayıcı tabanlı IDE.
3. [Solium](https://github.com/duaraghav8/Solium/)
  Solidity'de stil ve güvenlik konularını belirlemek ve çözmek için Linter.
4.[Solhint](https://github.com/protofire/solhint)
  Akıllı sözleşme geçerliliği için güvenlik, stil rehberi ve en iyi uygulama kuralları sağlayan Solidity linter.
5. [Superblocks Lab](https://lab.superblocks.com/) 
  Tarayıcı tabanlı IDE. Yerleşik tarayıcı tabanlı VM ve Metamask entegrasyonu (Testnet / Mainnet'e bir tıklamayla dağıtım).

+ Atom:

1. [Etheratom](https://github.com/0mkara/etheratom)
  Atom düzenleyicisi için sözdizimi vurgulama, derleme ve çalışma zamanı ortamı (Ek uç ve VM uyumlu) özelliği.
2. [Atom Solidity Linter](https://atom.io/packages/linter-solidity)
  Solidity linting sağlayan Atom editörü için eklenti.
3. [Atom Solium Linter(https://atom.io/packages/linter-solium)
  Baz olarak Solium kullanan Atom için Yapılandırılabilir Solidty linter.

+Eclipse:

1. [YAKINDU Solidity Araçları](https://yakindu.github.io/solidity-ide/)
  Eclipse tabanlı IDE. Bağlam duyarlı kod tamamlama ve yardım, kod gezinme, sözdizimi renklendirme, yerleşik derleyici, hızlı düzeltmeler ve şablonlar içerir.

+Emacs:

1. [Emacs Solidity](https://github.com/ethereum/emacs-solidity/)
  Emacs editörü için eklenti sözdizimi vurgulama ve derleme hatası raporlama sağlar.

+IntelliJ:

1. [IntelliJ IDEA eklentisi](https://plugins.jetbrains.com/plugin/9475-intellij-solidity)
  IntelliJ IDEA için Solidity eklentisi (ve diğer tüm JetBrains IDE'ler)

+Sublime:

1. [SublimeText için Paket - Solidity dili sözdizimi](https://packagecontrol.io/packages/Ethereum/)
  SublimeText editörü için vurgulama sözdizimi.

+Vim:

1. [Vim Solidity](https://github.com/tomlion/vim-solidity/)
Sözdizimi vurgulama sağlayan Vim editörü için eklenti.
2. [Vim Sözdizimi](https://github.com/scrooloose/syntastic)
Derleme kontrolü sağlayan Vim editörü için eklenti.

+Visual Studio Kodu:

1. [Visual Studio Kod uzantısı](http://juan.blanco.ws/solidity-contracts-in-visual-studio-code/)
  Microsoft Visual Studio Code için sözdizimi vurgulaması ve Solidity derleyicisini içeren Solidity eklentisi.

Durdurulan:

1. [Karışık IDE](https://github.com/ethereum/mix/)
Solidity akıllı sözleşmelerin tasarlanması, hata ayıklaması ve test edilmesi için Qt tabanlı IDE.

2. [Ethereum Studio](https://live.ether.camp/)
Tam bir Ethereum ortamına kabuk erişimi sağlayan özel web IDE.

3. [Visual Studio Uzantısı](https://visualstudiogallery.msdn.microsoft.com/96221853-33c4-4531-bdd5-d2ea5acc4799/)
Solidity derleyicisini içeren Microsoft Visual Studio için Solidity eklentisi.

## Solidity Araçları

+ [Dapp](https://dapp.tools/dapp/)
Solidity için araç, paket yöneticisi ve dağıtım asistanı oluşturun.
+ Solidity REPL(https://github.com/raineorshine/solidity-repl)
Komut satırı Solidity konsolu ile hemen Solidity'yi deneyin.
+ [solgraph](https://github.com/raineorshine/solgraph)
Solidity kontrol akışını görselleştirin ve potansiyel güvenlik açıklarını vurgulayın.
+ [Doxity](https://github.com/DigixGlobal/doxity)
Solidity için dokümantasyon Jeneratör.
+ [evmdis](https://github.com/Arachnid/evmdis)
Ham EVM işlemlerinden daha yüksek bir soyutlama düzeyi sağlamak için byte kodunda statik analiz yapan EVM Disassembler.
+ [ABI Solidity arayüz dönüştürücü](https://gist.github.com/chriseth/8f533d133fa0c15b0d6eaf3ec502c82b)
Akıllı bir sözleşmenin ABI'sinden sözleşme arayüzleri oluşturmak için bir senaryo.
+ [Securify](https://securify.ch/)
Akıllı sözleşmeler için tam otomatik çevrimiçi statik analizör, güvenlik açığı kalıplarına dayalı bir güvenlik raporu sunar.
+ [Sürya](https://github.com/ConsenSys/surya/)
Akıllı sözleşme sistemleri için bir takım görsel çıktılar ve sözleşmelerin yapısı hakkında bilgiler sunan yardımcı program aracı. Ayrıca, işlev çağrısı grafiğini sorgulamayı da destekler.
+ [EVM Lab](https://github.com/ethereum/evmlab/)
EVM ile etkileşime girmek için zengin takım paketi. Bir VM, Etherchain API ve gaz maliyet göstergeli bir izleyici içerir.

### [Not]()

> Derleme işleminde değişken isimleri, yorumlar ve kaynak kodu formatlama gibi bilgiler kaybedilir ve orijinal kaynak kodunun tamamen geri kazanılması mümkün değildir. Özgün kaynak kodunu veya kod yapısını görüntülemek için akıllı sözleşmelerin açılması mümkün olmayabilir.

## Üçüncü Parti Solidity Parserleri

+ [Solidity-Parser](https://github.com/ConsenSys/solidity-parser)
  JavaScript için Solidity ayrıştırıcısı
+ [ANTLR 4 için Solidity Syntax](https://github.com/federicobond/solidity-antlr4)
  ANTLR 4 ayrıştırıcı jeneratör için Solidity gramer
  
# Derleyici Kullanımı

## Komut Satırı Derleyicisini Kullanma

### [Not]()

> Komut satırı modunda kullanılsa bile bu bölüm `solcjs` için geçerli değildir.

Solidity deposunun inşa hedeflerinden biri `solc`, solidity komut satırı derleyicisidir. `solc --help` kullanımı, tüm olası seçeneklerin açıklamasını sağlar. Derleyici, basit ikili dosyalardan ve montajdan soyut bir sözdizimi ağacı (ayrıştırma ağacı) üzerinden gaz kullanımı tahminlerine kadar çeşitli çıktılar üretebilir. Yalnızca tek bir dosyayı derlemek istiyorsanız, dosyayı `solc --bin sourceFile.sol` olarak çalıştırın ve ikili dosyayı yazdırın. Solc'un daha gelişmiş çıktı değişkenlerinden bazılarını elde etmek istiyorsanız, `solc -o outputDirectory --bin --ast --asm sourceFile.sol` kullanarak dosyaları ayırmak için her şeyi çıkarmasını söylemek daha iyidir.

Sözleşmenizi yayınlamadan önce, `solc --optimize --bin sourceFile.sol` kullanarak derlerken en iyi duruma getiriciyi etkinleştirin. Varsayılan olarak, bu iyileştirici, sözleşmenin ömrü boyunca 200 kez çağrıldığı varsayılarak sözleşmeyi optimize eder. İlk sözleşme dağıtımının daha ucuz olmasını ve daha sonraki fonksiyon işlemlerinin daha pahalı olmasını istiyorsanız, `--optimize-running = 1` olarak ayarlayın. Çok fazla fonksiyon çalıştırıyorsanız ve daha yüksek dağıtım maliyeti ve çıktı boyutunu umursamıyorsanız, `--optimize-running`'ları yüksek bir sayıya ayarlayın.

Komut satırı derleyicisi, içe aktarılan dosyaları dosya sisteminden otomatik olarak okuyacaktır, ancak `prefix = path`'i kullanarak aşağıdaki şekilde yol yönlendirmeleri sağlamak da mümkündür:
  
```
solc github.com/ethereum/dapp-bin/=/usr/local/lib/dapp-bin/ file.sol

```
Bu esasen derleyiciye `github.com/ethereum/dapp-bin/ ile / usr / local / lib / dapp-bin` altında başlayan herhangi bir şeyi aramasını söyler. `solc`, yeniden hedeflenen hedeflerin dışında ve açıkça belirtilen kaynak dosyalarının bulunduğu dizinlerin dışında kalan dosya sisteminden dosya okumaz; bu nedenle `"/ etc / passwd"` komutunu içe aktarır; Yalnızca `/ = /` remapping olarak eklerseniz çalışın.

Boş bir remapping öneki kullanımına izin verilmez.

Remapping nedeniyle birden fazla eşleşme varsa, en uzun ortak öneki olan bir tanesi seçilir.

Güvenlik nedeniyle, derleyicinin hangi dizinlere erişebileceği konusunda kısıtlamalar vardır. Komut satırında belirtilen kaynak dosyalarının yolları (ve bunların alt dizinleri) ve yeniden yapılanmalarla tanımlanan yolların içe aktarım ifadelerine izin verilir, ancak diğer her şey reddedilir. Ek yollara (ve bunların alt dizinlerine) izin verilen `--allow-paths / sample / path, / another / sample / path` anahtarı aracılığıyla ulaşılır.

Sözleşmeleriniz kitaplık kullanıyorsa, bayt kodunun `__ $ 53aea86b7d70b31448b230b20ae141a537 $ __` biçimindeki alt dizeleri içerdiğini fark edeceksiniz. Bunlar gerçek kütüphane adreslerinin yer tutucularıdır. Yer tutucu, tam nitelikli kütüphane adındaki `keccak256` karmasının onaltılı kodlamasının 34 karakterlik bir önekidir. Bayt kodu dosyası ayrıca yer tutucuların hangi kitaplıkları temsil ettiğini belirlemeye yardımcı olmak için sonunda `// <placeholder> -> <fq library name>` biçiminde satırlar içerecektir. Tam nitelikli kitaplık adının kaynak dosyasının ve kitaplık adının ayrıldığı yol olduğuna dikkat edin. `Solc`'u bir `linker` olarak kullanabilirsiniz, yani kütüphane adreslerini sizin için bu noktalara yerleştirir:

`--Libraries "file.sol: Math: 0x1234567890123456789012345678901234567890 file.sol: Heap: 0xabCD567890123456789012345678901234567890"` komutunu kullanarak her kütüphanenize bir adres sağlayacabilir veya dosyalarınızın saklanması için bir konum sağlayabilirsiniz. `--libraries fileName` komutunu kullanarak `solc`ü çalıştırın.

Solc - link seçeneğiyle çağrılırsa, tüm girdi dosyaları yukarıda verilen `__ $ 53aea86b7d70b31448b230b20ae141a537 $ __- ` biçiminde bağlantısız ikili dosyalar (hex-kodlanmış) olarak yorumlanır ve girdiler yerinde (eğer girdiler `stdin`'den okunursa) , `stdout`'a yazılmıştır). Bu durumda - kiralamalar hariç tüm seçenekler (-o dahil) yoksayılır.

Solc, `--standard-json` seçeneğiyle çağrılırsa, standart girişte bir JSON girişi (aşağıda açıklandığı gibi) bekleyecek ve standart çıkışta bir JSON çıkışı döndürecektir. Bu, daha karmaşık ve özellikle de otomatikleştirilmiş kullanımlar için önerilen arayüzdür.

### [Not]()

> Kütüphane yer tutucusu, hash yerine kütüphanenin kendisinin tam adıdır. Bu format hala `solc - link` tarafından desteklensede, derleyici artık çıktı vermeyecektir. Bu değişiklik, kütüphaneler arasında bir çarpışma olasılığını azaltmak için yapılmıştır, çünkü tam nitelikli kütüphanenin adının yalnızca ilk 36 karakteri kullanılabilmiştir.

## EVM Sürümünü Hedefe Ayarlama

Sözleşme kodunuzu derlerken, belirli özelliklerden veya davranışlardan kaçınmak için derlenecek Ethereum sanal makine versiyonunu belirleyebilirsiniz.

### [Uyarı]()

>Yanlış EVM sürümünün derlenmesi yanlış, garip ve başarısız davranışlarla sonuçlanabilir. Lütfen özel bir zincir kullanıyorsanız, eşleşen EVM sürümlerini kullandığınızdan emin olun.

Komut satırında EVM sürümünü aşağıdaki gibi seçebilirsiniz:
```
solc - evm-version <SÜRÜM> sözleşme.sol
```
Standart JSON arayüzünde, `settings` alanındaki `evmVersion` anahtarını kullanın:

```

  "sources": { ... },
  "settings": {
    "optimizer": { ... },
    "evmVersion": "<VERSION>"
  }
}
```
### Hedef seçenekleri

Aşağıda hedef EVM sürümlerinin ve her bir sürümde tanıtılan derleyiciyle ilgili değişikliklerin bir listesi bulunmaktadır. Her sürüm arasında geriye dönük uyumluluk garanti edilmez.

+ `homestead` (en eski sürüm)
+ `tangerineWhistle`
  Diğer hesaplara erişim için gaz maliyeti artarken, gaz tahmini ve kullanımı ile ilgili.
  Harici aramalar için varsayılan olarak gönderilen tüm gazlar için önceden belirli bir miktarın blokajı.
+ `spuriousDragon`
  `exp` opcode için gaz maliyeti, gaz kestirimi ve optimize edici ile ilgili olarak arttı.
+ `byzantium` (varsayılan)
  opcodes `returndatacopy`, `returndatasize` ve `staticcall` montajda kullanılabilir.
  `staticcall` opcode, kütüphane dışı görünümü veya saf işlevleri çağırırken kullanılır; bu, işlevlerin EVM düzeyinde durum değiştirmesini önler, yani geçersiz tür dönüşümleri kullandığınızda bile geçerlidir.
  İşlev çağrılarından döndürülen dinamik verilere erişmek mümkündür.
  `revert` kodu tanıtıldı, bu return()ün, gaz harcamasına neden olmayacağı anlamına gelir.
+ `Constantinople` (hala devam ediyor)
  `shl`, `shr` ve `sar` opcoları montajda mevcuttur.
  vites değiştirme operatörleri, değişen işlem kodlarını kullanır ve bu nedenle daha az gaza ihtiyaç duyar.

## Derleyici Giriş ve Çıkış JSON Açıklaması

Özellikle daha karmaşık ve otomatik kurulumlar için Solidity compiler ile arayüz oluşturmanın önerilen yolu JSON-giriş-çıkış arayüzüdür. Aynı arabirim, derleyicinin tüm dağıtımları tarafından sağlanır.

Alanlar genellikle değişime tabidir, bazıları isteğe bağlıdır (belirtildiği gibi), ancak yalnızca geriye dönük uyumlu değişiklikler yapmaya çalışıyoruz.

Derleyici API, JSON formatlı bir girdi bekler ve derleme sonucunu JSON formatlı bir çıktı olarak verir.

Aşağıdaki alt bölümler, bir örnek yoluyla formatı açıklar. Elbette, açıklamalara izin verilmez ve burada sadece açıklayıcı amaçlar için kullanılır.

### Giriş Açıklaması

```
{
  // Required: Source code language, such as "Solidity", "Vyper", "lll", "assembly", etc.
  "language": "Solidity",
  // Required
  "sources":
  {
    // The keys here are the "global" names of the source files,
    // imports can use other files via remappings (see below).
    "myFile.sol":
    {
      // Optional: keccak256 hash of the source file
      // It is used to verify the retrieved content if imported via URLs.
      "keccak256": "0x123...",
      // Required (unless "content" is used, see below): URL(s) to the source file.
      // URL(s) should be imported in this order and the result checked against the
      // keccak256 hash (if available). If the hash doesn't match or none of the
      // URL(s) result in success, an error should be raised.
      // Using the commandline interface only filesystem paths are supported.
      // With the JavaScript interface the URL will be passed to the user-supplied
      // read callback, so any URL supported by the callback can be used.
      "urls":
      [
        "bzzr://56ab...",
        "ipfs://Qma...",
        "/tmp/path/to/file.sol"
        // If files are used, their directories should be added to the command line via
        // `--allow-paths <path>`.
      ]
    },
    "mortal":
    {
      // Optional: keccak256 hash of the source file
      "keccak256": "0x234...",
      // Required (unless "urls" is used): literal contents of the source file
      "content": "contract mortal is owned { function kill() { if (msg.sender == owner) selfdestruct(owner); } }"
    }
  },
  // Optional
  "settings":
  {
    // Optional: Sorted list of remappings
    "remappings": [ ":g/dir" ],
    // Optional: Optimizer settings
    "optimizer": {
      // disabled by default
      "enabled": true,
      // Optimize for how many times you intend to run the code.
      // Lower values will optimize more for initial deployment cost, higher values will optimize more for high-frequency usage.
      "runs": 200
    },
    "evmVersion": "byzantium", // Version of the EVM to compile for. Affects type checking and code generation. Can be homestead, tangerineWhistle, spuriousDragon, byzantium or constantinople
    // Metadata settings (optional)
    "metadata": {
      // Use only literal content and not URLs (false by default)
      "useLiteralContent": true
    },
    // Addresses of the libraries. If not all libraries are given here, it can result in unlinked objects whose output data is different.
    "libraries": {
      // The top level key is the the name of the source file where the library is used.
      // If remappings are used, this source file should match the global path after remappings were applied.
      // If this key is an empty string, that refers to a global level.
      "myFile.sol": {
        "MyLib": "0x123123..."
      }
    }
    // The following can be used to select desired outputs based
    // on file and contract names.
    // If this field is omitted, then the compiler loads and does type checking,
    // but will not generate any outputs apart from errors.
    // The first level key is the file name and the second level key is the contract name.
    // An empty contract name is used for outputs that are not tied to a contract
    // but to the whole source file like the AST.
    // A star as contract name refers to all contracts in the file.
    // Similarly, a star as a file name matches all files.
    // To select all outputs the compiler can possibly generate, use
    // "outputSelection: { "*": { "*": [ "*" ], "": [ "*" ] } }"
    // but note that this might slow down the compilation process needlessly.
    //
    // The available output types are as follows:
    //
    // File level (needs empty string as contract name):
    //   ast - AST of all source files
    //   legacyAST - legacy AST of all source files
    //
    // Contract level (needs the contract name or "*"):
    //   abi - ABI
    //   devdoc - Developer documentation (natspec)
    //   userdoc - User documentation (natspec)
    //   metadata - Metadata
    //   ir - New assembly format before desugaring
    //   evm.assembly - New assembly format after desugaring
    //   evm.legacyAssembly - Old-style assembly format in JSON
    //   evm.bytecode.object - Bytecode object
    //   evm.bytecode.opcodes - Opcodes list
    //   evm.bytecode.sourceMap - Source mapping (useful for debugging)
    //   evm.bytecode.linkReferences - Link references (if unlinked object)
    //   evm.deployedBytecode* - Deployed bytecode (has the same options as evm.bytecode)
    //   evm.methodIdentifiers - The list of function hashes
    //   evm.gasEstimates - Function gas estimates
    //   ewasm.wast - eWASM S-expressions format (not supported atm)
    //   ewasm.wasm - eWASM binary format (not supported atm)
    //
    // Note that using a using `evm`, `evm.bytecode`, `ewasm`, etc. will select every
    // target part of that output. Additionally, `*` can be used as a wildcard to request everything.
    //
    "outputSelection": {
      "*": {
        "*": [
          "metadata", "evm.bytecode" // Enable the metadata and bytecode outputs of every single contract.
          , "evm.bytecode.sourceMap" // Enable the source map output of every single contract.
        ],
        "": [
          "ast" // Enable the AST output of every single file.
        ]
      },
      // Enable the abi and opcodes output of MyContract defined in file def.
      "def": {
        "MyContract": [ "abi", "evm.bytecode.opcodes" ]
      }
    }
  }
}
```
### Çıkış Açıklaması
```
{
  // Optional: not present if no errors/warnings were encountered
  "errors": [
    {
      // Optional: Location within the source file.
      "sourceLocation": {
        "file": "sourceFile.sol",
        "start": 0,
        "end": 100
      ],
      // Mandatory: Error type, such as "TypeError", "InternalCompilerError", "Exception", etc.
      // See below for complete list of types.
      "type": "TypeError",
      // Mandatory: Component where the error originated, such as "general", "ewasm", etc.
      "component": "general",
      // Mandatory ("error" or "warning")
      "severity": "error",
      // Mandatory
      "message": "Invalid keyword"
      // Optional: the message formatted with source location
      "formattedMessage": "sourceFile.sol:100: Invalid keyword"
    }
  ],
  // This contains the file-level outputs. In can be limited/filtered by the outputSelection settings.
  "sources": {
    "sourceFile.sol": {
      // Identifier of the source (used in source maps)
      "id": 1,
      // The AST object
      "ast": {},
      // The legacy AST object
      "legacyAST": {}
    }
  },
  // This contains the contract-level outputs. It can be limited/filtered by the outputSelection settings.
  "contracts": {
    "sourceFile.sol": {
      // If the language used has no contract names, this field should equal to an empty string.
      "ContractName": {
        // The Ethereum Contract ABI. If empty, it is represented as an empty array.
        // See https://github.com/ethereum/wiki/wiki/Ethereum-Contract-ABI
        "abi": [],
        // See the Metadata Output documentation (serialised JSON string)
        "metadata": "{...}",
        // User documentation (natspec)
        "userdoc": {},
        // Developer documentation (natspec)
        "devdoc": {},
        // Intermediate representation (string)
        "ir": "",
        // EVM-related outputs
        "evm": {
          // Assembly (string)
          "assembly": "",
          // Old-style assembly (object)
          "legacyAssembly": {},
          // Bytecode and related details.
          "bytecode": {
            // The bytecode as a hex string.
            "object": "00fe",
            // Opcodes list (string)
            "opcodes": "",
            // The source mapping as a string. See the source mapping definition.
            "sourceMap": "",
            // If given, this is an unlinked object.
            "linkReferences": {
              "libraryFile.sol": {
                // Byte offsets into the bytecode. Linking replaces the 20 bytes located there.
                "Library1": [
                  { "start": 0, "length": 20 },
                  { "start": 200, "length": 20 }
                ]
              }
            }
          },
          // The same layout as above.
          "deployedBytecode": { },
          // The list of function hashes
          "methodIdentifiers": {
            "delegate(address)": "5c19a95c"
          },
          // Function gas estimates
          "gasEstimates": {
            "creation": {
              "codeDepositCost": "420000",
              "executionCost": "infinite",
              "totalCost": "infinite"
            },
            "external": {
              "delegate(address)": "25000"
            },
            "internal": {
              "heavyLifting()": "infinite"
            }
          }
        },
        // eWASM related outputs
        "ewasm": {
          // S-expressions format
          "wast": "",
          // Binary format (hex string)
          "wasm": ""
        }
      }
    }
  }
}
```
## Hata türleri
`JSONError`: JSON girişi, istenen formata uygun değil; giriş bir JSON nesnesi değil, dil desteklenmiyor.
`IOError`: IO ve çözülemeyen URL veya sağlanan kaynaklardaki karma uyuşmazlık gibi işleme hatalarını içe aktarın.
`ParserError`: Kaynak kodu dil kurallarına uymuyor.
`DocstringParsingError`: Yorum bloğundaki NatSpec etiketleri ayrıştırılamaz.
`SyntaxError`: `continue` gibi sözdizimsel bir hata `for` döngüsünün dışında kullanılır.
`DeclarationError`: Geçersiz, çözülemeyen veya çakışan tanımlayıcı adları. Örneğin. `Identifier Not Found`
`TypeError`: Yazım sistemi içinde geçersiz tür dönüştürmeleri, geçersiz atama vb. Gibi hatalar
`UnimplementedFeatureError`: Özellik, derleyici tarafından desteklenmiyor, ancak gelecek sürümlerde desteklenmesi bekleniyor.
`InternalCompilerError`: Derleyicide tetiklenen dahili hata - bu bir sorun olarak rapor edilmelidir.
`Exception`: Derleme sırasındaki bilinmeyen hata - bu bir sorun olarak rapor edilmelidir.
`CompilerError`: Derleyici yığınının geçersiz kullanımı - bu bir sorun olarak bildirilmelidir.
`FatalError`: Ölümcül hata doğru işlenmedi - bu bir sorun olarak bildirilmelidir.
`Warning`: Derlemeyi durdurmayan, ancak mümkünse ele alınması gereken bir uyarı.


# Sözleşme Meta Verileri

Solidity derleyicisi, geçerli sözleşme hakkında bilgi içeren sözleşme meta verileri olan bir JSON dosyası otomatik olarak oluşturur. Bu dosyayı derleyici sürümünü, kullanılan kaynakları, ABI ve NatSpec belgelerini sözleşmeyle daha güvenli bir şekilde etkileşime sokmak ve kaynak kodunu doğrulamak için kullanabilirsiniz.

Derleyici, her bir sözleşmenin bayt kodunun sonuna (ayrıntılar için aşağıya bakınız) meta veri dosyasının bir sürüsünü ekler, böylece dosyayı merkezi bir veri sağlayıcıya başvurmak zorunda kalmadan kimliği doğrulanmış bir şekilde alabilirsiniz.

Başkalarının erişebilmesi için meta veri dosyasını Swarm'a (veya başka bir hizmete) yayınlamanız gerekir. `ContractName_meta.json` adlı bir dosya üreten `solc --metadata` komutunu kullanarak bu dosyayı yaratırsınız. Kodunuz Swarm referansları içerir, bu nedenle tüm kaynak dosyalarını ve meta veri dosyasını yüklemeniz gerekir.

Meta veri dosyası aşağıdaki biçime sahiptir. Aşağıdaki örnek insan tarafından okunabilir bir şekilde sunulmaktadır. Düzgün biçimlendirilmiş meta veriler tırnakları doğru kullanmalı, boşlukları en aza indirmeli ve benzersiz bir biçimlendirmeye ulaşmak için tüm nesnelerin anahtarlarını sıralamalıdır. Yorumlara izin verilmez ve burada sadece açıklayıcı amaçlar için kullanılır.
```
{
  // Required: The version of the metadata format
  version: "1",
  // Required: Source code language, basically selects a "sub-version"
  // of the specification
  language: "Solidity",
  // Required: Details about the compiler, contents are specific
  // to the language.
  compiler: {
    // Required for Solidity: Version of the compiler
    version: "0.4.6+commit.2dabbdf0.Emscripten.clang",
    // Optional: Hash of the compiler binary which produced this output
    keccak256: "0x123..."
  },
  // Required: Compilation source files/source units, keys are file names
  sources:
  {
    "myFile.sol": {
      // Required: keccak256 hash of the source file
      "keccak256": "0x123...",
      // Required (unless "content" is used, see below): Sorted URL(s)
      // to the source file, protocol is more or less arbitrary, but a
      // Swarm URL is recommended
      "urls": [ "bzzr://56ab..." ]
    },
    "mortal": {
      // Required: keccak256 hash of the source file
      "keccak256": "0x234...",
      // Required (unless "url" is used): literal contents of the source file
      "content": "contract mortal is owned { function kill() { if (msg.sender == owner) selfdestruct(owner); } }"
    }
  },
  // Required: Compiler settings
  settings:
  {
    // Required for Solidity: Sorted list of remappings
    remappings: [ ":g/dir" ],
    // Optional: Optimizer settings (enabled defaults to false)
    optimizer: {
      enabled: true,
      runs: 500
    },
    // Required for Solidity: File and name of the contract or library this
    // metadata is created for.
    compilationTarget: {
      "myFile.sol": "MyContract"
    },
    // Required for Solidity: Addresses for libraries used
    libraries: {
      "MyLib": "0x123123..."
    }
  },
  // Required: Generated information about the contract.
  output:
  {
    // Required: ABI definition of the contract
    abi: [ ... ],
    // Required: NatSpec user documentation of the contract
    userdoc: [ ... ],
    // Required: NatSpec developer documentation of the contract
    devdoc: [ ... ],
  }
}
```
### [Uyarı]()
> Sonuçta ortaya çıkan sözleşmenin bayt kodu meta veri hashi içerdiğinden, meta verilerde yapılan herhangi bir değişiklik, bayt kodunun değişmesine neden olur. Bu bir dosya adı veya yolundaki değişiklikleri içerir ve meta veriler kullanılan tüm kaynakların bir karmasını içerdiğinden, tek bir beyaz boşluk değişikliği farklı meta verilerde ve farklı bytecode'larda sonuç verebilir.

### [Not]()

> Yukarıdaki ABI tanımının sabit bir sıraya sahip olmadığını unutmayın. Derleyici sürümleriyle değişebilir.

## Byte Kodunda Meta Veri Hash'in Kodlanması

Gelecekte meta veri dosyasını almanın başka yollarını da destekleyebileceğimizden, `{"bzzr0": <Swarm hash>}` eşlemesi `CBOR` kodlu olarak depolanır. Bu kodlamanın başlangıcını bulmak kolay olmadığından, uzunluğu iki baytlık bir büyük kodlayıcı koduna eklenir. Solidity derleyicisinin geçerli sürümü böylece dağıtılan bayt kodunun sonuna aşağıdakini ekler:

```
0xa1 0x65 'b' 'z' 'z' 'r' '0' 0x58 0x20 <32 bayt sürüsü karma> 0x00 0x29
```
Böylece verileri almak için, konuşlandırılan bayt kodunun sonu bu modelle eşleşecek şekilde kontrol edilebilir ve dosyayı almak için Swarm özeti kullanılır.

### [Not]()

> Derleyici şu anda meta verinin "sürüsü sürüm 0" değerini kullanıyor, ancak gelecekte değişebilir, bu nedenle `0xa1 0x65 'b' 'z' 'z' 'r' '0'` ile başlamak için bu diziye güvenmeyin . Bu CBOR yapısına ek veri de ekleyebiliriz, bu nedenle en iyi seçenek uygun bir CBOR ayrıştırıcı kullanmaktır.

## Otomatik Arayüz Üretimi ve NatSpec Kullanımı

Meta veriler şu şekilde kullanılır: Bir sözleşmeyle etkileşimde bulunmak isteyen bir bileşen (örneğin, Mist veya herhangi bir cüzdan), sözleşmenin kodunu alır, daha sonra alınan bir dosyanın Swarm'dan alır. Bu dosya JSON ile kodlanmış, yukarıdaki gibi bir yapıya dönüştürülmüş.

Bileşen daha sonra ABI'yi sözleşme için basit bir kullanıcı arayüzü oluşturmak için kullanabilir.

Ayrıca cüzdan, sözleşmeyle etkileşime girdiklerinde kullanıcıya, işlem imzası için izin istemekle birlikte kullanıcıya bir onay mesajı görüntülemek için 'NatSpec' kullanıcı belgelerini kullanabilir.

Ethereum Natural Specification (NatSpec) hakkında ek bilgi [burada](https://github.com/ethereum/wiki/wiki/Ethereum-Natural-Specification-Format) bulunabilir.

## Kaynak Kod Doğrulama Kullanımı

Derlemeyi doğrulamak için, kaynaklar meta veri dosyasındaki bağlantı yoluyla Swarm'dan alınabilir. Doğru sürümün derleyicisi (“resmi” derleyicilerin bir parçası olarak kontrol edilir) belirtilen girdilerle bu girdiye çağrılır. Elde edilen bytecode, yaratma işleminin veya 'CREATE' opcode verilerinin verileriyle karşılaştırılır. Bu, hash bayt kodunun bir parçası olduğundan meta verileri otomatik olarak doğrular. Aşırı veri, arayüze göre çözülmesi ve kullanıcıya sunulması gereken yapıcı girdi verilerine karşılık gelir.



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
