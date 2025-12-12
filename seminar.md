# Seminarium Frågor

---

## AI och datalogiskt tänkande

---

1. Jämför svaren. Vad betonar verktygen annorlunda? Hur påverkar deras olika skrivstilar er uppfattning om processen?
    * ChatGPT är strukturerad och pedagogisk. Tydligt uppställda svar med lättöverskådliga punktlistor.
      Aizo är lite mer lättsam och mer vägledande. Ställer motfrågor till mig som användare för att få igång ett
      resonemang.

---

2. Hur skiljer strukturen sig? Är någon pseudokod mer detaljerad, mer generell eller mer teknisk?
   Klistra in en av versionerna och skriv vilken tjänst den kommer från.
    * ### Pseudokod:
   ```
        START

        // 1. Identifiera stämning
          stämning ← fråga_användaren("Vad är du sugen på? (rolig, spännande, lugn, etc.)")

        // 2. Välj genre baserat på stämning
          genre_lista ← välj_genrer(stämning)

        // 3. Filtrera efter tillgänglig tid
          tid ← fråga_användaren("Hur mycket tid har du?")
          filmer ← filtrera_filmer_efter_längd(genre_lista, tid)

        // 4. Sortera efter betyg
          filmer ← sortera_efter_betyg(filmer)

        // 5. Välj topp 3 kandidater
          kandidater ← välj_topp(filmer, 3)

        // 6. Visa trailer eller beskrivning för varje kandidat
          för varje film i kandidater:
          visa_trailer(film)

        // 7. Användaren tar bort den minst intressanta filmen
          bortvald ← fråga_användaren("Vilken film lockar minst?")
          kandidater ← ta_bort(kandidater, bortvald)

        // 8. Slutval
          slutval ← fråga_användaren("Vilken av de två kvarvarande filmerna vill du se?")

        visa("Du ska se: " + slutval)

        END
      ```
    * ### **Svar**:
        * ChatGPT är mer detaljerad och utförlig. Aizo är mer vägledande, man får inte en färdig produkt. Vilket är
          förståeligt då Aizo är inställd på att vara vägledande.

---

## AI som studiekamrat

---

3. Var tror ni svårigheterna uppstår? Handlar det om logik, kontext, teknikval eller något annat?
    * Tyvärr kan vi inte ens resonera runt ett svar på denna fråga. Det ligger bortom våra kunskaper, men vi bad ChatGPT
      själv svara på frågan och fick följande summering:
        * “De största svårigheterna är inte algoritmer eller kodgenerering – det klarar AI:n bra.
        * Utmaningarna ligger i:
            * Kontextbegränsningar – AI ser bara det du visar.
            * Implicit logik – arkitekturbeslut och systemregler ligger ofta utanför texten.
            * Externa beroenden – API:er, DOM, miljöer, som AI inte kan köra eller testa.
            * Versions- och konfigurationsdetaljer – små skillnader som får stora effekter.”

---

4. Be båda förklara vad som händer. Jämför språket, noggrannheten och nivån på beskrivningen.
    * ChatGPT är mer detaljerad och utförlig, lite mer teknisk text uppställd i punktform. Aizo håller det mera
      kortfattat, beskriver mer med text istället för att ge tekniska exempel.

---

5. Varför tror ni att ChatGPT skickade tillbaks ursprungskoden ett par steg in i felsökningen? Varför tror ni att
   ChatGPT använde sig av ett utdaterat sätt att hantera databasuppkopplingen?
    1. Ett problem kanske kan vara att man inte promptat på ett bra sätt. Alltså användarrelaterat. Kanske också kan
       vara så att AI:n “glömt” vad som är ursprungskoden och skickar tillbaka den i tron om att den är ny -
       minnesrelaterat.
    2. Det kan bero på modellens träningsdata, begränsad kontext och att AI ofta använder gamla lösningar som den lärt
       sig fungerar.

---

6. Hur ändras ton, pedagogik och detaljnivå? Känns svaret mer eller mindre hjälpsamt? Diskutera varför.
    * Efter att ha anpassat profilen efter exemplet i uppgiftsbeskrivningen får man ett något enklare och kortare svar.
      Det ges även fler konkreta exempel och liknelser för att förenkla. Känns lite mer hjälpsamt när det är vänligare
      ton, känns mänskligare. Men samtidigt kanske inte riktigt lika fullödigt svar.

---

7. Finns skillnader? Isåfall beskriv dessa i struktur, förklaring och detaljer.'
    * Ja, det är stor skillnad. Med anpassningen får man ett vägledande svar och utan får man helt enkelt färdig kod i
      Python och Javascript.
    * Med anpassat svar får man ett välstrukturerat svar i numrerade punkter. Det får en att själv tänka till hur man
      ska gå till väga för att koda.
    * Utan anpassning är det lite mer pang på rödbetan en färdig lösning.

---

8. Diskutera också när det inte är okej: bedömningsuppgifter, inlämningar som ska visa egen förståelse eller moment där
   ni ska kunna resonsera själva.
    * AI är väldigt bra som bollplank, att diskutera problem och lösningar. Ett väldigt kraftfullt verktyg vid inlärning
      om det används på ett bra sätt.
    * Det kan vara bra att använd AI för de moment som kanske bara tar energi så man kan lägga fullt fokus på det som är
      roligt. T ex använda AI för att skriva pseudokod så man kan fokusera på att koda. Och till att effektivisera
      repetitiva uppgifter.
    * Sen är det ju väldigt osmart att använda AI för att fuska sig till färdiga lösningar som man själv inte kan
      förklara eller förstå.

---

9. Förutom risken för fusk — vilka är de största fallgroparna? T.ex. felaktig kod, bristande förståelse eller
   överberoende.
   Motivera era val.
    * De tre exemplen som anges i frågan är väl de största fallgroparna? Sen går de in i varandra litegrann - felaktig
      kod leder till bristande förståelse.
    * Om man bra genererar kod - vilket kan vara användbart ibland och begränsade fall - så har man ingen aning om var
      problemen finns om det börjar krångla.
    * Och visst finns en stor risk för ett beroende. Därför är vi ganska restriktiva i att använd AI i vår grupp.

---

## AI som kodkompis

---

10. Vilka fördelar ser ni med att använda GitHub Copilot när man kodar? Vilka risker finns det, särskilt i början av er
    lärprocess?
    * CoPilot gör en effektivare och snabbare. Däremot finns risk för att man inte har full förståelse för vad som
      genereras, vilket kan leda till problem när projektet växer i storlek och komplexitet.
    * Men om man kan koda och gör det dagligen så är det ett fantastiskt verktyg.
    * Vid inlärning kan CoPilot vara ett hinder då man får lösningen direkt, man behöver inte tänka själv.

---

11. Fundera över vilka delar av studierna som skulle må bra av automatisk hjälp (kommentarer, boilerplate, små
    repetitiva moment) och vilka delar som kräver egen förståelse.
    * AI kan användas för att generera enklare HTML och CSS vid behov, särskilt när det huvudsakliga är något annat,
      exempelvis JavaScript.
    * Förutsatt att man förstår den enklare koden man får ser vi inget problem med att låta AI producera den.
    * Att använda AI till boilerplate (alltså återkommande kod?) är väl lockande, men man måste ju fortfarande ha
      förståelse för vad den gör. Än en gång nåt man kan använda sig av när man jobbat med kod ett tag och kan det - då
      kan det vara ok för att spara både tid och humör.

---

12. Vad lockar mest med Copilot? Är det snabbheten, förslagen, strukturen eller något annat?
    * Främst är nog snabbheten och förslagen, man får direkt förslag på sin påbörjade kodrad och kan slutföra den med
      ett tryck. Vilket är väldigt smidigt och sparar tid – men man kan fakturera desto mer!

---

## AI i yrkeslivet

---

13. Diskutera hur ni ser på framtidens utvecklarroll. Kommer AI att förändra arbetsuppgifter, men inte nödvändigtvis ta
    bort dem? Hur kan en utvecklare bli mer värdefull genom att förstå och styra AI?
    * AI kommer absolut förändra sättet man jobbar på. Kan man koda i grunden och förstår hur man använder AI för att
      effektivisera arbetsflödet så kommer utvecklaren kanske till och med bli ännu mer värdefull för företaget hen
      jobbar på.

---

14. Vilka risker trr ni finns med AI-genererad kod i yrket? T.ex. säkerhet, felaktigheter, licenser, teknisk skuld.
    * Det finns som sagt risk för att man inte har full förståelse för vad som genereras av AI, vilket kan leda till
      problem när projektet växer i storlek och komplexitet (teknisk skuld).
    * Det är alltid användaren av AI som ansvarar för koden som produceras.
    * Det kan även vara svårt för AI att alltid ta full hänsyn till projektets kontext vad gäller exempelvis säkerhet.

---

## AI generellt

---

15. Leta upp tre andra AI-verktyg som är relevanta för utvecklare — exempelvis inom dokumentation, design, testning,
    debugging eller datastrukturering. Skriv 3–4 meningar om varje.
    * **Figma Make** - ett AI-verktyg för att generera prototyper/appar från textbeskrivningar. Verktyget effektiviserar
      och påskyndar designprocessen genom att snabbt ta fram designförslag. Här kan man även använda delar av
      designförslagen och jobba vidare med, plocka russinen ur kakan så att säga.
    * **GitHub Copilot** - Hjälper utvecklare att skriva kod snabbare genom att föreslå rader eller hela funktioner
      direkt i editorn. Det kan också förklara kod och bidra med idéer på hur något kan lösas. Man kan även prompta
      direkt i editorn.
    * **Testim (AI-driven testning)** - använder AI för att skapa och underhålla automatiserade tester för
      webbapplikationer. Det försöker göra tester mer stabila genom att själv anpassa sig när UI-element ändras. På så
      sätt minskar mängden manuellt arbete som krävs för att hålla testerna fungerande.

---

16. Av alla verktyg ni testat eller läst om i kompendiet: vilket tror ni att ni skulle ha mest nytta av som studerande,
    och som yrkesverksamma? Motivera gärna med situationer eller exempel.
    * Vad gäller mer allmänna frågor känns ChatGPT bäst, svaren kan ibland vara lite väl långa och utförliga, men oftast
      får man bra svar. Fungerar bra att använda som bollplank.
    * I arbetet längre fram i tiden är nog GitHub Copilot mycket användbar. Men bara när man kommit såpass långt att man
      kan sin kod såklart.

---