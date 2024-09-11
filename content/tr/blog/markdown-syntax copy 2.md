---
author: "Kadir Talha AK"
title: "Markdown Söz Dizimi Kılavuzu"
description: "HTML öğeleri için temel Markdown söz dizimi ve biçimlendirmeyi sergileyen örnek bir makale."
tags: ["markdown", "css", "html"]
date: 2024-09-01
thumbnail: https://e1.pxfuel.com/desktop-wallpaper/621/831/desktop-wallpaper-html-css-javascript-transparent-html-css.jpg
---

Bu makale, Hugo içerik dosyalarında kullanılabilecek temel Markdown söz diziminin bir örneğini sunar, ayrıca Hugo temasında temel HTML öğelerinin CSS ile süslenip süslenmediğini gösterir.

<!--more-->

## Başlıklar

Aşağıdaki HTML `<h1>`—`<h6>` öğeleri, altı farklı başlık seviyesini temsil eder. `<h1>` en yüksek seviye iken `<h6>` en düşük seviyeyi ifade eder.

# H1

## H2

### H3

#### H4

##### H5

###### H6

## Paragraf

Xerum, quo qui aut unt expliquam qui dolut labo. Aque venitatiusda cum, voluptionse latur sitiae dolessi aut parist aut dollo enim qui voluptate ma dolestendit peritin re plis aut quas inctum laceat est volestemque commosa as cus endigna tectur, offic to cor sequas etum rerum idem sintibus eiur? Quianimin porecus evelectur, cum que nis nust voloribus ratem aut omnimi, sitatur? Quiatem. Nam, omnis sum am facea corem alique molestrunt et eos evelece arcillit ut aut eos eos nus, sin conecerem erum fuga. Ri oditatquam, ad quibus unda veliamenimin cusam et facea ipsamus es exerum sitate dolores editium rerore eost, temped molorro ratiae volorro te reribus dolorer sperchicium faceata tiustia prat.

Itatur? Quiatae cullecum rem ent aut odis in re eossequodi nonsequ idebis ne sapicia is sinveli squiatum, core et que aut hariosam ex eat.

## Alıntılar

Alıntı öğesi, başka bir kaynaktan alıntılanan içeriği temsil eder, isteğe bağlı olarak bir `footer` veya `cite` öğesi içinde atıf yapılabilir ve satır içi değişiklikler (notlar ve kısaltmalar) eklenebilir.

#### Atıfsız Alıntı

> Tiam, ad mint andaepu dandae nostion secatur sequo quae.
> **Not**: Alıntı içinde _Markdown sözdizimi_ kullanabilirsiniz.

#### Atıflı Alıntı

> Belleği paylaşarak değil, iletişim kurarak paylaşın.<br>
> — <cite>Rob Pike[^1]</cite>

[^1]: Yukarıdaki alıntı, Rob Pike'ın 18 Kasım 2015'te Gopherfest'teki [konuşmasından](https://www.youtube.com/watch?v=PAAkCSZUG1c) alınmıştır.

## Tablolar

Tablolar, Markdown'ın temel özelliklerinden biri değildir, ancak Hugo'da varsayılan olarak desteklenir.

| İsim  | Yaş  |
| ----- | ---  |
| Bob   | 27   |
| Alice | 23   |

#### Tablolarda Satır İçi Markdown

| İtalik   | Kalın    | Kod    |
| -------- | -------- | ------ |
| _italik_ | **kalın** | `kod`  |

## Kod Blokları

#### Geri tırnaklarla kod bloğu

```html
<!DOCTYPE html>
<html lang="tr">
  <head>
    <meta charset="utf-8" />
    <title>Örnek HTML5 Belgesi</title>
  </head>
  <body>
    <p>Test</p>
  </body>
</html>
```

#### Dört boşlukla girintili kod bloğu

    <!doctype html>
    <html lang="tr">
    <head>
      <meta charset="utf-8">
      <title>Örnek HTML5 Belgesi</title>
    </head>
    <body>
      <p>Test</p>
    </body>
    </html>

#### Hugo'nun dahili vurgulama kısa koduyla kod bloğu

{{< highlight html >}}

<!doctype html>
<html lang="tr">
<head>
  <meta charset="utf-8">
  <title>Örnek HTML5 Belgesi</title>
</head>
<body>
  <p>Test</p>
</body>
</html>

{{< /highlight >}}

## Liste Türleri

#### Sıralı Liste

1. İlk öğe
2. İkinci öğe
3. Üçüncü öğe

#### Sırasız Liste

- Liste öğesi
- Başka bir öğe
- Bir başka öğe daha

#### İç içe liste

- Meyve
  - Elma
  - Portakal
  - Muz
- Süt ürünleri
  - Süt
  - Peynir

## Diğer Öğeler — abbr, sub, sup, kbd, mark

<abbr title="Grafik Değişim Formatı">GIF</abbr> bir bitmap görüntü formatıdır.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Oturumu sonlandırmak için <kbd><kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>Delete</kbd></kbd> tuşlarına basın.

Çoğu <mark>salamander</mark> gece aktiftir ve böcekler, solucanlar ve diğer küçük yaratıklarla beslenir.
```
