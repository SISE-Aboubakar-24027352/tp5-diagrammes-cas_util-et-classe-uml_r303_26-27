# TP 5 : Diagrammes de cas d’utilisation et diagrammes de classes 

## **Ex. 1 Simulation d’un réseau ferroviaire** 

Vous êtes chargé de créer un prototype de simulation simplifié d’un système de réseau ferroviaire du pays. Des lignes ferroviaires comportent au moins deux gares (correspondants aux extrémités de la ligne) et chaque gare a au moins une ligne ferroviaire qui la traverse. Les gares ont un nom. Le trains utilisent les lignes ferroviaires. À chaque train on affecte une gare d’origine et une gare d’arrivée, des propriétés qui sont modifiables. Chaque ligne ferroviaire possède des capteurs qui détectent les mouvements sur les lignes et des barrières. Chaque barrière peut être ouverte ou fermée (on va supposer des variables booléennes) et à chaque barrière un capteur est associé. 

1. Proposez un diagramme de classes 

## **Ex. 2 Location de bungalows** 

Un camping fonctionnant à l’ancienne souhaite découvrir les bénéfices d’un système informatique. On vous a chargé de réaliser le logiciel gérant les locations de bungalows. Ce logiciel devra permettre aux clients de réserver et de payer leur location via le portail web du camping. 

Les bungalows sont loués pour une semaine : du samedi après-midi au samedi matin suivant. Le coˆut d’un séjour varie selon la date de début du séjour. 

Le client précise la période de location souhaitée pour que le site affiche les types de bungalows disponibles durant la période de location avec le prix correspondant. 

Si la première étape est un succès (c’est-à-dire que le client a trouvé un type de bungalows qui lui convient et qui est disponible aux dates demandées) alors le client peut procéder à la réservation en saisissant ses coordonnées (nom, prénom, adresse, numéro de téléphone, adresse courriel, nombre d’adultes, nombre d’enfants). Une fois, les coordonnées du client saisies correctement, la réservation est enregistrée et un numéro est automatiquement affecté à la réservation. 

En début de séjour un état des lieux est fait. Le gestionnaire du camping vérifie l’état des lieux à la fin du séjour et facture éventuellement des réparations. 

Durant la saison morte (période ou le camping est fermé), afin de permettre au gestionnaire de maintenir l’état général des bungalows, celui-ci planifie des réparations et des remise en états qui s’étalent sur toute l’année. C’est pourquoi, des bungalows peuvent être retirés de la location pour être remis en état pendant plusieurs semaines. 

1. Réalisez le diagramme de classes. Vous ajouterez les attributs mais pas les méthodes. 

## **Ex. 3 Logiciel d’inscription à l’I.U.T.** 

Un étudiant qui souhaite être admis à l’IUT d’Aix-en-Provence doit déposer un dossier de candidature dˆument complété avant le 14 mai 2018. Un dossier comprend une feuille de renseignements o`u le candidat indique son nom, son prénom, son adresse et son numéro d’INSEE, ainsi que des documents pédagogiques : les bulletins de notes des 3 dernières années, des lettres de recommandation. 

Lors de la réception d’un dossier, l’administration de l’école enregistre l’arrivée du dossier, dans le logiciel, et le nom du professeur qui sera chargé d’examiner le dossier. Les professeurs sont prévenus par mail, lorsqu’ils doivent examiner un nouveau dossier. Ils ont jusqu’au 10 juin 2018 pour examiner les dossiers. 

L’examen du dossier peut conduire à trois cas différents : 

- **Cas 1** : le dossier est non-retenu (il est jugé insuffisant : le candidat ne peut être accepté). L’école envoie une lettre de refus au candidat. 

- **Cas 2** : un entretien est jugé nécessaire. L’administration de l’école convoque alors le candidat, lui fixant une date et une heure de d’entretien avec l’enseignant. Après l’entretien, le professeur qui a re¸cu le candidat décide si celui-ci est admis ou non. L’administration de l’école communique la décision au candidat. Si un candidat ne se présente pas à l’entretien, son dossier est classé parmi ceux des non-retenus. 

- **Cas 3** : le dossier est jugé suffisant pour une admission sans entretien. 

Les résultats de l’examen des dossiers et des entretiens sont enregistrés. 

En cas d’admission, après entretien ou non, l’administration de l’école prévient le candidat qui dispose d’un certain délais pour venir s’inscrire. Passé ce délai, son dossier est classé et enregistré parmi ceux des non-retenus ; un e-mail informant le candidat de son exclusion lui est envoyé. 

**Remarque** : les détails du déroulement de l’évaluation du candidat, ainsi que du déroulement de l’entretien ne concerne pas le système modélisé. Seuls les traitements des résultats de l’évaluation du candidat (directe ou à travers un entretien) sont considérés. 

1. Donnez le diagramme de cas d’utilisation. 

2. Donnez la description textuelle du cas d’utilisation ” _Traiter le résultat de l’examen d’une candidature_ ” 

3. Donnez le diagramme de classes. 

