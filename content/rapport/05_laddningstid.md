---
---
Webbshops online - laddningstid och användbarhet
=======================
Jag har valt att prova laddningstiden på några välkända märken online, på deras webbshoppar.
Då jag tycker det är intressant att se på märken som har resurser till att skapa stora webbplatser lägger tid på laddningshastigheten.


Urval
-----------------------

1. Prada : http://www.prada.com/en/e-store.html
2. Dolce & Gabbana : https://store.dolcegabbana.com/en/
3. Hugo Boss: https://www.hugoboss.com/women-clothing/


Metod
-----------------------
Jag har använt PageSpeed Insights på de olika webbplatserna för att se och jämföra laddningstiderna. Detta verktyg erbjuder en analys med möjlighet att gå djupare in i resultatet. En färgad cirkel indikerar ifall webbplatsen räknas som snabb eller ej, o längre ner på sidan så ges en analys som kan användas för att nå en ännu högre hastighet, samt att se vad som i nuläget fungerar.
Ett enkelt verktyg att använda för att förstå och att förbättra en webbplats.

Jag har också läst Moz.com (samt övriga rekommenderade artiklar ifrån kursen) översiktligt för att få en bättre idé om uppladdningshastighetens roll för en webbsida samt vilka faktorer som påverkar den, för att bättre kunna analysera webbplatser som t ex dessa i denna rapporten.

SEO rankningen är viktig för en webbsida för att den enkelt ska gå o hitta i uppsjön av webbsidor som finns på internet. Hastigheten som det tar för o ladda upp sidan spelar roll i rankningen, ju snabbare ju fler sidor hinner sökmotorens 'crawlers' gå igenom inom deras tidsbudget. Det nämns också att uppladdningshastigheten troligtvis används som faktor för att ranka sidorna.

Andra faktorer som spelar roll för sidans hastighet är:
- Filstorlekar
- Omdirigering av adress
- Cache
- JS filernas rendering
- Serverns tid att svara
- Användning av CDN (Att filer sparas fysiskt för lokalare tillgång)
- Bild optimering
- Prioritera synligt innehåll

(Läs mer på MOZ sida)

Resultat
-----------------------
<img src="img/analyzeThis/hugo_boss.png" width=300 alt="hugo_boss">
<img src="img/analyzeThis/prada.png" width=300 alt="prada">
<img src="img/analyzeThis/d&g.png" width=300 alt="d&g">

Jag tittade främst på möjligheterna och nämner nedan vad som behövs korrigeras.

Prada - Prada fick resultatet långsamt/genomsnittligt - 5 på skalan på mobilen och 73 på daton. Den främsta anledningen var att resurser blockerar renderingen, dvs att JS filer laddas upp innan hela sidan renderas. Den andra anledningen för ökad långsamhet är formatet på bildfiler. PNG och JPEG rekommenderas inte, utan istället mer moderna bildformat som JPEG 2000, JPEG XR och WebP. Optimering av bilder bör också genomföras, inläsning av viktiga resurser i förväg, samt att använda bilder i rätt storlek.

D&G - Dolce & Gabbana hamnade också på den röda/gula delen av mätaren - 6 på skalan på mobilen och 74 på datorn. Här var den främsta anledningen till den höga uppladdningshastigheten relaterat till bilderna. Det krävs även modernare bildformat samt videoformat, det krävs att använda bilder med rätt storlek samt att skjuta upp inläsningen av bilder som inte visas på skärmen.

Hugo Boss fick betydligt mkt bättre, trots att de hamnade på den röda delen av skalan på mobilen så kom de upp på den gröna på datorn, 38 på mobilen och 93 på datorn. Främsta anledningen är att resurser som blockar renderingen bör tas bort - alltså JS skripten. Samt att CSS som inte används bör skjutas upp. Några mobilanmärkningar på bilder som bör skjutas upp då de inte visas på skärmen, att viktiga resurser ska läsas in i förväg samt att moderna bildformat efterfrågas.

Kalkyl:
<a href='https://docs.google.com/spreadsheets/d/14SNfu-sgTb5gtBjNnzto3UoY03hsNUi9UCYgz6-PB88/edit#gid=0'> PageSpeed Insights </a>




Analys
-----------------------
Alla tre sidorna är troligtvis påkostade och hamnar högt i sökningarna. Men de är ju mycket kända och har de andra SEO faktorerna. Som det nämns i artiklarna så är det möjligt att hamna högt upp i rankningarna utan hög uppladdnings hastighet. Så dessa är alla exempel på det. O trots att de hamnar i det röda fältet så är det inte alls störigt då sidorna öppnas.
Men sökmotorerna utför ju klart deras uppgifter i en hastighet som är svår för oss att ens föreställa oss.

Den gemensamma nämnaren för efterfrågade snabbhetsuppdateringar är angående bilderna. Det krävs att arbeta med modernare format och bildoptimering. Rätt storlek på bild i passande format gör alltså sidorna bra mycket bättre. Renderingen av JS filerna är också återkommande som anledning - det handlar om att innan själva html-trädet visas så läses även JS-filerna i Att det klagas på av snabbhetsexperten betyder att det kan vara idé att bygga upp en annan struktur för att läsa in JS-filer, eller lägga dem längre ner på sidan så att innehållet först visas. Detta är inte korrekt enligt JS standards vad jag förstått (att lägga JS-sidorna sist - vilket som också kan ge problem om JS-inläsningen behövs för sidans effekter). Men något annat sätt att vänta med inladdningen av JS filerna tills sidan renderats är bra idé att tänka ut. Kanske skräddarsy efter varje sidas exakta behov.

Sidans uppladdningshastighet för användarens upplevelse beskrevs som viktig i artiklarna. Det är inte svårt att förstå, i detta moderna samhälle som går i hög takt. Så att ta hänsyn till dessa faktorer som tydligt beskrivs tycks i tid och strategiskt smart för att driva en framgångsrik webbplats, även om det ändå är innehållet som är det viktigaste.

Jag väljer att sikta på det gröna fältet, så det gäller att skapa webbplatser med det som mål. I dessa tester var det bara Hugo Boss som klarade testet, och då enbart på datorns sida.


Referenser
-----------------------

https://developers.google.com/speed/docs/insights/rules

https://developers.google.com/speed/pagespeed/insights/

https://webmasters.googleblog.com/2018/01/using-page-speed-in-mobile-search.html

https://moz.com/learn/seo/page-speed


Övrigt
-----------------------

Ylva Sjölin, 2018
