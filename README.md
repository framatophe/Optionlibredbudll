![cover](cover_small.jpg)

# Optionlibredbudll

Option Libre. Du bon usage des licences libres.

Projet de réédition du livre de BJ

# Notes importantes à propos de conversion LaTeX

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

