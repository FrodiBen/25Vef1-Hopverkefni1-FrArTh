# Háskóli Íslands, Vefforritun 1, hópverkefni 1, haustið 2025
## Að verkefninu vinna:
- Fróði Benjamín Þrastarson (fbt2@hi.is), FrodiBen á GitHub
- Theódór Helgi Kristinsson (thk105@hi.is), tmaestro75 á GitHub
- Arnold Obas, (air10@hi.is), Arnold Obas á GitHub

## Upplýsingar um verkefni
 - Github link verkefnis er https://github.com/FrodiBen/25Vef1-Hopverkefni1-FrArTh
 - Netlify link verkefnis er https://h1frarth.netlify.app/

## Uppsett scripts
 - Uppsett í verkefni er Stylelint fyrir SCSS og Parcel
 - Verkefni er sett upp með NPM
 - "dev" er script til að setja upp local server með Parcel
 - "build" er script til að setja upp vefsðíðuna, og er það sem að Netlify er látið keyra
 - "lint" lætur lint renna yfir allar .scss skrár
 - "lintfix" reyndir að laga sjálfkrafa villur sem að stylelint greinir

 ## Skipulagning verkefnis
 ### index.html
  - Forsíða vefsíðu
 ### styles.scss
  - Hérna eru scss fælar látnir ganga í röð. Ákveðnir files sem voru bara til hjálpar í hönnun eru commentuð út.
 ### myndir
  - Í þessari möppu geymast myndir fyrir verkefnið.
 ### sidur
  - Hér eru síður verkefnis
 ### styles
 - Hér eru scss files
    - config geymir grunnvariables sem hægt er að nota á allri síðunni
    - reset er reset skjalið
    - utils geymir hjálpar classes
    - grid setti inn grid til þess að bera saman við efnisatriði á síðu. Commentað úr styles.scss
    - Components mappa geymir rest
 ### components
  - Mappa í styles
  - footer og header stylla fót og haus síðu
  - baseline setur upp vídd main elements síðu og grunn stillingar 
  - intro geymir upplýsingar fyrir hvernig eigi að birta intros á síðum, þar eð, myndirnar á toppinum og meðfylgjandi texta
  - gridSections geymir allar upplýsingar fyrir þá parta 


    
