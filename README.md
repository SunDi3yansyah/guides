# Panduan Ruby on Rails Indonesia

[![Country](https://img.shields.io/badge/country-indonesia-blue.svg)](https://en.wikipedia.org/wiki/Indonesia)
[![Build Status](https://travis-ci.org/rails-id/guides.svg)](https://travis-ci.org/rails-id/guides)

Repositori ini menghasilkan apa yang ada di situs web [guides.rails.id](http://guides.rails.id).

## Petunjuk umum
##### Tidak lupa untuk bundle sumber Gemfile:
```
$ bundle install
```

##### Mengenerate hasil sumber:
```
$ rake guides:generate:html
```

##### Jalankan output dengan web server:
```
$ ruby -run -e httpd output -p 4000
```

##### Selengkapnya kalian bisa melihat di rake:
```
$ rake
```

### Versi

##### File yang selalu di terjemahkan
- Semua file di direktori `source` yang berektensi Markdown (.md) dan file `documents.yaml`

##### Branch
- **master**

	Jangan mensinkronkan semua panduan di branch master, karena branch master akan selalu berubah tergantung rilis dari Rails

- **5-2-stable**

	Sedang dikerjakan untuk panduan Rails versi ini

### Salinan terakhir

##### master
- Repositori: https://github.com/rails/rails/commits/master/guides
- SHA1: `0bc62b9c27b562986409851789c302be0ac7379f`

##### 5-2-stable
- Repositori: https://github.com/rails/rails/commits/5-2-stable/guides
- SHA1: `bd24ef67ff2cb2d378371db25bf65e6afe19cebb`

## Sumber konten

Secara umum konten panduan Ruby on Rails berada didirektori [source](source), lakukan perubahan pada panduan konten tersebut untuk berkontrbusi.

## Kontribusi

[![Contributors](https://img.shields.io/github/contributors/rails-id/guides.svg)](https://github.com/rails-id/guides/graphs/contributors)

Bagi member organisasi Ruby on Rails Indonesia bisa kontribusi langsung di remote `git@github.com:rails-id/guides.git`

```
$ git clone git@github.com:rails-id/guides.git
```

Dan bagi yang non member Ruby on Rails Indonesia diharuskan untuk fork repositori, dan melakukan pull request

```
$ git clone git@github.com:$USERNAME/$NAME_OF_REPOSITORY.git
```

Selengkapnya bisa dilihat di [Kontribusi](CONTRIBUTING.md) dan diharapkan untuk mengikuti [Kode Etik](CODE_OF_CONDUCT.md).

## Referensi
- [github.com/rails/rails/tree/master/guides](https://github.com/rails/rails/tree/master/guides)

## Lisensi

[![License](https://img.shields.io/github/license/rails-id/guides.svg)](LICENSE)

Ruby on Rails Indonesia dirilis di bawah [Lisensi MIT](https://opensource.org/licenses/MIT).
