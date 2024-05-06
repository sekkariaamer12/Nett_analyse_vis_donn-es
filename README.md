# Visualisation des données de mesure d'un automate.
Ce projet vise à visualiser les données de mesure d'un automate en utilisant la bibliothèque Pandas de Python pour l'extraction et le nettoyage des données, l'exploration des données, ainsi que la visualisation des résultats obtenus.

# Étapes du processus
- **Extraction des données :** Les données sont extraites en utilisant la bibliothèque Pandas de Python ce qui rend leur manipulation plus facile.
-  **Nettoyage des données :** Les données extraites peuvent contenir des erreurs, des valeurs manquantes ou des informations inutiles. Dans cette étape, les données sont nettoyées en éliminant les lignes ou les mesures incorrectes, ainsi qu'en extrayant les mesures spécifiques nécessaires à l'analyse.
-  **Transformation des données :** Les données sont transformées pour être compatibles avec le format requis pour la visualisation. Cela inclut la conversion des formats de données, l'extraction de valeurs spécifiques, et la création de nouvelles colonnes à partir des données existantes.
-  **Visualisation des données :** Une fois les données nettoyées et transformées, elles sont prêtes à être visualisées. Dans cette étape j'ai utilisé des bibliothèques de visualisation telles que Matplotlib, Seaborn et Plotly pour créer des graphiques et des diagrammes.

# Visualisation :

- **Boxplot des mesures pour chaque numéro de série :** Permet de visualiser la dispersion des mesures pour chaque numéro de série, identifiant les tendances centrales et les valeurs aberrantes potentielles.
- **Les nuages de points des mesures :** Cette disposition compacte offre une vue d'ensemble rapide de plusieurs variables en même temps, ce qui peut être utile pour explorer les caractéristiques générales des données.
- **Nuage de point 3D :** En observant la répartition des points dans l'espace tridimensionnel, on peut obtenir des informations sur la distribution des mesures. Par exemple, la dispersion des points le long de chaque axe peut indiquer la variabilité des mesures.
- **Evolution temporelle des mesures :** Elle permet de suivre les variations des mesures au fil du temps, ce qui peut être crucial pour identifier des tendances, des schémas périodiques ou des événements exceptionnels. Les variations soudaines ou les changements brusques dans les mesures de dérive peuvent indiquer des problèmes ou des anomalies dans le système. Cette visualisation peut aider à repérer ces moments clés.
- **Graphique de densité :** Il permet de visualiser la distribution des valeurs mesurées dans chaque colonne. Cela vous donne une idée de la forme de la distribution et de la concentration des valeurs autour de certaines zones. Les points éloignés du pic principal peuvent indiquer la présence de valeurs
aberrantes ou extrêmes. Cela peut être utile pour évaluer l'impact de ces valeurs sur la distribution globale.
