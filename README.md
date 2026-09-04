Varför flexbox?

- För att jag ska kunna styra layouten av korten utan att behöva räkna om procentsatser etc hela tiden.

Varför inte grid?

- Grid är till för om vi har rader och kolumner samtidigt, vilket vi inte har i detta paketet.

Feedback:
FEEDBACK: display: flex är skrivet som inline style → flytta till en class på containern i CSS-filen.
FEEDBACK: display: flex på ett enskilt .card → flex hör hemma på containern, inte på varje enskild child.
FEEDBACK: varje kort är en div och luften är margin: 20px → gör istället korten till articles och gap på föräldern.

Varför passar flexbox mitt innehåll?

- För att jag ska kunna styra det utan att manuellt ändra med procent och beräkna hela tiden. Jag kan nu enkelt lägga till fler artist-kort utan att layouten blir problematisk.

Vad är flexbox?

- Flexbox är en-dimensionell layout — vi ordnar barn i en rad eller en kolumn. Bra när liknande kort ska ligga i rad med jämna mellanrum (gap), och kunna wrappa.

Flex-box metod:

1. Har jag liknande bitar (kort) som ska ordnas?
2. Räcker en riktning (rad eller kolumn)? → Flexbox.
3. Behöver jag rader och kolumner samtidigt (ett schema)? → Grid

Har jag liknande bitar som ska ordnas? Räcker en riktning (rad eller kolumn)? Då Flexbox. Behöver jag rader och kolumner samtidigt — det är Grid, inte här.

Feedback-metod:
Titta på strukturen: vem är containern?
Välj en sak (saknar gap, Flex på fel element, fel tagg, ingen flex-wrap).
Skriv: FEEDBACK: [vad jag ser] → [förslag].

“Bra feedback pekar på något konkret i koden (tagg, flex-egenskap, struktur) och säger vad som funkar eller vad som kan förbättras — inte bara ‘snyggt’.”
