## Comment ça marche?

### 1 - Il faut installer une ligne de JS sur ton site juste avant la balise </body> .
 ```
<script src="https://tribadin.s3.eu-west-3.amazonaws.com/tribadin.js"></script>
```
### 2 - Il faut mettre une balise, un span par exempe, avec un id qui commence par
trb_
Par exemple
trb_your_team
```
<span id="trb_your_team">votre équipe</span>
```
Avec au milieu une valeur par default qui apparait si il n’y a pas de personnalisation dans l’url (optionnel)

### 3 - Tu peux utiliser l’url de ton site en ajoutant en parametre
?trb_your_team=Styx
https://www.tribly.co/fr/rh?trb_your_team=Styx
