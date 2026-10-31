# Kemi 1 – Materiaprov

Övningsprov för Kemi 1, materia (delprov 1, nivå E–C). Svara med egna ord eller ett tal, jämför med facit och rätta själv.

Hela sidan ligger i `index.html` och behöver ingen server eller inloggning.

## Välj vad du vill öva på

På startsidan kryssar du i vilka områden du vill öva på (atomen, elektroner och atommodeller, periodiska systemet, materia och blandningar, kemisk bindning, laboration och arbetssätt) och väljer läge och antal frågor. Frågorna dras bara från de områden du har valt. Har de valda områdena färre frågor än 10 eller 20 tonas de alternativen ned, och då tas alla frågor i områdena med. Valen sparas i webbläsaren på din egen enhet och går inte att nå av någon annan. Provet innehåller både uppgifter och begreppsfrågor, till exempel "Vad menas med sublimering?".

## Joels AI-hjälp och feedback

Knappen "Joels AI-hjälp och feedback" ligger kvar nere till höger på alla skärmar (och finns också längst ned på sidan). Den öppnar en ruta med två flikar.

**Fråga.** Joels AI-hjälp svarar på frågor om kemin direkt i webbläsaren, med en inbyggd sökning över färdiga förklaringar och några räknare (till exempel molekylmassa, antal neutroner och valenselektroner). Den är ingen AI-chatt och ingen språkmodell som skriver egna svar: det finns ingen server, ingen API-nyckel och inga kostnader, och det som skrivs i frågefältet lämnar aldrig sidan. Bara frågor om Kemi 1 – materia besvaras. Allt annat får svaret att det ligger utanför.

**Feedback.** Meddelanden sparas i tabellen `feedback` i Supabase (gratisplanen). Besökare kan bara lägga till rader, med typ, meddelande och eventuellt id på den fråga det gäller. De kan inte läsa, ändra eller ta bort något, varken feedback eller sidan. Läs meddelandena i Supabase under projektet `kemi1-feedback`, Table Editor, `feedback`.

Nycklarna i `index.html` är de publika nycklarna, som är gjorda för att ligga i en webbsida. De ger bara rätt att lägga till feedback.
