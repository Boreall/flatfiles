**C’est Quoi des Collections ?**
Les Collections dans Jekyll sont des ensembles de documents qui ont les mêmes fonctionnalités que les posts. Les collections ont la puissance des posts, mais vous les tenez à portée de main. Une chose à noter à cette heure : à la différence des posts, les collections ne supportent pas la pagination, bien que les collections de documents puissent être publiées individuellement sous forme de pages. Elles peuvent être aussi restituées sous forme de listes en utilisant le moteur de gabarits Liquid intégré dans Jekyll. Les collections disposent de leur propre espace nom sur tout le site avec des métadonnées et des propriétés personnalisables.

Les Collections fonctionnent sur le principe du moteur Jekyll qui lira votre collection définie dans le fichier config.yml lors de la construction du site. Jekyll ajoute le document de la collection frontmatter YAML aux variables de gabarits globales du site, et restitue –si vous le souhaitez— chaque document dans sa propre page. Les collections peuvent s’utiliser pour n’importe quel type d’ensemble de documents que vous souhaiteriez organiser sur votre site.

De bons exemples de collections peuvent être les projets sur lesquels vous avez travaillés, la publication de la liste des organisateurs d’un événement, la constitution d’une bibliothèque d’albums « women in rock », la documentation d’une API, ou plus simplement une liste de petites notes sur vos données de santé ou toute autre thématique-clé, etc.

**Configurer les Collections**
La première étape pour configurer les collections est d’indiquer à Jekyll que vous avez une collection dans le fichier _config.yml. collections: - LPO

Maintenant, ajoutez un dossier à la racine du répertoire de votre projet avec le même nom que la collection. Assurez-vous de préfixer le dossier avec un souligné “_”. Ajoutez quelques documents en format markdown dans le dossier de la collection.

**Les Collections en Action**
Maintenant que la collection est définie et une fois le contenu ajouté à la collection, ces collections peuvent être incluses sur n’importe quelle page dans le site Jekyll. Par exemple, les ajouts les plus récents de votre collection peuvent être affichés sur votre page d’accueil en utilisant la syntaxe Liquid. Tout front-matter YAML personnalisé déclaré dans chaque document peut aussi permettre de faire figurer le contenu.

http://christopheducamp.com/2014/12/31/demarrer-des-collections-dans-jekyll/

