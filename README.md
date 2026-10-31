# Kemi 1 – Materiaprov

Övningsprov för Kemi 1, materia (delprov 1, nivå E–C). Svara med egna ord eller ett tal, jämför med facit och rätta själv.

Hela sidan ligger i `index.html` och behöver ingen server eller inloggning.

## Fråga eller ge feedback

Knappen "Fråga eller ge feedback" ligger kvar nere till höger på alla skärmar (och finns också längst ned på sidan). Den öppnar en ruta med två flikar.

**Fråga.** Frågor om kemin besvaras direkt i webbläsaren, med en inbyggd sökning över förklaringar och några räknare (till exempel molekylmassa, antal neutroner och valenselektroner). Det är ingen AI-tjänst: det finns ingen server, ingen API-nyckel och inga kostnader, och det som skrivs i frågefältet lämnar aldrig sidan. Bara frågor om Kemi 1 – materia besvaras. Allt annat får svaret att det ligger utanför.

**Feedback.** Meddelanden sparas i tabellen `feedback` i Supabase (gratisplanen). Besökare kan bara lägga till rader, med typ, meddelande och eventuellt id på den fråga det gäller. De kan inte läsa, ändra eller ta bort något, varken feedback eller sidan. Läs meddelandena i Supabase under projektet `kemi1-feedback`, Table Editor, `feedback`.

Nycklarna i `index.html` är de publika nycklarna, som är gjorda för att ligga i en webbsida. De ger bara rätt att lägga till feedback.
