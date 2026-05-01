# 🐾 Kissapeli

Yksinkertainen selainpeli kissalle: ruudulle ilmestyy värikkäitä palloja, jotka liikkuvat ja kimpoilevat reunoista vaihtelevalla nopeudella. Kun kissa tassuttaa palloa, se poksahtaa, taustaväri vaihtuu, kuuluu ääni ja pisteet kasvavat.

## Pelaa

👉 **[Avaa peli](https://isokiho.github.io/kissapeli/)**

Lisää kotinäytölle (iPadilla):
1. Avaa peli Safarissa
2. Paina jakonappia → **Lisää Koti-valikkoon**
3. Käynnistä kotinäytöltä → aukeaa fullscreeniin ilman selaimen palkkeja

## Ominaisuudet

- Yksi pallo kerrallaan, kimpoilee reunoista satunnaisella nopeudella ja suunnalla
- Tassutus → pallo poksahtaa, tausta vaihtaa väriä, ääni soi, pisteet +1
- Viisi erilaista satunnaista ääntä (meow, boop, chirp, pop, twinkle)
- Sparkle-efekti palkinnoksi (✨ ⭐ 💫 🌟 🎉 🐾)
- Fullscreen-tila Aloita-painikkeesta
- ✕-nappi oikeassa yläkulmassa lopettaa pelin

## Tekninen toteutus

Yksi staattinen HTML-tiedosto. Ei riippuvuuksia, ei build-vaihetta.

- Vanilla JS + CSS
- Web Audio API äänille (oskillaattorigeneroidut, ei ääniresursseja)
- Fullscreen API + iOS PWA -metatagit
- Pointer Events tassuhavaintoon

## Käyttöönotto GitHub Pagesiin

1. Pushaa `index.html` repoon
2. Repon asetukset → Pages → Source: `main` branch, root
3. Sivusto on osoitteessa `https://<käyttäjä>.github.io/<repo>/`

## Lisenssi

MIT
