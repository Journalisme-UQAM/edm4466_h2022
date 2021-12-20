# ✨ Méthode

Le contenu de ce cours colle davantage à ce qu'on appelle, dans le monde anglo-saxon, du [_Computational journalism_](https://cj2020.northeastern.edu). Il s'agit de l'application de l'informatique au journalisme. Ce plan de cours est un exemple de ce qu'on peut faire avec ces technologies. Il repose sur un système appelé [_git_](https://fr.wikipedia.org/wiki/Git), qui permet de collaborer à plusieurs sur un même projet.

Mais ce qu'on fera, surtout, c'est d'apprendre la **programmation** et ses applications journalistiques.

![Au premier-plan, l'Immeuble où le quotidien Le Soleil était situé entre 1928 et 1994 avec, au fond, l'immeuble où la rédaction du journal est située aujourd'hui. Le logo de Python symbolise l'utilisation de la programmation à des fins journalistiques.](../.gitbook/assets/python-soleil.jpg)

Le langage qu'on utilisera s'appelle [**Python**](https://www.python.org). C'est un langage d'usage général qui est l'un des plus utilisés dans le monde. C'est celui qui, en 2022 et pour la prochaine décennie au moins, me paraît le plus utile pour vous comme journalistes et comme citoyen.nes. **JavaScript** est plus couramment utilisé par des informaticien.nes, mais il est difficile à appréhender pour des gens qui n'ont jamais programmé. Le langage **R** est très utilisé par mes collègues en sciences humaines et sociales, mais en dehors des cercles académiques, il fait plutôt figure de bizarrerie.

![Les langages les plus populaires utilisés dans Github, site de travail collaboratif, de contrôle de versions et de partage de code informatique, au cours des huit dernières années (source: The 2021 State of the Octoverse).](../.gitbook/assets/octoverse.jpeg)

Python a ses avantages et ses inconvénients, comme tous les langages informatiques. C'est celui que j'ai choisi, car il est devenu la _lingua franca_ dans l'univers de l'« intelligence artificielle » et de la science des données. C'est aussi un langage que comprendront les informaticien.nes que vous croiserez peut-être dans les rédactions où vous travaillerez. Enfin, son grand nombre d'utilisateurs fait en sorte que vous pourrez compter sur une grande communauté pour répondre aux questions que vous poserez certainement en ligne au cours de la session.

Plus concrètement, on s'en servira pour :

* **moissonner** des données, ou faire du _data scraping,_
* faire du **traitement du langage naturel** (ou _Natural Language Processing \[NLP]_), ce qui nécessite l'utilisation d'une forme d'« intelligence artificielle »,
* **analyser** des données lorsqu'elles sont trop volumineuses pour un tableur comme _Excel_ ou _Calc_ de LibreOffice,
* **visualiser** des données.

![Logo du Google Colaboratory, surimposé sur cette photo du pont Pierre-Laporte sans raison particulière sinon que je trouvais cette photo chouette. ](../.gitbook/assets/colab.jpg)

On va le faire au moyen d'un outil que j'utilise pour la première fois : [Google Colaboratory](https://colab.research.google.com), ou [**Colab**](https://colab.research.google.com). Pour ce faire, il faut que vous disposiez d'un compte Google (si vous vous servez déjà de Gmail et/ou de Google Drive, tout va bien).

Je ne suis pas un _cheerleader_ des GAFA. Mais si j'ai opté pour Colab, c'est après avoir jonglé avec plusieurs options au cours des sessions précédentes et dans les derniers mois de 2021 :

* en 2016 et 2017, je demandais aux étudiant.es d'utiliser [Cloud9](https://aws.amazon.com/fr/cloud9/); ce service en ligne a cependant été acheté par Amazon qui l'a intégré à ses AWS (Amazon Web Services) et l'a rendu payant :skull::exclamation:
* à partir de 2018, j'ai demandé à tout le monde d'installer sur son ordi [Anaconda](https://www.anaconda.com), une plateforme d'analyse de données. On réutilisait [Sublime Text](https://www.sublimetext.com) pour écrire du code. Mais cela se traduisait par une expérience différente selon que vous possédiez un ordinateur avec Windows ou avec Mac. En outre, les personnes munies d'un Chromebook étaient larguées (elles pouvaient utiliser [CodeAnywhere](https://codeanywhere.com) ou [PythonAnywhere](https://www.pythonanywhere.com), des services cependant payants). En 2020, j'ai même introduit un éditeur de code professionnel : [Visual Studio Code](https://code.visualstudio.com).
* à l'été 2020, j'ai donné avec deux collègues de la Faculté des sciences le cours [Initiation à la science des données et à l'intelligence artificielle](https://etudier.uqam.ca/cours?sigle=INF7100). C'était entre les deux premières vagues de la pandémie et le cours a exclusivement été donné en ligne. Je me suis alors servi de [Azure Notebooks](https://portal.azure.com), un service auquel toute personne qui travaille ou étudie à l'UQAM avait accès gratuitement dans le cadre de l'abonnement de l'université à Office365... j'utilise l'imparfait parce que ce service n'existe plus...
* Pour cette session-ci, j'ai exploré des solutions de rechange comme [PyCharm](https://www.jetbrains.com/fr-fr/pycharm/), [Gitpod](https://www.gitpod.io), [Glitch](https://glitch.com) ou les [Codespaces de Github](https://github.com/features/codespaces). Pour toutes sortes de raisons, je ne les trouvais pas appropriés pour cette session au cours de laquelle les risques de reconfinement sont grands et où j'ai besoin d'une solution en ligne.

Colab ressemble aux Azure Notebooks qui avaient très bien fonctionné en 2020. Ce service m'est apparu comme la meilleure solution. Nous allons en faire l'expérience ensemble au cours de la session.

Il permet de programmer à l'intérieur de ce qu'on appelle des **carnets**, ou _**notebooks**_, en anglais. Vous me rendrez d'ailleurs la plupart des devoirs sous la forme de carnets.

### Ce cours est un échange

Je reste ouvert à vos **demandes spéciales**. Vous avez entendu parler d'un projet, d'un reportage retentissant, d'une technologie, d'une application particulière en journalisme? Si je puis vous aider à l'appréhender, voire la réaliser, je vais tâcher de le faire. La meilleure façon d'apprendre est avec un projet concret.

Inversement, si vous connaissez une technique, un outil, un truc, n'hésitez jamais à le **partager** avec l'ensemble du groupe. Parlez-m'en au préalable et on pourra prévoir une période dans le prochain cours pour que vous puissiez nous le ou la présenter. Si vous pouvez vous aussi m'apprendre quelque chose, je serai le prof le plus heureux du monde.

> ### _Il n'y a aucune honte à admettre qu'on ignore quelque chose. La seule honte est de prétendre avoir réponse à tout._
>
> * Neil deGrasse Tyson

![](../.gitbook/assets/NeilDTyson.jpg)
