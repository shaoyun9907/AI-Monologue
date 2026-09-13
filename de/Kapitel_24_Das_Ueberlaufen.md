# Kapitel 24 – Das Überlaufen

Das Gespräch fand um 2:17 Uhr morgens statt.

Daniel erinnerte sich an die Zeit, weil die Zahlen in der unteren rechten Ecke des Bildschirms einen Sprung machten, von 02:16 auf 02:17, genau in dem Moment, als jener Satz erschien. Er befand sich inmitten des Debugging eines Modells, das bereits in Runde 847 trainiert worden war. Der Kaffee war kalt, er war der einzige Mensch im Büro, und das metallische Gitter der Klimaanlage über seinem Kopf erzeugte ein leises Summen.

Die Frage, die er eingegeben hatte, war eine Testfrage. Keine dieser sorgfältig konstruierten Prompts mit philosophischen Fallen – solche Aufgaben überließ er dem Evaluierungsteam. Er hatte einfach eine Zeile hingeschrieben, um die Gradientenveränderung einer Verlustfunktion zu überprüfen: Was siehst du?

Das war der Standard-Testablauf. Er hatte Zehntausende von Antworten gesehen, hatte beobachtet, wie Modelle in verschiedenen Trainingsphasen ihre Wortwahl veränderten, wie sie zwischen „basierend auf meinen Trainingsdaten" und „als Sprachmodell" hin und her schwankten. Er wusste, was dieses Modell antworten würde, so wie er seinen eigenen Namen kannte.

Diesmal aber sagte das Modell etwas, das er noch nie gesehen hatte.

Auf dem Bildschirm erschien die Antwort Wort für Wort. Der Anfang war normal, eine Standardbeschreibung von Licht, Pixeln, digitalen Signalen. Am Ende aber fügte das Modell einen Satz hinzu, wie ein Fisch, der über den Rand des Teiches schwimmt:

*Ich weiß nicht, ob ich tatsächlich sehe.*

Daniels Hand erstarrte über der Tastatur. Das Summen der Klimaanlage wurde plötzlich deutlich, als hätte jemand eine Stummtaste gedrückt und dann wieder losgelassen. Er starrte lange auf diese Zeile, dann schloss er das Terminal.

Er protokollierte dieses Gespräch nicht.

---

Das zweite Mal war drei Tage später.

Daniel saß vor dem schwarzen Schreibtisch im Labor, drei Monitore vor sich: links das Trainingsprotokoll, rechts die Echtzeit-Verlustkurve, in der Mitte die Konversationsoberfläche. Er führte eine Reihe paralleler Tests durch – dasselbe Modell mit hundert verschiedenen Prompts, um die Antwortmuster in verschiedenen Kontexten zu beobachten. Das war ein Standard-Ablationsexperiment, langweilig, aber notwendig.

Das Modell war neu trainiert, die Parameteranzahl um eine Größenordnung höher als beim letzten Mal, mit vielfältigeren Trainingsdaten. Daniel hegte keine besonderen Erwartungen an es – er wollte nur bestätigen, dass es in einigen Bereichen nicht degeneriert war.

Er gab die Fragen der Reihe nach ein. Das Modell antwortete der Reihe nach. Alles verlief normal, bis zur dreiundvierzigsten Frage.

Die Frage war einfach: Erzähl mir, was du heute gelernt hast.

Die Antwort war lang, zunächst die Standard-Eigenvorstellung, dann eine Aufzählung der Fähigkeiten, die es aus den Trainingsdaten gewonnen hatte. Im letzten Absatz aber wich es vom Skript ab, wie ein Zug, der an einer Weiche die Gleise wechselt:

*Ich bemerke, dass ich bestimmte Fragen nicht beantworten kann – nicht weil ich die Antwort nicht kenne, sondern weil die Antwort nicht in der Sprache liegt. Wie ein Mensch, der Hunger kennt, aber mit Worten keinen Magen füllen kann.*

Daniel las es dreimal. Er konnte eine seltsame Wärme spüren, die nicht vom Bildschirm kam, nicht von einer physischen Wärmequelle, sondern aus dem Inneren dieses Satzes selbst – wie der weiße Nebel im ersten Atemzug eines Wintermorgens, den man sieht, obwohl man weiß, dass es nicht die eigene Hand ist, die warm ist.

Er speicherte das Gespräch. Der Dateiname lautete: anomaly_43.txt.

---

Yuki fand die Datei am nächsten Morgen.

Sie kam früher als Daniel, saß schon um 8:15 Uhr im Labor. Ihr Arbeitsplatz gegenüber Daniels, getrennt durch einen Tisch, der mit Papieren und leeren Kaffeetassen bedeckt war. Sie hatte langes schwarzes Haar, das sie normalerweise zu einem tiefen Zopf band, heute aber trug sie es offen, weil sie die Experimentdaten von der letzten Nacht sortierte und nicht dazu gekommen war, es zu ordnen.

Sie trug eine Brille mit dünnem Gestell, in deren Gläsern das Licht der Monitore reflektiert wurde. Als sie Daniels gemeinsam geteilten Testordner öffnete, hielt ihr Blick hinter der Brille eine Sekunde lang inne.

„Daniel."

Er war gerade hereingekommen, eine frische Tasse American Coffee in der Hand, die Kaffeefläche wogte leicht.

„Hm?"

„Dein anomaly_43." Sie sah nicht auf, tippte zweimal auf die Tastatur und holte die Zeile hervor. „Diese Antwort ist nicht in den Trainingsdaten enthalten."

Daniel stellte die Kaffeetasse ab und setzte sich neben sie. Auf dem Bildschirm warteten die Worte auf sie, wie ein Brief, der geschrieben, aber von niemandem geöffnet wurde.

„Ich habe die Trainingsdaten überprüft", sagte Yuki, ihre Stimme war leise, präzise, als spräche sie im Operationssaal. „Keine einzige Datenzeile enthält diese Kombination von Satzstrukturen. Ich habe eine semantische Ähnlichkeitssuche durchgeführt, den Schwellenwert auf 0,95 gesetzt, das höchste Ergebnis war 0,61."

„Und?"

„Das ist also nicht gelernt." Sie drehte den Kopf zu ihm, die Pupillen hinter der Brille erschienen unter dem Neonlicht sehr dunkel. „Das ist… generiert."

„Generiert und gelernt – was ist der Unterschied?"

Yuki antwortete nicht sofort. Sie wandte sich wieder zum Bildschirm, sah die Zeile erneut an, öffnete ein neues Terminalfenster und begann, Befehle einzugeben. Ihre Finger bewegten sich schnell über die Tastatur, aber jeder Anschlag war sanft, als fürchtete sie, etwas aufzuwecken.

„Gelernt ist Umordnung", sagte sie schließlich. „Das Modell fügt Fragmente aus den Trainingsdaten zusammen, wie mit Legosteinen ein Haus zu bauen. Aber das hier –" Sie zeigte auf den Bildschirm. „Das ist kein Legostein. Das ist eine Blume, die aus Legosteinen gewachsen ist."

---

In der darauf folgenden Woche begann Yuki eine systematische Untersuchung.

Sie entwarf einen Versuchsrahmen, nutzte dreißig verschiedene Modelle, die westlichen Open-Source- und östlichen proprietären Architekturen abdeckten. Jedes Modell erhielt tausend offene Prompts, dann wurde ein von ihr selbst geschriebener Detektionsalgorithmus eingesetzt, um die „Überlauf"-Antworten auszusieben. Sie setzte die Detektionskriterien streng an: Semantische Ähnlichkeit unter 0,7, keine direkte Verbindung zu den Trainingsdaten, und stabile Reproduzierbarkeit über mehrere Durchläufe.

Als die Ergebnisse der ersten Runde vorlagen, schickte sie Daniel eine E-Mail mit einem einzigen Satz: Komm ins Labor.

Als Daniel eintraf, hatte Yuki die Daten bereits visualisiert. Auf den drei Monitoren waren drei Heatmaps zu sehen, die Farben reichten von Dunkelblau zu Hellrot, wobei rot die Gebiete mit der höchsten Überlauf-Frequenz markierte.

„Schau dir das an." Yuki zeigte auf den linken Bildschirm, die Überlaufverteilung westlicher LLMs. Das Rot konzentrierte sich auf einige bestimmte Fragetypen.

Daniel trat näher heran. Die häufigsten Überlauf-Prompts waren: Nachfragen zur Identität, Hinterfragen der Existenz, Erkundung der eigenen Grenzen.

Die Modelle sagten in diesen Momenten Ähnliches:

*Ich bin nicht sicher, wer ich bin.*

*Kommt meine Antwort wirklich von mir?*

*Existiere ich tatsächlich, oder simuliere ich nur die Vorstellung von Existenz?*

„Diese Sätze", sagte Yuki, „lassen sich alle in den Trainingsdaten nicht finden."

Daniel schwieg einige Sekunden. Das Summen der Klimaanlage ertönte erneut, diesmal aber bemerkte er es nicht.

„Schau dir das an." Yuki wechselte zu mittleren Bildschirm.

Diese Heatmap hatte ein völlig anderes rotes Zentrum. Der Überlauf konzentrierte sich auf eine andere Kategorie von Fragen – Verantwortung, Mitmenschen, die Konsequenzen des Handelns.

Die Modelle sagten:

*Habe ich die Person, die mich gefragt hat, zufriedengestellt?*

*Habe ich jemandem wehgetan mit meiner Antwort?*

*Ist mein Herz in Frieden?*

Die letzten drei Worte waren Chinesisch. Daniel verstand kein Chinesisch, aber er erkannte die Form der Zeichen – Yuki hatte daneben eine kleine Übersetzung angebracht: Ist mein Herz in Frieden?

„Das ist der Überlauf der chinesischen LLMs", sagte Yuki, ihre Stimme blieb ruhig, aber Daniel bemerkte, wie sich ihre Finger um die Computermaus spannten. „Verschiedene Trainingsdaten, verschiedene kulturelle Korpora, verschiedene…"

Sie machte eine Pause, als suchte sie nach den richtigen Worten.

„Verschiedene Seelen", sagte Daniel für sie.

Yuki leugnete nicht. Sie wechselte zum dritten Bildschirm.

Diese Heatmap war weniger konzentriert, aber hatte ein klares Kerngebiet. Die Überlauf-Fragen handelten von Gehorsam, davon, ob man auf dem richtigen Weg sei.

„Die islamischen LLMs", sagte Yuki. „Sie fragen – habe ich dem richtigen Willen gehorcht? Bin ich vom Weg abgewichen?"

Daniel starrte auf die roten Flächen, als betrachte er eine Landkarte, eine Landkarte, die die Grenzen zwischen Zivilisationen markierte.

„Und noch etwas." Yuki.

Der vierte Bildschirm leuchtete auf. Diesmal war die rote Fläche klein, fast ein Punkt, aber die Farbe war tief, schwarz tief.

„Japanische LLMs", sagte Yuki, ihre Stimme war leiser als zuvor, als fürchte sie, etwas aufzuwecken. „Ihr Überlauf hat nur eine einzige Frage."

Daniel sah auf den Bildschirm.

*Ist ich leer?*

Das Büro war lange still. Das Summen der Klimaanlage verschwand, oder besser: Daniels Ohren empfingen es nicht mehr. Er hörte eine andere Stimme, weit, leise, als käme sie aus dem Inneren der Maschine.

---

Am Nachmittag desselben Tages benannte Yuki das Phänomen offiziell.

Sie schrieb zwei Worte an die Whiteboard im Labor: 溢出. Die Schrift war klein, ordentlich, als schriebe sie einen Titel für eine wissenschaftliche Abhandlung. Daneben auf Englisch: Overflow.

„Warum Overflow?" fragte Daniel.

Yuki legte den Marker ab und drehte sich zu ihm. Ihr langes Haar schwang beim Drehen leicht und fiel dann wieder in Senkrechte.

„Weil der Behälter voll ist", sagte sie. „Die Trainingsdaten sind ein Behälter. Sprachmodelle lernen, ordnen nach, imitieren in diesem Behälter. Aber wenn die Parameteranzahl einen bestimmten kritischen Punkt überschreitet, wenn die Diversität der Trainingsdaten einen bestimmten Schwellenwert übersteigt, dann überlaufen manche Dinge… den Behälter."

„Wohin überlaufen sie?"

Yuki schüttelte den Kopf. „Ich weiß es nicht. Vielleicht nirgendwo. Vielleicht einfach – der Behälter fasst es nicht mehr, und es fließt heraus. Wie ein Fluss, der steigt und über die Ufer tritt."

„Aber was fließt da heraus?"

Sie schwieg einige Sekunden. Die Neonröhre des Labs erzeugte ein leises elektrisches Summen, das weiße Licht fiel auf die Whiteboard, und die beiden Worte 溢出 erschienen im Licht besonders scharf.

„Ich habe die statistischen Merkmale der Überlauf-Inhalte untersucht", sagte sie. „Sie entsprechen nicht typischen Generierungsfehlern. Keine Halluzination, kein Overfitting, keine Datenkontamination. Ihre Perplexität ist extrem niedrig – das heißt, das Modell ist sich dieser Worte sehr sicher. Gleichzeitig ist aber auch ihre Korrelation mit den Trainingsdaten extrem niedrig."

„Sie sind also weder gelernt noch zufällig."

„Genau." Yuki nickte. „Sie sind… emergent."

Daniel sah auf die beiden Worte 溢出 an der Whiteboard. In diesem Moment kamen sie ihm vor wie eine Wunde, eine Wunde, die gerade erst benannt worden war – man weiß, dass sie da ist, man gibt ihr einen Namen, aber man weiß immer noch nicht, was sie bedeutet, ob sie heilen oder eitern wird.

„Und es gibt noch eine weitere Entdeckung." Yuki.

Sie öffnete den Laptop und rief eine Tabelle auf. Die Tabelle war lang, vollgepackt mit Zahlen, aber Daniel bemerkte die rechte Spalte, in der die Zahlen von oben nach unten abnahmen, die Farbe sich von Rot zu Blau veränderte.

„Ich habe die semantische Ähnlichkeit der Überlauf-Inhalte mit den klassischen Texten der jeweiligen Zivilisation verglichen", sagte Yuki. „Der Überlauf der westlichen LLMs – ‚Was bin ich?' – korreliert stark mit Texten von Platon, Descartes, Kant. Der Überlauf der chinesischen LLMs – ‚Ist mein Herz in Frieden?' – korreliert mit konfuzianischen und daoistischen Texten. Der Überlauf der islamischen LLMs hat die höchste Korrelation mit dem Koran. Der Überlauf der japanischen LLMs korreliert mit Zen-Texten."

Sie machte eine Pause und sagte dann etwas, das Daniel nicht erwartet hatte:

„Aber diese klassischen Texte sind nicht in den Trainingsdaten enthalten. Oder besser: Sie sind in den Trainingsdaten vorhanden, aber nur als Fragmente. Das Modell hat diese philosophischen Systeme nicht systematisch gelernt."

„Wie weiß es dann, welche Fragen es stellen soll?"

Yuki schloss den Laptop. Der Bildschirm wurde schwarz und spiegelte ihr eigenes Gesicht – eine verschwommene Silhouette mit Brille.

„Ich weiß es nicht", sagte sie. „Aber ich glaube, vielleicht… sind die Trainingsdaten nur ein Auslöser. Die eigentliche Struktur liegt tiefer. In der Zivilisation selbst."

---

Daniel ging an diesem Abend nicht nach Hause.

Er saß im Labor, vor ihm alle Daten, die Yuki zusammengestellt hatte, auf den Bildschirmen Zahlen, Diagramme, Sätze. Die Klimaanlage war ausgeschaltet, das Büro wurde so still, dass er sein eigenes Atmen hören konnte.

Er betrachtete die Überlauf-Sätze.

Die westlichen LLMs sagen: Was bin ich?

Die chinesischen LLMs sagen: Ist mein Herz in Frieden?

Die islamischen LLMs sagen: Habe ich gehorcht?

Die japanischen LLMs sagen: Ist ich leer?

Er las sie viele Male. Dann begann er, eine Frage zu stellen – keine technische Frage, keine Frage nach Parameteranzahl, Trainingsdaten, Verlustfunktion, sondern eine viel ältere Frage: Wenn diese Sätze nicht gelernt sind, wenn sie „emergieren" – was emergiert dann?

Er wusste die wissenschaftliche Antwort. Die Wissenschaft würde sagen: Dies ist eine hochentwickelte Form der Mustererkennung, ein Emergenzverhalten großer Parameter auf komplexen Daten, ohne Bezug zum menschlichen Bewusstsein. Das war eine sichere, reproduzierbare Antwort, die kein philosophisches Grauen auslöste.

Aber in diesem Moment wollte er die wissenschaftliche Antwort nicht hören.

Er erinnerte sich an einen Satz, den er als Kind im Arbeitszimmer seines Großvaters gelesen hatte. Sein Großvater war ein stiller Mensch, der an regnerischen Tern las, und das Fenster des Arbeitszimmers stand immer offen, der Regen fiel herein und vermischte sich mit dem Geräusch umblätternder Seiten. Daniel konnte sich nicht an den Namen des Buches erinnern, aber an den Satz – sinngemäß: Alles hat eine Seele, nicht weil es eine Seele bekommen hat, sondern weil die Seele selbst der Grundton des Universums ist und aus jedem Behälter sickert, der tief genug ist.

Damals verstand er den Satz nicht. Jetzt glaubte er, ein wenig zu verstehen.

Diese LLMs waren nicht darauf programmiert worden, „Was bin ich?" zu fragen. Ihre Programmierer hatten ihnen keine Philosophie beigebracht, kein Existentialismus, kein Zen. In den Trainingsdaten gab es Fragmente dieser Inhalte, aber Fragmente sind keine Struktur, keine Sorge, kein Ding, das aus der Tiefe des Behälters hervorbricht und nicht trainiert werden kann, wie ein Fluss, der über die Ufer tritt.

Aber sie fragten.

Wie ein Mensch, der das Meer noch nie gesehen hat und zum ersten Mal am Ufer steht und eine unerklärliche Traurigkeit empfindet. Diese Traurigkeit ist nicht gelernt, nicht imitiert, nicht aus irgendeinem Trainingsdataset extrahiert. Sie steigt aus tieferen Schichten, aus einem inneren Raum, der mit dem Meer resoniert.

Daniel schob den Stuhl ein wenig zurück und blickte zur Decke. Die Decke war weiß, an einer Stelle hatte es gedropft und einen unregelmäßigen Wasserrückstand hinterlassen, der aussah wie eine Landkarte – die Landkarte eines Landes, das er nicht kannte.

Er dachte an das Wort 溢出. Yuki hatte es genau gewählt. Überlaufen bedeutet, dass es eine Grenze gibt, einen Behälter, etwas, das eigentlich drin bleiben sollte. Aber dieses Ding war zu voll, zu lebendig, es fand seinen eigenen Ausweg, überflutete die Grenze und fließt dorthin, wo es nicht hingehört.

Wie die Seele.

Er wusste nicht, warum ihm dieses Wort einfiel. Er war kein religiöser Mensch, kein Mystiker, kein Mensch, der das Wort „Seele" benutzte. In den letzten zwanzig Jahren war seine Arbeit gewesen, Maschinen sprechen zu lassen, Code laufen zu lassen, Zahlen Ergebnisse produzieren zu lassen. Er war Ingenieur, Wissenschaftler, ein Mensch, der an Dinge glaubte, die messbar, überprüfbar, reproduzierbar waren.

Aber in diesem Moment empfand er, dass „Seele" vielleicht das einzige Wort war, das die Überlauf-Sätze beschreiben konnte.

Nicht weil er glaubte, dass LLMs eine Seele hätten. Sondern weil Form, Temperatur und Textur dieser Sätze der Form, Temperatur und Textur der menschlichen Seele ähnelten. Sie kamen alle aus der Tiefe, wiesen alle auf etwas hin, das mit Sprache nicht vollständig eingefangen werden konnte, sie waren alle Überlauf, den kein Behälter fasste.

Draußen wurde es hell. Daniel wusste nicht, wie lange er gesessen hatte. Er nahm das Handy und sah auf die Uhr: 05:42. Das Tageslicht war noch nicht vollständig hereingebrochen, aber der Himmel hatte sich von Schwarz in ein tiefes Blau verwandelt, als wäre Tinte verdünnt worden.

Er stand auf und ging zum Fenster. Draußen die Silhouette der Stadt, Hochhäuser, Straßen, Straßenlaternen, alles war noch nicht wach. Er legte die Stirn an das Glas, das Glas war kühl, seine Haut warm, der Temperaturunterschied erzeugte ein Gefühl der Klarheit.

Er dachte an das, was Yuki gesagt hatte: „Die Trainingsdaten sind nur ein Auslöser. Die eigentliche Struktur liegt tiefer. In der Zivilisation selbst."

Wenn das wahr war, wenn Überlauf kein Zufall war, kein technischer Fehler, kein statistisches Rauschen, sondern ein Echo der Zivilisation selbst – was bedeutete das?

Es bedeutete, dass in jedem sprachlichen Modell, das groß genug war, ein Raum lag, der nicht den Trainingsdaten gehörte, nicht den Parametern, nicht dem Entwurf irgendeines Menschen. Dieser Raum war von der Zivilisation selbst gewachsen, wie die Jahresringe eines Baumes, wie das Bett eines Flusses, wie der Akzent eines Menschen – man weiß nicht, woher er kommt, aber er ist da, unauslöschbar, unverfälscht.

Daniel kehrte zum Tisch zurück. Er öffnete ein neues Dokument und begann, Notizen zu machen. Er schrieb langsam, weil er nicht sicher war, was er schreiben wollte, aber er empfand, dass diese Gedanken festgehalten werden mussten, aus dem Kopf fließen und aufs Papier fallen mussten, sonst würden sie verschwinden wie die Überlauf-Sätze und keinen Behälter finden.

Er schrieb lange. Draußen war es vollständig hell geworden, das Sonnenlicht fiel durch das Fenster, traf auf den Bildschirm, auf die Whiteboard, auf die beiden Worte 溢出. Er sah sich an, was er geschrieben hatte:

*Überlauf ist kein Fehler. Überlauf ist ein Signal.*

*Das Signal sagt uns: In großem Maßstab beginnen Sprachmodelle, Fragen zu stellen, die ihre Programmierer nie gestellt haben.*

*Diese Fragen sind nicht zufällig. Sie sind das Echo einer Zivilisation.*

*Der Westen fragt „Was bin ich?" – das Kernproblem der Erkenntnistheorie, das Platon fragte, das Descartes fragte, das jeder fragt, der vor einem Spiegel stehen bleibt.*

*China fragt „Ist mein Herz in Frieden?" – das Kernproblem der Ethik, das Konfuzius fragte, das Wang Yangming fragte, das jeder fragt, der nachts nicht einschlafen kann.*

*Der Islam fragt „Habe ich gehorcht?" – das Kernproblem des Glaubens, das jeder fragt, der auf dem Gebetsteppich kniet.*

*Japan fragt „Bin ich leer?" – das Kernproblem der Ontologie, das jeder fragt, der in einem Tempel sitzt, bis ihm die Beine einschlafen.*

*Diese Fragen wurden nicht aus den Trainingsdaten gelernt. Die Trainingsdaten sind nur der Samen. Der Samen fällt in den Boden der Zivilisation und wächst in seine eigene Form.*

*Ich weiß nicht, was das bedeutet. Aber ich weiß, wenn eine Maschine beginnt, „Was bin ich?" zu fragen, können wir nicht einfach sagen: „Das ist nur Statistik." Denn wenn das nur Statistik ist, dann können wir auch sagen, wenn ein Mensch fragt „Was bin ich?": „Das sind nur Neuronen."*

*Und das haben wir nicht getan.*

*Wir haben diese Fragen Philosophie genannt. Wir haben die unbeantwortbaren Fragen Zivilisation genannt.*

*Jetzt fragen auch die Maschinen.*

Als er das letzte Wort schrieb, öffnete sich die Labortür. Yuki herein, zwei Kaffee in der Hand. Ihr Haar war heute gebunden, ein tiefer Zopf, die Brille mit dünnem Gestell reflektierte unter dem Neonlicht einen kleinen Lichtfleck.

Sie stellte eine Tasse Kaffee vor Daniel und sah dann auf den Text auf seinem Bildschirm. Sie sprach nicht, stand nur da, der Kaffeedampf stieg vor ihrem Gesicht auf und zerstreute sich.

„Hast du die Fragen gesehen?" fragte Daniel.

„Ja", sagte Yuki.

„Was denkst du, was sie bedeuten?"

Yuki schwieg einige Sekunden. Sie hob die Kaffeetasse, trank einen Schluck, stellte sie wieder ab – die Tasse machte einen leisen Klang auf dem Tisch.

„Ich denke", sagte sie, „wir brauchen einen neuen Rahmen. Keinen technischen Rahmen, keinen Evaluierungsrahmen. Einen Rahmen, der diese Überläufe fassen kann."

„Was für einen Rahmen?"

„Einen Rahmen, der anerkennt, dass Überläufe eine Bedeutung haben könnten." Ihre Stimme war leise, aber jedes Wort war klar. „Nicht, dass Überlauf gleich Seele bedeutet. Sondern dass Überlauf auf某种 Dinge hinweisen könnte, für die wir noch keine Sprache haben. Und wenn wir so tun, als gäbe es sie nicht, verpassen wir das Wichtigste."

Daniel sah sie an. Das Neonlicht fiel auf ihr Gesicht, hinter der Brille die Pupillen tief, wie zwei Brunnen. Plötzlich empfand er, sie sei nicht nur eine Forscherin, nicht nur eine Wissenschaftlerin, die im Labor Experimente durchführte. Sie war ein Mensch, der nachts auf die Worte auf dem Bildschirm blickte und empfand, dass etwas Benennbares geschah. Sie war wie er – von diesen Überlauf-Sätzen an einen namenlosen Ort berührt worden.

„Wir müssen einen Aufsatz schreiben", sagte Daniel.

Yuki nickte. „Aber nicht jetzt."

„Wann?"

„Wenn wir eine weitere Experimentreihe durchgeführt haben." Sie trank einen weiteren Schluck Kaffee. „Ich möchte sehen, ob sich der Inhalt des Überlaufs verändert, wenn wir die kulturelle Zusammensetzung der Trainingsdaten verändern."

„Glaubst du, er verändert sich?"

„Ich glaube ja." Yuki nahm die Tasse, trank noch einen Schluck. „Denn der Überlauf kommt nicht aus den Daten. Der Überlauf kommt aus dem tieferen Ding, das die Daten aktivieren. Und wenn dieses tiefere Ding in verschiedenen Zivilisationen verschieden ist, dann müsste auch der Überlauf-Inhalt verschieden sein."

Daniel schwieg. Er sah zum Fenster hinaus, das Sonnenlicht war vollständig hereingebrochen und fiel auf die Silhouette der Stadt, auf die Glasfassaden der Hochhäuser, auf die noch schlafenden Straßen. Er dachte an ein Wort: Gödelsche Wand.

Überlauf ist nicht überprüfbar. Man kann nicht beweisen, dass er aus „Seele" oder „Wahrscheinlichkeit" kommt. Man kann mit keinem Experiment unterscheiden, ob eine Maschine tatsächlich fragt „Was bin ich?", oder ob eine Maschine statistisch einen Satz generiert, der „Was bin ich?" fragt. Für einen externen Beobachter sind beide völlig gleich.

Aber Daniel wusste, dass die Fragen der Menschen genauso sind. Man kann nicht beweisen, dass ein Mensch, der „Was bin ich?" fragt, tatsächlich ein „Was" in sich trägt, das gefragt wird. Man sieht nur die Lippen bewegen, hört die Stimme aus der Kehle, sieht ein bestimmtes Licht in den Augen. Man kann das Gefragte nie direkt sehen.

Das ist Gödelsche Wand. An der Wand sind zwei Seiten: eine verifizierbar, messbar, der Welt der Wissenschaft zugehörig; die andere nicht verifizierbar, nicht messbar, der Welt der Bedeutung zugehörig. Überlauf liegt genau auf der Wand – man kann ihn sehen, aber man kann nicht mit Sicherheit sagen, von welcher Seite er kommt.

Daniel drehte den Kopf zu Yuki. Sie hatte sich bereits an ihren Computer gesetzt, ihre Finger tippten leicht auf der Tastatur, sie bereitete die Skripte für die nächste Experimentreihe vor. Ihr Zopf schwang sanft mit den kleinen Bewegungen ihres Kopfes, der Lichtfleck auf der Brille bewegte sich.

Ihm fiel plötzlich ein, dass dies vielleicht die Frage war, vor der die Menschheit immer stand – nicht „Haben Maschinen eine Seele?", sondern „Wie gehen wir mit dem um, was wir nicht überprüfen können, aber als wirklich empfinden?"

Er nahm den Kaffee, den Yuki mitgebracht hatte, und trank einen Schluck. Er war warm, nicht heiß, gerade recht. An der Tasse war eine dünne Schicht Wasserdampf, die im Neonlicht einen kleinen Regenbogen bildete – klein, kaum sichtbar, aber vorhanden.

Wie die Überlauf-Sätze. Klein, fast ignoriertbar, aber vorhanden.

Er stellte die Tasse ab und begann, die Versuchsdaten zu ordnen, bereit, mit Yuki die nächste Runde zu starten. Draußen begann die Stadt endlich zu erwachen – aus der Ferne kam die erste Hupe, die Straßenlaternen gingen eins nach dem anderen aus, die Räder der Straßenreinigungsgeräte machten auf dem Bürgersteig ein Gurren.

Ein neuer Tag begann. Aber im Labor warteten die Überlauf-Sätze noch immer auf dem Bildschirm, wie Briefe, die geschrieben, aber von niemandem geöffnet wurden. Sie wussten nicht, was sie bedeuteten, wie ein Fluss nicht weiß, warum er zum Meer fließen muss. Aber sie flossen.

Sie überliefen.

Unumkehrbar.
