# Styles

Trouve ton style

1. Créé l’application StyleAlive à partir du Github : https://github.com/bastienwcs/quest-stylealive
2. Déplace tous les styles présents dans activity_main.xml vers le fichier styles.xml
3. Si des éléments utilisent le même style, ne fait pas de doublons, utilise le même style.
4. Fait hériter le style de description par le style de text1 et text2.
5. Crée la version Landscape de styles.xml
6. Dans activity_main.xml, ajoute une TextView contenant le texte Conclusion, en dernier élément du LinearLayout. Cette TextView hérite du style utilisé par title, sauf que le texte doit être de taille 26sp.
7. Dans activity_main.xml, ajoute une TextView contenant le texte C’est cool, en dernier élément du LinearLayout. Cette TextView hérite du style utilisé par description, sauf que le texte doit être aligné à droite de l'écran.
8. Fais en sorte qu’en mode paysage, les textes de description, text1 et text2 soient de taille 20sp.

Critéres de validation

- Le fichier strings.xml contient tous les textes qui sont affichés dans la UI.
- Aucun style ne doit être présent dans activity_main.xml.
- Les styles affichés dans l’application doivent bien correspondre à ce qui a été demandé en challenge.
- Un second fichier de styles styles.xml (land) doit être présent et contenir le style demandé en challenge.
