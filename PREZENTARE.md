# Scriptul prezentării — „Parabola: șase perspective asupra aceleiași curbe"

> **Durata totală: ~20 de minute** (versiunea completă) sau **~11 minute** (versiunea comprimată).
> Numerotarea de mai jos e cea din contorul de pe ecran (01/13 … 13/13).
> Prezintă: **Nedelcu Calin**.

**Legendă:** 🗣 = ce spui (poți citi aproape cuvânt cu cuvânt) · 🖱 = ce faci pe ecran · ⚠ = capcană / de evitat

---

## Pregătire înainte de oră (5 minute)

1. Deschide site-ul (linkul GitHub Pages sau fișierul `index.html` local — merge și **fără internet**, doar fonturile arată puțin diferit).
2. Apasă **F11** pentru fullscreen.
3. Navigare: **săgeți / Space / scroll** = slide următor; **Home/End** = primul/ultimul; punctele din dreapta = sari direct la un capitol.
4. **⤢ din colțul oricărui grafic** (sau click pe graficele fără punct mobil) = graficul pe tot ecranul; acolo: **scroll = zoom** (centrat pe cursor), **tras de fundal = panoramare**, **dublu-click = reset**, punctele mobile se trag direct; **Escape** = închide.
5. Testează o dată proiectorul: dacă rezoluția e mică, totul scrollează — nu intra în panică.

---

## 01 · ACASĂ (30 sec)

🗣 „Bună ziua! Sunt Nedelcu Calin, iar proiectul meu se numește *Parabola*. Toți știm parabola ca graficul funcției de gradul al II-lea din clasa a IX-a, dar definiția aceasta e prea îngustă: ea acoperă doar parabolele cu axă verticală. Teza mea e că **parabola, ca obiect geometric, e o curbă care poate fi studiată din șase perspective complementare**: ca loc geometric, ca grafic, ca oglindă, ca limită, ca sumă infinită și ca secțiune conică. Voi începe cu definiția geometrică riguroasă, voi deduce ecuația, apoi voi recupera funcția de gradul al II-lea ca un caz particular — și de aici totul se va lega."

🖱 Scroll mai departe.

---

## 02 · PARABOLA — DEFINIȚIE GEOMETRICĂ (2 min)

🗣 „Începem cu definiția riguroasă. **Definiție: fie F un punct fix, numit focar, și d o dreaptă fixă care nu trece prin F, numită directoare. Parabola de focar F și directoare d este locul geometric al punctelor P egal depărtate de F și de d** — adică PF = dist(P, d). Vârful e punctul cel mai apropiat de directoare, iar **p** notează distanța de la vârf la focar — egală, prin simetrie, cu distanța de la vârf la directoare.

Observați un lucru esențial pe care îl voi sublinia toată prezentarea: această definiție **caracterizează orice parabolă din plan**, indiferent de orientarea axei de simetrie. Nu doar parabolele care sunt grafice de funcție."

🖱 **Demo:** trage punctul **P** pe grafic — „ultimele două valori, PF și PQ, rămân egale oriunde duc punctul. Asta e definiția, verificată live."

## 03 · ECUAȚIA PARABOLEI (2 min)

🗣 „Acum scoatem ecuația. **Teoremă: în reperul cu vârful în origine, axa de simetrie Oy, focarul F(0, p) și directoarea y = −p, parabola are ecuația x² = 4py.**

Demonstrația, în patru pași: pun P(x, y) un punct oarecare al curbei; PF, prin formula distanței, este √(x² + (y−p)²); dist(P, d), pentru că d e orizontală, este y + p; egalez și ridic la pătrat: x² + (y−p)² = (y+p)²; dezvoltând, y² și p² se reduc, rămâne **x² = 4py**.

Și acum legătura cu clasa a IX-a — **corolarul**, în două puncte: (i) notând a = 1/(4p), ecuația devine y = ax² — recunoaștem deja funcția. (ii) Pentru o parabolă cu vârful V(m, n) și axa paralelă cu Oy, prin **translație de coordonate** obținem y − n = a(x − m)². Dezvoltând paranteza, ajungem la **y = ax² + bx + c** — exact forma generală a funcției de gradul al II-lea, recuperată din definiția pur geometrică."

## 04 · FUNCȚIA DE GRADUL AL II-LEA (1,5 min)

🗣 „**Definiție: funcția f : ℝ → ℝ, f(x) = ax² + bx + c, cu a ≠ 0, se numește funcție de gradul al II-lea.** Din corolarul precedent, graficul ei este o **parabolă cu axa de simetrie paralelă cu Oy** — și subliniez: **un caz particular** al parabolelor din plan. Cele cu axă orizontală sau rotite (vezi conicele) nu se pot scrie ca grafic y = f(x).

Trei coeficienți, trei roluri: **a** decide direcția și deschiderea ramurilor; **b** poziționează vârful pe orizontală; **c** este intersecția cu Oy, f(0) = c.

A doua scriere, echivalentă — **forma canonică: f(x) = a(x − m)² + n**, cu V(m, n) vârful. Se obține prin completarea pătratului (pe ecran, în dreapta): scot a factor comun, adun și scad pătratul lui b/(2a), și citesc direct **m = −b/(2a)**, **n = −Δ/(4a)**. E tocmai translația din slide-ul precedent: tiparul y = ax², mutat cu m pe orizontală și n pe verticală."

## 05 · ELEMENTELE PARABOLEI (1,5 min)

🗣 „După ce am scris parabola algebric, îi citim **elementele geometrice** direct de pe grafic — fiecare punct și fiecare dreaptă au un nume.

**Vârful V(m, n)**, cu m = −b/(2a) și n = −Δ/(4a), este punctul unde curba își schimbă sensul: minim dacă a > 0, maxim dacă a < 0. **Axa de simetrie** este dreapta verticală x = −b/(2a) care trece prin vârf — parabola e perfect simetrică față de ea. **Intersecția cu Oy** este punctul (0, c), pentru că f(0) = c. **Intersecțiile cu Ox** sunt punctele de abscise x₁,₂ = (−b ± √Δ)/(2a) — acolo unde curba taie axa; ele există doar când Δ ≥ 0.

Pe grafic le aveți pe toate etichetate pe un exemplu concret: f(x) = 0,5x² − x − 1,5, cu vârful V(1, −2), rădăcinile −1 și 3, și intersecția cu Oy la −1,5."

## 06 · POZIȚIA FAȚĂ DE AXA Ox — CALCULATOR (2 min — DEMO)

🗣 „Acum punem totul la lucru într-un calculator interactiv. Întrebarea centrală: **câte puncte comune are parabola cu axa Ox?** Răspunsul îl dă discriminantul: **Δ = b² − 4ac decide numărul de intersecții** — Δ > 0 două puncte, Δ = 0 unul singur (tangentă, în vârf), Δ < 0 niciunul. Combinat cu semnul lui a (ramuri sus sau jos), rezultă **șase configurații posibile**.

Le pot arăta pe toate șase instantaneu — am pus butoane-preset pentru fiecare caz; un click și parabola sare exact la acea configurație. Sau mut liber coeficienții și totul se recalculează live: discriminant, intersecții, vârf, forma canonică."

🖱 **Demo:** apasă pe rând cele 6 butoane-preset — „a > 0, Δ > 0: taie axa în două puncte... a > 0, Δ < 0: plutește deasupra... a < 0, Δ < 0: complet sub axă". Apoi mut liber **c** de la −4 spre +2: „priviți cum cele două intersecții se apropie, se contopesc când Δ = 0, apoi dispar". Click pe grafic → fereastra mare.

⚠ E slide-ul cel mai interactiv din prima parte — 2 minute, merită.

## 07 · TANGENTA, PE DOUĂ CĂI (2 min)

🗣 „**Definiție: tangenta în T(x₀, f(x₀)) este poziția limită a secantelor prin T**; din analiză, panta ei e derivata f′(x₀) = 2ax₀ + b. **Normala** = perpendiculara pe tangentă în T.

Există însă și o cale fără derivate. **Teoremă: dreapta y = sx + ℓ este tangentă parabolei dacă și numai dacă sistemul cu f are soluție dublă** — adică Δ = (b−s)² − 4a(c−ℓ) = 0, de unde ℓ = c − (s−b)²/(4a).

Verific că cele două căi dau aceeași dreaptă: cu s = 2ax₀ + b, obțin (s−b)² = 4a²x₀², deci ℓ = c − ax₀². Iar tangenta din prima teoremă taie Oy la f(x₀) − s·x₀ = c − ax₀². **Aceeași dreaptă** — derivata și discriminantul, două limbaje pentru același adevăr."

🖱 **Demo:** trage **T** → „Δ = 0 ✓" rămâne mereu. Apoi butonul **„înfășurătoare"**:

🗣 „Și acum momentul-cheie: scot parabola din desen. Ce vedeți sunt 41 de tangente — și totuși *vedeți parabola*. Curba poate fi descrisă nu doar prin puncte, ci și prin dreptele care o ating. Asta se numește înfășurătoare."

⚠ Lasă 3–4 secunde de tăcere.

## 08 · REFLEXIA ÎN FOCAR (1,5 min)

🗣 „A treia perspectivă: parabola ca **oglindă**. **Teoremă: orice rază paralelă cu axa de simetrie, după reflexie pe parabolă, trece prin focar.**

Demonstrația în trei pași: (1) fie P(t, at²) punctul de impact, Q proiecția lui pe directoare; din definiție PF = PQ, deci P e pe mediatoarea lui [FQ]. (2) panta lui FQ e −2p/t, iar perpendicularele au produsul pantelor −1, deci panta mediatoarei e t/(2p) = 2at = f′(t) — adică mediatoarea **este** tangenta. (3) În triunghi isoscel, mediatoarea bazei face unghiuri egale cu laturile — exact legea reflexiei.

De-asta antenele de satelit, radiotelescoapele, farurile, telescoapele și cuptoarele solare sunt parabolice — concentrează tot ce vine paralel într-un singur punct."

🖱 **Demo (animație):** fotonii cad paralel și se strâng în focar. Mișcă **a** — „indiferent de deschidere, toate razele trec prin focar".

## 09 · CERCUL OSCULATOR (2 min)

🗣 „A patra perspectivă: parabola prin **limite**.

**Definiție: cercul osculator într-un punct al curbei este poziția limită a cercului care trece prin trei puncte ale curbei, când acestea se strâng spre punctul dat.** Raza lui = raza de curbură; **evoluta** = locul geometric al centrelor.

**Teoremă: în vârful parabolei y = ax², raza de curbură este R = 1/(2a).** Demonstrația: cercul prin V(0,0) și (±h, ah²) are centrul pe Oy (din simetrie), C(0, r), iar din formula distanței (h, ah²) la C: h² + (ah² − r)² = r². După dezvoltare și reducere, r = (1 + a²h²)/(2a) → 1/(2a) când h → 0.

Și surpriza: R = 1/(2a) = 2p — **exact dublul distanței focale**."

🖱 **Demo (cel mai didactic):** deschide cu ⤢. Trage **h** de la 1 spre 0.05: „cercul prin cele trei puncte se stabilizează — limita văzută cu ochii". Trage **t**: „centrul desenează evoluta". La **t = 0**, „raza devine 1 — adică 1/(2a) = 2p".

## 10 · ARHIMEDE ȘI 4/3 (2 min)

🗣 „A cincea perspectivă: parabola ca **sumă infinită** — și istorie.

**Definiții: coardă** = segmentul AB dintre două puncte de pe parabolă; **segment parabolic** = regiunea dintre coardă și arc; **triunghiul înscris** = ABV′, cu V′ punctul de pe arc unde tangenta e paralelă cu coarda.

**Teorema lui Arhimede (sec. III î.Hr., Cvadratura parabolei): aria segmentului parabolic = 4/3 din aria triunghiului înscris.**

Demonstrația, în trei pași, fără integrale: (1) panta coardei dintre p și q pe y = x² e (q²−p²)/(q−p) = p + q; tangenta are panta 2x; egalez 2x = p + q ⇒ x = (p+q)/2, deci V′ stă la mijlocul absciselor. (2) aria triunghiului dintre p și q este (q−p)³/8; coarda se înjumătățește la fiecare pas, deci triunghiul nou are 1/8 din cel vechi, și fiind două — generația nouă = 1/4 din precedenta. (3) A = T(1 + ¼ + ¹⁄₁₆ + …); folosesc formula sumei progresiei geometrice cu rația ¼: limita e 1/(1 − ¼) = 4/3 ⇒ **A = 4/3 · T**."

🖱 **Demo:** **n** de la 0 la 6 — „127 de triunghiuri, 99,99% din 4/3".

## 11 · CONICA GENERALĂ ȘI MATRICEA EI (2 min)

🗣 „A șasea perspectivă: parabola între **conice**. **Definiție: o conică este mulțimea punctelor (x, y) care verifică o ecuație Ax² + Bxy + Cy² + Dx + Ey + F = 0**, cu A, B, C nu toți nuli.

Numele vine de la **secțiunile printr-un con dublu** (vezi imaginea de pe slide): plan paralel cu o generatoare → parabolă; plan oblic → elipsă; plan tăind ambele pânze → hiperbolă.

Toată ecuația se scrie matricial: vector-linie [x y 1] ori matricea simetrică ori vector-coloană. **Teoremă (admisă): semnul lui B² − 4AC decide tipul** — negativ elipsă, **zero parabolă**, pozitiv hiperbolă. Intuiția: partea de grad II e pătrat perfect exact când discriminantul ei se anulează — același criteriu din clasa a IX-a. Parabola e **frontiera** dintre elipsă și hiperbolă."

🖱 **Demo:** A=1, B=2, C=1 → „parabolă rotită, nici măcar grafic de funcție!". B=0 → „cerc". C=−1 → „hiperbolă". Revino → „și iar parabolă — frontiera".

## 12 · TOATE PARABOLELE SUNT ASEMENEA (1 min)

🗣 „Un fapt contraintuitiv, în trei rânduri. **Definiție: o asemănare de raport λ > 0 e o transformare a planului care înmulțește toate distanțele cu λ** — un „zoom" uniform.

**Teoremă: oricare două parabole sunt asemenea.** Demonstrație: pornesc cu y = ax², aplic X = λx, Y = λy; obțin Y = (a/λ)·X². Cu λ = a/a′, parabola „a" devine parabola „a′".

Deci nu există parabole „mai late" sau „mai înguste" — doar văzute mai de aproape sau mai de departe. Ca la cercuri."

🖱 **Demo:** **a** de la 0.25 la 4 — „stânga, fereastră fixă, pare că se schimbă; dreapta, zoom λ = a, identice pixel cu pixel".

## 13 · FINAL (30 sec)

*(pe ecran: „Vă mulțumesc pentru atenție!")*

🗣 „În concluzie: am pornit de la definiția geometrică a parabolei — locul punctelor egal depărtate de focar și directoare — și am studiat aceeași curbă din **șase perspective**: loc geometric, grafic al funcției de gradul al II-lea, oglindă, limită, sumă infinită și conică de frontieră. Șase perspective — o singură parabolă.

Vă mulțumesc pentru atenție! Dacă aveți întrebări, orice grafic se poate deschide pe tot ecranul, cu zoom oriunde."

---

# Întrebări probabile + răspunsuri pregătite

**„De ce ai pornit cu definiția geometrică, și nu cu funcția de gradul II?"**
→ „Pentru că funcția de gradul II acoperă doar parabolele cu axă verticală — un caz particular. Definiția cu focar și directoare include toate parabolele din plan, inclusiv pe cele rotite (vezi conicele, slide 11). Așa graficul devine consecință, nu definiție."

**„De unde formula curburii?"**
→ „Nu folosesc formula generală κ(x). Definesc cercul osculator ca limită a cercului prin trei puncte și deduc doar raza în vârf — un calcul de două rânduri."

**„Ați calculat aria cu integrale?"**
→ „Nu — am folosit chiar metoda lui Arhimede: triunghiuri înscrise plus suma progresiei geometrice infinite."

**„Demonstrați clasificarea conicelor?"**
→ „Enunțul îl admitem — demonstrația completă cere rotația axelor. Dar intuiția e accesibilă: partea de grad II e pătrat perfect exact când B² − 4AC = 0."

**„Ce este p?"**
→ „Distanța de la vârf la focar — sau, echivalent, până la directoare. Pentru y = ax², p = 1/(4a)."

**„De ce trec toate razele prin focar?"**
→ Redau demonstrația în 3 pași: PF = PQ → triunghi isoscel → mediatoarea lui FQ are panta 2at = f′(t), deci e tangenta → unghiuri egale.

**„Toate parabolele asemenea? Și y = 100x²?"**
→ „Da — zoom cu λ = 100 o duce în y = x². Pare mai «îngustă» doar pentru că o privim de aproape. La elipse argumentul cade, pentru că zoom-ul păstrează raportul semiaxelor."

**„Ce surse ați folosit?"**
→ „Lucrarea originală a lui Arhimede, *Cvadratura parabolei*; manualele claselor a IX-a și a XI-a; Wolfram MathWorld; LibreTexts; Wikipedia. Toate demonstrațiile sunt refăcute la nivelul materiei IX–XI, iar graficele sunt construite de la zero pentru proiect."

**Dacă pică o întrebare la care nu știi:**
→ „Demonstrația completă depășește materia tratată în proiect — ideea este [intuiția] — iar marcajul explicit „o admitem" de pe slide arată unde am decis intenționat să mă opresc."

---

# Versiunea comprimată (~11 min)

- 02–04 (definiție geometrică, ecuația, forma algebrică): intacte — sunt cheia rigorii. **4 min**.
- 05 (elementele parabolei): o frază + arăți graficul etichetat. **1 min**.
- 06 (Calculator + cele 6 cazuri): apeși 2-3 preset-uri. **1 min**.
- 07–12 (cele șase perspective avansate): intacte. **~5 min**.
- Demo-uri live obligatorii: **calculatorul cu preset-uri (06), înfășurătoarea (07), cercul osculator cu h → 0 (09), conicele (11)**.
