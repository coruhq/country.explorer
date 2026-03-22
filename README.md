# 🌍 country.explorer

> Explore every country on Earth — flags, capitals, currencies, populations and more. Powered by a free public API, zero dependencies.

![built with](https://img.shields.io/badge/built%20with-vanilla%20JS-f7df1e?style=flat-square&logo=javascript)
![api](https://img.shields.io/badge/API-REST%20Countries-4ade80?style=flat-square)
![dependencies](https://img.shields.io/badge/dependencies-zero-43e0a0?style=flat-square)
![license](https://img.shields.io/badge/license-MIT-6c63ff?style=flat-square)

---

## What is this?

`country.explorer` fetches live data for all 195 countries from the free [REST Countries API](https://restcountries.com) and displays them as interactive cards. Search, filter by region, sort by population or area, and save your favorites — all in a single HTML file with no build tools.

---

## Features

| Feature | Details |
|---|---|
| 🌐 Live API data | Fetches from `restcountries.com` — no API key needed |
| 🔍 Search | Filter by country name, capital city, or region |
| 🗺️ Region filter | Africa, Americas, Asia, Europe, Oceania |
| 📊 Sort | By name, population, or area |
| ★ Favorites | Save countries — persisted in `localStorage` |
| 🃏 Detail modal | Click any card for full info (currencies, languages, timezones…) |
| 🌗 Dark mode | Automatic via `prefers-color-scheme` |
| 🌐 EN / TR | Full English and Turkish language support |
| 📱 Responsive | Works on mobile and desktop |

---

## Data shown per country

- Flag emoji
- Name (common + native)
- Capital city
- Region & subregion
- Population
- Area (km²)
- Currency (name + symbol)
- Official languages
- Independent status
- Landlocked status
- Timezones

---

## Getting Started

No installation, no npm, no build step.

```bash
git clone https://github.com/coruhq/country.explorer.git
open index.html
```

Deploy to GitHub Pages:

1. Push to a GitHub repository
2. **Settings → Pages → Source: main branch / root**
3. Live at `https://coruhq.github.io/country.explorer`

---

## API

Uses the free [REST Countries v3.1 API](https://restcountries.com) — no authentication, no rate limits for normal usage.

```
GET https://restcountries.com/v3.1/all?fields=name,flag,cca3,capital,region,...
```

---

## Project Structure

```
country.explorer/
└── index.html   ← everything in one file
```

---

## License

MIT — use it, fork it, make it yours.

---
---

# 🌍 country.explorer — Türkçe

> Dünyanın her ülkesini keşfet — bayraklar, başkentler, para birimleri, nüfuslar ve daha fazlası. Ücretsiz bir API ile çalışır, sıfır bağımlılık.

---

## Bu nedir?

`country.explorer`, ücretsiz [REST Countries API](https://restcountries.com) üzerinden 195 ülkenin canlı verisini çeker ve etkileşimli kartlar olarak gösterir. Tek bir HTML dosyasında arama, bölgeye göre filtreleme, sıralama ve favorilere kaydetme — hiç build aracı gerekmez.

---

## Özellikler

| Özellik | Detay |
|---|---|
| 🌐 Canlı API verisi | `restcountries.com`'dan çeker — API anahtarı gerekmez |
| 🔍 Arama | Ülke adı, başkent veya bölgeye göre filtrele |
| 🗺️ Bölge filtresi | Afrika, Amerika, Asya, Avrupa, Okyanusya |
| 📊 Sıralama | Ada, nüfusa veya alana göre |
| ★ Favoriler | Ülkeleri kaydet — `localStorage`'da saklanır |
| 🃏 Detay modal | Karta tıklayınca tam bilgi (para birimi, diller, saat dilimleri…) |
| 🌗 Karanlık mod | `prefers-color-scheme` ile otomatik |
| 🌐 EN / TR | Tam İngilizce ve Türkçe dil desteği |
| 📱 Responsive | Mobil ve masaüstünde çalışır |

---

## Ülke başına gösterilen veriler

- Bayrak emojisi
- Ad (yaygın + yerel)
- Başkent
- Bölge ve alt bölge
- Nüfus
- Alan (km²)
- Para birimi (ad + sembol)
- Resmi diller
- Bağımsızlık durumu
- Denize çıkış durumu
- Saat dilimleri

---

## Kurulum

Kurulum yok, npm yok, build adımı yok.

```bash
git clone https://github.com/coruhq/country.explorer.git
open index.html
```

GitHub Pages'e yayınlamak için:

1. GitHub reposuna push'la
2. **Settings → Pages → Source: main branch / root**
3. `https://coruhq.github.io/country.explorer` adresinde canlıya geç

---

## API

Ücretsiz [REST Countries v3.1 API](https://restcountries.com) kullanılır — kimlik doğrulama yok, normal kullanımda rate limit yok.

---

## Lisans

MIT — kullan, fork'la, kendin yap.

---

<p align="center">Made with ✦ and vanilla JS &nbsp;|&nbsp; Vanilla JS ile yapıldı ✦</p>
