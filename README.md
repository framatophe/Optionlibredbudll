![cover](cover_small.jpg)

# Optionlibredbudll

Option Libre. Du bon usage des licences libres.

Projet de réédition du livre de BJ

# À propos de conversion LaTeX (pandoc)

Pour assurer le package listings, ne pas oublier de spécifier tous les caractères accentués ou spéciaux français

    \lstset{
    basicstyle=\ttfamily\footnotesize\color{lettrelisting},
    %    backgroundcolor=\color{fondlisting},
    tabsize=1,
    title=\lstname,
    escapeinside={\%*}{*)},
    breaklines=true,
    breakatwhitespace=true,
    inputencoding=utf8,
    extendedchars=true,
    literate={à}{{\`a}}1 {ê}{{\^e}}1 {é}{{\'e}}1 {è}{{\`e}}1 {â}{{\^a}}1 {ç}{{\c{c}}}1 {ù}{{\`u}}1 {î}{{\^i}}1 
    }

Attention avec les références bibliographiques situées en notes de bas de page. Pandoc les converti en \autocite{ref}, ce qui a pour effet de les transformer en notes qui ne renvoient à rien. Il faut les passer en \cite{ref}.

Pandoc traduit les lignes (encarts) de cette manière ``\begin{center}\rule{3in}{0.4pt}\end{center}`` Cela permet d'avoir un reprère pour les transformer en encarts dans la version LaTeX.

# À propos de conversion HTML (pandoc)

Il faudra faire une cosmétique légère des références bibliographiques pour les harmoniser.

Les lignes sont traduites en ``<hr />``, ce qui est tout à fait normal. Il faudra créer un style "encart" et l'appliquer partout.

Les notes de bas de page sont bel et bien traduites en chiffres ``fn42, fn43, etc``. La manière de nommer la note dans la version markdown n'a donc pas d'influence pourvu que chaque note soit bien évidemment unique. 



