<h2>Praktisk del</h2>

Bygg ett Spring Boot projekt där du använder OAuth2 för att hantera autentisering. Man skall kunna autentisera sig mot/med GitHub genom ditt API. Projektet, utöver all autentisering relaterad kod, behöver den bara innehålla en enda endpoint som gör något valfritt, men som bara kan nås om man är autentiserad.
<hr>

<img width="660" alt="FinalForm" src="https://user-images.githubusercontent.com/71407043/201141031-70ca9365-9b56-4336-a19f-8dbab8612c99.png">

<h2>Hur man använder appen</h2>
Boota upp applikationen och gå in på localhost:8080 för att komma åt hemsidan. Där kan du autentisera dig genom ditt github konto tack vare OAuth2.
När du väl har autentiserat dig så kommer hemsidan se annorlunda ut och nu kan du komma åt en annan knapp som kommer länka dig till min endpoint "/user".
Där du får tillbaka ditt namn som du satt i din Github profil i JSON-format från min RestController.
Du kan enbart komma åt den endpointen ifall du är autentiserad.
<hr>

<h2>Vad som "saknas"/ vad man hade kunnat göra bättre</h2>
För demo perspektiv och då det inte är specat i uppgiften så har jag inte gömt client-secret ifall något skulle krabba när du klonar ner projektet. 
Annars hade jag i vanliga fall använt mig av en environment variabel för att gömma detta genom att använda mig av edit configurations och sätta client-secret i en variabel istället för att ha det synligt.
 


