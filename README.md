# Baloni Đorđević - Dekoracije & Cvećara

Profesionalni sajt za Baloni Đorđević dekoracije sa balonima i cvećaru. Moderne dekoracije za rođendane, svadbe, punoletstva i sve posebne prilike.

## 🎯 Funkcionalnosti

- **Responsive Design** - Perfektno se prilagođava svim uređajima
- **SEO Optimizovan** - Meta tagovi, strukturirani podaci, sitemap
- **Hamburger Meni** - Elegantna mobilna navigacija
- **Hero Sekcija** - Atraktivna početna sekcija sa pozadinskom slikom
- **Galerija sa Filterima** - Organizovane kategorije radova
- **Kontakt Forma** - Funkcionalana forma za slanje poruka
- **Cvećara Sekcija** - Posebna sekcija za cvetni deo posla
- **Animacije** - Smooth scroll, fade-in efekti, parallax
- **Lightbox Galerija** - Prikaz slika u full screen
- **Back to Top** - Dugme za povratak na vrh
- **Loading Screen** - Elegantno učitavanje stranice

## 📁 Struktura Projekta

```
dekoracije.rs/
│
├── index.html          # Glavni HTML fajl
├── styles.css          # CSS stilovi
├── script.js          # JavaScript funkcionalnost
├── robots.txt         # SEO - instrukcije za crawlere
├── sitemap.xml        # SEO - mapa sajta
└── README.md          # Dokumentacija
```

## 🚀 Pokretanje

1. Preuzmite sve fajlove
2. Otvorite `index.html` u browser-u
3. Sajt je spreman za korišćenje!

## 🎨 Sekcije Sajta

### 1. Hero Sekcija
- Veliki naslov i opis
- Dva glavna dugmeta (Kontakt i Radovi)
- Pozadinska slika sa overlay efektom
- Scroll indicator

### 2. O Nama
- Opis kompanije i usluga
- Tri ključne karakteristike
- Slika kompanije

### 3. Usluge
- 6 različitih tipova usluga
- Ikone i opisi za svaku uslugu
- Hover efekti

### 4. Galerija
- Filter po kategorijama
- Lightbox prikaz slika
- Responsive grid layout

### 5. Cvećara
- Informacije o cvećari
- Lokacija i radno vreme
- Opis usluga cvećare

### 6. Kontakt
- Kontakt informacije
- Funkcionalna forma
- Društvene mreže
- Validacija polja

## 🎯 SEO Optimizacija

- Meta tagovi optimizovani za pretraživače
- Open Graph tagovi za društvene mreže
- Strukturirani podaci (JSON-LD)
- robots.txt i sitemap.xml
- Semantički HTML
- Optimizovane slike
- Brze loading vremena

## 📱 Responsive Design

- **Desktop** (1200px+) - Full layout
- **Tablet** (768px-1199px) - Adjusted grid
- **Mobile** (320px-767px) - Single column, hamburger menu

## 🔧 Prilagođavanje

### Dodavanje Slika
Zamenite placeholder slike sa stvarnim fotografijama:
- Hero pozadina: Dodajte URL u CSS `.hero` sekciji
- Galerija: Zamenite `src` atribute u `.gallery-item img`
- O nama slika: Dodajte pravu sliku u `.about-image img`

### Kontakt Informacije
Ažurirajte u HTML fajlu:
- Telefon broj
- Email adresa
- Adresa cvećare
- Linkovi društvenih mreža

### Boje i Font
Glavni CSS varijabli za lako menjanje:
- `#ff6b6b` - Glavna boja (crvena)
- `#4ecdc4` - Sekundarna boja (tirkizna)
- `#2c3e50` - Tamna boja za tekst
- `'Poppins'` - Glavni font

## 🌟 Dodatne Funkcionalnosti

### JavaScript Funkcionalnosti
- Smooth scroll navigacija
- Mobile hamburger menu
- Gallery lightbox
- Form validation i submission
- Scroll animations
- Back to top button
- Loading screen
- Parallax effects
- Notification system

### CSS Animacije
- Fade-in na scroll
- Hover efekti
- Button transitions
- Gallery filters
- Hero typing effect
- Bounce scroll indicator

## 📞 Kontakt Informacije

**Baloni Đorđević - Dekoracije & Cvećara**
- 📱 Telefon: +381 11 123 4567
- 📧 Email: info@baloni-dekoracije.rs
- 📍 Adresa: Trg Republike 5, Beograd 11000
- 🕒 Radno vreme: Pon-Pet 08:00-20:00

## 🔄 Ažuriranje Sadržaja

### Dodavanje Novih Radova u Galeriju
1. Dodajte novu `.gallery-item` div u HTML
2. Postavite odgovarajući `data-category` atribut
3. Dodajte sliku i opis

### Dodavanje Nove Usluge
1. Dodajte novu `.service-card` div
2. Izaberite odgovarajuću Font Awesome ikonu
3. Dodajte naziv i opis usluge

### Ažuriranje Kontakt Forme
Forma trenutno prikazuje uspešnu poruku. Za stvarno slanje:
1. Dodajte backend endpoint
2. Ažurirajte JavaScript `contactForm` event listener
3. Implementirajte stvarno slanje email-a

## 🛠 Tehnologije

- **HTML5** - Semantička struktura
- **CSS3** - Moderni stilovi i animacije
- **JavaScript ES6** - Interaktivnost
- **Font Awesome** - Ikone
- **Google Fonts** - Typography (Poppins)

## ✨ Buduća Proširenja

- CMS integracija za lakše ažuriranje
- Online booking sistem
- E-commerce za cvetni deo
- Blog sekcija
- Multilingual support
- Progressive Web App funkcionalnost

---

💝 **Kreiran sa ljubavlju za Baloni Đorđević dekoracije!**