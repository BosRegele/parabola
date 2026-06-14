# Scriptul prezentării — „Parabola: definiție geometrică și proprietăți"

> **Durata totală: ~21 de minute** (versiunea completă) sau **~12 minute** (versiunea comprimată).
> Numerotarea de mai jos e cea din contorul de pe ecran (01/13 … 13/13).
> Urmează **manualul, capitolul 11.4 (Parabola)**: parabola este studiată ca obiect geometric, cu ecuația canonică **y² = 2px**.
> Prezintă: **Nedelcu Calin**.

**Legendă:** 🗣 = ce spui (poți citi aproape cuvânt cu cuvânt) · 🖱 = ce faci pe ecran · ⚠ = capcană / de evitat

---

## Pregătire înainte de oră (5 minute)

1. Deschide site-ul (linkul GitHub Pages sau fișierul `index.html` local — merge și **fără internet**, doar fonturile arată puțin diferit).
2. Apasă **F11** pentru fullscreen.
3. Navigare: **săgeți / Space / scroll** = slide următor; **Home/End** = primul/ultimul; punctele din dreapta = sari direct la un capitol.
4. **⤢ din colțul oricărui grafic** (sau click pe graficele fără punct mobil) = graficul pe tot ecranul; acolo: **scroll = zoom** (centrat pe cursor), **tras de fundal = panoramare**, **dublu-click = reset**, punctele mobile se trag direct (pe verticală); **Escape** = închide.
5. Testează o dată proiectorul: dacă rezoluția e mică, totul scrollează — nu intra în panică.

---

## 01 · ACASĂ (30 sec)

🗣 „Bună ziua! Sunt Nedelcu Calin, iar proiectul meu se numește *Parabola*. Mulți cunosc parabola doar ca graficul funcției de gradul al II-lea, dar aceea e o singură parabolă — cea cu axă verticală. Eu urmez **manualul, capitolul 11.4**, unde parabola e tratată ca **obiect geometric**: pornesc de la definiția cu focar și directoare, deduc **ecuația canonică y² = 2px**, apoi tangenta, proprietatea optică, și încheiem cu câteva perspective mai avansate — curbura, aria după Arhimede, conicele și asemănarea. O singură curbă, privită riguros."

🖱 Scroll mai departe.

---

## 02 · PARABOLA — DEFINIȚIA GEOMETRICĂ (2 min)

🗣 „Începem cu **Definiția 80** din manual. **Fie g o dreaptă din plan și F un punct care nu aparține lui g. Parabola este locul geometric al punctelor M cu proprietatea d(M, g) = MF.** Punctul F se numește **focar**, dreapta g se numește **directoare**, iar segmentul MF este **raza focală** a punctului M.

Și un termen pe care îl voi folosi tot timpul: **parametrul parabolei**, notat **p**, este distanța de la focar la directoare, p = d(F, g). El măsoară deschiderea curbei."

🖱 **Demo:** trage punctul **M** pe grafic — „ultimele două valori, MF și d(M, g), rămân egale oriunde duc punctul. Asta e definiția, verificată live."

---

## 03 · PROCEDEUL DE CONSTRUCȚIE (1,5 min)

🗣 „Manualul dă și un mod concret de a desena parabola — secțiunea 11.4.1. **Așezăm o riglă de-a lungul directoarei. Pe riglă punem cateta mică a unui echer; de vârful unghiului ascuțit opus ei legăm o ață de lungime egală cu cateta mare, iar celălalt capăt îl fixăm în focarul F.** Plimbăm echerul de-a lungul riglei, ținând ața întinsă cu vârful creionului lipit de cateta mare — și vârful descrie o parabolă.

De ce funcționează? Cateta mare e perpendiculară pe directoare. Fie L lungimea ei, egală cu a aței. Creionul M împarte ața în MB, de-a lungul catetei, și MF, întins spre focar: MB + MF = L. Dar și de-a lungul catetei: d(M, g) + MB = L. Scad cele două și rămâne **MF = d(M, g)** — exact definiția."

🖱 **Demo (animație):** echerul alunecă pe riglă, iar M rămâne mereu pe curbă.

---

## 04 · ECUAȚIA CARTEZIANĂ (2,5 min)

🗣 „Acum scoatem ecuația — **Teorema 11.147**. Alegem reperul cu **originea la mijlocul distanței dintre F și directoare**, cu Oy paralelă cu g. Atunci focarul este **F(p/2, 0)**, directoarea este dreapta **x = −p/2**, iar teorema spune: **M(x, y) aparține parabolei dacă și numai dacă y² = 2px.**

Demonstrația: M e pe parabolă ⟺ d(M, g) = MF ⟺ d²(M, g) = MF². Distanța la directoare este x + p/2, iar MF² = (x − p/2)² + y². Egalez: (x + p/2)² = (x − p/2)² + y². Dezvolt — x² și p²/4 se reduc, px − (−px) = y² — și rămâne **y² = 2px**.

Două observații utile. **Parametric**, parabola se scrie x = t²/(2p), y = t. Și **explicit**, ea este reuniunea graficelor a două funcții, y = √(2px) și y = −√(2px). De aici un lucru important: **parabola, în această poziție, nu este graficul unei funcții** y = f(x) — pentru un x pozitiv are două ordonate. E reuniunea a două grafice."

🖱 Arată pe figură: F, directoarea g, punctul M, MF = d(M, g).

---

## 05 · ELEMENTELE PARABOLEI (1,5 min)

🗣 „Citim acum elementele direct de pe ecuație. **Vârful** este O(0, 0), punctul cel mai apropiat de directoare. Axa Ox se numește **axa transversă** — e axa de simetrie a curbei; axa Oy se numește **axa netransversă** — e tangenta în vârf. **Focarul** F(p/2, 0) și **directoarea** x = −p/2 sunt simetrice față de vârf, fiecare la distanța p/2.

Și o noțiune din manual: cu funcția **F(x, y) = y² − 2px**, planul se împarte în **interiorul** parabolei, int(P), unde F(x, y) < 0 — regiunea care conține focarul — și **exteriorul**, ext(P), unde F(x, y) > 0. Cele două sunt disjuncte și, împreună cu parabola, acoperă tot planul."

🖱 Arată pe figură interiorul colorat și eticheta semnului lui y² − 2px.

---

## 06 · INTERSECȚIA CU O DREAPTĂ (1,5 min — DEMO)

🗣 „Manualul face și o observație despre dreptele care taie parabola. **Punctele comune ale unei drepte cu parabola sunt soluțiile sistemului** format din ecuația dreptei și a parabolei. Înlocuind y = mx + q în y² = 2px, obțin o ecuație de gradul al II-lea — deci o dreaptă taie parabola în **cel mult două puncte**.

Pentru m ≠ 0, discriminantul ei este Δ = 4p(p − 2mq): **Δ > 0 dreaptă secantă**, două puncte; **Δ = 0 tangentă**, un punct; **Δ < 0 exterioară**, niciun punct."

🖱 **Demo:** mișc **q** și **m** — „priviți cum cele două puncte se apropie, se contopesc când Δ = 0 (tangenta), apoi dispar. Niciodată mai mult de două."

---

## 07 · TANGENTA PRIN DEDUBLARE (2 min)

🗣 „Tangenta — secțiunea 11.4.2. Manualul o obține fără derivate, prin **dedublare**. **Fie M₀(x₀, y₀) un punct al parabolei. Ecuația tangentei în M₀ este d: y·y₀ = p(x + x₀)** — se obține din y² = 2px înlocuind y² cu y·y₀ și x cu (x + x₀)/2. Panta ei este p/y₀.

Dreapta care trece prin M₀ și e perpendiculară pe tangentă se numește **normala**, notată n. Panta ei este −y₀/p, opusul inversului. Verific: (p/y₀) · (−y₀/p) = −1 — perpendiculare, cum trebuie."

🖱 **Demo:** trage **M₀** pe curbă (vertical) → tangenta și normala se rotesc, rămânând mereu perpendiculare.

---

## 08 · REFLEXIA ÎN FOCAR (2 min)

🗣 „Proprietatea optică — **Teorema 11.148**. **Tangenta și normala în M₀ sunt bisectoarele unghiurilor determinate de raza focală M₀F și de paralela prin M₀ la axa parabolei.** Optic: orice rază paralelă cu axa, reflectată de parabolă, trece prin focarul F.

Demonstrația din manual: fie A proiecția lui M₀ pe directoare, A(−p/2, y₀), și F(p/2, 0). Panta lui AF este −y₀/p, panta tangentei e p/y₀, produsul lor −1 — deci **AF ⊥ d**. Din definiție M₀A = M₀F, deci triunghiul AM₀F e isoscel; tangenta, fiind perpendiculară pe baza AF, e **bisectoarea unghiului din M₀**. Cum M₀A e paralelă cu axa, tangenta face unghiuri egale cu raza focală și cu paralela la axă — exact legea reflexiei.

De-asta antenele de satelit, radiotelescoapele, farurile și cuptoarele solare sunt parabolice."

🖱 **Demo (animație):** razele cad paralel cu axa și se strâng în focar. Mișcă **p** — „indiferent de deschidere, toate trec prin F".

---

## 09 · CERCUL OSCULATOR (2 min)

🗣 „Trecem la perspectivele suplimentare, dincolo de manual. Prima — parabola prin **limite**.

**Cercul osculator într-un punct este poziția limită a cercului care trece prin trei puncte ale curbei, când acestea se strâng spre punct.** Raza lui = raza de curbură; **evoluta** = locul centrelor.

**Teoremă: în vârful parabolei y² = 2px, raza de curbură este R = p.** Demonstrația: cercul prin vârful O și punctele simetrice (h²/2p, ±h) are centrul pe Ox, C(r, 0); din condiția ca (h²/2p, h) să fie pe cerc obțin r = p + h²/(4p), care tinde la **p** când h → 0. Raza de curbură în vârf este chiar parametrul."

🖱 **Demo:** deschide cu ⤢. Trage **h** spre 0: „cercul prin cele trei puncte se stabilizează — limita văzută cu ochii". Trage **t**: „centrul desenează evoluta".

---

## 10 · ARHIMEDE ȘI 4/3 (2 min)

🗣 „A doua — parabola ca **sumă infinită**, și puțină istorie.

**Coardă** = segmentul AB dintre două puncte; **segment parabolic** = regiunea dintre coardă și arc; **triunghi înscris** = ABV′, cu V′ punctul de pe arc unde tangenta e paralelă cu coarda.

**Teorema lui Arhimede (sec. III î.Hr.): aria segmentului parabolic = 4/3 din aria triunghiului înscris.**

Demonstrația, fără integrale, pe parabola y² = x. (1) Un punct are forma (t², t); panta coardei dintre parametrii a și b e 1/(a+b), panta tangentei e 1/(2t); le egalez și V′ stă la mijlocul parametrilor. (2) Aria triunghiului dintre a și b e (b−a)³/8; coarda se înjumătățește, deci fiecare triunghi nou are 1/8, și fiind două pe coardă — generația nouă e 1/4 din precedenta. (3) A = T(1 + ¼ + ¹⁄₁₆ + …); suma progresiei geometrice cu rația ¼ este 4/3 ⇒ **A = 4/3 · T**."

🖱 **Demo:** **n** de la 0 la 6 — „127 de triunghiuri, 99,99% din 4/3".

---

## 11 · CONICA GENERALĂ ȘI MATRICEA EI (2 min)

🗣 „A treia — parabola între **conice**. **O conică este mulțimea punctelor care verifică o ecuație Ax² + Bxy + Cy² + Dx + Ey + F = 0**, cu A, B, C nu toți nuli.

Numele vine de la secțiunile printr-un con dublu: plan paralel cu o generatoare → parabolă; plan oblic → elipsă; plan tăind ambele pânze → hiperbolă. Toată ecuația se scrie matricial. **Teoremă (admisă): semnul lui B² − 4AC decide tipul** — negativ elipsă, **zero parabolă**, pozitiv hiperbolă. Parabola e **frontiera** dintre elipsă și hiperbolă."

🖱 **Demo:** A=1, B=2, C=1 → „parabolă rotită". B=0 → „cerc". C=−1 → „hiperbolă". Revino → „și iar parabolă — frontiera".

---

## 12 · TOATE PARABOLELE SUNT ASEMENEA (1 min)

🗣 „Ultima — un fapt contraintuitiv. **O asemănare de raport λ > 0 înmulțește toate distanțele cu λ** — un „zoom" uniform.

**Teoremă: oricare două parabole sunt asemenea.** Pornesc cu y² = 2px și aplic X = λx, Y = λy: obțin Y² = 2(pλ)X. Alegând λ = p′/p, parabola de parametru p devine cea de parametru p′. Deci nu există parabole „mai late" sau „mai înguste" — doar văzute de la altă distanță. Ca la cercuri."

🖱 **Demo:** **p** de la 0.25 la 4 — „stânga, fereastră fixă, pare că se schimbă; dreapta, zoom λ = 1/p, coincide cu y² = 2x".

---

## 13 · FINAL (30 sec)

*(pe ecran: „Vă mulțumesc pentru atenție!")*

🗣 „În concluzie: am urmat manualul și am tratat parabola ca obiect geometric — locul punctelor egal depărtate de focar și directoare. Am dedus ecuația canonică y² = 2px, am construit-o cu rigla și echerul, i-am scris tangenta prin dedublare și am demonstrat proprietatea optică prin teorema bisectoarelor. Apoi am privit aceeași curbă și prin curbură, prin aria lui Arhimede, prin conice și prin asemănare.

Vă mulțumesc pentru atenție! Dacă aveți întrebări, orice grafic se poate deschide pe tot ecranul, cu zoom oriunde."

---

# Întrebări probabile + răspunsuri pregătite

**„De ce y² = 2px și nu y = ax² din clasa a IX-a?"**
→ „Pentru că urmez manualul, care tratează parabola ca obiect geometric. Ecuația canonică în reperul cu originea la mijlocul dintre focar și directoare este y² = 2px. Forma y = ax² descrie doar o parabolă cu axă verticală — un caz particular, obținut printr-o schimbare de axe."

**„Ce este parametrul p?"**
→ „Distanța de la focar la directoare, p = d(F, g). În ecuația y² = 2px, focarul e F(p/2, 0) și directoarea x = −p/2."

**„Ce înseamnă dedublarea?"**
→ „Un procedeu algebric: în ecuația parabolei înlocuiesc y² cu y·y₀ și x cu (x + x₀)/2; rezultatul, y·y₀ = p(x + x₀), e chiar tangenta în M₀. Nu folosește derivate."

**„De ce trec toate razele prin focar?"**
→ Redau Teorema 11.148: A = proiecția pe directoare; AF ⊥ tangentă (produsul pantelor −1); triunghiul AM₀F e isoscel, deci tangenta e bisectoarea unghiului din M₀; cum M₀A e paralelă cu axa, unghiurile de incidență și reflexie sunt egale.

**„De ce parabola nu e graficul unei funcții?"**
→ „În poziția canonică y² = 2px, pentru un x > 0 sunt două ordonate, y = ±√(2px). E reuniunea a două grafice de funcție, G_f ∪ G_{−f}, nu un singur grafic."

**„De unde formula curburii?"**
→ „Nu folosesc formula generală. Definesc cercul osculator ca limită a cercului prin trei puncte și deduc doar raza în vârf, R = p — un calcul de două rânduri."

**„Ați calculat aria cu integrale?"**
→ „Nu — am folosit chiar metoda lui Arhimede: triunghiuri înscrise plus suma progresiei geometrice infinite."

**„Demonstrați clasificarea conicelor?"**
→ „Enunțul îl admitem — demonstrația completă cere rotația axelor. Intuiția: partea de grad II e pătrat perfect exact când B² − 4AC = 0."

**„Toate parabolele asemenea? Și y² = 100x?"**
→ „Da — un zoom potrivit o duce în y² = 2x. Pare diferită doar pentru că o privim de la altă distanță. La elipse argumentul cade, pentru că zoom-ul păstrează raportul semiaxelor."

**„Ce surse ați folosit?"**
→ „Manualul, capitolul 11.4 (Parabola) — definiția, ecuația, dedublarea tangentei și teorema bisectoarelor sunt de acolo. Pentru perspectivele suplimentare: lucrarea lui Arhimede *Cvadratura parabolei*, plus MathWorld și LibreTexts. Graficele sunt construite de la zero pentru proiect."

**Dacă pică o întrebare la care nu știi:**
→ „Demonstrația completă depășește materia tratată în proiect — ideea este [intuiția] — iar marcajul „o admitem" de pe slide arată unde m-am oprit intenționat."

---

# Versiunea comprimată (~12 min)

- 02–05 (definiție, construcție, ecuația y² = 2px, elemente): intacte — sunt cheia rigorii din manual. **6 min**.
- 06 (intersecția cu o dreaptă): mișcă dreapta prin cele trei poziții. **1 min**.
- 07–08 (tangenta prin dedublare, reflexia): intacte — miezul capitolului. **2,5 min**.
- 09–12 (curbură, Arhimede, conice, asemănare): pe scurt, câte o frază + demo. **~2 min**.
- Demo-uri live obligatorii: **definiția cu M mobil (02), construcția animată (03), intersecția cu dreapta (06), reflexia (08), cercul osculator cu h → 0 (09)**.
