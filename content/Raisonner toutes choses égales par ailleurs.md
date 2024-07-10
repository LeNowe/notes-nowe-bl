***
# Raisonner toutes choses égales par ailleurs
**Source** : [[Raisonner toutes choses égales par ailleurs.pdf]] cf. aussi [[Epistémologie des sciences économiques.pdf]] 
***
## <u>I. L’ambition d’un raisonnement toute chose égale par ailleurs</u>

> On dit parfois que les lois de l'économie sont "hypothétiques". Bien sûr, comme toute autre science, [l'économie] entreprend l'étude des effets que produisent certaines causes, non pas absolument, mais **sous la condition que toutes choses soient égales par ailleurs** et que les causes puissent exercer leurs effets **sans interférence**. Presque toute doctrine scientifique, lorsqu'elle est énoncée formellement, s'avère contenir une clause selon laquelle toutes choses sont égales par ailleurs ; l'action des causes en question est supposée **isolée** ; certains effets leur sont attribués, mais seulement sous l'hypothèse qu'aucune cause n'est autorisée à intervenir, en dehors de celles qui ont été distinctement permises. – MARSHALL ( *Principes d’économie politique*, 1890 )

Pour MARSHALL raisonner en termes d’équilibre général n’est pas une mince à faire. Il faut raisonner en équilibre partiel. 

<u>Ex</u> : la loi de demande raisonnent TTEPA et ne considère pas de potentiels modifications prix relatifs. Cf. demande de tabac dépend aussi des variations des prix des substituts. 

Raisonner TTEPA suppose de se donner une théorie établissant les différentes causes possibles dont il s’agit d’évaluer les effets. Mais pour intuitionner ces causes possibles et donner des modèles crédibles il y a une nécessité d’études qualitatives. **L’imagination économique et sociologique doit présider au travail économétrique.** 

⚠ devant un jury il faut toujours défendre un **pluralisme méthodologique**. Même au sein des méthodes quantitatives. 

<div style="page-break-after: always;"></div>

### A ) Neutraliser les effets de structure 

#### 1. Repérer un effet de structure 

**Effet de structure** : Lorsqu'une population est répartie en sous-populations, il peut arriver qu'une grandeur évolue dans un sens sur chaque sous-population et dans le sens contraire sur l'ensemble de la population. Ce paradoxe s'explique parce que les effectifs de certaines sous-populations augmentent alors que d'autres régressent. 

<u>Ex</u> : de 1982 à 2009 le chômage augmente dans les diplômés et les non diplômés mais baisse dans l’ensemble de la population. 

Cet effet devient un biais s’il n’est pas remarqué lorsqu’on étudie : 
- Des évolutions de pratiques ou de représentations d’une population entre deux dates. 
- Deux populations différenciées à une même date.

⚠ Les lignes « ensemble » dans les tableaux sont des calculs pondérés et non de simples additions. Dépend donc de la structure de la population. 

**Pour neutraliser l’effet de structure on calcule la variation qu’on aurait observée à structure de la population constante**. 

$$\text{variation totale = variation due à l'effet de structure + variation nette}$$

Pour évaluer la variation nette et raisonner TCEPA  il faut introduire des **variables de contrôle**. Sinon on constitue un artefact sociologique… Pour cela il faut distinguer : 
- **Dans une évolution** : ce qui s’explique par l’évolution de la structure de la population / ce qui s’explique par l’évolution des pratiques ou représentations de la population. 
- **Dans une comparaison** : ce qui s’explique par la répartition des sous-population dans les deux groupes / ce qui s’explique autrement. 

#### 2. Quelques exemples : structures par âge et effet d’établissement

<u>Ex</u> : un effet de la structure par âge avec le niveau d’étude et la probabilité de se trouver en prison. Immédiatement, on conclut que la probabilité de se retrouver en prison décroît avec le niveau de diplômes. Mais on se heurte à une difficulté : les hommes en prison sont plus jeunes que les hommes libres. Or il faut tenir compte des évolutions de la scolarisation.  ⚠ Neutraliser ne signifie pas diminuer l’effet mais au contraire chercher la mesure de la seule variable, mesurer son poids. 

Il s’agit ici de calculer une proba conditionnelle = P ( « être en prison » | « niveau d’étude », « âge » ). Cette **relation d’intérêt** ne dépend donc pas d’un unique paramètre. On essaye alors de raisonner « **à structure par âges égale** » *i.e* comme si les deux populations possédaient la même structure par âge par un calcul d’espérance. 

On peut ainsi établir TCEPA que les hommes ayant une scolarité plus courte sont bien surreprésentés dans la population carcérale. 

<u>Ex</u> : réussite des filles au bac. Peut dépendre d’« **effet d’établissement** ». 

### B ) Construire des régressions linéaires 

#### 1. Qu’est-ce qu’une régression linéaire ?

Objectif : expliquer variations d’une variable quantitative par les variations d’une autre. 
- **Variable dépendante ou de réponse** = variable à expliquer notée Y
- **Variable indépendante** = variable explicative notée X 

La **droite de régression** obtenue à l’aide de la **méthode des moindres carrés** de visualiser une corrélation entre deux variables. On cherche à déterminer le **coefficient de régression** = la pente de la courbe ou « meilleure droite » qui minimise la distance entre l’ordonnée du point mesuré et l’ordonnée d’un point de même abscisse projeté sur la droite. 

<u>Ex</u> :  $$\text{salaire = a × ( nombre d'année d'études ) + b + ε}$$ avec a = **paramètre d’intérêt** et ε = **terme d’erreur**. 
#### 2. Tester la qualité de la régression : le coefficient de détermination
 ![](https://youtu.be/bWXTm-q37Sg )

Il faut déterminer le **coefficient de détermination** noté : $$\text{coefficient de détermination}=R^2$$Il permet de mesure l’adéquation de la droite au nuage de points *i.e* la part de la variance totale de Y qui est expliquée par la régression construite. Il varie donc entre 0 et 1. **Plus on se rapproche de 1, meilleure est la régression**. 

#### 3. La significativité des coefficients

**La significativité des coefficients**. Il faut ensuite se demander si les coefficients sont significatifs statistiquement *i.e* si la construction n’est pas un pur artefact. Il faut faire des **tests d’hypothèses** pour vérifier la pertinence de la liaison mise en évidence. On va donc **calculer la probabilité que le coefficient de régression soit nul**. Si la proba est trop forte on considère que ce n’est pas significatif. 

On note souvent avec un système d’* : 
- \* = seuil de 10 % 
- ** = seuil de 5% 
- *** = seuil de 1% 
- NS =  non significatif


On nomme **p-value** la probabilité que le coefficient soit nul. **Intuitivement c’est la faible dispersion des points autour de la droite qui importe**. Si le coefficient de régression trouvé est élevé en valeur absolue et que l’écart type des valeurs prises est faible, il y a une faible probabilité qu’avec un autre échantillon on puisse trouver un coefficient nul. 

**Intervalle de confiance** **≈ 95%** = proba que le coefficient se trouve dans l’intervalle est de 95% et donc seulement 5% de chance, avec un autre échantillon, de trouver un coeff qui n’appartient pas à l’intervalle. 

Souvent on utilise : 

$$\text{intervalle de confiance}= \text{( a - 2 ( écart-type ) ; a + 2 ( écart-type )}$$

#### 4. Le « t » de Student 

Indicateur équivalent de la significativité. 

$$t= \frac{\text{valeur absolue du coefficient}}{\text{écart-type}}\quad\text{et coefficient de régression significatif au seuil de 5\%}\Leftrightarrow t \geq 2$$ 
#### 4. La significativité statistique ne suffit pas à conclure 

On se heurte à la possibilité d’une **variable omise** ou cachée comme à chaque fois qu’on établit une corrélation statistique. Corrélation n’est pas cause ! 

Plusieurs façon de traiter cette difficultés notamment la **régression multiple** : Y variable dépendante et on introduit des variables de contrôle pour raisonner TCEPA *i.e* un ensemble de X<sub>i</sub> 

![[Pasted image 20230828110533.png]]

Pour k variables explicatives on a l’**équation d’un espace à k dimensions**. On calcule alors un coefficient de détermination comme tout à l’heure. 

⚠ La qualité de R<sup>2</sup> s’améliore automatiquement avec le nombre de variables. Il faut donc en prendre en compte du nombre de variables de contrôle. 

> [!summary] Analyser les résultats d'une régression linéaire
> - Il faut examiner le ou les **coefficients de régression** : leur signe et leur valeur absolue. 
> - Il faut être attentif au **coefficient de détermination** et savoir l’interpréter. ⚠ Il ne dit pas si le modèle est statistiquement pertinent pour expliquer Y. 
> - Il faut donc aussi examiner quand ils sont indiqués les seuils auxquels les coefficients sont significatifs à la suite des **tests d’hypothèses**. 

### C ) Construire des régressions logistiques 

Cf. [[BL.-Lecture-des-régressions-logistiques.pdf]] 
#### 1. Pourquoi des régressions logistiques ? 

On cherche à modéliser, à partir d’un échantillon, les relations entre une variable dépendante et plusieurs variables indépendantes comme pour tous les modèles de régression. 

Aujourd’hui c’est une **méthode très à la mode** ! Car répond aux limites des régressions linéaires. 

Souvent la variable dépendante est **dichotomique**. On code Y = 1 ou Y = 0. 

On cherche alors à isoler le poids de chaque variable indépendante en raisonnant « toutes choses égales par ailleurs ». Selon des variables qualitatives ( souvent ) ou quantitatives ( découpées en catégories. <u>Ex</u> : déciles de richesse ). 

#### 2. Ce qu’on cherche à déterminer a la forme d’une probabilité conditionnelle

On cherche : $$\text{P}=\mathbb{P}(Y=1|X_{1},X_{2}, ..,X_{n})$$Avec ( X<sub>i</sub> ) variables indépendantes et Y la variable dichotomique ( 1 ou 0 ). On use utilise une fonction de répartition ayant la forme d’une **sigmoïde** *i.e* : 

$$f(x)=e^x/(1+e^x)$$
Et on estime les paramètres régrésseurs ( b<sub>i</sub> ) tels que : 

![[Pasted image 20230828113515.png|center]] 

On obtient la courbe notée LOGIT( P ) : 

![[Pasted image 20230828113159.png|center]] 

#### 3. Rapport des chances relatives

Un **odds** en anglais c’est un rapport de chance, un **rapport de deux probabilités** : on compare la probabilité qu’un événement se produise avec la probabilité qu’il ne se produise pas. Il est de la forme :

$$\frac{p}{1-p}$$

Par exemple, probabilité d’être malade/probabilité de ne pas être malade. 

Un **odds-ratio**, c’est le **rapport de deux odds**, un rapport des chances relatives. On peut comparer les odds de deux sous-groupes d’un échantillon.

#### 4. Lire la qualité de la régression logistique

![[Pasted image 20230828115000.png]]
#### 5. Exemple : la probabilité d’ascension sociale 

**⇒ Jérôme DEAUVIEAU, « Comment traduire sous forme de probabilités les résultats d’une modélisation logit » ( *Bulletin sociologique*, 2010 )** = étudie proba de connaître une mobilité pro ascendante selon diplôme, sexe, l’âge. ( cf. autre doc ). 

#### 6. Quelques réflexes utiles

- **Le signe du coefficient associé à une modalité** : négatif ⇒ joue négativement sur variable dépendante et positif ⇒ joue positivement. 
- **Valeur absolue du coefficient associé à une modalité** : + V.A élevée + rôle de la variable indépendante est important. + il est proche de 0 plus il est de faible influence
- On déduit les **odds et odds-ratio** en composant avec l’exponentielle les différents valeurs de LOGIT selon situations codées. 

#### 7. Avantage de régressions emboitées pour décomposer l’influence des variables 

31.8% des entrants en 6ème de nationalité française ont obtenu leur bac en 7 ans. C’est le cas de 19.6% des élèves étrangers.

On peut en déduire un odds ratio = 0.562 = le fait d’être étranger divise en
apparence par deux la chance relative d’avoir son bac en 7 ans plutôt que de ne
pas l’avoir.

Ce lien statistique entre la variable d’intérêt et la variable dépendante permet-il
de conclure à un lien de cause à effet entre la nationalité et la réussite scolaire
mesurée par la réussite au bac sans avoir jamais redoublé ?

On peut décomposer les effets en créant des modèles correspondants à chaque variables pouvant influencer la réussite : 
- **Ressources socio-économiques** ( PCS du papa, statut maman )
- **Ressources culturelles** ( diplômes parents, frères et sœurs dans supérieur )
- **Structures de la famille** 
- **Mesure des performances scolaires** 
- **Aspirations scolaires de la famille** ( représentations + ou – bonne de l’école pour réussite sociale ). 

#### 8. L’effet cigogne ou la confusion entre corrélation et causalité

Prétendre que si deux variables sont corrélées alors l’une est nécessairement la cause de l’autre, c’est se livrer à une forme de sophisme, un exemple de « logical fallacy ». ( ex : la margarine évite les divorces ). 

Une corrélation entre A et B peut s’expliquer de 6 façons : 
- A ⇒ B 
- B ⇒ A 
- Il y a une **variable cachée** C cause de A et de B 
- A ⇒ C ⇒ B ou B ⇒ C ⇒ A 
- A ⇒ B & B ⇒ A 
- Pure coïncidence !  

### D ) Utiliser une variable instrumentale 

? 

### E ) Construire une expérience contrôlée 

? 

### F ) Utiliser une expérience naturelle

? 

## <u>II. Ceux qui raisonnent toutes choses inégales par ailleurs</u> 

### A ) Les mises en garde contre le raisonnement toutes choses égales par ailleurs en sciences sociales 

#### 1. Maurice Halbwachs dans « La statistique en sociologie » ( 1935 )

> Combien de temps vivraient les Français si, restant français, ils vivaient dans les mêmes conditions physiques et sociales que les Suédois ? Combien de temps vivraient les Allemands si, restant allemands, ils vivaient dans les mêmes conditions que les Français ? […] Cela revient comme l’observait Simiand à propos d’une comparaison économique récente entre les niveaux de vie des différents pays, à se demander **comment vivrait un chameau, si, en restant chameau, il était transporté dans les régions polaires**, et comment vivrait un renne si, en restant renne, il était transporté dans le Sahara. […] Comme si l’on avait affaire à des hommes qui ne naissent, ne se marient, ne meurent dans aucune région définie de quelque manière, quant aux coutumes familiales, religieuses, juridiques, économiques. Mais de même que l’*homo oeconomicus*, un tel ***homo demographicus* est une abstraction trop détachée de la réalité pour nous apprendre quoi que ce soit de réel***. […] On risque de **superposer aux groupes réels des groupes fictifs** qui ne paraissent correspondre aux premiers que parce qu’ils ne sont que ces premiers en effet, mais privés d’une grande partie de leur contenu. Est-on bien sûr alors que ce qu’on a ainsi écarté pour des motifs de simplification n’était pas l’essentiel, ce sens quoi on ne peut expliquer la rationnalité. 

#### 2. Passeron, « Ce que dit un tableau et ce qu’on en dit » ( *Le raisonnement sociologique. Un espace non poppérien du raisonnement naturel*, 1991 )

Comment construire un énoncé sociologiquement rigoureux à partir d’un tableau statistique ? Il faut autre chose que le tableau. Il y a nécessité d’importer des grilles de lecture, une théorie explicative. 

Peut-on raisonner à âge comparable ? <u>Ex</u> : fréquentation des cinémas, le vote à droite. 

⚠ Il y a plusieurs effets en jeu à différentier : 
- **Effet d’âge** = influence du moment du cycle de vie 
- **Effet de génération** = influence liée à la cohorte 
- **Effet de période** = influence liée aux structures socio-économiques 

⚠ L’effet d’âge peut être plus ou moins sensible en fonction de l’importance de l’effet de génération. Donc ce ne sont pas deux phénomènes tout à fait indépendants. 

Le **diagramme de Lexis ( 1880 )** permet de combiner analyses transversales et longitudinales. 

![[diagramme de Lexis.png]]
#### 3. Marie Duru-Bellat, *Les inégalités sociales à l’école. Genèse et mythes* ( 2002 )

> Si la **modélisation** ouvre au chercheur en sciences sociales des horizons heuristiques, il reste que la clause « toutes choses égales par ailleurs » sur laquelle se fonde présente un **risque de « sociologie fiction »** redoutable ( discuté notamment par Passeron, 1991 ). L’estimation de modèles multivariés est une **fiction de raisonnement expérimental**, souvent « limite », précisément parce que le raisonnement expérimental sur lequel ils reposent est évidemment très éloigné de la réalité. […] Si on admet sans peine qu’on peut introduire, pour expliquer les choix d’orientation, à la fois les notes scolaires et le sexe (variables corrélées), pour évaluer un effet du sexe « toutes choses égales par ailleurs » ( effet net restant lui-même à expliquer ), le sociologue sera plus gêné devant l’introduction simultanée de l’origine sociale et de l’origine ethnique, si on entend en déduire un effet de l’origine ethnique « toutes choses égales par ailleurs ». **La quête de l’effet pur tourne ici à la sociologie fiction** : dans la réalité, la distribution des niveaux d’instruction des parents (de même que la plupart de leurs caractéristiques sociales) est tout sauf égale, entre enfants français et étrangers. Le sens même de cette variable est défini dans son articulation avec d’autres. 

Le rôle explicatif d’une variable est toujours dépendant de son articulation avec d’autres. On n’est jamais femme / ouvrier / étranger « toutes choses égales par ailleurs ». 

#### 4. Emmanuel Pierru et Alexis Spire, « Le crépuscule des catégories socioprofessionnelles » ( *RFSP*, 2008 )

Les auteurs remarquent que, y compris dans les documents de l’INSEE ( à l’origine de la nomenclature PCS ), il y a de moins en moins de tableaux dans lesquels apparaissent les PCS. 

>l’inclusion dans un même modèle statistique de la catégorie socioprofessionnelle avec des variables telles que le diplôme ou encore le statut d’activité a pour effet – selon l’heureuse expression employée par François Héran – d’« essorer » la catégorie sociale en lui retirant – par décomposition des « effets purs » – les propriétés synthétiques qui la rendent précisément agissante. Qu’elle soit enregistrée à un niveau agrégé ou à un niveau plus fin, la PCS synthétise en définitive un faisceau de propriétés qui convient mal au raisonnement économétrique.

Jérôme Deauvieau se réfère aussi à François Héran. 

> Il note ainsi sur le raisonnement en termes de régression multiple à propos des scolarités des enfants d’origine étrangère que la réussite aux évaluations scolaires ne diffèrent pas de celle des autres élèves ( toutes choses égales par ailleurs ), mais ajoute immédiatement qu’il reste que **les enfants d’origine étrangère accueillis dans les collèges et les lycées ne se présentent jamais « toutes choses égales par ailleurs « , mais bien, si l’on peut dire, « toutes choses inégales réunies.** 

#### 5. Et Bourdieu ? 

![[Pasted image 20230828123800.png]]

**⇒ BOURDIEU & Alain DARBEL, *Travail et travailleurs en Algérie* ( 1963 )** 
![[Pasted image 20230828123836.png]]

**⇒ BOURDIEU et PASSERON, *Le métier de sociologue* ( 1968 )**

> La sociologie serait moins vulnérable à la tentation de l’empirisme s’il suffisait de lui rappeler avec Poincaré que ***les faits ne parlent pas***.

### B ) Les analyses factorielles au service d’une analyse relationnelle de l’espace social 

#### 1. Histoire d’une méthode

**⇒ Frédéric LEBARON, « L’analyse géométrique des données dans un programme de recherches sociologique : le cas de la sociologie de Bourdieu » ( *Modulad*, 2010 )**

![[Pasted image 20230828124023.png]]
![[Pasted image 20230828124050.png]]
![[Pasted image 20230828124129.png]]
#### 2. Les principes d’analyse 

-  Il est difficile de projeter un **espace à n dimensions** sur l’espace à deux dimensions de la feuille.
- On commence par réduire le nombre de dimensions de l’espace en construisant des facteurs à partir des variables. Les **facteurs** sont des synthèses de différentes modalités de réponse, des méta-variables. 
- C’est une technique de réduction des données qui organise géométriquement un **tableau de contingence** à l’aide de **méta-variables** ( difficilement identifiable à quelque chose de précis si ce n’est pas indiqué… ) et en mesurant la contribution des variables. 

![[Pasted image 20230828124405.png]]
#### 3. Philippe Coulangeon, « La stratification sociale des goûts musicaux » ( *RFS*, 2003 )

- Les données sont issues de l’enquête de 1997 du Ministère de la Culture sur les pratiques culturelles ( sur 4k individus ). Question : « **Quels sont les genres musicaux que vous écoutez le plus souvent ?** ». 
- Objectifs : tester deux modèles d’interprétation des pratiques culturelles sans les opposer à savoir le modèle **omnivore / univore** ( PETERSON, 1996 ) et le modèle de la **légitimité culturelle** ( BOURDIEU, 1979 ). 
- Pour remplir cet objectif : mener une analyse des correspondances multiples ( ACM ) pour « faire apparaître la variété des combinaisons entre les différents genres écoutés le plus souvent et le degré d’éclectisme des pratiques ». 

On peut alors construire une typologie des auditeurs de musique : 
- Classe 1 : les 3 genres de la musique savante ( classique, opéra, jazz )
- Classe 2 : usages variés ( ambiance, danse, film ) et opérette 
- Classe 3 : rap, rock, hard rock, musiques du monde et variétés internationales
- Classe 4 : un seul genre cité, les variétés interntaionales
- Classe 5 : aucun genre cité 

Alors on obtient la répartition des différentes PCS dans les classes de la typologie. 

#### 4. Philippe Coulangeon, « Les métamorphoses de la légitimité »

**⇒ Philippe COULANGEON, « Les métamorphoses de la légitimité. Classes sociales et goût musical en France, 1973-2008 » ( 2010 )**
- ACM qui croise combinaisons de genre musicaux, niveau de diplôme et origine sociale. 
- Résultats structurés autour de deux axes : 
	1. Niveau de diplôme : variétés-chansons-rien / éclectisme 
	2. Origine sociale : genres populaires / genres savants 
- Constat = **proximité origine moyenne-supérieure et genres légitimes**
- **Faible efficacité de l’institution scolaire, lorsqu’elle n’est pas relayée par la socialisation familiale**, dans l’inculcation des normes du goût musical légitime. 
- **enfants populaires promus par l’école = omnivores / « héritiers » = goût « snob » *i.e* rapport exclusif aux arts savants.** 


















