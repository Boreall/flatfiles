#CMS
* Lancer le serveur dans le dossier "Flatfiles" en tapant "Jekyll Serve".
* Se connecter à l'adresse http://127.0.0.1:4000/.
file:///home/atc123/Bureau/sites/flatfiles/

##Organisation du blog 

* Le fichier _config contient la configuration générale du blog.
* Le dosser _layout contient les templates qui serviront à générer les pages.
* Le dossier _post contient les articles.
* Le dossier _site contient le blog généré.
C'est ce dossier qu'il faut placer sur le serveur pour générer le blog.

##Articles
Les posts doivent se trouver dans le dossier _posts, ils peuvent être écrit en Markdown ou en
Textile. Pour ajouter un article, il faut créer un fichier ANNEE-MOIS-JOUR-titre.md. Les pages commencent par quelques lignes de YAML pour la configuration. Les formats Markdown et Textiles sont simples, il n'y a pas de code HTML à écrire, le code est généré lors de la génération de la page.
Voir la suite ici : http://www.toam.fr/20-05-2013-guide-demarrage-jekyll/