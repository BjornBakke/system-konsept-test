# system-konsept-test
Testøkt - modulært system med «bundet kontekst», «aggregert domene root»  der 
«infrastruktur»  og «web» betraktes som detaljer.
 
 
 Hypotese:
  I stedet for å modellere problemdomenet (og arbeidsflyten) som en sekvens av hendelser som til slutt setter databasen i en tilstand der «problemet» anses som løst, ønsker vi her å «modellere» domenet slik at et sett med kjente «fakta» påføres modellen slik at man kan stille spørsmålet:
 -	Dette er hva vi har, er det korrekt?
 -	Hvis ikke fyll inn korrekte verdier!
 

 Eksempel: en sak opprettes i et system. Systemets applikasjonslogikk beskriver hvordan alle eksterne systemer av interesse bes returnere informasjon interessant for det spesifikke tilfellet.
 Det oppsatte domenet returneres til klienten. 
 
 Mangler forventninger fra eksternt system, vises som «ikke tilfredsstilte domene kriterier» på domenemodellen.
 
 …
 

 

