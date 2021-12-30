# Churn_detection

**Contexte**

Dans en environnement concurrentiel mondialisé, la fidélisation de la clientèle devient un luxe pour les entreprises. A l’ère du big data, de nombreuses entreprises ont la capacité de comprendre le comportement de leurs clients. Seulement, si de nombreux responsables marketing sont satisfaits d’observer ces comportement, nombreux sont ceux qui estiment ne pas avoir les clefs pour agir sur la fidélisation de leur clientèle. 
Le churn est un indicateur permettant de mesurer la fidélité d’une clientèle. Une stratégie marketing orientée sur l’anticipation et la réduction du churn est très bénéfique et rentable. En effet, dans un contexte de saturation du marché, il plus important de fidéliser ses clients que d’essayer d’acquérir des nouveaux d’autant plus que le coût engagé pour ajouter un nouveau client est beaucoup plus élevé que de retenir un client.

**Objectif**

L'objectif de se projet est de prédire si un client changera de fournisseur de télécommunications, ce que l'on appelle le « churning ».

**Ensemble de données**

L'ensemble de données d'apprentissage contient 4 250 échantillons. Chaque échantillon contient 19 caractéristiques et 1 variable booléenne "churn" qui indique la classe de l'échantillon. Les 19 entités d'entrée et 1 variable cible sont :

"état", chaîne . Code à 2 lettres de l'État américain de résidence du client

"compte_longueur", numérique . Nombre de mois que le client a été avec le fournisseur de télécommunications actuel

"area_code", chaîne ="area_code_AAA" où AAA = code régional à 3 chiffres.

"plan_international", (oui/non) . Le client a un plan international.

"voice_mail_plan", (oui/non) . Le client a un forfait de messagerie vocale.

"number_vmail_messages", numérique . Nombre de messages vocaux.

"total_day_minutes", numérique . Nombre total de minutes d'appels par jour.

"total_day_calls", numérique . Nombre total de minutes d'appels par jour.

"total_day_charge", numérique . Charge totale des appels de jour.

"total_eve_minutes", numérique . Nombre total de minutes d'appels en soirée.

"total_eve_calls", numérique . Nombre total d'appels en soirée.

"total_eve_charge", numérique . Charge totale des appels en soirée.

"total_night_minutes", numérique . Nombre total de minutes d'appels de nuit.

"total_night_calls", numérique . Nombre total d'appels de nuit.

"total_night_charge", numérique . Charge totale des appels de nuit.

"total_intl_minutes", numérique . Nombre total de minutes d'appels internationaux.

"total_intl_calls", numérique . Nombre total d'appels internationaux.

"total_intl_charge", numérique . Taxe totale des appels internationaux

"number_customer_service_calls", numérique . Nombre d'appels au service client

"churn", (oui/non) . Désabonnement des clients - variable cible.

L'indicateur choisit pour évaluer la performance des modèles est : l'**accuracy**

