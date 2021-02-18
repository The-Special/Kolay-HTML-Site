# Basic Website Starter

HTML/CSS/JS Website.

## About

Bu dosya temel bir HTML sitesi oluşturmanıza yardım eder.

Bu dosyada bir site oluşturmak için gereken dosyaları mevcuttur.

1. [index.html](index.html) bu dosyaya "HTML" kodlarınızı yazmalısınız.
2. [styles.css](styles.css) bu dosyaya "CSS" kodlarınızı yazmalısınız.
3. [scripts.js](scripts.js) bu dosyaya "JavaScript" kodlarınızı yazmalısınız.

- Bu dosya da favicon.ico da bulunur. Favicon sizin 16*16 boyutlarrına sahip sitenizin harf , resim ve simge şeklinde tasarlanan web sitesinin tanınmasına yardımcı olan sembollerdir.

- Favicon tasarımınızı en güzel ve etkileyici şekilde oluşturarak web sitenizi daha güzel ve daha zengin hale getirebilirsiniz.

`Favicon'un kullanım örneği:

<link rel= “shortcut icon” href=” /favicon.ico” type=” image/x-icon” />

Bu şekilde faviconunuzu kullanabilirsiniz.`

## Why

### The HTML

- `<!DOCTYPE html>` Tarayıcıya aşağıdakilerin html kodu olduğunu bildirmek için bir HTML dosyasının başlangıcında gerekir.

- `<meta charset=utf-8>` dosyanın karakter kodlamasını ayarlamak için gereklidir, Bu özellik sayesinde özel karakterleri daha rahat kullanabiliriz. 

- `<meta name=viewport content="width=device-width, initial-scale=1">` Bu özellik tamamen gerekli olan bir şey değildir, fakat tarayıcıların mobil cihazlarda varsayılan görünümünü ayarlamak için kullanılan yaygın bir yoldur. Bu özellik küçük bir cihaza sığacak şekilde ayarlanmış bir masaüstü sitesi gibi davranmak yerine bu siteyi normal hale getirir ve normal boyutuyla bize aktarır.

- Bütün HTML dosyalarının bir başlığa ihtiyacı vardır. `<title>`

- Dosyaya JavaScript ve CSS dosyası ekledim ve bunlar siz kodlarınızı eklediğinizde düzgün çalışacaktır.

 ## The CSS

- `box-sizing: border-box;` öğelerin boyutunu hesaplamak içi kulllanılır ve size daha güzel bir boyut ayarlar.

- `text-rendering`, `-webkit-font-smoothing`, `-moz-osx-font-smoothing`, `font-kerning` Bu özellikler tarayıcılarda daha iyi yazı tipi işlemeyi sağlarr ve bu özellikler yazı tiplerinin farklı tarayıcılarda ve işletim sistemlerinde tutarlı görünmesine yardım eder.

- `-webkit-text-size-adjust: 100%;` Bu özellik sitenizin mobil cihazdan görüntülendiğinde dikey ve yatay mod arasında döndürülürken görüntülenen sayfanın en ve boy oranını değiştirmeden ekranın genişliğini doldurmak için ve sayfanın yakınlaştırılması için kullanılır.