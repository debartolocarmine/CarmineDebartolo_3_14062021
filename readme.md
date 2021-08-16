# Ohmyfood

## Identité

Ohmyfood! est une entreprise de commande de repas en ligne. Notre concept permet aux
utilisateurs de composer leur propre menu et réduire leur temps d’attente dans les
restaurants car leur menu est préparé à l’avance. Plus de perte de temps à consulter la carte!

## Proposition

Nous souhaitons proposer à nos clients les menus de restaurants gastronomiques.
Développé à New-York dans un premier temps, nous souhaitons désormais élargir notre
concept à la capitale de la gastronomie : *Paris*.


## Consideration du font-size


```scss
html{
    font-size: 62.5%;
}
```

 ### Utilisation du REM
 Sur ce projet nous utilisons l'unité de mesure REM pour optimiser au mieux le resposive et l'accésiblite.
 [en savoir plus](https://connect.adfab.fr/dev/dev-front/unite-de-mesure-css-rem)


 ### Meno technique:
 Nous reduisons la valeur du font-size par défault des navigateurs en attribuant la valeur de 62.5% (16px=100% > 10px=62.5% ) à la proprieté font-size de notre balise Root (<html>).
 Ce qui nous permet une conversion du pixel au REM  plus aisé en utilisant un multiple de 10 plutôt que de 16.

 ```
 1rem  = 10px
 1.5rem = 15px
 102.4rem = 1024px 
 ```

 
  
  