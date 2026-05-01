# VoltZone — Magazin Online de Electronice
> Proiect realizat pentru materia Comert Electronic

## Despre proiect

In loc sa folosesc un CMS precum WordPress sau Wix, am ales sa construiesc site-ul de la zero folosind HTML, CSS si JavaScript pur. Aceasta decizie a fost luata din mai multe motive:

- CMS-urile gratuite sunt limitate si nu permit controlul complet asupra design-ului si functionalitatilor
- Versiunile cu functionalitati complete (WooCommerce, teme premium, plugin-uri) implica costuri semnificative
- Construind de la zero am putut implementa exact cerintele proiectului, fara restrictiile impuse de o platforma terta
- Rezultatul este un site complet functional, mobile-first, cu toate elementele unui magazin online real

Toate cerintele din enuntul proiectului sunt indeplinite si demonstrabile.

## Pagini (6 pagini)

- **Acasa (Home)** — hero section, categorii, produse featured, banner promotie cu timer, newsletter
- **Produse (Products)** — catalog cu 24 de produse si filtrare pe categorii
- **Despre noi (About)** — povestea magazinului, valori, echipa
- **Blog** — articole si ghiduri despre tehnologie
- **Contact** — formular de contact si informatii
- **Termeni si Conditii** — politica de plata, retur, livrare, GDPR

## Functionalitati implementate

- Design **mobile-first**, responsive pe telefon, tableta si desktop
- **Cos de cumparaturi** functional cu adaugare, stergere si modificare cantitate
- **Filtrare produse** pe categorii (telefoane, audio, laptopuri, gaming, wearables, camere)
- Timer countdown pentru promotii flash sale
- Wishlist, newsletter, formular de contact
- Imagini reale pentru toate produsele

## Simulare gateway de plata (metoda de monetizare)

Metoda de monetizare aleasa este **one-time payments** — plata unica per comanda, modelul standard al oricarui magazin online.

Fluxul de plata este complet simulat si functional:

1. Utilizatorul adauga produse in cos si apasa "Checkout"
2. Se deschide o fereastra de plata securizata (simulata)
3. Utilizatorul alege metoda de plata: **Card bancar, PayPal, Apple Pay sau Google Pay**
4. Completeaza datele cardului (formular cu formatare automata)
5. Apasa "Pay" — apare o animatie de procesare (simuleaza comunicarea cu Stripe)
6. Se afiseaza un ecran de confirmare cu numar de comanda unic generat (ex: #VZ-483921)

> Platile sunt simulate in scop demonstrativ. Nu se proceseaza bani reali.

## Imagini prelucrate

Site-ul contine peste 5 imagini prelucrate, utilizate in:
- Cardurile de produs (24 produse cu imagini individuale)
- Sectiunea hero si miniaturi
- Sectiunea About
- Articolele de blog

Imaginile provin din surse libere de drepturi (Unsplash) si au fost prelucrate prin tehnici de corectie cromatica, redimensionare si ajustare.

## Stiva tehnologica

HTML5 · CSS3 · JavaScript vanilla (fara framework-uri sau librarii externe)

## Cum se ruleaza

Deschide fisierul `index.html` in orice browser modern. Nu necesita instalare sau server.

## Structura

```
index.html   — intregul site
README.md    — documentatia proiectului
```
