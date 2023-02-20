## Omschrijving van de opdracht

In deze opdracht moeten we een examensysteem concurrent maken. Het loopt nu sequentieel maar moet middels threads en locks concurrent draaien waardoor het sneller gaat dan de sequentiële versie. 

Er zijn drie bestanden belangrijk.
- Program.cs trapt het programma af (dit start je door `dotnet run` te typen in de folder van het programma)
- Quiz.cs draait de sequentiële versie van het examen
- ConcQuiz.cs is de concurrent versie van het examen. Deze is nu niet geïmplementeerd, het is aan ons om dat te doen.

In het PDF-bestand van de opdracht staat nog meer uitgelegd over de opdracht. 


Onze TODO bestaat uit: 
- Het toepassen van concurrency (`threads` en `locks`)
- Zorgen dat het hiermee sneller is dan de sequentiële versie


### PROTIPS
- Verander de waardes in Program.FixedParams naar een kleiner aantal zodat de quiz niet eeuwig lang duurt. Ik heb zelf alles `* 0.1` gedaan zodat het hooguit een paar seconden duurt
- Let erop dat we geen async/await mogen gebruiken (zoals in de opdrachtomschrijving vermeld)
