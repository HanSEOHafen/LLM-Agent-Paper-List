Der Aufstieg und das Potenzial großer sprachmodellbasierter Agenten: Eine Umfrage
🔥 Pflichtlektüre für LLM-basierte Agenten.

🏃 Demnächst erhältlich: Fügen Sie jeder Arbeit eine Einleitung mit einem Satz hinzu.

🔔 Neuigkeiten
🥳 [20.09.2023] Dieses Projekt wurde auf GitHub Trendings gelistet ! Es ist eine große Ehre!
💥 [15.09.2023] Unsere Umfrage ist veröffentlicht! Siehe „The Rise and Potential of Large Language Model Based Agents: A Survey“ für den Artikel!
✨ [14.09.2023] Wir erstellen dieses Repository, um eine Papierliste zu LLM-basierten Agenten zu führen. Weitere Papiere folgen in Kürze!

🌟 Einführung
Seit langem strebt die Menschheit nach künstlicher Intelligenz (KI), die dem menschlichen Niveau entspricht oder dieses übertrifft, wobei KI-Agenten als vielversprechendes Vehikel für dieses Streben gelten. KI-Agenten sind künstliche Einheiten, die ihre Umgebung wahrnehmen, Entscheidungen treffen und Maßnahmen ergreifen.

Aufgrund der vielseitigen und bemerkenswerten Fähigkeiten, die sie demonstrieren, gelten große Sprachmodelle (LLMs) als potenzielle Impulse für die Künstliche Allgemeine Intelligenz (AGI) und bieten Hoffnung für die Entwicklung allgemeiner KI-Agenten. Viele Forschungsanstrengungen haben LLMs als Grundlage für die Entwicklung von KI-Agenten genutzt und erhebliche Fortschritte erzielt.

In diesem Repository bieten wir eine systematische und umfassende Übersicht über LLM-basierte Agenten und listen einige Artikel auf, die man unbedingt lesen muss.

Konkret beginnen wir mit dem allgemeinen konzeptionellen Rahmen für LLM-basierte Agenten: Er umfasst drei Hauptkomponenten: Gehirn, Wahrnehmung und Aktion, und der Rahmen kann an verschiedene Anwendungen angepasst werden. Anschließend untersuchen wir die umfangreichen Anwendungen von LLM-basierten Agenten in drei Aspekten: Einzelagentenszenarien, Multiagentenszenarien und Mensch-Agenten-Kooperation. Anschließend befassen wir uns mit Agentengesellschaften und erforschen das Verhalten und die Persönlichkeit von LLM-basierten Agenten, die sozialen Phänomene, die bei der Bildung von Gesellschaften entstehen, und die Erkenntnisse, die sie für die menschliche Gesellschaft bieten. Abschließend besprechen wir eine Reihe wichtiger Themen und offene Probleme auf diesem Gebiet.

Wir freuen uns sehr über Beiträge über PRs, Issues, E-Mails oder auf andere Weise.

Inhaltsverzeichnis (ToC)
Der Aufstieg und das Potenzial großer sprachmodellbasierter Agenten: Eine Umfrage
🔔 Neuigkeiten
🌟 Einführung
Inhaltsverzeichnis (ToC)
1. Die Geburt eines Agenten: Aufbau von LLM-basierten Agenten
1.1 Gehirn: Besteht hauptsächlich aus einem LLM
1.1.1 Interaktion mit natürlicher Sprache
Hochwertige Generation
Tiefes Verständnis
1.1.2 Wissen
Pretrain-Modell
Sprachkenntnisse
Gesundes Wissen
Umsetzbares Wissen
Mögliche Wissensprobleme
1.1.3 Speicher
Speicherfähigkeit
Erhöhung der Längenbeschränkung von Transformers
Erinnerung zusammenfassen
Komprimieren von Speichern mit Vektoren oder Datenstrukturen
Erinnerungsabruf
1.1.4 Argumentation und Planung
Argumentation
Planung
Planformulierung
Reflexion planen
1.1.5 Übertragbarkeit und Verallgemeinerung
Ungesehene Aufgabenverallgemeinerung
Lernen im Kontext
Kontinuierliches Lernen
1.2 Wahrnehmung: Multimodale Eingaben für LLM-basierte Agenten
1.2.1 Visuell
1.2.2 Audio
1.3 Aktion: Aktionsraum von LLM-basierten Agenten erweitern
1.3.1 Werkzeugverwendung
1.3.2 Verkörperte Aktion
2. Agenten in der Praxis: Anwendungen von LLM-basierten Agenten
2.1 Allgemeine Fähigkeiten eines Einzelagenten
2.1.1 Aufgabenorientierte Bereitstellung
2.1.2 Innovationsorientierter Einsatz
2.1.3 Lebenszyklusorientierte Bereitstellung
2.2 Koordinierungspotential mehrerer Agenten
2.2.1 Kooperative Interaktion für Komplementarität
2.2.2 Gegnerische Interaktion für den Fortschritt
2.3 Interaktive Interaktion zwischen Mensch und Agent
2.3.1 Instructor-Executor-Paradigma
Ausbildung
Gesundheit
Andere Anwendung
2.3.2 Paradigma der gleichberechtigten Partnerschaft
Einfühlsamer Kommunikator
Teilnehmer auf menschlicher Ebene
3. Agentengesellschaft: Von der Individualität zur Sozialität
3.1 Verhalten und Persönlichkeit von LLM-basierten Agenten
3.1.1 Sozialverhalten
Individuelle Verhaltensweisen
Gruppenverhalten
3.1.2 Persönlichkeit
Erkenntnis
Emotion
Charakter
3.2 Umgebung für die Agentengesellschaft
3.2.1 Textbasierte Umgebung
3.2.2 Virtuelle Sandbox-Umgebung
3.2.3 Physische Umgebung
3.3 Gesellschaftssimulation mit LLM-basierten Agenten
Zitat
Projektbetreuer und Mitwirkende
Kontakt
Sternengeschichte
1. Die Geburt eines Agenten: Aufbau von LLM-basierten Agenten

1.1 Gehirn: Besteht hauptsächlich aus einem LLM
1.1.1 Interaktion mit natürlicher Sprache
Hochwertige Generation
[2023/10] Auf dem Weg zu einer durchgängigen verkörperten Entscheidungsfindung über ein multimodales großes Sprachmodell: Erkundungen mit GPT4-Vision und darüber hinaus Liang Chen et al. arXiv. [ Papier ] [ Code ]
Diese Arbeit schlägt PCA-EVAL vor, das die verkörperte Entscheidungsfindung mittels MLLM-basierter End-to-End-Methode und LLM-basierter Tool-Using-Methoden auf Wahrnehmungs-, Kognitions- und Aktionsebene bewertet.
[2023/08] Eine mehrsprachige, multimodale Multitasking-Bewertung von ChatGPT in Bezug auf Argumentation, Halluzination und Interaktivität. Yejin Bang et al. arXiv. [ Papier ]
Diese Arbeit bewertet die Multitasking-, Mehrsprachigkeits- und Multimodalaspekte von ChatGPT anhand von 21 Datensätzen, die 8 verschiedene gängige NLP-Anwendungsaufgaben abdecken.
[2023/06] LLM-Eval: Einheitliche mehrdimensionale automatische Bewertung für Open-Domain-Konversationen mit großen Sprachmodellen. Yen-Ting Lin et al. arXiv. [ Papier ]
Die LLM-EVAL-Methode bewertet mehrere Bewertungsdimensionen wie Inhalt, Grammatik, Relevanz und Angemessenheit.
[2023/04] Ist ChatGPT ein hochflüssiges System zur Korrektur grammatikalischer Fehler? Eine umfassende Auswertung. Tao Fang et al. arXiv. [ Papier ]
Die Ergebnisse der Evaluierung zeigen, dass ChatGPT über hervorragende Fähigkeiten zur Fehlererkennung verfügt und Fehler frei korrigieren kann, um die korrigierten Sätze sehr flüssig zu machen. Darüber hinaus unterstreicht seine Leistung in nicht-englischsprachigen und ressourcenarmen Umgebungen sein Potenzial bei mehrsprachigen GEC-Aufgaben.
Tiefes Verständnis
[2023/06] Clever Hans oder Neural Theory of Mind? Stresstests des sozialen Denkens in großen Sprachmodellen. Natalie Shapira et al. arXiv. [ Papier ]
LLMs weisen bestimmte Fähigkeiten zur Theorie des Geistes auf, aber dieses Verhalten ist alles andere als robust.
[2022/08] Ableitung von Belohnungen aus der Sprache im Kontext. Jessy Lin et al. ACL. [ Papier ]
Diese Arbeit stellt ein Modell vor, das Belohnungen aus der Sprache ableitet und optimale Aktionen in einer unsichtbaren Umgebung vorhersagt.
[2021/10] Theorie der gedankenbasierten unterstützenden Kommunikation in der komplexen Mensch-Roboter-Kooperation. Moritz C. Buehler et al. arXiv. [ Papier ]
Diese Arbeit entwirft einen Agenten Sushi mit einem Verständnis für den Menschen während der Interaktion.
1.1.2 Wissen
Pretrain-Modell
[2023/04] Lernen verteilter Darstellungen von Sätzen aus unbeschrifteten Daten. Felix Hill (Universität Cambridge) et al. arXiv. [ Papier ]
[2020/02] Wie viel Wissen können Sie in die Parameter eines Sprachmodells packen? Adam Roberts (Google) et al. arXiv. [ Papier ]
[2020/01] Skalierungsgesetze für neuronale Sprachmodelle. Jared Kaplan (Johns Hopkins University) et al. arXiv. [ Papier ]
[2017/12] Commonsense-Wissen in maschineller Intelligenz. Niket Tandon (Allen Institute for Artificial Intelligence) et al. SIGMOD. [ Papier ]
[2011/03] Verarbeitung natürlicher Sprache (fast) von Grund auf. Ronan Collobert (Princeton) et al. arXiv. [ Papier ]
Sprachkenntnisse
[2023/02] Eine mehrsprachige, multimodale Multitasking-Bewertung von ChatGPT in Bezug auf Argumentation, Halluzination und Interaktivität. Yejin Bang et al. arXiv. [ Papier ]
[2021/06] Untersuchung vorab trainierter Sprachmodelle auf semantische Attribute und ihre Werte. Meriem Beloucif et al. EMNLP. [ Papier ]
[2020/10] Untersuchung vorab trainierter Sprachmodelle für die lexikalische Semantik. Ivan Vulić et al. arXiv. [ Papier ]
[2019/04] Eine strukturelle Sonde zum Finden der Syntax in Wortdarstellungen. John Hewitt et al. ACL. [ Papier ]
[2016/04] Verbesserte automatische Schlüsselwortextraktion mit mehr semantischem Wissen. H. Leung. Systeme für fortgeschrittene Anwendungen. [ Papier ]
Gesundes Wissen
[2022/10] Sprachmodelle des Codes sind Few-Shot-Commonsense-Lernende. Aman Madaan et al.arXiv. [ Papier ]
[2021/04] Relationale Weltwissensrepräsentation in kontextuellen Sprachmodellen: Ein Rückblick. Tara Safavi et al. arXiv. [ Papier ]
[2019/11] Wie können wir wissen, was Sprachmodelle wissen? Zhengbao Jiang et al.arXiv. [ Papier ]
Umsetzbares Wissen
[2023/07] Große Sprachmodelle in der Medizin. Arun James Thirunavukarasu et al. Natur. [ Papier ]
[2023/06] DS-1000: Ein natürlicher und zuverlässiger Maßstab für die Generierung von Data Science-Code. Yuhang Lai et al. ICML. [ Papier ]
[2022/10] Sprachmodelle des Codes sind Few-Shot-Commonsense-Lernende. Aman Madaan et al. arXiv. [ Papier ]
[2022/02] Eine systematische Bewertung großer Sprachmodelle von Code. Frank F. Xu et al.arXiv. [ Papier ]
[2021/10] Schulung von Verifizierern zur Lösung mathematischer Wortprobleme. Karl Cobbe et al. arXiv. [ Papier ]
Mögliche Wissensprobleme
[2023/10] FreshLLMs: Auffrischung großer Sprachmodelle mit Suchmaschinenerweiterung. Tu Vu (Google) et al. arXiv [ Papier ] [ Code ]
[2023/05] Bearbeiten großer Sprachmodelle: Probleme, Methoden und Chancen. Yunzhi Yao et al. arXiv. [ Papier ]
[2023/05] Self-Checker: Plug-and-Play-Module zur Faktenprüfung mit großen Sprachmodellen. Miaoran Li et al. arXiv. [ Papier ]
[2023/05] KRITIK: Große Sprachmodelle können sich mit Tool-interaktiver Kritik selbst korrigieren. Zhibin Gou et al. arXiv. [ Papier ]
[2023/04] Tool-Lernen mit Grundlagenmodellen. Yujia Qin et al. arXiv. [ Papier ]
[2023/03] SelfCheckGPT: Ressourcenlose Black-Box-Halluzinationserkennung für generative große Sprachmodelle. Potsawee Manakul et al. arXiv. [ Papier ]
[2022/06] Speicherbasierte Modellbearbeitung im Maßstab. Eric Mitchell et al. arXiv. [ Papier ]
[2022/04] Ein Überblick über Sprachmodelle als Wissensdatenbanken. Badr AlKhamissi et al.arXiv. [ Papier ]
[2021/04] Bearbeiten von Faktenwissen in Sprachmodellen. Nicola De Cao et al.arXiv. [ Papier ]
[2017/08] Messung des katastrophalen Vergessens in neuronalen Netzen. Ronald Kemker et al.arXiv. [ Papier ]
1.1.3 Speicher
Speicherfähigkeit
Erhöhung der Längenbeschränkung von Transformers
[2023/10] MemGPT: Auf dem Weg zu LLMs als Betriebssystemen. Charles Packer (UC Berkeley) et al. arXiv. [ Papier ] [ Projektseite ] [ Code ] [ Datensatz ]
[2023/05] Randomisierte Positionskodierungen fördern die Längengeneralisierung von Transformatoren. Anian Ruoss (DeepMind) et al. arXiv. [ Papier ] [ Code ]
[2023-03] CoLT5: Schnellere Ferntransformatoren mit bedingter Berechnung. Joshua Ainslie (Google Research) et al. arXiv. [ Papier ]
[2022/03] Effiziente Klassifizierung langer Dokumente mithilfe von Transformern. Hyunji Hayley Park (Illinois University) et al. arXiv. [ Papier ] [ Code ]
[2021/12] LongT5: Effizienter Text-zu-Text-Transformer für lange Sequenzen. Mandy Guo (Google Research) et al. arXiv. [ Papier ] [ Code ]
[2019/10] BART: Denoising Sequence-to-Sequence Pre-Training für die Erzeugung, Übersetzung und das Verständnis natürlicher Sprache. Michael Lewis (Facebook AI) et al. arXiv. [ Papier ] [ Code ]
Erinnerung zusammenfassen
[2023/10] Durch das Gedächtnislabyrinth: Über Kontextgrenzen hinaus durch interaktives Lesen Howard Chen (Princeton University) et al. arXiv. [ Papier ]
[2023/09] Stärkung des Privatunterrichts durch Verkettung großer Sprachmodelle Yulin Chen (Tsinghua-Universität) et al. arXiv. [ Papier ]
[2023/08] ExpeL: LLM-Agenten sind erfahrungsorientierte Lernende. Andrew Zhao (Tsinghua-Universität) et al. arXiv. [ Papier ] [ Code ]
[2023/08] ChatEval: Auf dem Weg zu besseren LLM-basierten Evaluatoren durch Multi-Agent-Debatte. Chi-Min Chan (Tsinghua-Universität) et al. arXiv. [ Papier ] [ Code ]
[2023/05] MemoryBank: Erweiterung großer Sprachmodelle mit Langzeitgedächtnis. Wanjun Zhong (Harbin Institute of Technology) et al. arXiv. [ Papier ] [ Code ]
[2023/04] Generative Agenten: Interaktive Simulakren menschlichen Verhaltens. Joon Sung Park (Stanford University) et al. arXiv. [ Papier ] [ Code ]
[2023/04] Entfesselung der Eingabekapazität unendlicher Länge für große Sprachmodelle mit selbstkontrolliertem Speichersystem. Xinnian Liang (Universität Beihang) et al. arXiv. [ Papier ] [ Code ]
[2023/03] Reflexion: Sprachagenten mit verbalem Verstärkungslernen. Noah Shinn (Northeastern University) et al. arXiv. [ Papier ] [ Code ]
[2023/05] RecurrentGPT: Interaktive Generierung von (beliebig) langem Text. Wangchunshu Zhou (AIWaves) et al. arXiv. [ Papier ] [ Code ]
Komprimieren von Speichern mit Vektoren oder Datenstrukturen
[2023/07] Kommunikative Agenten für die Softwareentwicklung. Chen Qian (Tsinghua-Universität) et al. arXiv. [ Papier ] [ Code ]
[2023/06] ChatDB: Erweiterung von LLMs mit Datenbanken als symbolischem Gedächtnis. Chenxu Hu (Tsinghua-Universität) et al. arXiv. [ Papier ] [ Code ]
[2023/05] Ghost in the Minecraft: Generell leistungsfähige Agenten für Open-World-Umgebungen über große Sprachmodelle mit textbasiertem Wissen und Gedächtnis. Xizhou Zhu (Tsinghua-Universität) et al. arXiv. [ Papier ] [ Code ]
[2023/05] RET-LLM: Auf dem Weg zu einem allgemeinen Lese-/Schreibspeicher für große Sprachmodelle. Ali Modarressi (LMU München) et al. arXiv. [ Papier ] [ Code ]
[2023/05] RecurrentGPT: Interaktive Generierung von (beliebig) langem Text. Wangchunshu Zhou (AIWaves) et al. arXiv. [ Papier ] [ Code ]
Erinnerungsabruf
[2023/08] Memory Sandbox: Transparente und interaktive Speicherverwaltung für Konversationsagenten. Ziheng Huang (University of California – San Diego) et al. arXiv. [ Papier ]
[2023/08] AgentSims: Eine Open-Source-Sandbox für die Evaluierung großer Sprachmodelle. Jiaju Lin (PTA Studio) et al. arXiv. [ Papier ] [ Projektseite ] [ Code ]
[2023/06] ChatDB: Erweiterung von LLMs mit Datenbanken als symbolischem Gedächtnis. Chenxu Hu (Tsinghua-Universität) et al. arXiv. [ Papier ] [ Code ]
[2023/05] MemoryBank: Erweiterung großer Sprachmodelle mit Langzeitgedächtnis. Wanjun Zhong (Harbin Institute of Technology) et al. arXiv. [ Papier ] [ Code ]
[2023/04] Generative Agenten: Interaktive Simulakren menschlichen Verhaltens. Joon Sung Park (Stanford) et al. arXiv. [ Papier ] [ Code ]
[2023/05] RecurrentGPT: Interaktive Generierung von (beliebig) langem Text. Wangchunshu Zhou (AIWaves) et al. arXiv. [ Papier ] [ Code ]
1.1.4 Argumentation und Planung
Argumentation
[2023/09] ReConcile: Round-Table-Konferenz verbessert die Argumentation durch Konsens zwischen verschiedenen LLMs. Justin Chih-Yao Chen (University of North Carolina at Chapel Hill) et al. arXiv. [ Papier ] [ Code ]

[2023/05] Self-Polish: Verbessern Sie das Denken in großen Sprachmodellen durch Problemverfeinerung. Zhiheng Xi (Fudan-Universität) et al. arXiv. [ Papier ] [ Code ]

[2023-03] Große Sprachmodelle sind Zero-Shot-Reasonatoren. Takeshi Kojima (Universität Tokio) et al. arXiv. [ Papier ] [ Code ]

[2023/03] Self-Refine: Iterative Verfeinerung mit Selbst-Feedback. Aman Madaan (Carnegie Mellon University) et al. arXiv. [ Papier ] [ Code ]

[2022/05] Auswahl-Inferenz: Nutzung großer Sprachmodelle für interpretierbares logisches Denken. Antonia Creswell (DeepMind) et al. arXiv. [ Papier ]

[2022/03] Selbstkonsistenz verbessert die Gedankenkette in Sprachmodellen. Xuezhi Wang (Google Research) et al. arXiv. [ Papier ] [ Code ]

[2023/02] Multimodales Chain-of-Thought Reasoning in Sprachmodellen. Zhuosheng Zhang (Shanghai Jiao Tong Universität) et al. arXiv. [ Papier ] [ Code ]

[2022/01] Chain-of-Thought-Prompting löst Argumentation in großen Sprachmodellen aus. Jason Wei (Google Research) et al. arXiv. [ Papier ]

Planung
Planformulierung
[2023/11] JARVIS-1: Open-World-Multitasking-Agenten mit speichererweiterten multimodalen Sprachmodellen. ZiHao Wang (Universität Peking) et al. arXiv. [ Papier ] [ Code ]
[2023/10] Die Sprachagentenbaumsuche vereint Argumentation, Handeln und Planen in Sprachmodellen. Andy Zhou (University of Illinois Urbana-Champaign) et al. arXiv. [ Papier ] [ Projektseite ] [ Code ]
[2023/05] Gedankenbaum: Bewusste Problemlösung mit großen Sprachmodellen. Shunyu Yao (Princeton University) et al. arXiv. [ Papier ] [ Code ]
[2023/05] Planen, eliminieren und verfolgen – Sprachmodelle sind gute Lehrer für verkörperte Agenten. Yue Wu (Carnegie Mellon University) et al. arXiv. [ Papier ]
[2023/05] Denken mit dem Sprachmodell ist Planen mit dem Weltmodell. Shibo Hao (UC San Diego) et al. arXiv. [ Papier ] [ Code ]
[2023/05] SwiftSage: Ein generativer Agent mit schnellem und langsamem Denken für komplexe interaktive Aufgaben. Bill Yuchen Lin (Allen Institute for Artificial Intelligence) et al. arXiv. [ Papier ] [ Code ]
[2023/04] LLM+P: Unterstützung großer Sprachmodelle durch optimale Planungskompetenz. Bo Liu (University of Texas at Austin) et al. arXiv. [ Papier ] [ Code ]
[2023/03] HuggingGPT: KI-Aufgaben lösen mit ChatGPT und seinen Freunden in Hugging Face. Yongliang Shen (Microsoft Research Asia) et al. arXiv. [ Papier ] [ Code ]
[2023/02] Beschreiben, erklären, planen und auswählen: Interaktive Planung mit großen Sprachmodellen ermöglicht Open-World-Multitasking-Agenten. ZiHao Wang (Universität Peking) et al. arXiv. [ Papier ] [ Code ]
[2022/05] Least-to-Most-Prompting ermöglicht komplexes Denken in großen Sprachmodellen. Denny Zhou (Google Research) et al. arXiv. [ Papier ]
[2022/05] MRKL Systems: Eine modulare, neurosymbolische Architektur, die große Sprachmodelle, externe Wissensquellen und diskretes Denken kombiniert. Ehud Karpas (AI21 Labs) et al. arXiv. [ Papier ]
[2022/04] Tue, was ich kann, nicht was ich sage: Sprache in Roboterleistungen verankern. Michael Ahn (Robotik bei Google) et al. arXiv. [ Papier ]
[2023/05] Agenten: Ein Open-Source-Framework für autonome Sprachagenten. Wangchunshu Zhou (AIWaves) et al. arXiv. [ Papier ] [ Code ]
[2022/12] Nicht generieren, sondern diskriminieren: Ein Vorschlag zur Verankerung von Sprachmodellen in realen Umgebungen. Yu Gu (The Ohio State University) et al. ACL. [ Papier ] [ Code ]
Reflexion planen
[2023/11] JARVIS-1: Open-World-Multitasking-Agenten mit speichererweiterten multimodalen Sprachmodellen. ZiHao Wang (Universität Peking) et al. arXiv. [ Papier ] [ Code ]
[2023/10] Chain-of-Verification reduziert Halluzinationen in großen Sprachmodellen. Shehzaad Dhuliawala (Meta AI & ETH Zürich) et al. arXiv. [ Papier ]
[2023/10] FireAct: Auf dem Weg zur Feinabstimmung des Sprachagenten. Baian Chen (System2 Research) et al. arXiv. [ Papier ] [ Projektseite ] [ Code ] [ Datensatz ]
[2023/08] SelfCheck: Verwenden von LLMs zur Zero-Shot-Überprüfung ihrer eigenen schrittweisen Argumentation. Ning Miao (Universität Oxford) et al. arXiv. [ Papier ] [ Code ]
[2023/05] ChatCoT: Tool-erweitertes Chain-of-Thought Reasoning auf Chat-basierten großen Sprachmodellen. Zhipeng Chen (Renmin-Universität China) et al. arXiv. [ Papier ] [ Code ]
[2023/05] Voyager: Ein verkörperter Agent mit offenem Ende und großen Sprachmodellen. Guanzhi Wang (NVIDIA) et al. arXiv. [ Papier ] [ Projektseite ] [ Code ]
[2023/03] Chat mit der Umwelt: Interaktive multimodale Wahrnehmung mithilfe großer Sprachmodelle. Xufeng Zhao (Universität Hamburg) et al. arXiv. [ Papier ] [ Code ]
[2022/12] LLM-Planner: Few-Shot Grounded Planning für verkörperte Agenten mit großen Sprachmodellen. Chan Hee Song (The Ohio State University) et al. arXiv. [ Papier ] [ Code ]
[2022/10] ReAct: Synergie zwischen Denken und Handeln in Sprachmodellen. Shunyu Yao (Princeton University) et al. arXiv. [ Papier ] [ Code ]
[2022/07] Innerer Monolog: Verkörpertes Denken durch Planung mit Sprachmodellen. Wenlong Huang (Robotik bei Google) et al. arXiv. [ Papier ] [ Code ]
[2021/10] KI-Ketten: Transparente und kontrollierbare Mensch-KI-Interaktion durch Verkettung großer Sprachmodell-Eingabeaufforderungen. Tongshuang Wu (University of Washington) et al. arXiv. [ Papier ]
1.1.5 Übertragbarkeit und Verallgemeinerung
Ungesehene Aufgabenverallgemeinerung
[2023/10] AgentTuning: Aktivierung allgemeiner Agentenfähigkeiten für LLMs. Aohan Zeng (Tsinghua-Universität) et al. arXiv. [ Papier ] [ Projektseite ] [ Code ] [ Datensatz ]
[2023/10] Lemur: Harmonisierung natürlicher Sprache und Code für Sprachagenten Yiheng Xu (Universität Hongkong) et al. arXiv. [ Papier ] [ Code ]
[2023/05] Sprachmodelle trainieren, um Anweisungen mit menschlichem Feedback zu befolgen. Long Ouyang et al. NeurIPS. [ Papier ]
InstructGPT: Ausrichtung von Sprachmodellen auf die Benutzerabsicht bei einer Vielzahl von Aufgaben durch Feinabstimmung mit menschlichem Feedback.
[2023/01] Multitasking-gestütztes Training ermöglicht die Verallgemeinerung von Zero-Shot-Aufgaben. Victor Sanh et al. ICLR. [ Papier ] [ Code ]
T0: T0 ist ein Encoder-Decoder-Modell, das Texteingaben verarbeitet und Zielantworten erzeugt. Es wird auf einer Multitasking-Mischung aus NLP-Datensätzen trainiert, die in verschiedene Aufgaben unterteilt sind.
[2022/10] Skalierung von anweisungsfein abgestimmten Sprachmodellen. Hyung Won Chung et al. arXiv. [ Papier ] [ Code ]
Diese Arbeit untersucht die Feinabstimmung von Anweisungen mit besonderem Schwerpunkt auf der Skalierung der Anzahl der Aufgaben und der Modellgröße, wodurch die Leistung bei einer Vielzahl von Modellklassen, Eingabeaufforderungseinstellungen und Bewertungsbenchmarks verbessert wird.
[2022/08] Fein abgestimmte Sprachmodelle sind Zero-Shot-Lernende. Jason Wei et al. ICLR. [ Papier ]
FLAN: Die Befehlsoptimierung verbessert die Zero-Shot-Leistung bei unsichtbaren Aufgaben erheblich.
Lernen im Kontext
[2023/08] Bilder sprechen in Bildern: Ein generalistischer Maler für kontextbezogenes visuelles Lernen. Xinlong Wang et al. IEEE. [ Papier ] [ Code ]
Maler: Diese Arbeit stellt ein generalistisches Modell für kontextbezogenes visuelles Lernen mit einer „bildzentrierten“ Lösung vor.
[2023/08] Neuronale Codec-Sprachmodelle sind Zero-Shot-Text-zu-Sprache-Synthesizer. Chengyi Wang et al. arXiv. [ Papier ] [ Code ]
VALL-E: Diese Arbeit trainiert ein neuronales Codec-Sprachmodell, das kontextbezogene Lernfähigkeiten hervorbringt.
[2023/07] Eine Umfrage zum kontextbezogenen Lernen. Qingxiu Dong et al. arXiv. [ Papier ]
Diese Umfrage fasst die Fortschritte und Herausforderungen des In-Context-Lernens (ICL) zusammen.
[2023/05] Sprachmodelle sind Few-Shot-Lernende. Tom B. Brown (OpenAI) et al. NeurIPS. [ Papier ]
GPT-3: Die Skalierung von Sprachmodellen verbessert die aufgabenunabhängige Leistung bei wenigen Schüssen erheblich und wird manchmal sogar mit früheren Feinabstimmungsansätzen auf dem neuesten Stand der Technik konkurrenzfähig.
Kontinuierliches Lernen
[2023/11] JARVIS-1: Open-World-Multitasking-Agenten mit speichererweiterten multimodalen Sprachmodellen. ZiHao Wang (Universität Peking) et al. arXiv. [ Papier ] [ Code ]
[2023/07] Progressive Prompts: Kontinuierliches Lernen für Sprachmodelle. Razdaibiedina et al. arXiv. [ Papier ]
In dieser Arbeit werden progressive Eingabeaufforderungen vorgestellt, die eine Vorwärtsübertragung ermöglichen und katastrophalem Vergessen widerstehen, ohne auf die Datenwiedergabe oder eine große Anzahl aufgabenspezifischer Parameter angewiesen zu sein.
[2023/05] Voyager: Ein verkörperter Agent mit offenem Ende und großen Sprachmodellen. Guanzhi Wang (NVIDIA) et al. arXiv. [ Papier ] [ Projektseite ] [ Code ]
Voyager: Dies ist ein Beispiel für einen LLM-gestützten, verkörperten lebenslangen Lernagenten in Minecraft, der kontinuierlich die Welt erkundet, verschiedene Fähigkeiten erwirbt und ohne menschliches Eingreifen neue Entdeckungen macht.
[2023/01] Ein umfassender Überblick über kontinuierliches Lernen: Theorie, Methode und Anwendung. Liyuan Wang et al. arXiv. [ Papier ]
Diese Umfrage stellt einen umfassenden Überblick über kontinuierliches Lernen dar und versucht, eine Brücke zwischen grundlegenden Einstellungen, theoretischen Grundlagen, repräsentativen Methoden und praktischen Anwendungen zu schlagen.
[2022/11] Kontinuierliches Lernen von Aufgaben zur Verarbeitung natürlicher Sprache: Eine Umfrage. Zixuan Ke et al. arXiv. [ Papier ]
Diese Umfrage bietet einen umfassenden Überblick und eine Analyse der jüngsten Fortschritte von CL im NLP.
1.2 Wahrnehmung: Multimodale Eingaben für LLM-basierte Agenten
1.2.1 Visuell
[2023/10] Auf dem Weg zu einer durchgängigen verkörperten Entscheidungsfindung über ein multimodales großes Sprachmodell: Erkundungen mit GPT4-Vision und darüber hinaus Liang Chen et al. arXiv. [ Papier ] [ Code ]
[2023/05] Sprache ist nicht alles, was Sie brauchen: Wahrnehmung mit Sprachmodellen in Einklang bringen. Shaohan Huang et al. arXiv. [ Papier ]
[2023/05] InstructBLIP: Auf dem Weg zu universellen Vision-Language-Modellen mit Instruction Tuning. Wenliang Dai et al. arXiv. [ Papier ]
[2023/05] MultiModal-GPT: Ein Visions- und Sprachmodell für den Dialog mit Menschen. Tao Gong et al. arXiv. [ Papier ]
[2023/05] PandaGPT: Ein Modell zum Anleiten – Befolgen Sie sie alle. Yixuan Su et al. arXiv. [ Papier ]
[2023/04] Optimierung der visuellen Anweisungen. Haotian Liu et al. arXiv. [ Papier ]
[2023/04] MiniGPT-4: Verbesserung des Vision-Sprach-Verständnisses mit fortschrittlichen großen Sprachmodellen. Deyao Zhu. arXiv. [ Papier ]
[2023/01] BLIP-2: Bootstrapping-Sprachbild-Vortraining mit Encodern für eingefrorene Bilder und großen Sprachmodellen. Junnan Li et al. arXiv. [ Papier ]
[2022/04] Flamingo: ein visuelles Sprachmodell für Few-Shot-Lernen. Jean-Baptiste Alayrac et al. arXiv. [ Papier ]
[2021/10] MobileViT: Leichter, universeller und mobilfreundlicher Vision Transformer. Sachin Mehta et al.arXiv. [ Papier ]
[2021/05] MLP-Mixer: Eine reine MLP-Architektur für Vision. Ilya Tolstikhin et al.arXiv. [ Papier ]
[2020/10] Ein Bild sagt mehr als 16 x 16 Worte: Transformatoren für die Bilderkennung im Maßstab. Alexey Dosovitskiy et al. arXiv. [ Papier ]
[2017/11] Neuronales diskretes Repräsentationslernen. Aaron van den Oord et al. arXiv. [ Papier ]
1.2.2 Audio
[2023/06] Video-LLaMA: Ein auf Anweisungen abgestimmtes audiovisuelles Sprachmodell für das Videoverständnis. Hang Zhang et al. arXiv. [ Papier ]
[2023/05] X-LLM: Bootstrapping fortgeschrittener großer Sprachmodelle durch Behandlung von Multimodalitäten als Fremdsprachen. Feilong Chen et al. arXiv. [ Papier ]
[2023/05] InternGPT: Vision-zentrierte Aufgaben durch Interaktion mit ChatGPT Beyond Language lösen. Zhaoyang Liu et al. arXiv. [ Papier ]
[2023/04] AudioGPT: Sprache, Musik, Ton und sprechenden Kopf verstehen und erzeugen. Rongjie Huang et al. arXiv. [ Papier ]
[2023/03] HuggingGPT: KI-Aufgaben lösen mit ChatGPT und seinen Freunden in Hugging Face. Yongliang Shen et al. arXiv. [ Papier ]
[2021/06] HuBERT: Selbstüberwachtes Sprachrepräsentationslernen durch maskierte Vorhersage versteckter Einheiten. Wei-Ning Hsu et al. arXiv. [ Papier ]
[2021/04] AST: Audio Spectrogram Transformer. Yuan Gong et al. arXiv. [ Papier ]
1.3 Aktion: Aktionsraum von LLM-basierten Agenten erweitern
1.3.1 Werkzeugverwendung
[2023/10] OpenAgents: Eine offene Plattform für Sprachagenten in freier Wildbahn. XLang Lab (Universität Hongkong) arXiv. [ Papier ] [ Projektseite ] [ Code ] [ Demo ]
[2023/10] Lemur: Harmonisierung natürlicher Sprache und Code für Sprachagenten Yiheng Xu (Universität Hongkong) et al. arXiv. [ Papier ] [ Code ]
[2023/10] Auf dem Weg zu einer durchgängigen verkörperten Entscheidungsfindung über ein multimodales großes Sprachmodell: Erkundungen mit GPT4-Vision und darüber hinaus Liang Chen (Universität Peking) et al. arXiv. [ Papier ] [ Code ]
HOLMES ist ein Multi-Agenten-Kooperationsrahmen, der es LLMs ermöglicht, MLLMs und APIs zu nutzen, um multimodale Informationen für eine fundierte Entscheidungsfindung zu sammeln.
[2023/07] ToolLLM: Erleichtert die Beherrschung großer Sprachmodelle von über 16.000 realen APIs. Yujia Qin (Tsinghua-Universität) et al. arXiv. [ Papier ] [ Code ] [ Datensatz ]
ToolLLM ist ein allgemeines Tool-Nutzungs-Framework, das Datenkonstruktion, Modelltraining und -bewertung umfasst.
[2023/05] Große Sprachmodelle als Werkzeugmacher. Tianle Cai (Princeton University) et al. arXiv. [ Papier ] [ Code ]
LATM ist ein Closed-Loop-Framework, das einen ersten Schritt zur Beseitigung der Abhängigkeit von der Verfügbarkeit vorhandener Tools unternimmt.
[2023/05] CREATOR: Abstrakte und konkrete Überlegungen großer Sprachmodelle durch Tool-Erstellung entwirren. Cheng Qian (Tsinghua-Universität) et al. arXiv. [ Papier ]
CREATOR ist ein neuartiges Framework, das es LLMs ermöglicht, ihre eigenen Tools durch Dokumentation und Code-Realisierung zu erstellen.
[2023/04] Tool-Lernen mit Grundlagenmodellen. Yujia Qin (Tsinghua-Universität) et al. arXiv. [ Papier ] [ Code ]
Diese Umfrage stellt in erster Linie ein neues Paradigma namens „Tool-Lernen auf Basis grundlegender Modelle“ vor, das die Vorteile spezialisierter Tools und grundlegender Modelle kombiniert und so eine höhere Präzision, Effizienz und Automatisierung bei der Problemlösung erreicht.
[2023/04] ChemCrow: Erweiterung großer Sprachmodelle mit Chemie-Tools. Andres M Bran (Labor für künstliche chemische Intelligenz, ISIC, EPFL) et al. arXiv. [ Papier ] [ Code ]
ChemCrow ist ein LLM-Chemieagent, der 13 von Experten entwickelte Tools integriert, die LLM-Leistung in der Chemie steigert und neue Fähigkeiten hervorbringt.
[2023/04] GeneGPT: Erweiterung großer Sprachmodelle mit Domänentools für einen verbesserten Zugang zu biomedizinischen Informationen. Qiao Jin (National Institutes of Health), Yifan Yang, Qingyu Chen, Zhiyong Lu. arXiv. [ Papier ] [ Code ]
GeneGPT ist ein Modell, das Fragen zur Genomik beantwortet. Es stellt eine neuartige Methode zur Bewältigung von Herausforderungen mit Halluzinationen vor, indem LLMs die Verwendung der Web-APIs beigebracht werden.
[2023/04] OpenAGI: Wenn LLM Domänenexperten trifft. Yingqiang Ge (Rutgers University) et al. arXiv. [ Papier ] [ Code ]
OpenAGI ist eine Open-Source-AGI-Forschungsplattform. Es stellt ein Paradigma für LLMs vor, die verschiedene Expertenmodelle zur Lösung komplexer Aufgaben betreiben, und schlägt einen RLTF-Mechanismus vor, um die Fähigkeit des LLM zur Aufgabenlösung zu verbessern.
[2023/03] HuggingGPT: KI-Aufgaben lösen mit ChatGPT und seinen Freunden in Hugging Face. Yongliang Shen (Universität Zhejiang) et al. arXiv. [ Papier ] [ Code ]
HuggingGPT ist ein System, das LLMs nutzt, um verschiedene und multimodale KI-Modelle in Communitys für maschinelles Lernen zu verbinden und so KI-Aufgaben zu lösen.
[2023/03] Visual ChatGPT: Sprechen, Zeichnen und Bearbeiten mit Visual Foundation-Modellen. Chenfei Wu (Microsoft Research Asia) et al. arXiv. [ Papier ] [ Code ]
Visual ChatGPT ist ein System, das die Tür zur Untersuchung der visuellen Rollen von ChatGPT mithilfe von Visual Foundation Models öffnet.
[2023/02] Augmented Language Models: eine Umfrage. Grégoire Mialon (Meta AI) et al. TMLR. [ Papier ]
In dieser Umfrage werden Arbeiten überprüft, bei denen LMs um die Fähigkeit erweitert werden, Werkzeuge zu verwenden. Erweiterte LMs können externe Module verwenden, um ihre Kontextverarbeitungsfähigkeiten zu erweitern.
[2023/02] Toolformer: Sprachmodelle können sich selbst den Umgang mit Werkzeugen beibringen. Timo Schick (Meta AI) et al. arXiv. [ Papier ]
Toolformer zeigt anhand einer Handvoll Demonstrationen für jede API, dass LLMs sich selbst beibringen können, externe Tools zu verwenden.
[2022/05] TALM: Tool Augmented Language Models. Aaron Parisi (Google) et al. arXiv. [ Papier ]
TALM führt eine Methode ein, die nicht differenzierbare Tools mit LMs kombiniert und es dem Modell ermöglicht, auf Echtzeit- oder private Daten zuzugreifen.
[2022/05] MRKL Systems: Eine modulare, neurosymbolische Architektur, die große Sprachmodelle, externe Wissensquellen und diskretes Denken kombiniert. Ehud Karpas (AI21 Labs) et al. arXiv. [ Papier ]
MRKL Systems erweitert LLMs durch einen leicht erweiterbaren Satz externer Wissens- und Argumentationsmodule.
[2022/04] Tue, was ich kann, nicht was ich sage: Sprache in Roboterleistungen verankern. Michael Ahn (Google) et al. CoRL. [ Papier ]
SayCan wendet LMs in realen Roboteraufgaben an, indem es fortgeschrittenes semantisches Wissen von LLMs mit der Wertfunktion vorab trainierter Fähigkeiten kombiniert.
[2021/12] WebGPT: Browsergestützte Fragebeantwortung mit menschlichem Feedback. Reiichiro Nakano (OpenAI) et al. arXiv. [ Papier ]
WebGPT beantwortet Fragen mithilfe einer Webbrowser-Umgebung. Es nutzt Nachahmungslernen während des Trainings und optimiert dann die Antwortqualität durch menschliches Feedback.
[2021/07] Evaluierung großer Sprachmodelle, die auf Code trainiert wurden. Mark Chen (OpenAI) et al. arXiv. [ Papier ] [ Code ]
Codex kann Programme aus Dokumentzeichenfolgen synthetisieren, d. h. Tools basierend auf der Dokumentation erstellen.
1.3.2 Verkörperte Aktion
[2023/11] Ein verkörperter generalistischer Agent in der 3D-Welt. Jiangyong Huang (BIGAI & Peking University) et al. arXiv. [ Papier ] [ Projektseite ]
[2023/11] JARVIS-1: Open-World-Multitasking-Agenten mit speichererweiterten multimodalen Sprachmodellen. ZiHao Wang (Universität Peking) et al. arXiv. [ Papier ] [ Code ]
[2023/10] Lemur: Harmonisierung natürlicher Sprache und Code für Sprachagenten Yiheng Xu (Universität Hongkong) et al. arXiv. [ Papier ] [ Code ]
[2023/10] Auf dem Weg zu einer durchgängigen verkörperten Entscheidungsfindung über ein multimodales großes Sprachmodell: Erkundungen mit GPT4-Vision und darüber hinaus Liang Chen et al. arXiv. [ Papier ] [ Code ]
[2023/07] Interaktive Sprache: In Echtzeit mit Robotern sprechen. Corey Lynch et al. IEEE (RAL) [ Papier ]
[2023/05] Voyager: Ein verkörperter Agent mit offenem Ende und großen Sprachmodellen. Guanzhi Wang (NVIDIA) et al. arXiv. [ Papier ] [ Projektseite ] [ Code ]
[2023/05] AVLEN: Audio-visuell-sprachliche verkörperte Navigation in 3D-Umgebungen. Sudipta Paul et al. NeurIPS. [ Papier ]
[2023/05] EmbodiedGPT: Vision-Language-Vorschulung über die verkörperte Gedankenkette. Yao Mu et al. Arxiv [ Papier ] [ Code ]
[2023/05] NavGPT: Explizites Denken in der Vision-and-Language-Navigation mit großen Sprachmodellen. Gengze Zhou et al. Arxiv [ Papier ]
[2023/05] AlphaBlock: Verkörperte Feinabstimmung für Vision-Language Reasoning in der Robotermanipulation. Chuhao Jin et al. Arxiv [ Papier ]
[2023/03] PaLM-E: Ein verkörpertes multimodales Sprachmodell. Danny Driess et al. Arxiv. [ Papier ]
[2023/03] Reflexion: Sprachagenten mit verbalem Verstärkungslernen. Noah Shinn et al. Arxiv [ Papier ] [ Code ]
[2023/02] Zusammenarbeit mit Sprachmodellen für verkörpertes Denken. Ishita Dasgupta et al. Arxiv. [ Papier ]
[2023/02] Code als Richtlinien: Sprachmodellprogramme für verkörperte Kontrolle. Jacky Liang et al. IEEE (ICRA). [ Papier ]
[2022/10] ReAct: Synergie zwischen Denken und Handeln in Sprachmodellen. Shunyu Yao et al. Arxiv [ Papier ] [ Code ]
[2022/10] Befehlsfolgende Agenten mit multimodalem Transformator. Hao Liu et al. CVPR [ Papier ] [ Code ]
[2022/07] Innerer Monolog: Verkörpertes Denken durch Planung mit Sprachmodellen. Wenlong Huang et al. Arxiv. [ Papier ]
[2022/07] LM-Nav: Roboternavigation mit großen vortrainierten Modellen für Sprache, Vision und Aktion. Dhruv Shahet al. CoRL [ Papier ] [ Code ]
[2022/04] Tue, was ich kann, nicht was ich sage: Sprache in Roboterleistungen verankern. Michael Ahn et al. Arxiv. [ Papier ]
[2022/01] Ein Überblick über verkörperte KI: Von Simulatoren zu Forschungsaufgaben. Jiafei Duan et al. IEEE (TETCI). [ Papier ]
[2022/01] Sprachmodelle als Zero-Shot-Planer: Extrahieren von umsetzbarem Wissen für verkörperte Agenten. Wenlong Huang et al. Arxiv. [ Papier ] [ Code ]
[2020/04] Experience Grounds Language. Yonatan Bisk et al. EMNLP [ Papier ]
[2019/03] Rückblick auf Deep Reinforcement Learning zur Robotermanipulation. Hai Nguyen et al. IEEE (IRC). [ Papier ]
[2005/01] Die Entwicklung der verkörperten Kognition: Sechs Lektionen von Babys. Linda Smith et al. Künstliches Leben. [ Papier ]
2. Agenten in der Praxis: Anwendungen von LLM-basierten Agenten

2.1 Allgemeine Fähigkeiten eines Einzelagenten

2.1.1 Aufgabenorientierte Bereitstellung
In Webszenarien

[2023/10] OpenAgents: Eine offene Plattform für Sprachagenten in freier Wildbahn. XLang Lab (Universität Hongkong) arXiv. [ Papier ] [ Projektseite ] [ Code ] [ Demo ]
[2023/07] WebArena: Eine realistische Webumgebung zum Aufbau autonomer Agenten. Shuyan Zhou (CMU) et al. arXiv. [ Papier ] [ Code ]
[2023/07] Ein realer WebAgent mit Planung, umfassendem Kontextverständnis und Programmsynthese. Izzeddin Gur (DeepMind) et al. arXiv. [ Papier ]
[2023/06] SYNAPSE: Nutzung von Few-Shot-Exemplaren für die Computersteuerung auf menschlicher Ebene. Longtao Zheng (Nanyang Technological University) et al. arXiv. [ Papier ] [ Code ]
[2023/06] Mind2Web: Auf dem Weg zu einem generalistischen Agenten für das Web. Xiang Deng (Ohio State University) et al. arXiv. [ Papier ] [ Code ]
[2023/05] Multimodale Webnavigation mit durch Anweisungen abgestimmten Grundlagenmodellen. Hiroki Furuta (Universität Tokio) et al. arXiv. [ Papier ]
[2023/03] Sprachmodelle können Computeraufgaben lösen. Geunwoo Kim (University of California) et al. arXiv. [ Papier ] [ Code ]
[2022/07] WebShop: Auf dem Weg zu einer skalierbaren realen Webinteraktion mit Grounded Language Agents. Shunyu Yao (Princeton University) et al. arXiv. [ Papier ] [ Code ]
[2021/12] WebGPT: Browsergestützte Fragebeantwortung mit menschlichem Feedback. Reiichiro Nakano (OpenAI) et al. arXiv. [ Papier ]
[2023/05] Agenten: Ein Open-Source-Framework für autonome Sprachagenten. Wangchunshu Zhou (AIWaves) et al. arXiv. [ Papier ] [ Code ]
In Lebensszenarien

[2023/10] OpenAgents: Eine offene Plattform für Sprachagenten in freier Wildbahn. XLang Lab (Universität Hongkong) arXiv. [ Papier ] [ Projektseite ] [ Code ] [ Demo ]
[2023/08] InterAct: Erkundung der Potenziale von ChatGPT als kooperativer Agent. Po-Lin Chen et al. arXiv. [ Papier ]
[2023/05] Planen, eliminieren und verfolgen – Sprachmodelle sind gute Lehrer für verkörperte Agenten. Yue Wu (CMU) et al. arXiv. [ Papier ]
[2023/05] Erweiterung autotelischer Agenten mit großen Sprachmodellen. Cédric Colas (MIT) et al. arXiv. [ Papier ]
[2023/03] Planung mit großen Sprachmodellen durch korrigierendes Re-Prompting. Shreyas Sundara Raman (Brown University) et al. arXiv. [ Papier ]
[2022/10] Generierung ausführbarer Aktionspläne mit umweltbewussten Sprachmodellen. Maitrey Gramopadhye (University of North Carolina at Chapel Hill) et al. arXiv. [ Papier ] [ Code ]
[2022/01] Sprachmodelle als Zero-Shot-Planer: Extrahieren von umsetzbarem Wissen für verkörperte Agenten. Wenlong Huang (UC Berkeley) et al. arXiv. [ Papier ] [ Code ]
2.1.2 Innovationsorientierter Einsatz
[2023/10] OpenAgents: Eine offene Plattform für Sprachagenten in freier Wildbahn. XLang Lab (Universität Hongkong) arXiv. [ Papier ] [ Projektseite ] [ Code ] [ Demo ]
[2023/08] Per Anhalter zur Programmanalyse: Eine Reise mit großen Sprachmodellen. Haonan Li (UC Riverside) et al. arXiv. [ Papier ]
[2023/08] ChatMOF: Ein autonomes KI-System zur Vorhersage und Generierung metallorganischer Gerüste. Yeonghun Kang (Korea Advanced Institute of Science and Technology) et al. arXiv. [ Papier ]
[2023/07] Mathe-Agenten: Computerinfrastruktur, mathematische Einbettung und Genomik. Melanie Swan (University College London) et al. arXiv. [ Papier ]
[2023/06] Auf dem Weg zu autonomen Testagenten über konversationale große Sprachmodelle. Robert Feldt (Chalmers University of Technology) et al. arXiv. [ Papier ]
[2023/04] Neue autonome wissenschaftliche Forschungsfähigkeiten großer Sprachmodelle. Daniil A. Boiko (CMU) et al. arXiv. [ Papier ]
[2023/04] ChemCrow: Erweiterung großer Sprachmodelle mit Chemie-Tools. Andres M Bran (Labor für künstliche chemische Intelligenz, ISIC, EPFL) et al. arXiv. [ Papier ] [ Code ]
[2022/03] ScienceWorld: Ist Ihr Agent schlauer als ein Fünftklässler? Ruoyao Wang (Universität von Arizona) et al. arXiv. [ Papier ] [ Code ]
2.1.3 Lebenszyklusorientierte Bereitstellung
[2023/05] Voyager: Ein verkörperter Agent mit offenem Ende und großen Sprachmodellen. Guanzhi Wang (NVIDIA) et al. arXiv. [ Papier ] [ Projektseite ] [ Code ]
[2023/05] Ghost in the Minecraft: Generell leistungsfähige Agenten für Open-World-Umgebungen über große Sprachmodelle mit textbasiertem Wissen und Gedächtnis. Xizhou Zhu (Tsinghua-Universität) et al. arXiv. [ Papier ] [ Code ]
[2023/03] Plan4MC: Lernen und Planen zur Kompetenzverstärkung für Open-World-Minecraft-Aufgaben. Haoqi Yuan (PKU) et al. arXiv. [ Papier ] [ Projektseite ]
[2023/02] Beschreiben, erklären, planen und auswählen: Interaktive Planung mit großen Sprachmodellen ermöglicht Open-World-Multitasking-Agenten. Zihao Wang (PKU) et al. arXiv. [ Papier ] [ Code ]
[2023/01] Träumen verkörperte Agenten von pixeligen Schafen: Verkörperte Entscheidungsfindung mithilfe sprachgesteuerter Weltmodellierung. Kolby Nottingham (University of California Irvine, Irvine) et al. arXiv. [ Papier ] [ Code ]
2.2 Koordinierungspotential mehrerer Agenten

2.2.1 Kooperative Interaktion für Komplementarität
Ungeordnete Zusammenarbeit

[2023/07] Freisetzung kognitiver Synergien in großen Sprachmodellen: Ein Agent zur Aufgabenlösung durch Selbstzusammenarbeit mehrerer Personen. Zhenhailong Wang (University of Illinois Urbana-Champaign) et al. arXiv. [ Papier ] [ Code ]
[2023/07] RoCo: Dialektische Multi-Roboter-Kollaboration mit großen Sprachmodellen. Zhao Mandi, Shreeya Jain, Shuran Song (Columbia University) et al. arXiv. [ Papier ] [ Code ]
[2023/04] ChatLLM-Netzwerk: Mehr Gehirne, mehr Intelligenz. Rui Hao (Universität für Post und Telekommunikation Peking) et al. arXiv. [ Papier ]
[2023/01] Blindes Urteil: Agentenbasierte Modellierung des Obersten Gerichtshofs mit GPT. Sil Hamilton (McGill University). arXiv. [ Papier ]
[2023/05] Agenten: Ein Open-Source-Framework für autonome Sprachagenten. Wangchunshu Zhou (AIWaves) et al. arXiv. [ Papier ] [ Code ]
Geordnete Zusammenarbeit

[2023/10] AutoAgents: Ein Framework für die automatische Agentengenerierung. Guangyao Chen (Universität Peking) et al. arXiv. [ Papier ] [ Code ]
[2023/09] MindAgent: Neue Gaming-Interaktion. Ran Gong (UCLA) et al. arXiv. [ Papier ] [ Code ]
[2023/08] CGMI: Konfigurierbares allgemeines Multi-Agent-Interaktions-Framework. Shi Jinxin (East China Normal University) et al. arXiv. [ Papier ]
[2023/08] ProAgent: Aufbau einer proaktiven kooperativen KI mit großen Sprachmodellen. Ceyao Zhang (Chinesische Universität Hongkong, Shenzhen) et al. arXiv. [ Papier ] [ Code ]
[2023/08] AgentVerse: Erleichterung der Zusammenarbeit mehrerer Agenten und Erforschung neu auftretender Verhaltensweisen bei Agenten. Weize Chen (Tsinghua-Universität) et al. arXiv. [ Papier ] [ Code ]
[2023/08] AutoGen: Ermöglichung von LLM-Anwendungen der nächsten Generation über das Multi-Agent Conversation Framework. Qingyun Wu (Pennsylvania State University) et al. arXiv. [ Papier ] [ Code ]
[2023/08] MetaGPT: Metaprogrammierung für das Multi-Agent Collaborative Framework. Sirui Hong (DeepWisdom) et al. arXiv. [ Papier ] [ Code ]
[2023/07] Kommunikative Agenten für die Softwareentwicklung. Chen Qian (Tsinghua-Universität) et al. arXiv. [ Papier ] [ Code ]
[2023/06] Multi-Agenten-Zusammenarbeit: Die Leistungsfähigkeit intelligenter LLM-Agenten nutzen. Yashar Talebira (Universität Alberta) et al. arXiv. [ Papier ]
[2023/05] Training sozial ausgerichteter Sprachmodelle in der simulierten menschlichen Gesellschaft. Ruibo Liu (Dartmouth College) et al. arXiv. [ Papier ] [ Code ]
[2023/05] SwiftSage: Ein generativer Agent mit schnellem und langsamem Denken für komplexe interaktive Aufgaben. Bill Yuchen Lin (Allen Institute for Artificial Intelligence) et al. arXiv. [ Papier ] [ Code ]
[2023/05] ChatGPT als Ihr Personal Data Scientist. Md Mahadi Hassan (Auburn University) et al. arXiv. [ Papier ]
[2023/03] CAMEL: Kommunikative Mittel zur „Geistes“-Erforschung einer groß angelegten Sprachmodellgesellschaft. Guohao Li (King Abdullah University of Science and Technology) et al. arXiv. [ Papier ] [ Code ]
[2023/03] DERA: Verbesserung der Vervollständigung großer Sprachmodelle mit dialogfähigen Auflösungsagenten. Varun Nair (Curai Health) et al. arXiv. [ Papier ] [ Code ]
[2023/04] Selbstkollaborative Codegenerierung über ChatGPT. Yihong Dong (Universität Peking) et al. arXiv. [ Papier ]
2.2.2 Gegnerische Interaktion für den Fortschritt
[2023/08] ChatEval: Auf dem Weg zu besseren LLM-basierten Evaluatoren durch Multi-Agent-Debatte. Chi-Min Chan (Tsinghua-Universität) et al. arXiv. [ Papier ] [ Code ]
[2023/05] Verbesserung der Faktizität und Argumentation in Sprachmodellen durch Multiagentendebatte. Yilun Du (MIT CSAIL) et al. arXiv. [ Papier ] [ Code ]
[2023/05] Verbesserung der Sprachmodellverhandlung durch Selbstspiel und kontextbezogenes Lernen aus KI-Feedback. Yao Fu (Universität Edinburgh) et al. arXiv. [ Papier ] [ Code ]
[2023/05] Untersuchung der Interkonsistenz großer Sprachmodelle: Eine eingehende Analyse mittels Debatte. Kai Xiong (Harbin Institute of Technology) et al. arXiv. [ Papier ]
[2023/05] Divergentes Denken in großen Sprachmodellen durch Multi-Agenten-Debatte fördern. Tian Liang (Tsinghua-Universität) et al. arXiv. [ Papier ] [ Code ]
2.3 Interaktive Interaktion zwischen Mensch und Agent

2.3.1 Instructor-Executor-Paradigma
Ausbildung
[2023/07] Mathe-Agenten: Computerinfrastruktur, mathematische Einbettung und Genomik. Melanie Swan (UCL) et al. arXiv. [ Papier ]
Kommunizieren Sie mit Menschen, um ihnen zu helfen, Mathematik zu verstehen und anzuwenden.
[2023/03] Hey Dona! Können Sie mir bei der Kursanmeldung für Studierende helfen? Vishesh Kalvakurthi (MSU) et al. arXiv. [ Papier ]
Hierbei handelt es sich um eine entwickelte Anwendung namens Dona, die virtuelle Sprachunterstützung bei der Kursanmeldung für Studierende bietet, bei der Menschen Anweisungen geben.
Gesundheit
[2023/08] Zhongjing: Verbesserung der chinesischen medizinischen Fähigkeiten eines großen Sprachmodells durch Experten-Feedback und realen Multi-Turn-Dialog. Songhua Yang (ZZU) et al. arXiv. [ Papier ] [ Code ]
[2023/05] HuatuoGPT, auf dem Weg, das Sprachmodell zu zähmen, um Arzt zu werden. Hongbo Zhang (CUHK-SZ) et al. arXiv. [ Papier ] [ Code ] [ Demo ]
[2023/05] Dem Helfer helfen: Unterstützung von Peer-Beratern durch KI-gestützte Praxis und Feedback. Shang-Ling Hsu (Gatech) et al. arXiv. [ Papier ]
[2020/10] Ein virtueller Gesprächsagent für Jugendliche mit Autismus-Spektrum-Störung: Experimentelle Ergebnisse und Design-Lektionen. Mohammad Rafayet Ali (U of R) et al. IVA '20. [ Papier ]
Andere Anwendung
[2023/08] RecMind: Großer Sprachmodell-basierter Agent für Empfehlungen. Yancheng Wang (ASU, Amazon) et al. arXiv. [ Papier ]
[2023/08] Multi-Turn-Dialogagent als Vertriebsassistent im Telemarketing. Wanting Gao (JNU) et al. IEEE. [ Papier ]
[2023/07] PEER: Ein kollaboratives Sprachmodell. Timo Schick (Meta AI) et al. arXiv. [ Papier ]
[2023/07] DIALGEN: Kollaborative von Mensch und LM generierte Dialoge für ein besseres Verständnis von Mensch-Mensch-Gesprächen. Bo-Ru Lu (UW) et al. arXiv. [ Papier ]
[2023/06] AssistGPT: Ein allgemeiner multimodaler Assistent, der planen, ausführen, prüfen und lernen kann. Difei Gao (NUS) et al. arXiv. [ Papier ]
[2023/05] Agenten: Ein Open-Source-Framework für autonome Sprachagenten. Wangchunshu Zhou (AIWaves) et al. arXiv. [ Papier ] [ Code ]
2.3.2 Paradigma der gleichberechtigten Partnerschaft
Einfühlsamer Kommunikator
[2023/08] SAPIEN: Affektive virtuelle Agenten, die auf großen Sprachmodellen basieren. Masum Hasan et al. arXiv. [ Papier ] [ Projektseite ]
[2023/05] Dem Helfer helfen: Unterstützung von Peer-Beratern durch KI-gestützte Praxis und Feedback. Shang-Ling Hsu (Gatech) et al. arXiv. [ Papier ]
[2022/07] Künstliche Empathie in Marketinginteraktionen: Überbrückung der Lücke zwischen Mensch und KI im affektiven und sozialen Kundenerlebnis. Yuping Liu-Thompkins et al. [ Papier ]
Teilnehmer auf menschlicher Ebene
[2023/08] Quantifizierung des Einflusses großer Sprachmodelle auf die kollektive Meinungsdynamik. Chao Li et al. AdR. [ Papier ]
[2023/06] Das Spiel der No-Press-Diplomatie durch vom Menschen reguliertes Verstärkungslernen und -planung meistern. Anton Bakhtin et al. ICLR. [ Papier ]
[2023/06] Entscheidungsorientierter Dialog für die Zusammenarbeit zwischen Mensch und KI. Jessy Lin et al. AdR. [ Papier ]
[2022/11] Spielen auf menschlicher Ebene im Spiel der Diplomatie durch die Kombination von Sprachmodellen mit strategischem Denken. FAIR et al. Wissenschaft. [ Papier ]
3. Agentengesellschaft: Von der Individualität zur Sozialität

3.1 Verhalten und Persönlichkeit von LLM-basierten Agenten
3.1.1 Sozialverhalten
Individuelle Verhaltensweisen
[2023/10] Lyfe Agents: Generative Agenten für kostengünstige soziale Interaktionen in Echtzeit. Zhao Kaiya (MIT) et al. arXiv. [ Papier ]
[2023/05] Voyager: Ein verkörperter Agent mit offenem Ende und großen Sprachmodellen. Guanzhi Wang (NVIDIA) et al. arXiv. [ Papier ] [ Code ] [ Projektseite ]
[2023/04] LLM+P: Unterstützung großer Sprachmodelle durch optimale Planungskompetenz. Bo Liu (Universität von Texas) et al. arXiv. [ Papier ] [ Code ]
[2023/03] Reflexion: Sprachagenten mit verbalem Verstärkungslernen. Noah Shinn (Northeastern University) et al. arXiv. [ Papier ] [ Code ]
[2023/03] PaLM-E: Ein verkörpertes multimodales Sprachmodell. Danny Driess (Google) et al. ICML. [ Papier ] [ Projektseite ]
[2023/03] ReAct: Synergie von Denken und Handeln in Sprachmodellen. Shunyu Yao (Princeton University) et al. ICLR. [ Papier ] [ Projektseite ]
[2022/01] Die Aufforderung zur Gedankenkette löst Argumentation in großen Sprachmodellen aus. Jason Wei (Google) et al. NeurIPS. [ Papier ]
Gruppenverhalten
[2023/10] Erforschung von Kooperationsmechanismen für LLM-Agenten: Eine sozialpsychologische Sicht. Jintian Zhang (Universität Zhejiang) et al. arXiv. [ Papier ] [ Code ]

[2023/09] MindAgent: Neue Gaming-Interaktion. Ran Gong (UCLA) et al. arXiv. [ Papier ] [ Code ]

[2023/09] Erforschung großer Sprachmodelle für Kommunikationsspiele: Eine empirische Studie über Werwolf. Yuzhuang Xu (Tsinghua-Universität) et al. arXiv. [ Papier ]

[2023/09] Suspicion Agent: Unvollkommene Informationsspiele mit Theory of Mind Aware spielen GPT-4 Jiaxian Gu oet al. arXiv. [ Papier ]

[2023/08] AgentVerse: Erleichterung der Zusammenarbeit mehrerer Agenten und Erforschung neu auftretender Verhaltensweisen bei Agenten. Weize Chen (Tsinghua-Universität) et al. arXiv. [ Papier ] [ Code ]

[2023/08] AutoGen: Ermöglichung von LLM-Anwendungen der nächsten Generation über das Multi-Agent Conversation Framework. Qingyun Wu (Pennsylvania State University) et al. arXiv. [ Papier ] [ Code ]

[2023/08] ChatEval: Auf dem Weg zu besseren LLM-basierten Evaluatoren durch Multi-Agent-Debatte. Chi-Min Chan (Tsinghua-Universität) et al. arXiv. [ Papier ] [ Code ]

[2023/07] Kommunikative Agenten für die Softwareentwicklung. Chen Qian (Tsinghua-Universität) et al. arXiv. [ Papier ] [ Code ]

[2023/07] RoCo: Dialektische Multi-Roboter-Kollaboration mit großen Sprachmodellen. Zhao Mandi, Shreeya Jain, Shuran Song (Columbia University) et al. arXiv. [ Papier ] [ Code ]

[2023/08] ProAgent: Aufbau einer proaktiven kooperativen KI mit großen Sprachmodellen. Ceyao Zhang (Chinesische Universität Hongkong, Shenzhen) et al. arXiv. [ Papier ] [ Code ]

3.1.2 Persönlichkeit
Erkenntnis
[2023/09] Suspicion Agent: Unvollkommene Informationsspiele mit Theory of Mind Aware spielen GPT-4 Jiaxian Gu oet al. arXiv. [ Papier ]
[2023/03] Maschinenpsychologie: Untersuchung neuer Fähigkeiten und Verhaltensweisen in großen Sprachmodellen mit psychologischen Methoden. Thilo Hagendorff (Universität Stuttgart) et al. arXiv. [ Papier ]
[2023/03] Geist trifft Maschine: Die kognitive Psychologie von GPT-4 enträtseln. Sifatkaur Dhingra (Nowrosjee Wadia College) et al. arXiv. [ Papier ]
[2022/07] Sprachmodelle zeigen menschenähnliche inhaltliche Auswirkungen auf das Denken. Ishita Dasgupta (DeepMind) et al. arXiv. [ Papier ]
[2022/06] Nutzung der kognitiven Psychologie zum Verständnis von GPT-3. Marcel Binz et al. arXiv. [ Papier ]
Emotion
[2023/07] Emotionale Intelligenz großer Sprachmodelle. Xuena Wang (Tsinghua-Universität) et al. arXiv. [ Papier ]
[2023/05] ChatGPT übertrifft Menschen bei der Bewertung des emotionalen Bewusstseins. Zohar Elyoseph et al. Grenzen in der Psychologie. [ Papier ]
[2023/02] Empathische KI zur Stärkung der Resilienz in Spielen. Reza Habibi (University of California) et al. arXiv. [ Papier ]
[2022/12] Computer sagt „Nein“: Das Argument gegen empathische Konversations-KI. Alba Curry (Universität Leeds) et al. ACL. [ Papier ]
Charakter
[2023/10] Character-LLM: Ein trainierbarer Agent für Rollenspiele. Yunfan Shao (Fudan-Universität) et al. arXiv. [ Papier ] [ Code ]
[2023/07] Besitzen LLMs eine Persönlichkeit? Machen Sie den MBTI-Test zu einer erstaunlichen Bewertung für große Sprachmodelle. Keyu Pan (ByteDance) et al. arXiv. [ Papier ] [ Code ]
[2023/07] Persönlichkeitsmerkmale in großen Sprachmodellen. Mustafa Safdari (DeepMind) et al. arXiv. [ Papier ] [ Code ]
[2022/12] Zeigt GPT-3 Psychopathie? Bewertung großer Sprachmodelle aus psychologischer Sicht. Xingxuan Li (Alibaba) et al. arXiv. [ Papier ]
[2022/12] Identifizierung und Manipulation der Persönlichkeitsmerkmale von Sprachmodellen. Graham Caron et al. arXiv. [ Papier ]
3.2 Umgebung für die Agentengesellschaft
3.2.1 Textbasierte Umgebung
[2023/08] Hoodwinked: Täuschung und Kooperation in einem textbasierten Spiel für Sprachmodelle. Aidan O'Gara (University of Southern California) et al. arXiv. [ Papier ] [ Code ]
[2023/03] CAMEL: Kommunikative Mittel zur „Geistes“-Erforschung einer groß angelegten Sprachmodellgesellschaft. Guohao Li (King Abdullah University of Science and Technology) et al. arXiv. [ Papier ] [ Code ]
[2020/12] Textbasierte Spiele mit gesundem Menschenverstand spielen. Sahith Dambekodi (Georgia Institute of Technology) et al. arXiv. [ Papier ]
[2019/09] Interaktive Fiction-Spiele: Ein kolossales Abenteuer. Matthew Hausknecht (Microsoft Research) et al. AAAI. [ Papier ] [ Code ]
[2019/03] Sprechen und Handeln lernen in einem Fantasy-Text-Abenteuerspiel. Jack Urbanek (Facebook) et al. ACL. [ Papier ] [ Code ]
[2018/06] TextWorld: Eine Lernumgebung für textbasierte Spiele. Marc-Alexandre Côté (Microsoft Research) et al. IJCAI. [ Papier ] [ Code ]
3.2.2 Virtuelle Sandbox-Umgebung
[2023/11] JARVIS-1: Open-World-Multitasking-Agenten mit speichererweiterten multimodalen Sprachmodellen. ZiHao Wang (Universität Peking) et al. arXiv. [ Papier ] [ Code ]
[2023/10] Humanoid Agents: Plattform zur Simulation menschenähnlicher generativer Agenten. Zhilin Wang (University of Washington und NVIDIA) et al. arXiv. [ Papier ] [ Code ] [ Demo ]
[2023/08] AgentSims: Eine Open-Source-Sandbox für die Evaluierung großer Sprachmodelle. Jiaju Lin (PTA Studio) et al. arXiv. [ Papier ] [ Projektseite ] [ Code ]
[2023/05] Training sozial ausgerichteter Sprachmodelle in der simulierten menschlichen Gesellschaft. Ruibo Liu (Dartmouth College) et al. arXiv. [ Papier ] [ Code ]
[2023/05] Voyager: Ein verkörperter Agent mit offenem Ende und großen Sprachmodellen. Guanzhi Wang (NVIDIA) et al. arXiv. [ Papier ] [ Projektseite ] [ Code ]
[2023/04] Generative Agenten: Interaktive Simulakren menschlichen Verhaltens. Joon Sung Park (Stanford University) et al. arXiv. [ Papier ] [ Code ]
[2023/03] Plan4MC: Lernen und Planen zur Kompetenzverstärkung für Open-World-Minecraft-Aufgaben. Haoqi Yuan (PKU) et al. arXiv. [ Papier ] [ Projektseite ]
[2022/06] MineDojo: Aufbau offener verkörperter Agenten mit Wissen im Internetmaßstab. Linxi Fan (NVIDIA) et al. NeurIPS. [ Papier ] [ Projektseite ]
3.2.3 Physische Umgebung
[2023/11] Ein verkörperter generalistischer Agent in der 3D-Welt. Jiangyong Huang (BIGAI & Peking University) et al. arXiv. [ Papier ] [ Projektseite ]
[2023/09] RoboAgent: Generalisierung und Effizienz in der Robotermanipulation durch semantische Augmentationen und Action Chunking. Homanga Bharadhwaj (Carnegie Mellon University) et al. arXiv. [ Papier ] [ Projektseite ]
[2023/05] AVLEN: Audio-visuell-sprachliche verkörperte Navigation in 3D-Umgebungen. Sudipta Paul et al. NeurIPS. [ Papier ]
[2023/03] PaLM-E: Ein verkörpertes multimodales Sprachmodell. Danny Driess (Google) et al. ICML. [ Papier ] [ Projektseite ]
[2022/10] Interaktive Sprache: In Echtzeit mit Robotern sprechen. Corey Lynch (Google) et al. arXiv. [ Papier ] [ Code ]
3.3 Gesellschaftssimulation mit LLM-basierten Agenten
[2023/08] AgentSims: Eine Open-Source-Sandbox für die Evaluierung großer Sprachmodelle. Jiaju Lin (PTA Studio) et al. arXiv. [ Papier ] [ Projektseite ] [ Code ]
[2023/07] S 3 : Simulationssystem für soziale Netzwerke mit durch große Sprachmodelle unterstützten Agenten. Chen Gao (Tsinghua-Universität) et al. arXiv. [ Papier ]
[2023/07] Epidemiemodellierung mit generativen Agenten. Ross Williams (Virginia Tech) et al. arXiv. [ Papier ] [ Code ]
[2023/06] RecAgent: Ein neuartiges Simulationsparadigma für Empfehlungssysteme. Lei Wang (Renmin-Universität China) et al. arXiv. [ Papier ]
[2023/05] Training sozial ausgerichteter Sprachmodelle in der simulierten menschlichen Gesellschaft. Ruibo Liu (Dartmouth College) et al. arXiv. [ Papier ] [ Code ]
[2023/04] Generative Agenten: Interaktive Simulakren menschlichen Verhaltens. Joon Sung Park (Stanford University) et al. arXiv. [ Papier ] [ Code ]
[2022/08] Social Simulacra: Erstellung bevölkerter Prototypen für Social Computing-Systeme. Joon Sung Park (Stanford University) et al. UIST. [ Papier ]
