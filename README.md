# Guttas Vertshus – Event House and Café

![Guttas Vertshus Banner](https://via.placeholder.com/800x200/6e7f80/ffffff?text=GUTTAS+VERTSHUS)

[![Norsk](https://img.shields.io/badge/🇳🇴-Norsk-blue)](./README.md)
[![English](https://img.shields.io/badge/🇬🇧-English-blue)](./README_EN.md)

---

## 📑 Innholdsfortegnelse

- [Prosjektoversikt](#prosjektoversikt)
- [Funksjoner](#funksjoner)
- [Teknologistakk](#teknologistakk)
- [Sider](#sider)
- [Universell Tilgjengelighet](#universell-tilgjengelighet)
- [Testing og Validering](#testing-og-validering)
- [Mappestruktur](#mappestruktur)
- [Teammedlemmer](#teammedlemmer)
- [Bildekrediteringer](#bildekrediteringer)
- [Kontaktinformasjon](#kontaktinformasjon)
- [Nettleserkompatibilitet](#nettleserkompatibilitet)
- [Fremtidige Forbedringer](#fremtidige-forbedringer)
- [Lisens](#lisens)

---

## 📋 Prosjektoversikt

Dette prosjektet er et responsivt nettsted for **Guttas Vertshus**, et arrangementssted og kafé i Finnsnes, Norge. Nettstedet fungerer som en digital plattform hvor kunder kan utforske stedets tjenester, se menyen og sende forespørsler for bookinger.

---

## 🌟 Funksjoner

- **Responsivt Design**: Optimalisert for stasjonære, nettbrett og mobile enheter  
- **Bookingsystem**: Enkel bookingskjema for arrangementforespørsler  
- **Menyvisning**: Presentasjon av kaféens tilbud med bilder og detaljer  
- **Stedsinformasjon**: Interaktivt kart og kontaktinformasjon  
- **Universell Tilgjengelighet**: Bygget med prinsipper for universell utforming

---

## 🧰 Teknologistakk

- **HTML5** – Semantisk markup for økt tilgjengelighet  
- **CSS3** – Responsivt design ved hjelp av media queries  
- **JavaScript** – Interaktive elementer og funksjonalitet

---

## 📱 Sider

1. **Velkommen (index.html)** – Introduksjon til stedet  
2. **Booking (Booking.html)** – Booking-skjema og informasjon om lokalet  
3. **Meny (meny.html)** – Oversikt over mat- og drikketilbud  
4. **Informasjon (aktuellinformasjon.html)** – Nyheter og oppdateringer  
5. **Tilgjengelighet (tilgjenglighet.html)** – Informasjon om tilgjengelighetsfunksjoner

---

## ♿ Universell Tilgjengelighet

Nettstedet er utviklet med universell utforming for økt tilgjengelighet:
- Semantisk HTML for optimal støtte til skjermlesere
- Riktige kontrastforhold for lesbarhet
- Tastaturnavigasjon med `tabindex`-attributter
- Alternativ tekst for alle bilder
- Responsivt design for alle enheter
- Klar og lesbar typografi med passende skriftstørrelser

---

## 🔍 Testing og Validering

Nettstedet er testet med [WAVE – Web Accessibility Evaluation Tool](https://wave.webaim.org/) for å sikre overholdelse av tilgjengelighetsstandarder. Alle større feil er utbedret; kun noen mindre varsler gjenstår.

---

## 📁 Mappestruktur

```bash
/
├── CSS/
│   ├── index.css         # Grunnleggende layout og stiler
│   └── Pages.css         # Sidetilpassede stiler
├── bilder/               # Hovedbilder
├── nyeBilder/            # Ekstra bildebibliotek
├── index.html            # Forside
├── Booking.html          # Bookingside
├── meny.html             # Menyside
├── aktuellinformasjon.html  # Informasjon/nyhetsside
├── tilgjenglighet.html      # Tilgjengelighetsside
├── README_NO.md          # Prosjektdokumentasjon (Norsk)
└── README_EN.md          # Project documentation (English)
