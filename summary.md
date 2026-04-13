# VIP Úklidový Servis — Shrnutí projektu

## Datum: 2026-04-13

## Zdroj dat
Web www.vip-uklidovyservis.com — přečteno: hlavní stránka, generální úklid, ceník, rezervace, upozornění, recenze, nabídka práce, firmy.cz profil.

## Firmy data
- **Název:** VIP cleaning service s.r.o.
- **IČO:** 14135574
- **Adresa:** Velehradská třída 1206, 686 01 Uherské Hradiště (OD Centrum, 2. patro)
- **Telefon:** +420 776 636 636
- **Email:** poptavkauklid@gmail.com
- **Web:** www.vip-uklidovyservis.com
- **Hodnocení:** 98.2/100 (99 recenzí na Firmy.cz)
- **Pracovní doba:** Po–Pá 8:30–15:30

## Služby
1. Klasický úklid domácnosti (pravidelný / jednorázový)
2. Generální úklid (hloubkový, centimetr po centimetru, předávací protokol)
3. Mytí oken (klasická, výlohová, francouzská)
4. Čištění sedaček, koberců a čalounění

## Ceník info
- Storno poplatek: 1 000 Kč (méně než 48h před termínem)
- Ekologické prostředky: +100 Kč/hod
- Nejsou plátci DPH (osobní; firemní úklid VIP firemní úklid s.r.o. — plátce DPH 21 %)
- Individuální ceník, neveřejný

## Design rozhodnutí

### Fonty
- **Nadpisy:** Syne 400–800 — moderní, geometrická, výrazná, komunikuje profesionalitu
- **Text:** Inter 400–600 — maximální čitelnost, neutrální, osvědčená pro webový obsah

### Barevná paleta
- `#0F2A4A` — Deep Navy (důvěra, profesionalita)
- `#06B6D4` — Electric Teal (čistota, svěžest, čisticí asociace)
- `#0891B2` — Teal Dark (hover stav)
- `#E0F7FA` — Teal Light (jemné pozadí)
- `#F0F7FF` — Soft Blue-White (sekční pozadí)
- `#1E293B` — Slate (tělo textu)
- `#64748B` — Muted Slate (doplňkový text)

### Sekce webu
1. Navigation (sticky, scrolled state, hamburger mobile)
2. Hero (gradient navy, badge s hodnocením, service chips karta)
3. Why Us (4 karty — hodnocení, protokol, prostředky, diskrétnost)
4. Služby (4 karty se seznamy)
5. Jak to funguje (4 kroky na navy pozadí)
6. Generální úklid detail (pokoje + tabulka pracovníků)
7. Ceník (3 karty + info o podmínkách)
8. Recenze (98.2/100 + 3 karty s recenzemi)
9. Kontakt (info + poptávkový formulář)
10. Footer (logo, sociální sítě, odkaz sloupce)

### Animace
- Fade-up pomocí IntersectionObserver
- Hover efekty na kartách (translateY, border reveal)
- Nav přechod při scrollu

### Watermark
- Vrstva s position: fixed, pointer-events: none, z-index: 9999
- Grid s ~200 opakováními textu "Demoverze – Tomáš Smolík"
- Rotace -30°, opacity 0.08 — viditelný ale nerušivý

### Responsivita
- 5 breakpointů: 1024px, 768px, 640px, 428px, 375px, 320px
- Hamburger menu na ≤768px
- Všechny buttony min-height 48px
- Font-size nikde pod 16px
- overflow-x: hidden na html i body

## GitHub
- Repo: vip-uklidovyservis
- GitHub username: supercigan
- Branch: master
