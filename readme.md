<p align="center">
<a href="https://getbootstrap.com">
<img src="https://getbootstrap.com/docs/5.3/assets/brand/bootstrap-logo-shadow.png" alt="Bootstrap logo" width="200" height="165">
</a>
</p>

<h3 align="center">Bootstrap</h3>

<p align="center">
    Şık, sezgisel ve güçlü bir ön uç çerçevesi ile daha hızlı ve kolay web geliştirme.
    <br>
    <a href="https://getbootstrap.com/docs/5.3">
        <strong>Bootstrap dokümantasyonunu keşfedin.</strong>
    </a>
    <br>
    <br>
    <a href="https://github.com/twbs/bootstrap/issues/new?assignees=-&labels=bug&template=bug_report.yml">
        Hata bildir
    </a>
    .
    <a href="https://github.com/twbs/bootstrap/issues/new?assignees=&labels=feature&template=feature_request.yml">
        Özellik iste
    </a>
    .
    <a href="https://themes.getbootstrap.com/">
        Temalar
    </a>
    .
    <a href="https://blog.getbootstrap.com">
        Blog
    </a>
</p>

## Bootstrap 5

Bootstrap, modern ve duyarlı web siteleri oluşturmayı kolaylaştıran açık kaynaklı bir CSS çerçevesidir. HMTL, CSS ve Javascript ile önceden oluşturulmuş bileşenler ve 12 sütunlu ızgara sistemi sunarak, geliştiricilerin hızlı ve tutarlı arayüzler oluşturmasını sağlar. Duyarlı tasarım prensipleriyle mobil uyumluluk sunan Bootstrap, butonlar, formlar, modal pencereler ve açılır menüler gibi birçok hazır bileşen içerir. Ayrıca, özelleştirilebilir tema seçenekleri ve Javascript eklentileri ile geliştirme sürecini hızlandırarak esneklik sağlar.

## İçindekiler

- [Hızlı Başlangıç](#hızlı-başlangıç)
- [Durum](#durum)
- [Neler Dahil](#neler-dahil)
- [Hata ve Özellik Talepleri](#hata-ve-özellik-talepleri)
- [Dokümantasyon](#dokümantasyon)
- [Katkıda Bulunma](#katkıda-bulunma)
- [Topluluk](#topluluk)
- [Sürümleme](#sürümleme)
- [Geliştiriciler](#geliştiriciler)
- [Teşekkürler](#teşekkürler)
- [Telif Hakkı ve Lisans](#telif-hakkı-ve-lisans)

## Hızlı Başlangıç

Birden fazla hızlı başlangıç seçeneği mevcuttur:

- [En son sürümü indir](https://github.com/twbs/bootstrap/archive/v5.3.3.zip)

- Depoyu klonla: `git clone https://github.com/twbs/bootstrap.git`

- [npm](https://www.npmjs.com) ile yükle: `npm install bootstrap@v5.3.3`

- [yarn](https://yarnpkg.com/) ile yükle: `yarn add bootstrap@v5.3.3`

- [Composer](https://getcomposer.org/) ile yükle: `composer require twbs/bootstrap:5.3.3`

- [NuGet](https://www.nuget.org/) ile yükle: CSS: `Install-Package bootstrap` Sass: `Install-Package bootstrap.sass`

## Durum

[![Derleme Durumu](https://img.shields.io/github/actions/workflow/status/twbs/bootstrap/js.yml?branch=main&label=JS%20Tests&logo=github)](https://github.com/twbs/bootstrap/actions/workflows/js.yml?query=workflow%3AJS+branch%3Amain)
[![npm sürümü](https://img.shields.io/npm/v/bootstrap?logo=npm&logoColor=fff)](https://www.npmjs.com/package/bootstrap)
[![Gem sürümü](https://img.shields.io/gem/v/bootstrap?logo=rubygems&logoColor=fff)](https://rubygems.org/gems/bootstrap)
[![Meteor Atmosphere](https://img.shields.io/badge/meteor-twbs%3Abootstrap-blue?logo=meteor&logoColor=fff)](https://atmospherejs.com/twbs/bootstrap)
[![Packagist Ön Sürüm](https://img.shields.io/packagist/vpre/twbs/bootstrap?logo=packagist&logoColor=fff)](https://packagist.org/packages/twbs/bootstrap)
[![NuGet](https://img.shields.io/nuget/vpre/bootstrap?logo=nuget&logoColor=fff)](https://www.nuget.org/packages/bootstrap/absoluteLatest)
[![Kapsam Durumu](https://img.shields.io/coveralls/github/twbs/bootstrap/main?logo=coveralls&logoColor=fff)](https://coveralls.io/github/twbs/bootstrap?branch=main)
[![CSS gzip boyutu](https://img.badgesize.io/twbs/bootstrap/main/dist/css/bootstrap.min.css?compression=gzip&label=CSS%20gzip%20boyutu)](https://github.com/twbs/bootstrap/blob/main/dist/css/bootstrap.min.css)
[![CSS Brotli boyutu](https://img.badgesize.io/twbs/bootstrap/main/dist/css/bootstrap.min.css?compression=brotli&label=CSS%20Brotli%20boyutu)](https://github.com/twbs/bootstrap/blob/main/dist/css/bootstrap.min.css)
[![JS gzip boyutu](https://img.badgesize.io/twbs/bootstrap/main/dist/js/bootstrap.min.js?compression=gzip&label=JS%20gzip%20boyutu)](https://github.com/twbs/bootstrap/blob/main/dist/js/bootstrap.min.js)
[![JS Brotli boyutu](https://img.badgesize.io/twbs/bootstrap/main/dist/js/bootstrap.min.js?compression=brotli&label=JS%20Brotli%20boyutu)](https://github.com/twbs/bootstrap/blob/main/dist/js/bootstrap.min.js)
[![Open Collective Destekçileri](https://img.shields.io/opencollective/backers/bootstrap?logo=opencollective&logoColor=fff)](#backers)
[![Open Collective Sponsorları](https://img.shields.io/opencollective/sponsors/bootstrap?logo=opencollective&logoColor=fff)](#sponsors)

## Neler Dahil?

İndirilen dosyanın içinde aşağıdaki dizinler ve dosyalar bulunur. ortak varlıklarını mantıklı bir şekilde gruplandırarak, derlenmiş ve küçültülmüş sürümleri sağlar.

<details>
    <summary>İndirme İçeriği</summary>

```text
bootstrap/
├── css/
│   ├── bootstrap-grid.css
│   ├── bootstrap-grid.css.map
│   ├── bootstrap-grid.min.css
│   ├── bootstrap-grid.min.css.map
│   ├── bootstrap-grid.rtl.css
│   ├── bootstrap-grid.rtl.css.map
│   ├── bootstrap-grid.rtl.min.css
│   ├── bootstrap-grid.rtl.min.css.map
│   ├── bootstrap-reboot.css
│   ├── bootstrap-reboot.css.map
│   ├── bootstrap-reboot.min.css
│   ├── bootstrap-reboot.min.css.map
│   ├── bootstrap-reboot.rtl.css
│   ├── bootstrap-reboot.rtl.css.map
│   ├── bootstrap-reboot.rtl.min.css
│   ├── bootstrap-reboot.rtl.min.css.map
│   ├── bootstrap-utilities.css
│   ├── bootstrap-utilities.css.map
│   ├── bootstrap-utilities.min.css
│   ├── bootstrap-utilities.min.css.map
│   ├── bootstrap-utilities.rtl.css
│   ├── bootstrap-utilities.rtl.css.map
│   ├── bootstrap-utilities.rtl.min.css
│   ├── bootstrap-utilities.rtl.min.css.map
│   ├── bootstrap.css
│   ├── bootstrap.css.map
│   ├── bootstrap.min.css
│   ├── bootstrap.min.css.map
│   ├── bootstrap.rtl.css
│   ├── bootstrap.rtl.css.map
│   ├── bootstrap.rtl.min.css
│   └── bootstrap.rtl.min.css.map
└── js/
    ├── bootstrap.bundle.js
    ├── bootstrap.bundle.js.map
    ├── bootstrap.bundle.min.js
    ├── bootstrap.bundle.min.js.map
    ├── bootstrap.esm.js
    ├── bootstrap.esm.js.map
    ├── bootstrap.esm.min.js
    ├── bootstrap.esm.min.js.map
    ├── bootstrap.js
    ├── bootstrap.js.map
    ├── bootstrap.min.js
    └── bootstrap.min.js.map
```

</details>

Derlenmiş CSS ve JS (`bootstrap.*`) dosyalarının yanı sıra, küçültülmüş (minified) CSS ve JS (`bootstrap.min.*`) sürümlerini de sağlıyoruz. [Kaynak haritaları](https://web.dev/articles/source-maps) (`bootstrap.*.map`), belirli tarayıcıların geliştirici araçlarıyla kullanılabilir. Birleştirilmiş JS dosyaları (`bootstrap.bundle.js` ve küçültülmüş `bootstrap.bundle.min.js`), [Popper](https://popper.js.org/docs/v2/) içermektedir.

## Hata ve Özellik Talepleri

Bir hata mı buldunuz ya da yeni bir özellik mi istiyorsunuz? Lütfen önce [sorun yönergelerini](https://github.com/twbs/bootstrap/blob/main/.github/CONTRIBUTING.md#using-the-issue-tracker) okuyun ve mevcut ya da kapatılmış sorunları arayın. Eğer probleminiz veya fikriniz henüz ele alınmadıysa, [yeni bir sorun açın](https://github.com/twbs/bootstrap/issues/new/choose).

## Dokümantasyon

Bootstrap'ın dokümantasyonu, bu depoda kök dizinde bulunur, [Hugo](https://gohugo.io/) ile oluşturulmuştur ve GitHub Pages üzerinden <https://getbootstrap.com/> adresinde barındırılmaktadır. Dokümantasyon ayrıca yerel olarak da çalıştırılabilir.

Dokümantasyon araması, [Algolia'nın DocSearch](https://docsearch.algolia.com/) hizmetiyle sağlanmaktadır.

### Dokümantasyonu Yerel Olarak Çalıştırma

1. Node.js bağımlılıklarını (Hugo dahil) yüklemek için `npm install` komutunu çalıştırın.
2. Dağıtılmış CSS ve JavaScript dosyalarını ve dokümantasyon varlıklarını yeniden oluşturmak için `npm run test` (veya belirli bir npm komut dosyası) çalıştırın.
3. Kök `/bootstrap` dizininden, komut satırında `npm run docs-serve` komutunu çalıştırın.
4. Tarayıcınızda `http://localhost:9001/` adresini açın ve işte bu kadar.

Hugo kullanımı hakkında daha fazla bilgi almak için [dokümantasyonunu](https://gohugo.io/documentation/) okuyabilirsiniz.

### Önceki Sürümler için Dokümantasyon

Tüm önceki sürümlerin dokümantasyonunu <https://getbootstrap.com/docs/versions/> adresinde bulabilirsiniz.

[Önceki sürümler](https://github.com/twbs/bootstrap/releases) ve ilgili dokümantasyonları da indirilebilir durumdadır.

## Katkıda Bulunma

Lütfen [katkı yönergelerimizi](https://github.com/twbs/bootstrap/blob/main/.github/CONTRIBUTING.md) okuyun. Bu belgede, sorun açma prosedürleri, kodlama standartları ve geliştirme notları yer almaktadır.

Ayrıca, gönderdiğiniz değişikliklerde JavaScript yamaları veya özellikler bulunuyorsa, [ilgili birim testlerini](https://github.com/twbs/bootstrap/tree/main/js/tests) eklemeniz gerekmektedir. Tüm HTML ve CSS kodları, [Mark Otto](https://github.com/mdo) tarafından yönetilen [Kod Kılavuzu](https://github.com/mdo/code-guide) ile uyumlu olmalıdır.

Düzenleyici tercihleri, yaygın metin düzenleyicilerde kolay kullanım için [editor config](https://github.com/twbs/bootstrap/blob/main/.editorconfig) dosyasında belirtilmiştir. Daha fazla bilgi edinmek ve eklentileri indirmek için <https://editorconfig.org/> adresini ziyaret edebilirsiniz.

## Topluluk

Bootstrap'ın gelişimi hakkında güncellemeler alın ve proje bakımcıları ile topluluk üyeleriyle iletişim kurun.

- [@getbootstrap Twitter hesabını](https://twitter.com/getbootstrap) takip edin.
- [Resmi Bootstrap Blogunu](https://blog.getbootstrap.com/) okuyun ve abone olun.
- Sorular sorun ve [GitHub Tartışmalarımızı](https://github.com/twbs/bootstrap/discussions) keşfedin.
- [Topluluk Discord sunucusunda](https://discord.gg/bZUvakRU3M) veya [Bootstrap subredditinde](https://www.reddit.com/r/bootstrap/) tartışmalara katılın, sorular sorun ve daha fazlasını yapın.
- IRC'de diğer Bootstrap kullanıcılarıyla sohbet edin. `irc.libera.chat` sunucusunda `#bootstrap` kanalında bulunabilirsiniz.
- Stack Overflow'da [`bootstrap-5`](https://stackoverflow.com/questions/tagged/bootstrap-5) etiketi ile yardım alabilirsiniz.
- Geliştiriciler, Bootstrap'in işlevselliğini değiştiren veya genişleten paketlerini [npm](https://www.npmjs.com/browse/keyword/bootstrap) gibi platformlarda dağıtırken `bootstrap` anahtar kelimesini kullanmalıdır.

## Sürümleme

Yayın döngümüzü şeffaf hale getirmek ve geriye dönük uyumluluğu korumak amacıyla, Bootstrap [Anlamsal Sürümleme kurallarına](https://semver.org/) uygun olarak sürdürülmektedir. Bazen hatalar yapabiliriz, ancak mümkün olduğunca bu kurallara bağlı kalırız.

Her sürümün değişiklik günlüğü için [GitHub projemizin Sürümler bölümüne](https://github.com/twbs/bootstrap/releases) göz atabilirsiniz. Her sürümde yapılan en dikkat çekici değişikliklerin özetlerini içeren duyuru yazıları [resmi Bootstrap blogunda](https://blog.getbootstrap.com/) yayınlanmaktadır.

## Geliştiriciler

**Mark Otto**

- <https://twitter.com/mdo>
- <https://github.com/mdo>

**Jacob Thornton**

- <https://twitter.com/fat>
- <https://github.com/fat>

## Teşekkürler

<a href="https://www.browserstack.com/">
  <img src="https://live.browserstack.com/images/opensource/browserstack-logo.svg" alt="BrowserStack" width="192" height="42">
</a>

[BrowserStack](https://www.browserstack.com/) ekibine, gerçek tarayıcılarda test yapmamıza olanak sağlayan altyapıyı sağladıkları için teşekkür ederiz!

<a href="https://www.netlify.com/">
  <img src="https://www.netlify.com/v3/img/components/full-logo-light.svg" alt="Netlify" width="147" height="40">
</a>

[Netlify](https://www.netlify.com/) ekibine, bize Deploy Previews hizmeti sağladıkları için teşekkür ederiz!

## Sponsorlar

Bu projeyi desteklemek için sponsor olun. Logonuz burada, web sitenize yönlendiren bir bağlantı ile gösterilecektir. [[Sponsor Olun](https://opencollective.com/bootstrap#sponsor)]

[![OC sponsor 0](https://opencollective.com/bootstrap/sponsor/0/avatar.svg)](https://opencollective.com/bootstrap/sponsor/0/website)
[![OC sponsor 1](https://opencollective.com/bootstrap/sponsor/1/avatar.svg)](https://opencollective.com/bootstrap/sponsor/1/website)
[![OC sponsor 2](https://opencollective.com/bootstrap/sponsor/2/avatar.svg)](https://opencollective.com/bootstrap/sponsor/2/website)
[![OC sponsor 3](https://opencollective.com/bootstrap/sponsor/3/avatar.svg)](https://opencollective.com/bootstrap/sponsor/3/website)
[![OC sponsor 4](https://opencollective.com/bootstrap/sponsor/4/avatar.svg)](https://opencollective.com/bootstrap/sponsor/4/website)
[![OC sponsor 5](https://opencollective.com/bootstrap/sponsor/5/avatar.svg)](https://opencollective.com/bootstrap/sponsor/5/website)
[![OC sponsor 6](https://opencollective.com/bootstrap/sponsor/6/avatar.svg)](https://opencollective.com/bootstrap/sponsor/6/website)
[![OC sponsor 7](https://opencollective.com/bootstrap/sponsor/7/avatar.svg)](https://opencollective.com/bootstrap/sponsor/7/website)
[![OC sponsor 8](https://opencollective.com/bootstrap/sponsor/8/avatar.svg)](https://opencollective.com/bootstrap/sponsor/8/website)
[![OC sponsor 9](https://opencollective.com/bootstrap/sponsor/9/avatar.svg)](https://opencollective.com/bootstrap/sponsor/9/website)

## Destekçiler

Tüm destekçilerimize teşekkürler! 🙏 [[Destekçi Olun](https://opencollective.com/bootstrap#backer)]

[![Destekçiler](https://opencollective.com/bootstrap/backers.svg?width=890)](https://opencollective.com/bootstrap#backers)

## Telif Hakkı ve Lisans

Kod ve dokümantasyon telif hakkı 2011-2025 [Bootstrap Yazarlarına](https://github.com/twbs/bootstrap/graphs/contributors) aittir. Kod, [MIT Lisansı](https://github.com/twbs/bootstrap/blob/main/LICENSE) altında yayımlanmıştır. Dokümantasyon ise [Creative Commons](https://creativecommons.org/licenses/by/3.0/) lisansı altında yayımlanmıştır.
