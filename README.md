# VIS Vrljika — Website

Zvanični sajt **Vokalno Instrumentalnog Sastava Vrljika** iz Gornjeg Milanovca.

> *"Amalgamacija gomile žanrova — ponekad sa smislom, ali češće bez ikakvog zdravog razuma."*

## O bendu

VIS Vrljika je bend od **šest dobrih ljudi, ali loših muzičara** koji samo žele da se dobro zabave i svoj entuzijazam prenesu na narod.

- 📍 Gornji Milanovac, Srbija
- 📞 Petar: 064/0260771
- 📧 visvrljika@gmail.com
- 📷 [@visvrljika](https://instagram.com/visvrljika) na Instagramu
- 📘 [Vokalno Instrumentalni Sastav Vrljika](https://facebook.com/VokalnoInstrumentalniSastavVrljika) na Facebooku
- 🎵 [bend.rs/oglas/vrljika](https://bend.rs/oglas/vrljika/)

---

## Verzije sajta

| Verzija | URL | Estetika | Opis |
|---------|-----|----------|------|
| **v2** (aktivna) | `/` | Scam / Maximalist / Frutiger Aero / 2000s | Pop-up-ovi na svaki 5. klik, lažni virus scan, scam estetika, 8 vrsta pop-up prozora, 5 stranica |
| v1 | `/v1/` | Web Brutalism / 2000s / Anti-design | Originalni brutalistički one-pager sa `<table>` layout-om |
| v3 | `/v3/` | Conspiracy / Classified Documents / Area 51 | Eksperimentalna verzija — dosijei, zavere, NLO-i |

---

## Dizajn filozofija

Detaljne smernice su u [`design.md`](design.md). Estetika crpi iz:
- Web brutalizma (sirove strukture, sistemski fontovi, oštre senke)
- Sajtova iz 2000-ih (Comic Sans, `<marquee>`, tiled pozadine, 88×31 badgevi)
- Frutiger Aero (sjajni skeuomorfni dugmići, staklene površine)
- Scam sajtova (lažni pop-upovi, "ČESTITAMO!", countdown tajmeri)
- Anti-design / trash design (namerno ružno, pikselizovano, JPEG artefakti)

---

## Struktura projekta

```
/
├── index.html          ← v2 — glavna stranica (scam maximalist)
├── about.html          ← v2 — o bendu
├── music.html          ← v2 — diskografija / cover art
├── contact.html        ← v2 — kontakt forma + lažna payment forma
├── razonoda.html       ← v2 — 18+ retro humor
├── v1/
│   └── index.html      ← v1 — brutalist one-pager
├── v3/
│   ├── index.html      ← v3 — conspiracy dosijei
│   ├── about.html      ← v3 — lični dosijei
│   ├── music.html      ← v3 — presretnuti signali
│   ├── contact.html    ← v3 — sigurni kanal
│   └── razonoda.html   ← v3 — zona 69
├── Images/covers/      ← cover art slike (7 komada)
├── logo/               ← logo u SVG, PNG, AI formatima
├── design.md           ← dizajn smernice
├── versions.txt        ← spisak verzija sa linkovima
├── .nojekyll           ← onemogućava Jekyll obradu na GitHub Pages
└── README.md           ← ovaj fajl
```

---

## Hosting

Hostovano na **GitHub Pages**:  
🔗 [koturkotur.github.io/vrljika-website-test](https://koturkotur.github.io/vrljika-website-test/)

Sajt je statički — sav HTML, CSS i JS je inline u svakom fajlu. Nema build procesa, nema framework-a, nema zavisnosti. Otvori bilo koji `.html` fajl direktno u browseru.

---

## Lokalni razvoj

```bash
# Kloniraj
git clone git@github.com:koturkotur/vrljika-website-test.git

# Otvori u browseru — to je to, nema npm install
open index.html
```
