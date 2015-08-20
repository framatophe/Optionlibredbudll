# Les bons réflexes

L'innovation, la création ou le développement reposent aujourd'hui, plus que jamais, sur une très large réutilisation des travaux de tiers. Dès lors, la question n'est plus de savoir qui détient les droits de propriété intellectuelle, mais simplement comment pouvoir les exercer&nbsp;! Cette situation &ndash;&nbsp;une concentration de titulaires de droits exclusifs réunis pour l'exploitation d'une seule création&nbsp;&ndash; amplifie l'importance d'une bonne maîtrise tant des enjeux de propriété intellectuelle que des licences libres.

Chaque nouveau projet se traduit par une multitude de relations contractuelles destinées à favoriser et sécuriser les collaborations composées d'une part croissante de contrats types fixant à priori et de façon _intangible_ les conditions d'utilisation. À cet égard et puisqu'elles opèrent une cession de droits d'exploitation très large facilitant la réutilisation de leurs créations (au bénéfice seulement de ceux qui respectent le cadre qu'elles ont fixé), les licences libres et _open source_ constituent une réponse optimum à cette recherche d'une innovation rapide et efficace. La liberté offerte est néanmoins conditionnée au respect de certaines conditions et obligations qui nécessitent une vigilance particulière (avec comme sanction l'action en contrefaçon). Ainsi, cette logique de mutualisation, génératrice d'importantes économies pour l'industrie, nécessite la mise en place d'une gestion spécifique, et notamment juridique, destinée à garantir le respect de l'ensemble des licences. Innover dans ce cadre juridique ouvert impose donc&nbsp;:

   - de _gérer l'extension des effets des licences sur d'autres composants_&nbsp;: c'est la question de _l'ajout d'une licence_ et des _situations d'incompatibilité_&nbsp;;
   - de _veiller au respect du formalisme_ imposé par les différentes licences (transmission du code source, mention de paternité, différenciation des modifications, etc.). Celui-ci est notamment destiné à assurer la maîtrise effective du code, essentielle dans les projets _open source_ (code source, documents préparatoires, scripts, etc.).

Ces deux composantes doivent imprégner l'élaboration de bonnes pratiques au sein des projets, voire de politiques _open source_ formalisées au sein des sociétés concernées.

Ce dernier chapitre est celui le plus orienté «&nbsp;pratique&nbsp;» de l'ouvrage, répondant à la question «&nbsp;comment, concrètement, doit-on utiliser les licences libres&nbsp;». Pour commencer, il convient d'admettre qu'il est encore habituel que les enjeux relatifs aux licences libres ne soient appréhendés que trop tardivement, par exemple lorsque la distribution de la création est d'ores et déjà programmée, ce qui abouti à des situations de concession peu satisfaisantes tant pour l'équipe juridique que technique. Une réflexion en amont doit donc être systématiquement préférée, car même si chaque licence obéit à un mécanisme qui lui est propre, il est néanmoins possible de donner un certain nombre de recommandations quant à la mise sous licence libre (3.1) et la diffusion sous licence libre (3.2).

## Les réflexes préalables à la diffusion

Les projets doivent veiller à respecter l'ensemble des licences attachées aux composants qu'ils utilisent, notamment vis-à-vis du cadre juridique qu'elles imposent et ses conséquences quant au choix et l'ajout d'une licence (3.1.1) et du formalisme qui leur est attaché (3.1.2).

### Apprécier le cadre juridique induit par les licences libres

Une bonne connaissance des licences est la condition nécessaire à l'appréhension du cadre juridique qu'elles induisent. Cette appréhension permet alors de prendre toute mesure liée aux contraintes issues des choix des composants. C'est en agissant avec méthode que l'on choisit la licence (3.1.1.1) et que l'on s'assure du respect des conditions nécessaires à l'ajout d'une licence libre (3.1.1.2).

#### Méthode relative à la sélection de la licence initiale

Le choix initial de la licence est fondamental&nbsp;: en termes de marketing afin d'interpeller des communautés déjà existantes&nbsp;; en termes stratégiques, car le modèle économique développé autour du logiciel peut en dépendre&nbsp;; et enfin en termes juridiques puisque l'ouverture du projet peut engendrer l'arrivée de contributions pour lesquelles le titulaire initial ne pourra pas unilatéralement changer de licence. Une licence adaptée au logiciel et aux attentes de la société facilitera la structuration de la collaboration future, cette dernière n'étant alors concentrée que sur l'optimisation et la mutualisation dans le développement et l'exploitation du logiciel (les licences assurent, elles, les cessions de droits de propriété intellectuelle nécessaires). Le choix de la licence peut aussi avoir pour objectif d'ouvrir ou de fermer des pistes de collaboration avec des sociétés concurrentes : on parle alors de _coopétition_, pour traduire l'idée d'une coopération entre des entreprises potentiellement concurrentes qui gagnent toutes au développement du Libre.

Plusieurs démarches doivent être décrites&nbsp;: la création d'une nouvelle licence (3.1.1.1.a), ou le choix d'une ou plusieurs licence(s) existante(s), éventuellement adaptée(s) au logiciel (3.1.1.1.b).

##### La création d'une licence particulière

S'épargnant tout choix, il peut être tentant de s'orienter vers la rédaction d'une licence spécifique, particulièrement lorsque les projets et structures impliquées sont importants.

Néanmoins, avant de se lancer dans cet exercice, il est nécessaire de mesurer l'intérêt et les inconvénients de cette solution, généralement motivée par une volonté de créer un pot commun «&nbsp;encadré&nbsp;» ou de créer une licence «&nbsp;mieux adaptée&nbsp;» aux besoins. En effet, ces préoccupations emportent aussi un certain nombre de désavantages qu'il peut être préférable d'éviter.

S'il s'agit de sectoriser afin de ne pas risquer la récupération par un projet ou une entreprise concurrents, l'effet n'est pas garanti (compte tenu des libertés conférées par la licence) et les inconvénients sont non négligeables&nbsp;: la manne de composants _open source_ tiers devient indisponible (en effet, plus la licence est spécifique et plus la compatibilité sera difficile à atteindre) et il sera alors plus difficile d'intéresser les tiers aux projets (et il n'est pas possible d'ajouter une compatibilité en faveur d'autres licences sans entrer en contradiction avec cet objectif de réservation &ndash;&nbsp;mieux vaut revoir complètement sa position que d'aboutir à la situation hybride qui consisterait à ajouter _in extremis_ une telle compatibilité).

S'il s'agit, de manière tout à fait légitime, d'une volonté de créer une nouvelle licence optimisée pour la création (et son auteur), cet effort peut aussi s'avérer contre-productif&nbsp;: il fait courir le risque que la licence contienne des failles non existantes (ou résolues) dans d'autres licences, et demande, outre sa rédaction, la mise en œuvre d'un travail de communication, d'interprétation et d'assistance dans la compréhension de cette licence, ce qui est, une nouvelle fois, une activité coûteuse en temps et en énergie[^partdeuxchaptrois1]. En effet, la rédaction d'une licence est un projet ambitieux. Il n'est pas rare que les nouvelles versions de licences prennent un ou deux ans avant d'être terminées. Un tel projet fait appel à des compétences particulières. Il est ainsi généralement plus sûr d'utiliser une licence largement répandue chez des grands groupes tels IBM, HP, Microsoft, Sun, Oracle, Google, etc.. Le seul aspect positif est la potentielle compatibilité avec la licence utilisée comme canevas, avantage bien faible compte tenu des autres solutions assurant une même compatibilité.

<!-- NOTES -->

[^partdeuxchaptrois1]: C'est d'ailleurs ce constat qui explique en partie l'insuccès des licences CeCILL&nbsp;: alors que l'initiative était réellement novatrice, il n'y avait qu'une seule personne qui s'occupait &ndash;&nbsp;parmi bien d'autres tâches&nbsp;&ndash; de la mise à jour du site, de la FAQ, des relations avec les différentes instances de l'écosystème (OSI, FSF, etc.).

<!-- /NOTES -->

Ainsi, la rédaction d'une nouvelle licence _open source_, si elle peut dans certains cas (limités) se justifier, ne doit pas être une solution «&nbsp;par défaut&nbsp;», mais au contraire le fruit d'une réflexion globale qui ne peut faire l'économie d'une sélection en amont d'une ou plusieurs licences «&nbsp;modèles&nbsp;». Elle devra par ailleurs être le fruit de professionnels, aptes à intégrer les contraintes de sécurité juridique face à l'écosystème existant du Libre et de l'_open source_.

L'aspect politique pouvant, à lui seul, être la justification d'un tel choix, il est alors nécessaire de rappeler les éléments qui précèdent afin que les risques soient clairement identifiés (un mauvais choix en la matière pourra annuler l'intégralité des avantages qu'apporterait l'ouverture du projet).

##### Le choix d'une licence adaptée

Plutôt que de «&nbsp;réinventer la roue&nbsp;», il est généralement conseillé d'utiliser une ou plusieurs licences existantes.

###### Le choix d'une licence

Le choix d'une licence est une juste combinaison de stratégie et de tactique. 

En termes _stratégiques_, le choix de la licence doit traduire les intérêts juridiques, techniques et commerciaux du projet (voire de la société). Par ailleurs, il doit intégrer les contraintes issues de la réutilisation de créations tierces, sous licence _open source_ ou non.

Il est nécessaire d'adopter la licence la plus adaptée à son projet en se concentrant sur ses obligations, son étendue, son élément déclencheur et éventuellement la compatibilité qu'elle organise. Il convient donc, dans un premier temps, de réaliser un «&nbsp;cahier des charges des besoins&nbsp;» et de dresser un inventaire des licences qui répondent, en totalité ou en partie, aux attentes. Dans un second temps, il peut être utile d'estimer l'intérêt des licences au regard du contexte&nbsp;: est-ce important d'utiliser une licence largement connue et testée&nbsp;? Doit-on s'inspirer des choix opérés par des projets concurrents analogues&nbsp;? Ces réponses ne peuvent être données qu'au cas par cas, en fonction de l'examen et de l'approche choisie. Incontestablement, une licence disposant d'une large notoriété participe avantageusement à la communication qui suivra la libération de la création. En revanche, le choix d'une licence similaire à un projet concurrent est un pari dont il faut bien mesurer les aléas&nbsp;: les contributions pouvant librement circuler d'un projet à l'autre, celui qui réunit la meilleure communauté risque de l'emporter et de détourner à son profit les contributeurs de son concurrent&nbsp;; à l'inverse, bénéficier de l'expérience et de l'expertise déployée par une société concurrente peut s'avérer être un choix judicieux. 

Une fois sélectionnée la licence (ou un nombre limité de licences), il est nécessaire de faire preuve de _tactique_ de sorte à peaufiner l'usage fait de la licence afin de s'assurer qu'elle réponde en tout point aux objectifs de l'auteur ou du projet. La seule existence de plusieurs centaines de licences laisse présager un nombre tout aussi grand de situations particulières les ayant justifiées. Il faut néanmoins rester vigilant au phénomène d'incompatibilité que cette multiplication a favorisé (cf. _supra_). Cette tactique peut prendre la forme d'interprétations ou d'exceptions.

En cas de clauses imprécises ou équivoques, il peut être utile de préciser le sens attendu, voire de désigner une personne tierce &ndash;&nbsp;un médiateur ou _proxy_&nbsp;&ndash; comme source d'interprétation. Cela confère une portée précise à la licence, qui tient les parties et le juge. C'est cette technique, dite de l'«&nbsp;interprétation&nbsp;» qu'utilisa Linus Torvalds sur le noyau Linux[^partdeuxchaptrois2].

L'usage des _exceptions_ est une autre technique plus radicale qui consiste à modifier une licence préexistante en ajoutant, dans une clause jointe à la licence (ou insérée dans les en-têtes des fichiers), une spécificité qui déroge aux termes initiaux avec pour effet de rendre la licence finale plus ou moins contraignante. Cela permet, par exemple, de réduire efficacement la portée d'un _copyleft_, en lui fixant une étendue différente, en excluant plusieurs logiciels ou une catégorie entière de logiciels (plusieurs exceptions peuvent d'ailleurs être attachées à des parties différentes d'un logiciel[^partdeuxchaptrois3]). Il est à noter qu'en l'absence de stipulation contraire, une clause additionnelle qui ne fait «&nbsp;qu'ajouter des droits&nbsp;» pourra être supprimée par tout licencié au moment de la redistribution d'une copie de cette création[^partdeuxchaptrois4].

La maîtrise de plus en plus fine de la pratique contractuelle liée aux licences _open source_ conduit aujourd'hui à conseiller une pratique réfléchie et adaptée de ces exceptions et interprétations. Les premières confèrent plus de souplesse aux licences[^partdeuxchaptrois5], les secondes assurent une plus grande sécurité juridique. Un bon usage de celles-ci peut permettre de prévoir et de résoudre a priori la plupart des situations préjudiciables (obligations particulières du licencié, problèmes d'incompatibilité, failles au sein des licences, etc.).

<!-- NOTES -->

[^partdeuxchaptrois2]: «&nbsp;The _user program_ exception is not an exception at all, for example, it's just a more clearly stated limitation on the _derived work_ issue&nbsp;», [courriel de Linus Torvald](https://oss.oracle.com/projects/rhel3kernels/src/releases/2.4.21-15.40.1.EL/SOURCES/COPYING.modules) daté du 19 oct. 2001, _Re: GPL, Richard Stallman, and the Linux kernel_. Le [texte ajouté par l'auteur à la licence](https://www.kernel.org/pub/linux/kernel/COPYING)&nbsp;: «&nbsp;NOTE! This copyright does *not* cover user programs that use kernel services by normal system calls - this is merely considered normal use of the kernel, and does *not* fall under the heading of 'derived work'.&nbsp;»

[^partdeuxchaptrois3]: Tel Sencha qui offre une exception pour les applications différentes de l'exception pour le Framework (plus ouverte).

[^partdeuxchaptrois4]: Ceci valant bien sûr pour les licences dites permissives, mais aussi pour toute licence _copyleft_ puisque le _copyleft_ ne perpétue que les termes _stricto sensu_ de la licence. Enfin, cette remarque n'est pas valable si la clause additionnelle contient aussi des obligations supplémentaires.

[^partdeuxchaptrois5]: Dans un article dédié, la troisième version de la GNU GPL invite même à user de cette faculté sur ses propres contributions (en distinguant d'une part les permissions additionnelles qui peuvent être ajoutées sans limitation et les termes supplétifs à tirer parmi une liste de sept types de clauses).

<!-- /NOTES -->

###### Le choix du libre choix : les multilicences

On parle de multilicence lorsqu'une seule et même création est simultanément disponible sous différentes licences&nbsp;: qu'elles soient toutes _open source_ ou qu'au moins l'une d'elles le soit. On ne parle plus de «&nbsp;double licence&nbsp;» lorsque la licence _open source_ n'est qu'une option au côté de licences propriétaires classiques. Multiplier les licences permet généralement d'associer leurs avantages&nbsp;: assurer une compatibilité au bénéfice de plusieurs licences, bénéficier de la renommée de l'une, consolider la cession de droits, etc. 

Contrairement à ce que beaucoup semblent croire, il s'agit d'une technique simple et efficace&nbsp;: 

   1. le contenu sous licence est dès lors compatible avec la totalité des licences qui lui sont adjointes &ndash;&nbsp;auxquelles se rajoutent les licences avec lesquelles celles-ci sont déjà elles-mêmes compatibles&nbsp;;
   2. le licencié dispose donc de beaucoup plus de droits &ndash;&nbsp;dès lors qu'il respecte au moins l'une des licences. En quelque sorte, cette pratique permet d'ajouter une liberté au licencié qui est celle du choix de la licence à laquelle il se soumet (chaque usage fait de la création doit être conforme au moins à l'une des licences)&nbsp;;
   3. conséquence du point précédent, cette pratique permet de limiter le _copyleft_ global qui s'applique à l'œuvre par cela même que, le licencié pouvant utiliser tout droit compris dans l'une au moins des licences, ce sont les dispositions de la licence la plus permissive qui l'emportent souvent[^partdeuxchaptrois6]&nbsp;;
   4. enfin, en termes de sécurité juridique&nbsp;: si l'une des licences devait être annulée par une juridiction nationale, le licencié pourrait toujours revendiquer les droits conférés par l'autre[^partdeuxchaptrois7] (c'est aussi une source de prévisibilité pour celui qui utilise au moins une licence assurément valide &ndash;&nbsp;qui pourrait par exemple souhaiter utiliser une licence en langue française, conforme à son droit national, etc.).

C'est donc une solution qui, utilisée à bon escient par les auteurs, peut permettre optimiser la diffusion des créations et faciliter les contributions. Enfin, les motivations ne sont pas uniquement d'ordre juridique et il est possible de constater des situations où l'une des licences «&nbsp;contenant&nbsp;» déjà la seconde, la réunion des deux ne confère ainsi aucune prérogative spéciale au licencié[^partdeuxchaptrois8]. Inutile juridiquement, mais utile en termes de communication…


<!-- NOTES -->

[^partdeuxchaptrois6]: Une double licence MPL/GNU GPL permet d'appliquer les deux licences, ou l'une au choix, dans les limites du _copyleft_ de la MPL.

[^partdeuxchaptrois7]: Par exemple, en utilisant conjointement les licences GNU GPL/CeCILL ou BSD/CeCILL-B, puisque les secondes sont expressément conformes au droit français.

[^partdeuxchaptrois8]: L'exemple révélateur est le navigateur Firefox, sous MPL, GNU LGPL et GNU GPL. Si la double licence MPL/LGPL est sans conteste utile, l'ajout de la licence GNU GPL semble l'être beaucoup moins puisque tout code sous GNU LGPL peut expressément être licencié sous GNU GPL.

<!-- /NOTES -->

Pour finir, ce mécanisme n'est pérenne dans son application sur un projet qu'autant que l'ensemble des contributions se fasse _a minima_ sous licence multiple (quitte à ce que celles qui ne le seraient pas soient réécrites), ou licence permettant ces licences multiples (par exemple des licences du type MIT ou BSD).

![Différentes techniques appliquées à une même licence](images/tableau_technique_licence.png)



#### Les conditions relatives à l'ajout d'une licence

L'ajout d'une licence libre à une création peut être du fait volontaire d'une personne physique ou morale qui diffuse l'œuvre (par exemple en application d'une politique globale à l'échelle de son entreprise ou du projet, etc.) ou par application des contraintes d'une licence (clause dite _copyleft_) qui imposerait l'extension des termes à d'autres composants (généralement du fait de leur combinaison ou d'une relation d'utilisation).

Quel que soit le contexte, celui qui diffuse une création selon les termes d'une licence _open source_ doit veiller à être en capacité de le faire. Il ne s'agit pas ici de savoir s'il a la capacité d'opérer sur le marché, mais de savoir si cela se fait en conformité avec les différents droits de propriété intellectuelle qui peuvent porter sur la création &ndash;&nbsp;les licences libres n'étant en effet que des outils juridiques dont l'effectivité repose sur la possession de droits de propriété intellectuelle suffisants. Deux statuts peuvent exister&nbsp;:

   1. celui de titulaire des droits&nbsp;;
   2. celui de cessionnaire.

Finalement, un tel ajout est peu complexe vis-à-vis des créations que l'on contrôle personnellement (3.1.1.2.a), mais il en va autrement en présence de créations tierces soumises au respect de licences particulières (3.1.1.2.b).

##### L'ajout d'une licence sur ses propres créations

Le titulaire des droits peut être le créateur originaire (ou son employeur si l'œuvre est créée «&nbsp;dans l'exercice de ses fonctions ou d'après les instructions de son employeur&nbsp;» (cf. _supra_) ou une personne qui se serait fait céder l'intégralité des droits (par exemple le bénéficiaire de la création dans le cadre d'un contrat de commande lorsqu'une telle répartition des droits est prévue). On ne saurait trop conseiller à une personne morale (société, association, etc.) de vérifier les droits qu'elle détient (par contrat, dévolution automatique ou du fait de ses propres démarches en cas de dépôts de brevet, marques, etc.).

Le titulaire des droits va ainsi user de ses prérogatives patrimoniales[@Vivant2005a] afin d'organiser le partage de ses droits gracieusement[^partdeuxchaptrois9] au profit de détenteur de support ou de l'utilisateur de la création sur laquelle porte la licence. Cette cession non-exclusive n'empêche aucune autre exploitation ultérieure&nbsp;:

<!-- NOTES -->

[^partdeuxchaptrois9]: Art. L122-7 CPI prévoit la cession de ces droits à titre onéreux ou gratuit, dans la limite de ce qui est expressément stipulé dans le contrat.

<!-- /NOTES -->

   - le titulaire des droits qui communique son œuvre sous licence libre peut aussi (concomitamment ou ultérieurement) la diffuser d'une façon tout autre, et pas nécessairement libre ou _open source_&nbsp;;
   - le contributeur qui doit diffuser sous licence libre ses propres contributions peut cumulativement le faire sous une autre licence, voire sous une licence non libre (ou _open source_) s'il trouve à les réutiliser dans d'autres contextes (pour résumer&nbsp;: sa contribution restera  _a minima_ aussi libre).


----------------------------------

__Note__

Il y a donc une grande différence de situation entre la (ou les) personne(s) titulaire(s) de droit(s) et les personnes cessionnaires (en capacité d'exploiter l'œuvre). Ainsi la création serait véritablement libre lorsque, au surplus d'être soumise à une licence, elle est aussi partagée entre de multiples auteurs&nbsp;: la création devenant alors quasiment autonome &ndash;&nbsp;une _res communis_ qui, de par sa nature, ne peut être appropriée&nbsp;&ndash; appartenant à tous, donc à personne.

----------------------------------



----------------------------------

__L'œuvre d'un mineur__

L'auteur est celui qui crée l'œuvre originale&nbsp;: enfant, adulte, peu importe. Néanmoins, la question de sa capacité à s'engager se pose lorsque le concédant en est incapable (notamment entre enfant ou représentant légal).

La réponse est en deux temps, selon qu'il s'agit du droit moral ou du droit patrimonial… 

En tant qu'auteur, le contrat est soumis à l'autorisation écrite de l'auteur (droit moral de divulgation), mais, en tant qu'incapable mineur, l'enfant ne peut pas exploiter son œuvre (droit patrimonial), car c'est un engagement qui dépasse les seuls actes de la vie courante et qui doit donc être confié à ses représentants. 

Ainsi, pour mettre sous licence libre l'œuvre d'un mineur (ou d'un quelconque incapable), il faut réunir les deux signatures&nbsp;: celle de l'auteur et celle de son représentant (on peut noter que la seconde est moins importante puisque la seule action disponible est l'action en rescision pour lésion&nbsp;: si l'acte est pécuniairement désavantageux pour le mineur, alors même que les 
licences libres sont en principe sans considération économique). 

----------------------------------

##### L'ajout d'une licence sur d'autres composants _open source_ et les situations d'incompatibilité

Le second statut, celui de cessionnaire d'une licence, est régi par contrat et est généralement assorti d'un certain nombre de conditions&nbsp;: qu'il s'agisse d'une autre licence _open source_ ou d'une cession limitée (il peut, par exemple, ne disposer que du droit de céder les droits, sans possibilité d'en jouir lui-même). 

Les conditions peuvent être plus ou moins contraignantes, mais il faut garder à l'esprit qu'il est impossible de simplement «&nbsp;remplacer&nbsp;» une licence et, ainsi, que toute utilisation d'une nouvelle licence doit respecter celles préexistantes &ndash;&nbsp;c'est la raison pour laquelle on parle d'ajouter une licence «&nbsp;_au surplus_ de celle(s) déjà existante(s).&nbsp;»

Ainsi, lorsque plusieurs licences nécessitent leur extension à un même composant, il convient de régler en amont les problèmes de compatibilité entre elles (la situation la plus simple étant lorsqu'une telle compatibilité est expressément assurée au sein de la licence) &ndash;&nbsp;en déterminant dans quelle mesure la distribution sous une licence spécifique respecte les autres licences&nbsp;&ndash; afin de vérifier ensuite que l'ajout est bien possible au regard de la licence d'origine.

Il convient donc de déterminer les situations de superposition et, à défaut d'une compatibilité expresse, de vérifier l'existence d'une compatibilité logique entre les différentes licences (c'est-à-dire la possibilité de respecter l'une en utilisant l'autre, généralement parce qu'elle n'oblige pas moins et ne donne pas plus de droits). Cette problématique est relativement simple lorsque les licences font partie d'une même famille de licences[^partdeuxchaptrois10], mais devient rapidement plus complexe lorsque les licences sont d'origines diverses. La dernière version de la GNU GPL (v.&nbsp;3) s'appuie sur ce principe pour accueillir en son sein une souplesse et une modularité qui lui permettent d'assurer la compatibilité à l'égard de licences libres et _open source_ auparavant incompatibles[^partdeuxchaptrois11]&nbsp;: en permettant, sur chaque nouvelle contribution, d'une part, l'ajout de _permissions additionnelles_ et, d'autre part, l'ajustement par l'utilisation de certains _termes supplétifs_ limitativement autorisés[^partdeuxchaptrois12].

<!-- NOTES -->

[^partdeuxchaptrois10]: La plus connue est certainement la famille des licences GNU (GPL, LGPL, AGPL, etc.), mais bien d'autres peuvent être citées pour l'exemple&nbsp;: CeCILL (CeCILL-A, CeCILL -B, CeCILL -C), OSL (OSL, AFL), etc.

[^partdeuxchaptrois11]: Notamment les licences plus permissives comme les licences Apache, LaTeX, etc.


[^partdeuxchaptrois12]: Il convient donc de confronter chaque licence aux différentes clauses, au cas par cas, afin d'être certain de leur compatibilité &ndash;&nbsp;avec le risque d'une divergence d'interprétation, comme c'était déjà le cas les licences GPL et Apache.

<!-- /NOTES -->


Néanmoins, il peut arriver dans certaines situations que les obligations soient contradictoires et inconciliables (impossibles à respecter simultanément), y compris en présence seulement de composants _open source_, on parle alors d'_incompatibilité_ entre les licences&nbsp;: la création ainsi composée ne peut être exploitée en respectant cumulativement toutes les licences. Parfois, la lecture des licences peut permettre, matériellement[^partdeuxchaptrois13] ou techniquement, de résoudre certaines incompatibilités (par exemple dans l'hypothèse de certaines formes de distribution[^partdeuxchaptrois14], certains modes de distribution[^partdeuxchaptrois15] et certaines constructions de la création[^partdeuxchaptrois16]). Mais de tels contournements compliquent la compréhension de la licence et ne sont généralement pas souhaitables &ndash;&nbsp;ou possibles&nbsp;&ndash; et, à défaut de solution à cette incompatibilité, il faudra renoncer à l'utilisation d'un composant (ce qui revient souvent à le réécrire), voire à la diffusion d'un ensemble de composants, ou encore se rapprocher de l'auteur (ou des auteurs[^partdeuxchaptrois17]) de la création afin qu'il consente soit à une exception expresse[^partdeuxchaptrois18] indiquant à quel logiciel il entend ne pas étendre sa licence[^partdeuxchaptrois19] (dans un fichier supplémentaire distribué avec le logiciel et sa licence), soit à l'utilisation d'une autre licence[^partdeuxchaptrois20].


<!-- NOTES -->

[^partdeuxchaptrois13]: Les licences modulaires du type MPL sont justement optimisées en ce sens puisqu'elles permettent, par leur étendue limitée aux seuls fichiers, la conception de logiciels complexes soumis à différentes licences, ce qui réduit la nécessité de clause particulière assurant leur compatibilité. À noter néanmoins que la seconde version de la MPL devrait organiser une compatibilité au profit des licences GNU (le problème venant du fait que celles-ci ont des étendues très larges qui favorisent les situations d'incompatibilité).

[^partdeuxchaptrois14]: Par exemple un exécutable, tant que les sources des modifications sont disponibles par ailleurs.

[^partdeuxchaptrois15]: On pense notamment aux logiciels dont seul le client est distribué alors que le serveur est hébergé chez l'éditeur.


[^partdeuxchaptrois16]: Par exemple la construction modulaire pour l'utilisation de composants sous licence du type MPL, voire LGPL.

[^partdeuxchaptrois17]: Le nombre et la dispersion des auteurs et contributeurs restant néanmoins un écueil notable.

[^partdeuxchaptrois18]: Qui n'est en réalité qu'un avenant au contrat.

[^partdeuxchaptrois19]: Des exemples d'exceptions sont proposés par la [FAQ de la GPL](http://www.gnu.org/licenses/gpl-faq.html)&nbsp;: «&nbsp;Linking ABC statically or dynamically with other modules is making a combined work based on ABC. Thus, the terms and conditions of the GNU General Public License cover the whole combination. In addition, as a special exception, the copyright holders of ABC give you permission to combine ABC program with free software programs or libraries that are released under the GNU LGPL and with independent modules that communicate with ABC solely through the ABCDEF interface. You may copy and distribute such a system following the terms of the GNU GPL for ABC and the licenses of the other code concerned, provided that you include the source code of that other code when and as the GNU GPL requires distribution of source code. Note that people who make modified versions of ABC are not obligated to grant this special exception for their modified versions; it is their choice whether to do so. The GNU General Public License gives permission to release a modified version without this exception; this exception also makes it possible to release a modified version which carries forward this exception&nbsp;».

[^partdeuxchaptrois20]: Sur ces points, voir aussi [Software Freedom Law Center](http://www.softwarefreedom.org/resources/2007/gpl-non-gpl-collaboration.html), _Maintaining Permissive-Licensed Files in a GPL-Licensed Project: Guidelines for Developers_, 2007.


<!-- /NOTES -->



------------------------------
 
__La théorie des ensembles et la compatibilité__

  
Cette réflexion peut se traduire mathématiquement grâce à la théorie des ensembles sous la forme qui suit&nbsp;: la licence B est dite compatible (c'est-à-dire qu'elle peut être utilisée pour redistribuer le logiciel en respectant les termes de la licence originaire A) si et seulement si l'ensemble des droits de la licence B est inclus dans la licence A et que l'ensemble des obligations de la licence A est inclus dans la licence B.

------------------------------

### Respecter le formalisme lié à l'utilisation des licences libres

La maîtrise effective des éléments constitutifs de la création est essentielle dans les projets _open source_ puisque ce n'est que lorsque l'utilisateur est matériellement en mesure d'en user que les droits cédés par la licence trouvent leur utilité[^partdeuxchaptrois20] &ndash;&nbsp;rendant indispensable l'accès à un certain nombre d'éléments matériels (code source, documents préparatoires, scripts, etc.).

Ainsi, au-delà de la simple cession de droits, les licences libres et _open source_ contiennent généralement un ensemble de dispositifs pratiques qui ont pour fonctions principales d'assurer aux utilisateurs une bonne information (3.1.2.1) et une réception effective de la création (3.1.2.2). C'est sur leur fondement que la cour de Munich avait, courant 2007, rendu une décision en ce sens lors de l'affaire Welte vs. Skype Technologies SA, condamnant la société Skype qui n'incluait ni une copie de la GNU GPL ni le code source correspondant au binaire conformément au texte de la licence (Skype incluait néanmoins l'URL de celui-ci par l'intermédiaire d'un flyer).


<!-- NOTES -->

[^partdeuxchaptrois20]: Voir/écouter à cet égard <span style="font-variant:small-caps;">Peterson</span> (Scott), Senior Counsel Hewlett-Packard Company, «&nbsp;Current trends in the hardware sector: the HP Experience&nbsp;», EOLE 2010. Ainsi que <span style="font-variant:small-caps;">Marr</span> (Dave) (Director Legal , Open Source Group Products and Technology Law, Sun Microsystems, Inc), «&nbsp;GPLv3 from an Embedded Industry Perspective &nbsp;», EOLE 2009.

<!-- /NOTES -->

#### Le respect du formalisme assurant une bonne information

La reconnaissance par les pairs, ainsi que l'entretien d'une «&nbsp;image&nbsp;» liée à leurs activités créatrices (pour des raisons artistiques ou économiques), sont des éléments moteurs pour de nombreux individus. Les mentions légales, obligatoires, y pourvoient, mais sans indiquer précisément quelles sont les actions attendues et quel formalisme doit accompagner la réutilisation et la diffusion de leurs œuvres (les juges appréciant au regard des «&nbsp;usages du métier&nbsp;»).

C'est ce manque &ndash;&nbsp;moins présent pour les œuvres non logicielles[^partdeuxchaptrois21]&nbsp;&ndash; que comblent les contraintes des licences relatives au formalisme, sous la forme d'une série d'obligations qui assurent une bonne information quant à l'origine du code et des conditions de son exploitation auprès des utilisateurs. Ces obligations vont parfois plus loin que les simples mentions légales &ndash;&nbsp;telles les clauses dites «&nbsp;de publicité&nbsp;» qui s'étendent à tous les documents commerciaux publicitaires relatifs au logiciel qui les contient.


<!-- NOTES -->

[^partdeuxchaptrois21]: Ce qui explique qu'elles imposent un formalisme beaucoup plus léger, qui peut le plus souvent être rempli par l'indication du titre de l'œuvre, son auteur, sa date, la licence et un lien vers l'œuvre originale. Les exemples qu'elles fournissent sont généralement très simples à mettre en œuvre (voir notamment la LAL ou la GNU FDL).

<!-- /NOTES -->

Ainsi, il est possible de distinguer les obligations opérant une mise à disposition passive des informations légales (3.1.2.1.a) et celles contraignant à un affichage actif (3.1.2.1.b).

##### La mise à disposition passive des informations légales

Les informations légales (y compris le texte des licences) figurent dans les en-têtes des fichiers et (si nécessaire) dans des fichiers joints aux sources.

De manière générale, tout fichier (comprenant du code sous licence libre ou non) devrait contenir un en-tête affichant les «&nbsp;mentions légales minimums&nbsp;»&nbsp;: c'est-à-dire rappelant le nom et la qualité du titulaire de droits, la date de la création (et éventuellement des ajouts) et les licences utilisées. Une mention excluant toute garantie est aussi à prévoir dans le cadre des licences libres. Elle peut être assez courte pour les petits fichiers, et reprendre l'intégralité de la clause d'exclusion de garantie de la licence utilisée pour les fichiers plus importants.

Pour éviter d'alourdir inutilement le code distribué, toutes les mentions trop longues pour être insérées en l'état dans chaque en-tête peuvent être transférées dans des fichiers joints aux sources&nbsp;:

   - les textes des licences[^partdeuxchaptrois22], leurs éventuelles traductions et modalités spécifiques d'application (fichier license(s).txt)&nbsp;;
   - le fichier explicatif permettant à l'utilisateur ou au licencié de comprendre où trouver les informations qu'il recherche, le fonctionnement du projet, comment contribuer au projet, les éventuels composants soumis à d'autres licences, etc. (fichier readme.txt)&nbsp;;
   - la liste exhaustive des contributeurs originaux et subséquents au logiciel, avec les dates de chacune de leur contribution (fichier authors.txt)&nbsp;;
   - les autres informations (documentation du logiciel &ndash;&nbsp;qui rappellera par ailleurs les mentions légales du logiciel&nbsp;&ndash;, une FAQ &ndash;&nbsp;qui permettra de lever toute ambiguïté&nbsp;&ndash;, etc.).


Il s'agit ici de bon sens et de bonnes pratiques, les licences n'imposant généralement que des mentions «&nbsp;raisonnables&nbsp;»[^partdeuxchaptrois23] de ces éléments, d'autres fichiers peuvent venir compléter cette liste&nbsp;: changelog.txt, legal.txt, export.txt, etc.

<!-- NOTES -->

[^partdeuxchaptrois22]: Certaines, très courtes, telles les licences BSD, peuvent néanmoins se retrouver en en-tête.

[^partdeuxchaptrois23]: Voir le texte de la GNU GPL v.&nbsp;3, Art.&nbsp;7&nbsp;: «&nbsp;b) Exigeant le maintien de mentions légales spécifiées ou de mentions d'attribution de paternité spécifiées raisonnables au sein de cette contribution ou dans les Mentions Légales Appropriées affichées par les créations la contenant&nbsp;; c) Interdisant une indication erronée de l'origine de cette contribution, ou exigeant que les versions modifiées de cette contribution soient marquées de façon raisonnable comme étant différent de la version originale&nbsp;; ou (…).&nbsp;»

<!-- /NOTES -->

------------------------------------
 
__Faut-il impérativement utiliser le signe ©&nbsp;?__

En matière de copyright, le droit américain s'est longtemps différencié du système latin du droit d'auteur, et ceci notamment en conditionnant l'action en justice à un enregistrement des œuvres auprès de l'United States Copyright Office. 

En parallèle, et afin de reconnaître des droits aux auteurs étrangers dont les œuvres n'étaient pas soumises à ce formalisme, une procédure plus légère fut assimilée à cet enregistrement, consistant en l'apposition d'une mention comportant «&nbsp;de façon nette le symbole ©, accompagné du nom du titulaire du droit d'auteur et de l'année de publication de l'œuvre.&nbsp;»

Depuis l'adhésion des États-Unis à la Convention de Berne, en 1989, un assouplissement du
 formalisme américain a rapproché celui-ci du système du droit d'auteur qui protège les œuvres du simple fait de leur conception. Ainsi, une simple mention de l'auteur et de la date de conception devrait permettre à toute personne de revendiquer ses droits. 

Néanmoins, cette _notice de copyright_ doit être considérée comme une présomption de titularité des droits, et la rédaction «&nbsp;à l'américaine&nbsp;», notamment recommandée par l'article III.1 de la Convention Universelle, conserve ainsi une certaine utilité.

------------------------------------

##### L'affichage actif des mentions légales

Dépassant l'affichage classique des mentions légales, quelques licences demandent aux licenciés de s'assurer par un comportement actif que les utilisateurs auront bien connaissance des mentions légales, de la licence, etc.

Ainsi peut-on regrouper les clauses qui ont pour vocation d'assurer&nbsp;:

   - _la visibilité de l'affichage des mentions légales_. Les licences peuvent demander à ce que les mentions légales soient clairement affichées&nbsp;: à certains moments et dans certains contextes (telle la GNU GPL en présence d'interface utilisateur interactive[^partdeuxchaptrois24]) ou telles qu'elles étaient affichées à la réception de l'œuvre (telles les licences Yahoo Public License ou Zimbra Public License[^partdeuxchaptrois25])&nbsp;;
   - _l'affichage d'attributions particulières_. Ces clauses vont un peu plus loin que les simples mentions légales et demandent que soient ajoutées certaines mentions ou phrases lors de la distribution et/ou l'utilisation du logiciel[^partdeuxchaptrois26]&nbsp;;
   - _la publicité autour du logiciel_. Ainsi était-ce notamment le cas de la licence Apache version&nbsp;1.0 ou de la version initiale de la BSD (4-clause BSD) &ndash;&nbsp;ces deux licences étant encore utilisées sur le logiciel Truecrypt[^partdeuxchaptrois27]. Ces clauses, bénignes à leur origine, deviennent lourdes de conséquences lorsque leurs effets se cumulent ou s'accroissent. Ainsi en est-il lors de la multiplication de clauses de publicité, la plus renommée pour sa dégénérescence étant celle de la licence BSD[^partdeuxchaptrois28]. Elle contraignait à citer le donneur de licence dans toute publicité relative au logiciel ou à son utilisation, provoquant de lourds problèmes lorsque les contributeurs choisirent d'utiliser cette licence en modifiant la citation en leur faveur&nbsp;: la multiplication des citations devint rapidement extrêmement fastidieuse et gênante. La FSF s'est rapidement prononcée contre l'«&nbsp;[odieuse clause de publicité BSD](http://www.gnu.org/philosophy/bsd.html)&nbsp;» (Richard Stallman rapporte ainsi avoir décompté en 1997 plus de 75 mentions publicitaires obligatoires attachées à la distribution de NetBSD).

<!-- NOTES -->

[^partdeuxchaptrois24]: Une interface utilisateur interactive affiche des «&nbsp;Mentions Légales Appropriées&nbsp;» dans la mesure où elle inclut un dispositif pratique et visible de façon proéminente qui (1) affiche une mention de droit d'auteur appropriée et (2) indique à l'utilisateur qu'il n'y a aucune garantie portant sur la création (sauf si des garanties sont accordées), que les licenciés peuvent transmettre la création sous cette licence, et comment voir une copie de cette licence. Si l'interface intègre une liste de commandes ou d'options utilisateur, tel qu'un menu, un élément proéminent dans la liste remplit ce critère.

[^partdeuxchaptrois25]: «&nbsp;3 &ndash;&nbsp;Intellectual Property Rights (…) 3.2&nbsp;&ndash; In any copy of the Software or in any Modification you create, You must retain and reproduce, any and all copyright, patent, trademark, and attribution notices that are included in the Software in the same form as they appear in the Software. This includes the preservation of attribution notices in the form of trademarks or logos that exist within a user interface of the Software.&nbsp;»

[^partdeuxchaptrois26]: Par exemple&nbsp;: «&nbsp;This product includes PHP software, freely available from ``http://www.phpnet/software/``&nbsp;» ou «&nbsp;RSA Data Security, Inc. MD5 Message-Digest Algorithm&nbsp;» ou «&nbsp;derived from the RSA Data Security, Inc. MD5 Message-Digest Algorithm&nbsp;», pour toute distribution du logiciel modifié.

[^partdeuxchaptrois27]: Ce qui oblige à cumuler les deux mentions suivantes&nbsp;: «&nbsp;This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](http://www.openssl.org).&nbsp;»&nbsp;; «&nbsp;This product includes cryptographic software written by Eric Young (``eay@cryptsoft.com``).&nbsp;»

[^partdeuxchaptrois28]: Qui figurait dans son article 3&nbsp;: «&nbsp;All advertising materials mentioning features or use of this software must display the following acknowledgement: This product includes software developed by the University of California, Berkeley and its contributors.&nbsp;», supprimé en 1999 par l'Université de Californie.

<!-- /NOTES -->

#### Le respect du formalisme assurant une réception effective de l'œuvre

Il s'agit ici du code source correspondant (3.1.2.2.a), de la documentation (3.1.2.2.b) et tout autre élément utile pour l'appréhension de la création (3.1.2.2.c).

##### Le code source correspondant

De nombreuses licences définissent la notion de code source comme la forme de la création préférée pour faire des modifications sur celle-ci. 

Les licences vont dorénavant plus loin et la GNU GPL requiert la «&nbsp;source correspondante&nbsp;» du logiciel fourni en exécutable, défini comme étant «&nbsp;tout le code source nécessaire pour générer, installer et (pour une création exécutable) exécuter le code objet et modifier la création, y compris les scripts pour contrôler ces activités&nbsp;». Les bibliothèques systèmes et autres éléments habituellement disponibles dans un environnement de développement sont cependant exclus pour des raisons pratiques.

Le plus simple est généralement que la source accompagne le binaire (ou soit disponible sur le même serveur). Or, ce n'est cependant pas toujours possible ou souhaité et d'autres alternatives sont généralement proposées&nbsp;: telle l'offre de fournir les sources correspondantes à la demande (mais avec d'autres problématiques comme le délai raisonnable de cette communication des sources).

-----------------------------------
 
__Non respect de la GNU GPL sur GNU EMACS ?__

Il est toujours bon de se rappeler que même les meilleurs sont faillibles. Ainsi, RMS a récemment publié un article annonçant que plusieurs versions de son logiciel GNU Emacs ne respectaient pas la GNU GPL ([Emacs distributions are not GPL-compliant](http://lists.gnu.org/archive/html/emacs-devel /2011-07/msg01155.html))&nbsp;:


	From: Richard Stallman
	Subject: Re: Compiled files without sources????
	Date: Thu, 28 Jul 2011 19:00:17 -0400

	They are in Emacs releases 23.2 and 23.3.
	They have been in all pretests since 
	emacs-23.1.90, dated 2009-12-09. They
	were merged into the Emacs trunk 
	in bzr 97804, dated 2009-09-28;
	here's a URL for that: (URL).

	We have made a very bad mistake. Anyone
	redistributing those versions is violating
	the GPL, through no fault of his own.

	We need to fix those releases retroactively
	(or else delete them), and we need to do it
	right away.

	I see two quick ways to fix them: to delete the
	compiled files, or to add the sources they are
	made from.
	--
	Dr Richard Stallman

	President, Free Software Foundation

Bien entendu, cette erreur est aujourd'hui corrigée.

----------------------------------------

##### La documentation

La documentation d'un code et d'un logiciel (ou d'une création utilitaire qui sera ou non amenée à évoluer) est une condition nécessaire à sa bonne prise en main. Deux types de documentation peuvent être distribués&nbsp;:

   - la documentation relative à l'installation et au paramétrage du logiciel. Son statut juridique est calqué sur celui du logiciel et certaines licences imposent sa communication dans les mêmes termes (notamment l'OSL)&nbsp;;
   - la documentation «&nbsp;utilisateur&nbsp;» qui est protégée de manière indépendante et pour laquelle la société peut parfaitement utiliser une licence différente (la GNU FDL étant généralement la plus adaptée en raison de son étendue très large qui permet d'assurer de conserver une documentation entièrement libre).

##### Autres éléments

Enfin, dans l'hypothèse où certains composants pourraient être _certifiés_ (ou simplement qualifiés, selon le secteur industriel), la problématique d'une mutualisation des coûts engendrés par cette certification peut venir s'ajouter aux réflexions sur l'_open source_&nbsp;: le matériel de certification pourra ainsi être librement communiqué (afin de favoriser la diffusion et utilisation du logiciel) ou, au contraire, être réservé à un groupe de sociétés afin de mutualiser le coût au sein d'une communauté d'utilisateurs. Ces problématiques sont très fortes dans des secteurs tels l'aéronautique, l'aérospatiale, le ferroviaire, l'automobile, etc.

## Diffuser sous licences libres

Le courant des licences libres, malgré sa jeunesse et sa relative complexité, a rapidement donné naissance à un nouveau système. Ainsi, c'est l'organisation des acteurs privés qui doit être examinée (3.2.1) avant de se pencher sur l'organisation relative à la diffusion du logiciel sous licence libre (3.2.2).

### Se positionner dans l'écosystème du logiciel libre

  Par leur organisation, les acteurs privés ont dessiné un nouveau système dont il convient de présenter les acteurs (3.2.1.1) et les interactions qui le caractérisent (3.2.1.2)[^partdeuxchaptrois29].

<!-- NOTES -->

[^partdeuxchaptrois29]: On pourra accessoirement se reporter au Rapport Ernst&amp;Young, _Open source software in business-critical environments_, 2011 (sur [www.ey.com](http://www.ey.com)).

<!-- /NOTES -->

#### Les acteurs du système du logiciel libre

Les licences libres ne sont que des outils. Le corollaire est que tous les types de personnes (physiques ou morales, privées ou publiques, de tout secteur ou métier) les utilisent, avec une pluralité de motivations, mais au profit de la constitution d'un «&nbsp;pot commun&nbsp;» qui les réunit (chacun étant libre d'y verser comme d'y puiser). Les individus, les associations et autres organismes à but non lucratif ont souvent un rapport au Libre complexe qui mêle philosophie, idéologie, et des arguments plus raisonnés comme le coût ou l'indépendance qu'offrent les solutions logicielles libres. Tandis que les entreprises, neutres par essence[@Frison-Roche2011], ainsi que les collectivités et administration adoptent le Libre par opportunité et pragmatisme (les logiciels libres assurant, outre une maîtrise des coûts, les avantages d'une grande flexibilité et d'un développement rapide).

Parmi tous les courants et même s'il n'est peut-être pas le plus connu du grand public (le mouvement de l'Open Data est par exemple «&nbsp;très vendeur&nbsp;»), le secteur le plus avancé et structuré est incontestablement celui du logiciel&nbsp;: 50% des entreprises interrogées par Gartner[^partdeuxchaptrois30] ont adopté les logiciels libres dans le cadre de leur stratégie informatique. Ainsi, l'industrie du logiciel libre devrait représenter 10% du marché de demandes en logiciels et services français d'ici 2 ans[^partdeuxchaptrois31] (renforçant ainsi la compétitivité de la France en matière de développement de logiciels).

Les développements qui suivent seront donc dédiés au système qui caractérise le logiciel libre. On s'aperçoit que les frontières entre les différents acteurs (éditeurs des logiciels, intégrateurs, constructeurs et utilisateurs) sont beaucoup moins étanches que dans le secteur traditionnel du logiciel&nbsp;: les éditeurs intègrent de plus en plus de composants _open source_ dans leurs logiciels, les intégrateurs peuvent prendre le rôle d'éditeur vis-à-vis de leur client (support de niveau 3, développement de nouvelles fonctionnalités, etc.) et les utilisateurs eux-mêmes se réunissent en «&nbsp;une communauté d'utilisateurs éditrice&nbsp;»[@Elie2009]. Néanmoins, si on distingue les entreprises simples utilisatrices de composants _open source_ de celles qui orientent leur modèle économique en rapport avec cet usage, et qu'on se concentre sur ces dernières seulement, on peut distinguer différents rôles&nbsp;: éditeurs (3.2.1.1.a), intégrateurs (3.2.1.1.b), constructeurs (3.2.1.1.c), grands utilisateurs clients (3.2.1.1.d), fondations  et communautés (3.2.1.1.e) et centres de recherche (3.2.1.1.f).


<!-- NOTES -->

[^partdeuxchaptrois30]: «&nbsp;Gartner Survey Reveals More than Half of Respondents Have Adopted Open-Source Software Solutions as Part of IT Strategy&nbsp;», Fevrier 2011 (sur [www.gartner.com](http://www.gartner.com)).

[^partdeuxchaptrois31]: Étude OPIIEC Mars 2009&nbsp;: «&nbsp;Les métiers du logiciel libre en France&nbsp;» (sur [www.syntec-informatique.fr](http://www.syntec-informatique.fr/)) &ndash;&nbsp;tendance 2008-2009 du logiciel libre, [www.ob2l.com](http://www.ob2l.com/)). Voir aussi le _Rapport de la Commission pour la libération de la croissance française_, sous la présidence de Jacques Attali,  _La documentation française_, 2008 ([lesrapports.ladocumentationfrancaise.fr](http://lesrapports.ladocumentationfrancaise.fr/BRP/084000041/0000.pdf)).

<!-- /NOTES -->

##### Les éditeurs _open source_

Il s'agit ici de l'entreprise distribuant sous licence libre un logiciel qu'elle édite. De multiples adoptions de l'_open source_ coexistent dans le monde de l'édition&nbsp;: en fonction de l'éditeur (et de son histoire), du type de produit édité et de ses utilisateurs. Le choix n'est pas systématique, mais les éditeurs qui souhaitent construire un modèle économique innovant, voire disruptif, ont besoin de s'appuyer sur  une communautés, préexistante ou nouvellement créée, qui va jouer le rôle de soutènement (renforçant le logiciel, se substituant parfois à la société, et constituant une réserve de clients voire de salariés pour la société). À partir de là, le modèle économique de la société est généralement issu d'un équilibre entre ce qui est cédé et le contrôle, plus ou moins fort, conservé par l'éditeur (par un droit exclusif, sur la feuille de route, etc.). Se concentrant sur les seules pratiques juridiques et sans que la liste soit exhaustive, les principaux mécanismes (librement combinables) sont l'usage du droit des marques, la proposition de licence commerciale complémentaire, la mise à disposition décalée ou encore le contrat.

Le plus souvent, les éditeurs assurent la protection de leur produit par l'usage complémentaire du droit des marques[^partdeuxchaptrois32]&nbsp;: le logiciel est librement diffusé sous licence _open source_, mais tout usage de la marque est soumis à autorisation. Cette faculté qu'offre le cumul de droits exclusifs concurrents sur un même objet a ici l'avantage de rendre quasi inexistant le coût d'entrée pour les utilisateurs, tout en assurant à l'éditeur principal un contrôle sur l'évolution, la distribution des copies et l'exploitation globale du logiciel. Dans l'usage de ce droit, il est possible de distinguer les sociétés commerciales qui ont tendance à en user de façon très agressive &ndash;&nbsp;au point parfois de réduire les libertés concédées par la licence _open source_ sur le logiciel[^partdeuxchaptrois33]&nbsp;&ndash; tandis que les structures non commerciales en font un usage plus modéré, équilibré, qui a principalement pour objectif de défendre l'image associée au logiciel[^partdeuxchaptrois34]. Le risque inhérent à ce type d'utilisation du droit des marques est que l'éditeur, trop mercantile, se mette à dos la communauté qui s'émancipe alors en enlevant toute allusion à la marque du logiciel et en reprenant à son compte les logiciels diffusés sous licence _open source_[^partdeuxchaptrois35]. Aux États-Unis, les brevets sont aussi utilisés comme un levier supplémentaire permettant de convaincre les investisseurs et les clients (Novell en étant le meilleur exemple). On observe le même phénomène en Europe, même si l'utilisation des brevets parallèlement à une licence libre reste heureusement un comportement isolé et très critiquable.

<!-- NOTES -->

[^partdeuxchaptrois32]: Cf. _supra_ concernant l'étude du droit des marques.

[^partdeuxchaptrois33]: Un très bon exemple est la société américaine Red Hat&nbsp;: elle n'autorise aucun usage de ses marques, sauf&nbsp;: pour un usage non commercial par des établissements éducatifs, des associations à but non lucratif, aux groupes d'utilisateurs et leurs personnels correspondants&nbsp;; pour un usage personnel ou professionnel issu d'une version originale sous la condition de non-redistribution… Mandriva propose, elle, une licence de marque pour la distribution d'une version non modifiée d'un produit Mandriva lorsque celui-ci est disponible gratuitement sur son site internet.

[^partdeuxchaptrois34]: La Mozilla Foundation limite par exemple l'usage des marques Firefox et Thunderbird selon la version du logiciel (licence complète sur la version binaire non modifiée, licence large pour les versions officielles localisées, licence réduite pour la version communautaire et enfin aucune licence pour une version du logiciel trop modifiée).

[^partdeuxchaptrois35]: Red Hat a ainsi vu naître CentOS, version «&nbsp;expurgée&nbsp;» de la première (opération qui est par ailleurs techniquement compliquée par Red Hat), et Firefox s'est vu opposer Iceweasel (avec un succès plus mitigé) &ndash;&nbsp;aujourd'hui GNU IceCat.

<!-- /NOTES -->


Par ailleurs, il est fréquent que les éditeurs ne fassent pas le choix exclusif de l'_open source_ et développent de façon périphérique des offres commerciales en associant à la version libre des _add-ons_ ou _plug-ins_ (greffon) sous licence commerciale[^partdeuxchaptrois36]. Dans le même esprit, il est possible de proposer le même logiciel sous une licence commerciale présentée comme alternative à la licence _open source_[^partdeuxchaptrois37] ou de proposer un service autour d'une  version non encore distribuée du logiciel (à noter néanmoins que ces deux solutions sont conditionnées au fait que la société détienne tous les droits sur le logiciel[^partdeuxchaptrois38] ou que les licences des composants _open source_ utilisés n'interdisent pas de telles utilisations ou distributions fermées). Dans ce second cas, il est possible de penser à un modèle du type _free cloud_ telle que l'offre _Drupal Garden_ de la société Acquia&nbsp;: un ou plusieurs services fournis sur la plate-forme de l'éditeur (par exemple création et hébergement d'un site) s'harmonisent avec la distribution _open source_ du logiciel puisque l'utilisateur peut à tout moment exporter le code et le contenu générés pour les installer sur sa propre instance. Dans ces hypothèses, mixer licences _open source_ et commerciales[^partdeuxchaptrois39] permet divers montages dans lesquels les communautés continuent à 
trouver leur intérêt à utiliser et collaborer au développement du logiciel grâce à la licence _open source_, tandis que les utilisateurs professionnels préfèrent à terme opter pour une licence commerciale[^partdeuxchaptrois40].

<!-- NOTES -->

[^partdeuxchaptrois36]: Cette pratique est surtout répandue en matière de distribution ou compilation de logiciel, c'est-à-dire des situations où des briques non libres peuvent être mêlées à d'autres qui le sont. C'est notamment le cas de Red Hat et Mandriva.

[^partdeuxchaptrois37]: Encore faut-il que cette licence soit suffisamment contraignante pour intéresser au choix de la licence commerciale. Ce sont les exemples de MySQL AB, Sleepycat Software Inc., TrollTech AS, etc. Ainsi, MySQL AB qui propose MySQL Entreprise sous licence GNU GPL v&nbsp;2 (avec exception en faveur d'autres logiciels libres) ou sous licence propriétaire pour ceux qui ne désirent pas respecter la licence (notamment pour développer ou distribuer un projet propriétaire) ou veulent bénéficier de mises à jour, de service support et assurance.

[^partdeuxchaptrois38]: Ce dont MySQL s'assure en n'intégrant dans le produit que les contributions qu'elle a pu réécrire ou racheter.

[^partdeuxchaptrois39]: Le terme peut sembler ambigu&nbsp;: une licence _open source_ autorise parfaitement un usage commercial du logiciel, mais elle n'en restera pas moins une cession non exclusive gracieuse&nbsp;; à l'inverse, une licence dite commerciale sera conditionnée au paiement d'une souscription quelconque.

[^partdeuxchaptrois40]: À la différence de la licence _open source_ par ailleurs proposée (probablement  _copyleft_ ou tout du moins suffisamment contraignante pour que l'utilisateur ait un intérêt à opter pour la licence commerciale), la licence commerciale de l'éditeur offre aux clients des avantages comme la possibilité de ne pas diffuser le contenu de leur création dérivée (échappant ainsi à la réciprocité afin de continuer de disposer de leur monopole).

<!-- /NOTES -->
 

De façon assez similaire, certaines sociétés proposent des mises à jour plus simples et régulières à leurs clients (non immédiatement accessible aux utilisateurs de la version communautaire)&nbsp;: soit par une mise à disposition systématiquement décalée (de quelques mois ou quelques semaines)&nbsp;; soit par une mise à disposition graduelle des mises à jour pour les clients (alors qu'elles seraient regroupées pour la version complémentaire). Ce décalage peut être matériel ou juridique (les mises à jour ne sont considérées comme _divulguées_ qu'à compter d'une certaine période).

  Enfin, certaines sociétés usent du droit des contrats afin de limiter accessoirement l'utilisateur dans les libertés que lui concède la licence  _open source_&nbsp;: que ce soit lors de la vente de services aux utilisateurs qui souhaitent bénéficier du support et des mises à jour[^partdeuxchaptrois41]  ou dans les rapports entre distributeurs et revendeurs [^partdeuxchaptrois42]. Les contrats sont aussi essentiels pour les logiciels orientés métiers demandant de concevoir plus finement la collaboration entre les différents industriels[^partdeuxchaptrois43]&nbsp;: la licence _open source_ n'étant alors plus qu'une partie du cadre contractuel (s'ils sont concurrents, une licence _copyleft_ sera une condition _sine qua non_ afin d'assurer une relative pérennité et équité dans le développement du logiciel) &ndash;&nbsp;un contrat de consortium complétant éventuellement tous les aspects non couverts par la licence (comité de direction, procédé de développement, prise en compte des orientations, marketing et communication, etc.)

<!-- NOTES -->

[^partdeuxchaptrois41]: C'est notamment le cas de Red Hat avec les produits comme _JBoss Enterprise Middleware_, _Red Hat Directory Server_, _Red Hat Certificate System_, etc.

[^partdeuxchaptrois42]: On retrouve ce type de limitation dans les contrats de MySQL, Ingres, Alfresco, etc. Le revendeur se retrouvant bien souvent contraint de ne pas utiliser ou conseiller la version communautaire.

[^partdeuxchaptrois43]: La licence _open source_ assurera la confiance entre ces derniers vis-à-vis de ce qui est créé et permettra éventuellement à d'autres acteurs de bénéficier d'un coût d'entrée quasi inexistant &ndash;&nbsp;de façon à ce qu'ils puissent par la suite éventuellement rejoindre le cercle des partenaires&nbsp;; par ailleurs, le consortium jouera le rôle d'un contrat d'indivision par lequel les partenaires s'organisent pour la gestion du projet (en amont lors de la création et en aval pour l'exploitation du projet).

<!-- /NOTES -->


---------------------------------------

__Par exemple…__

Révélateur de l'intérêt de l'_open source_, les diverses structures représentatives de l'industrie du logiciel se positionnent progressivement sur le sujet et mettent en place des commissions _open source_. Ainsi, Syntec Numérique a rédigé un [Guide Open Source](http://guideopensource.info) et créé un comité _open source_ avec pour mission de «&nbsp;fixer le cadre contractuel et d'usage en matière de projets informatiques incluant du logiciel libre&nbsp;: comment s'inscrit le logiciel libre dans l'architecture des projets informatiques, en matière technique, juridique, business model, organisationnelle et distribution&nbsp;». À son tour, l'AFDEL qui avait abordé en 2007 les logiciels libres au travers d'un guide («&nbsp;Propriété intellectuelle et logiciels, la position de l'association Française des éditeurs de logiciels&nbsp;»), a récemment mis en place une commission dédiée, présidée par Bertrand Diard (Talend), avec  pour mission de «&nbsp;réunir et fédérer les éditeurs de logiciels en France pour débattre de thèmes spécifiques liés au modèle open source, et rédiger des conclusions et propositions sur ces thèmes&nbsp;». Le Cigref  a aussi récemment publié son guide intitulé «&nbsp;Maturité et gouvernance de l'Open Source&nbsp;: la vision des grandes entreprises&nbsp;» ([www.cigref.fr](http://www.cigref.fr/cigref_publications/2011/03/maturite-gouvernance-open-source-vision-grandes-entreprises.html)).

------------------------------------------

__Microsoft et l'open source__

Le comportement de cette société peut, à divers égards, sembler paradoxal.

   1. Microsoft a ouvertement qualifié le mouvement du logiciel libre de «&nbsp;cancer&nbsp;» avant de rédiger ses propres licences labellisées _open source_ &ndash;&nbsp;Microsoft Public License ([Ms-PL](http://www.microsoft.com/opensource/licenses.mspx)) et Microsoft Reciprocal License ([Ms-RL](http://www.microsoft.com/opensource/licenses.mspx))&nbsp;&ndash; au sein du programme [Shared Source Initiative](http://www.microsoft.com/resources/sharedsource/default.mspx) (initiative destinée à favoriser l'innovation technique, elle permet un accès favorisé au code source des logiciels de la société au profit des clients, partenaires, chercheurs et développeurs).
      - Voir <span style="font-variant:small-caps;">Green</span> ( Thomas C.), «&nbsp;Ballmer&nbsp;: _Linux is a cancer_&nbsp;; Contaminates all other software with Hippie GPL rubbish&nbsp;» (_The Register_, 2001), qui cite les propos de Steve Ballmer lors d'une interview pour le _Chicago Sun-Times_&nbsp;: «&nbsp;Linux is a cancer that attaches itself in an intellectual property sense to everything it touches.&nbsp;»
   2. Un laboratoire _open source_ a été mis en place, et Microsoft [s'enorgueillit](http://www.microsoft.com/presspass/features/2009/Jul09/07-20LinuxQA.mspx) de contribuer à plusieurs projets libres (voir le billet intitulé «&nbsp;Microsoft Contributes Linux Drivers to Linux Community&nbsp;», sur [Microsoft.com](https://news.microsoft.com/2009/07/20/microsoft-contributes-linux-drivers-to-linux-community/), 2009).
   3. La société a une politique en matière de brevets généralement contraire à l'_open source_&nbsp;: elle oppose régulièrement ses brevets contre des projets _open source_&nbsp;; et a racheté des brevets de Novell par l'intermédiaire d'un consortium (CPTN Holdings LLC) qu'elle dirige&nbsp;; même si elle a par ailleurs publié deux promesses de non-agression («&nbsp;[Patent Pledge for Open Source Developers](http://www.microsoft.com/openspecifications/en/us/programs/other/interoperability-principles-patent-pledges/default.aspx)&nbsp;»&nbsp;; «&nbsp;[Microsoft Approach to Interoperability](http://www.microsoft.com/openspecifications/en/us/default.aspx)&nbsp;»).
   4. La société s'est rapprochée de l'éditeur Novell au sein d'un [Interop Ability Lab](http://www.moreinterop.com/) (interopérabilité entre Windows serveur et Suse Linux Entreprise&nbsp;: http://www.moreinterop.com).
   5. La WebApp de Microsoft comporte par ailleurs des clauses interdisant aux développeurs d'utiliser directement ou indirectement des composants sous licence _open source_ (voir Computing.co.uk, «&nbsp;[Microsoft restricts use of open source in app](http://www.computing.co.uk/ctg/news/2027347/microsoft-restricts-source-apps\#ixzz1WXd4RpST)&nbsp;»)&nbsp;: «&nbsp;the
 application must not include software, documentation, or other materials that, in whole or in part, are governed by or subject to an _excluded license_, or that would otherwise cause the application to be subject to the terms of an excluded license.&nbsp;». Sont ainsi exclues les licences GNU GPL et AGPL, et équivalentes…
   6. Depuis peu, la société communique sur son modèle économique intitulé Open Surface, un _cloud_ qui mêle logiciels libres et propriétaires.

-------------------------------------------

##### Les intégrateurs

De leur côté, les intégrateurs de logiciels libres et _open source_ (ou de solutions partiellement composées de ceux-ci) subissent généralement plus les licences qu'ils ne les choisissent&nbsp;: leur seule préoccupation étant que les briques logicielles puissent aisément se combiner entre elles. Il n'y a donc pas d'usage du droit des marques à l'égard des produits, mais surtout une expertise approfondie des combinaisons de licences leur permettant de s'assurer de la faisabilité du projet et de s'engager sur ce point auprès de leurs clients et dans leurs contrats (les clients demandant aujourd'hui la garantie de telle compétence ainsi que la livraison de certaines études précises sur ces questions). Transférant généralement un logiciel qu'il n'a pas (à priori) lui-même développé, mais seulement adapté au besoin de son client, l'intégrateur est lui-même limité par sa qualité de licencié à l'égard des auteurs des logiciels libres sur lesquels il intervient, et, ne _pouvant céder plus de droits qu'il n'en possède lui-même_, il communiquera à ses clients cesdits logiciels sous leur licence _open source_ d'origine (ou toute autre licence compatible).

  En ce qui concerne leurs contributions spécifiques, les pratiques sont multiples, mais il semblerait finalement que le plus avantageux pour l'ensemble des parties soit que la titularité des droits soit conservée par celui qui maintient et édite le logiciel (généralement l'intégrateur). Ainsi celui-ci cède l'ensemble de ses développements sous licence libre au client et conserve la titularité des droits. Ce compromis reste fidèle au procédé de création _open source_ dans lequel l'auteur reste titulaire de droits et cède sous licence _open source_ de façon non exclusive, afin de permettre tant au client de mutualiser les résultats de la prestation, qu'à l'intégrateur de valoriser les travaux par tous moyens appropriés[^partdeuxchaptrois44].

<!-- NOTES -->

[^partdeuxchaptrois44]: L'intégrateur se révèle être le mieux disposé pour faire évoluer le produit et assurer la pérennité de son développement au travers, notamment, d'un reversement systématique au bénéfice des communautés. Sa situation d'intermédiaire lui permet par ailleurs d'être idéalement placé pour favoriser les échanges indirects de contributions entre ses différents clients &ndash;&nbsp;l'évolution des solutions étant aussi dans l'intérêt de ceux-ci, tout le monde profite de cette collaboration.

<!-- /NOTES -->

##### Les constructeurs

Concourant à la création d'une industrie réunissant innovations matérielles et logicielles, les constructeurs (tels HP, Intel, IBM ou Dell) embarquent de plus en plus de logiciels et se rapprochent à ce titre des différents projets de logiciels libres (et l'_open cloud_) &ndash;&nbsp;devenant de jour en jour des contributeurs majeurs dans les projets OS (Linux, Busybox, etc.) au point de faire de leurs contributions respectives des éléments différenciant.

En effet, de tels logiciels permettent, en plus d'écorner certains monopoles, de réduire le coût de développement, d'optimiser l'interaction entre les logiciels et leurs matériels (ou _a minima_ d'assurer la compatibilité avec leur produit). 

À l'instar des intégrateurs, les constructeurs sont généralement désireux d'une compatibilité maximum entre les licences des logiciels _open source_ utilisés, même s'ils peuvent avoir intérêt à définir certaines politiques&nbsp;: favorables à certaines licences permissives (par exemple dans le secteur du mobile, avec la diffusion d'Android sous licence Apache)&nbsp;; ou exemptes de certaines obligations (par exemple, de licences de brevets) qui seraient incompatibles avec leur politique plus vaste relative à la propriété intellectuelle.

De nombreux secteurs sont concernés par une certification (ou qualification, cf. _supra_)de leur produit&nbsp;: l'_open source_ est pour eux une solution qui permet de mutualiser les frais de développement tout en conservant le bénéfice personnel de la certification de leur version.

##### Les utilisateurs

Contrairement aux logiciels traditionnels, les logiciels libres sont généralement accessibles à toutes catégories d'utilisateurs, dans les mêmes conditions. Ainsi, libre à chacun (individu, société, organisme à but non lucratif, collectivité ou État) de s'installer un forum (Phpbb), un wiki (Mediawiki), voire un Facebook-like (Elgg) ou un Youtube-like (Mediacore), etc.

Les utilisateurs d'un projet _open source_ sont particulièrement sensibles à la licence du projet&nbsp;: l'impact de cette dernière étant fonction de l'utilisation qu'ils en font (par exemple, si des services sont proposés sur la base de ces logiciels libres) voire de leur forme (société, GIE, association, etc.).

Lorsqu'il s'agit de sociétés «&nbsp;utilisatrices poussées&nbsp;», elles peuvent faire appel à des intégrateurs ou consultants pour mettre en place les solutions _open source_ dans leur SI &ndash;&nbsp;ce qui les place dans une situation analogue aux utilisateurs standards, avec quelques spécificités relatives aux contrats passés avec ces prestataires. En l'absence de tels intermédiaires, il est aussi possible de se tourner vers des solutions d'assurance (telle l'offre américaine [Open Source Risk Management](http://www.osriskmanagement.com/) proposée par la société OSRM).

Néanmoins, l'impact de l'utilisation des logiciels libres peut être lié à des politiques stratégique ou économique particulières&nbsp;: par exemple en cas d'externalisation quasi totale du support, maintenance, veille _open source_ à partir d'un SI essentiellement composé de logiciels libres, ou, au contraire, lors de la mise en place d'une entité informatique interne qui gère le déploiement de solutions en logiciels libres au sein de toute la structure (avec une vraie logique de service et d'édition). Dans toutes ces situations, les utilisateurs veillent à ce que les développements réalisés pour leur compte soient ensuite mis à disposition du (et si possible intégrés dans) projet 
 _open source_ &ndash;&nbsp;gardant à l'esprit qu'il est généralement aussi cher de maintenir un composant logiciel dans la durée que de le faire développer.

##### Les organisations à but lucratif et non lucratif

En plus des acteurs précédents, on retrouve plusieurs types de groupements sur lesquels s'appuient les projets libres et _open source_&nbsp;: ils sont commerciaux (tels les sociétés ou GIE) ou non (associations ou fondations), avec une personnalité morale ou non (association de fait &ndash;&nbsp;fréquent lors du lancement d'un projet&nbsp;&ndash; ou consortium), voire multiples (tel OpenOffice.org qui reposait sur l'association TeamEV, mais dont les droits de PI étaient gérés par Sun puis Oracle).

Les fondations et autres organisations à but non lucratif occupent une place prépondérante dans le système du Libre. Elles peuvent être classées en deux catégories[^partdeuxchaptrois45]&nbsp;: celles qui concourent directement au développement d'un logiciel et celles qui y concourent indirectement.

<!-- NOTES -->

[^partdeuxchaptrois45]: Distinction basée sur les travaux présentés par Jean-Pierre Laisné lors de l'OWF 2011.

<!-- /NOTES -->

Les premières sont productrices de code, de créations (qu'elles soient ou non titulaires de droits)&nbsp;:

   - organisations avec base de code diversifiée (Linux Foundation, Apache Foundation, Eclipse Foundation, OW2 Consortium, Adullact)&nbsp;;
   - organisations supportant une ligne de produits (Libreoffice, Mozilla.org, VideoLan, Genivi, Open Handset Alliance)&nbsp;;
   - communautés orientées technologie (FreeBSD, Ruby, Rails, Joomla).

Les secondes concourent indirectement au développement de projets (ne produisent pas de code _per se_)&nbsp;:

   - organisations fournissant des ressources organisationnelles (administratif, hébergement, conseil, etc.) aux projets (Software Freedom Conservancy, Eclipse, Linux Foundation)&nbsp;;
   - organisations fournissant des ressources légales (Free Software Foundation, Open Source Initiative, Software Freedom Law Center, VVL)&nbsp;;
   - organisations de standards (W3C, IEEE, ODF Alliance, OSGI Alliance, ETSI)&nbsp;;
   - organisations de lobbying et de promotion (April, Aful, Framasoft, Open Source for America, Ubuntu-fr, Fedora Fr, Adullact, etc.)


##### Les centres de recherche

L'implication et l'utilisation des logiciels libres par les centres de recherche sont si importantes qu'il est impossible de ne pas considérer les centres de recherches[^partdeuxchaptrois46] (et, dans une moindre mesure les universités[^partdeuxchaptrois47]) comme des acteurs à part entière du système que nous décrivons (notamment pour au regard de leur recherche à application industrielle).

<!-- NOTES -->

[^partdeuxchaptrois46]: L'INRIA et le CNRS étant les deux centres français les plus actifs sur le sujet.

[^partdeuxchaptrois47]: L'Université de technologie de Compiègne (UTC) est ainsi à l'origine de nombreux projets Open Source dans le domaine du logiciel ([scenari-platform](http://scenari-platform.org/projects/scenari/fr/pres/co/) pour n'en nommer qu'un) et en dehors.

<!-- /NOTES -->

Leur apport est néanmoins limité aux domaines directement liés à leur activité de recherche et ils ne prennent ainsi qu'un rôle passif dans l'animation des communautés ou la proposition de services. Ainsi, et même si la situation semble évoluer, on s'aperçoit que leur action se limite aujourd'hui au stade qui précède la valorisation de leurs projets Open Source&nbsp;: cette dernière phase étant réalisée par des sociétés existantes, partenaires ou non, ou nouvellement créées (le transfert en faveur de _spin off_ se multiplie).

#### Les relations entre le projet et les acteurs du système

Enfin, il est fréquent que l'intégrateur soit tenu de contribuer aux projets _open source_ en fournissant les modifications réalisées pour le client&nbsp;: il s'agit là d'une sécurité tant pour le client qui s'assure ainsi que les versions ultérieures du projet intégreront ces développements (et qu'il n'aura ainsi pas à le payer une seconde fois) que pour l'intégrateur qui ne souhaite généralement pas endosser la responsabilité d'un éditeur.

Chaque relation mérite néanmoins un examen dédié&nbsp;: entre un projet et ses utilisateurs (3.2.1.2.a), entre un projet et ses contributeurs (3.2.1.2.b), entre le projet et les autres groupements (3.2.1.2.c) et entre les sociétés (3.2.1.2.d).

##### Les relations entre un projet et ses utilisateurs

Les utilisateurs sont les premiers destinataires des logiciels. Ils contribuent généralement en livrant des retours sur leur expérience. Ils sont aussi souvent les premiers générateurs de valeur, le nombre d'utilisateurs d'un logiciel étant généralement un facteur multipliant la valeur du logiciel vis-à-vis de ceux qui ne l'utilisent pas encore. La licence utilisée sur l'œuvre logicielle est souvent le seul document les intéressant et, au sein de ce dernier, seuls les droits d'utilisation les concernent véritablement. Dans le cadre de certains projets, il arrive que des limitations s'ajoutent, en raison, par exemple, de composants commerciaux&nbsp;: l'utilisateur y consentira alors lors du téléchargement, de l'exécution ou de l'installation du logiciel.

Ces utilisateurs peuvent néanmoins devenir clients, contributeurs et/ou partenaires potentiels, voire concurrents du projet, et il est toujours utile de prévoir à leur attention des documents les informant de leurs droits et devoirs au terme de la licence, des conditions d'utilisation des marques, logos et noms du projet, voire, s'il y a lieu, du processus leur permettant de contribuer au projet (ainsi que la politique du projet en matière de propriété intellectuelle).

-------------------------------------

__Exemple pratique__

Par application d'un effet de réseau, les logiciels libres gagnent en intérêt et fonctionnalité au fur et à mesure que la communauté d'utilisateurs (et de développeurs) s'en approche. Ainsi, les utilisateurs de téléphones Android ont formé des projets, tel le projet [CyanogenMod](http://www.cyanogenmod.com), qui distribue des ROM optimisées pour de nombreux portables, permettant de bénéficier des dernières versions d'Android sur les téléphones qui ne sont plus maintenus par leur constructeur. Cela grâce à la version communautaire du système d'exploitation Android qui est publiée par Google sous licence Apache (et sans embarquer les applications propriétaires telles google maps, voice, search, etc.).

-------------------------------------

##### La collaboration avec les contributeurs

Les caractères évolutifs et participatifs étant l'essence même du logiciel libre, il n'est pas exclu que certains contributeurs souhaitent apporter leur lot de développements (envisagés sur un mode projet, en constante amélioration).

Dans la situation d'un éditeur (ou la communauté qui revêt ce rôle) déjà identifié sur le projet, il peut proposer plusieurs schémas de contribution qui conditionneront la reprise du code au sein du projet&nbsp;:

   - lorsque ces développements concernent le logiciel lui-même, il est souvent demandé une cession globale (ou suffisante) des droits (il est aussi fréquent, au sein des projets commerciaux, que les sociétés rachètent ou réécrivent les contributions qui les intéressent)&nbsp;;
   - lorsque ces développements portent sur des modules communautaires, les solutions sont généralement liées au choix initial de la licence du projet (mais il est aussi possible que l'éditeur n'héberge ou ne maintienne la contribution qu'en cas de cession de droits ou d'une politique de licence précise).

Dès les premières contributions au projet, il devient nécessaire d'avoir une réflexion pointue sur la gestion de la propriété intellectuelle, donnant éventuellement naissance à une politique en la matière, que celle-ci soit très protectionniste ou au contraire très ouverte.

###### Les enjeux et problématiques liés à la détention des droits de propriété intellectuelle

La question de la détention des droits de propriété intellectuelle, de la «&nbsp;titularité&nbsp;», est d'une importance variable dans un projet _open source_. En fonction de la licence (surtout si cette dernière est _copyleft_) et du type de projets, la détention peut être cruciale en ce qu'elle confère un certain contrôle sur le projet (par exemple pour toutes les sociétés qui pratiquent les doubles licences, dit _dual licensing_). Cette détention peut au contraire être très faible lorsque la licence choisie est très ouverte, lorsque le projet est soumis aux licences de composants _open source_ qu'il intègre, ou encore lorsque trop de contributeurs se partagent cette titularité.

Pour remédier à cette division de la propriété, de nombreux projets recourent à des politiques de licences spécifiques, de cession de droits ou de «&nbsp;copropriété libre&nbsp;» (chaque copropriétaire pouvant exploiter librement les droits détenus)&nbsp;: par le biais de _Contributor License Agreements_, _Copyright Assignment_ ou de _Joint Copyright_ qui conditionnent généralement la possibilité pour un développeur de voir sa contribution être acceptée dans un projet ou, dans le cadre professionnel, pour un client qui souhaite que ses développements soient maintenus par le projet. C'est une politique que l'on retrouve à l'égard des salariés d'une société &ndash;&nbsp;qui sont aujourd'hui les principaux contributeurs, sur tout type de contenu[^partdeuxchaptrois48].

Inversement, afin de se prémunir face à un éventuel contrôle sur un logiciel libre du fait de la détention des droits par un ou plusieurs, certains peuvent chercher à bloquer l'exercice de ces prérogatives en imposant une convention de copropriété (ou d'indivision) qui lie les parties quant à l'exploitation conformément à la licence _open source_ du projet[^partdeuxchaptrois49].

<!-- NOTES -->

[^partdeuxchaptrois48]: Pour rappel, la dévolution légale des droits en faveur de l'employeur ne joue qu'en présence d'une création salariale logicielle. [@Bensamoun2011]

[^partdeuxchaptrois49]: C'est notamment le choix pris pour l'ENT Lilie commandée par la Région Île-de-France.

<!-- /NOTES -->

###### Les _Contributor License Agreement_, _Copyright Assignment_ ou de _Join Copyright_

Il est ainsi fréquent que le nombre de contributeurs (et donc de titulaires de droits) dépasse la dizaine voire le millier. Leur anonymat ainsi que leur dispersion géographique sont parfois des obstacles infranchissables pour la suite du projet&nbsp;: l'absence de consentement d'un seul interdit toute décision concernant la création dans son ensemble et la seule échappatoire reste alors de supprimer les contributions pour lesquelles il manque cette autorisation.

C'est pour cette raison que, très tôt, certains développeurs ou organismes, telle la FSF, ont mis en place des documents qui permettent aux contributeurs d'un projet soit de leur céder leur copyright &ndash;&nbsp;pour centraliser la prise de décision (notamment le changement de licence[^partdeuxchaptrois50]), la gestion, et la défense de l'œuvre&nbsp;&ndash; soit de leur consentir une licence très large. On parle de _Copyright Assignement_ en présence d'un vrai transfert (cession exclusive) de droits, la structure devenant la seule et unique titulaire de droit. On parle de _Contributor License Agreement_ lorsque le contrat opère une cession (non exclusive) très large au profit de la structure sans que le contributeur soit lui-même dessaisi de ses prérogatives. Ils sont généralement doublés d'un second document à destination des employeurs lorsque les contributions sont réalisées dans un cadre salarial. Chacun de ces contrats est rédigé en fonction de l'équilibre particulier du projet, de l'implication des contributeurs dans celui-ci et de la confiance dont bénéficie l'organisme collecteur.

Devant le constat de la multiplicité, de la diversité et de la complexité de ces documents, de   nombreux industriels, professionnels et associations du libre ont formé un groupe de travail pour plancher sur la rédaction de documents types à destination des communautés et entreprises&nbsp;: leur épargnant un travail d'écriture en même temps qu'ils épargnent à leurs utilisateurs-contributeurs un travail de lecture (et de compréhension). Le [projet Harmony](http://harmonyagreements.org), s'il permet de mutualiser les politiques auparavant éclatées[^partdeuxchaptrois51], ne résout néanmoins pas la difficulté du rapport que cela génère entre les parties, les uns voulant un engagement fort des contributeurs &ndash;&nbsp;notamment par le biais de clauses de responsabilité et de garantie&nbsp;&ndash;, les autres voulant un engagement fort des collecteurs &ndash;&nbsp;notamment quant à l'exploitation des contributions.

Par ailleurs, ces contrats ne sont réellement fiables qu'en cas de certitude quant à l'identification du contributeur. C'est la raison pour laquelle la Free Software Foundation (mais Mozilla aussi) envoie un contrat papier qu'il convient de retourner signé. De même, l'Eclipse Foundation à mis en place un processus complet visant à sécuriser les relations entre les différents acteurs ([Eclipse Legal Process](http://www.eclipse.org/legal/EclipseLegalProcessPoster.pdf)).

<!-- NOTES -->

[^partdeuxchaptrois50]: Plusieurs situations de blocage peuvent être prises comme exemple&nbsp;: le changement de licence du contenu du site de Debian au profit d'une licence compatible avec la GNU GPL, l'ajout des licences GNU LGPL, et sur le navigateur Firefox (en faisant une [triple licence MPL/LGPL/GPL](http://mozillazine-fr.org/archive.phtml?article=4155)) ou encore le noyau Linux qui utilise actuellement volontairement la seule version&nbsp;2 de la GNU GPL.

[^partdeuxchaptrois51]: Voir <span style="font-variant:small-caps;">Meeks</span> (Michael), «&nbsp;Some brief thoughts on Project Harmony&nbsp;», 2011 (disponible sur [people.gnome.org](http://people.gnome.org)).

<!-- /NOTES -->

##### La collaboration avec d'autres groupements

Il est très fréquent que les différents projets ou organisations se réunissent pour travailler de concert sur des projets communs&nbsp;: soit qu'ils aient des compétences ou expériences complémentaires, transverses (tels les aspects juridiques liés aux licences et aux brevets), soit qu'ils mettent en commun leurs forces pour le développement d'une solution plus vaste.

##### La collaboration entre sociétés

Une société éditrice de logiciels qui met en place son modèle commercial prend généralement en considération ses partenaires, ses concurrents et ses clients. Il est assez simple de séparer les uns des autres&nbsp;: la société est liée par contrat avec ses partenaires (distributeurs, revendeurs, etc.) et ses clients (contrats souvent négociés pour les premiers et imposés pour les seconds), et n'entretient que des relations contractuelles exceptionnelles avec ses concurrents.

Les licences libres modifient cet ordre puisqu'elles s'adressent autant aux individus &ndash;&nbsp;personnes physiques&nbsp;&ndash; qu'aux entreprises commerciales. Ainsi, les concurrents comme les partenaires pourront en revendiquer le bénéfice, leur permettant notamment d'utiliser ou de proposer des services autour des logiciels édités par un autre avec pour seule limite le respect de la licence libre du projet et éventuellement de la politique de marques ou de brevets.

On peut y voir un paradoxe puisque les partenaires risquent d'être «&nbsp;moins libres&nbsp;» que les concurrents, du fait de clauses supprimant le bénéfice de la licence, qui peuvent être comprises dans leurs engagements avec l'éditeur[^partdeuxchaptrois52].

<!-- NOTES -->

[^partdeuxchaptrois52]: Clauses d'usage dans les contrats de partenariats proposés par MySQL, Ingres, Talend, etc.

<!-- /NOTES -->

###### Gérer les risques de _fork_

On parle de _fork_ lorsqu'une partie d'une communauté décide de s'éloigner du projet principal pour en développer une version différente. De manière générale, les _forks_ préjudicient à tous&nbsp;: l'ancienne et la nouvelle communautés, les utilisateurs et les projets.

C'est la raison pour laquelle il est généralement conseillé d'augmenter l'investissement dans un projet plutôt que d'initier son propre projet[^partdeuxchaptrois53].

<!-- NOTES -->

[^partdeuxchaptrois53]: Voir notamment la présentation de <span style="font-variant:small-caps;">Prouty</span> (Tim), «&nbsp;Becoming a Samba Developer&nbsp;», Isilon Systems, 2009 (disponible sur [sambaxp.org](http://sambaxp.org/fileadmin/user_upload/SambaXP2009-DATA/Tim_Prouty.pdf)).

<!-- /NOTES -->

----------------------------------
 
__De StarOffice à LibreOffice__

Récemment, la communauté d'OpenOffice.org s'est détachée du projet pour proposer sa propre version (nommée LibreOffice) au sein d'une fondation créée à cet effet&nbsp;: la Document Foundation. Cette dernière abrite le code de LibreOffice, mais aussi de tout autre produit qui souhaiterait dériver de ses sources. Lors de la formation du projet OpenOffice.org en 2000, la mise en place d'une telle fondation avait été annoncée par Sun. Dix ans après, et pour se protéger de la nouvelle politique commerciale imposée par Oracle (qui a racheté Sun) sur ses produits, les principaux responsables communautaires du projet ont pensé qu'il était temps de monter une fondation vraiment indépendante. Il n'y a pas de rupture avec le projet, simplement une communauté suffisamment mature pour prendre son destin en main et ne plus dépendre d'un décideur unique. LibreOffice (ou LibO) est une suite bureautique, développée par la fondation, qui s'appuie sur les sources d'OpenOffice.org et contient des patchs fournis par ses contributeurs (les plus assidus étant Novell, Red Hat et Debian, mais il y en a de plus en plus chaque jour).

Quelques mois après ces évènements, et pour répondre aux fortes demandes d'IBM, Oracle a «&nbsp;donné&nbsp;» son code et ses marques à la Fondation Apache qui distribue ainsi OpenOffice.org sous licence Apache.

Il faudrait certainement se projeter dans quelques années pour mesurer l'impact de ce _fork_ (sur l'entreprise, les communautés, voire, plus globalement, le projet global), mais beaucoup y voient une excellente nouvelle et de nombreux concurrents d'Oracle commencent à retrouver un intérêt dans le développement de cette version dont le succès dépendra de tous et non plus majoritairement d'une société  (ne serait-ce que par la détention du patrimoine immatériel). Gageons aussi que cette «&nbsp;insurrection&nbsp;» sera perçue comme une épée de Damoclès pour toute société qui chercherait à trop contrôler un projet qui se veut ouvert. Éspérons aussi que les deux projets parviennent à mutualiser leurs efforts.

------------------------------------

### Organiser la diffusion (accompagner l'ouverture du code)

L'organisation de la diffusion est souvent la clé qui  assure la pérennité d'un projet, sa stagnation ou son abandon. Malheureusement, il n'y a pas une organisation idéale, une structure parfaite, mais uniquement des cas d'espèce. Pour une entreprise, cela implique de se reposer sur un ensemble hétérogène de personnes au sein de l'entreprise qui perçoivent les enjeux de l'_open source_ et qui s'assure du respect des licences.

Ainsi, que ce soit pour ce seul projet ou pour une multitude, il est nécessaire d'entamer une telle réflexion et, une fois les besoins identifiés, d'organiser l'accompagnement &ndash;&nbsp;que ce soit en interne ou en externe ([guideopensource.info](http://guideopensource.info)).

#### Gérer les licences libres

La mise en place d'une bonne gestion des licences libres passe nécessairement par une étude des enjeux pour la société et/ou le projet (3.2.2.1.a), la définition des besoins (3.2.2.1.b) et l'organisation de l'accompagnement (3.2.2.1.c).

##### Mesurer les enjeux liés au respect des licences

Quelles sont les sanctions juridiques, mais aussi commerciales ou marketing, susceptibles de découler du non-respect des licences libres&nbsp;? De nombreuses sociétés, pourtant importantes, ont ainsi dû baisser l'échine face aux actions des communautés qui leur reprochaient l'absence de prise en compte des licences sur des composants utilisés (ce qui inclut [BestBuy](http://www.internetnews.com/bus-news/article.php/3853311/Best-Buy-Caught-in-GPL-Tussle.htm), [Westinghouse](http://www.internetnews.com/dev-news/article.php/3897231/GPL-Enforcement-Notches-Another-Victory.htm) et  [Cisco](http://blog.internetnews.com/skerner/2009/05/cisco-settles-gpl-lawsuit-with.html)). Ajoutons que les titulaires de droits, généralement seuls aptes à faire respecter leur licence, ont tendance à les accompagner l'utilisation de leur logiciel _open source_).

En effet, tout non-respect de licence emporte le risque de se voir qualifier de contrefacteur&nbsp;: tout usage n'entrant pas dans le cadre de la licence est un usage non autorisé et donc contrefaisant. Par ailleurs, en cas de violation, par certains usages de droits de propriété intellectuelle, ou plus fréquemment, du non-respect du formalisme de la licence, celle-ci sera généralement automatiquement résiliée et l'ancien licencié se trouvera rapidement contrefacteur pour tout usage de la création. Cela vaut pour l'entreprise, mais aussi pour tous ses clients et partenaires qui redistribuent les logiciels «&nbsp;non conformes&nbsp;» (on perçoit d'ailleurs une telle prise de conscience en Asie).

Au minimum (mais ce n'est pas toujours vrai), il est possible de considérer que lors de l'utilisation d'un composant _open source_ sans modification, la simple redistribution (tel qu'il a été reçu) devrait suffire. Au contraire, une démarche plus lourde serait nécessaire en cas de modification. La solution la plus fiable est néanmoins de mettre en place un formalisme générique, construit sur le modèle de la licence la plus contraignante, de manière à ce que son respect suffise pour remplir les attentes classiques de l'ensemble des licences. Enfin, des procédures particulières peuvent être élaborées afin de prendre en compte les spécificités des utilisateurs (professionnels du métier ou non, de nationalité précise, etc.) ou du domaine d'exploitation (embarqué, SaaS, etc.).

##### Définir les besoins

En fonction des enjeux, plusieurs besoins peuvent être identifiés&nbsp;:

   - La mise en place de bonnes pratiques (_guidelines_). Il s'agit ici de l'édiction de procédures relatives au respect du formalisme des licences ainsi qu'une procédure associée à l'usage de toutes nouvelles licences/composants _open source_. Celles-ci permettraient par ailleurs de rendre transparente la gestion des droits de propriété intellectuelle tant à l'intérieur qu'à l'extérieur de la société&nbsp;;
   - La mise en place d'une veille relative aux licences, pratiques afférentes et outils d'audit de codes (il est en effet important de rester connecté aux usages qui se développent, voire d'y confronter ses nouvelles pratiques, afin de se tenir informé tout en conservant un regard critique)&nbsp;;
   - La création d'un support relatif aux questions liées à l'utilisation des licences ou autres questions juridiques. Il s'agit ici des problématiques liées à l'ajout de licences et aux enjeux de compatibilité, mais un support juridique étendu peut permettre de résoudre certaines difficultés liées à la propriété intellectuelle ou à d'autres dispositions légales (comme l'exportation de certains produits)&nbsp;;
   - Une procédure d'audit de codes. Pour ce faire, il peut être très utile d'utiliser les outils réalisés pour faciliter ces missions&nbsp;: notamment le logiciel _open source_ Fossology qui peut permettre un examen systématique de code et l'outil commercial Protex de la société Black Duck qui offrira une analyse beaucoup plus poussée[^partdeuxchaptrois53]. Les deux solutions[^partdeuxchaptrois54] peuvent utilement être combinées&nbsp;: la première étant systématique et la seconde préalable à certaines mises à dispositions ou distributions du code&nbsp;;
   - La labellisation de composants et de licences. Cette politique de labellisation permettrait d'accélérer la réutilisation de composants, modifiés ou non, déjà audités et considérés comme conformes à la politique du groupement (techniquement et juridiquement), alors que le suivi d'une procédure particulière obligatoire accompagnerait l'utilisation de composants non encore certifiés. La même pratique pourrait être élaborée au profit des licences libres et _open source_ _a priori_ considérées comme «&nbsp;conformes à la politique du projet/du groupement&nbsp;». Une procédure particulière serait alors attachée à l'acceptation de composants _open source_ soumis à d'autres licences (de nombreuses sociétés ont ainsi constitué en leur sein de tels catalogues de composants _open source_, éventuellement aidées pour cela par des logiciels comme l'outil _Code Center_ de la société Black Duck).

<!-- NOTES -->

[^partdeuxchaptrois53]: La société éditrice propose un certain nombre d'offres pour les projets communautaires &ndash;&nbsp;à commencer d'ailleurs par l'_Eclipse Foundation_.

[^partdeuxchaptrois54]: La liste n'est néanmoins pas exhaustive et d'autres produits similaires existent, édités par des sociétés américaines (telles Palamida, OpenLogic ou ProteCode) ou françaises (comme Antelink).

<!-- /NOTES -->

##### Organiser l'accompagnement

À ce stade, il s'agit de définir quelles sont les tâches qui peuvent être externalisées et quelles sont celles qui doivent être conservées en interne.

###### La création d'une structure _ad hoc_

Une externalisation totale semble difficile en raison de l'interpénétration des notions juridiques et techniques d'une part, et de la criticité de ces enjeux d'autre part. Tout au plus est-il possible de penser à l'intervention de tiers quant à l'audit initial (en cas de solution préexistante), à l'édiction d'une gouvernance, voire en préalable à toute distribution &ndash;&nbsp;pour le reste, une personne, voire une équipe interne, doit être référente afin de résoudre (ou transmettre à cette fin) les difficultés qui se présentent à elle et «&nbsp;infuser&nbsp;» les bonnes pratiques. Une solution intermédiaire pourrait être de rejoindre une structure plus grande (comme une fondation) qui permette de mutualiser une partie de la fonction.

L'internalisation elle-même peut prendre différentes formes, qu'il s'agisse de créer une entité _ad hoc_ (référent _open source_, comité _open source_, etc.) ou de modifier les structures existantes pour y intégrer ces besoins, notamment par l'intégration de règles générales, comme la définition de politique en matière de licences, la validation de paquets logiciels, etc.. De nombreux paramètres entrent dans cette équation, mais il est généralement conseillé, lorsque la taille le permet, de commencer par la mise en place d'entités autonomes, de sorte qu'elles s'éclipsent une fois la nouvelle culture infusée et les réflexes intégrés &ndash;&nbsp;au risque sinon de buter sur la résistance des collaborateurs (surtout dans le cas du passage d'une politique de licence traditionnelle à une politique ouverte&nbsp;: la longue domination du paradigme antérieur, engendrant de nombreux réflexes et habitudes profondément ancrées, peut entraîner le rejet irrationnel de ce mode alternatif d'édition).

Quelle que soit l'organisation choisie, il est nécessaire que cet accompagnement s'appuie sur des relais locaux (_scouts_), des correspondants aptes à faire remonter et redescendre les informations utiles.

À la fois structure de référence et structure inter-services, un tel organisme permet de mutualiser le travail d'accompagnement, de rationaliser les décisions, de définir des politiques globales et d'automatiser le traitement des questions. Par ailleurs, pour qu'une telle structure puisse être suivie d'effet, il est nécessaire qu'elle soit facilement joignable, qu'elle bénéficie d'un pouvoir décisionnel et, dans l'idéal, qu'elle soit suivie par un membre de la direction. Enfin, elle seule doit être consultée pour autoriser et décider de l'utilisation de briques logicielles sous licences libres / _open source_ et de la diffusion sous de telles licences (quitte à ce que ses décisions soient avalisées par la direction).

###### Gérer les contributions au sein de la société

Comme nous l'avons vu, les licences s'étendent graduellement à l'ensemble des droits de propriété intellectuelle. Une vigilance accrue s'observe donc chez les sociétés qui mixent une culture libre (_open source_) et propriétaire&nbsp;: l'enjeu est alors de délimiter très précisément (généralement par des politiques _open source_ très soignées), voire de cloisonner, les portefeuilles de droits relatifs au projet afin de s'assurer que l'activité _open source_ ne vienne pas impacter et dévaloriser certains droits de propriété intellectuelle qui restent très attractifs pour la société.

C'est ce type d'attention qui explique par exemple la renonciation au bénéfice de la dévolution légale de droits relative à certains développements qui doivent être reversés à des projets placés sous des licences trop contraignantes (au profit des salariés qui conservent ainsi leurs droits)[^partdeuxchaptrois55]. De la même façon, une responsabilité particulière pèse sur les services juridiques qui doivent s'assurer que les engagements contractuels avec les sous-traitants, fournisseurs, etc. soient bien respectés et maintenus lors de la diffusion sous licence libre et _open source_.

<!-- NOTES -->

[^partdeuxchaptrois55]: On peut ici citer l'exemple d'HP vis-à-vis de la GNU GPL v.&nbsp;3 (qui pourrait impacter la valeur de son portefeuille de brevets).

<!-- /NOTES -->

Pour une société, il arrive parfois qu'il soit plus simple, voire nécessaire, d'envisager un cession de droits au profit de projets qui assureront le maintient et l'intégration des différentes contributions. Dans cette solution, tant l'entreprise que le salarié seront généralement signataires d'un document de cession de droits au profit du projet. Il peut aussi être envisagé, lorsque la mission du salarié l'exige ou en raison du contrat particulier qui le lie à la société, que celle-ci lui délègue le pouvoir de mettre sous licences libres les contributions réalisées dans le cadre de ses missions salariales&nbsp;: le risque est faible pour l'entreprise lorsque celui-ci travaille dans un tel environnement, et cela lui permettra de sécuriser les contributions de son salarié vis-à-vis des communautés et des projets dans lesquels il intervient.

###### Faire travailler ensemble les différentes équipes

De façon pragmatique, lorsque l'on exploite du contenu sous licence libre en entreprise ou ailleurs, il est nécessaire d'adapter la procédure de validation juridique et contractuelle, l'analyse devant être réalisée autant en amont des projets qu'en aval. Un travail est nécessaire dès en amont afin de déterminer la faisabilité juridique des propositions techniques et s'assurer que les engagements puissent être respectés (en gardant en tête le leitmotiv&nbsp;: «&nbsp;on ne peut donner plus de droits que l'on en possède&nbsp;», c'est d'ailleurs cette seule idée qui ressort des contentieux français ayant mis en jeu la GNU GPL). Enfin, une dernière étude juridique est nécessaire en aval pour confirmer le choix final de la licence et procéder, s'il y a lieu, aux ajustements contractuels en fonction du produit, des attentes et bien évidemment des licences en présence.

Ainsi, ce travail ne peut être mené que conjointement entre l'équipe technique, seule apte à fournir les informations détaillées sur le logiciel, et l'équipe juridique. Les données brutes nécessaires à l'étude juridique sont&nbsp;: le détail des briques logicielles utilisées, leur(s) licence(s) respective(s) (comprenant leur version, et toute autre information influant sur ces licences&nbsp;: restriction, interprétation, exception, etc.), et enfin les interactions existantes entre chacune de ces briques (en pratique, un schéma). Un dialogue s'établit par la suite pour affiner les derniers détails, et de nombreuses navettes permettront de compléter l'analyse.

D'une manière plus générale, le succès d'une politique active en faveur de l'_open source_ repose sur une implication de l'ensemble des collaborateurs dans le processus de restructuration et une montée des compétences de ces derniers afin qu'ils comprennent et partagent ce nouveau paradigme&nbsp;: par l'organisation de formations, la rédaction et la mise à disposition des informations qui leurs sont utiles, l'organisation de leurs contributions au sein de chartes (contribution, développements, processus de validation, etc.).

###### S'équiper avec de bons outils

Enfin, l'usage de certaines solutions logicielles peut simplifier, voire approfondir[^partdeuxchaptrois56] cette mission, en automatisant l'audit de code[^partdeuxchaptrois57] voire la gestion au quotidien de la base de code validée. Tous les outils ne sont pas équivalents, et tous n'ont pas vocation à être utilisés au même moment ou par les mêmes personnes (dans le cadre de _due diligence_, les audits demanderont ponctuellement l'utilisation d'outils très poussés, alors que la vérification automatique et journalière des développements réalisés pourra être plus superficielle).

Enfin, le projet _Software Package Data Exchange_[^partdeuxchaptrois58] ([SPDX](http://spdx.org)) a récemment introduit un format standard pour communiquer les éléments, les licences et droits d'auteur associés à un logiciel (et ainsi faciliter la prise de connaissance des obligations et le respect des licences). Ainsi, chaque société ayant réalisé ce travail d'audit pourra dorénavant accompagner la livraison de son logiciel d'un fichier SPDX qui recensera tous les composants utilisés et leur(s) licence(s).

<!-- NOTES -->

[^partdeuxchaptrois56]: Par exemple avec une comparaison du code du projet avec celui de leur base.

[^partdeuxchaptrois57]: Voir à cet égard les solutions décrites dans le _Guide Open Source_, partie 1.2.2. «&nbsp;Description du code source&nbsp;».

[^partdeuxchaptrois58]: Le projet SPDX (pour Software Package Data Exchange) est un format 
standard pour la communication des composants, licences et mentions légales associées à la distribution d'un logiciel. Le site a été réalisé sous la direction de la Linux Foundation, avec la participation de nombreuses sociétés parmi lesquelles Alcatel-Lucent, Antelink, Black Duck Software, Canonical, HP, Micro Focus, Motorola Mobility, nexB Inc, OpenLogic, Palamida, Protecode, Source Auditor, Texas Instruments et Wind River.

<!-- /NOTES -->



#### Gérer les autres aspects juridiques

Comme vu précédemment, différents documents peuvent être mis en place pour accompagner l'organisation vis-à-vis des tiers et notamment pour donner un cadre formel à la collaboration&nbsp;(3.2.2.2.a), et la rédaction d'une politique en matière de marque précise à l'intention des tiers et des licenciés (3.2.2.2.b).

##### Structurer le projet

Que le projet soit ouvert ou fermé, la mise en place d'un cadre propice à son développement et son exploitation nécessite une réflexion quant à l'organisation du groupement autour du projet et vis-à-vis des tiers.

Tant que l'organisation du projet est suffisamment attractive pour motiver des contributions extérieures et qu'il répond aux contraintes des mainteneurs, il n'y a aucune raison de changer celle-ci.

Si le projet souhaite s'ouvrir de manière à impliquer plus de contributeurs, plusieurs schémas peuvent être construits pour organiser les développements collaboratifs, avec leurs avantages et inconvénients (création d'une entité juridique distincte, mise en place d'un consortium, l'appui d'un partenaire leader &ndash;&nbsp;voire une absence délibérée). Notons que la mise en place d'un consortium est la solution la plus légère (généralement la première utilisée par les sociétés qui cherchent à collaborer en raison de la faiblesse de l'engagement), éventuel premier jalon d'une autonomisation quasi-systématique des projets dès lors qu'ils gagnent en contributeurs.

Dans l'hypothèse de la libération d'un projet, il est préférable de structurer un minimum dès le début (donner simplement l'accès au code et le processus pour contribuer) quitte à mettre ensuite en place une organisation adaptée.

Enfin, la gouvernance des groupements est généralement découpée entre les aspects stratégiques, les aspects techniques et les aspects communication/sensibilisation (lien avec les utilisateurs et la communauté).

##### Les politiques en matière de marque

Le droit des marques retrouve toute sa noblesse dans l'industrie de l'_open source_, puisqu'il reste bien souvent le meilleur garde-fou pour empêcher certains types d'exploitation d'un projet qui est pourtant librement disponible (notamment en termes d'image, mais aussi de comportement commercial). Néanmoins, il est parfois nécessaire de relativiser l'usage qui peut en être fait au regard des prérogatives qu'il confère à son titulaire, car la tentation est grande pour certains d'essayer de récupérer là un contrôle qu'ils ont abandonné en faisant le choix de l'_open source_.

Ainsi, les politiques en matière de marque sont généralement des documents publics qui précisent quelles sont les marques détenues par le projet et les conditions de leur utilisation&nbsp;: une seule marque pouvant être utilisée différemment selon le contexte (lorsque la création est modifiée ou non) ou plusieurs marques pouvant être utilisées pour différencier les usages permis sur chacune (par exemple en autorisant seulement les partenaires à utiliser la marque figurative).

Les meilleurs exemples existants, à cet égard, sont ceux des projets du type OpenOffice.org / LibreOffice, Firefox, GNU/Linux, etc., qui réunissent à la fois entreprises, associations et fondations, contributeurs individuels et le grand public.


