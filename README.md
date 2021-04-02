# Scrape-Kartun
Scrape kartun adalah package untuk mendapatkan data film-film kartun, dalam banyak genre

#### Jika ada masalah di dalam Package, langsung laporkan aja yak :)

## Installasi

Via NPM:
```bash
$ npm install scrape-kartun
```

## Cara Menggunakan

```js
const zahirganteng = require('scrape-kartun');

/*
zahirganteng.jenis-modul.nama-modul(params)
.then(res => console.log(res))
.catch(err => console.log(err))
*/
```

### Example

```js
//Example!
zahirganteng.Scrape.SearchKartun('spongebob')
.then(res => console.log(res))
.catch(err => console.log(err))

zahirganteng.Scrape.Action()
.then(res => console.log(res))
.catch(err => console.log(err))

zahirganteng.Scrape.Adventure()
.then(res => console.log(res))
.catch(err => console.log(err))

zahirganteng.Scrape.Comedy()
.then(res => console.log(res))
.catch(err => console.log(err))

zahirganteng.Scrape.Drama()
.then(res => console.log(res))
.catch(err => console.log(err))

zahirganteng.Scrape.Military()
.then(res => console.log(res))
.catch(err => console.log(err))

zahirganteng.Scrape.Movie()
.then(res => console.log(res))
.catch(err => console.log(err))
```


### Link Packages

https://www.npmjs.com/package/scrape-kartun

### Created By
- Zahirr ( 14 y.o Coders )
