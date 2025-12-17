# 🎯 Webbshop Project - Kanban Board

**Grupp:** Grupp 8
## 📄 Page Structure Overview

**Totalt antal sidor som behövs: 9 sidor**

1. **Startsida** - Publik
2. **Shop-sida** - Publik
3. **Produktdetaljsida** - Publik
4. **Varukorgssida** - Publik
5. **Checkout-sida** - Publik
6. **Inloggningssida** - Publik
7. **Admin-sida** - Skyddad (Sara)
8. **Butiksägarens sida** - Skyddad (Oliver)
9. **Customer history page** - Skyddad

## 📋 Product Backlog
**[🏃 Sprint Backlog](#-sprint-backlog-aktuell-sprint)** - User stories valda för aktuell sprint


*All user stories prioritized by value*

**Status:**
- Product Backlog innehåller alla 21 user stories prioriterade efter värde (Hög, Medel, Lägre)
- Alla 21 user stories är slutförda (Done)
- **Sprint 1 slutförda:** 5 user stories (Startsida, Produktsida, Fraktalternativ, Produkter i kategorier, Lägga i varukorg)
- **Sprint 2 slutförda:** 13 user stories (alla övriga funktioner inklusive checkout, admin och ägarens dashboard)

### 🔴 High Priority (10 user stories)

- [x] Kunden Johan vill se en överblick på kampanjvaror på startsidan *(Sprint 1 - Done)*
- [x] Kunden Johan vill kunna klicka in på en specifik produkt *(Sprint 1 - Done)*
- [x] Kunden Johan vill se en lista med olika fraktalternativ *(Sprint 1 - Done)*
- [x] Kunden Johan vill kunna se alla produkter i olika kategorier, söka i sökfältet och filtrera kategorier genom att klicka på tag-filtren högst upp på sidan, så att han snabbt kan hitta sitt favoritlag (Amir) *(Sprint 1 - Done)*
- [x] Kunden Johan vill kunna lägga till produkter i en varukorg *(Sprint 1 - Done)*
- [x] Kunden Johan vill kunna sortera och filtrera i alla vyer *(Sprint 2 - Done)*
- [x] Kunden Johan vill kunna se produkterna i sin varukorg *(Sprint 2 - Done)*
- [x] Kunden Johan vill se alla lag (kategorier) som har tröjor i shoppen *(Sprint 2 - Done)*
- [x] Kunden Johan vill kunna se en lista med olika betalningsalternativ *(Sprint 2 - Done)*
- [x] Kunden Johan vill se en summering av sin order *(Sprint 2 - Done)*

### 🟡 Medium Priority (6 user stories)

- [x] Ägaren vill kunna se försäljning per dag (Amir) *(Sprint 2 - Done)*
- [x] Ägaren vill kunna se produkter som är slut i lager (Amir) *(Sprint 2 - Done)*
- [x] Ägaren vill kunna se total försäljning (Amir) *(Sprint 2 - Done)*
- [x] Kunden Johan vill kunna logga in som kund *(Sprint 2 - Done)*
- [x] Kunden Johan vill kunna spara produkter *(Sprint 2 - Done)*
- [x] Kunden Johan vill kunna söka bland produkter *(Sprint 2 - Done)*

### 🟢 Lower Priority / Admin (5 user stories)

- [x] Ägaren vill kunna se vilka kategorier som säljer bäst per lag (Amir) *(Sprint 2 - Done)*
- [x] Admin vill kunna ändra lagersaldo *(Sprint 2 - Done)*
- [x] Admin vill kunna lägga till nya tröjor *(Sprint 2 - Done)*
- [x] Admin vill kunna välja ut specifika varor till utförsäljning *(Sprint 2 - Done)*
- [x] Admin vill kunna ändra pris, text och bild på produkter *(Sprint 2 - Done)*

---

## 🏃 Sprint Backlog

*Current Sprint: Sprint 1 - Development (Thu 11/12 - Tue 16/12)*

### Sprint Goal
Etablera projektgrunden med personas, user stories och börja designa startsidan och shop-sidan.

### Selected User Stories for Sprint 1

- [ ] Som kund (Johan) vill jag kunna se startsidan med välkomsttext, så att jag förstår vad webbshoppen erbjuder
  - [ ] Skriv välkomsttext (max 2-3 meningar)
  - [ ] Välj/skapa bild som representerar FootyShop (fotbollströjor)
  - [ ] Placera text och bild på mockup-startsidan
  - [ ] Testa att det ser bra ut på olika skärmstorlekar
  - **Persona:** Johan Edberg (Kund)
  - **Priority:** 🔴 High

- [ ] Som kund vill jag kunna logga in med användarnamn och lösenord, så att jag kan komma åt min profil
  - [ ] Design inloggningsformulär med tydliga fält
  - [ ] Placera på startsidan mockup (höger övre hörnet)
  - [ ] Lägg till "Glömt lösenord?"-länk (visuellt)
  - [ ] Se till att formuläret ser användarvänligt ut
  - **Persona:** Johan Edberg (Kund)
  - **Priority:** 🔴 High

- [ ] Som kund (Johan) vill jag kunna se tre utvalda produkter på startsidan, så att jag snabbt kan se populära produkter
  - [ ] Välj tre populära fotbollströjor (t.ex. Manchester United, Barcelona, Retro)
  - [ ] Hitta/skapa produktbilder
  - [ ] Design produktkort med bild, pris och titel
  - [ ] Placera tre produkter på startsidan mockup
  - [ ] Se till att de ser attraktiva ut
  - **Persona:** Johan Edberg (Kund)
  - **Priority:** 🔴 High

- [x] Kunden Johan vill kunna se alla produkter i olika kategorier, söka i sökfältet och filtrera kategorier genom att klicka på tag-filtren högst upp på sidan, så att han snabbt kan hitta sitt favoritlag (Amir) *(Sprint 1 - Done)*
  - [x] Design vy som visar produkter i olika kategorier
  - [x] Skapa shop-sida mockup med kategorier
  - [x] Implementera sökfunktion i sökfältet
  - [x] Implementera kategorifiltrering via tag-filtren högst upp på sidan
  - [x] Se till att kategorier är tydligt separerade
  - [x] Testa att kategorier är lätt att navigera och att sök/filtrering fungerar
  - **Persona:** Johan Edberg (Kund)
  - **Priority:** 🔴 High

- [ ] Som kund (Johan) vill jag kunna se produkter i minst tre kategorier, så att jag kan hitta produkter efter typ
  - [ ] Definiera tre kategorier (t.ex. Premier League, La Liga, Retrotröjor)
  - [ ] Välj 5 produkter per kategori
  - [ ] Design kategori-layout med rubriker
  - [ ] Placera produkter i kategorier på shop-sidan mockup
  - [ ] Se till att kategorier är visuellt separerade
  - **Persona:** Johan Edberg (Kund)
  - **Priority:** 🔴 High

---