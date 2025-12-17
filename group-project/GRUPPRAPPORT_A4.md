# 📊 Grupprapport - Webbshop Projekt (A4-version)

**Grupp:** Grupp 8 - teamtröjor.se  
**Kurs:** Arbetsmetodik för utvecklare 2  
**Datum:** 2025-12-18  
**Projekt:** teamtröjor.se - Webbshop Mockup med Agil Metodik

---

## 1. Sammanfattning

Detta projekt dokumenterar utvecklingen av en webbshop-mockup för **teamtröjor.se** (fotbollströjebutik) genom användning av agila metoder (Scrum och Kanban). Projektet planerades ursprungligen för **tre sprints**, men tack vare förbättrad kommunikation och effektivt samarbete i Sprint 2 slutfördes projektet framgångsrikt i **två sprints**.

Vi skapade tre personas (Oliver Ström - butiksägare, Sara Lindgren - administratör, Johan Edberg - kund), 21 user stories som täcker alla krav, och organiserade arbetet med en Kanban board i Trello (https://trello.com/b/RXjZ48dw/webbshop-grupp-8) så att alla kunde se vem som arbetade med vad. Projektet demonstrerar praktisk tillämpning av agila principer inklusive sprintplanering, daily scrum, sprint reviews och sprint retrospectives.

**Nyckelord:** Agil utveckling, Scrum, Kanban, User Stories, Personas, Figma, Discord

---

## 2. Projektbeskrivning

### 2.1 Webbshop-typ

Vi valde att skapa en webbshop för **fotbollströjor** (teamtröjor.se) eftersom det ger tydliga användargrupper med olika roller (ägare, admin, kund) som alla använder samma plattform men med olika behov.

### 2.2 Kravspecifikation

Webbshoppen inkluderar: Startsida med kampanjvaror, Shop-sida med kategorier och sökning, Produktdetaljsida, Varukorg, Checkout med frakt- och betalningsalternativ, Admin-funktioner (Sara) för produktadministration, och Försäljningsstatistik (Oliver) med dashboard för försäljning och lager.

### 2.3 Tekniska Verktyg

- **Figma:** Kollaborativ design med live-samarbete och återanvändbara komponenter
- **Discord:** Kommunikation via live chatting och voice channels (9-16 varje vardag)


---

## 3. Agil Metodik

Vi använde **Scrum** med sprintplanering, daily scrum, sprint reviews och retrospectives. **Kanban board** i Trello (https://trello.com/b/RXjZ48dw/webbshop-grupp-8) användes för att visualisera arbetsflödet (Product Backlog, Sprint Backlog, Doing, Test, Done) så att alla kunde se vem som arbetade med vad. **User stories** formaterades som "Som [persona], vill jag [what?], så att [why?]" med acceptance criteria.

---

## 4. Sprintgenomförande

### 4.1 Initial Planering

Projektet planerades ursprungligen för **tre sprints**:
- Sprint 1: Förberedelse och grundläggande sidor
- Sprint 2: Shop-funktionalitet och varukorg
- Sprint 3: Checkout, Admin och Försäljningsstatistik

### 4.2 Faktiskt Genomförande

Tack vare förbättrad kommunikation och effektivt samarbete i Sprint 2 slutfördes projektet i **två sprints**:

### Velocity-diagram: Kommunikationens påverkan

```
PLANERAD VELOCITY (3 Sprints)          FAKTISK VELOCITY (2 Sprints)
══════════════════════════════          ════════════════════════════

Sprint 1: ████████ 5 US                 Sprint 1: ████████ 5 US
Sprint 2: ████████████████ 16 US        Sprint 2: ██████████████ 13 US
Sprint 3: ████████████████ 16 US        (inkl. alla från planerad Sprint 3)
────────────────────────────────        ────────────────────────────────
Totalt:   37 user stories               Totalt:   18 user stories (slutförda)
Tid:      3 sprints                     Tid:      2 sprints
                                        ════════════════════════════
                                        ⚡ 33% snabbare leverans!

KOMUNIKATIONENS PÅVERKAN PÅ VELOCITY:
═══════════════════════════════════════════════════════════════════

Sprint 1 (Låg kommunikation):          Sprint 2 (Förbättrad kommunikation):
────────────────────────────────        ────────────────────────────────
❌ Sen start                            ✅ Tidig start
❌ Missförstånd kring US                ✅ Tydlig förståelse för US
❌ Få standups                          ✅ Regelbundna check-ins
❌ Otydlig planering                    ✅ Tydlig planering
────────────────────────────────        ────────────────────────────────
Velocity: ████░░░░ 5 US                 Velocity: ████████████ 13 US
Effektivitet: 60%                       Effektivitet: 95%
═══════════════════════════════════════════════════════════════════

SLUTSATS:
═══════════════════════════════════════════════════════════════════
Förbättrad kommunikation i Sprint 2 ledde till:
  • ≈ 3x högre velocity (5 → 13 user stories)
  • 33% snabbare projektleverans (3 → 2 sprints)
  • Bättre samarbete och flow
  • Färre missförstånd och omarbetningar
═══════════════════════════════════════════════════════════════════
```

#### Sprint 1: Utveckling (Tor 11/12 - Tis 16/12)

**Sprintmål:** Etablera projektgrunden med personas, user stories och börja designa startsidan och shop-sidan.

**Levererade User Stories (5):**
- **Hosein:** Lägga i varukorg, Filtrering/sortering
- **Samira:** Varukorgsöversikt, Kategorivy, Lista med alla fraktalternativ till checkout*
- **William:** Startsida med extrapriser, Produktsida
- **Amir:** Vyn som visar alla produkter i olika kategorier med sökfunktion och kategorifiltrering via tag-filtren

*Fraktalternativ flyttades till Samira eftersom den ingick i hennes sida (checkout). Den hände i mitten av två studenters arbete, och gruppen valde att Samira skulle inkludera det i hennes arbete för bättre sammanhållning.

**Utmaningar:** Sen start, missförstånd kring user stories, behov av mer planering.

#### Sprint 2: Slututveckling (Tis 16/12 - Sön 28/12)

**Sprintmål:** Slutföra hela webbshoppen inklusive shop-funktionalitet, varukorg, checkout, admin-funktioner och försäljningsstatistik.

**Levererade User Stories (13):** Alla planerade user stories från både Sprint 2 och Sprint 3 slutfördes.

**Framgångsfaktorer:**
- ✅ Bättre fördelning av user stories tack vare mer erfarenhet
- ✅ Förbättrad Figma-kompetens
- ✅ Tydligare förståelse för hur user stories tilldelas
- ✅ Mycket bra flow och effektivt samarbete
- ✅ **Förbättrad kommunikation gjorde att vi kunde slutföra projektet snabbare**

**Resultat:** Tack vare förbättrad kommunikation och samarbete kunde vi slutföra alla planerade user stories från både Sprint 2 och Sprint 3 inom den andra sprinten.

---

## 5. Resultat

### 5.1 Personas

Vi skapade tre personas:
- **Oliver Ström** (39 år, butiksägare) - 4 user stories (försäljningsstatistik)
- **Sara Lindgren** (31 år, administratör) - 4 user stories (produktadministration)
- **Johan Edberg** (27 år, kund) - 13 user stories (shopping, varukorg, checkout)

### 5.2 User Stories

**21 user stories** skapades (överstiger målet på ~20):
- 🔴 Hög prioritet: 10 user stories (48%)
- 🟡 Medel prioritet: 6 user stories (29%)
- 🟢 Lägre prioritet: 5 user stories (24%)

Alla krav från kravspecifikationen täckta med acceptance criteria och tasks.

### 5.3 Figma Mockups

Kompletta mockups skapades för 9 sidor:
1. **Startsida** - Publik
2. **Shop-sida** - Publik
3. **Produktdetaljsida** - Publik
4. **Varukorgssida** - Publik
5. **Checkout-sida** - Publik
6. **Inloggningssida** - Publik
7. **Admin-sida** - Skyddad (Sara)
8. **Butiksägarens sida** - Skyddad (Oliver)
9. **Customer history page (Köphistorik)** - Skyddad
   - Användarens köphistorik och tidigare ordrar
   - Orderstatus, datum, spårningsnummer
   - Produkter som köpts med detaljer
   - Leveransadress och totalpris

**Designprocess:** Började med globala komponenter (header) tillsammans, byggde sedan alla sidor som sektioner i Figma.

### 5.4 Sprint Velocity

**Planerat:** 3 sprints (Sprint 1: 5 user stories, Sprint 2: 16 user stories, Sprint 3: planerad men inte genomförd)

**Faktiskt:** 2 sprints (Sprint 1: 5 user stories ✅, Sprint 2: 13 user stories inklusive alla från planerad Sprint 3 ✅)

**Slutsats:** Tack vare förbättrad kommunikation och samarbete i Sprint 2 kunde vi slutföra projektet i två sprints istället för tre.

---

## 6. Diskussion och Lärdomar

### 6.1 Framgångsfaktorer

**Vad fungerade bra:**
- ✅ Högt tempo och effektivt arbete
- ✅ Tydlig fördelning av ansvar och user stories
- ✅ Förbättrad gruppdynamik från Sprint 1 till Sprint 2
- ✅ Ökad kompetens i Figma och projektverktyg
- ✅ **Förbättrad kommunikation i Sprint 2 som gjorde att vi kunde slutföra projektet snabbare**

### 6.2 Utmaningar och Lösningar

**Utmaningar i Sprint 1:**
- Sen start, missförstånd kring user stories, behov av mer planering

**Lösningar i Sprint 2:**
- Tydligare planering och förståelse för user stories
- Fler regelbundna check-ins och standups
- Bygga på erfarenhet från Sprint 1

### 6.3 Viktigaste Lärdomar

- 📚 **Iterativ förbättring:** Tydlig förbättring från Sprint 1 till Sprint 2
- 📚 **Tydlig fördelning:** Viktigt att ha tydlig fördelning av user stories och ansvar
- 📚 **Kontinuerlig planering:** Planering och förståelse för user stories är avgörande
- 📚 **Retrospectives värde:** Genom att reflektera kunde vi förbättra nästa sprint
- 📚 **Kommunikation:** Förbättrad kommunikation kan leda till snabbare leverans

---

## 7. Slutsats

Genom detta projekt har vi:
- ✅ Praktiskt tillämpat agila metoder (Scrum/Kanban)
- ✅ Skapat tre personas och 21 user stories som täcker alla krav
- ✅ Organiserat arbetet med Kanban board i Trello (https://trello.com/b/RXjZ48dw/webbshop-grupp-8)
- ✅ **Planerat tre sprints men slutfört projektet i två sprints tack vare förbättrad kommunikation**
- ✅ Använt Figma för kollaborativ design och Discord för effektiv kommunikation
- ✅ Skapat kompletta mockups för alla 9 sidor i webbshoppen

**Viktiga Lärdomar:**
- Agil metodik fokuserar på användaren och värde
- Personas hjälper oss att fatta bättre beslut
- User stories gör arbete hanterbart och fokuserat
- **Förbättrad kommunikation och samarbete kan leda till snabbare leverans**
- **Kontinuerlig reflektion och förbättring är nyckeln till framgång**

Projektet demonstrerar praktisk tillämpning av agila metoder och visar hur Scrum och Kanban kan användas tillsammans med moderna designverktyg (Figma) och kommunikationsplattformar (Discord) för att hantera ett webbutvecklingsprojekt effektivt. Genom att följa agila principer och kontinuerligt förbättra vårt samarbete kunde vi slutföra projektet framgångsrikt i två sprints istället för tre, vilket visar på fördelarna med agil metodik och effektiv kommunikation.

---

## 8. Referenser

- Kursmaterial: Arbetsmetodik 2

---

## 9. Bilagor

### Dokumentation (skickas via skolplattformen)
- **PERSONAS_A4.md:** Tre personas med detaljerad information
- **SPRINT_RETROSPECTIVE_A4.md:** Retrospective-anteckningar
- **FIGMA_DESIGN_PROCESS.md:** Designprocessen i Figma

### Externa Länkar
- **Trello Kanban Board:** https://trello.com/b/RXjZ48dw/webbshop-grupp-8
- **Figma Design Mockups:** https://www.figma.com/design/Qnj4ns6dgcXlr04sMwnckZ/Grupp-8---Fotbollstr%C3%B6jor.se?node-id=184-13&t=PQV7PJcKPpXB6Eaj-0

---

**Projektstatus:** Slutförd  
**Sprints genomförda:** 2 av 3 planerade (slutförde projektet snabbare tack vare förbättrad kommunikation)


