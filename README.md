# ProjetDocWeb
personaliter scientifique : Robert Oppenheimer


### commande :

    pandoc -f commonmark -t html --metadata pagetitle="Robert Oppenheimer" -c ../CSS/julienDametteDamienDoree.css --template HTML/squelette.html -s MarkDown/index.md --ascii > HTML/index.html
    
    pandoc -f commonmark -t html --metadata-file metadata.yml --template HTML/squelette.html -s MarkDown/index.md --ascii > HTML/index.html
    
    pandoc -f commonmark -t html --ascii MarkDown/auteur.md > HTML/auteur.html

## Site utilisé pour les recherches

    https://fr.wikipedia.org/wiki/Robert_Oppenheimer
    https://www.radiofrance.fr/franceculture/les-regrets-de-robert-oppenheimer-le-pere-de-la-bombe-atomique-6509412
    https://www.radiofrance.fr/franceculture/podcasts/toute-une-vie/robert-oppenheimer-1904-1967-l-architecte-du-projet-manhattan-5953095
    https://www.europe1.fr/emissions/Au-coeur-de-l-histoire/12-robert-oppenheimer-le-pere-de-la-bombe-atomique-4170219
    https://www.universalis.fr/encyclopedie/julius-robert-oppenheimer/
    https://www.histogames.com/HTML/chronologie/epoque_contemporaine/dossier/le-projet-manhattan.php
    https://www.sciencesetavenir.fr/fondamental/histoire-des-sciences/le-projet-manhattan-ou-la-fin-de-l-innocence_168630



### Faire un récap de nos recherche dans le document recherche.txt 

essayer de préciser au possible dans quel partie le mettre


# TODO

- ajouter classe section dans le #contenu
- ajouter lien interne vers les diférentes section sur une page regarder comment faire les liens sur un même page 
- ajouter un tableau en page de webographie 
- verfier la présence de liste à ajouter ou ne pas faire a voir selon nos envie 
- verifier la validiter des différents documents css et html normalement ok pour HTML en xHtml 1.0 strict et css en CSS3
- voir ce a quoi correspond le sous template  OK 
- passez l'usage de markdown au niveaux expert 
