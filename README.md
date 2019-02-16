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
  - 
  
  Temelleri
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
===

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

