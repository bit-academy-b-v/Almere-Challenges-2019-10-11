## Challenge 01: PHP Roulette 

### In te leveren bestanden
1) `roulette.php`

### Opdracht
We gaan naar het casino en gaan roulette spelen (de Europeaanse versie)! Je begint met een saldo van 500. Elke beurt kan je een deel of alles van je saldo inzetten. Daarna rolt de bal en krijg je uitbetaald naar ratio. Vervolgens begint de volgende beurt. De officiële regels van Roulette worden gevolgd en ten-minste de volgende gok-opties moeten worden geïmplementeerd:  
- Odd bet/even bet  
- High bet/low bet  
- Black bet/Red bet  
- Column bet  
- Dozen bet  
- Single number bet  

Je kunt gebruik maken van [deze](https://www.roulettesites.org/rules/odds/) website voor de kansen en payouts van Roulette. 

Zorg bij het maken van deze challenge dat je de functionaliteiten in kleine stukken ophakt. Maak, voordat je gaat programmeren, voor jezelf, een overzicht van de functionaliteiten die je gaat implementeren. Rangschik de functionaliteiten en implementeer ze één voor één. 

_Tip: begin met een Odd bet/Even bet. Pas als je die werkend hebt, ga je door met High bet/low bet._

Hieronder zie je meerdere output velden. Deze kun je als houvast gebruiken om de challenge in stukken op te delen.

### Output - Basic
```php
> php roulette.php
> Welcome to Roulette!!! Your balance is 500. GL&HF!
> Place your bets please! 
> 1) Odd bet/Even bet
> 2) High bet/low bet
> 3) Black bet/Red bet
> 4) Column bet
> 5) Dozen bet
> 6) Single number bet
> 1
> Do you want odd or even? 
> 1) Odd
> 2) Even
> 2
> What amount do you want to bet?
> 20
> Lets roll!
> ........
> .....
> ...
> .
> 32 RED
> You won 40! Congratulations! You new balance is 520.
```

### Output - Continue playing
```php
> php roulette.php
> Welcome to Roulette!!! Your balance is 500. GL&HF!
> Place your bets please! 
> 1) Odd bet/Even bet
> 2) High bet/low bet
> 3) Black bet/Red bet
> 4) Column bet
> 5) Dozen bet
> 6) Single number bet
> 1
> Do you want odd or even? 
> 1) Odd
> 2) Even
> 2
> What amount do you want to bet?
> 20
> Lets roll!
> ........
> .....
> ...
> .
> 32 RED
> You won 40! Congratulations! You new balance is 520.
> Want to continue playing?  
> 1) Yes
> 2) No  
> 1
> _____________________________________________________
> Your balance is 520.
> Place your bets please!
> 1) Odd bet/Even bet
> 2) High bet/low bet
> 3) Black bet/Red bet
> 4) Column bet
> 5) Dozen bet
> 6) Single number bet
> 1
> Do you want odd or even? 
> 1) Odd
> 2) Even
> 1
> What amount do you want to bet?
> 50
> Lets roll!
> ........
> .....
> ...
> .
> 18 RED
> You lost 50! Too bad! You new balance is 470.
> Want to continue playing?  
> 1) Yes
> 2) No  
> 2
```

### Output - Multiple bets
```php
> php roulette.php
> Welcome to Roulette!!! Your balance is 500. GL&HF!
> Place your bets please! 
> 1) Odd bet/Even bet
> 2) High bet/low bet
> 3) Black bet/Red bet
> 4) Column bet
> 5) Dozen bet
> 6) Single number bet
> 1
> Do you want odd or even? 
> 1) Odd
> 2) Even
> 2
> What amount do you want to bet?
> 20
> Thank you. Would you like to place another bet? 
> 1) Yes
> 2) No
> 2
> No more bets please! Lets roll!
> ........
> .....
> ...
> .
> 32 RED
> You won 40! Congratulations! You new balance is 520.
> Want to continue playing?  
> 1) Yes
> 2) No  
> ...
```



### Notities
- Foutieve input mag je programma niet crashen. 
