# Construire le portefeuille de 10 indices équipondéré et rebalancé tous les 3 mois qui soit de bêta minimal contre le S&P 500 et le comparer avec le S&P 500.
## Calculer les rendements quotidiens pour le S&P 500 et chaque indice. 
Pour cela, nous allons utiliser la formule suivante : Rendement quotidien = (Prix actuel - Prix précédent) / Prix précédent

## Calculer le rendement moyen pour le S&P 500 et chaque indice en utilisant la formule suivante :
Rendement moyen = Somme des rendements quotidiens / Nombre de jours

## Calculer le coefficient de corrélation entre les rendements quotidiens de chaque indice et ceux du S&P 500. 
Le coefficient de corrélation mesure la relation linéaire entre deux variables et peut prendre des valeurs allant de -1 (corrélation négative parfaite) à 1 (corrélation positive parfaite). Nous utiliserons la formule suivante :
Coefficient de corrélation = Covariance entre les rendements quotidiens de l'indice et ceux du S&P 500 / (Ecart-type des rendements quotidiens de l'indice * Ecart-type des rendements quotidiens du S&P 500)

La covariance mesure la mesure dans laquelle les deux variables varient ensemble, tandis que l'écart-type mesure la dispersion des rendements autour de leur moyenne. Nous pouvons calculer ces deux mesures en utilisant les formules suivantes :
Covariance = Somme des [(rendement quotidien de l'indice - rendement moyen de l'indice) * (rendement quotidien du S&P 500 - rendement moyen du S&P 500)] / Nombre de jours
Ecart-type = Racine carrée de (Somme des (rendement quotidien - rendement moyen) au carré / Nombre de jours)

## Calculer le bêta:
Bêta de l'indice = Coefficient de corrélation * (Ecart-type des rendements quotidiens de l'indice / Ecart-type des rendements quotidiens du S&P 500)

## Construire le portefeuille de 10 indices équipondéré et rebalancé tous les 3 mois qui soit de bêta minimal

## Construire le portefeuille de 10 indices équipondéré et rebalancé tous les 3 mois qui soit de bêta maximal

## Construire le portefeuille qui ne voudrait investir que dans le SPX.

## Comparer les stratégies
