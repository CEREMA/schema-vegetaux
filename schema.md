## vegetaux

Végétaux

Spécification du fichier relatif aux végétaux

- Schéma créé le : 04/09/24
- Site web : https://github.com/CEREMA/schema-vegetaux
- Version : vx.x.x
- Valeurs manquantes : `""`, `"NA"`, `"NaN"`, `"N/A"`
- Clé primaire : `ID`

### Modèle de données


##### Liste des propriétés

| Propriété | Type | Obligatoire |
| -- | -- | -- |
| [ID](#id---propriété-id) | nombre réel  | Oui |
| [nom_scientifique](#nomenclature-binominale---propriété-nom_scientifique) | chaîne de caractères  | Oui |
| [nom_commun](#nom-commun---propriété-nom_commun) | chaîne de caractères  | Oui |
| [famille](#famille---propriété-famille) | chaîne de caractères  | Non |
| [accueil_insectes](#capacité-d'accueil-des-insectes---propriété-accueil_insectes) | booléen  | Non |
| [aire_naturelle](#aire-naturelle---propriété-aire_naturelle) | chaîne de caractères  | Non |
| [allergisant](#allergène---propriété-allergisant) | booléen  | Non |
| [anime](#animer---propriété-anime) | booléen  | Non |
| [capacite_recepage](#capacité-de-recépage---propriété-capacite_recepage) | booléen  | Non |
| [categorie_paysagere](#catégorie-paysagère---propriété-categorie_paysagere) | chaîne de caractères  | Non |
| [cavites](#capacité-à-générer-des-cavités---propriété-cavites) | booléen  | Non |
| [cheminement](#cheminement---propriété-cheminement) | booléen  | Non |
| [cimetiere](#cimetière---propriété-cimetiere) | booléen  | Non |
| [comestibles_faune](#éléments-comestibles-pour-l’avifaune-et-la-moyenne-faune---propriété-comestibles_faune) | booléen  | Non |
| [commentaire_biodiversite](#commentaire---propriété-commentaire_biodiversite) | chaîne de caractères  | Non |
| [commentaire_consommation](#commentaires---propriété-commentaire_consommation) | chaîne de caractères  | Non |
| [commentaire_origine](#commentaire-sur-l’origine---propriété-commentaire_origine) | chaîne de caractères  | Non |
| [commentaire_paysage](#paysage-et-cadre-de-vie---propriété-commentaire_paysage) | chaîne de caractères  | Non |
| [confort](#confort---propriété-confort) | booléen  | Non |
| [conifere_feuillu](#conifère-/-feuillu---propriété-conifere_feuillu) | chaîne de caractères  | Non |
| [contraintes_physiques](#contraintes-physiques---propriété-contraintes_physiques) | liste  | Non |
| [cortege_naturel](#cortège-végétal---propriété-cortege_naturel) | chaîne de caractères  | Non |
| [cour_ecole](#cour-d’école---propriété-cour_ecole) | booléen  | Non |
| [danger_mecanique](#danger-mécanique---propriété-danger_mecanique) | liste  | Non |
| [envahissante](#envahissante---propriété-envahissante) | chaîne de caractères  | Non |
| [espace_intermediaire](#espace-intermédiaire---propriété-espace_intermediaire) | booléen  | Non |
| [feuilles_composition](#composition-foliaire---propriété-feuilles_composition) | chaîne de caractères  | Non |
| [feuilles_densite](#densité-du-feuillage---propriété-feuilles_densite) | chaîne de caractères  | Non |
| [feuilles_forme](#forme-des-feuilles---propriété-feuilles_forme) | chaîne de caractères  | Non |
| [feuilles_rugosite](#rugosité---propriété-feuilles_rugosite) | chaîne de caractères  | Non |
| [feuilles_taille](#taille-des-feuilles---propriété-feuilles_taille) | chaîne de caractères  | Non |
| [feuilles_type](#feuillage---propriété-feuilles_type) | chaîne de caractères  | Non |
| [fleurs_couleur](#couleur---propriété-fleurs_couleur) | chaîne de caractères  | Non |
| [fleurs_periode](#période---propriété-fleurs_periode) | liste  | Non |
| [fleurs_valorisation](#valorisation-des-fleurs---propriété-fleurs_valorisation) | liste  | Non |
| [fruits_comestibles](#fruit-comestible---propriété-fruits_comestibles) | booléen  | Non |
| [fruits_commentaire](#commentaire---propriété-fruits_commentaire) | chaîne de caractères  | Non |
| [grande_voie](#grande-voie-de-circulation---propriété-grande_voie) | booléen  | Non |
| [habitats_hote](#capacité-à-générer-des-habitats,-rôle-de-plante-hôte---propriété-habitats_hote) | booléen  | Non |
| [hauteur_max](#hauteur-maximale---propriété-hauteur_max) | nombre réel  | Non |
| [indigene_exogene](#caractère-indigène/exogène---propriété-indigene_exogene) | chaîne de caractères  | Non |
| [inflammabilite](#inflammabilité---propriété-inflammabilite) | chaîne de caractères  | Non |
| [infusion](#utilisable-en-infusion---propriété-infusion) | booléen  | Non |
| [insectes](#insectes-observés---propriété-insectes) | chaîne de caractères  | Non |
| [interet_lepidopteres](#intérêt-pour-les-lépidoptères---propriété-interet_lepidopteres) | booléen  | Non |
| [largeur_houppier](#largeur---propriété-largeur_houppier) | chaîne de caractères  | Non |
| [longevite](#longévité---propriété-longevite) | chaîne de caractères  | Non |
| [mer_etang](#bord-de-mer-et-étang---propriété-mer_etang) | booléen  | Non |
| [noue_bassin_orage](#noue-et-bassin-d’orage---propriété-noue_bassin_orage) | booléen  | Non |
| [origine](#type-d'origine---propriété-origine) | chaîne de caractères  | Non |
| [parc_urbain](#parc-urbain---propriété-parc_urbain) | booléen  | Non |
| [partie_toxique](#partie-toxique- ---propriété-partie_toxique) | liste  | Non |
| [place](#place---propriété-place) | booléen  | Non |
| [placette](#placette---propriété-placette) | booléen  | Non |
| [pollen_nectar](#capacité-à-générer-des-pollens-et-nectars---propriété-pollen_nectar) | booléen  | Non |
| [port](#forme---propriété-port) | chaîne de caractères  | Non |
| [quai_berge](#quai-et-berge---propriété-quai_berge) | booléen  | Non |
| [racines_degats](#dégâts---propriété-racines_degats) | chaîne de caractères  | Non |
| [racines_systeme](#systèmes-racinaires---propriété-racines_systeme) | chaîne de caractères  | Non |
| [recommandations_guides](#recommandations-par-des-guides-locaux-en-terme-de-biodiversité---propriété-recommandations_guides) | chaîne de caractères  | Non |
| [resistance_chaleur](#chaleur---propriété-resistance_chaleur) | chaîne de caractères  | Non |
| [resistance_gel](#résistance-au-gel---propriété-resistance_gel) | chaîne de caractères  | Non |
| [resistance_secheresse](#sécheresse---propriété-resistance_secheresse) | chaîne de caractères  | Non |
| [resistance_vent](#vents---propriété-resistance_vent) | chaîne de caractères  | Non |
| [sol_salinite](#salinité---propriété-sol_salinite) | chaîne de caractères  | Non |
| [sol_texture](#besoins-de-texture---propriété-sol_texture) | liste  | Non |
| [square](#square---propriété-square) | booléen  | Non |
| [stationnement](#stationnement---propriété-stationnement) | booléen  | Non |
| [structure](#structurer---propriété-structure) | booléen  | Non |
| [symbolique](#symbolique---propriété-symbolique) | booléen  | Non |
| [toxique](#toxicité---propriété-toxique) | booléen  | Non |
| [vitesse_croissance](#vitesse-de-croissance---propriété-vitesse_croissance) | chaîne de caractères  | Non |
| [voie_peripherique](#voie-périphérique---propriété-voie_peripherique) | booléen  | Non |

#### id - Propriété `ID`

> *Description : Identifiant de l’espèce selon Sesame 13<br/>Ex : 10*
- Valeur obligatoire
- Type : nombre réel

#### Nomenclature binominale - Propriété `nom_scientifique`

> *Description : <br>Nom scientifique de l’espèce (en latin)<br/>Ex : Jasminum nudiflorum Lindl.*
- Valeur obligatoire
- Type : chaîne de caractères

#### Nom commun - Propriété `nom_commun`

> *Description : Nom commun (en français) de l’espèce<br/>Ex : Érable de Montpellier*
- Valeur obligatoire
- Type : chaîne de caractères

#### Famille - Propriété `famille`

> *Description : Famille de l’espèce<br/>Ex : Betulaceae*
- Valeur optionnelle
- Type : chaîne de caractères

#### Capacité d'accueil des insectes - Propriété `accueil_insectes`

> *Description : Capacité d’accueil des insetes<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Aire naturelle - Propriété `aire_naturelle`

> *Description : Le niveau de précision est le pays, ou la région (selon la taille du pays, la répartition de l'espèce) dans lequel l’espèce se situe de façon naturelle<br/>Ex : Maroc, Andalousie*
- Valeur optionnelle
- Type : chaîne de caractères

#### Allergène - Propriété `allergisant`

> *Description : Oui/Non, et si plus d'informations :<br>Faible ou négligeable – Il faut une très grande quantité de pollen pour déclencher une allergie et cela ne concerne que les personnes les plus sensibles. <br>Modéré <br>Fort - Quelques pollens suffisent à provoquer une réaction allergique<br><br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Animer - Propriété `anime`

> *Description : la floraison printanière exubérante de certains arbres et/ou le feuillage lumineux à l’automne permet de qualifier une ambiance, un signal ou un repère spatial.<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Capacité de recépage - Propriété `capacite_recepage`

> *Description : Oui/Non et commentaires<br>Arbres feuillus se recèpent mieux. <br>La capacité et vigueur de recépage diminue avec l'âge<br>La plupart des arbustes se recèpent<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Catégorie paysagère - Propriété `categorie_paysagere`

> *Description : Arbre : Végétal ligneux atteignant au moins 7m de haut, et développant dès le départ une tige principale forte (tronc) <br>Arbuste : Végétal ligneux ne dépassant pas 7m de haut, et développant dès le départ un tronc, portant les tiges secondaires à une certaine distance du sol.<br>Arbrisseau : Végétal ligneux ne dépassant pas 7m de haut (en général pas plus de 4), et ne développant pas tronc, mais de nombreuses tiges ramifiées dès la base.<br>Sous arbrisseau : Végétal ligneux, sous-frutescent, inférieur à 1m, et dont l’extrémité des rameaux herbacées se dessèche chaque hiver.<br>Herbacée : Végétal tendre, non ligneux - annuelle, bisannuelle ou vivace.<br/>Ex : Liane*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Arbre
    - Arbuste
    - Arbrisseau
    - Sous-arbrisseau
    - Herbacée
    - Liane

#### Capacité à générer des cavités - Propriété `cavites`

> *Description : Capacité à générer des cavités<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Cheminement - Propriété `cheminement`

> *Description : Espace linéaire dédiés exclusivement aux modes actifs offrant à la fois confort sécurité et convivialité à ses usagers. Exemples: pistes, sentiers, etc.<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Cimetière - Propriété `cimetiere`

> *Description : Espace funéraire et lieu de recueillement de sépultures, il est souvent clos et ouvert au public. Plus ou moins végétalisé, cet espace intègre une symbolique forte (végétale, ornementale, etc.) qui varie en fonction des cultures et des lieux géographiques.<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Éléments comestibles pour l’avifaune et la moyenne faune - Propriété `comestibles_faune`

> *Description : Éléments comestibles pour l’avifaune et la moyenne faune<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Commentaire - Propriété `commentaire_biodiversite`

> *Description : Commentaire associé aux services rendus à la biodiversité<br/>Ex : Visité par de nombreux passereaux, papillons, bourdons. Il est nectarifère*
- Valeur optionnelle
- Type : chaîne de caractères

#### Commentaires - Propriété `commentaire_consommation`

> *Description : Commentaire associé à la consommation par les humains<br/>Ex : En dehors de son utilisation en bouquets secs,ses fleurs ont  des vertus antitussives et diurétiques. En cuisine, les immortelles ne valent pas le vrai curry, un mélange d'épices complexe au parfum plus subtil et tenant beaucoup mieux à la cuisson. En Espagne, les fleurs de l'immortelle des dunes sont toutefois utilisées en infusion et fournissent une tisane improprement appelée « manzanilla », ce qui signifie camomille.*
- Valeur optionnelle
- Type : chaîne de caractères

#### Commentaire sur l’origine - Propriété `commentaire_origine`

> *Description : Commentaire associé à l’origine de l’espèce<br/>Ex : None*
- Valeur optionnelle
- Type : chaîne de caractères

#### Paysage et cadre de vie - Propriété `commentaire_paysage`

> *Description : Commentaire associé au paysage et au cadre de vie<br/>Ex : Arbre au feuillage très décoratif, il est utilisé en alignement dans sa zone de répartition d'origine, mais sera plutôt utilisé comme sujet isolé, bosquet, ou haie haute sous nos latitudes. Il requiert une température d’au moins 5°C avec son port dressé puis étalé avec les années. Esthétique   avec des branches fortes, il est bon pour la faune. Feuilles odorantes*
- Valeur optionnelle
- Type : chaîne de caractères

#### Confort - Propriété `confort`

> *Description : la qualité d’ombrage de certaines essences apporte une voûte protectrice des rayons de soleil, le végétal peut également être un brise-vent ou/et un écran visuel (pour masquer) ou marque une limite infranchissable (pour protéger).<br><br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Conifère / feuillu - Propriété `conifere_feuillu`

> *Description : Classe d'appartenance de l'espèce à l'embranchement des pinophytes (conifères) ou non.<br>0-inconnu : valeur recherchée mais inconnue<br>1-conifère : plante appartenant à l’embranchement des pinophytes. Synonyme : résineux.<br>2-feuillu : plante n’appartenant pas à l’embranchement des pinophytes.<br/>Ex : Inconnu*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Inconnu
    - Conifère
    - Feuillu

#### Contraintes physiques - Propriété `contraintes_physiques`

> *Description : détails dans commentaires<br>♠Valeurs multiples possibles : Epines, Brûlures, Poils urticants, Fruits salissants, Dépôt de miellat, Aucun, Aucune<br/>Ex : ['Dépôt de miellat', 'Fruits salissants']*
- Valeur optionnelle
- Type : liste

#### Cortège végétal - Propriété `cortege_naturel`

> *Description : Certaines espèces sont associées entre elles dans la nature et il peut être intéressant dans certains cas de reproduire cette association (affinités des végétaux entre eux). Ainsi le cortège végétal proposé est un ensemble d'espèces ayant des caractéristiques écologiques communes.<br/>Ex : romarin,ciste, lavande,pistachier lentisque,chêne kermès, génévrier oxycèdre*
- Valeur optionnelle
- Type : chaîne de caractères

#### Cour d’école - Propriété `cour_ecole`

> *Description : Espace extérieur clos réservé aux établissements scolaire à dominante minérale. Soumis à un règlement, ils peuvent être aménagés avec des structures/équipements sportifs et pédagogiques.<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Danger mécanique - Propriété `danger_mecanique`

> *Description : Ex - La plupart des Eucalyptus<br>2 - Ex - chute des cônes d'Araucaria. <br>♠Valeurs multiples possibles : Branches cassantes, Fructification pouvant entraîner des dommages, Chute d'arbre, Aucun, Aucune<br/>Ex : ['Branches cassantes', 'Fructification pouvant entraîner des dommages']*
- Valeur optionnelle
- Type : liste

#### Envahissante - Propriété `envahissante`

> *Description : Espèce envahissante (émergente, modérée, majeure - noter dans commentaires)<br>2 – EVEpotE - Espèce potentiellement envahissante - Alerte - Espèce végétale exotique peu fréquente sur le territoire considéré, elle est citée comme envahissante ailleurs et a un risque de prolifération intermédiaire à élevé <br>3 - EVEpotE - Prévention -  Espèce végétale exotique a priori absente du territoire considéré, citée comme envahissante ailleurs et ayant un risque intermédiaire à élevé de prolifération .<br>4 - L'espèce n'est pas sur la liste de prévention de PACA, mais elle est considérée comme envahissante à l'étranger - considerer le danger potentiel<br>a : Beaucoup de territoires la considèrent comme envahissante - évaluer le danger potentiel<br>b :  Peu (1 à 3 max) de territoires considèrent cette espèce comme enhavissante - la plante n'est pas considérée comme potentiellement invasive. <br>5 - Espèce non envahissante<br>5b - l'Espèce est peu plantée, peu connue<br/>Ex : EVEE*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - EVEE
    - Alerte
    - Prévention
    - A-EVEE à l'étranger
    - B-EVEE à l'étranger
    - Non

#### Espace intermédiaire - Propriété `espace_intermediaire`

> *Description : Espace interstitiel non construit formant des intervalles et respirations entre les bâtiments. Il est fréquent dans les quartiers des grands ensembles. Non structurant et parfois non entretenus, ils constituent des « respirations » vé-gétalisées dans le tissu urbain, à l'image des pas japonais dans la ville.<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Composition foliaire - Propriété `feuilles_composition`

> *Description : Composition foliaire<br/>Ex : Simple*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Simple
    - Composée

#### Densité du feuillage - Propriété `feuilles_densite`

> *Description : Classe de densité du feuillage de l’arbre adulte en condition naturelle isolée. <br>0-inconnu : valeur recherchée mais inconnue<br>1-ouvert : feuillage peu dense, la lumière traverse aisément. Exemple : Saule blanc, Févier d’Amérique<br>2-moyennement dense : feuillage moyennement dense, la lumière traverse difficile. Exemple : Tilleul, Pin sylvestre<br>3-dense : feuillage très dense, la lumière ne traverse quasiment pas. Exemple : Génévrier, Erable de Montpellier<br/>Ex : Moyennement dense*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Inconnu
    - Ouvert
    - Moyennement dense
    - Dense

#### Forme des feuilles - Propriété `feuilles_forme`

> *Description : Classe de la forme du limbe de la feuille (ou de la foliole/foliolule si feuille composée).<br>0-inconnu : valeur recherchée mais inconnue,<br>1-aiguille : Forme des feuilles très fine et très allongée (beaucoup plus longue que large) (Aiguille, linéaire, aciculaire…)<br>2-lobé : Forme plus longue que large, en partie découpée (Lobée, pennatilobée,  pennatifide, pennatipartite, pennatiséquée…)<br>3-lancéolé ou ovale : Forme plus longue que large, entière (Lancéolé, oblongue, ovale, obovale, elliptique, oblancéolée, sagitée, falciforme…)<br>4-palmilobé : Forme aussi longue que large, en partie découpée (Incisé, acutilobée, pédatilobée, pédatifide, palmilobée, palmatilobée, palmatifide, palmatipartite…)<br>5-ronde : Forme aussi longue que large, entière (Ronde, cordée, réniforme, orbiculaire, luné, lunulée, peltée, deltoïde, cordiforme, en éventail…)<br>6-écaille : Forme particulière en écaille (Feuilles plates et très courte imbriquée les unes dans les autres)<br/>Ex : Lancéolé ou ovale*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Inconnu
    - Aiguille
    - Lobée
    - Lancéolé ou ovale
    - Palmilobé
    - Ronde
    - Écaille

#### Rugosité - Propriété `feuilles_rugosite`

> *Description : Classe de rugosité du limbe de la feuille (ou de la foliole/foliolule si feuille composée).<br>0-inconnu : valeur recherchée mais inconnue,<br>1-glabre : Feuilles glabres et souples des 2 côtés,<br>2-cireuse : Feuille avec cuticule supérieure épaisse (et glabre face inférieure),<br>3-cireuse sur deux faces : Feuille avec 2 faces cireuses,<br>4-poilue : Feuille avec 1 face poilue  (glabre et souple sur l’autre face),<br>5-poilue sur deux faces : Feuille avec 2 faces poilues ,<br>6-cireuse et poilue :Feuille avec cuticule supérieure épaisse et face inférieure poilue,<br>7-limbe réduit : Forme particulière en aiguille ou écaille<br/>Ex : Limbe réduit*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Inconnu
    - Glabre
    - Cireuse
    - Cireuse sur deux faces
    - Poilue
    - Poilue sur deux faces
    - Cireuse et poilue
    - Limbe réduit

#### Taille des feuilles - Propriété `feuilles_taille`

> *Description : Classe de longueur maximale du limbe de la feuille (si feuille simple), de la foliole/foliolule (si feuille composée), de l’aiguille ou de l’écaille de l’arbre adulte en condition naturelle. <br>0-inconnu : valeur recherchée mais inconnue<br>1-petite : de 0 à 5,0cm de long (exemple  Cupressus sempervirens : 0.5-1cm, Cedrus atlantica : 2.5cm)<br>2-moyenne : de 4,9cm à 14,9cm de long (exemple  Crataegus monogyna : 3-5cm, Fraxinus ornus : 5-10cm, Celtis australis : 5-12cm)<br>3-grande : 15cm de long et plus (Prunus persica : 8-15cm, Broussonetia papyrifera : 10-20cm, Platanus orientalis : 15-30cm, Paulownia tomentosa : 17-50cm. )<br/>Ex : Moyenne*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Inconnu
    - Petite
    - Moyenne
    - Grande

#### Feuillage - Propriété `feuilles_type`

> *Description : Classe de persistance du feuillage en condition naturelle. <br>0-inconnu : valeur recherchée mais inconnue<br>1-caduc : feuilles qui tombent selon un rythme saisonnier. L’arbre n’a plus de feuille pendant une période de l’année. Synonyme : décidue.<br>2-marcescent : feuilles qui flétrissent selon un rythme saisonnier. Elles sèchent sur la plante sans s'en détacher. L’arbre perdra ses feuilles lors du débourrement qui interviendra après une période sans feuille vivante.<br>3-semi-persistant : feuilles qui tombent selon un rythme saisonnier, mais suivie immédiatement de la repousse. Synonyme : brévidécidue.<br>4-persistant : feuilles qui ne tombent pas selon un rythme saisonnier. Le feuillage reste vert et fonctionnel en permanence.<br/>Ex : Caduc*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Inconnu
    - Caduc
    - Marcescent
    - Semi-persistant
    - Persistant

#### Couleur - Propriété `fleurs_couleur`

> *Description : Une ou plusieurs couleurs de la floraison<br>Couleur de la floraison = dominante<br/>Ex : vert puis pourpre*
- Valeur optionnelle
- Type : chaîne de caractères

#### Période - Propriété `fleurs_periode`

> *Description : Les mois de floraison :<br>janvier ... 12 - décembre<br>Ex : 3.5 - 5 : de mi mars à mai<br>Hiver : 12.5 – 3.5<br>Printemps : 3.5 – 6.5<br>Eté : 6.5-9.5<br>Automne :9.5 -12.5<br/>Ex : ['5', '10']*
- Valeur optionnelle
- Type : liste

#### Valorisation des fleurs - Propriété `fleurs_valorisation`

> *Description : Valorisation des fleurs : esthétique, en parfum ou les deux<br>♠Valeurs multiples possibles : Apparence, Parfum, Les deux, Non<br/>Ex : ['Non', 'Les deux']*
- Valeur optionnelle
- Type : liste

#### Fruit comestible - Propriété `fruits_comestibles`

> *Description : Le fruit est-il comestible ?<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Commentaire - Propriété `fruits_commentaire`

> *Description : Commentaire associé aux fruits<br/>Ex : Capsules coriaces, contenant 4 graines*
- Valeur optionnelle
- Type : chaîne de caractères

#### Grande voie de circulation - Propriété `grande_voie`

> *Description : Espace public linéaire structurant à l'échelle de la ville dédié en priorité à la mobilité et pouvant accueillir de habitat et des commerces. Exemples: boulevard, rambla, avenue, etc.<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Capacité à générer des habitats, rôle de plante hôte - Propriété `habitats_hote`

> *Description : Capacité à générer des habitats, rôle de plante hôte<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Hauteur maximale - Propriété `hauteur_max`

> *Description : Hauteur maximale atteinte par l’arbre adulte, en condition naturelle, en mètres, arrondi à l’entier le plus proche.<br/>Ex : 10*
- Valeur optionnelle
- Type : nombre réel

#### Caractère Indigène/Exogène - Propriété `indigene_exogene`

> *Description : SUPPRIMER<br/>Ex : Invasive avérée*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Espèce autochtone
    - Espèce allochtone
    - Exotique à surveiller
    - Invasive potentielle
    - Invasive avérée

#### Inflammabilité - Propriété `inflammabilite`

> *Description : Niveau d’inflammabilité<br/>Ex : Moyen*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Faible
    - Moyen
    - Fort
    - Très fort

#### Utilisable en infusion - Propriété `infusion`

> *Description : Le végétal est-il utilisable en infusion ?<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Insectes observés - Propriété `insectes`

> *Description : Nom des insectes, famille<br/>Ex : papillons nectar et hôte*
- Valeur optionnelle
- Type : chaîne de caractères

#### Intérêt pour les Lépidoptères - Propriété `interet_lepidopteres`

> *Description : Intérêt pour les Lépidoptères<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Largeur - Propriété `largeur_houppier`

> *Description : Classe de largeur maximale (diamètre) atteinte par le houppier adulte, en condition naturelle.<br>0-inconnu : valeur recherchée mais inconnue<br>1-étroit : de 0 à 3,9m de large<br>2-moyen : de 4,0m à 7,9m de large<br>3-large : de 8,0m à 19,9m de large<br>4-très large : 20,0m de large et plus<br/>Ex : Très large*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Inconnu
    - Étroit
    - Moyen
    - Large
    - Très large

#### Longévité - Propriété `longevite`

> *Description : Critère qualitatif - les chiffres sont un guide pour les arbres.<br>Courte : 0-25 <br>Moyenne : 25 - 75<br>Longue – 75 : 150<br>Très longue : 150+<br>Record : 500+<br/>Ex : Moyenne*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Courte
    - Moyenne
    - Longue
    - Très longue
    - Record

#### Bord de mer et étang - Propriété `mer_etang`

> *Description : Espace public  aménagé sous la forme de promenades plantées le long des espaces maritimes et lacustres. Soumis aux embruns et aux vents, seule une gamme végétale spécifique s’adapte dans ces situations.<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Noue et bassin d’orage - Propriété `noue_bassin_orage`

> *Description : Lieu de déambulation, de séjour, de loisirs qui participe à la gestion écologique de l’eau pluviale sous différentes formes où la diversité des ambiances et le confort sont recherchés. Exemples: bassins et fossés plantés, jardins de pluie, prairie urbaine et plaine de jeux inondable.<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Type d'origine - Propriété `origine`

> *Description : Indigènes : Taxons dont l’aire naturelle de répartition se superpose, au moins en partie, au territoire considéré.<br>Cryptogènes : Taxons dont l’aire de répartition naturelle et leur origine éventuelle avant une possible expansion liée à l’homme ne peuvent être définies en raison d’un manque d’informations<br>Exogènes : Taxons dont l’aire naturelle de répartition ne se superpose pas au territoire considéré ( dont archéophytes et néophytes)<br/>Ex : Cryptogène*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Indigène
    - Cryptogène
    - Exogène

#### Parc urbain - Propriété `parc_urbain`

> *Description : Vaste espace public végétalisé structurant à l'échelle de la ville. Cet aménagement, généralement clos, propose une large diversité végétale et offre de nombreuses aménités aux habitants<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Partie toxique   - Propriété `partie_toxique`

> *Description : 4 - La sève est phototoxique (autres types de toxicité?)<br>5 - Fleurs<br>6-Ecorce,<br>7-Racines<br>♠Valeurs multiples possibles : Fruits, Graines, Feuilles, Sève, Fleurs, Ecorce, Racines, Aucun, Aucune<br/>Ex : ['Feuilles', 'Graines']*
- Valeur optionnelle
- Type : liste

#### Place - Propriété `place`

> *Description : Espace public structurant à l'échelle de la ville ou du quartier pouvant accueillir de multiples usages<br>Un espace de circulation, d’interaction et lieu de promenade. Ce lieu attractif est propice aux rendez-vous, aux petits et grands rassemblements.  La place est une scène idéale de représentation collective, sociale et urbaine à haute valeur patrimoniale.<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Placette - Propriété `placette`

> *Description : Petite place publique d’un quartier de ville ou de village offrant un lieu central aspirant à la convivialité, au confort et à l'identité locale, valorisant le patrimoine auquel il est parfois visuellement associé.<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Capacité à générer des pollens et nectars - Propriété `pollen_nectar`

> *Description : Capacité à générer des pollens et nectars<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Forme - Propriété `port`

> *Description : Forme, port, silhouette de l’arbre adulte, en condition naturelle isolée.<br>valeurs possibles : <br>1-colonnaire (Colonnaire, Fastigié, Stipe, Conique étroit…), <br>2-pyramidal (Pyramidal, Conique, Conique large),<br>3-arrondi (Arrondi, Ovale, Boule, Globuleux, Sphérique, Ovoïde),<br>4-étalé (Etalé, Rampant, Tabulaire, Verticillé, Etalé bas, Parasol),<br>5-pleureur (Pleureur),<br>6-buissonnant (Buissonnant),<br>7-liane (Liane, Grimpant)<br/>Ex : Colonnaire*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Inconnu
    - Colonnaire
    - Pyramidal
    - Arrondi
    - Étalé
    - Pleureur
    - Buissonnant
    - Liane

#### Quai et berge - Propriété `quai_berge`

> *Description : Voie publique aménagée en bordure de cours d'eau aux aménagements naturalisés (berge) ou minéralisés (quai). Voués à l'accostage et prioritairement à la déambulation et à la circulation des modes actifs, elle offre sécurité et confort d'usages.<br><br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Dégâts - Propriété `racines_degats`

> *Description : La plante fait des drageons, ou des rejets de souche.<br>La plante a besoin d'un grand volume de sol et le système racinaire peut soulever le trottoir, endommager les structures souterraines. <br/>Ex : Racines agressives*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Racines agressives
    - Drageonnantes
    - Aucun

#### Systèmes racinaires - Propriété `racines_systeme`

> *Description : 1 – Système racinaire pivotant : Une racine verticale prépondérante (pivot), développement de longs pivots secondaires et de racines horizontales <br>2 – Système racinaire traçant : un pivot qui avorte rapidement, laissant la place à des racines horizontales et de courts pivots verticaux. La surface prospectée est étendue mais peu profonde.<br>3 – Système en cœur : Caractérisé par un mélange de racines horizontales, obliques et verticales – racines moins étalées et superficielles<br>4 - Système mixte : mélange de pivotant et traçant (peu de racines obliques)<br/>Ex : Cœur*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Pivotant
    - Traçant
    - Cœur
    - Mixte

#### Recommandations par des guides locaux en terme de biodiversité - Propriété `recommandations_guides`

> *Description : Recommandations par des guides locaux en terme de biodiversité<br/>Ex : Espèce non citée*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Espèce citée dans plusieurs guides
    - Espèce citée dans un guide
    - Espèce non citée

#### Chaleur - Propriété `resistance_chaleur`

> *Description : Voire hyperthermophile : développement optimal en milieu chaud – plus de 30° <br>Mésothermophile : Les plantes ne subiront pas ou peu de dommages pendant des vagues de chaleur importantes<br>Résistante : La plante peut survivre à des vagues de chaleurs, si elles ne sont pas trop intenses, ou trop longues<br>Intolérante : La plante ne tolère pas les fortes chaleurs<br><br/>Ex : Thermophile*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Thermophile
    - Mésothermophile
    - Résistante
    - Intolérante

#### Résistance au gel - Propriété `resistance_gel`

> *Description : Résistance au gel faible/moy/forte<br>Faible : 0<br>Moyenne : - 5/-10<br>Forte : - 15<br>(trsè forte : -25 et +)<br/>Ex : Moyenne*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Faible
    - Moyenne
    - Forte
    - Très forte

#### Sécheresse - Propriété `resistance_secheresse`

> *Description : 1 – Xérophyte : Plante capable de vivre dans des régions habituellement sèches (déserts) ou dans des milieux physiologiquement secs (sols salés). Possède des adaptations morphologiques /physiologiques à la sécheresse. <br>2 – Mésoxérophyte : Se développe bien dans les millieux secs, mais ne supporte pas une sécheresse extrême. <br>3 - Peut résister à une sécheresse - si elle n'est pas trop longue ou <br> 4 – Mésophyte : Se développe le mieux dans des conditions d’humidité intermédiaire. Ne résiste pas très bien à la sécheresse. Elles peuvent avoir quelques adaptations à la sécheresse ou à la sur-humidité.  <br>5 – Hygrocline : Préfère un milieu assez humide. Ne supporte pas la sécheresse.<br/>Ex : Hygrocline*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Xérophyte
    - Mésoxérophyte
    - Résistant
    - Mésophyte
    - Hygrocline

#### Vents - Propriété `resistance_vent`

> *Description : Les plantes adaptées au vent ont des branches solides, et un système racinaire développé qui leur permet de résister au chablis (déracinement).<br/>Ex : Intolérant*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Adapté
    - Tolérant
    - Intolérant

#### Salinité - Propriété `sol_salinite`

> *Description : 1 Euhalophyte : Ne pousse que dans des environnements salés – OU – haute tolérance au sel, avec un effet favorable du sel sur la plante (croissance et productivité) <br>2 : Tolère bien le sel– stratégies - excrétion, compartimentalisation, réduction de l’influx de sodium <br>3 : Tolérance plus faible au sel-  Ces plantes réussissent à minimiser le transport des ions de sodium vers les parties aériennes (3a - très tolérante, 3b assez tolérante)<br>4 : Intolérance au sel - Effet négatifs, (ralentissement de la croissance, voire mort) <br/>Ex : Halophyte facultative*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Euhalophyte
    - Halophyte facultative
    - Glycophyte tolérante
    - Glycophyte intolérante

#### Besoins de texture - Propriété `sol_texture`

> *Description : Sableux : draine très bien, peu fertile, beaucoup d’érosion, chauffe rapidement<br>2 – Limoneux : fertile, retient moyennement l’eau, se compacte facilement, moins de 10% d’argile <br>3 – Argileux : fertile, retient bien l’eau, plus de 10% d’argile.<br>4 -Humifère : foncé – sol riche en matière organique – fertile – retient bien l’eau en étant pas trop compact - acide<br>♠Valeurs multiples possibles : Sable, Limon, Argile, Humus, Gravier/roches<br/>Ex : ['Sable', 'Limon']*
- Valeur optionnelle
- Type : liste

#### Square - Propriété `square`

> *Description : Jardin public de proximité, généralement clos en cœur de quartier offrant une ambiance rassurante et calme propice au séjour, à la détente et aux jeux.<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Stationnement - Propriété `stationnement`

> *Description : Espaces spécifiquement aménagés pour le stationnement des véhicules en secteur urbain et péri urbain, sur des places ou le long des voies<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Structurer - Propriété `structure`

> *Description : Un alignement qui cadre un point de vue vers un monument mais aussi le port architecturé des<br>arbres, le dessin des branches charpentières… le végétal permet de souligner des limites, des lignes<br>directrices.<br><br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Symbolique - Propriété `symbolique`

> *Description : le prestige et le rôle symbolique des plantations permet de jouer/de faire écho avec le patrimoine architectural. Le végétal peut également conforter une identité locale en lien avec l’histoire du lieu ou évoquer un lieu particulier ou sacré.<br><br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Toxicité - Propriété `toxique`

> *Description : Oui (majeure ou mineure)<br>Non<br/>Ex : None*
- Valeur optionnelle
- Type : booléen

#### Vitesse de croissance - Propriété `vitesse_croissance`

> *Description : Critère qualitatif - fourchette pour vérifier : <br>1 : 60+cm ans<br>2 : 30/60, <br>3- : de 30 par an. <br>Catégories intermédiaires si incertitude -  moyenne/rapide, lente/moyenne<br/>Ex : Moyenne*
- Valeur optionnelle
- Type : chaîne de caractères
- Valeurs autorisées : 
    - Rapide
    - Moyenne
    - Lente

#### Voie périphérique - Propriété `voie_peripherique`

> *Description : Espace public linéaire assurant le lien entre la ville centre et sa périphérie. Il est une transition entre des secteurs urbanisés et péri-urbanisés voire des espaces ruraux. Il constitue une entrée de ville et/ou dessert des zones d'ha-bitation et d'activités économiques. Exemples: bas-côtés et dépendances routières de ZAC, etc.<br/>Ex : None*
- Valeur optionnelle
- Type : booléen
