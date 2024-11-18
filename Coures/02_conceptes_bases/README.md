# cour 02 : **Concepts de bases**

- **Les concepts de base:** en LaTeX sont les fondements nécessaires pour écrire et formater des documents. 

## 1. **Structure du document :**

- **La structure du document** en LaTeX assure une organisation logique et cohérente du contenu, facilitant la création de documents de qualité avec une présentation professionnelle.
- **La structure d'un document** en LaTeX se compose de deux sections principales : le préambule et le corps du document. 

### **a.Préambule :**

- **Le préambule** est la section initiale du document qui précède le corps principal. 

- Il contient des commandes, des configurations et des informations générales concernant le document.


- **Les éléments courants dans le préambule comprennent :**

    - **Classe de document :** La classe (`\documentclass{}`) définit le type de document, tel que `article`, `report`, `book`, etc.

    - **Packages :** Inclusion de packages externes (`\usepackage{}`) pour ajouter des fonctionnalités supplémentaires au document, comme la gestion des langues, la coloration syntaxique, etc.

    - **Titre, auteur, date :** Définition du titre (`\title{}`), de l'auteur (`\author{}`), et de la date (`\date{}`) pour la page de titre du document.

    - **Configurations générales :** Personnalisation des paramètres tels que la taille de la police, les marges, etc.

### **b. Corps du document :**

- **Le corps du document:** est la partie principale du fichier LaTeX. C'est là que se trouve le contenu réel du document. 

- Cette section commence après **le préambule** et est encadrée par les commandes `\begin{document}` et `\end{document}`. 

- Le corps du document comprend :

    - **Page de titre :** Création de la page de titre à l'aide de commandes telles que `\maketitle`.

    - **Sections, sous-sections :** Structuration du contenu avec des commandes `\section{}`, `\subsection{}`, etc.

    - **Paragraphes :** Ajout de texte en paragraphes avec des sauts de ligne.

    - **Listes :** Utilisation d'environnements pour créer des listes numérotées (`enumerate`), à puces (`itemize`), ou descriptives (`description`).

    - **Éléments graphiques :** Inclusion d'images, de tableaux, de graphiques, etc.

    - **Éléments mathématiques :** Création d'équations, insertion de symboles mathématiques, etc.

    - **Références et bibliographie :** Ajout de références croisées avec `\label{}` et `\ref{}` et gestion des bibliographies avec BibTeX ou biblatex.










### 2. **Commandes et Environnements :**

- Les commandes et les environnements en LaTeX sont les éléments de base pour créer des documents bien formatés. 

- Les commandes sont des instructions spécifiques, tandis que les environnements définissent des zones de contenu avec des comportements particuliers. 

### 2.1 **Commande en LaTeX :**

- **Définition:**

    - **une commande** est une instruction commençant par un `\` suivi du nom de la commande. 
    
    - Les commandes modifient la mise en forme du texte, insèrent des éléments, changent la mise en page et exécutent diverses actions. Elles sont fondamentales pour formater le document.

- **Exemple de commande en LaTeX :**

    - **Commande pour créer une section :**
    ```latex
    \section{Titre de la section}
    ```

    - **Commande pour insérer une image :**
    ```latex
    \includegraphics{image.png}
    ```

    - **Commande pour mettre en gras :**
    ```latex
    \textbf{Texte en gras}
  ```

### 2.2 **Environnement en LaTeX :**

- **Définition:**

    - **les environnements** sont des structures délimitées par une paire de commandes : `\begin{}` et `\end{}`. 
    
    - Ils définissent des zones de texte ou de contenu avec un comportement spécifique. 


- **Exemple d'environnement en LaTeX :**

    - **Environnement `document` :**
    ```latex
    \documentclass{article}
    \begin{document}
    Contenu du document...
    \end{document}
    ```

    - **Environnement `itemize` pour créer une liste à puces :**
    ```latex
    \begin{itemize}
    \item Premier élément
    \item Deuxième élément
    \end{itemize}
    ```

    - **Environnement `equation` pour écrire des équations :**
    ```latex
    \begin{equation}
    E=mc^2
    \end{equation}
    ```




## 3. **classe de document: `\documentclass[]{}`**

### 3.1 **une classe de document:** 

- **Définition:**

    - **une classe de document:**  est un modèle prédéfini qui définit la structure de base, la mise en page, et parfois le style général d'un document. 



- **Classes de documents courantes en LaTeX :**

    1. **article :** Pour des articles académiques, des rapports courts, des documents plus courts sans chapitres, adapté pour des publications uniques.
    
    2. **report :** Pour des rapports plus longs, avec chapitres, idéal pour des mémoires, des thèses, etc.
    
    3. **book :** Pour des livres, contient des chapitres, idéal pour les ouvrages plus longs.

    4. **letter :** Pour écrire des lettres.
    
    5. **beamer :** Pour les présentations.


- Chaque classe a des configurations et des caractéristiques par défaut spécifiques qui affectent la présentation du document. 





## 3.2. **le commande `\documentclass[]{}`:**

- **Définition:**
    
    - La commande `\documentclass[]{}` est une commande fondamentale en LaTeX utilisée pour définir le type de document que vous souhaitez créer. 

    - La commande `\documentclass[]{}` est utilisée pour définir la classe du document. 
    
    - Elle est placée au tout début du fichier LaTeX, après les éventuels commentaires ou espaces blancs. Voici sa structure de base :

        ```latex
        \documentclass[options]{class}
        ```

- **Rôle :**

    - **Définition de la classe du document :** Cette commande détermine le type de document que vous créez, comme un article, un livre, un rapport, une lettre, etc.

- **Options courantes :**

    - **Taille de police :** Options pour spécifier la taille de la police, comme `10pt`, `11pt`, `12pt`.
    
    - **Format du papier :** Options pour définir le format de papier, comme `a4paper`, `letterpaper`, `legalpaper`.
    
    - **Orientation :** 

        - **l'orientation** se réfère à la disposition de la page de votre document par rapport à la largeur et la hauteur. 

        - Il existe deux orientations principales : 

            - **Portrait :**
                - C'est l'orientation par défaut. Les pages sont disposées en mode portrait, où la hauteur est plus grande que la largeur. 
                - Les documents de type lettre, rapport ou article sont généralement disposés en mode portrait.

            - **Paysage :**
                - Dans cette orientation, la largeur est plus grande que la hauteur. 
                - Cette orientation est souvent utilisée pour les grandes illustrations, diagrammes, tableaux, ou tout contenu qui nécessite plus d'espace horizontal. Elle permet de mieux présenter du contenu à large échelle.

        - **Comment changer l'orientation en LaTeX :**
            
            - Pour définir l'orientation, vous utilisez l'option `landscape` ou `portrait` dans la commande `\documentclass[]`. Par exemple :

                ```latex
                \documentclass[a4paper, landscape]{article}
                ```
    - **l'option `twoside`:**

        - l'option `twoside` est utilisée pour définir la mise en page recto verso d'un document imprimé. Lorsque cette option est activée, LaTeX formate le document en tenant compte des pages paires et impaires, ce qui est particulièrement utile pour des documents destinés à être imprimés en recto verso (sur les deux côtés des feuilles). 

        - **Utilisation :**

            - Pour activer la mise en page recto verso, vous pouvez inclure l'option `twoside` dans la commande `\documentclass`. Par exemple :

                ```latex
                \documentclass[twoside]{article}
                ```



    


- **Exemples :**

    - **Document basique :**

        - Pour un document standard, sans options spéciales :

            ```latex
            \documentclass{article}
            ```

    - **Document avec options :**

        - Pour un document avec une taille de police de 12 points et un format de papier A4 :

            ```latex
            \documentclass[12pt, a4paper]{article}
            ```

    - **Rapport ou mémoire :**

        - Pour un rapport ou un mémoire avec une taille de police de 11 points, un format A4, et une mise en page recto-verso :

            ```latex
            \documentclass[11pt, a4paper, twoside]{report}
            ```

### Remarques :

- Certaines classes de document offrent des options supplémentaires spécifiques à leur utilisation. Par exemple, la classe `beamer` pour les présentations offre des options spécifiques aux diapositives.





