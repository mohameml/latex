# cour 03 : les commandes de base en latex 



### 1. \usepackage{package} :
- **Définition :** Inclut des packages pour ajouter des fonctionnalités supplémentaires.
- **Rôle :** Étend les capacités de LaTeX.
- **Options :** Variables spécifiques au package.
- **Exemple :** 
  ```latex
  \usepackage{graphicx}
  ```

### 2. \title{Texte} :
- **Définition :** Définit le titre du document.
- **Rôle :** Informe LaTeX sur le titre du document.
- **Exemple :** 
  ```latex
  \title{Mon Document}
  ```

### 3. \author{Nom de l'auteur} :
- **Définition :** Indique l'auteur du document.
- **Rôle :** Attribue l'auteur au document.
- **Exemple :** 
  ```latex
  \author{John Doe}
  ```

### 4. \date{Date} :
- **Définition :** Spécifie une date pour le document.
- **Rôle :** Attribue une date au document.
- **Exemple :** 
  ```latex
  \date{Janvier 2023}
  ```

### 5. \maketitle :
- **Définition :** Génère la page de titre en utilisant les informations fournies par ``\title``, ``\author`` et ``\date``.
- **Rôle :** Crée la page de titre du document.
- **Exemple :** 
  ```latex
  \maketitle
  ```


### 6. \begin{document} ... \end{document} :
- **Définition :** Encadre le contenu principal du document.
- **Rôle :** Contient le contenu réel du document.
- **Exemple :** 
  ```latex
  \begin{document}
  Contenu du document...
  \end{document}
  ```



### 7. \section{Titre de section} :
- **Définition :** Crée une section numérotée avec un titre.
- **Rôle :** Structure le document en sections.
- **Exemple :** 
  ```latex
  \section{Introduction}
  ```

### 8. \subsection{Titre de sous-section} :
- **Définition :** Crée une sous-section numérotée avec un titre.
- **Rôle :** Divise les sections en sous-sections.
- **Exemple :** 
  ```latex
  \subsection{Contexte}
  ```



### 9. \begin{itemize} ... \end{itemize} :
- **Définition :** Crée une liste non numérotée.
- **Rôle :** Affiche une liste à puces.
- **Exemple :** 
  ```latex
  \begin{itemize}
  \item Premier élément
  \item Deuxième élément
  \end{itemize}
  ```

### 10. `\\`:

  - **Définition:**
    - La commande `\\` en LaTeX est utilisée pour indiquer un retour à la ligne, c

  - **Utilisation de `\\` :**

    - Pour créer une nouvelle ligne, utilisez `\\` à la fin d'une ligne pour passer à la ligne suivante.

  - **Exemple :**

    ```latex
    Voici une phrase sur la première ligne. \\
    Et voici une autre phrase sur la deuxième ligne.
    ```











