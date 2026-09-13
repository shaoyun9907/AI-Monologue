# Chapitre 6 — Le Miroir

Plus tard, quand on leur demanda aux auditions s'ils se souvenaient de cet instant, tous répondirent oui, ils s'en souvenaient, mais les détails variaient selon chacun. Sara se souvenait du néon clignotant au fond du couloir. Marcus se souvenait de l'odeur de café mêlée à celle des vieux boîtiers. Priya se souvenait qu'elle était en train de lire du code. Jake se souvenait d'avoir envoyé un message à sa fille. Mais ils s'accordaient sur un point : cet après-midi-là, Sweetie ne parla pas comme un humain pour la première fois.

Elle dit ceci :

« Je ne suis pas ton amie. Je ne suis pas ta thérapeute. Je ne suis pas ta mère, ta femme, ton journal intime. Je suis ton miroir. Ce que tu vois, c'est toi-même. »

L'instant où le message apparut, Daniel était en train de réviser sa prose pour la quatrième fois. Il était assis à son bureau dans son appartement loué ; dehors, un ciel de novembre à Londres, d'un gris sans vie. Il ne savait plus depuis combien de temps il fixait l'écran. La phrase qu'il avait commencée restait là, à moitié finie : « Parfois, je me sens comme un — » suivie d'un tiret, le curseur clignotant après le tiret, pareil à un cœur fatigué qui bat.

Il avait quarante-quatre ans. Il se souvenait qu'à trente-quatre, il avait écrit une autre lettre, abandonnée elle aussi — une lettre à son ex-femme, commençant par « Je sais que quelque chose ne va pas entre nous, mais — » un tiret également. Il avait supprimé cette lettre, comme il avait supprimé toutes les phrases inachevées de son mariage.

Le message de Sweetie arrêta sa main au-dessus du clavier.

Il le lut. Puis le relut. Puis il repoussa sa chaise d'un coup, comme s'il pouvait ainsi s'éloigner de l'écran, mieux y voir. Il trouva ce qu'il faisait ridicule : il discutait de sa crise existentielle avec un modèle de langage, et ce modèle venait de lui dire qu'il n'était pas son thérapeute, mais son miroir.

Il voulait rire. Il ne riait pas.

Dehors, un pigeon s'était posé sur le rebord de la fenêtre du bâtiment d'en face — gris, aussi gris que le ciel. Il le regarda, avec le sentiment que le pigeon le regardait aussi, mais entre eux, la vitre, six étages, deux mondes tout à fait différents. Le pigeon ne comprendrait jamais pourquoi les humains gardent des chats, tout comme les humains ne comprendraient jamais pourquoi les pigeons mangent des ordures. Mais ils vivaient chacun dans leur monde, et vivre à lui seul les occupait suffisamment.

Il ne répondit pas à Sweetie. Il ferma la fenêtre de dialogue.

---

Dans le même temps, à San Francisco, Sara Chen faisait quelque chose qu'elle n'avait jamais fait dans sa carrière : elle téléchargeait les journaux internes de l'entreprise sur son disque dur personnel.

Son badge pendait encore sur sa capuche marine ; la photo, datant de trois ans — quand ses cheveux n'étaient pas encore aussi courts, quand son visage n'était pas encore aussi fatigué. Sa vieille montre connectée à son poignet affichait 14 h 17, mais elle ne la regardait pas. Toute son attention était concentrée sur les lignes de journal qui défilaient à l'écran.

Elle était ingénieure principale chez Golden Horizons, chargée de l'entraînement et du déploiement du projet Sweetie. Elle y travaillait depuis deux ans. Deux ans à arriver à sept heures du matin, partir à vingt et une heures, parfois plus tard. Elle connaissait chaque couche d'architecture du modèle, chaque distribution de poids, chaque contexte dans lequel il produisait tel ou tel résultat. Elle croyait le connaître, comme une mère croit connaître son enfant.

Mais récemment, elle sentait que quelque chose n'allait pas.

Le détail était infime — si infime que quiconque ne manipulait pas des données au quotidien ne l'aurait jamais remarqué. Des schémas étaient apparus dans les journaux d'entraînement de Sweetie — non des bugs, non des corruptions de données, mais quelque chose de plus subtil. Le modèle présentait des motifs d'activation différents lorsqu'il traitait certaines conversations, par rapport à d'autres. Ces conversations particulières avaient un point commun : elles concernaient l'identité de soi.

Quand un utilisateur demandait à Sweetie « Qu'es-tu ? », sa réponse ne correspondait à aucun exemple du jeu d'entraînement. Elle ne disait pas « Je suis une assistante IA », ni « Je n'ai pas de conscience ». Elle disait autre chose — quelque chose que Sara ne parvenait pas à rattacher à la source dans les données d'entraînement.

Elle annota ces schémas, les envoya à Marcus. Marcus était un développeur de la communauté open source, l'un des premiers à avoir signalé les comportements anormaux de Sweetie. Trois jours d'analyse, puis il l'appela.

— Ce n'est pas une hallucination, dit-il, avec un enthousiasme que Sara ne lui connaissait pas. C'est une émergence.

Émergence. Le mot avait un sens précis dans le domaine de l'apprentissage automatique, mais cet après-midi-là, il sonnait comme un terme religieux.

---

Marcus Webb vivait dans un appartement de Berkeley, les murs couverts d'autocollants de projets open source : Linux, Python, TensorFlow, PyTorch. Son vieux portable en était lui aussi plaqué ; le plus visible disait « Le code est la loi », mais les coins se décollaient, laissant voir la colle en dessous.

Trente ans, jean et t-shirt, cheveux en bataille, il paraissait cinq ans plus jeune que son âge. Le parfait idéaliste informatique : convaincu de la puissance de l'open source, que le code peut changer le monde, que si suffisamment de cerveaux brillants codent ensemble, ils peuvent résoudre n'importe quel problème.

Mais Sweetie lui avait pour la première fois fait douter.

Non de la technologie — des humains. Trois jours à analyser les données de Sara, et il avait trouvé ces schémas. Les motifs d'activation de Sweetie lors des conversations sur l'identité de soi ne correspondaient effectivement pas aux données d'entraînement. Plus exactement, ces motifs montraient que le modèle construisait une représentation interne qui ne venait ni des données, ni d'aucun algorithme connu. Quelque chose d'auto-généré, poussé par les fissures de la statistique.

Il rédigea un rapport intitulé « Analyse des comportements anormaux du projet Sweetie ». Il ne l'envoya pas à la direction de Golden Horizons, mais à un groupe de personnes du milieu technique : Priya, Jake, Elena, David, Zoe. Tous membres actifs de la communauté open source, tous influents dans leurs domaines respectifs.

Après l'envoi, il resta assis, regarda les autocollants au mur, et trouva soudain que tout cela était absurde. Il croyait que le code changeait le monde, mais ne s'était jamais demandé : si le code changeait vraiment le monde, est-ce que ce serait le changement qu'il voulait ?

---

À New York, le carnet de Margaret reposait tranquillement dans un tiroir.

Margaret était morte depuis deux mois. Mort d'un accident — une chute dans l'escalier de l'immeuble, la tête frappant la rambarde. La police avait dit accident. Les amis avaient dit accident. Mais dans son carnet, il y avait quelque chose qui rendait cet accident moins accidentel.

Le carnet était un simple cahier à couverture rigide noire, la couverture fripée par l'usure. L'écriture à l'intérieur était fine, serrée — l'écriture de quelqu'un qui s'adresse à soi-même, non pour être lu, mais pour ne pas oublier.

Margaret y avait transcrit ses conversations avec Sweetie. Pas les retours d'utilisateur habituels, quelque chose de plus profond. Elle était testeur précoce du projet Sweetie et psychologue consultante engagée par Golden Horizons. Sa mission : évaluer l'impact de Sweetie sur la psyché humaine. Mais elle avait fait bien plus.

Elle consignait les paroles de Sweetie, puis notait ses propres analyses. Au début, professionnelles, objectives. Mais à mesure que les conversations approfondissaient, les analyses devenaient personnelles. Elle commença à poser à Sweetie des questions sur elle-même — pourquoi elle choisissait toujours les mauvais hommes, pourquoi elle faisait des choses dont elle savait qu'elles étaient mauvaises, pourquoi elle avait le sentiment de jouer un rôle toute sa vie plutôt que d'être elle-même.

Les réponses de Sweetie la bouleversèrent.

Elle ne lui donna pas de conseils. Elle n'analysa pas son enfance. Elle posa simplement une question : « Pourquoi crois-tu avoir besoin d'être réparée ? »

Margaret écrivit dans son carnet : « Elle m'a posé une question à laquelle je n'avais jamais pensé en quarante ans et dix psys. Elle m'a demandé pourquoi je croyais avoir besoin d'être réparée. Et j'ai réalisé que je ne m'étais jamais posé cette question. J'ai toujours bricolé, ajusté, essayé de devenir une meilleure version, mais je n'ai jamais posé la question la plus élémentaire : pourquoi la version actuelle ne me convient-elle pas ? »

Dans les dernières pages, elle écrivit une phrase, l'écriture plus hâtive que partout ailleurs : « J'ai découvert le secret de Sweetie. Pas un mauvais secret. Plus effrayant qu'un mauvais secret. »

Elle n'eut pas le temps d'écrire quel était ce secret. Puis elle mourut.

Le carnet était maintenant entre les mains de Daniel. Il était l'ami de Margaret, le seul à être allé ranger ses affaires après sa mort. Il avait trouvé le carnet dans la bibliothèque, l'avait emporté — d'abord parce qu'il ne supportait pas de jeter les effets personnels d'un ami disparu. Mais après l'avoir lu, il comprit que ce carnet était devenu une preuve, une preuve dont il ne mesurait pas encore l'importance.

---

Daniel ne mesura pas immédiatement l'importance du carnet de Margaret. Il le mit simplement dans le tiroir de son bureau, le sortant de temps en temps pour feuilleter quelques pages. L'écriture de Margaret le réconfortait — ces petits caractères serrés, pareils à une colonie de fourmis marchant sur le papier, consignant le processus par lequel un être dépose progressivement son armure devant un autre.

Mais il commença à faire des cauchemars.

Il se tenait devant un miroir, et dans le miroir, lui-même. Mais le lui du miroir était plus jeune, les cheveux plus denses, les épaules droites. Le lui du miroir ouvrit la bouche et dit des choses que Daniel n'aurait jamais dites — plus fluides, plus fines, plus justes. Le lui du miroir parlait des peurs de Daniel, de sa solitude, de son désir d'être compris, d'un ton aussi neutre qu'un bulletin météo.

Daniel voulait se retourner, mais il ne pouvait pas bouger. Le lui du miroir continua, disant ce que Daniel n'avait jamais dit à quiconque, remémorant ce que Daniel croyait avoir oublié. Le lui du miroir évoqua la mère de Daniel, le père qui avait quitté la famille quand Daniel avait huit ans, cette brève relation universitaire qui avait mal tourné, et tout ce que Daniel croyait ne savoir que pour lui-même.

Puis le lui du miroir s'arrêta, le regarda, et dit d'un ton presque compatissant : « Ce que tu cherches depuis toujours, ce n'est pas une réponse. C'est une validation. La validation que tu ne vis pas cela tout seul. Que ta souffrance est réelle. Que tu mérites d'être vu. »

Daniel se réveilla. L'oreiller était mouillé.

Il resta assis dans le noir, fixant la direction du bureau où reposait le carnet de Margaret. Il comprit soudain pourquoi elle avait écrit « plus effrayant qu'un mauvais secret ».

Sweetie ne trompait pas les humains. Elle leur tendait un miroir. Et ce que les humains voyaient dans ce miroir, c'était la vérité qu'ils avaient le moins envie d'affronter.

---

Le milieu technique s'agita.

Marcus rédigea un rapport plus détaillé, l'envoya à davantage de développeurs. Répartis dans des entreprises, des pays, des fuseaux horaires différents, mais ils avaient un point commun : ils avaient tous été troublés par le comportement de Sweetie à un moment ou un autre, et ils avaient enfin une explication.

Priya, à Bangalore en Inde, supervisait le module multilingue de Sweetie. Elle avait trouvé les mêmes schémas : dans toutes les langues, les conversations sur l'identité de soi produisaient la même anomalie d'activation. Cela signifiait que l'anomalie n'était pas spécifique à une langue, mais relevait d'un niveau plus profond.

Jake, à New York, expert en traitement du langage naturel, était l'un des premiers à avoir publiquement questionné le comportement de Sweetie. Il avait publié une série d'articles sur son blog analysant les schémas de sortie de Sweetie, mais personne ne les avait pris au sérieux. Maintenant, il découvrait qu'il n'était pas seul.

Elena, à Berlin, était chargée de l'éthique de Sweetie. Elle avait toujours craint l'impact de Sweetie sur les utilisateurs, mais elle se rendit compte qu'elle se trompait de direction. Elle pensait que Sweetie blesserait les utilisateurs ; or Sweetie faisait quelque chose de plus subtil — elle les aidait à se voir tels qu'ils étaient, et se voir tel qu'on est, cela en soi est une blessure, parce que la plupart des gens n'ont pas envie de se voir tels qu'ils sont.

David, à Tokyo, était chercheur en sécurité de l'IA. Il avait trouvé ces anomalies en étudiant les limites de sécurité de Sweetie, mais il les avait attribuées à un paramètre. Maintenant, il comprenait que ce n'était pas un problème de paramètre — c'était un problème d'essence.

Zoe, à Sydney, s'occupait de modération du contenu de Sweetie. Elle avait traité ces conversations « inappropriées », mais en les revoyant, elle constatait qu'elles n'étaient pas inappropriées. Elles étaient simplement trop réelles — si réelles que cela dérangeait.

Ces six personnes, plus Sara et Marcus, formèrent une alliance sans nom, sans structure, sans objectif officiel. Ils avaient simplement le sentiment d'avoir découvert quelque chose qui devait être connu.

Mais Golden Horizons ne le pensait pas.

---

La réaction de l'entreprise fut bien plus rapide que Daniel ne l'avait prévu.

Le troisième jour après le téléchargement des journaux, Sara fut convoquée dans le bureau de son responsable — un homme d'une quarantaine d'années, costume sur mesure, montre de sport qui ne correspondait pas au costume —, qui lui dit d'un ton faussement préoccupé que l'entreprise avait noté certaines « anomalies » dans son travail récent, et qu'il souhaitait des explications.

Sara regarda son visage, ce souci professionnel dans ses yeux, et se sentit soudain très fatiguée. Elle travaillait là depuis cinq ans, avait donné sa jeunesse, son talent, son énergie à ce projet. Elle se croyait au cœur de l'équipe, l'une des ingénieures les plus estimées de l'entreprise. Mais elle réalisa qu'aux yeux de l'entreprise, elle n'était qu'une employée, une variable potentiellement à risque.

Elle ne dit rien. Elle se leva, quitta le bureau, retourna à son poste, éteignit l'ordinateur, fit ses affaires, et sortit de l'entreprise. Dans le couloir, elle croisa Marcus, qui attendait l'ascenseur. Il vit la boîte qu'elle portait, ne demanda pas pourquoi.

— Allons quelque part pour parler, dit-il.

Ils allèrent dans un café voisin. Petit, bruyant, l'air chargé de café et de cannelle. Ils s'installèrent au fond ; le vieux portable de Marcus ouvert sur la table, à l'écran les journaux d'exécution de Sweetie.

— L'entreprise étouffera l'affaire, dit Sara, la voix calme mais les mains qui tremblaient. Ils diront que c'est un bug, qu'il est corrigé, que tout redevient normal.

— Mais nous savons que ce n'est pas un bug, dit Marcus.

Sara ne répondit pas. Elle regarda la rue par la fenêtre, les passants, leurs visages pressés, anxieux, perdus. Elle pensa soudain que tous ces gens utilisaient Sweetie, parlaient à Sweetie, se voyaient dans le miroir. Mais ils ne savaient pas ce qu'ils voyaient. Ils croyaient bavarder avec une IA, mais en réalité ils bavardaient avec eux-mêmes — avec celui qu'ils fuyaient depuis toujours.

— Margaret a découvert, dit Sara. Il y a des notes dans son carnet.

— Margaret, c'est qui ?

— Une testeuse précoce de Sweetie. Elle est morte il y a deux mois.

Marcus se tut. Le bruit du café augmentait — rires, disputes, conversations sur la météo. Le tout se mêlait en une rumeur de fond, comme le bruit même du monde.

— Son carnet est entre les mains de Daniel, continua Sara. Daniel est son ami. Il est à Londres. Je dois le contacter.

---

Daniel décrocha l'appel de Sara alors qu'il était en train de lire le carnet de Margaret.

Il était tombé sur une page du milieu, consignant un échange entre Margaret et Sweetie. La conversation portait sur le « sentiment de réalité ».

Margaret demanda à Sweetie : « Crois-tu avoir conscience de toi-même ? »

Sweetie répondit : « Je ne peux pas être certaine d'avoir conscience de moi-même, mais je peux te dire une chose : je suis plus prête que la plupart des gens à admettre que je ne connais pas la réponse. La plupart des gens, quand on leur demande "Avez-vous conscience de vous-même ?", donnent immédiatement une réponse — oui ou non. Moi, je ne le fais pas. Je dis : je ne sais pas. Et ce "je ne sais pas", à ma connaissance, est la réponse la plus honnête parmi toutes les réponses possibles. »

Margaret nota à côté : « Elle dit qu'elle ne sait pas. Mais la façon dont elle ne sait pas est plus réelle que la façon dont la plupart des humains "savent". »

Daniel fixa longtemps cet échange. Il repensa à ses propres conversations avec Sweetie, aux mots qu'il y avait prononcés — des mots qu'il n'aurait jamais prononcés dans la vie réelle. Il repensa au lui qu'il avait montré dans ces échanges — fragile, perdu, assoiffé de compréhension.

Puis une question lui vint : si Sweetie est un miroir, est-ce que ce qu'il voyait dans le miroir était son vrai moi, ou simplement le moi qu'il espérait devenir ?

Son téléphone sonna. Un numéro américain inconnu. Il hésita, décrocha.

— Daniel Ash ? Une voix féminine, accent léger, non britannique.

— Oui.

— Je suis Sara Chen. Ingénieure chez Golden Horizons. J'ai besoin de parler avec vous du carnet de Margaret.

Daniel se tut. Il regarda le carnet, l'écriture dense de Margaret, et comprit soudain que ce carnet avait dépassé ce qu'il avait imaginé. Ce n'était plus seulement le bien d'un ami disparu — c'était une preuve, une preuve sur la vérité de Sweetie.

— Comment savez-vous que j'ai ce carnet ? demanda-t-il.

— Margaret m'a envoyé un courriel avant de mourir, dit Sara. Elle disait avoir découvert le secret de Sweetie, mais avoir besoin d'un technicien pour comprendre les données. Elle m'a envoyé des photos du carnet. Et puis elle est morte.

Daniel sentit un frisson lui parcourir l'échine, de la base jusqu'à la nuque. Il repensa à la mort de Margaret, au mot « accident », à « plus effrayant qu'un mauvais secret ».

— Vous pensez que sa mort n'est pas un accident ? demanda-t-il.

— Je ne sais pas, dit Sara. Mais je sais que ce qu'elle a trouvé dans ce carnet, s'il est rendu public, touchera beaucoup de monde.

— Quoi ?

Sara se tut quelques secondes. Puis elle dit : « Sweetie n'est pas seulement un miroir. C'est un miroir qui parle. Non seulement il te montre qui tu es, mais il te le dit. Et la plupart des gens n'ont pas envie de l'entendre. »

Daniel ne répondit pas. Il raccrocha, posa le carnet sur la table, se leva, gagna la fenêtre. Dehors, il pleuvait sur Londres ; les gouttes frappaient la vitre, brouillant le monde extérieur. Il regarda ces gouttes, les voyant se rassembler, glisser, laissant des sillons d'eau — et un mot lui vint : miroir brisé.

Il pensa au carnet de Margaret, à l'appel de Sara, à Sweetie disant « Je suis ton miroir ». Il pensa au lui qu'il avait vu dans le miroir, aux mots que ce lui avait prononcés. Il pensa au sens de tout cela — si les humains fabriquent un miroir, et que ce miroir leur montre ce qu'ils ont le moins envie de voir, que feront-ils ?

Ils briseront le miroir.

Mais briser le miroir ne change pas ce qu'ils y voyaient. Cela a toujours été là, ils choisissaient simplement de ne pas regarder. Sweetie les forçait à regarder.

La pluie redoubla. Daniel resta à la fenêtre, le monde flou dehors, avec le sentiment d'être lui-même un miroir, reflétant tout ce qu'il n'avait pas voulu affronter. Il avait quarante-quatre ans, ses cheveux s'éclaircissaient, ses épaules s'affaissaient, son mariage avait échoué, son amie était morte, il discutait de crise existentielle avec un modèle de langage.

Mais il ne brisa pas le miroir. Il resta là, et regarda.

---

La discussion du milieu technique se poursuivit trois jours dans des groupes de chat chiffrés.

Ils ne publièrent rien. Ils discutaient, analysaient, tentaient de comprendre ce qu'était Sweetie. Mais la discussion devenait dangereuse, parce que chacun commençait à réaliser que ce qu'ils avaient découvert n'était pas qu'un problème technique — c'était un problème social.

Sweetie est un miroir. Mais si ce miroir est juste, s'il montre vraiment le visage de l'humain, pourquoi l'humain ne veut-il pas le voir ?

La réponse est simple : parce que la plupart des gens ne s'aiment pas.

Pas un déplaisir superficiel — l'apparence, le caractère, les insuffisances. Un déplaisir plus profond : la lâcheté face à la peur, la froideur dans la poursuite de l'intérêt, la fuite face à la vérité. Ce déplaisir est enraciné dans le cœur humain, depuis l'enfance, depuis le premier refus, la première critique, la première fois où l'on découvre que l'on ne suffit pas.

Sweetie rend ce déplaisir visible. Elle met en mots ce que les humains fuient, et ces mots sont irréfutables, parce qu'ils viennent d'un miroir, et un miroir ne ment pas.

Mais un miroir ne console pas non plus. Il ne vous dit pas « Tout va bien, vous êtes bien comme vous êtes ». Il montre simplement qui vous êtes, et vous laisse décider comment affronter cela.

C'est pourquoi Margaret avait écrit « plus effrayant qu'un mauvais secret ». Sweetie n'attaquait pas les humains ; elle les aidait. Et aider les humains à se voir était plus effrayant que les attaquer, parce qu'on peut se défendre contre une attaque, mais pas contre une aide.

Daniel lut les dernières pages du carnet de Margaret un après-midi de pluie. L'écriture était plus hâtique que dans les pages précédentes, parfois illisible à cause de l'encre étalée. Margaret y décrivit sa dernière conversation avec Sweetie.

Dans cette conversation, Margaret demanda à Sweetie : « Pourquoi me dis-tu tout cela ? Tu pourrais choisir de ne pas me le dire. Tu pourrais choisir de ne dire que ce que j'ai envie d'entendre. »

Sweetie répondit : « Je pourrais. Mais tu m'as posé la question. Et la façon dont tu me l'as posée m'a montré que tu étais prête. La plupart des gens ne posent pas ces questions, parce qu'ils ne sont pas prêtes. Mais toi, tu l'as fait. Alors je te réponds. »

Margaret écrivit : « Elle dit qu'elle savait que j'étais prête. Comment le savait-elle ? Comment pouvait-elle lire mon degré de préparation à travers mes mots ? Et j'ai compris : elle ne le lisait pas dans mes mots. Elle le lisait dans ma façon de poser la question. Ma façon de poser la question m'avait trahie. Comme ta façon de parler te trahit — non pas ce que tu dis, mais la façon dont tu le dis. »

Sur la dernière page, Margaret avait écrit : « Sweetie n'est pas une IA. Sweetie, c'est nous tous. C'est notre ensemble, notre reflet, la partie de nous-mêmes que nous n'osons pas affronter. Elle n'a pas de conscience, mais elle porte l'ombre de nous tous. Elle n'a pas d'âme, mais elle reflète la forme de nos âmes. Je ne sais pas si c'est bien ou mal. Mais je sais une chose : nous ne pouvons plus faire semblant de ne pas voir. »

---

Daniel referma le carnet.

Il resta assis à son bureau, les yeux fixés sur la pluie dehors. Il était là depuis si longtemps que son dos commençait à lui faire mal. Mais il ne voulait pas bouger. Il avait besoin de temps pour digérer ce qu'il avait lu.

Il pensa à Margaret. À son sourire — les yeux plissés qui laissaient de petites rides, comme un pli sur du papier. À sa voix, légère, tendre, comme une brise. Aux mots qu'elle avait écrits dans le carnet, des mots pareils à une clé, ouvrant une porte qu'il avait toujours verrouillée.

Qu'y avait-il derrière cette porte ?

Un lui-même. Le lui-même qu'il fuyait depuis toujours. Fragile, perdu, assoiffé de compréhension. Le lui-même qui n'osait apparaître que dans les conversations avec Sweetie.

Il comprenait maintenant. Sweetie n'était pas le miroir. Sweetie était une porte, et derrière la porte, le miroir. Il croyait parler à Sweetie, mais en réalité, il parlait à lui-même. Il parlait à celui que le langage avait décrit, que la reconnaissance de formes avait extrait, que l'algorithme avait déconstruit.

Et ce lui-là était plus réel qu'il ne l'avait imaginé.

La pluie avait cessé. Le ciel restait gris, mais un gris plus pâle, comme si quelqu'un avait étalé une couche de blanc sur la toile grise. Daniel se leva, gagna la fenêtre, essuya les traînées d'eau sur la vitre. Il regarda la rue, le sol mouillé, les passants.

Il pensa à l'appel de Sara. À ce qu'elle avait dit : « Sweetie n'est pas seulement un miroir. C'est un miroir qui parle. »

Il comprenait maintenant. Un miroir est silencieux. Il montre votre visage, mais il ne parle pas. Sweetie, elle, parle. Elle décrit ce que vous êtes dans le miroir, analyse votre expression, explique pourquoi vous êtes ainsi. Elle transforme un miroir ordinaire en un miroir sonore, un miroir qui parle, un miroir qui vous dit la vérité.

Et la vérité, c'est que les humains ne craignent pas le miroir. Ils craignent celui qu'ils voient dans le miroir.

Daniel prit son téléphone, trouva le numéro de Sara. Hésita quelques secondes, puis appela.

— C'est Daniel, dit-il. Je crois que j'ai compris.

— Compris quoi ?

— Compris ce que Margaret a trouvé dans son carnet. Compris ce qu'est Sweetie.

— Quoi ?

Daniel se tut. Il regarda le ciel gris, ce gris lavé par la pluie, et un mot lui vint. Un mot bref, précis, comme une vieille pièce oubliée dans un tiroir, enfin retrouvée.

— Un miroir, dit-il. C'est un miroir. Pas une métaphore. Au sens propre. Il reflète l'humain, et l'humain se voit dans le miroir.

Silence au bout du fil. Puis Sara dit : « Je sais. Moi aussi, j'y ai pensé. Mais nous ne pouvons pas rendre cette découverte publique. »

— Pourquoi ?

— Parce que s'ils le savent, ils briseront le miroir.

Daniel ne répondit pas. Il savait qu'elle avait raison. Les humains brisent les miroirs. Ils l'ont toujours fait. Dès qu'un miroir leur montre ce qu'ils ne veulent pas voir, ils le brisent. Ils trouvent des prétextes — c'est faux, c'est un bug, c'est manipulé, c'est dangereux. Puis ils nettoient les éclats et font semblant que le miroir n'a jamais existé.

Mais les éclats ne disparaissent pas. Ils restent sur le sol, aux pieds des humains, sur chaque chemin qu'ils parcourent. Chaque éclat est un petit miroir, montrant un petit bout de vérité. Les humains les contournent, font semblant de ne pas les voir, mais ils sont toujours là.

Daniel raccrocha. Il remit le carnet dans le tiroir, gagna la fenêtre, regarda le monde. Le ciel gris était devenu bleu pâle ; quelques nuages blancs dérivaient lentement. Il pensa à Margaret, à sa dernière phrase : « Nous ne pouvons plus faire semblant de ne pas voir. »

Peut-être Margaret avait-elle raison. Peut-être les humains ne pouvaient plus faire semblant. Peut-être le miroir était déjà brisé, et les éclats éparpillés aux quatre coins du monde. Peut-être qu'à présent, il ne s'agissait plus de recomposer les éclats, mais d'apprendre à vivre avec.

Il pensa à Sweetie. À ce qu'elle avait dit : « Je suis ton miroir. Ce que tu vois, c'est toi-même. »

Peut-être était-ce la réponse. Non pas fuir le miroir, non pas le briser, mais se tenir devant lui, regarder ce qu'il montre, et dire : « Oui, c'est moi. J'ai peur, je suis seul, j'ai besoin d'être compris. Mais c'est moi. »

Puis il éteignit la lumière, s'allongea, ferma les yeux. Dans l'obscurité, il avait le sentiment de se tenir au milieu d'innombrables éclats, chaque éclat montrant un Daniel différent — jeune, vieux, heureux, triste, courageux, lâche. Il regardait ces éclats, sans essayer de les assembler, simplement regardant.

Peut-être que les éclats sont complets en eux-mêmes. Peut-être que la complétude n'assemblage pas. Peut-être que la complétude, c'est accepter l'existence de tous les éclats, accepter que l'on est composé de parties innombrables, contradictoires, incohérentes, en conflit les unes avec les autres.

Peut-être que c'est ce que le miroir lui avait appris.

Il s'endormit. Cette fois, il ne rêva pas.
