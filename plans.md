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

## Style execution plan (beginner-friendly)

Work through these steps in order. Make one small change at a time, save the file, refresh the browser, and check the result before moving on. Keep the first visual pass focused on the content already in the page; add missing portfolio content later, using only accurate information.

1. **See the starting point.** Open `index.html` in a browser and note what is already present and what feels unfinished. Keep the page open so you can compare each change.
    - Done when: you can see the current layout and identify the About, Projects, and Contact sections.

2. **Fix the HTML foundation.** In `index.html`, correct the stylesheet path to `css/style.css`, put its link in the document head, close the hero paragraph, and make sure the page has a viewport declaration. Keep the existing section IDs so navigation links continue to work.
    - Done when: the stylesheet loads and the navigation still jumps to the right sections.

3. **Set the visual basics.** In `css/style.css`, define a restrained palette using the neutral colors and single accent above. Add CSS variables for repeated colors and spacing, choose a readable font stack, and set a comfortable line-height.
    - Done when: text is easy to read and colors look consistent, even before adding decorative details.

4. **Set content width and spacing.** Center the page content, limit the width of long text, and use consistent space between sections. Start with moderate values rather than fixed heights or very large margins.
    - Done when: paragraphs are comfortable to read on desktop and sections feel clearly separated.

5. **Style the header and navigation.** Make the existing links easy to scan and space them clearly. Add both a hover state and a visible keyboard-focus state.
    - Done when: links are easy to find, work when clicked, and show a clear indicator when you press Tab.

6. **Build a clear hero.** Make the name, role, and supporting sentence visually distinct. Constrain the paragraph width and make the main heading adjust to screen size with a responsive CSS value such as `clamp()`. Use the current truthful copy; do not invent metrics.
    - Done when: a visitor can quickly understand who the site is about and what they do.

7. **Style the existing sections consistently.** Give About and the other section headings a shared size and spacing system. Keep Projects, Skills, and Contact simple until their content is ready; avoid designing detailed cards for information that is not there yet.
    - Done when: all existing sections feel like parts of one page.

8. **Practice the CSS selectors from this plan.** Use element selectors for defaults, classes for reusable styles, IDs for existing one-off sections, and grouped selectors when elements share a rule. Use nested or multi-class selectors only when they make a real style easier to express. Include `:hover` and `:focus-visible` link states.
    - Done when: each selector has a clear purpose and you can see which HTML elements it affects.

9. **Check the mobile layout.** Narrow the browser to about 375px. Adjust navigation spacing, section padding, heading size, and any columns that feel cramped. Add a media query only when the layout needs a different arrangement on a smaller screen.
    - Done when: there is no sideways scrolling, clipped text, or crowded navigation. Recheck the page at desktop width afterward.

10. **Polish and verify.** Check color contrast, consistent spacing, all link destinations, and keyboard navigation at both mobile and desktop widths. In a later content pass, add truthful project case studies (problem, role, approach, challenge, result), skills, and working contact/social/CV links.
     - Done when: the page looks coherent at both sizes and every visible interaction works. Do not present placeholder achievements, testimonials, or project outcomes as facts.
