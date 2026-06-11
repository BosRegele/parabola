# Scriptul prezentării — „Parabola: o curbă, șase identități"

> **Durata totală: ~23 de minute** (versiunea completă) sau **~13 minute** (versiunea comprimată — vezi nota de la finalul fiecărui slide din Partea I).
> Numerotarea de mai jos e cea din contorul de pe ecran (01/20 … 20/20).

**Legendă:** 🗣 = ce spui (poți citi aproape cuvânt cu cuvânt) · 🖱 = ce faci pe ecran · ⚠ = capcană / de evitat

---

## Cine prezintă ce

| Prezentator | Partea | Slide-uri | Conținut |
|---|---|---|---|
| **Boștină Vlad** | Partea I — **Fundamentele** | 01–10 | deschiderea, funcția de gradul al II-lea (definiție → 6 cazuri), demo-ul cu calculatorul |
| **Nedelcu Calin** | Partea a II-a — **Cercetarea** | 11–20 | șase identități ale parabolei, sursele, concluzia, Q&A |

**Dacă profesorul întreabă „cine ce prezintă?":**
- Vlad: „Eu prezint **Partea I — Fundamentele: funcția de gradul al II-lea**, de la definiție la cele șase cazuri geometrice, plus calculatorul interactiv."
- Calin: „Eu prezint **Partea a II-a — Cercetarea: șase identități ale parabolei** — aceeași curbă ca loc geometric, oglindă, limită, sumă infinită și conică, fiecare cu definiție, teoremă și demonstrație, doar cu materia claselor IX–XI."
- Pe scurt, oricare: „*Parabola: o curbă, șase identități* — Vlad acoperă lecția, Calin cercetarea."

La întrebări (Q&A) răspunde cel pe a cărui parte pică întrebarea; demonstrațiile din Partea a II-a sunt ale lui Calin, formulele de bază ale lui Vlad.

---

## Pregătire înainte de oră (5 minute)

1. Deschide site-ul (linkul GitHub Pages sau fișierul `index.html` local — merge și **fără internet**, doar fonturile arată puțin diferit).
2. Apasă **F11** pentru fullscreen.
3. Navigare: **săgeți / Space / scroll** = slide următor; **Home/End** = primul/ultimul; punctele din dreapta = sari direct la un capitol.
4. **⤢ din colțul oricărui grafic** (sau click pe graficele fără punct mobil) = graficul pe tot ecranul; acolo: **scroll = zoom** (centrat pe cursor), **tras de fundal = panoramare**, **dublu-click = reset**, punctele mobile se trag direct; **Escape** = închide.
5. Testează o dată proiectorul: dacă rezoluția e mică, totul scrollează — nu intra în panică.

---

## 01 · ACASĂ (40 sec) — vorbește VLAD

🗣 „Bună ziua! Suntem Vlad Boștină și Calin Nedelcu, iar proiectul nostru se numește *Parabola*. Toți știm parabola ca graficul funcției de gradul al II-lea din clasa a IX-a. Teza proiectului nostru este însă alta: **parabola nu e doar un grafic — e aceeași curbă care apare în matematică sub șase identități diferite**: grafic, loc geometric, oglindă, limită, sumă infinită și conică. Prezentarea are două părți: eu prezint fundamentele — lecția clasică — iar Calin partea de cercetare. Și totul, subliniez, e demonstrat doar cu materia claselor a IX-a – a XI-a."

🖱 Scroll mai departe.

---

# PARTEA I — FUNDAMENTELE · prezintă VLAD (slide-urile 02–10, total 7–8 min; comprimat: 4 min)

## 02 · FORMA GENERALĂ (1 min)

🗣 „Începem cu definiția. **Definiție: se numește funcție de gradul al II-lea o funcție f definită pe ℝ cu valori în ℝ, f(x) = ax² + bx + c, unde a, b, c sunt numere reale și a ≠ 0. Graficul ei se numește parabolă.**

Condiția a ≠ 0 e esențială — dacă a ar fi zero, ar rămâne bx + c, adică o funcție de gradul I, o dreaptă.

Fiecare coeficient are rolul lui: **a** decide direcția ramurilor — în sus dacă e pozitiv, în jos dacă e negativ; **b** influențează poziția orizontală a vârfului; iar **c** este exact intersecția cu axa Oy, pentru că f(0) = c."

*(comprimat: doar definiția + „a decide direcția, c e intersecția cu Oy" — 25 sec)*

## 03 · FORMA CANONICĂ (1 min)

🗣 „**Teoremă: orice funcție de gradul al II-lea se poate scrie sub forma canonică f(x) = a(x − m)² + n**, unde V(m, n) este vârful parabolei.

Demonstrația e completarea pătratului, o aveți în dreapta: scot a factor comun din primii doi termeni, adun și scad pătratul lui b/2a, și obțin exact a(x + b/2a)² − Δ/4a. De aici se citesc direct **m = −b/2a** și **n = −Δ/4a**.

Forma canonică e importantă pentru că arată parabola ca pe o «translatare» a lui ax²: același tipar, mutat cu m pe orizontală și cu n pe verticală."

## 04 · DISCRIMINANTUL (1 min)

🗣 „**Definiție: numărul Δ = b² − 4ac se numește discriminantul ecuației ax² + bx + c = 0.**

Discriminantul e «ADN-ul» parabolei, pentru că semnul lui decide tot comportamentul față de axa Ox: **Δ > 0** — două rădăcini reale distincte, parabola taie axa în două puncte; **Δ = 0** — rădăcină dublă, parabola e tangentă la axă exact în vârf; **Δ < 0** — nicio rădăcină reală, parabola nu atinge axa.

Și observați că Δ nu apare doar la rădăcini: apare și în ordonata vârfului, n = −Δ/4a. Deci Δ controlează și *cât de sus sau jos* e vârful."

## 05 · RĂDĂCINILE (45 sec)

🗣 „**Teoremă — formula rădăcinilor: pentru Δ ≥ 0, x₁,₂ = (−b ± √Δ) / 2a.**

Din ea derivă proprietățile din tabel: suma rădăcinilor e −b/a, produsul e c/a, iar o formulă mai puțin cunoscută: **distanța dintre rădăcini este |x₁ − x₂| = √Δ / |a|** — deci când Δ crește, rădăcinile se depărtează, iar când Δ devine 0, ele se «topesc» într-un singur punct. Și factorizarea: f(x) = a(x − x₁)(x − x₂)."

## 06 · VIÈTE (45 sec)

🗣 „**Teorema lui Viète: x₁ + x₂ = −b/a și x₁ · x₂ = c/a.**

Demonstrația e direct din formula rădăcinilor — o aveți pe ecran: adunând cele două rădăcini, radicalii se anulează și rămâne −b/a; înmulțindu-le, obținem (b² − Δ)/4a², adică 4ac/4a² = c/a.

Viète e utilă în ambele sensuri: din coeficienți afli suma și produsul fără să calculezi rădăcinile, și invers — din sumă și produs reconstruiești ecuația: x² − Sx + P = 0. Plus cazurile speciale: de exemplu dacă a + b + c = 0, atunci x = 1 e automat rădăcină."

## 07 · VÂRFUL (45 sec)

🗣 „**Consecință a formei canonice: vârful parabolei este V(−b/2a, −Δ/4a).**

Dacă a > 0, ramurile merg în sus și vârful e punct de **minim**; dacă a < 0, e punct de **maxim**. De o parte și de alta a vârfului, funcția e strict monotonă — descrește apoi crește, sau invers. Iar dreapta verticală x = −b/2a e **axa de simetrie**: parabola e perfect simetrică față de ea."

## 08 · SEMNUL (45 sec)

🗣 „Regula semnului se ține minte într-o singură frază: **f are semnul lui a în afara rădăcinilor și semn contrar lui a între rădăcini.** Dacă Δ ≤ 0, nu mai există «între» — funcția păstrează semnul lui a peste tot, cu eventuala excepție a vârfului care atinge zero. Pe ecran aveți toate cele șase combinații scrise explicit."

## 09 · CELE 6 CAZURI (40 sec)

🗣 „Toate combinațiile dintre semnul lui a și semnul lui Δ dau exact șase poziții posibile ale parabolei față de axa Ox — astea șase desene. Oricare exercițiu de poziționare se reduce la unul dintre ele."

🖱 *(opțional, dacă e timp)* Click pe un card → se deschide fereastra mare cu toate valorile calculate. Escape să închizi.

## 10 · CALCULATORUL (1 min — DEMO)

🗣 „Ca să nu rămână teorie, am construit un calculator interactiv: mut coeficienții și totul se recalculează live — discriminant, rădăcini, vârf, formă canonică, factorizare, monotonie, Viète."

🖱 **Demo-ul:** pornește de la a=1, b=0, c=−4 → „rădăcinile ±2". Mută **c** spre +2 → „Δ a devenit negativ — parabola s-a ridicat peste axă, rădăcinile au dispărut". Mută **a** la −1 → „acum avem maxim, nu minim". *(opțional: click pe grafic → fereastra mare.)*

⚠ Nu te juca prea mult — 1 minut maxim, urmează partea importantă.

---

# PARTEA A II-A — CERCETAREA · prezintă CALIN (slide-urile 11–20, total ~13 min)

## 11 · DIVIDER „Aceeași curbă, șase identități" (40 sec) — de aici preia CALIN

🗣 „Mulțumesc, Vlad. De aici preiau eu, cu partea de cercetare. Prima identitate — graficul — tocmai ați văzut-o. Urmează celelalte cinci: **loc geometric, oglindă, limită, sumă infinită și conica de frontieră**, plus două instrumente care le leagă între ele: tangentele și asemănarea.

Două promisiuni pentru tot ce urmează: fiecare capitol e construit ca în manual — definiție, teoremă, demonstrație, apoi experimentul interactiv — și **nu folosesc nimic peste materia claselor a IX-a – a XI-a**: distanțe, discriminant, derivate, limite, progresii și matrice."

## 12 · FOCARUL ȘI DIRECTOAREA (2 min)

🗣 „Prima identitate nouă: parabola ca **loc geometric**. Întâi termenul: **loc geometric înseamnă mulțimea tuturor punctelor din plan care îndeplinesc o proprietate dată.**

**Definiție: fie un punct F și o dreaptă d care nu trece prin el. Parabola de focar F și directoare d este locul geometric al punctelor P egal depărtate de F și de d** — adică PF = distanța de la P la d. Notăm cu **p** distanța de la vârf la focar.

Acum legătura cu clasa a IX-a — și asta e demonstrația mea preferată din proiect, pentru că are trei rânduri. Pun vârful în origine: focarul e F(0, p), directoarea e y = −p. Iau un punct P(x, y) de pe curbă și egalez distanțele: rădăcina din x² + (y−p)² trebuie să fie egală cu y + p. Ridic la pătrat: x² + (y−p)² = (y+p)². Termenii y² și p² se reduc și rămâne **x² = 4py**, adică **y = x²/4p**.

Dar asta e exact funcția noastră ax², cu **a = 1/4p**! Deci definiția geometrică cu distanțe și formula algebrică din clasa a IX-a descriu *același obiect*. Pentru orice parabolă ax² + bx + c: p = 1/4a, focarul e F(m, n+p), directoarea y = n − p."

🖱 **Demo:** trage punctul **P** pe grafic (direct cu mouse-ul) → „uitați-vă la ultimele două valori: PF și PQ rămân **egale** oriunde duc punctul — asta e definiția, verificată live." *(opțional ⤢ pentru ecran mare.)*

## 13 · TANGENTA, PE DOUĂ CĂI (2 min)

🗣 „**Definiție: tangenta la grafic în punctul T(x₀, f(x₀)) este poziția limită a secantei prin T**, când al doilea punct de intersecție se apropie de T. Din analiza de clasa a XI-a știm că panta ei este derivata: f′(x₀) = 2ax₀ + b. **Normala** este perpendiculara pe tangentă în punctul de tangență.

Dar există și o cale care nu folosește deloc derivata — doar clasa a IX-a. **Teoremă: dreapta y = sx + ℓ** — unde s e panta și ℓ e ordonata la origine — **este tangentă parabolei dacă și numai dacă sistemul lor are soluție dublă**, adică ecuația ax² + (b−s)x + (c−ℓ) = 0 are **Δ = 0**. Rezolvând, obținem ℓ = c − (s−b)²/4a.

Și acum momentul-cheie: verific că cele două căi dau **aceeași dreaptă**. Pe calea derivatei, ordonata la origine iese f(x₀) − s·x₀ = c − ax₀². Pe calea discriminantului, înlocuiesc s = 2ax₀ + b și obțin… tot c − ax₀². **Derivata din clasa a XI-a și discriminantul din clasa a IX-a sunt două limbaje pentru același adevăr.**"

🖱 **Demo:** trage punctul **T** → tangenta și normala se mișcă, iar în statistici „Δ = 0 ✓" rămâne mereu. Apoi apasă **butonul «înfășurătoare»**:

🗣 „Și acum ceva special: am scos parabola din desen. Ce vedeți sunt **doar 41 de tangente**, calculate cu formula de pe ecran — și totuși *vedeți parabola*. Curba poate fi descrisă nu doar prin punctele ei, ci și prin dreptele care o ating. Asta se numește înfășurătoare."

⚠ Lasă 3–4 secunde de tăcere aici — e cel mai puternic vizual din proiect.

## 14 · REFLEXIA ÎN FOCAR (1,5 min)

🗣 „A treia identitate: parabola ca **oglindă perfectă**. **Teoremă — proprietatea optică: orice rază paralelă cu axa de simetrie, după reflexie pe parabolă, trece prin focar.** Legea reflexiei spune că unghiul de incidență e egal cu unghiul de reflexie, măsurate față de tangentă.

Demonstrația folosește fix definiția cu focarul de adineauri, în trei pași: iau P pe parabolă și Q proiecția lui pe directoare — din definiție, **PF = PQ**, deci triunghiul FPQ e isoscel. Calculez mediatoarea segmentului FQ — adică perpendiculara pe mijlocul lui: are panta t/2p, care e exact 2at, adică **f′(t)** — și trece prin P. Deci mediatoarea **este chiar tangenta**. Iar într-un triunghi isoscel, mediatoarea bazei face unghiuri egale cu laturile — exact legea reflexiei: raza verticală se reflectă spre F. ∎

De-asta antenele de satelit, farurile, telescoapele și cuptoarele solare sunt parabolice: tot ce vine paralel se adună într-un singur punct."

🖱 **Demo:** animația rulează singură — fotonii cad paralel și se strâng în focarul care pulsează. Mișcă sliderul **a**: „indiferent de deschidere, toate razele trec prin focar". *(⤢ recomandat aici — arată foarte bine pe tot ecranul.)*

## 15 · CERCUL OSCULATOR (2 min)

🗣 „A patra identitate: parabola văzută prin **limite** — geometria diferențială, dar construită cinstit, cu materia noastră.

**Definiție: cercul osculator într-un punct al unei curbe este poziția limită a cercului care trece prin trei puncte ale curbei, când acestea se strâng spre punctul dat.** Raza lui se numește **raza de curbură**. Iar **evoluta** este locul geometric al centrelor acestor cercuri.

Observați că definiția folosește doar lucruri pe care le știm: cerc prin trei puncte — clasa a X-a; limită — clasa a XI-a.

**Teoremă: în vârful parabolei y = ax², raza de curbură este R = 1/2a.** Demonstrația, pe ecran: cercul prin vârf și prin punctele simetrice (±h, ah²) are, dintr-un calcul de două rânduri, raza r = (1 + a²h²)/2a. Când h tinde la 0, limita e 1/2a. ∎

Și aici vine surpriza care leagă capitolele între ele: **R = 1/2a = 2p — exact dublul distanței focale!** Cercul de curbură din vârf «știe» unde e focarul."

🖱 **Demo (cel mai didactic):** deschide cu **⤢**. Trage sliderul **h** de la 1 spre 0.05: „uitați cum cercul prin cele trei puncte roșii se stabilizează — **asta e o limită, văzută cu ochii**". Apoi trage **t** stânga-dreapta: „centrul cercului desenează curba mov — evoluta". Adu **t** la 0: „raza devine exact 1 — adică 1/2a — adică 2p".

## 16 · ARHIMEDE ȘI 4/3 (2 min)

🗣 „A cincea identitate: parabola ca **sumă infinită** — și un strop de istorie. Acum 2 250 de ani, Arhimede a demonstrat un rezultat uluitor, în lucrarea *Cvadratura parabolei*.

Două definiții: **segment parabolic** = regiunea cuprinsă între o coardă și arcul de parabolă; **triunghiul înscris al lui Arhimede** = triunghiul cu baza pe coardă și al treilea vârf în punctul de pe arc unde tangenta e paralelă cu coarda.

**Teorema lui Arhimede: aria segmentului parabolic este exact 4/3 din aria triunghiului înscris.**

Subliniez: Arhimede **nu avea integrale** — ele apar abia peste 1 900 de ani. Ideea lui, metoda epuizării, merge așa: pe lemă — pe y = x², coarda de la p la q are panta p + q, iar tangenta are panta 2x; sunt paralele exact la mijlocul absciselor, x = (p+q)/2. De aici rezultă, printr-un calcul de arii, că **fiecare generație nouă de triunghiuri are exact ¼ din aria generației precedente**.

Deci aria totală e T·(1 + ¼ + ¹⁄₁₆ + …) — o **progresie geometrică infinită cu rația ¼**, exact ce am învățat anul ăsta la limite de șiruri: suma e 1/(1 − ¼) = 4/3. ∎"

🖱 **Demo:** mută sliderul **n**: 0 → „un triunghi, arie 1" → 1 → „plus două triunghiuri mici, total 1,25" → 6 → „127 de triunghiuri, arie 1,33325 — adică **99,99%** din 4/3. Segmentul se umple, suma converge."

## 17 · CONICA GENERALĂ ȘI MATRICEA EI (2 min)

🗣 „A șasea identitate: parabola ca membru al unei familii — **conicele**. **Definiție: o conică este mulțimea punctelor din plan ale căror coordonate verifică o ecuație de gradul al II-lea: Ax² + Bxy + Cy² + Dx + Ey + F = 0**, cu A, B, C nu toate nule.

De ce se numesc «conice»? Pentru că sunt secțiunile unui con: un plan paralel cu o generatoare decupează o parabolă; mai «culcat» — o elipsă; mai «vertical», tăind ambele pânze — o hiperbolă.

Acum legătura cu algebra de clasa a XI-a: toată ecuația se poate scrie ca **un singur produs de matrice** — vectorul [x y 1] ori matricea simetrică din mijloc ori transpusul vectorului. O ecuație întreagă, comprimată într-o înmulțire de matrice.

**Teorema de clasificare** — pe care o admitem, demonstrația completă cerând rotații de axe: semnul lui **B² − 4AC** decide tipul: negativ — elipsă, **zero — parabolă**, pozitiv — hiperbolă. Dar intuiția e accesibilă: partea de gradul II, Ax² + Bxy + Cy², devine **pătrat perfect** exact când B² − 4AC = 0 — e *același discriminant* din clasa a IX-a, întâlnit într-un context nou! Deci **parabola e cazul de frontieră dintre elipsă și hiperbolă** — clipa de echilibru dintre o curbă închisă și una cu două ramuri."

🖱 **Demo:** deschide cu **⤢**. Pornești pe A=1, B=2, C=1: „B²−4AC = 0 — și priviți: o **parabolă rotită**, care nici măcar nu e grafic de funcție — nu trece testul dreptei verticale!" Mută **B** la 0: „a devenit cerc — discriminantul e −4". Mută **C** la −1: „hiperbolă". Revino la B=2, C=1: „și iar parabolă — frontiera".

## 18 · TOATE PARABOLELE SUNT ASEMENEA (1,5 min)

🗣 „Un fapt contraintuitiv, demonstrabil în trei rânduri. **Definiție: o asemănare de raport λ > 0 este o transformare a planului care înmulțește toate distanțele cu λ** — un «zoom» uniform; de exemplu (x, y) → (λx, λy). Două figuri sunt asemenea dacă una e imaginea celeilalte printr-o asemănare.

**Teoremă: oricare două parabole sunt asemenea.** Demonstrație: iau y = ax² și aplic zoom-ul X = λx, Y = λy. Atunci Y = λ·ax² = λa·(X/λ)² = **(a/λ)·X²**. Alegând λ = a/a′, parabola cu coeficientul a devine exact parabola cu coeficientul a′. ∎

Deci nu există parabole «mai grase» sau «mai subțiri» — există doar parabole văzute mai de aproape sau mai de departe, exact ca cercurile. Atenție, la elipse asta e **fals**: raportul semiaxelor nu se schimbă la zoom, deci o elipsă turtită nu e asemenea cu una rotundă. Parabolele sunt speciale."

🖱 **Demo:** mută sliderul **a** de la 0.25 la 4: „în stânga, fereastră fixă — curba *pare* să se schimbe; în dreapta, aceeași curbă văzută cu zoom λ = a — **nu se mișcă deloc, pixel cu pixel aceeași**."

## 19 · SURSE (30 sec)

🗣 „Sursele: lucrarea originală a lui Arhimede, manualele claselor a IX-a și a XI-a, plus MathWorld, LibreTexts și Wikipedia pentru capitolele de conice și optică. Un punct de metodă: **fiecare rezultat din partea a doua a fost re-demonstrat cu instrumente din programa IX–XI — fără integrale și fără geometrie proiectivă** — tocmai ca să pot răspunde la orice întrebare despre orice formulă de pe ecran."

## 20 · FINAL (40 sec)

🗣 „În concluzie: am plecat de la trei coeficienți — a, b, c — și am ajuns la **șase identități ale aceleiași curbe**: graficul funcției de gradul II, locul geometric al punctelor egal depărtate de focar și directoare, oglinda care adună razele în focar, limita cercurilor prin trei puncte, suma infinită a lui Arhimede și conica de frontieră cu B² − 4AC = 0.

Șase fețe — o singură parabolă. Vă mulțumim! Dacă aveți întrebări, orice grafic se poate deschide pe tot ecranul — și putem face zoom oriunde pe el."

---

# Întrebări probabile + răspunsuri pregătite

**„De unde ai formula curburii?"**
→ „Nu o folosesc. Definesc cercul osculator ca limită a cercului prin trei puncte — definiția riguroasă — și deduc doar raza în vârf, elementar: r = (1+a²h²)/2a, limită 1/2a. Formula generală κ(x) e materie de facultate și am evitat-o intenționat."

**„Ați calculat aria cu integrale?"**
→ „Nu — am folosit chiar metoda lui Arhimede: triunghiuri înscrise plus suma progresiei geometrice infinite, care e materie de a XI-a. Integrala ar da același 4/3, dar o vom face abia în clasa a XII-a."

**„Puteți demonstra clasificarea conicelor?"**
→ „Enunțul îl admitem — demonstrația completă cere rotația axelor. Dar intuiția da: partea de grad II e pătrat perfect exact când B²−4AC = 0, același criteriu de discriminant din clasa a IX-a."

**„Ce este p?"**
→ „Distanța de la vârf la focar; pentru y = ax², p = 1/4a. Directoarea e simetric, la distanța p sub vârf."

**„De ce trec toate razele prin focar?"**
→ Redau demonstrația în 3 pași: PF = PQ din definiție → triunghi isoscel → mediatoarea lui FQ are panta 2at = f′(t) și trece prin P, deci e tangenta → unghiuri egale. (E pe slide-ul 14.)

**„De ce e tangenta unică? / Ce înseamnă Δ = 0 la tangentă?"**
→ „Intersectarea dreptei cu parabola dă o ecuație de gradul II; tangentă înseamnă punct dublu de intersecție, adică soluție dublă, adică Δ = 0."

**„Toate parabolele asemenea? Și y = 100x²?"**
→ „Da — zoom cu λ = 100 o duce în y = x². Pare mai «îngustă» doar pentru că o privim de aproape. La elipse argumentul pică, pentru că zoom-ul păstrează raportul semiaxelor."

**„Cum e făcut site-ul?"**
→ „O singură pagină HTML cu JavaScript; toate graficele sunt desenate programatic pe canvas, cu exact formulele din prezentare — calculatorul chiar calculează, nu sunt poze."

**Dacă pică o întrebare la care nu știi:**
→ „Demonstrația completă depășește materia noastră — ideea însă e [spui intuiția] — și tocmai de-asta în proiect am marcat explicit ce demonstrăm și ce admitem."

---

# Versiunea comprimată (~13 min)

- Slide-urile 02–09 (Partea I): doar definiția + o frază fiecare → **4 min**.
- Calculatorul: un singur gest (c peste axă) → **30 sec**.
- Partea a II-a rămâne întreagă — ea e cercetarea: **~8–9 min**.
- Demo-uri live obligatorii: **înfășurătoarea (13), cercul osculator cu h→0 (15), conicele (17)**. Restul pot rămâne statice.
- La întrebări, folosește fereastra mare cu **zoom** ca să arăți detaliul exact despre care ești întrebat.
