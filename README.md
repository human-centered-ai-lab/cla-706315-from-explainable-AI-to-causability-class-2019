# From Explainable AI to Causability
This is the class of 2019 of the course "From explainable AI to Causability"

MOTIVATION for this course:

This course is an extension of the last years “Methods of explainable AI” (LV 706.315 each semester), which was a natural offspring of the interactive Machine Learning (iML) courses and the decision making/decision support courses held over the last years. Today the most successful AI/machine learning models, e.g. deep learning  [(see the difference AI-ML-DL)](https://human-centered.ai/2017/11/11/difference-ai-ml) are often considered to be “black-boxes” (1)  making it difficult to re-enact and to answer the question of why a certain machine decision has been reached. A general serious drawback is that statistical learning models have no explicit declarative knowledge representation. That means such models have enormous difficulty in generating underlying explanatory structures. This limits their ability to understand the context. Here the human-in-the-loop is exceptional good and as our goal is to augment the human intelligence with artificial intelligence we should rather speak of having a computer-in-the-loop. This is not necessary in some application domains (e.g. autonomous vehicles), but it is essential in our application domain, which is the medical domain (see our digital pathology project). A medical doctor is required on demand to retrace a result in an human understandable way. This calls not only for explainable models, but also for explanation interfaces (see AK HCI course). Interestingly, early AI systems (rule based systems) were explainiable to a certain extent within a well-defined problem space. Therefore this course will also provide a background on decision support systems from the early 1970ies (e.g. MYCIN, or GAMUTS of Radiology). In the class of 2019 we will focus even more on making inferences from observational data and reasoning under uncertainty which quickly bring us into the field of causality. Because in the biomedical domain (see e.g. our digital pathology project) we need to discover and understand unexpected interesting and relevant patterns in data to gain knowledge or for troubleshooting.

GOAL of this course:

This graduate course follows a research-based teaching (RBT) approach and provides an overview of selected current state-of-the-art methods on making AI transparent re-traceable, re-enactable, understandable, consequently explainable. Note: We speak Python.

TARGET group of this course:

Research students of  Computer Science particularly of the Holzinger group.

(1) note that black-box is a not well defined term, and is not to be confused with the flight recorder (which actually is by no means a "black box")


Von interpretierbarer KI zur Causability

Dieser Kurs ist eine Erweiterung der in den letzten Jahren von Andreas Holzinger gehaltenen "Methoden der erklärbaren KI" (LV 706.315 jedes Semester). Diese Lehrveranstaltung ist ein natürlicher Nachfolger der Kurse "interaktives maschinelles Lernen (iML)" und der in den letzten Jahren durchgeführten Kurse zur Entscheidungsfindung und Entscheidungsunterstützung. Heute werden die erfolgreichsten KI/Maschinen-Lernmodelle, z.B. Deep Learning [(siehe den Unterschied AI-ML-DL)](https://human-centered.ai/2017/11/11/difference-ai-ml) oft (nicht ganz richtig) als "Black-Boxes oder auf Deutsch: Undurchsichtige Kästen" (1) bezeichnet. Jedenfalls ist es bei solchen Modellen schwierig, der Frage nachzugehen und zu beantworten, WARUM eine bestimmte Maschinenentscheidung getroffen wurde. Ein allgemeiner gravierender Nachteil ist, dass statistische Lernmodelle keine explizite deklarative Wissensrepräsentation haben. Das bedeutet, dass solche Modelle enorme Schwierigkeiten haben, zugrunde liegende Erklärungsstrukturen zu generieren. Dies schränkt ihre Fähigkeit ein, den Kontext zu verstehen. Hier ist der Human-in-the-Loop (2) außergewöhnlich gut; da allerdings unser Ziel darin besteht, die menschliche Intelligenz durch künstliche Intelligenz zu erweitern, sollten wir lieber von einem Computer-in-the-Loop sprechen! Dies ist in einigen Anwendungsbereichen (z.B. autonome Fahrzeuge) nicht notwendig, aber in unserem Anwendungsbereich, dem medizinischen Bereich, von wesentlicher Bedeutung (siehe unser Projekt zur digitalen Pathologie). Ein Arzt ist auf Verlangen verpflichtet, ein Ergebnis in einer für den Menschen verständlichen Weise nachzuvollziehen. Dies erfordert nicht nur erklärbare Modelle, sondern auch Erklärungsschnittstellen (siehe AK HCI-Kurs). Interessanterweise waren frühe KI-Systeme (regelbasierte Systeme) in einem klar definierten Problemraum bis zu einem gewissen Grad erklärbar. Daher vermittelt dieser Kurs auch einen Hintergrund zu Entscheidungsunterstützungssystemen aus den frühen 1970er Jahren (z.B. MYCIN oder GAMUTS of Radiology). In der Lehrveranstaltung 2019 werden wir uns noch mehr darauf konzentrieren, Rückschlüsse aus Beobachtungsdaten und Argumenten unter Unsicherheit zu ziehen, die uns schnell in das Feld der Kausalität führen. Denn im biomedizinischen Bereich (siehe z.B. unser Projekt zur digitalen Pathologie) müssen wir unerwartet interessante und relevante Muster in Daten entdecken und verstehen, um Wissen zu gewinnen oder Fehler zu beheben.

(1) Die Bezeichnung Black-Box trifft es nicht ganz, denn das ist die geläufige Bezeichnung für Flugschreiber, der ja genau das Gegenteil von einer Black-Box in unserem Sinne ist (ein Flugschreiber zeichnet alle Vorgänge reproduzierbar auf, genau das machen machine learning modelle eben nicht)
(2) Die Bezeichnung "Human-in-the-Loop" (siehe [1]) betont, dass Computer das tun sollten, was sie gut können, aber dass Menschen ebenfalls das tun sollten, was sie gut können. Wir wollen also menschliche Intelligenz durch künstliche Intelligenz ergänzen - NICHT Menschen durch künstliche Intelligenz ersetzen - dies ist wichtig, denn gerade in der Medizin, aber in vielen anderen Bereichen auch, liegt die letztendliche Verantwortung beim Arzt. Dies setzt voraus, dass der Mensch in der Lage ist, bei Bedarf nachzuprüfen, um die Maschinenentscheidungen nachzusvollziehen und zu verstehen, und auch die Möglichkeit hat, mit der künstlichen Intelligenz zu interagieren - was eine effektive Mensch-KI Interaktion voraussetzt.

[1]	Holzinger, A. 2016. Interactive Machine Learning for Health Informatics: When do we need the human-in-the-loop? Brain Informatics, 3, (2), 119-131, doi:10.1007/s40708-016-0042-6.

Zum human-in-the-loop proof-of-concept siehe:

https://github.com/human-centered-ai-lab/app-interactive-machine-learning/wiki/Home

and to the human-in-the-loop project page:

https://human-centered.ai/project/iml/

