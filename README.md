

# Free COVID-19 :rocket:  
**type: specification** <br/>
**Update 30.12.2020** <br/>
**Version 0.1** <br/>

## Une solution Anti-Lockdown

Et si il y avait plusieurs stratégies de depistage ? Depuis Mars, il y en a une, dès les premiers symptomes, il faut contacter son médecin ou utilisez une les offres de dépsitage du canton. A genève il existe aussi plusieurs solutions de test rapide comme avec m3-test.ch. Des solutions de désengorgement, mais il faut quand même prendre rendez-vous, patienter, et sans symptome il faut payer une facture non négligeable ([source](https://www.bag.admin.ch/bag/fr/home/krankheiten/ausbrueche-epidemien-pandemien/aktuelle-ausbrueche-epidemien/novel-cov/testen.html#2051828467)) L'indicateur principal qui permet de suivre l'épidémie, c'est la valeur du nombre de reproduction `Re` ([Ro](https://www.covid19.admin.ch/fr/repro/val) ) qui pour simplifier, s'il est en dessus de 1.0 `Re > 1.0` alors c'est la politique de lockdown qui s'applique et le coma artificiel du fédéralisme.

**Un problème de vitesse**</br>
La prosition du Professeur Michael Mina (Epidemiology, Harvard T.H) souligne que le principale problème du protocole actuel c'est sa vitesse, ou plutôt qu'il est trop lent. Et il ajoute que le problème de vitesse est principalement un problème d'ingénierie. Il part du principe que le débordement de `Re` avec le lockdown ne peut être qu'une solution d'urgence, efficace pour gagner un peu de temps, mais en dehors de l'urgence, il créé plus de problèmes qu'il en résoud. L'hypothèse de M. Mina est simple à mettre en oeuvre. A la place de suivre le virus, il faut suivre la zone contagieuse du virus. Il faut déployer des tests rapides, bon marchés (*<= 5 fr*), efficaces (*basé sur la structure virale ou le RNA*), et utilisables anonymement depuis la maison. Conjointement, il faut une solution technique, neutre et anonyme, qui permette de produire une carte "Météo" du virus actif pour permettre d'avertir les personnes qui ont traversés un lieu risqué à moment donné. Lorsqu'un risque de contamination existe, on informe, et on tests rapidement, sans cout et anonymement. Selon Michael Mina, une solution efficace permettrait en 30 jours, de vivre avec le virus sans lockdown jusqu'au moment ou on atteind le seuil de l'immunité collective.

> For an effective Covid filter that will stop this pandemic, we need tests that can enable regimens that will capture most infections while they are still infectious. These tests exist today in the form of rapid lateral-flow antigen tests, and rapid lateral-flow tests based on CRISPR gene-editing technology are on the horizon. Such tests are cheap (<$5), can be produced in the tens of millions or more per week, and could be performed at home, opening the door to effective Covid filter regimens ([source](https://www.nejm.org/doi/full/10.1056/NEJMp2025631))

**Lockdown is not a solution, destroying small businesses is not a solution** <br/>
[![Michael Mina](https://img.youtube.com/vi/PYd-Q_CYmKA/0.jpg)](https://www.youtube.com/watch?v=PYd-Q_CYmKA)


## Une solution en 3 piliers

Pour faire maintenir le taux de reproduction R en dessous de 1.0 (reproduction non exponentionnelle) et donc éviter le lockdown, il faut connaître la carte "météo" du virus. Ceci tout en respectant 3 piliers,
- *Pas de lockdown;* Ce n'est pas l'économie qui doit être arrêtée, c'est le virus
- *Pas de traçage individuel;* Ce n'est pas la population qui doit être controlée, c'est le virus
- *Une incitation finnancière individualisée;* L'état ne doit pas arroser aveuglement, il doit permettre l'économie locale de fonctionner


## 1. Un protocol de test rapide 
Un test rapide est considéré si et seulement si il est accesssible simplement parout et sans restriction à toute la population à coût un marginal. Un test Antigen rapide est basée sur une technologie qui mesure la structure virale dans un échantillon (protéine), il n'est pas question de mesurer les anticorps résiduel de la suite d'une infection. Le test rapide n'invalide pas le test PCR qui doit toujours être effectué en cas de réponse positive au test rapide ou lors des premiers symptomes de la maladie.

- le département fédérale doit valider cette stratégie sur la base du travail de Michael Mina ( https://www.rapidtests.org)
- le test doit être fiable, bon marché et accessible anonymement,
- le test doit être identifiable par un ID unique 

## 2. Une technologie neutre et anonyme pour construire une Carte "Météo"

Le traçage est caractérisé par a une précision qui varie entre 0 et 100%, à 0 il est inexistant et à 100% il est libeticide. Comme souvent c'est une question d'arbitrage qui produit une fonction dont le résultat un  vecteur de deux valeurs, sanitaire et économique.
Les solutions SwissCovid et Covidwatch sont excellentes mais une autre manière est possible qui se concentre sur deux éléments: 

- l'ajout d'une incitation d'utilisation; Qui doit remplacer le mode passif actuel.
- joindre le traçage avec l'activité culturelle, de loisir et de consomation; L'application trace le passage dans un lieux de cluster

**Notre proposition,** 

0. Après avoir installé l'application, on achète un test rapide Antigen à 5 fr que l'on garde.
1. L'achat d'un test donne le droit de réclamer le montant en BON de consommation valable dans toutes la suisse,
1. La trace individuelle est anonyme, ce qui n'est pas anonyme, se sont les clusters: magasins, restaurants, stades, théâtres, clubs, écoles, stations, etc.
2. La trace anonyme est enregistrée sur le réseau publique Ethereum et permet de produire une carte "météo" dont la géographie est identifiée par les clusters.
3. Si une personne est testée positive au COVID-19, elle informe l'application qui va ensuite suivre les clusters qu'elle a parcouru les 5 derniers jours, et informer toutes les personnes passés par ces mêmes lieux.
4. Toutes les personnes informées doivent utiliser le test rapide (acheter au préalable), et informer le réseau si le test est opsitif.


## 3. Une incitation économique pour utiliser l'application

En se concentrant sur les clusters, l'application permet également d'échanger des BONs numériques (cryptomonnaie) dédiés à stimuler l'économie nationale. En effet, un BON peut être acheté en ligne à 10% ou 20% de sa valeur marchande. Ensuite, ils sont disponibles dans l'application pour consommer des produits dans les lieux visités (Cluster). Finalement, le commerçant peut convertir les BONs collectés en argent depuis une plateforme en ligne ou dans des offres de change du canton.

0. Chaque achat de test rapide Antigen permet de réclamer sa valeur en un BON d'achat
1. Chaque personne peut acheter des bon d'achats depuis l'application a l'aide d'une carte maestro, crédit, ou débit.
2. La valeur d'un bon est payé à 90% par le consommateur, et 10% par l'état.
1. Chaque magasins concernés par le lockdown: restaurants, stades, théâtres, clubs, écoles, stations, etc. doivent inscrire sur le site de l'application. Cela permet de construire une carte des clusters de contagion
3. Dans chacun de ces lieux, il est possible d'utiliser les BONs depuis l'application mobile.

Avec le test rapide Antigen bon marché, et utilisable à domicile, la chaine de contagion peut être anéantie sans avaoir au recours du lockdown centralisé et difficile à justifier. 



### Support or Contact
* [questions et communications](../../discussions),,, 


![image](https://user-images.githubusercontent.com/1422935/103349621-9ed4d000-4a9d-11eb-8e11-6330a827a553.png)
