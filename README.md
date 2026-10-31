# Kemi 1 – Materiaprov

Övningsprov för Kemi 1, materia (delprov 1, nivå E–C). Svara med egna ord eller ett tal, jämför med facit och rätta själv.

Hela sidan ligger i `index.html` och behöver ingen server eller inloggning.

## Välj vad du vill öva på

På startsidan kryssar du i vilka områden du vill öva på (atomen, elektroner och atommodeller, periodiska systemet, materia och blandningar, kemisk bindning, laboration och arbetssätt) och väljer läge och antal frågor. Frågorna dras bara från de områden du har valt. Har de valda områdena färre frågor än 10 eller 20 tonas de alternativen ned, och då tas alla frågor i områdena med. Valen sparas i webbläsaren på din egen enhet och går inte att nå av någon annan. Provet innehåller både uppgifter och begreppsfrågor, till exempel "Vad menas med sublimering?". Frågorna följer planeringen fram till E/C-provet. Bindningar mellan molekyler (vätebindning, dipol-dipolbindning, van der Waals-krafter) och löslighet kommer efter det provet och finns därför inte med bland frågorna, men Joels AI-hjälp kan förklara dem.

## Begreppskort

Fliken Begreppskort har kort för alla begrepp i arbetspaketet, grupperna i periodiska systemet, de 20 första grundämnena, sammansatta joner och lågfärger. Varje begreppskort har en förklaring för E och ofta en fördjupning för C. Man kan vända kort, se förklaringen först, skriva svaret (det rättas direkt och små stavfel godkänns) eller para ihop. Kort man inte kan kommer tillbaka i omgången, och vad man kan sparas i webbläsaren. Lösningar och bindningar mellan molekyler är en egen lek som inte är vald från början, eftersom den delen kommer efter E/C-provet.

## Läs

Fliken Läs har en sammanfattning med egna ord av genomgång 2–5 och arbetspaketet, i samma ordning som lektionerna. Varje avsnitt har knappar som startar korten för det avsnittet, och sist finns en checklista. Lärarens egna bilder och texter ligger inte på sidan.

## Joels AI-hjälp och feedback

Knappen "Joels AI-hjälp och feedback" ligger kvar nere till höger på alla skärmar (och finns också längst ned på sidan). Den öppnar en ruta med två flikar.

**Fråga.** Joels AI-hjälp svarar på frågor om kemin direkt i webbläsaren, med en inbyggd sökning över färdiga förklaringar och några räknare (till exempel molekylmassa, antal neutroner och valenselektroner). Den är ingen AI-chatt och ingen språkmodell som skriver egna svar: det finns ingen server, ingen API-nyckel och inga kostnader, och det som skrivs i frågefältet lämnar aldrig sidan. Bara frågor om Kemi 1 – materia besvaras. Allt annat får svaret att det ligger utanför.

**Feedback.** Meddelanden sparas i tabellen `feedback` i Supabase (gratisplanen). Besökare kan bara lägga till rader, med typ, meddelande och eventuellt id på den fråga det gäller. De kan inte läsa, ändra eller ta bort något, varken feedback eller sidan. Läs meddelandena i Supabase under projektet `kemi1-feedback`, Table Editor, `feedback`.

## Se om någon har varit inne

Sidan räknar bara besök: en rad med tidpunkten varje gång någon öppnar den. Inget sparas om vem besökaren är (inga kakor och inget id), och robotar och automatiska tester räknas inte. Längst ned på sidan står att den räknar besök.

Se siffrorna i Supabase under projektet `kemi1-feedback`, Table Editor, vyn `besok_per_dag` (en rad per dag med kolumnerna `besok`, `mina_besok` och `andras_besok`). Varje enskilt besök finns i tabellen `besok`.

Dina egna besök märks som dina om du öppnar sidan en gång med `?mina-besok` sist i adressen, i varje webbläsare du använder: https://homerun5320.github.io/kemi1-materiaprov/?mina-besok. Med `?inte-mina-besok` tas märkningen bort.

Nycklarna i `index.html` är de publika nycklarna, som är gjorda för att ligga i en webbsida. De ger bara rätt att lägga till feedback och besöksrader, inte att läsa eller ändra något.
