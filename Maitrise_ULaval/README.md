# Cher(ère) étudiant(e)

## Supervision par Yannick Dufresne, Université Laval

Afin de faciliter au maximum votre cheminement scolaire et votre introduction à notre équipe de travail, je vous invite à télécharger ce repository Github. Il est accompagné d'un dossier Dropbox qui vous sera partagé. 
Le fichier README (que vous consultez actuellement) permet de détailler tous les éléments des différents dossiers Github et Dropbox, en plus d'expliciter le mode d'emploi de notre collaboration. 

N'ayez crainte, ça finira rapidement par être très simple!

**À noter**: pour le moment, vous constaterez que ce repository et le Dropbox associés sont plutôt adaptés aux études à la maitrise. N'empêche que toute l'information sera pertinente à votre entrée dans notre équipe, peu importe votre niveau universitaire. Étudiant.es au baccalauréat, au doctorat ou au postdoctorat, le repository n'est pas nécessaire à télécharger (il contient surtout des modèles pour le mémoire). **Il est cependant important de bien lire ce fichier README**. N'hésitez pas à réfléchir à la logique des différents dossiers, et à les adapter en fonction de vos propres besoins!

### D'abord, voici les 12 premières étapes à suivre au départ d’une supervision :

1. Acheter un Dropbox professionnel et l'installer sur votre ordinateur (~17,50$CA/mois quand on prend l'abonnement annuel);
2. Télécharger ce repository en cliquant sur le bouton vert «Clone or download» ci-dessus, puis sur «Download ZIP», et le stocker dans votre Dropbox;
3. Le renommer comme il vous plait (par exemple: «Maitrise»);
4. Ajouter le dossier Dropbox «_SharedFolder_trousseEtudiante» qui vous a été partagé **À L'INTÉRIEUR** du repository *trousse_etudiante* (que l'on a renommé «Maitrise»);
5. Créer un dossier nommé «_PrivateFolder_trousseEtudiante» et le glisser dans «Maitrise». **Il est important de ne pas nommer différemment vos dossiers _SharedFolder ET _PrivateFolder**;
6. Installer Slack, qui sert aux communications de l'équipe (https://slack.com/intl/fr-ca/);
7. Installer R, qui sert à l’analyse de données (https://www.r-project.org/); 
8. Installer LaTeX, une plateforme de création de documents (https://www.latex-project.org/get/);
9. Installer RStudio, le logiciel qui héberge R et LaTeX (https://rstudio.com/products/rstudio/download/);
10. Dans votre Dropbox, vous pouvez déjà créer un autre dossier nommé «CLESSN» (il servira à entreposer tous les projets de notre équipe). 
11. Vous pouvez aussi déjà nous envoyer une photo professionnelle de vous que nous ajouterons à notre site internet (https://www.clessn.com/).
12. Si vous n'en avez pas déjà une, il faudrait aussi vous créer une adresse gmail. Elle vous servira sur notre Google Calendar commun, mais elle sera aussi utile pour vous créer une adresse courriel @clessn.com!

Pour davantage d'informations sur les différentes installations, vous pouvez consulter l'onglet «Wiki» en haut de cette page. 

C'est fait? Bravo! Le plus dur est passé!
Maintenant, concentrons-nous sur la logique de vos nouveaux dossiers.

### La logique du dossier Dropbox (_SharedFolder_trousseEtudiante), fichier par fichier :

1. **_data_article1**: ici, vous entreposerez les données de votre article 1;
2. **_data_article2**: même chose ici, pour l'article 2;
3. **_divers**: on vous a déjà mis les cheat sheets pertinentes des guides de rédaction et les recueils créés par la CLESSN pour faciliter l'apprentissage de méthodologies;
4. **Conferences**: vous participerez sans doute à plusieurs conférences pendant vos études. Vous trouverez dans ce dossier les plus pertinentes;
5. **Financement**: il est essentiel d'appliquer pour l'obtention de bourses d'études! Vous trouverez ici les plus importantes et leurs instructions;
6. **Formations**: vous serez invité à participer à l'école d'été méthodologique ICPSR de l'Université du Michigan! Il s'agit d'un excellent complément à votre formation. Les cours en ligne de Datacamp serviront aussi à solidifier votre base en R;
7. **Litterature**: ici, vous entreposerez votre fichier Bibtex contenant toute la bibliographie de votre mémoire. Commencez à la nourrir dès maintenant!
  
![](https://github.com/clessn/communication/blob/master/trousse_etudiante/pathShared.jpg)

### La logique du dossier Github (trousse_etudiante), fichier par fichier:

Vous constaterez que certains des dossiers présentés ci-dessous ne sont pas présents dans le repo. Ce sera donc à vous de les créer! La raison est fort simple: dans git, on ne peut pas «commiter» des dossiers vides, car git ne sauvegarde pas réellement les dossiers, mais seulement les fichiers. À vous, par exemple, de créer les dossiers *_divers* ou *article1* et leur contenu, si vous choisissez de réaliser un mémoire par articles (plus de détails là-dessus dans la section suivante).

1. **Memoire**: c'est dans ce dossier que vous pourrez prochainement commencer la rédaction de votre mémoire;
  - *_divers*: sert à entreposer tous les divers éléments intéressants ou nécessaires à votre mémoire, **mais pas les données**;
  - *article1*: ici vous procéderez à l'analyse et à la rédaction de votre 1er article;
    - _graphs: ici se trouveront vos graphiques finaux à être insérés dans votre article 1;
    - code: ici se retrouvera votre fichier R;
    - writing: vous pourrez créer un beau document RMarkdown pour la rédaction de votre article 1;
  - *article2*: puis vous poursuivrez avec l'article 2;
  - *devis*: puisque vous devrez défendre votre devis de recherche devant votre comité, mieux vaut prévoir un dossier où vous le rédigerez. Pour l'instant, vous y retrouverez le gabarit officiel du mémoire de l'Ulaval en format LaTeX;
  - *index*: dans index, vous trouverez le gabarit RMarkdown pour la rédaction d'un mémoire par article. Amusez-vous à fouiller les différents dossiers et à les comprendre;
2. **README.md**: tout bon logiciel, package ou repository a un README. Il s'agit simplement d'un fichier texte contenant la description et les instructions du dossier;
3. **.gitignore**: le fichier texte (caché) .gitignore est nécessaire, comme son nom l'indique, pour ignorer la mise en ligne de certains fichiers à l'intérieur de notre repository Github. Par exemple, dans notre cas, même si nous avons ajouté le _SharedFolder_trousseEtudiante à l'intérieur de trousse_etudiante, il sera ignoré lors d'un «push» en ligne par le .gitignore. Allez voir par vous-même!

![](https://github.com/clessn/communication/blob/master/trousse_etudiante/pathMemoire.jpg)

### Mémoire/thèse

Les étudiants seront sans doute heureux d'apprendre qu'il est désormais possible de réaliser un mémoire et une thèse par articles (généralement 2 articles à la maitrise et 3 au doctorat). À la maitrise, il n'est pas obligatoire d'avoir soumis les articles à une publication scientifique. Au doctorat, les articles doivent être soumis, mais pas nécessairement acceptés.

Toute l'information pertinente au sujet de votre rédaction peut être obtenue ici: https://www.fesp.ulaval.ca/etudiants-actuels/rediger-votre-memoire-ou-these

### _SharedFolder et _PrivateFolder

Vos données de mémoire doivent **en tout temps** demeurer dans le *_SharedFolder_trousseEtudiante*. Comme mentionné, les dossiers Dropbox qui commencent par *_SharedFolder_* sont ignorés par le .gitignore, c'est-à-dire qu'ils ne seront **jamais** partagés en ligne, même lors d'un git push (vous allez bientôt bien connaitre par coeur ces expressions). Ainsi, vos données demeureront confidentielles, sur votre ordinateur. C'est la logique que nous utilisons pour tous nos projets en équipe.

De plus, nous avons pensé le fichier .gitignore pour qu'il ignore aussi les dossiers dont le nom débute par *_PrivateFolder_*. C'est pourquoi vous l'avez créé plus haut! Vous pourrez y glisser tout votre travail personnel (par exemple, les dossiers relatifs à vos cours). Ce dossier restera confidentiel; il ne sera ni publié en ligne ni partagé avec moi ou vos collègues.

Pour que cela fonctionne: **il est nécessaire de ne pas nommer autrement les fichiers _SharedFolder ET _PrivateFolder**. Faites attention aux lettres majuscules et à la ponctuation!

### Git et Github (et encore .gitignore)

Éventuellement, vous serez appelé à «pusher» en ligne, sur Github, votre «trousse étudiante» que vous personnaliserez avec votre travail. Il est donc essentiel de la renommer (par exemple: «Maitrise»), comme il est suggéré à l'étape 3. Ensuite, pour «pusher» (ou déployer) votre trousse sur Github, vous devrez vous créer un compte Github... puis travailler à comprendre son fonctionnement! Comprenez bien: vous déploierez votre repo sur votre propre compte Github et non pas celui de la CLESSN.

Git n'aime pas que l'on entrepose des informations trop lourdes sur ses serveurs... Des repo trop costauds seront aussi plus longs à télécharger. C'est une autre bonne raison pour laquelle vos données doivent se trouver dans votre _SharedFolder (qui est ignoré par notre .gitignore). Les fichiers pdf et png sont aussi ignoré par le .gitignore. Elles doivent donc préférablement être entreposées dans le _SharedFolder. La taille de fichier maximale recommandée par GitHub est de 50 MB.

Pour bien saisir la logique de Git et de Github, nous vous conseillons de visionner les tutoriels *Git and GitHub for Poets* de la chaine YouTube The Coding Train. Voici le lien du premier vidéo: https://www.youtube.com/watch?v=BCQHnlnPusY&t=3s. Ce genre de vidéo vous apprendra notamment à minimiser le risque d'erreurs sur Git. Notez bien la formule magique à inscrire dans votre terminal (oui, nous utilisons le terminal!):

1. git add -A
2. git commit -m "écrire ici la description du commit"
3. git pull
4. git push

Quand on fait un pull après un certain temps dans un repo, il est tout aussi important de taper ces codes dans le terminal, même si nous n'avons rien modifié depuis longtemps. Parfois, un fichier caché a été modifié (.RData, .Rhistory ou .DS_Store). En «commitant» comme ça, on s’assure de ne pas avoir de conflits.

**Important**: malheureusement, apprendre une formule magique n'est jamais une solution miracle. Il est plutôt nécessaire de comprendre les commandes et de pouvoir faire ce que l'on veut, peu importe les circonstances. Dans certains cas, la formule ci-dessus pourrait être inappropriée!

Pour en savoir plus, je vous invite aussi à consulter la «cheat sheet» sur Git qui est dans votre _SharedFolder -> _divers -> CheatSheets. Vous pouvez aussi compléter le cours Datacamp *Introduction to Git*.

### Datacamp

Parlant de https://www.datacamp.com/users/sign_in, voici une série de cours utiles à l'introduction à R:
 
  - Introduction to R;
  - Intermediate R;
  - Introduction to the Tidyverse (pour faciliter votre utilisation de R);
  - Data Manipulation with dplyr (pour manipuler plus facilement vos données);
  - Correlation and Regression in R;
  - Multiple and Logistic Regression in R;
  - Data Visualization with ggplot2 (Part 1) (pour faire de beaux graphiques).
  
Allez-y à votre rythme! L'introduction de chaque cours est gratuite, mais vous êtes encouragés à vous abonner. Datacamp est un outil formidable pour l'apprentissage de R.
  
### Lectures
  
Vous pouvez aussi déjà vous lancer dans la lecture de *KKV*. **Designing Social Inquiry (1994)** est un ouvrage d'introduction à la méthodologie de recherche en science sociale rédigé par Gary King, Robert Keohane et Sidney Verba (le surnom *KKV* vient des initiales de leur nom de famille). Tous.tes les étudiant.es de la CLESSN l'ont déjà lu une fois... ou plus! Le recueil «Devis de recherche», monté et utilisé pour le cours de Devis de recherche, est également une bonne lecture à faire. Vous le retrouverez dans _SharedFolder_trousseEtudiante -> _divers -> Recueils.
  
### Rencontres (et méthodes agiles)
  
Vous n'avez jamais codé en R et vous avez tapé "Mark Down" dans Google en pensant qu'il s'agissait d'un grand scientifique anglais? Aucune crainte! Vous êtes au bon endroit pour vous initier et rapidement développer une expertise dans les sciences sociales numériques. Plusieurs étudiant.es de l'équipe n'avaient jamais codé avant leur arrivée! Pour apprendre rapidement, le mieux est de commencer maintenant, et d'en faire un peu tous les jours. Quelques pages de KKV, une vidéo YouTube, un cours de Datacamp, et surtout, la participation aux scrums! 

À la chaire, nous opérons un virage organisationnel calqué sur les «Méthodes agiles». Ces méthodes permettent l'optimisation du temps et des ressources, afin de permettre un travail d'équipe efficace. Bien que nous ne respectons pas encore l'ensemble des techniques des méthodes agiles, plusieurs sont déjà bien implantées. Par exemple, chaque projet est dirigé par un «chargé de projet», qui s'occupe de suivre l'avancement des différentes tâches. Les «scrums» sont des rencontres rapides qui permettent à l'ensemble de l'équipe de faire le point. Il y en a 3 par semaine, en plus du *Mardi métho* et du *Jeudi 3P*. Vous êtes bien sûr invité à vous joindre à nous en personne ou via Slack (à distance, les rencontres se font dans la chaine **00_général**). Voici les heures de scrums et de rencontres:

  - Mardi, 15h30-16h15 (scrum long de 45 minutes, pour suivre plus en détail l'avancement des projets);
  - Mardi, 16h15-17h00 (*Mardi métho*, on fait des lectures et on jase méthodologie);
  - Jeudi, 15h30-15h45 (scrum court de 15 minutes);
  - Jeudi, 15h45-16h45 (*Jeudi 3P*, on présente un ou deux projets, et on les commente en équipe);
  - Dimanche, 15h30-15h45 (scrum court de 15 minutes).
  
### Slack
  
Si vous êtes à distance, les rencontres (scrums) se font aussi sur Slack (bien qu'il soit préférable d'être à l'Université le plus régulièrement possible). D'ailleurs, Slack est notre outil de communication et d'archivage principal. Déjà, vous pouvez demander d'être ajouté aux chaines suivantes:

  - 00_calendrier (pour recevoir les notifications du Google Calendar de la CLESSN);
  - 00_communication (pour la communication de la chaire);
  - 00_financement (pour le financement de la chaire);
  - 00_général (pour les rencontres, et les discussions générales);
  - 00_git (pour suivre l'évolution des commits git);
  - 00_mardi-metho (pour organiser les mardis méthos);
  - 00_publication (pour suivre l'évolution des publications de la chaire);
  - 99_sante-bien-etre (pour assurer la santé et le bien-être à la chaire!).
  
Il existe beaucoup d'autres chaines Slack. Plusieurs sont publiques (vous pouvez les trouver vous-même et vous y ajouter en cliquant sur «Canaux»), d'autres sont privées (vous devez demander d'y être ajoutées). À la CLESSN, les chaines débutant par 00 sont les chaines de bases. D'autres chaines existent ensuite selon les projets (01, 02, etc.), et vous y serez ajouté selon votre participation à ceux-ci. Les chaines 98 sont dédiées aux discussions méthodologiques. Les chaines 99 sont des chaines mélimélos, parfois plus ludiques. Voici, d'ailleurs, certaines chaines qui pourraient vous intéresser (il y en a beaucoup d'autres!):

  - rss_985 (amateur de Paul Archand? Retrouvez chaque matin toutes les chroniques de son émission Puisqu'il faut se lever!);
  - rss_lapresse (en temps réel, vous recevrez des notifications des nouvelles politiques de La Presse);
  - 98_méthode_analyse-textuelle (vous avez des questions à propos de l'analyse textuelle? C'est l'endroit!);
  - 99_random (pour tout... et surtout rien);
  - 99_veille-académique (pour recevoir une fois par semaine des articles pertinents à notre champ d'étude).
  
### Nos projets

C'est au travers de Slack que nous discutons des différents projets en cours. Voici une liste (non exhaustive) de ceux-ci (les numéros associés correspondent d'ailleurs aux numéros des chaines Slack!):

1. INSPQ: création d'un sondage sur les perceptions par rapport à l'alcool;
2. RADAR+: construction d'un outil pour entreposer et analyser les Unes des médias canadiens;
3. Polimètre: conception d'un algorithme de pondération selon l'importance des promesses électorales;
4. Livre CLESSN: écriture d'un livre d'introduction aux sciences sociales numériques;
5. Build-a-Voter: déploiement d'une plateforme en ligne où l'on peut construire un électeur selon une multitude de variables socio-démographiques et de «lifestyle» (mode de vie);
6. Global-ES: nettoyage et uniformisation des études électorales de plusieurs pays;
7. Boussole Japon: lancement d'une boussole électorale au Japon;
8. Entre-voix: cueillette des textes des débats législatifs disponibles sur les sites web des parlements;
9. Marché politique: création d'un marché (d'une loterie) sur la politique;
10. Lobbying: analyse de réseau avec la base de données du registre des lobbyistes;
11. Synopsis STM: élaboration de graphiques sur le STM pour un projet de la firme de marketing Synopsis;
12. Tact: production de graphiques pour la firme de marketing Tact;
13. Sondage COVID-19: réalisation d'un sondage sur le COVID-19 en partenariat avec le Centre canadien sur les dépendances et l'usage de substances.
14. Articles COVID-19: rédaction de 2 articles pour la revue CJPS avec les données de Radar+.
15. Sondage OBVIA: création d'un sondage sur l'utilisation de l'IA à l'ère du COVID-19.
16. Projet KORUM: lancement d'une plateforme en ligne de vulgarisation graphique de données politiques, médiatiques et d’opinion publique.
  
### ICPSR

Si je vous supervise, c'est que vous acceptez d'aller à ICPSR Summer Program de l'Université du Michigan. Il s'agit d'une école d'été (parmi les meilleures au monde) lors de laquelle vous pourrez approfondir vos connaissances en méthodologie quantitative. La participation à cette école constitue un rite de passage pour tous mes étudiants depuis 2017! Pour toutes les informations, voir le site web: https://www.icpsr.umich.edu/icpsrweb/sumprog/. Mais nous en parlerons assurément ensemble!

### Financement (et groupe de recherche)

Pour financer votre participation à ICPSR, voire pour financer vos études en général, il existe de nombreuses possibilités de bourses. Voici les plus populaires. À noter que les dates d'inscription sont offertes à titre informatif, mais celles-ci peuvent être modifiées d'année en année.

1. FRQSC (~9 octobre): Le Fond de recherche du Québec Société et Culture est l'équivalent provincial du CRSH. Il offre 17 500$ pour les études à la maitrise.
https://www.sshrc-crsh.gc.ca/funding-financement/programs-programmes/fellowships/cgs_masters-besc_maitrise-fra.aspx
2. CRSH (~13 décembre): Le Conseil de recherches en sciences humaines du Canada offre chaque année une possibilité de financement de 17 500$ pour les études à la maitrise. Il s'agit de la plus haute bourse de votre champ d'études, et ainsi de la plus prestigieuse. Mais elle reste à portée de tout bon dossier. https://www.sshrc-crsh.gc.ca/funding-financement/programs-programmes/fellowships/cgs_masters-besc_maitrise-fra.aspx
3. ICPSR (~31 mars): Plusieurs bourses sont offertes directement par ICPSR. Ça vaut la peine de tenter sa chance!
https://www.icpsr.umich.edu/icpsrweb/content/sumprog/scholarships/index.html

Et voici les opportunités de financement des groupes de recherche auxquels vous faites maintenant partie:

4. OBVIA (~30 août): L'Observatoire international sur les impacts sociétaux de l'IA et du numérique organise chaque année un concours de bourse de 15 000$ pour la réalisation d'un mémoire en lien avec leurs objectifs.
https://observatoire-ia.ulaval.ca/programmes-de-bourses-dappui-a-la-releve-de-lobvia/
5. CÉCD (~30 septembre et ~1er mars): Le Centre pour l'étude de la citoyenneté démocratique offre à tous ses membres 750\$ par année pour la présentation à l'étranger d'un article scientifique. Il est toutefois nécessaire d'indiquer au CECD avant le 30 septembre que vous comptez utiliser cette bourse (je vous conseille de le faire, même si vous ne pensez pas l'utiliser!). Aussi, le CÉCD offre 2500\$ en bourse de formation méthodologique (comme la participation à ICPSR).
https://csdc-cecd.ca/fr/resources/csdc-student-funding-fr/
6. GRCP (en tout temps): Le Groupe de recherche en communication politique offre 800$ par année pour la formation méthodologique et la diffusion de vos résultats de recherche. À prendre ou à laisser!
https://www.grcp.ulaval.ca/ressources/formulaires
7. CAPP: Le Centre d'analyse des politiques publiques n'offre pas de bourses pour le moment, mais c'est dans les plans!
8. Département de science politique (en tout temps): Ce n'est pas un groupe de recherche, mais le département offre des bourses de 2000$ par année pour la formation méthodologique.
https://repertoire.bbaf.ulaval.ca/bourse/52857/bourses-de-formations-methodologiques-hiver-2020

Il existe beaucoup d'autres bourses, à vous maintenant de fouiller et à me faire part de vos trouvailles! Et assurez-vous aussi d'être ajouté à ces groupes de recherches, pour (notamment) avoir droit aux financements.

### Cheminement «normal»

Sachez aussi que la Faculté des sciences sociales offre un financement pour tous les étudiants qui effectuent leurs études dans des temps considérés comme étant «normaux» par la Faculté: https://www.bourses.fss.ulaval.ca/connexion. À la maitrise en science politique, c'est 1400\$ en trois versements, c'est-à-dire que vous pouvez réclamer 280\$ si vous complétez l'ensemble de vos cours en 3 sessions, un autre 420\$ si votre projet de recherche est défendu avant la 4e session, et un dernier 700$ si votre mémoire est déposé avant la 6e session. Conseil d'ami: prenez en considération ces délais, mais ne laissez pas l'argent vous aveugler. Mieux vaut un bon projet bien réfléchi, même s'il est défendu la 5e session. L'image ci-dessous est une copie du dossier d'un étudiant (qui, contrairement à vous, n'était pas au courant au début de ses études de l'existence de ce financement!).

![](https://github.com/clessn/communication/blob/master/trousse_etudiante/cheminementNormal.jpg)

### Panique?

Bien sûr que non! La CLESSN travaille dans l'objectif d'optimiser constamment son travail. Tous les étudiants ont réussi, en avançant pas-à-pas dans leurs apprentissages, à développer les outils essentiels à leur cheminement scolaire et, en plus, à apporter leur propre contribution à la chaire. Pas de panique, donc, si vous n'avez jamais codé et si tout ça semble complexe! C'est complètement à votre portée. Et n'hésitez jamais à nous poser vos questions.

Je vous souhaite d'excellentes études.
Je vous l'assure, le temps passera très vite!

## Yannick Dufresne

![](https://github.com/clessn/communication/blob/master/trousse_etudiante/CLESSN-UL-NOIR.jpg)