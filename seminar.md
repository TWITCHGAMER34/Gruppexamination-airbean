# Seminarium Frågor

---

## Svar på frågor från seminariet

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
    * x

---

6. Hur ändras ton, pedagogik och detaljnivå? Känns svaret mer eller mindre hjälpsamt? Diskutera varför.
    * x

---

7. Finns skillnader? Isåfall beskriv dessa i struktur, förklaring och detaljer.'
    * x

---

8. Diskutera också när det inte är okej: bedömningsuppgifter, inlämningar som ska visa egen förståelse eller moment där
   ni ska kunna resonsera själva.
    * x

---

9. Förutom risken för fusk — vilka är de största fallgroparna? T.ex. felaktig kod, bristande förståelse eller
   överberoende.
   Motivera era val.
    * x

---

10. Vilka fördelar ser ni med att använda GitHub Copilot när man kodar? Vilka risker finns det, särskilt i början av er
    lärprocess?
    * x

---

11. Fundera över vilka delar av studierna som skulle må bra av automatisk hjälp (kommentarer, boilerplate, små
    repetitiva moment) och vilka delar som kräver egen förståelse.
    * x

---

12. Vad lockar mest med Copilot? Är det snabbheten, förslagen, strukturen eller något annat?
    * x

---

13. Diskutera hur ni ser på framtidens utvecklarroll. Kommer AI att förändra arbetsuppgifter, men inte nödvändigtvis ta
    bort dem? Hur kan en utvecklare bli mer värdefull genom att förstå och styra AI?
    * x

---

14. Vilka risker trr ni finns med AI-genererad kod i yrket? T.ex. säkerhet, felaktigheter, licenser, teknisk skuld.
    * x

---

15. Leta upp tre andra AI-verktyg som är relevanta för utvecklare — exempelvis inom dokumentation, design, testning,
    debugging eller datastrukturering. Skriv 3–4 meningar om varje.
    * x

---

16. Av alla verktyg ni testat eller läst om i kompendiet: vilket tror ni att ni skulle ha mest nytta av som studerande,
    och som yrkesverksamma? Motivera gärna med situationer eller exempel.
    * x

---