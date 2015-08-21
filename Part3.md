# Quelques études de licences libres

La diversité des licences s'explique par la diversité des projets et des modèles commerciaux qui suivent le courant de l'_open source_. On observe néanmoins une forte parenté entre ces licences, le nombre de celles réputées pleinement «&nbsp;originales&nbsp;» devant être d'une petite dizaine dans le seul domaine du logiciel (GNU GPL, MPL, OSL, EUPL, Apache voire EPL). L'analyse de ces dernières permet de donner un aperçu fidèle de leur écosystème.

Nous allons donc nous intéresser aux licences suivantes&nbsp;: AFL, Apache, APSL, EPL, EUPL, GNU (GPL, LGPL et Affero GPL), MIT, MPL, CeCILL(-A, -B, -C), Creative Commons, LAL, ODbL, PHP License, OSL, et la TAPR Open Hardware License.

Chacune d'elle sera analysée conformément à la grille de lecture proposée précédemment[^parttrois1]&nbsp;: droits et obligations, étendue, élément déclencheur et clause de compatibilité.

## AFL v&nbsp;3.0 (Academic Free License) {-}

Assez similaire à la licence Apache, l'[Academic Free License](http://www.opensource.org/licenses/afl-3.0.php) est la petite sœur permissive de l'OSL (toutes les clauses lui sont identiques, à l'exception de celles instaurant le _copyleft_) rédigée par l'avocat américain Lawrence Rosen. Elle est dite «&nbsp;de contenu libre&nbsp;», c'est-à-dire qu'elle a vocation à être utilisée sur toutes œuvres originales (ce qui inclut donc les logiciels, mais aussi les documentations, images, etc. &ndash;&nbsp;avec comme intention de pouvoir s'appliquer à tout ce qui accompagne le logiciel). La version&nbsp;1.1 date de 2002 et fut certifiée _open source_ par l'Open Source Initiative (OSI), mais déclarée incompatible avec la DFSG par la communauté Debian&nbsp;; la version&nbsp;2.0 date de 2003, et la dernière version fut publiée en 2005.

En termes de _droits_, c'est une licence conforme à l'OSD qui autorise expressément les sous-licenciements (sous la même licence). Elle est gratuite (mais la communication de l'œuvre peut être payante), non exclusive et perpétuelle et porte sur les droits d'auteur comme sur ceux des brevets contenus dans le code soumis à la licence (elle cherche à créer ici un pot commun de brevets, équivalent à celui issu de l'usage des licences _copyleft_). Enfin, la licence incorpore une limitation &ndash; et non pas une exclusion &ndash; de garantie (de la provenance des sources) et de responsabilité à l'égard du concédant&nbsp;; solution bien plus pragmatique puisqu'il s'agit de ce qui est, dans les faits, le minimum légal.

En termes d'_obligations_, la licence n'est pas _copyleft_, mais quiconque poursuit l'auteur original ou ses utilisateurs pour violation de brevet contenu dans le logiciel soumis à cette licence voit toutes les licences qui lui étaient accordées se terminer immédiatement. Toute action ou poursuite doit se faire devant un tribunal de la juridiction du lieu où le concédant exerce son activité principale &ndash;&nbsp;tous les frais d'avocats seront à la charge de la partie qui poursuit.

L'_élément déclencheur_ de la licence est l'_external deployment_, c'est-à-dire «&nbsp;l'utilisation, la distribution ou la communication de l'œuvre originale ou dérivée d'une façon telle que cette œuvre originale ou dérivée puisse être utilisée par toute autre personne que vous.&nbsp;»[^parttrois2].

L'_étendue_ de la licence s'appuie sur les distinctions du copyright quant à la portée de l'œuvre dérivée. À noter que le code source, tel que défini par l'OSL, inclut la «&nbsp;documentation décrivant comment modifier l'œuvre originale.&nbsp;»

En termes de _compatibilité_, la licence est relativement souple dès lors que ses obligations sont respectées&nbsp;: ce qui la rendait incompatible avec la GNU GPL v2 (elle serait néanmoins compatible avec la troisième version), mais entièrement compatible avec sa grande sœur de l'OSL (rédigée sur le même canevas).

Enfin, la licence elle-même est copyrightée et ne peut donc servir de base à une nouvelle licence[^parttrois3].


## Apache License (APL) {-}

Seule l'utilisation de la version&nbsp;2.0, publiée le 1^er^ mars 2004, de l'[Apache Public License](http://www.apache.org/licenses/LICENSE-2.0) est aujourd'hui préconisée (notamment, par défaut, pour tous les projets de la fondation Apache)[^parttrois4]. C'est aussi une licence permissive par laquelle les contributeurs partagent leur monopole en matière de droit d'auteur et éventuellement de brevets portant sur ces contributions (cette licence tombe en cas d'action à l'encontre des contributeurs).

En termes de _droits_, la licence autorise expressément les sous-licences.

En termes d'_obligations_, on retrouve les mentions traditionnelles relatives à la paternité et à la licence (avec notamment la nécessité de distinguer les différentes contributions et le respect d'un formalisme quant aux mentions légales attachées aux œuvres dérivées). Toute contribution reversée au concédant pour inclusion dans son logiciel est, sauf mention contraire, réputée être soumise à la même licence. Enfin, une sanction est prévue à l'encontre de tout licencié qui agirait sur la base d'une violation de brevet dans l'usage d'un logiciel sous licence Apache ou ses contributions (toutes les licences de brevets qu'il tire de la licence Apache se terminent au jour de l'assignation).

L'_étendue_ de la licence est, pour l'essentiel, limitée à la portion du code sous licence Apache, mais certaines obligations (notamment celles concernant les mentions légales du logiciel final) s'étendent aussi aux logiciels dérivés (basés sur ou incluant des composants sous licences Apache).

L'élément déclencheur est la distribution de copies du logiciel (l'accès au code offert à un tiers).

La licence ne prévoit pas de _compatibilité_ particulière, mais plusieurs licences peuvent être utilisées, dont la GNU GPL v.&nbsp;3 si sont précisées les obligations supplémentaires liées à la licence Apache.

## Apple Public Source License v2.0 {-}

Licence utilisée depuis 2003 sur une partie du système d'exploitation MacOS X d'Apple, la [APSL](http://www.opensource.apple.com/apsl) n'a pas vocation à être utilisée sur d'autres projets et la firme Apple est citée à plusieurs reprises (ce qui est d'autant plus logique que cette licence est elle-même une adaptation de la licence MPL).

Ainsi, en termes d'_obligations_ peut-on remarquer que la licence est _copyleft_ et organise une licence en matière de brevets. En cas de non-respect de la licence, la licence prévoit une certaine souplesse qui permet éventuellement de corriger le comportement défaillant. La compétence territoriale est fixée en Californie.

En termes d'_étendue_, la licence est modulaire et opère par fichier[^parttrois5] autorisant donc le lien vers d'autres fichiers qui peuvent être entièrement propriétaires.

Son _élément déclencheur_ est celui du déploiement externe (_external deployment_), ce qui la met à l'échelle des licences du type OSL ou GNU Affero GPL.


La licence ne prévoit aucune _compatibilité_ particulière.

## Eclipse Public License (EPL) {-}

L'[Eclipse Public License](http://www.eclipse.org/legal/epl-v10.html) est la licence qui a succédé à la CPL sur le projet Eclipse (cette dernière ayant elle-même succédé à la licence IBM _Public License_).

Concernant ses _obligations_, la licence Eclipse est elle aussi _copyleft_, et comporte une clause en matière de brevets qui est sensiblement similaire à celle de la licence Apache (en cas d'action basée sur une violation de brevet dans l'usage du logiciel sous EPL, toutes les licences de brevets tirées de la licence sont terminées).

L'_étendue_ de l'EPL est basée sur la définition américaine de l'œuvre dérivée, interprétée de manière plus restrictive que pour la GNU GPL&nbsp;: la licence ne s'étend pas aux modules séparés développés autour du logiciel, ni aux autres travaux qui ne seraient pas directement dérivés du programme[^parttrois7].

L'_élément déclencheur_ est, classiquement, celui de la distribution.

La licence précise que la loi applicable est celle de l'état de New York et des États-Unis en matière de propriété intellectuelle.

## European Union Public License (EUPL) {-}

Disponible en 22 langues (chacune de ses traductions ayant la même valeur contractuelle), l'[European Union Public License](http://www.osor.eu/eupl/european-union-public-licence-eupl-v.1.1) est sans conteste la licence la plus internationale.

Elle est _copyleft_ et contient une _licence de brevets_ dans la «&nbsp;mesure nécessaire à l'exercice des droits qui … sont concédés sur l'œuvre distribuée sous la … licence&nbsp;». La terminaison de la licence est automatique en cas de son non-respect. 

En termes d'_étendue_, la licence renvoie à la loi «&nbsp;applicable en matière de droit d'auteur dans le pays désigné à l'article&nbsp;15&nbsp;» (pays du concédant, voire loi belge si ce dernier n'est pas européen ou s'il s'agit de la Commission européenne). 

En termes d'_élément déclencheur_&nbsp;: tant la distribution que la communication au public (même de façon indirecte, ce qui comprend notamment l'usage d'un logiciel en _Software as a Service_)[^parttrois8].

La loi applicable et le tribunal compétent sont ceux de «&nbsp;l'État membre de l'Union européenne où le donneur de licence réside ou a établi son siège social&nbsp;» (pays du concédant, voire loi belge si ce dernier n'est pas européen ou s'il s'agit de la Commission européenne). La licence contient une garantie d'éviction (l'assurance que chaque concédant est bien titulaire de droits sur ses contributions) et repose sur un mécanisme de sous-licence.

Enfin, la licence est expressément _compatible_ avec cinq autres licences similaires&nbsp;: une clause venant spécialement autoriser la redistribution sous un certain nombre de licences dès lors qu'une œuvre dérivée combine composants sous licence EUPL et composants sous l'une de ces licences compatibles[^parttrois9].

## GNU General Public License (GNU GPL) {-}

Première licence libre, la GNU GPL fut la première à contractualiser la notion de pot commun, avec pour objectif de faciliter l'accès aux codes sources et leurs interactions. La GNU GPL est, historiquement, réservée aux logiciels et elle est de mieux en mieux rédigée au fur et à mesure de ses versions.

L'_étendue_ ainsi que la _portée_ (droit d'auteur, droit des brevets, droit des topographies des semi-conducteurs, DRM, etc.) très larges de la licence GNU GPL sont ses principales caractéristiques.

Deux versions de la licence (la deuxième et la troisième) sont actuellement utilisées et méritent un examen spécifique.



## GNU GPL v.&nbsp;2 {-}

En termes d'_obligations_&nbsp;: 

   - tout est fait pour que les mentions légales soient accessibles sinon publiées&nbsp;: ainsi, dans l'hypothèse d'un programme lisant habituellement des instructions de façon interactive lorsqu'on l'exécute, celui-ci doit imprimer ou afficher une annonce comprenant une mention relative aux droits d'auteur, à l'absence de garantie, et à la soumission à la GNU GPL&nbsp;;
   - la livraison du code source doit être réalisée dans sa forme préférentielle&nbsp;;
   - la licence est bien sûr _copyleft_.

L'étendue de la GNU GPL est très large puisque tout logiciel basé sur un composant sous GNU GPL doit être distribué sous cette même licence et que le logiciel lui-même est envisagé «&nbsp;comme un tout&nbsp;». Le flou de ces notions induit plusieurs interprétations. La Free Software Foundation prône la plus extensive (par laquelle toute liaison avec un composant sous cette licence emporterait son extension). 

Ainsi, dans le cas du logiciel auquel est associé de multiples modules&nbsp;:

   - les modules développés autour du logiciel sont, [selon la FAQ de la licence](http://www.gnu.org/licenses/gpl-faq.html), des «&nbsp;créations basées&nbsp;» (_based on_) sur le logiciel. En tant que telles, elles doivent donc être diffusées sous la même licence que le logiciel[^parttrois10]&nbsp;;
   - si le logiciel est distribué simultanément avec des modules sous cette licence, alors celle-ci doit s'étendre au logiciel «&nbsp;comme un tout&nbsp;», c'est-à-dire au logiciel et ses différents modules.

Concernant l'_élément déclencheur_, les obligations de la licence ne sont opposées aux licencié que s'il distribue le programme. Le _copyleft_ s'applique uniquement au programme et non à ses sorties, par exemple un portail web utilisant une version modifiée privée d'un CMS (Content Management System) sous GPL ne sera pas obligé de livrer ses sources (élément traité par la GNU Affero GPL) tant qu'il n'aura pas donné accès à une copie du logiciel.

Intransigeante, même envers les autres licences libres et _open source_, la licence GNU GPL n'organise elle-même aucune compatibilité. 

## GNU GPL v.&nbsp;3 {-}

Un lot de nouvelles stipulations précise ou étend les obligations de la précédente version&nbsp;:

   - la notion de code source est précisée et étendue[^parttrois11]&nbsp;;
   - vis-à-vis des mesures techniques, de protection et d'information (ADPIC, EUCD, DADVSI)&nbsp;: l'auteur d'un logiciel sous GPL renonce à ce que celui-ci soit considéré comme une mesure technique (à priori, autant de protection que d'information &ndash;&nbsp;MTP/MTI) et ne peut limiter la jouissance tirée de la licence par une interdiction du contournement de mesures techniques.
   - Le _peer to peer_ est enfin pris en considération en tant que distribution (sans pour autant que les personnes qui téléchargent le logiciel par ce canal n'aient à fournir les sources)&nbsp;;
   - _Tivoïzation_[^parttrois12]&nbsp;: stipulation réservée aux «&nbsp;produits de consommation&nbsp;» (non applicable à un usage interne ou entre professionnels), elle interdit de limiter l'usage d'un produit embarquant du code sous GNU GPL v.&nbsp;3 à la seule version fournie par le constructeur&nbsp;;
   - en matière de brevet, la GNU GPL garantit une «&nbsp;licence de brevet non exclusive, mondiale et gratuite, sur les revendications essentielles de brevet du contributeur pour réaliser, utiliser, vendre, commercialiser, importer et ainsi qu'exécuter, modifier et propager les contenus de sa version contributive&nbsp;» et impose à tout bénéficiaire de brevets de rendre le code source disponible, renoncer au bénéfice de licences sur cesdits brevets ou s'engager à étendre la licence au destinataire du logiciel&nbsp;;
   - la _terminaison automatique des droits_, avec procédure de semonce (article&nbsp;8) est tempérée lorsqu'il s'agit d'une première violation et en fonction de la réaction du concédant&nbsp;;
   - en termes de _compatibilité_&nbsp;: on notera une compatibilité expresse au profit de la GNU Affero GPL et l'ajout d'une modularité qui permet à la licence de se rendre compatible avec plusieurs licences permissives grâce à l'ajout autorisé de termes additionnels&nbsp;: soit pour donner plus de droits, soit pour ajouter quelques obligations limitativement énumérées (la GNU GPL liste dans son article&nbsp;7 six termes supplétifs).


## Exceptions à la GNU GPL {-}

La GNU GPL étant la licence la plus utilisée, il n'est pas étonnant qu'une pratique se soit développée atour des aménagements qui pouvaient lui être apportés par le biais d'exceptions expresses. La GPL Linking exception et la FOSS exception sont les deux plus connues.

### La _GPL with special linking exception_ {-}

Pour répondre aux besoins de certains projets libres importants souhaitant autoriser le développement de plug-ins propriétaires, une exception (_GPL Linking exception_) a été rédigée (elle est actuellement utilisée par des projets comme GNU Guile, GNAT ou GNU Classpath). Elle contient les mêmes libertés que la GNU LGPL en ce qu'elle permet expressément les liaisons entre programmes, mais sans requérir les conditions posées par la LGPL quant à la fourniture des informations nécessaires à la modification de la bibliothèque.

La bibliothèque GNU Classpath utilise ainsi la licence qui suit&nbsp;:

> Classpath is distributed under the terms of the GNU General Public License with the 
following clarification and special exception.
> 
> Linking this library statically or dynamically with other modules is making a 
combined work based on this library. Thus, the terms and conditions of 
the GNU General Public License cover the whole combination. 
> 
> As a special exception, the copyright holders of this library give you permission to link this library with independent modules to produce an executable, regardless of the license terms of these independent modules, and to copy and distribute the resulting executable under terms of your choice,
 provided that you also meet, for each linked independent module, the terms and conditions of the license of that module. An independent module is a module which is not derived from or based on this library. If you modify this library, you may extend this exception to your version of the library, but you are not obliged to do so. If you do not wish to do so, delete this exception statement from your version. 



### _FOSS exception_ {-}

La _FOSS exception_ organise une limitation de l'étendue de la licence dans un contexte _open source_  seulement&nbsp;: système souvent utilisé, notamment sur la [bibliothèque MySQL](http://www.mysql.com/about/legal/licensing/foss-exception/) diffusée sous GNU GPL, l'exception réduit l'étendue de la licence en présence d'une combinaison avec des composants tiers _open source_ (ceux-ci, pour autant que leur licence figure dans la liste annexée à cette exception, peuvent ainsi continuer à être régi par leur licence d'origine).

> Oracle's Free and Open Source Software (FOSS) License Exception (formerly known as the FLOSS License Exception) allows developers of FOSS applications to include Oracle's MySQL Client Libraries (also referred to as _MySQL Drivers_ or _MySQL Connectors_) with their FOSS applications. MySQL Client Libraries are typically licensed pursuant to version 2 of the General Public License (GPL), but this exception permits distribution of certain MySQL Client Libraries with a developer's FOSS applications licensed under the terms of another FOSS license listed below, even though such other FOSS license may be incompatible with the GPL.

## GNU Lesser General Public License (GNU LGPL) {-}

Deux versions coexistent actuellement, sans grande différence sur le fond, mais avec une grande différence sur la forme&nbsp;: la GNU LGPL était une licence à part entière jusqu'à la version&nbsp;2.1 et n'est plus qu'une exception associée à la GNU GPL à partir de la version&nbsp;3 (les textes des deux licences devant alors simultanément être distribués).

De manière générale, elle apporte un lot de permissions additionnelles à la GNU GPL en venant atténuer l'étendue ou les effets de cette dernière (une telle technique est toujours possible pour le titulaire de droits). 

Ainsi, la GPLv3 est la licence que l'on applique par défaut et, dès lors que l'on se trouve dans l'une des situations définies par la LGPL v.&nbsp;3, on applique le «&nbsp;régime dérogatoire&nbsp;» spécialement prévu (exception d'interprétation stricte)&nbsp;:

   - Art.&nbsp;3&nbsp;: l'inclusion de _material from header file that is part of the library_&nbsp;;
   - Art.&nbsp;4&nbsp;: la création de _combined work_ (qui peut être diffusée sous une autre licence)&nbsp;;
   - Art.&nbsp;5&nbsp;: la création de _combined libraries_.

Il est à tout moment possible de redistribuer sous GNU GPL un logiciel auparavant sous GNU LGPL.

## GNU Affero General Public License (GNU AGPL) {-}

La GNU AGPL 3.0[^parttrois13] est elle aussi construite sur le canevas de la GNU GPL v.&nbsp;3. Seul son article&nbsp;13 est différent. 

Ainsi, en matière d'_obligation_, il faut distinguer d'une part ceux qui distribuent le logiciel ou en offrent un accès en ligne et, d'autre part, ceux qui contribuent&nbsp;:

   - les distributeurs et utilisateurs offrant un accès en ligne, sont tenus&nbsp;: a) à un certain affichage des mentions légales, b) à la distribution de la licence et c) à la distribution du code source correspondant&nbsp;;
   - et, au surplus, les contributeurs sont «&nbsp;classiquement&nbsp;» tenus&nbsp;: a) par le caractère _copyleft_ de la licence, c'est-à-dire à ce que toute redistribution du logiciel, d'une version modifiée ou d'une solution basée sur ce logiciel se fasse sous la même licence[^parttrois14], b) à une licence de brevet qui s'étend automatiquement à tout brevet détenu par un contributeur sur sa contribution, c) à une interdiction d'opposer d'éventuels droits qui seraient détenus sur une mesure technique de protection.


L'_étendue_ de la GNU AGPL est particulièrement large puisqu'elle reprend celle de la GNU GPL sans l'adapter aux solutions logicielles donnant accès à des services&nbsp;: ainsi sont soumises à la licence (et doivent donc être distribuées selon les termes de cette dernière) les versions modifiées du logiciel, mais aussi les versions basées sur le logiciel[^parttrois15]&nbsp;&ndash; la limite étant celle de l'«&nbsp;agrégat&nbsp;», compris comme «&nbsp;une compilation du code couvert (par la licence) avec d'autres œuvres séparées et indépendantes, qui ne sont pas par leur nature des extensions du code couvert, et qui ne sont pas combinées comme un programme plus large, sur ou dans un média de stockage ou de distribution…&nbsp;»

En matière d'_élément déclencheur_, deux hypothèses se cumulent&nbsp;: la distribution du logiciel (comprise comme la mise à disposition de celui-ci[^parttrois16]) ou l'interaction via le réseau d'une version modifiée du logiciel (il faut une interaction _et_ une modification).



## GNU Free Documentation licence (GNU FDL) {-}

La licence [GNU FDL](http://www.gnu.org/licenses/fdl.html) est le pendant de la GNU GPL, utilisable de façon complémentaire sur la documentation des logiciels libres. La première version de la GNU FDL date de 1999, elle a ensuite connu deux révisions successives en 2000 (v.&nbsp;1.1) et 2002 (v.&nbsp;1.2) et une plus récente en 2008 (v.&nbsp;1.3). Le [draft de la GNU FDL v 2.0](http://gplv3.fsf.org/fdl-draft-2006-09-22.html) est en discussion depuis 2006 (ainsi que celui de sa petite sœur, la [GNU Simpler FDL v.&nbsp;1.0](http://gplv3.fsf.org/sfdl-draft-2006-09-26.html), licence plus souple qui supprime notamment les mécanismes complexes de la GNU FDL).

En termes d'_obligation_, la licence GNU FDL est une licence _copyleft_. Elle offre la possibilité de préciser la présence de certaines sections invariantes (toute information ne peut néanmoins être identifiée comme telle) afin d'empêcher tout contributeur subséquent d'y apporter des modifications (ou même de la supprimer). Par ailleurs, elle impose un formalisme particulier attaché à la diffusion de la version papier de la création diffusée sous GFDL (un formalisme assez contraignant qui passe notamment par l'impression de l'intégralité du texte de la licence).

En termes de _compatibilité_, la licence est une licence _copyleft_ classique, c'est-à-dire sans autre compatibilité qu'avec les versions ultérieures de la même licence. Néanmoins, la publication de la version&nbsp;1.3 prévoyait une compatibilité expresse et limitée au profit de la CC-By-SA 3.0 &ndash;&nbsp;par ailleurs spécialement limitée au seul bénéfice des sites de collaboration multiauteurs (_Massive Multiauthor Collaboration Site_) et avant le 1^er^ août 2009 (cela pour répondre à la demande de la fondation Wikimedia qui souhaitait modifier la licence de Wikipedia).


------------------------------------

__Remarque__

   - Cette licence est l'une des «&nbsp;[DFSG-incompatibles](http://wiki.debian.org/DFSGLicenses)&nbsp;» &ndash;&nbsp;par exception, la licence est considérée comme libre lorsqu'utilisée&nbsp; [GFDL sans sections invariantes](http://www.debian.org/vote/2006/vote_001)&nbsp;;
   - La FSF a publié un article sur «&nbsp;[comment utiliser la FDL de GNU pour vos documents](http://www.gnu.org/licenses/fdl.html).&nbsp;»

-------------------------------------


## MIT License {-}

La [licence MIT](http://opensource.org/licenses/mit-license.php), dans ses différentes versions, est une licence libre très permissive qui ressemble beaucoup à la licence BSD&nbsp;: elle opère le partage de tous les droits patrimoniaux de l'auteur sous la seule condition de respecter la paternité de ce dernier et de conserver les mentions légales. Il s'agit ainsi d'une sorte de «&nbsp;mise dans le domaine public.&nbsp;»[^parttrois17]

Elle se distingue néanmoins de la licence BSD par une plus grande description des droits cédés (qui lui vaut d'être souvent préférée).

Les _obligations_ de la licence concernent essentiellement les mentions légales et la licence qui doivent être incluses dans toute copie ou «&nbsp;portion substantielle&nbsp;».

L'_étendue_ de la licence se limite à la seule portion du code publiée sous cette licence et l'_élément déclencheur_ est la distribution, diffusion, de copies du logiciel. 

Enfin, en raison de son caractère peu contraignant, la licence est _compatible_ avec la majorité des autres licences (commerciales ou libres).

## Mozilla Public License (MPL) {-}

Crée en 1998 à l'occasion de la libération du code source de Netscape Communicator 5, la MPL est actuellement utilisée en sa version&nbsp;1.1, une version&nbsp;2.0 est néanmoins en cours d'écriture &ndash;&nbsp;intégrant quelques idées qui avaient justifié la création de la licence CPAL. 

### Mozilla Public License v.&nbsp;1.1 {-}

Autorisation expresse est donnée de _sous-licencier_ le code. La [MPL](http://www.mozilla.org/MPL) est _copyleft_. En matière de brevets, une licence expresse (auteurs initiaux et contributeurs) autorise toute fabrication, utilisation ou vente du logiciel original, ses modifications et/ou des combinaisons entre le logiciel et les modifications (le tout limité à la seule version du contributeur auteur).

Quant à l'_étendue_&nbsp;: se limitant aux seules modifications apportées au logiciel, la licence permet de contribuer au logiciel sans devoir distribuer sous la même licence tant que les fichiers contenant du code sous MPL restent sous MPL (les autres fichiers pouvant dès lors être soumis à n'importe quelle autre licence).

L'_élément déclencheur_ est la distribution (ou toute autre communication du code à un tiers). En cas de violation de la licence, la licence se termine automatiquement dans les trente jours qui suivent la prise de connaissance de cette violation par le licencié.

### Mozilla Public License v.&nbsp;2.0 {-}

En plus de préciser les définitions de la version précédente, la [seconde version](http://mpl.mozilla.org) poursuit des objectifs supplémentaires&nbsp;:

   - en termes d'_élément déclencheur_, il était envisagé que l'utilisation par le réseau soit assimilée à une distribution et emporte des obligations &ndash;&nbsp;notamment pour ce qui concerne les mentions légales&nbsp;;
   - en termes de _compatibilité_, la licence prévoit la possibilité de diffuser le composant sous licence GNU (GPL, LGPL ou AGPL) en situation d'incompatibilité.


### Common Public Attribution License Version 1.0 (CPAL) {-}

Approuvée par l'OSI en 2007, la licence CPAL s'inspire de la MPL qu'elle module sur deux aspects&nbsp;:

   - concernant les _obligations_, la licence ajoute une obligation d'attribution de paternité renforcée[^parttrois18];
   - concernant l'_élément déclencheur_, la licence associe la notion de déploiement externe (_external deployment_) à celle de distribution[^parttrois19].



## CeCILL(-A, -B, -C) {-}

Les licences [CeCILL](http://www.cecill.info/licences.fr.html), acronyme pour Ce(A) C(nrs) I(NRIA) L(ogiciel) L(ibre), furent créées pour répondre aux arguments qui empêchaient les administrations françaises d'utiliser les licences GNU pour diffuser leurs logiciels&nbsp;: l'application de la loi 94-665 du 4 août 1994 relative à l'emploi de la _langue française_ (plus connue sous le nom de _loi Toubon_, ministre de la Culture de l'époque) qui contraint toute administration à s'appuyer sur des textes juridiques français, le constat d'imprécision à l'égard du droit français (droit sur lequel repose la licence, droits patrimoniaux, clause de non garantie).

Elles sont toutes construites sur le canevas de la première licence (la licence CeCILL ou CeCILL-A).

### La CeCILL-A {-}

Première des licences, la licence CeCILL (ou CeCILL-A) précéda la rédaction des deux autres.

En termes d'obligations, la CeCILL-A, rédigée sur le modèle de la GNU GPL, est une licence _copyleft_  qui impose donc la redistribution selon ses propres termes. Par ailleurs, le concédant s'engage à ne pas opposer d'«&nbsp;éventuels droits conférés par ces brevets aux licenciés successifs qui utiliseraient, exploiteraient ou modifieraient le logiciel&nbsp;». Par ailleurs, «&nbsp;en cas de cession de ces brevets, le concédant s'engage à faire reprendre les obligations du présent alinéa aux cessionnaires.&nbsp;»

Son _étendue_ se limite au logiciel et à ses seuls modules internes, ces derniers étant entendus comme tout module lié au logiciel de telle sorte qu'il s'exécute dans le même espace d'adressage. Tout autre module, appelé module externe, n'est pas soumis aux licences

L'_élément déclencheur_ est la distribution (envisagée comme «&nbsp;notamment le droit de diffuser, de transmettre et de communiquer le Logiciel au public sur tout support et par tout moyen ainsi que le droit de mettre sur le marché à titre onéreux ou gratuit, un ou des exemplaires du logiciel par tout procédé&nbsp;». Il est a noter que les rédacteurs de la licence CeCILL estiment, contre toute attente, que leur licence appréhende les usages par le réseau[^parttrois20] (il semble néanmoins plus prudent de considérer que, sauf mention contraire de l'auteur lors de la diffusion sous licence CeCILL, un tel usage n'est pas saisi par la licence elle-même).

La licence est _compatible_ avec la CeCILL-A et la CeCILL-C. Ainsi toutes les clauses qui rendraient la licence CeCILL-B incompatible avec la CeCILL-A et CeCILL-C sont suspendues en cas de situation d'incompatibilité (mécanisme de compatibilité expresse passive)[^parttrois21].

### La CeCILL-B {-}

La CeCILL-B, rédigée sur le modèle de la BSD, n'est pas _copyleft_, mais contient une clause supplémentaire en matière de citation. Ainsi, en cas de modification du logiciel (qui ne serait pas qualifié de module externe), le licencié qui distribue s'engage expressément

   1. à faire référence au logiciel avec ses mentions légales dans sa documentation&nbsp;;
   2. à faire en sorte que les mentions légales soient indiquées dans un texte facilement accessible depuis l'interface du logiciel&nbsp;;
   3. à mentionner, sur un site Web librement accessible décrivant le logiciel modifié, et pendant au moins toute la durée de sa distribution, qu'il a été réalisé à partir du logiciel&nbsp;;
   4. et lorsqu'il le distribue à un tiers susceptible de distribuer lui-même un logiciel modifié, sans avoir à en distribuer le code source, à faire les meilleurs efforts pour que les obligations soient reprises.

La licence est _compatible_ avec la CeCILL-A et la CeCILL-C. Ainsi toutes les clauses qui rendraient la licence CeCILL-B incompatible avec la CeCILL-A et CeCILL-C sont suspendues en cas de situation d'incompatibilité (mécanisme de compatibilité expresse passive)[^parttrois22].

### La CeCILL-C {-}

Basée sur le CeCILL, la licence CeCILL-C limite son _étendue_ en matière de _copyleft_ à l'instar de la MPL (les autres obligations restant intouchées) puisqu'elle permet expressément la diffusion sous leur propre licence de modules liés (ensembles de fichiers sources y compris leur documentation qui, sans modification du code source, permet de réaliser des fonctionnalités ou services supplémentaires à ceux fournis par le logiciel).

La licence est _compatible_ avec la CeCILL-A, de telle sorte que toutes les clauses qui rendraient la licence CeCILL-C incompatible avec la CeCILL-A sont suspendues en cas de situation d'incompatibilité (mécanisme de compatibilité expresse passive)[^parttrois23].

## Les licences Creative Commons {-}

Quatrième série des licences Creative Commons (la numérotation intermédiaire 2.5 s'expliquant par les faibles changements qu'elle intégrait), les CC 3.0 furent rédigées en 2009 &ndash;&nbsp;publiées en version  _unported_ avant d'être transposées dans les diverses juridictions (les versions françaises, pourtant traduites depuis près de deux ans, ne sont pas encore officiellement publiées). Elles sont aujourd'hui détachées du droit américain pour simplifier leur portage et intègrent de nouveaux dispositifs (notamment concernant les DRM et le droit _sui generis_ des bases de données).

Les licences Creatives Commons sont dédiées aux œuvres utilitaires (et ne sont donc pas adaptées à une [utilisation sur des logiciels](https://wiki.creativecommons.org/wiki/Frequently_Asked_Questions#Can_I_use_a_Creative_Commons_license_for_software.3F) ou [bases de données](https://creativecommons.org/weblog/entry/26283)).


### Droits et obligations {-}

Concernant les droits, toutes les licences Creatives Commons ne sont pas aussi libres et elles n'ont donc en commun que de permettre la diffusion et l'utilisation non commerciale des œuvres _non modifiées_.

Ainsi, les deux premières clauses limitent les droits accordés&nbsp;:

   - les utilisations commerciales sont autorisées dès lors que la clause NC n'est pas utilisée&nbsp;;
   - la modification est permise tant que la clause ND n'est pas utilisée.


Tandis que les deux autres clauses ajoutant des obligations relatives à l'utilisation de l'œuvre partagée&nbsp;:

   - la clause By (obligatoire)&nbsp;;
   - la clause Share Alike (SA) introduit un mécanisme de _copyleft_ au sein de la licence.

### L'étendue {-}

Dans leur seconde version, les licences CC distinguent les œuvres collectives (un ensemble d'œuvres) des œuvres «&nbsp;dites dérivées » (qui rejoint la définition française de l'œuvre dérivée). Au surplus, la licence précise  que si l'œuvre est «&nbsp;une composition musicale ou un enregistrement sonore, la synchronisation de l'œuvre avec une image animée sera considérée comme une œuvre dite dérivée pour les propos de ce contrat.&nbsp;»

Dans leur troisième version, les termes utilisés sont «&nbsp;compilation&nbsp;» et «&nbsp;adaptation&nbsp;» (avec une portée similaire).

### L'élément déclencheur {-}

Les licences CC ne précisent aucune sphère privée&nbsp;: tout acte autorisé par la licence est conditionné au respect des obligations de celle-ci (voir l'article 4 «&nbsp;Restrictions&nbsp;: L'autorisation accordée par l'article 3 est expressément assujettie et limitée par le respect des restrictions suivantes…&nbsp;»).

### La compatibilité {-}

La _compatibilité_ est l'un des points forts des licences Creative Commons&nbsp;: dès lors que la licence n'est pas _copyleft_ (clause Share Alike), il est possible de redistribuer l'œuvre sous une licence plus contraignante que précédemment (par exemple en rajoutant un NC ou ND à une licence CC By, ou en distribuant des articles sous CC By-NC dans un ouvrage sous CC By-NC-ND &ndash;&nbsp;voire sous licence commerciale classique).

Au surplus, la CC By-SA insère une nouvelle compatibilité dans sa troisième version au travers la licence CC By-SA, permettant la redistribution sous d'autres licences compatibles (le dispositif tarde néanmoins à être activé[^parttrois24]).

# La licence Art Libre

Recommandée par la [FSF](http://www.vvlibri.org/index.php?title=FSF), la licence Art Libre (LAL) est certainement la licence appliquée aux créations artistiques la plus proche de l'esprit originaire du Libre. Elle est porteuse d'une philosophie adaptée à l'ensemble des pratiques artistiques (y compris logicielles) et rassemble l'aspect communautaire qui fait la force de ces licences (et qui explique qu'elle soit souvent utilisée par conviction, sans forcément être lue). La licence 1.3 «&nbsp;est rédigée en référence au droit français et à la Convention de Berne relative au droit d'auteur&nbsp;» (les versions précédentes, expressément soumises au droit français restaient néanmoins valides dans tous les pays signataires de la Convention de Berne).

Les changements apportés depuis sa rédaction en 2000 sont peu importants&nbsp;: une meilleure prise en compte du _copyleft_ afin de l'adapter effectivement aux œuvres d'art (insertion de la précision d'originels et conséquents dans l'article&nbsp;3) par la version&nbsp;1.2 et, en avril 2007, la version 1.3 (en cours) est venue apporter certains changements prévenant notamment les conflits entre droits de propriété intellectuelle (article 3&nbsp;: «&nbsp;droits connexes&nbsp;»), et entre licences similaires.

Les _obligations_ sont de plusieurs ordres. En termes de responsabilité, la LAL rappelle que «&nbsp;la liberté de jouir de l'œuvre tel que permis par la LAL (liberté de copier, diffuser, modifier) implique pour chacun la responsabilité de ses propres faits&nbsp;». En termes de formalisme, les mentions légales classiques sont demandées (avec la précision des modifications lorsqu'il y a lieu) et un simple lien vers la licence est suffisant&nbsp;: placer son œuvre sous licence Art Libre requiert l'implémentation d'un court texte, et des notations (Copyright, Année Nom de l'auteur ou nom de l'auteur original). Un exemple est donné&nbsp;:

	Nom de(s) l'auteur(s), titre, date et
	le cas échéant, le nom des auteurs de
	l'œuvre initiale et conséquentes ainsi
	que leurs localisations _Copyleft_ :
	cette œuvre est libre, vous pouvez la
	copier, la diffuser et la modifier selon
	les termes de la Licence Art Libre
	http://www.artlibre.org.



L'_étendue_ de la licence est relativement standard&nbsp;: les compilations d'œuvres sont permises sans qu'une licence soit imposée pour le tout. 

L'_élément déclencheur_ est la diffusion (définie comme l'interprétation, la représentation ou la distribution).

De par leur _copyleft_, les versions antérieures à la LAL v.&nbsp;1.3 ne sont pas compatibles avec une autre licence _copyleft_ ou qui imposerait certaines restrictions supplémentaires (comme la licence&nbsp;CC By&nbsp;par exemple). Pour résoudre cette incompatibilité de fait, la LAL v.&nbsp;1.3 introduit un nouvel article (5. «&nbsp;Critères de compatibilité&nbsp;») grâce auquel, dès lors qu'il y a modification de l'œuvre, une compatibilité avec toute licence répondant à un certain nombre d'exigences (être une licence libre, _copyleft_, et réciproquement compatible envers la LAL) est possible. Actuellement, la licence CC By-SA v&nbsp;3.0 est la seule susceptible d'être déclarée comme compatible, dès lors que le mécanisme qu'elle-même contient sera opérationnel (il faut notamment que la LAL soit indiquée comme compatible sur le site de Creative Commons).

## L'OpenDatabase License {-}

La particularité des licences attachée à des bases de données réside dans l'(in)adaptation à leurs objets&nbsp;: les données &ndash;&nbsp;ou, plus précisément, un ensemble de données organisées sous forme de bases de données.

En effet, contrairement aux créations classiques (logiciels, articles, etc.), les données ne génèrent pas, en tant que telles, un quelconque droit de propriété intellectuelle au profit de celui qui les crée, les détient ou les exploite &ndash;&nbsp;sauf à ce qu'elles en réunissent les critères (elles sont alors des créations originales soumises au droit d'auteur&nbsp;&ndash; cette qualification concernant l'organisation globale de la base, mais non les extractions qui peuvent en être faites). Or, en l'absence de droit exclusif qui permettrait de conditionner chaque usage au respect du cadre contractuel défini, celui qui détient des données se trouve démuni face à toute personne qui aurait pris connaissance des données sans contracter.

C'est à cette problématique que tente de répondre l'ODbL, la licence faisant reposer son efficience sur une assiette plus large que le seul droit d'auteur, en incluant également le droit des contrats et le droit _sui generis_ des bases de données (article 2.0, «&nbsp;Champ d'application de la présente licence&nbsp;»). Ainsi, la condition essentielle de la licence, son _copyleft_, impose que toute base de données &ndash;&nbsp;modifiée ou non&nbsp;&ndash; soit distribuée sous la même licence. C'est cette prise de conscience qui a conduit le projet OpenStreetMap a mettre en place un processus de changement de licence au profit de l'ODbL.

La licence ne couvre néanmoins pas le contenu même de la base de données pris isolément. Une nouvelle licence peut alors y être associée (article 2.4, «&nbsp;Rapport avec le contenu de la base de données&nbsp;»), ni même les brevets ou marques qui pourraient y figurer (article&nbsp;2.3, «&nbsp;Droits non compris dans la licence&nbsp;»).

### Droits et obligations {-}

Tout accès, toute transmission ou toute publication d'une base de données (d'origine, dérivée ou en tant que partie d'une BdD collaborative) vaut acceptation de la licence.

L'utilisateur bénéficie ainsi de certains droits tout en étant tenu par certaines obligations.

#### Droits {-}

Tous les droits d'auteur et droits _sui generis_ détenus sur la base de données sont cédés (non exclusivement) à l'utilisateur de la base. Il en est de même de tout autre droit inclus dans la base et dont la cession est nécessaire au respect de la licence (article 10.4).

La licence n'autorise pas les sous-licences (il n'y a pas de chaîne contractuelle&nbsp;: chaque titulaire cédant ses seuls droits à chaque utilisateur) et est bien sûr non exclusive (article&nbsp;3.3).

#### Obligations {-}

Tout manquement aux obligations de la licence entraîne la résiliation de la licence (article 9.0, «&nbsp;Cessation de vos droits au titre de la présente licence&nbsp;») &ndash;&nbsp;même si un processus de rétablissement des droits est prévu pour réintroduire les utilisateurs «&nbsp;repentants&nbsp;» dans leurs droits (les personnes dont les droits font l'objet d'une cessation permanente ne pouvant bénéficier d'une nouvelle licence).

#### _Copyleft_ (partage à l'identique des conditions initiales) {-}

La base de données d'origine et les bases de données dérivées doivent être licenciées sous la même licence ou sous l'une des licences compatibles (article&nbsp;4.4, «&nbsp;Partage à l'identique des conditions initiales&nbsp;»).

#### Formalisme {-}

La licence impose un certain formalisme relatif à l'utilisation des bases (ou des créations générées) et à leur transfert.

Ainsi, en cas d'utilisation publique d'une base de données (originale, dérivée ou collaborative) ou d'une création issue d'une telle base,

   - il faut mentionner la licence et les bases de données sous ODbL utilisées&nbsp;;
   - en présence d'une BdD dérivée, il faut rendre disponible une copie numérique de la totalité de celle-ci ou un fichier contenant toutes les modifications apportées.

Lors de la transmission de la BdD, il faut veiller à conserver les mentions légales intactes et inclure une copie de l'ODbL ou de son URI (dans la BdD, originale ou dérivée, ou toute autre documentation pertinente). Le coût de cette transmission doit être raisonnable, voire gratuit en cas de distribution en ligne.

#### Divers {-}

La licence contient par ailleurs une interdiction de l'usage de mesures techniques de protection (MTP), sauf à rendre parallèlement disponible ladite base sans MTP, ainsi qu'une exclusion de garantie et une limitation de responsabilité totale (la portée de ces dernières étant limitée en France).

### Étendue {-}

Au-delà de la base de données d'origine, la licence doit être étendue à toute base de données dite  _dérivée_ (base de données _reposant sur_ la base originaire) et exploitée publiquement.

La licence permet néanmoins toute utilisation conjointe de plusieurs bases de données indépendantes. Il s'agit alors de bases de données collaboratives et seules la base de données d'origine ou ses dérivées doivent être diffusées sous ODbL.

### Éléments déclencheurs {-}

La licence n'impose aucune contrainte quant au transfert, à l'utilisation privée de la base de données ou à la conception de créations grâce à ladite base de données.

La licence prend ses pleins effets dès lors qu'il y a&nbsp;:

   - transfert public de la base de données (la communication d'une copie, de la base à un tiers)&nbsp;;
   - l'utilisation publique (mise au contact de tiers) d'une base de données dérivée ou d'une création issue de cette base (originale, dérivée ou partie d'une base de données collaborative). 

### Compatibilité {-}

Un mécanisme de compatibilité expresse est prévu au sein de la licence, laissant à la charge du concédant le soin de préciser quelles sont les licences compatibles ou de désigner un mandataire qui le fera pour son compte (article&nbsp;4.4e).

## PHP License v.3.01 {-}

La licence PHP est une licence _open source_ aujourd'hui utilisée en version [3.01](http://www.php.net/license/3_01.txt). C'est une licence permissive, qui contient néanmoins quelques _obligations_ en matière d'attribution&nbsp;:

   - pour tout type de distribution, l'indication de l'utilisation du logiciel par la mention ``This product includes PHP software, freely available from <http://www.php.net/software/>``&nbsp;;
   - l'interdiction d'utiliser le mot PHP comme titre de toute création dérivée&nbsp;: «&nbsp;Products derived from this software may not be called _PHP_, nor may _PHP_ appear in their name, without prior written permission from group@php.net. You may indicate that your software works in conjunction with PHP by saying _Foo for PHP_ instead of calling it _PHP Foo_ or _phpfoo_.&nbsp;»



## OSL (Open Software License) {-}

L'[Open Software License](http://www.opensource.org/licenses/OSL-3.0) (OSL) est une licence issue des travaux du juriste américain Lawrence E. Rosen. La version 1.1 date de 2002 et fut certifiée _open source_ par l'_Open Source Initiative_ (OSI), mais fut déclarée incompatible avec la DFSG par la communauté Debian. La version&nbsp;2.0 date de 2003, et la dernière version &ndash;&nbsp;la troisième&nbsp;&ndash; de 2005 (elle prend notamment en compte les remarques de la Commission européenne).

Cette licence permet expressément les sous-licenciements, mais ceux-ci doivent impérativement se faire sous la même licence.

En termes d'_obligations_, la licence est gratuite (mais la communication de l'œuvre peut être payante), non exclusive et perpétuelle et porte sur les droits d'auteur comme sur ceux des brevets contenus dans le code soumis à la licence (la licence cherche à créer ici un pot commun de brevets, équivalent à celui issu de l'usage des licences _copyleft_). Quiconque poursuit l'auteur original ou ses utilisateurs pour violation de brevet contenu dans le logiciel soumis à cette licence voit toutes les licences qui lui étaient accordées se terminer immédiatement. Enfin, la licence incorpore une limitation &ndash; et non pas une exclusion &ndash; de garantie (de la provenance des sources) et de responsabilité à l'égard du concédant, solution bien plus pragmatique puisqu'il s'agit de ce qui est, dans les faits, le minimum légal. Toutes les actions ou poursuites doivent se faire devant un tribunal de la juridiction du lieu où le concédant exerce son activité principale. Par ailleurs, tous les frais d'avocats seront à la charge de la partie qui poursuit. Enfin, la licence OSL est de type _copyleft_.

L'_étendue_ de la licence n'est pas contractuellement définie et renvoie expressément à la définition de l'œuvre dérivée dans la loi américaine sur le copyright. À noter que le code source, tel que défini par l'OSL, étend la licence à la «&nbsp;documentation décrivant comment modifier l'œuvre originale&nbsp;».

L'_élément déclencheur_ s'appuie sur la notion de déploiement externe[^parttrois25] (_external deployment_) qui englobe l'utilisation et les liaisons par réseau de logiciels. Celles-ci sont considérées comme une distribution et soumises en tant que telles à la licence.





<!-- NOTES -->

[^parttrois1]: Cf. partie II, chapitre 2&nbsp;: «&nbsp;2.3 Déchiffrer&nbsp;: une grille de lecture de licences libres&nbsp;».

[^parttrois2]: Article 5, _external deployment_&nbsp;: «&nbsp;The term _External Deployment_ means the use, distribution, or communication of the Original Work or Derivative Works in any way such that the Original Work or Derivative Works may be used by anyone other than You, whether those works are distributed or communicated to those persons or made available as an application intended for use over a network. As an express condition for the grants of license hereunder, You must treat any External Deployment by You of the Original Work or a Derivative Work as a distribution under section 1(c).&nbsp;»

[^parttrois3]: Même si dans son livre Lawrence Rosen doute de la pertinence d'une telle protection attachée aux licences[@Rose2004].

[^parttrois4]: Il est encore néanmoins possible de retrouver la version&nbsp;1.0 dans certains projets, comme OpenSSL License.

[^parttrois5]: «&nbsp;When code is released as a series of files, a modification is: (a) any addition to or deletion from the contents of a file containing Covered Code; and/or (b) any new file or other representation of computer program statements that contains any part of Covered Code.&nbsp;»

[^parttrois6]: Traduction personnelle&nbsp;: 1.4 &ndash;&nbsp;«&nbsp;déployé extérieurement&nbsp;» signifie&nbsp;: (a)&nbsp;de sous-licencier, distribuer ou rendre le _code couvert_ disponible autrement, directement ou indirectement, à quiconque autre que vous, et/ou (b)&nbsp;d'utiliser le  _code couvert_, seul ou comme partie d'une création plus large, d'une manière à fournir à service, notamment pour fournir du contenu, à travers une communication électronique avec un client autre que vous.

[^parttrois7]: «&nbsp;As described in article 1(b)(ii) of the Eclipse Public License, _…Contributions do not include additions to the Program which: (i) are separate modules of software distributed in conjunction with the Program under their own license agreement, and (ii) are not derivative works of the Program_. The definition of derivative work varies under the copyright laws of different jurisdictions. The Eclipse Public License is governed under U.S. law. Under the U.S. Copyright Act, a _derivative work_ is defined as _…a work based upon one or more preexisting works, such as a translation, musical arrangement, dramatization, fictionalization, motion picture version, sound recording, art reproduction, abridgment, condensation, or any other form in which a work may be recast, transformed, or adapted. A work consisting of editorial revisions, annotations, elaborations, or other modifications which, as a whole, represent an original work of authorship, is a derivative work_. The Eclipse Foundation interprets the term _derivative work_ in a way that is consistent with the definition in the U.S. Copyright Act, as applicable to computer software. You will need to seek the advice of your own legal counsel in deciding whether your program constitutes a derivative work.

[^parttrois8]: À noter cependant que la version&nbsp;1.0 de la licence n'avait que la distribution comme élément déclencheur.

[^parttrois9]: Sont actuellement concernées&nbsp;: la GNU General Public License (GNU GPL) v. 2, l'Open Software License (OSL) v. 2.1, v. 3.0 , la Common Public License v. 1.0 , l'Eclipse Public License v. 1.0 et la CeCILL v. 2.0.


[^parttrois10]: Sauf à envisager une politique de type «&nbsp;double licence&nbsp;» qui permettrait, moyennant un certain prix, le développement de module tiers commerciaux. Ceci peut néanmoins être un frein à la diffusion du logiciel.


[^parttrois11]: La «&nbsp;source correspondante&nbsp;» d'une création sous forme de code objet désigne tout le code source nécessaire pour générer, installer et (pour une création exécutable) exécuter le code objet et modifier la création, y compris les scripts pour contrôler ces activités. Cependant, cela n'inclut pas les bibliothèques systèmes de la création, ni les outils d'usage général ou les programmes libres généralement disponibles qui peuvent être utilisés sans modification pour réaliser ces activités, mais ne sont pas partie de cette création. Par exemple, la source correspondante inclut les fichiers de définition d'interfaces associés aux fichiers sources de la création, et le code source des bibliothèques partagées et des sous-programmes liés dynamiquement, dès lors que la création est spécialement conçue pour les requérir via, par exemple, des communications de données ou contrôles de flux internes entre ces sous-programmes et d'autres parties de la création.


[^parttrois12]: Néologisme définissant la création d'un système qui inclut des logiciels libres, mais utilise le matériel électronique pour interdire aux utilisateurs d'y exécuter des versions modifiées (voir la page Wikipedia consacrée).

[^parttrois13]: La précédente version, corédigée par la société Affero et la FSF, n'était pas une licence (de la famille) GNU.

[^parttrois14]: L'article&nbsp;7 de la GNU Affero GPL autorise l'ajout d'un certain nombre de clauses sur des parties clairement identifiées du logiciel.

[^parttrois15]: La licence emploie le vocabulaire «&nbsp;_modified version_&nbsp;», «&nbsp;_work based on_&nbsp;» et «&nbsp;_entire work, as a whole_&nbsp;».

[^parttrois16]: Il est néanmoins possible (à l'instar de la GNU GPL v.&nbsp;3) de faire appel à des prestataires sans que leurs développements pour le compte de leur client ne soient considérés comme une distribution.

[^parttrois17]: Une telle renonciation au droit est sans valeur, c'est-à-dire sans effet, en droit français. D'où la nécessité d'user d'une telle licence aux effets similaires.

[^parttrois18]: Article 14, Additional term&nbsp;: «&nbsp;the Original Developer may include …a requirement that each time an Executable and Source Code or a Larger Work is launched or initially run …a prominent display of the Original Developer's Attribution Information …must occur on the graphic user interface employed by the end user to access such Covered Code…&nbsp;»

[^parttrois19]: Article 15, «&nbsp;Terme additionnel&nbsp;: utilisation réseau&nbsp;». Le terme «&nbsp;déploiement externe&nbsp;» signifie l'utilisation, distribution ou communication du code original ou des modifications d'une façon telle que le code original ou les modifications puissent être utilisés par toute autre personne que vous, que ces œuvres soient distribuées ou communiquées à ces personnes ou rendues disponibles comme une application destinée à une utilisation sur le réseau.

[^parttrois20]: Voir la [FAQ](http://www.cecill.info/faq.fr.html)&nbsp;: «&nbsp;Si le 5.3.2 parle de distribution, il s'agit, comme indiqué en préambule de l'article&nbsp;5.3, de _diffuser, de transmettre et de communiquer le logiciel au public, sur tout support et par tout moyen_. Une mise à disposition via un site web ou un serveur est donc bien une distribution même si l'utilisateur ne dispose pas d'un exemplaire du logiciel en propre, et l'obligation de fournir le code source du logiciel modifié s'applique.&nbsp;»

[^parttrois21]: Article 5.3.4&nbsp;: Compatibilité avec la licence GNU GPL.

[^parttrois22]: Article 5.3.5&nbsp;: Compatibilité avec les licences CeCILL et CeCILL-C.

[^parttrois23]: Article 5.3.4&nbsp;: Compatibilité avec la licence CeCILL.

[^parttrois24]: Voir notamment [recherche de compatibilité](http://lists.ibiblio.org/pipermail/cc-licenses/2007-February/005013.html) au sein de la licence Creative Commons 3.0.

[^parttrois25]: Article 5, «&nbsp;Déploiement externe&nbsp;»&nbsp;: utilisation, distribution, communication de l'oeuvre originale ou des oeuvres dérivées afin qu'elles soient utilisées par toute autre personne que vous, même si ces oeuvres sont distribuées ou communiquées à ces personnes ou rendues disponibles sous forme d'applications conçues pour une utilisation réseau.

<!-- /NOTES -->



