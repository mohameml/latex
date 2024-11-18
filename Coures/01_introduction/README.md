# cour 01 : Introduction 


## 1.**Introduction à LaTeX**

- **Définition :** 
    - **LaTeX** est un langage de composition de documents largement utilisé pour la création de documents scientifiques, académiques et professionnels.
     
    - Contrairement à un traitement de texte classique, LaTeX se concentre sur la structure logique du document plutôt que sur son apparence visuelle. Il repose sur TeX, un système de typographie créé par **Donald Knuth**.


- **Utilisation :** 
    
    - LaTeX est couramment utilisé pour rédiger :
        
        - **des articles scientifiques**, 
        
        - **des thèses**, 
        
        - **des rapports**, 
        
        - **des livres**, 
        
        - des présentations, des CV, et d'autres documents nécessitant une mise en forme complexe, des équations mathématiques, des références croisées et une gestion avancée des bibliographies.


- **Caractéristiques :** 
    
    - Les caractéristiques clés de LaTeX comprennent :

        - **Syntaxe basée sur les balises** : 
            
            - Les documents LaTeX sont écrits en utilisant des balises et une syntaxe structurée pour définir le contenu, la mise en forme et les éléments du document.
        
        - **Gestion avancée des formules mathématiques :** 
            
            - LaTeX offre un support exceptionnel pour la rédaction d'équations mathématiques complexes et de symboles mathématiques.

        - **Réutilisabilité :** 
            
            - Grâce à sa structure modulaire, les documents LaTeX permettent de réutiliser et de gérer facilement le contenu.




## 2. **Compilation `pdflatex`:** 



- **Définition:**
    
    - **`pdflatex`:** 
        - est un moteur de compilation LaTeX très courant, largement utilisé pour transformer les fichiers source LaTeX (fichiers `.tex`) en documents PDF. 
    
    - Il est souvent le moteur de compilation par défaut utilisé pour produire des documents PDF à partir de fichiers LaTeX.



- **Caractéristiques de pdflatex :**

    1. **Génération de fichiers PDF :** `pdflatex` compile les fichiers LaTeX en produisant directement des fichiers PDF.

    2. **Support des images et des polices :** Il est capable de gérer les images aux formats courants (comme PNG, JPEG, PDF) ainsi que les polices TrueType et OpenType.

    3. **Simplicité d'utilisation :** Son utilisation est relativement simple et conviviale, idéale pour la plupart des cas d'utilisation standards.


- **Utilisation de pdflatex :**

    - Pour compiler un document LaTeX en utilisant `pdflatex`:

```bash
pdflatex votre_fichier.tex
```

Cette commande générera un fichier PDF à partir de votre fichier source LaTeX.




## 3.**Premier programme :** 

- Un exemple simple de programme LaTeX serait la création d'un document basique avec une structure minimale comprenant le documentclass, les sections, et du texte simple.

Exemple minimal de document LaTeX :

```latex
\documentclass{article}
\begin{document}

\title{Mon premier document LaTeX}
\author{Votre nom}
\date{\today}
\maketitle

\section{Introduction}
Ceci est mon premier document LaTeX. 

\subsection{Première section}
Du texte simple.

\end{document}
```

Ce code créera un document de base avec un titre, une section, et du texte simple.

