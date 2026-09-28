# my-portfolio project terv

## Mit tartalmazzon?
- Rövid bemutatkozás és pozíciómegjelölés.
- Válogatott projektek, mindenhol kontextussal, szereppel és eredménnyel.
- Esettanulmányok, nem csak képek.
- Referenciák vagy ügyfélvélemények.
- Szolgáltatások vagy kompetenciák.
- Kapcsolatfelvételi lehetőség, CTA-val.
- Letölthető CV, social linkek és FAQ

## How am I? this is my short bio
Hi, I’m Csaba. I’m an engineering manager at a software development company.

I have a wonderful family: I’m the father of a 17-year-old daughter, Nóra, and a 13-year-old son, Balázs.

I’m an athlete — I train for both my body and my mind.

Sometimes I need to feel the wind on my face and clear my mind. That’s when I ride my Yamaha Tracer 7.


## Projects  impacts

### KKSZB Next - the new channel to get personal data from the state registers








## Ötletek:

### Content
Pozicionálás: Mivel a kkszb mikroszervizes release management tapasztalatod és az EM szerepkör iránti érdeklődésed is megjelenik a hátteredben, érdemes a portfóliót nem sima "frontend fejlesztő" pozícióra, hanem fejlesztő → tech lead/EM irányba növekvő szakember narratívára építeni. Ez megkülönböztet a sablonos junior-portfólióktól.

1. Hero + bemutatkozás
Név, jelenlegi/célszerepkör (pl. "Software Engineer | Release & Delivery fókusszal")
Egy mondatos value proposition: mit tudsz, amit mások nem – pl. multi-környezetes deployment pipeline-ok (INT → UAT-SANDBOX → PROD) kezelése, 10+ mikroszerviz koordinálása
2. Rólam
Fejlesztői háttér + az EM irányba mutató érdeklődés (folyamatszervezés, release management, csapatkoordináció)
Personal touch: motoros túrázás (Szardínia), Economist-olvasás, TABATA/EMOM edzés – ez élővé teszi a profilt, nem csak száraz CV
3. Projektek – esettanulmányokkal (a plans.md "nem csak képek" elve alapján)

Már van 2 konkrét anyagod, amit be tudsz mutatni:

TABATA/EMOM Workout Timer – vanilla JS, önálló HTML fájl, Web Audio API drift-korrigált időzítéssel, animált SVG progress ring, localStorage history. Case study sztori: "beginner-friendly kódbázis, amit utólag bővítettem EMOM prep-timer funkcióval, és Playwright teszthiba alapján debuggoltam."
K&H CSV → Google Sheets automatizáló – Python/pandas/Google API, CLI-first MVP, PyInstaller csomagolás. Ez jól mutatja a backend/automatizálási oldaladat, valós üzleti problémára (háztartási pénzügyek).
Ha van rá mód, egy release management / kkszb pipeline összefoglaló (anonimizálva, cégspecifikus infó nélkül) – ez erősen EM-irányba mutat: hogyan kezelsz komplex, több-környezetes deploy folyamatokat.

Minden projektnél: probléma → megoldás → technológiák → kihívás → eredmény struktúra.

4. Skillek / kompetenciák

Két oszlopban érdemes: technikai (Python, pandas, JS, Google API, Git, CI/CD) és folyamat/vezetői (release management, cross-team koordináció, dokumentáció).

5. GitHub-integráció

Linkeld élőben a tabata-timer demót (GitHub Pages-en könnyen hostolható), plusz a repókat konkrét, informatív leírásokkal.

6. Kapcsolat + CTA

E-mail, LinkedIn, letölthető CV – egyértelmű gomb, ahogy a plans.md-ben is szerepel.

### Style

#### select html element by type, class or ID
Használjuk az összes lehetséges selectort a style ruleset definiálása során.


#### pseudo class
Hasznájunk hozzá pseudo class-okat. Pl. amikor az egeret a linkjeim fölé viszem, akkor színeződjön el. Code snippet:
```css
a:hover {
color: darkorange;
}
```
#### multi class
Használjunk multi class-t is. Vagyis a css file-ban definiáljunk egy ruleset-et egy class-ra, és azt a class-t adjuk hozzá a html file-ban néhány item property-jeként is. 

#### nested elements
vegyünk fel olyan ruleset-et is a css file-ba, amelyben olyan selectort definiálunk, amelyet egy nested element-re mutat rá, pl. egy main alatt egy p type.

#### multiple unrelated selectors
Vegyünk fel olyan ruleset-et is a css file-ba, amely olyan selectort tartalmaz, amely több egymástól független elem stílusát képes definiálni. Itt majd vesszővel elválasztva kell felvenni ezeket a selectorokat a ruleset-hez.  

#### jó példák
https://mattfarley.ca/
https://www.aherriot.com/
https://joshuarogan.com/
https://adambrady.ca/
https://njgerner.com/

A vizsgált oldalakból a következő elemeket érdemes átvenni:
Matt Farley: letisztult hero section, nagy whitespace, erős személyes brand.
Andrew Herriot: vezetői tapasztalat + mérőszámok + projektek kiegyensúlyozott bemutatása.
Joshua Rogan: storytelling és Engineering Leader pozicionálás.
Adam Brady: minimalizmus, rövid szövegek, gyors áttekinthetőség.
Nick Gerner: modern dark/light megközelítés, technológiai hitelesség.
Ajánlott struktúra:
01. Hero
02. About Me
03. Leadership Metrics
04. Experience
05. Featured Projects
06. Skills
07. Writing / Thoughts
08. Contact

#### Design alapelvek
01. Sok whitespace
02. Egyetlen hangsúlyszín
03. Neutral Gray Palette
    --bg: #ffffff;
    --bg-secondary: #f8fafc;
    --text: #0f172a;
    --text-secondary: #475569;
    --border: #e2e8f0;
    --accent: #2563eb;
04. Tipográfia
    Font páros
        Heading
            font-family: "Inter", sans-serif;
        Body
            font-family: "Inter", sans-serif;
05. Méretezés
            h1 {
                font-size: clamp(3rem, 8vw, 5rem);
                font-weight: 800;
                }

            h2 {
                font-size: 2.25rem;
                font-weight: 700;
                }

            h3 {
                font-size: 1.5rem;
                font-weight: 600;
                }

            body {
                font-size: 1.1rem;
                line-height: 1.8;
                }
