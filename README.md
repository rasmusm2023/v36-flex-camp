Varför flexbox?

- För att jag ska kunna styra layouten av korten utan att behöva räkna om procentsatser etc hela tiden.

Varför inte grid?

- Grid är till för om vi har rader och kolumner samtidigt, vilket vi inte har i detta paketet.

Feedback:
FEEDBACK: display: flex är skrivet som inline style → flytta till en class på containern i CSS-filen.
FEEDBACK: display: flex på ett enskilt .card → flex hör hemma på containern, inte på varje enskild child.
FEEDBACK: varje kort är en div och luften är margin: 20px → gör istället korten till articles och gap på föräldern.
