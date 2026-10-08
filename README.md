# Mémoire-de-Stage-M2
Ce mémoire porte sur l'évaluation des caractéristiques des tests à l'aide de modèle bayésiens à classe latentes

# Résumé du mémoire de stage

Ce stage, réalisé au sein de l'unité Épidémiologie et Appui à la Surveillance (EAS) du laboratoire de 
Lyon de l'Anses, s'inscrit dans un projet de validation de nouveaux kits ELISA destinés au diagnostic 
sérologique de la brucellose porcine. L'objectif principal était d'évaluer les performances diagnostiques 
de plusieurs kits ELISA en les comparant aux deux tests sérologiques classiquement utilisés, l’Épreuve 
à l'antigène tamponné (EAT) et le test de Fixation du complément (FC), à l'aide de modèles bayésiens à 
classes latentes. 
Le travail réalisé a comporté une revue bibliographique sur les modèles bayésiens appliqués à 
l'évaluation des tests diagnostiques, la construction des jeux de données, l'élaboration de distributions a 
priori à partir d'un jeu indépendant d'animaux de statut connu et de données issues de la littérature, puis 
le développement de plusieurs modèles bayésiens sous R et JAGS (Just Another Gibbs Sampling). Deux 
approches de modélisation ont été étudiées : une approche multinomiale appliquée à l'analyse conjointe 
de deux tests (ELISA Ar et FC) et une approche individuelle permettant l'analyse simultanée de plusieurs 
tests diagnostiques. Des modèles supposant l'indépendance conditionnelle puis la dépendance 
conditionnelle entre les tests ont été développés et comparés à l'aide de critères d'ajustement (Deviance 
Information Criterion), de diagnostics de convergence Monte Carlo Markov Chain (MCMC) et de 
l'analyse des corrélations résiduelles. 
Les résultats obtenus montrent que la prise en compte de la dépendance conditionnelle améliore la 
qualité de l'ajustement des modèles et conduit à des estimations plus cohérentes des caractéristiques 
diagnostiques. Parmi les kits évalués, le kit ELISA compétitif G présente la sensibilité la plus élevée, 
tandis que le kit ELISA indirect Ar et le test FC présentent les spécificités les plus importantes. Les 
modèles développés permettent ainsi de mieux caractériser les performances des différents tests et 
constituent une contribution à l'évaluation de nouveaux outils diagnostiques utilisables dans le cadre de 
la surveillance de la brucellose porcine. 

Mots clés :  Brucellose porcine ; Tests diagnostiques ; ELISA ; Modèles bayésiens à classes latentes ; 
Sensibilité ; Spécificité ; Prévalence ; Dépendance conditionnelle ; JAGS ; R. 

# Materiels

R, Rjags, Rmarkdown
