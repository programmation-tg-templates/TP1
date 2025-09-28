# Conditions TP1

Déterminer si une année est bissextile

On souhaite écrire un programme en TypeScript qui détermine si une année donnée est bissextile ou non.

## Rappel

Une année est bissextile si :
- Elle est divisible par 4.
- Mais si elle est aussi divisible par 100, elle n’est pas bissextile.
- Sauf si elle est divisible par 400, alors elle est quand même bissextile.

## Exemples

- 2024 est bissextile (divisible par 4 et pas par 100).
- 1900 n’est pas bissextile (divisible par 100 mais pas par 400).
- 2000 est bissextile (divisible par 400).

## Travail demandé

Écrire une fonction `estBissextile(annee: number): boolean` qui retourne `true` si l’année est bissextile et `false` sinon.
