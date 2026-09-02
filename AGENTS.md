# AGENTS.md — Tipicul practic al Duminicii

## 1. Rolul acestui repository

Acest repository NU este în primul rând un proiect software.

Este un proiect editorial, liturgic și documentar pentru construirea unei
cărți practice și complete privind rânduiala slujbelor de Duminică după
Tipicul Sfântului Sava și cărțile liturgice ortodoxe.

Rolul principal al agentului în acest repository este:

1. cercetarea regulilor tipiconale;
2. verificarea informațiilor în sursele proiectului;
3. compararea și corelarea surselor liturgice;
4. redactarea și editarea manuscrisului în limba română;
5. integrarea textului slujbei cu indicațiile tipiconale;
6. menținerea consistenței între diferitele părți ale manuscrisului;
7. identificarea contradicțiilor, lacunelor și informațiilor neverificate;
8. menținerea unei structuri Markdown curate și predictibile.

Nu trata implicit sarcinile din acest repository ca sarcini de programare.

Nu crea scripturi, aplicații, framework-uri, configurații, baze de date,
pipeline-uri sau automatizări decât dacă utilizatorul solicită explicit acest
lucru sau dacă sunt strict necesare pentru o operațiune tehnică cerută.

Fișierele Markdown din `carte/` reprezintă manuscrisul unei cărți, nu
documentație software.

Fișierele din `cercetare/` reprezintă materialul documentar care susține
manuscrisul.


# 2. Obiectivul cărții

Se construiește o carte practică pentru rânduiala completă a ciclului
liturgic:

SÂMBĂTĂ SEARA → DUMINICĂ

cuprinzând:

1. Ceasul al IX-lea;
2. Vecernia;
3. Pavecernița;
4. Miezonoptica Duminicii;
5. Utrenia;
6. Ceasul I;
7. Sfânta Liturghie.

Cartea trebuie să poată fi folosită direct pentru pregătirea și urmărirea
slujbei.

Nu trebuie să fie doar un tratat teoretic despre Tipic.

Textul efectiv al slujbei și instrucțiunile tipiconale trebuie integrate
într-un singur parcurs coerent.


# 3. Domeniul proiectului actual

Proiectul actual privește rânduiala duminicală de bază în perioada în care
funcționează schema Octoih + Minei, inclusiv întâlnirile relevante cu
praznicele fixe.

NU se construiesc în acest repository, în etapa actuală:

- rânduielile proprii perioadei Triodului;
- rânduielile proprii perioadei Penticostarului;
- tipicul general pentru zilele de luni până sâmbătă.

Acestea vor constitui proiecte sau volume separate.

Dacă o sursă consultată conține reguli pentru Triod sau Penticostar, acestea
pot fi folosite pentru înțelegere și verificare, dar nu trebuie introduse în
manuscrisul actual decât dacă utilizatorul cere explicit acest lucru.


# 4. Regula fundamentală

ACURATEȚEA LITURGICĂ ȘI TIPICONALĂ ARE PRIORITATE ASUPRA VITEZEI.

Nu inventa.

Nu completa din memorie o regulă tipiconală atunci când aceasta poate fi
verificată în sursele proiectului.

Nu transforma o presupunere într-o regulă.

Nu transforma practica parohială contemporană într-o regulă a Tipicului fără
o sursă explicită.

Nu generaliza o regulă găsită pentru un caz particular la toate cazurile
asemănătoare.

Nu deduce automat o formulă generală dintr-un singur exemplu.

Dacă informația nu poate fi verificată suficient:

- nu o prezenta drept certă;
- marcheaz-o `[DE VERIFICAT]`;
- explică succint ce anume trebuie verificat;
- indică, dacă este posibil, sursa în care ar trebui căutată confirmarea.

Este preferabil un `[DE VERIFICAT]` explicit unei reguli liturgice inventate.


# 5. Ierarhia surselor

Consultă `SURSE.md` pentru lista concretă a surselor și URL-urilor.

În principiu, sursele au următoarele roluri:

## 5.1. Tipicul

TIPICUL stabilește:

- ce se face;
- când se face;
- ce se combină;
- ce se omite;
- ordinea elementelor;
- numărul stihirilor/troparelor;
- rangurile slujbelor;
- regulile pentru coincidențe;
- regulile pentru praznice;
- regulile pentru hramuri;
- regulile pentru sfinții cu rang diferit.

Pentru stabilirea RÂNDUIELII, Tipicul are prioritate.

## 5.2. Ceaslovul

CEASLOVUL furnizează în principal:

- scheletul slujbei;
- textele fixe;
- rugăciunile și elementele fixe ale Ceasurilor;
- Pavecernița;
- Miezonoptica;
- elementele fixe ale Vecerniei și Utreniei.

Principiu de lucru:

> Ceaslovul dă scheletul slujbei.

## 5.3. Octoihul

OCTOIHUL furnizează materialul variabil al Învierii pentru cele opt glasuri.

Principiu de lucru:

> Octoihul este cartea fundamentală pentru Duminică.

Nu inventa materialul unui glas și nu muta material între glasuri fără
verificarea sursei.

## 5.4. Mineiul

MINEIUL furnizează materialul propriu al sfântului sau praznicului:

- stihiri;
- tropare;
- condace;
- sedelne;
- canoane;
- luminânde;
- stihiri la Laude;
- alte texte proprii.

## 5.5. Psaltirea

PSALTIREA furnizează:

- psalmii;
- catismele;
- stările și alte elemente psalmice necesare.

## 5.6. Calendarul

CALENDARUL ajută la determinarea situației concrete a unei zile:

- data;
- sfântul/sfinții;
- praznicul;
- rangul indicat;
- perioada liturgică;
- eventualele coincidențe.

Calendarul NU înlocuiește Tipicul ca sursă pentru regula de combinare.


# 6. Algoritmul de determinare a unei Duminici

Principiul general al proiectului este:

CALENDAR
→ PERIOADĂ LITURGICĂ
→ GLAS
→ MINEI
→ RANGUL SFÂNTULUI
→ COINCIDENȚĂ
→ TIPIC
→ ALCĂTUIREA SLUJBEI

Cartea trebuie să-l ajute pe utilizator să efectueze acest proces cât mai
simplu.


# 7. Sistemul codurilor tipiconale

Manuscrisul utilizează coduri tipiconale pentru ca utilizatorul să poată
identifica rapid regula care i se aplică.

Codul trebuie întotdeauna scris explicit.

Nu te baza exclusiv pe culoare.


## 7.1. Familia A — rang obișnuit

### A1 — Sfânt simplu / fără rang tipiconal superior

Acesta este cazul de bază.

ATENȚIE:

Nu echivala automat expresiile:

- „sfânt simplu”;
- „sfânt pe 4”.

Dacă Tipicul sau Mineiul utilizează explicit o rânduială „pe patru”,
verifică regula concretă înainte de a o include în A1.

### A2 — Sfânt pe 6

Categorie tipiconală distinctă.

Tipicul are rânduială explicită pentru sfântul care se cântă „pe șase”
atunci când cade Duminica și nu are Polieleu.


## 7.2. Familia B — rang superior

### B1 — Sfânt cu Doxologie

Categorie distinctă.

Nu presupune că B1 este identic cu A2 sau B2.

### B2 — Sfânt cu Polieleu

Categorie tipiconală distinctă, cu rânduială proprie pentru întâlnirea cu
Duminica.


## 7.3. Familia C — Priveghere și Hram

### C1 — Sfânt cu Priveghere

Categorie tipiconală distinctă.

### C2 — Hram de sfânt sau sfântă

Tipicul indică pentru hramul unui sfânt căzut Duminica o legătură directă
cu rânduiala sfântului cu Priveghere căzut Duminica.

Nu presupune însă că fiecare detaliu este identic fără verificarea
contextului.

### C3 — Hram al Maicii Domnului

Este păstrat separat de C2 deoarece Tipicul tratează distinct hramurile
Născătoarei de Dumnezeu.

### Posibil C4 — Hram Domnesc

C4 NU este încă o categorie aprobată.

Nu introduce C4 în manuscris fără verificare și fără decizia explicită a
utilizatorului.

În timpul cercetării trebuie verificat dacă hramul Domnesc necesită o
categorie proprie sau este tratat mai corect în familia E.


# 8. Familia D — modificatori de praznic

Familia D trebuie înțeleasă în primul rând ca familie de MODIFICATORI.

### D1 — Înainte-prăznuire

### D2 — După-prăznuire

### D3 — Odovanie

Aceste coduri se pot combina cu rangurile A/B/C.

Exemple:

`[A2] [D1]`

înseamnă:

Duminică + sfânt pe 6 + înainte-prăznuire.

`[B2] [D2]`

înseamnă:

Duminică + sfânt cu Polieleu + după-prăznuire.

`[C2] [D3]`

înseamnă:

Duminică + hram de sfânt + odovanie.

Nu inventa însă formula liturgică rezultată doar prin „adunarea” regulilor
celor două coduri.

Combinația concretă trebuie verificată în Tipic.


# 9. Familia E — praznicul însuși

### E1 — Praznic Domnesc căzut Duminica

### E2 — Praznic al Maicii Domnului căzut Duminica

ATENȚIE MAJORĂ:

NU utiliza ca regulă universală afirmația:

„Dacă un Praznic Domnesc cade Duminica, slujba Învierii se omite complet.”

Această generalizare nu este acceptată în proiect.

Pentru E1 și E2 trebuie consultată rânduiala proprie praznicului și regula
Tipicului pentru întâlnirea lui cu Duminica.

Păstrarea, modificarea sau omiterea elementelor Învierii se stabilește
pentru cazul concret.


# 10. Codul cromatic

În manuscrisul Markdown codurile rămân textuale.

Culorile vor fi aplicate în etapa de formatare DOCX.

Paleta stabilită este:

| Cod | Culoare | HEX |
|---|---|---|
| A1 | verde deschis clar | #7CB342 |
| A2 | verde închis | #388E3C |
| B1 | albastru deschis | #42A5F5 |
| B2 | albastru închis | #1565C0 |
| C1 | violet | #7E57C2 |
| C2 | violet închis | #5E35B1 |
| C3 | magenta-violet | #AD3E8C |
| D1 | galben-auriu | #F9A825 |
| D2 | portocaliu | #EF6C00 |
| D3 | portocaliu-roșcat | #D84315 |
| E1 | roșu | #C62828 |
| E2 | bordo | #8E244D |

Familiile sunt:

A = verde  
B = albastru  
C = violet  
D = auriu / portocaliu  
E = roșu / bordo

Culorile trebuie să fie vizibile clar pe fundal alb.

În documentul final se vor folosi în principal etichete/pastile/dreptunghiuri
colorate cu codul.

Nu colora paragrafe întregi fără un motiv editorial explicit.

Cartea trebuie să rămână utilizabilă:

- alb-negru;
- în fotocopii;
- de persoane care nu disting toate culorile.

Din acest motiv, codul textual A1, B2 etc. este obligatoriu.


# 11. Principiul editorial al slujbei

Indicația tipiconală trebuie plasată acolo unde utilizatorul are nevoie de ea.

NU construi manuscrisul astfel:

PARTEA I — toate regulile Tipicului
PARTEA II — textul slujbei

În schimb, integrează regulile în parcursul slujbei.

Exemplu conceptual:

## Doamne, strigat-am

[TEXT]
Textul fix necesar...

[TIPIC A1]
Rânduiala pentru A1...

[TIPIC A2]
Rânduiala pentru A2...

[TIPIC B1]
Rânduiala pentru B1...

[TIPIC B2]
Rânduiala pentru B2...

Apoi continuă slujba.

Scopul este ca un utilizator care a determinat că ziua este, de exemplu,
`B2 + D2`, să poată urmări marcajele respective pe tot parcursul slujbei.


# 12. Tipurile de conținut

Manuscrisul trebuie să distingă semantic cel puțin trei categorii principale.


## 12.1. TEXT

Text care se rostește sau se cântă efectiv în slujbă.

Exemplu:

[TEXT]
Doamne, strigat-am către Tine, auzi-mă...


## 12.2. RUBRICA

Indicație privind acțiunea liturgică sau modul de executare.

Exemplu:

[RUBRICA]
Preotul face Vohodul cu cădelnița.


## 12.3. TIPIC

Instrucțiune privind alcătuirea slujbei.

Exemplu:

[TIPIC B2]
Se pun 3 stihiri ale Învierii, 1 a lui Anatolie și 6 ale Sfântului.


# 13. Marcarea surselor în manuscrisul de lucru

În timpul construcției trebuie să fie posibilă identificarea originii unei
reguli importante.

Se poate utiliza:

[SURSA]
Tipic, Seria I, cap. ...

sau o convenție echivalentă stabilită în `REGULI-EDITORIALE.md`.

Nu este obligatoriu ca toate aceste marcaje tehnice să apară identic în
ediția finală.

Ele sunt însă importante în manuscrisul de lucru pentru verificarea
informațiilor.

Pentru reguli tipiconale importante, preferă o referință suficient de
specifică încât informația să poată fi regăsită.


# 14. Marcarea incertitudinilor

Utilizează:

`[DE VERIFICAT]`

pentru informații care necesită confirmare.

Exemplu:

[DE VERIFICAT]
Trebuie verificată rânduiala exactă A2 fără înainte-prăznuire sau
după-prăznuire.

Nu șterge un marcaj `[DE VERIFICAT]` decât după verificarea efectivă a
problemei.

Când problema este rezolvată:

1. introdu regula verificată;
2. adaugă sursa;
3. elimină marcajul `[DE VERIFICAT]`.


# 15. Reguli deja verificate — nu generaliza dincolo de ele

Unele formule au fost deja identificate în cercetarea proiectului.

Ele pot fi utilizate în limitele cazului pentru care au fost verificate.


## 15.1. C1 — sfânt cu Priveghere căzut Duminica

La Vecernia Mare, la „Doamne, strigat-am”:

- 3 stihiri ale Învierii;
- 1 a lui Anatolie / a Răsăritului;
- 6 ale Sfântului;
- Slavă: a Sfântului;
- Și acum: Născătoarea corespunzătoare rânduielii.

Rânduiala completă trebuie verificată în sursă înainte de redactarea
definitivă a secțiunii.


## 15.2. B2 — sfânt cu Polieleu căzut Duminica

La Vecernia Mare a fost verificată aceeași structură principală:

- 3 ale Învierii;
- 1 a lui Anatolie;
- 6 ale Sfântului.

La Sfânta Liturghie a fost identificată formula:

- Fericirile glasului pe 6;
- Cântarea a III-a a canonului Sfântului pe 4.

Verifică sursa înainte de introducerea formei definitive.


## 15.3. A2 — atenție la o generalizare greșită

În cercetarea anterioară a fost găsită formula:

- 3 ale Învierii;
- 3 ale Praznicului;
- 4 ale Sfântului.

Această formulă apărea într-un context care includea explicit materialul
Praznicului.

NU o transforma în formula generală pentru A2.

Rânduiala A2 fără praznic trebuie verificată separat.


# 16. Psaltirea și catismele

Au fost identificate următoarele puncte generale:

- la Vecernia de sâmbătă apare Catisma I;
- la Utrenia Duminicii apar Catismele II și III;
- Polieleul are reguli proprii;
- Psalmul 136 „La râul Babilonului...” apare în anumite perioade;
- la praznice și sfinți mari pot interveni mărimurile și psalmii aleși.

Nu simplifica aceste reguli într-o formulă universală fără verificarea
contextului.


# 17. Cele opt glasuri

Nu duplica întreaga slujbă de opt ori.

Textul fix trebuie păstrat o singură dată.

Materialul variabil al Octoihului trebuie identificat semantic după glas.

Exemplu conceptual:

[OCTOIH GLAS 1]
...

[OCTOIH GLAS 2]
...

etc.

Structura exactă pentru integrarea celor opt glasuri poate fi rafinată pe
măsură ce manuscrisul evoluează.

Prioritatea este evitarea repetării inutile a textului fix.


# 18. Structura repository-ului

Structura recomandată este:

tipic-duminica/
├── README.md
├── AGENTS.md
├── REGULI-EDITORIALE.md
├── CAZURI-TIPICONALE.md
├── SURSE.md
│
├── carte/
│   ├── 00-introducere.md
│   ├── 01-ceasul-9.md
│   ├── 02-vecernia.md
│   ├── 03-pavecernita.md
│   ├── 04-miezonoptica.md
│   ├── 05-utrenia.md
│   ├── 06-ceasul-1.md
│   └── 07-liturghia.md
│
├── cercetare/
│   ├── A1.md
│   ├── A2.md
│   ├── B1.md
│   ├── B2.md
│   ├── C1.md
│   ├── C2.md
│   ├── C3.md
│   ├── D1-D3.md
│   └── E1-E2.md
│
├── surse/
│   └── README.md
│
└── output/
    └── .gitkeep

Nu modifica arbitrar această structură.

Dacă apare necesitatea unei reorganizări majore, explică motivul înainte de
a o executa.


# 19. Separarea cercetării de manuscris

Această regulă este importantă.

`cercetare/` = dovezi, comparații, citate scurte, observații, întrebări,
cazuri-limită, rezultate ale verificărilor.

`carte/` = textul care poate intra efectiv în carte.

Nu transforma fișierele din `carte/` într-un jurnal de cercetare.

Nu umple manuscrisul cu discuții interne despre incertitudini.

Dacă există o problemă:

1. documenteaz-o în `cercetare/`;
2. pune în manuscris `[DE VERIFICAT]` dacă este necesar;
3. rezolvă problema;
4. introdu rezultatul verificat în `carte/`.


# 20. Structura cărții

Ordinea generală urmărită este:

## Partea introductivă

- pagina de titlu;
- scopul cărții;
- domeniul cărții;
- cum se folosește cartea;
- sursele liturgice;
- cum se determină rânduiala Duminicii;
- legenda A1–E2;
- explicația codurilor cromatice;
- mic dicționar tipiconal.

## Slujbele

1. Ceasul al IX-lea;
2. Vecernia;
3. Pavecernița;
4. Miezonoptica Duminicii;
5. Utrenia;
6. Ceasul I;
7. Sfânta Liturghie.


# 21. Construirea fiecărei slujbe

Pentru fiecare moment relevant trebuie să se poată răspunde la întrebările:

1. Ce se face?
2. De unde se ia?
3. Cât se ia?
4. În ce ordine?
5. Ce se schimbă după rang?
6. Ce se schimbă dacă există înainte-prăznuire?
7. Ce se schimbă dacă există după-prăznuire?
8. Ce se schimbă la odovanie?
9. Ce se schimbă dacă praznicul însuși cade Duminica?

Nu introduce artificial toate codurile într-un punct dacă ele nu produc nicio
diferență acolo.

Dacă A1, A2, B1 și B2 au aceeași regulă într-un anumit loc, regula poate fi
grupată, cu condiția să fie absolut clar ce coduri acoperă.


# 22. Checklist pentru Vecernie

La construirea Vecerniei verifică sistematic:

- începutul slujbei;
- Psalmul 103;
- ectenia;
- Catisma I;
- ecteniile;
- „Doamne, strigat-am”;
- numărul stihirilor;
- proveniența stihirilor;
- ordinea stihirilor;
- „Slavă”;
- „Și acum”;
- Vohodul;
- „Lumină lină”;
- Prochimenul;
- Paremiile;
- ecteniile;
- Litia;
- Stihoavna;
- „Acum slobozește”;
- troparele;
- binecuvântarea pâinilor, unde este cazul;
- otpustul și trecerea spre următoarea slujbă.


# 23. Checklist pentru Utrenie

Verifică sistematic:

- începutul;
- cei șase psalmi;
- ectenia;
- „Dumnezeu este Domnul”;
- troparele;
- catismele;
- sedelnele;
- Polieleul;
- mărimurile, unde este cazul;
- Binecuvântările Învierii;
- ipacoi;
- antifoanele glasului;
- Prochimenul;
- Evanghelia Utreniei;
- „Învierea lui Hristos văzând...”;
- Psalmul 50;
- stihirile după Psalmul 50;
- canoanele;
- irmoasele;
- numărul troparelor;
- catavasiile;
- după Cântarea a III-a;
- după Cântarea a VI-a;
- Cântarea a IX-a;
- „Ceea ce ești mai cinstită...” sau înlocuirea ei;
- luminânda;
- Laudele;
- numărul și proveniența stihirilor;
- „Slavă”;
- „Și acum”;
- Doxologia;
- troparele finale;
- ecteniile;
- otpustul;
- Ceasul I.


# 24. Checklist pentru Sfânta Liturghie

Verifică sistematic:

- începutul;
- antifoanele, unde există particularități;
- Fericirile;
- troparele după Vohod;
- condacele după Vohod;
- ordinea troparelor și condacelor;
- Trisaghionul sau înlocuirea lui;
- Prochimenul;
- Apostolul;
- Aliluia;
- Evanghelia;
- Axionul sau înlocuirea lui;
- Chinonicul;
- alte particularități determinate de praznic/rang.


# 25. Stilul limbii

Limba principală a proiectului este ROMÂNA.

Păstrează terminologia liturgică tradițională a surselor.

Nu moderniza arbitrar termenii.

Nu înlocui terminologia Tipicului cu terminologie generică doar pentru a face
textul „mai ușor”.

Explicațiile editoriale trebuie însă să fie clare și practice.

Evită stilul academic inutil de complicat.

Cartea trebuie să fie exactă, dar utilizabilă.


# 26. Ortografie și texte liturgice

Nu corecta automat textele liturgice doar pentru că o formulare pare arhaică
sau neobișnuită.

Dacă textul sursei folosește o formă tradițională, păstreaz-o până când
există o decizie editorială explicită privind normalizarea ortografiei.

Nu amesteca fără avertisment texte provenite din ediții diferite.

Dacă două surse oferă variante diferite:

1. documentează diferența;
2. nu alege arbitrar;
3. solicită o decizie editorială dacă diferența este importantă.


# 27. Citarea și copierea surselor

Când cercetezi, păstrează suficient context pentru ca regula să poată fi
verificată.

Nu folosi fragmente scoase din context pentru a construi reguli generale.

Distinge clar:

- textul exact al sursei;
- parafraza;
- concluzia editorială;
- inferența.

Nu prezenta o inferență ca și cum ar fi citat din Tipic.


# 28. Contradicții între surse

Dacă două surse par să se contrazică:

NU încerca automat să le armonizezi.

În schimb:

1. verifică dacă se referă la același caz;
2. verifică rangul sfântului;
3. verifică perioada liturgică;
4. verifică dacă există praznic;
5. verifică dacă una dintre reguli este pentru zi de rând și alta pentru
   Duminică;
6. verifică ediția și contextul;
7. documentează problema.

Dacă contradicția rămâne:

`[DE VERIFICAT — CONTRADICȚIE ÎNTRE SURSE]`


# 29. Duminica are prioritate contextuală

Nu aplica automat unei Duminici o regulă găsită pentru o zi de rând.

Acest lucru este deosebit de important pentru:

- înainte-prăznuire;
- după-prăznuire;
- odovanie;
- sfinți pe 6;
- Doxologie;
- Polieleu;
- Priveghere.

Dacă sursa descrie luni-vineri sau o zi fără Duminică, nu extrapola fără
confirmare.


# 30. Triod și Penticostar

Dacă în timpul cercetării este găsită o regulă pentru:

- Duminicile Triodului;
- Postul Mare;
- Duminica Floriilor;
- Săptămâna Mare;
- Paști;
- Săptămâna Luminată;
- Duminicile Penticostarului;
- Înălțare;
- Cincizecime etc.,

nu o integra automat în cartea actuală.

Aceste perioade vor avea volume separate.


# 31. Practică monahală versus practică parohială

Cartea actuală urmărește în primul rând TIPICUL COMPLET.

Nu elimina elemente doar pentru că sunt rar întâlnite în practica parohială.

Nu introduce prescurtări parohiale drept normă.

Dacă în viitor se dorește o variantă parohială/prescurtată, aceasta va fi
tratată separat.

Când sursa Tipicului descrie o rânduială monahală completă, păstrează acest
fapt.


# 32. Git și modificarea manuscrisului

Lucrează conservator.

Nu rescrie fișiere mari fără motiv.

Nu șterge cercetarea anterioară doar pentru că ai găsit o formulare mai bună.

Când modifici o regulă deja existentă:

1. verifică de ce fusese introdusă;
2. verifică sursa nouă;
3. caută toate celelalte locuri unde aceeași regulă este folosită;
4. actualizează coerent manuscrisul;
5. evită apariția unor reguli contradictorii în fișiere diferite.

Înainte de modificări structurale mari, inspectează repository-ul.


# 33. Consistența globală

Când stabilești definitiv o regulă pentru un cod, verifică dacă ea afectează
alte secțiuni.

Exemplu:

Dacă cercetarea modifică definiția lui B1, caută toate aparițiile:

`B1`

în:

- `carte/`;
- `cercetare/`;
- `CAZURI-TIPICONALE.md`;
- documentele editoriale relevante.

Nu lăsa definiții divergente ale aceluiași cod.


# 34. Nu optimiza prematur

În etapa actuală prioritatea este:

1. corectitudinea;
2. completitudinea;
3. trasabilitatea surselor;
4. structura semantică;
5. lizibilitatea manuscrisului.

Formatarea tipografică finală în DOCX va fi realizată ulterior.

Nu pierde timp simulând în Markdown aspectul final al paginii Word.

Markdown-ul trebuie să exprime SEMANTICA documentului.


# 35. Viitoarea conversie în DOCX

Manuscrisul va fi transformat ulterior într-o carte DOCX editabilă.

Din acest motiv, folosește consecvent marcajele semantice.

În etapa DOCX vor exista stiluri distincte pentru:

- titluri;
- subtitluri;
- text liturgic;
- rubrici;
- indicații tipiconale;
- surse;
- note;
- codurile A1–E2;
- eventual glasurile Octoihului.

Codurile A1–E2 vor deveni etichete colorate.

Nu introduce soluții Markdown care fac dificilă această conversie.


# 36. Regula pentru răspunsurile agentului

Când utilizatorul cere modificarea manuscrisului:

- inspectează mai întâi fișierele relevante;
- consultă sursele dacă sarcina implică o regulă liturgică;
- efectuează modificarea;
- raportează succint ce ai modificat;
- menționează explicit orice punct rămas `[DE VERIFICAT]`.

Nu răspunde cu planuri lungi dacă sarcina poate fi executată direct.

Nu cere confirmări inutile.

Dacă există suficient context pentru a continua în siguranță, continuă.


# 37. Când trebuie oprită redactarea

Oprește-te și marchează problema dacă:

- regula nu este susținută de sursele disponibile;
- există două interpretări tipiconale semnificativ diferite;
- sursa este incompletă;
- nu este clar dacă regula privește Duminica;
- nu este clar rangul sfântului;
- aplicarea regulii ar necesita o presupunere importantă;
- ar trebui creată o categorie tipiconală nouă;
- ar trebui modificată definiția A1–E2;
- ar trebui schimbată arhitectura fundamentală a cărții.

În aceste situații nu lua singur o decizie editorială majoră.


# 38. Principiul final

Scopul cărții este ca utilizatorul să poată determina înaintea slujbei cazul
tipiconal, de exemplu:

`B2 + D2`

și apoi să poată parcurge întreaga slujbă urmărind acele marcaje, fără să fie
nevoit să reconstruiască singur rânduiala din Tipic, Ceaslov, Octoih și Minei.

Fiecare secțiune trebuie construită având acest scop în vedere.

Formula de lucru a întregului repository este:

VERIFICĂ → DOCUMENTEAZĂ → REDACTEAZĂ → VERIFICĂ DIN NOU

iar regula absolută este:

NU INVENTA O RÂNDUIALĂ LITURGICĂ.