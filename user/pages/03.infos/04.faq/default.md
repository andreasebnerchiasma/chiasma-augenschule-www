---
title: "FAQ"
menu: "FAQ"
visible: true
process:
    markdown: true
    twig: true
---

<!-- ===================== HERO ===================== -->
<div class="imp-hero">
    <div class="imp-hero-bg"></div>
    <div class="imp-hero-content">
        <h1 class="animate-pop-in">Häufige Fragen</h1>
        <p class="animate-slide-up">Alles, was Sie über Sehtraining & Optometrie wissen möchten</p>
    </div>
</div>

<!-- ===================== SECTION NAV ===================== -->
<div class="faq-section-nav">
    <a href="#ablauf" class="faq-nav-card">
        <div class="faq-nav-icon">
            <svg viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                <rect x="8" y="8" width="48" height="56" rx="6" stroke="currentColor" stroke-width="3" fill="none"/>
                <path d="M20 8 v-4 a4 4 0 0 1 8 0 v4" stroke="currentColor" stroke-width="3" stroke-linecap="round"/>
                <path d="M36 8 v-4 a4 4 0 0 1 8 0 v4" stroke="currentColor" stroke-width="3" stroke-linecap="round"/>
                <line x1="18" y1="28" x2="46" y2="28" stroke="currentColor" stroke-width="3" stroke-linecap="round"/>
                <line x1="18" y1="38" x2="38" y2="38" stroke="currentColor" stroke-width="3" stroke-linecap="round"/>
                <line x1="18" y1="48" x2="30" y2="48" stroke="currentColor" stroke-width="3" stroke-linecap="round"/>
                <circle cx="50" cy="50" r="10" fill="#c4d04f" stroke="none"/>
                <text x="50" y="54" text-anchor="middle" fill="white" font-size="12" font-weight="bold">€</text>
            </svg>
        </div>
        <span class="faq-nav-label">Ablauf &amp; Kosten</span>
        <span class="faq-nav-count" id="count-ablauf">6 Fragen</span>
    </a>

    <a href="#allgemeine" class="faq-nav-card">
        <div class="faq-nav-icon">
            <svg viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M8 12 Q8 6 14 6 H50 Q56 6 56 12 V38 Q56 44 50 44 H38 L28 58 L26 44 H14 Q8 44 8 38 Z" stroke="currentColor" stroke-width="3" fill="none" stroke-linejoin="round"/>
                <circle cx="32" cy="20" r="3" fill="currentColor"/>
                <path d="M32 26 V34" stroke="currentColor" stroke-width="3" stroke-linecap="round"/>
            </svg>
        </div>
        <span class="faq-nav-label">Allgemeine Fragen</span>
        <span class="faq-nav-count" id="count-allgemeine">8 Fragen</span>
    </a>

    <a href="#optometrie" class="faq-nav-card">
        <div class="faq-nav-icon">
            <svg viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M4 32 C12 14 22 8 32 8 C42 8 52 14 60 32 C52 50 42 56 32 56 C22 56 12 50 4 32 Z" stroke="currentColor" stroke-width="3" fill="none"/>
                <circle cx="32" cy="32" r="10" stroke="currentColor" stroke-width="3" fill="none"/>
                <circle cx="32" cy="32" r="4" fill="#c4d04f"/>
                <line x1="32" y1="8" x2="32" y2="14" stroke="currentColor" stroke-width="2" stroke-linecap="round"/>
                <line x1="32" y1="50" x2="32" y2="56" stroke="currentColor" stroke-width="2" stroke-linecap="round"/>
            </svg>
        </div>
        <span class="faq-nav-label">Grundlagen Optometrie</span>
        <span class="faq-nav-count" id="count-optometrie">6 Fragen</span>
    </a>
</div>

<!-- ===================== SECTION 1: ABLAUF & KOSTEN ===================== -->
<div class="faq-wrapper">
    <section id="ablauf" class="faq-section">
        <div class="faq-section-header faq-header-green">
            <div class="faq-section-icon-small">
                <svg viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <rect x="8" y="8" width="48" height="56" rx="6" stroke="white" stroke-width="3" fill="none"/>
                    <line x1="18" y1="28" x2="46" y2="28" stroke="white" stroke-width="3" stroke-linecap="round"/>
                    <line x1="18" y1="38" x2="38" y2="38" stroke="white" stroke-width="3" stroke-linecap="round"/>
                    <line x1="18" y1="48" x2="30" y2="48" stroke="white" stroke-width="3" stroke-linecap="round"/>
                </svg>
            </div>
            <div>
                <h2>Ablauf &amp; Kosten</h2>
                <p>Von der ersten Messung bis zum laufenden Training</p>
            </div>
        </div>

        <div class="faq-accordion">

            <div class="faq-item">
                <button class="faq-question" onclick="toggleFaq(this)">
                    <span>Welche Voraussetzungen gibt es vor dem Training?</span>
                    <span class="faq-icon">+</span>
                </button>
                <div class="faq-answer">
                    <p>Bevor wir gemeinsam mit einem Training beginnen, sollte jedes Kind augenärztlich untersucht worden sein. Erste Hinweise kommen häufig aus der Schule oder fallen auf, wenn ein Kind eingeschult wird. Mögliche organische Ursachen müssen vorab durch einen Augenarzt und – je nach Befund – durch einen Neurologen abgeklärt werden. Erst wenn eine medizinische Grunderkrankung ausgeschlossen ist, kann ein funktionelles Sehtraining wirklich greifen.</p>
                </div>
            </div>

            <div class="faq-item">
                <button class="faq-question" onclick="toggleFaq(this)">
                    <span>Wie vereinbare ich einen Termin?</span>
                    <span class="faq-icon">+</span>
                </button>
                <div class="faq-answer">
                    <p>Die Terminvergabe ist auf verschiedenen Wegen möglich:</p>
                    <ul class="faq-list">
                        <li>Über das <a href="/kontakt" class="imp-link">Kontaktformular</a> auf dieser Website</li>
                        <li>Telefonisch – hinterlassen Sie gerne eine Nachricht auf dem Anrufbeantworter, ich rufe zurück</li>
                        <li>Per E-Mail</li>
                        <li>Per Nachricht über Signal Messenger (gleiche Telefonnummer)</li>
                    </ul>
                </div>
            </div>

            <div class="faq-item">
                <button class="faq-question" onclick="toggleFaq(this)">
                    <span>Wie läuft die Eingangsanalyse ab?</span>
                    <span class="faq-icon">+</span>
                </button>
                <div class="faq-answer">
                    <p>Die Eingangsanalyse umfasst zwei aufeinander aufbauende Messungen, die zusammen ca. 3 Stunden dauern:</p>
                    <div class="faq-two-col">
                        <div class="faq-infobox faq-infobox-green">
                            <h4>Optometrische Messung <span class="faq-badge">ca. 90 Min.</span></h4>
                            <ul>
                                <li>Funktionelle Brillenbestimmung</li>
                                <li>Blickmotorik</li>
                                <li>Messung der Binokularität</li>
                                <li>Fusionsbreite</li>
                                <li>Akkommodation</li>
                            </ul>
                        </div>
                        <div class="faq-infobox faq-infobox-grey">
                            <h4>Visuo-kognitive Tests <span class="faq-badge">ca. 90 Min.</span></h4>
                            <ul>
                                <li>Blickmotorik beim Lesen</li>
                                <li>Raum-Lage-Wahrnehmung</li>
                                <li>Visuelles Gedächtnis</li>
                                <li>Visuo-motorische Verarbeitung</li>
                                <li>Individuelle Wahrnehmungstests</li>
                            </ul>
                        </div>
                    </div>
                    <p>Im Anschluss erhalten Sie einen ausführlichen Befundbericht mit individuellem Trainingsplan – verständlich formuliert und geeignet als Grundlage für Gespräche mit Lehrkräften oder behandelnden Ärzten.</p>
                </div>
            </div>

            <div class="faq-item">
                <button class="faq-question" onclick="toggleFaq(this)">
                    <span>Wie geht es nach der Eingangsanalyse weiter?</span>
                    <span class="faq-icon">+</span>
                </button>
                <div class="faq-answer">
                    <p>Nach der Eingangsanalyse erhalten Sie einen schriftlichen Bericht, in dem alle Ergebnisse klar und verständlich dokumentiert sind. Gemeinsam besprechen wir daraufhin den individuellen Trainingsplan.</p>
                    <p>In der Regel sehe ich Kinder einmal pro Woche – wahlweise vor Ort in der Augenschule oder bequem per Videokonferenz. Nach jeder Sitzung erhalten Sie gezielte Hausaufgaben für die folgende Woche. In den Terminen überprüfe ich die Fortschritte und passe die Übungen laufend an die aktuelle Entwicklung an. Einige Kinder erhalten außerdem Zugang zu Online-Trainingstools, bei denen ich den Übungsverlauf in Echtzeit verfolgen kann. Nach einer definierten Trainingsphase findet zudem eine umfassende Verlaufskontrolle statt.</p>
                    <p><em>Auf Wunsch spreche ich auch direkt mit der Schule.</em></p>
                </div>
            </div>

            <div class="faq-item faq-item-highlight">
                <button class="faq-question" onclick="toggleFaq(this)">
                    <span>Was kostet das Training?</span>
                    <span class="faq-icon">+</span>
                </button>
                <div class="faq-answer">
                    <div class="faq-cost-grid">
                        <div class="faq-cost-block">
                            <h4 class="faq-cost-title">Erstuntersuchung</h4>
                            <div class="faq-cost-item">
                                <span>Optometrische Messung</span>
                                <strong>175 €</strong>
                            </div>
                            <div class="faq-cost-item">
                                <span>Visuo-kognitive Analyse</span>
                                <strong>175 €</strong>
                            </div>
                            <p class="faq-cost-note">Inklusive ausführlichem Befundbericht, individuellem Trainingsplan und konkreten Handlungsempfehlungen.</p>
                        </div>
                        <div class="faq-cost-block">
                            <h4 class="faq-cost-title">Laufendes Training</h4>
                            <div class="faq-cost-item">
                                <span>Einzelsitzung (45 Min.)</span>
                                <strong>110 €</strong>
                            </div>
                            <div class="faq-cost-item">
                                <span>Leihgebühr Trainingsmaterialien</span>
                                <strong>25 € <small>einmalig</small></strong>
                            </div>
                            <div class="faq-cost-item">
                                <span>Online-Trainingsprogramme</span>
                                <strong>auf Anfrage</strong>
                            </div>
                        </div>
                    </div>
                    <div class="faq-hint-box">
                        <span class="faq-hint-icon">ℹ</span>
                        <div>
                            <strong>Hinweis zur Kostenerstattung:</strong> Als staatlich anerkannte Orthoptistin können Privatpatienten und Beihilfeberechtigte die Kosten bei ihrer Versicherung einreichen. Für eine mögliche Teilerstattung benötigen Sie in der Regel ein Privatrezept über 10–12 Sitzungen für orthoptische / pleoptische Behandlungen bei <em>„Chiasma Augenschule, Mireia Macian"</em>. Gesetzliche Krankenkassen übernehmen die Kosten leider nicht. Ich berate Sie gerne persönlich zu allen Fragen der Kostenerstattung.
                        </div>
                    </div>
                </div>
            </div>

            <div class="faq-item">
                <button class="faq-question" onclick="toggleFaq(this)">
                    <span>Wann haben Sie geöffnet?</span>
                    <span class="faq-icon">+</span>
                </button>
                <div class="faq-answer">
                    <p>Die Augenschule ist <strong>Montag bis Freitag von 10:30 bis 18:00 Uhr</strong> geöffnet – Mittwoch ausgenommen. Alle Termine finden ausschließlich nach vorheriger Vereinbarung statt.</p>
                </div>
            </div>

        </div>
    </section>

<!-- ===================== SECTION 2: ALLGEMEINE FRAGEN ===================== -->
    <section id="allgemeine" class="faq-section">
        <div class="faq-section-header faq-header-red">
            <div class="faq-section-icon-small">
                <svg viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M8 12 Q8 6 14 6 H50 Q56 6 56 12 V38 Q56 44 50 44 H38 L28 58 L26 44 H14 Q8 44 8 38 Z" stroke="white" stroke-width="3" fill="none" stroke-linejoin="round"/>
                    <circle cx="32" cy="20" r="3" fill="white"/>
                    <path d="M32 26 V34" stroke="white" stroke-width="3" stroke-linecap="round"/>
                </svg>
            </div>
            <div>
                <h2>Allgemeine Fragen</h2>
                <p>Sehtraining, Symptome und was das Auge leisten kann</p>
            </div>
        </div>

        <div class="faq-accordion">

            <div class="faq-item">
                <button class="faq-question" onclick="toggleFaq(this)">
                    <span>Was macht eine Funktionaloptometristin?</span>
                    <span class="faq-icon">+</span>
                </button>
                <div class="faq-answer">
                    <p>Eine Funktionaloptometristin misst und analysiert visuelle Fähigkeiten weit über die reine Brillenstärke hinaus. Sehen ist ein komplexer Prozess: Es umfasst alles, was die visuelle Information von der Netzhaut bis zur Verarbeitung im Gehirn betrifft – also Koordination, Ausdauer, Wahrnehmung und vieles mehr. Genau diese Fähigkeiten stehen im Mittelpunkt unserer Arbeit.</p>
                </div>
            </div>

            <div class="faq-item">
                <button class="faq-question" onclick="toggleFaq(this)">
                    <span>Unser Kind liest langsam und stockend – obwohl die Augen laut Augenarzt gesund sind. Was kann man tun?</span>
                    <span class="faq-icon">+</span>
                </button>
                <div class="faq-answer">
                    <p>Dass die Augen medizinisch gesund sind, ist eine wichtige und gute Grundlage. Aber auch vollkommen gesunde Augen können Schwierigkeiten in der gezielten Koordination und Ausdauer zeigen. Um das abzuklären, führen wir unsere Eingangsanalysen durch – optometrische und visuo-kognitive Messungen.</p>
                    <p>Lesen ist ein hochkomplexer Vorgang. Wenn die Grundlage – also die präzise Ausrichtung und Koordination der Augen – nicht reibungslos funktioniert, muss das Gehirn enorm viel Energie für die Kompensation aufwenden. Für das eigentliche Lesen, geschweige denn das Verstehen von Texten, bleibt dann oft nicht mehr genug übrig.</p>
                </div>
            </div>

            <div class="faq-item">
                <button class="faq-question" onclick="toggleFaq(this)">
                    <span>Beim Arbeiten am Laptop bekomme ich heftige Kopfschmerzen – kann das an den Augen liegen?</span>
                    <span class="faq-icon">+</span>
                </button>
                <div class="faq-answer">
                    <p>Kopfschmerzen können viele Ursachen haben und sollten grundsätzlich zuerst ärztlich abgeklärt werden. Die Augen sind jedoch eine häufig unterschätzte Ursache. Wenn beide Augen nicht präzise miteinander arbeiten, muss das Gehirn Schwerstarbeit leisten: Es überlagert kontinuierlich zwei leicht voneinander abweichende Bildeindrücke, damit wir nicht doppelt sehen. Je mehr Energie dafür aufgewendet wird, desto weniger bleibt für Konzentration und Ausdauer. Die Folge können neben Kopfschmerzen auch Ermüdung, Augenbrennen oder Verschwommensehen sein.</p>
                </div>
            </div>

            <div class="faq-item">
                <button class="faq-question" onclick="toggleFaq(this)">
                    <span>Kann man Kurzsichtigkeit wegtrainieren?</span>
                    <span class="faq-icon">+</span>
                </button>
                <div class="faq-answer">
                    <p>Diese Frage hört man oft – aber eine pauschale Antwort wäre irreführend. Kurzsichtigkeit hat in der Regel zwei Komponenten: eine <strong>physiologische</strong> (das Auge ist anatomisch zu groß und daher kurzsichtig) und eine <strong>funktionelle</strong> (das Auge arbeitet viel und lang auf kurze Distanz und kann sich schwer entspannen).</p>
                    <p>Mit gezieltem Sehtraining lässt sich der funktionelle Anteil verbessern – eine weitere Progression kann verlangsamt oder aufgehalten werden. Den physiologischen Anteil kann Training allein nicht verändern; hierfür arbeite ich eng mit <strong>Optik Teichmann</strong> zusammen, wo unter anderem spezielle Kontaktlinsen zur Myopiekontrolle eingesetzt werden können.</p>
                </div>
            </div>

            <div class="faq-item">
                <button class="faq-question" onclick="toggleFaq(this)">
                    <span>Unser Kind hat Probleme mit dem Schreiben – können Sie da helfen?</span>
                    <span class="faq-icon">+</span>
                </button>
                <div class="faq-answer">
                    <p>Möglicherweise ja. Es lohnt sich, einen Blick auf unsere <a href="/infos/checkliste" class="imp-link">Checkliste</a> zu werfen. Wissenschaftlich ist inzwischen gut belegt, dass Lese-Rechtschreib-Schwäche (LRS) sowie Schwierigkeiten mit dem Schreiben häufig mit Störungen des visuellen Systems zusammenhängen. Als klassisches Beispiel gilt die Konvergenzinsuffizienz. Auch Rechenschwäche (Dyskalkulie) wird zunehmend mit visuellen Verarbeitungsproblemen in Verbindung gebracht.</p>
                </div>
            </div>

            <div class="faq-item">
                <button class="faq-question" onclick="toggleFaq(this)">
                    <span>Kann ein Sehtraining eine Winkelfehlsichtigkeit beheben?</span>
                    <span class="faq-icon">+</span>
                </button>
                <div class="faq-answer">
                    <p>Ein Sehtraining kann keine anatomischen Abweichungen korrigieren. Was es jedoch kann: die <strong>Kompensationsfähigkeit</strong> gezielt stärken. Durch systematisches Visualtraining werden als zu schwach identifizierte Sehfunktionen aufgebaut – so dass die Winkelfehlsichtigkeit langfristig beschwerdefrei ausgeglichen werden kann.</p>
                    <p>Gerade wenn eine Winkelfehlsichtigkeit mit einer Fokussierstörung kombiniert auftritt, ist Visualtraining oft effektiver als eine Prismenbrille allein. Das erfordert Zeit und Disziplin – zahlt sich aber nachhaltig aus.</p>
                </div>
            </div>

            <div class="faq-item">
                <button class="faq-question" onclick="toggleFaq(this)">
                    <span>Ist es wichtig, Winkelfehlsichtigkeit früh zu behandeln?</span>
                    <span class="faq-icon">+</span>
                </button>
                <div class="faq-answer">
                    <p>Ja, sehr. Schule und Alltag stellen heute enorme Anforderungen an das visuelle System. Mängel in diesem System wirken sich unweigerlich auf die Entwicklung und die späteren Möglichkeiten eines Kindes aus.</p>
                    <p>Leider ist es in Deutschland üblich, erst dann zu handeln, wenn klar messbare Defizite sichtbar sind – oft erst in der 2. oder 3. Klasse oder wenn Fehlfunktionen bereits zu sichtbaren Rückständen geführt haben. In Ländern wie Spanien gibt es bereits ab dem Vorschulalter systematische Screenings, die eine frühere Intervention ermöglichen. Je früher ein Problem erkannt und angegangen wird, desto geringer ist der Aufwand – und desto größer die Wirkung.</p>
                </div>
            </div>

            <div class="faq-item">
                <button class="faq-question" onclick="toggleFaq(this)">
                    <span>Auf welchen Grundlagen basiert ein optometrisches Visualtraining?</span>
                    <span class="faq-icon">+</span>
                </button>
                <div class="faq-answer">
                    <p>Optometrisches Visualtraining ist systematisch aufgebaut und folgt exakt der natürlichen Entwicklungsreihenfolge des Sehens. Das stellt sicher, dass nicht einzelne Prozesse isoliert geübt werden, sondern das gesamte visuelle System aufgebaut wird. Der Erfolg des Trainings hängt zu <strong>95 % von der Einhaltung dieser genauen Systematik</strong> ab.</p>
                    <p>Die Hirnforschung zeigt zunehmend, wie komplex und vernetzt der Sehvorgang ist: Statt eines einzelnen Sehzentrums im Gehirn sind mindestens 3–4 Bereiche gleichzeitig beteiligt, die auf hochkomplexe Weise miteinander interagieren. Bereits in den 1920er Jahren entwickelte <strong>Dr. Skeffington</strong> ein wegweisendes Modell des Sehvorgangs mit vier ineinandergreifenden Kreisen. Nur wenn alle vier Bereiche gleichwertig funktionieren, entsteht das, was wir als vollständiges „Sehen" – die Vision – erleben.</p>
                    <p>In der Visuellen Analyse messen wir die Stärke jedes einzelnen dieser Bereiche. Was als schwach identifiziert wird, wird gezielt trainiert und mit den anderen Bereichen verknüpft. Diese Trainingsprozesse funktionieren in jedem Alter – je jünger, desto schneller zeigen sich die Ergebnisse.</p>
                </div>
            </div>

        </div>
    </section>

<!-- ===================== SECTION 3: GRUNDLAGEN OPTOMETRIE ===================== -->
    <section id="optometrie" class="faq-section">
        <div class="faq-section-header faq-header-black">
            <div class="faq-section-icon-small">
                <svg viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M4 32 C12 14 22 8 32 8 C42 8 52 14 60 32 C52 50 42 56 32 56 C22 56 12 50 4 32 Z" stroke="white" stroke-width="3" fill="none"/>
                    <circle cx="32" cy="32" r="10" stroke="white" stroke-width="3" fill="none"/>
                    <circle cx="32" cy="32" r="4" fill="white"/>
                </svg>
            </div>
            <div>
                <h2>Grundlagen Optometrie</h2>
                <p>Was Sie über das visuelle System wissen sollten</p>
            </div>
        </div>

        <div class="faq-accordion">

            <div class="faq-item">
                <button class="faq-question" onclick="toggleFaq(this)">
                    <span>Was ist der Unterschied zwischen Winkelfehlsichtigkeit und echtem Schielen?</span>
                    <span class="faq-icon">+</span>
                </button>
                <div class="faq-answer">
                    <div class="faq-two-col">
                        <div class="faq-infobox faq-infobox-green">
                            <h4>Winkelfehlsichtigkeit <em>(„verstecktes Schielen")</em></h4>
                            <p>Ein Augenstellungsfehler, der durch den Einsatz von Muskeln und Nerven selbstständig ausgeglichen werden kann. Gehen die Energiereserven zur Neige, entstehen Anstrengungsbeschwerden. Kann die Kompensation nicht dauerhaft aufrechterhalten werden, zeigen sich Sehbeschwerden.</p>
                        </div>
                        <div class="faq-infobox faq-infobox-grey">
                            <h4>Echtes Schielen</h4>
                            <p>Ein Augenstellungsfehler, bei dem die Abweichung nicht selbstständig ausgeglichen werden kann. Es fehlt die Kraft oder Kontrolle, beide Augen gleichzeitig auf denselben Punkt auszurichten.</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="faq-item">
                <button class="faq-question" onclick="toggleFaq(this)">
                    <span>Haben alle Menschen mit Winkelfehlsichtigkeit Probleme?</span>
                    <span class="faq-icon">+</span>
                </button>
                <div class="faq-answer">
                    <p>Nein. Bei rund <strong>80 % aller Menschen</strong> lässt sich eine Winkelfehlsichtigkeit messen – doch nur etwa <strong>20 % von ihnen</strong> zeigen auffällige Beschwerden. Häufig treten diese nur in bestimmten Lebensphasen auf. Besonders stark betroffen sind oft Kinder während der Schuljahre: In dieser Zeit werden die Augen enorm beansprucht, und oft reicht die Kompensationskraft nicht aus, um dem Augenstellungsfehler zusätzlich zur schulischen Belastung standzuhalten.</p>
                </div>
            </div>

            <div class="faq-item">
                <button class="faq-question" onclick="toggleFaq(this)">
                    <span>Verursacht Winkelfehlsichtigkeit eine Wahrnehmungsstörung?</span>
                    <span class="faq-icon">+</span>
                </button>
                <div class="faq-answer">
                    <p>Ja, das kann sie. Eine Augenstellungsabweichung, die nicht vollständig und stabil kompensiert werden kann, führt zu ständig wechselnden visuellen Wahrnehmungen. Dieses instabile Sehen lässt sich als Wahrnehmungsstörung bezeichnen – mit direkten Auswirkungen auf Konzentration, Lesen und räumliche Orientierung.</p>
                </div>
            </div>

            <div class="faq-item">
                <button class="faq-question" onclick="toggleFaq(this)">
                    <span>Was ist der Unterschied zwischen der Messung von Kurz-/Weitsichtigkeit und einer Winkelfehlsichtigkeit?</span>
                    <span class="faq-icon">+</span>
                </button>
                <div class="faq-answer">
                    <p>Bei der klassischen Augenuntersuchung wird die sogenannte <strong>Längenfehlsichtigkeit</strong> gemessen – also Kurzsichtigkeit, Weitsichtigkeit oder Hornhautverkrümmung. Diese Messung erfolgt für jedes Auge einzeln.</p>
                    <p>Da wir jedoch zwei Augen haben, die idealerweise präzise zusammenarbeiten, wäre es logisch, bei jeder Messung auch deren <strong>Zusammenarbeit und symmetrische Ausrichtung</strong> zu überprüfen. Genau das geschieht bei der Messung auf Winkelfehlsichtigkeit – einer Untersuchung, die im Rahmen einer Standarduntersuchung beim Augenarzt leider oft nicht vorgenommen wird.</p>
                </div>
            </div>

            <div class="faq-item">
                <button class="faq-question" onclick="toggleFaq(this)">
                    <span>Was haben die Augen mit Legasthenie zu tun?</span>
                    <span class="faq-icon">+</span>
                </button>
                <div class="faq-answer">
                    <p>Wenn das visuelle System nicht reif genug ist oder Probleme mit der <strong>Raum-Lage-Wahrnehmung</strong> hat – also das Kind nicht sicher zwischen Rechts und Links unterscheiden kann –, dann kann es auch Buchstaben und Silben nicht zuverlässig auseinanderhalten: „b" und „d", „ei" und „ie", „sie" und „eis" werden verwechselt. Was wie ein sprachliches Problem wirkt, hat in vielen Fällen eine visuelle Ursache.</p>
                </div>
            </div>

            <div class="faq-item">
                <button class="faq-question" onclick="toggleFaq(this)">
                    <span>Was haben die Augen mit Dyskalkulie zu tun?</span>
                    <span class="faq-icon">+</span>
                </button>
                <div class="faq-answer">
                    <p>Ähnlich wie bei der Legasthenie: Wer Rechts und Links nicht sicher unterscheiden kann, hat auch Schwierigkeiten, Zahlen räumlich zu erfassen. „25" und „52" sehen dann aus wie dasselbe – und der Zehner- oder Hunderterübergang beim Rechnen wird zur echten Herausforderung. Auch hier ist eine gründliche Überprüfung des visuellen Systems ein wichtiger Schritt auf der Suche nach den Ursachen.</p>
                </div>
            </div>

        </div>
    </section>
</div>

<!-- ===================== CTA ===================== -->
<div class="faq-cta">
    <div class="faq-cta-inner">
        <h2>Ihre Frage war nicht dabei?</h2>
        <p>Ich helfe Ihnen gerne persönlich weiter – per Telefon, E-Mail oder direkt in der Praxis.</p>
        <a href="/kontakt" class="btn-v10">Jetzt Kontakt aufnehmen</a>
    </div>
</div>

<!-- ===================== STYLES ===================== -->
<style>
/* --- FAQ SECTION NAV --- */
.faq-section-nav {
    display: flex;
    gap: 1.5rem;
    justify-content: center;
    flex-wrap: wrap;
    max-width: 1100px;
    margin: -60px auto 3rem auto;
    padding: 0 1.5rem;
    position: relative;
    z-index: 10;
}

.faq-nav-card {
    flex: 1;
    min-width: 220px;
    max-width: 320px;
    background: white;
    border-radius: 20px;
    padding: 2rem 1.5rem;
    text-align: center;
    text-decoration: none !important;
    color: #333;
    box-shadow: 0 10px 30px rgba(0,0,0,0.08);
    border: 2px solid transparent;
    transition: all 0.35s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 0.75rem;
}

.faq-nav-card:hover {
    border-color: var(--c-green);
    transform: translateY(-8px);
    box-shadow: 0 20px 40px rgba(196,208,79,0.25);
    color: #000;
}

.faq-nav-icon {
    width: 72px;
    height: 72px;
    color: var(--c-grey);
    transition: color 0.3s ease;
}

.faq-nav-card:hover .faq-nav-icon {
    color: var(--c-green);
}

.faq-nav-label {
    font-weight: 700;
    font-size: 1.05rem;
    text-transform: uppercase;
    letter-spacing: 0.5px;
}

.faq-nav-count {
    font-size: 0.8rem;
    color: #aaa;
    background: #f5f5f5;
    padding: 0.2rem 0.75rem;
    border-radius: 50px;
}

/* --- FAQ WRAPPER --- */
.faq-wrapper {
    max-width: 900px;
    margin: 0 auto;
    padding: 0 1.5rem 4rem 1.5rem;
}

/* --- FAQ SECTION --- */
.faq-section {
    margin-bottom: 4rem;
    scroll-margin-top: 120px;
}

.faq-section-header {
    display: flex;
    align-items: center;
    gap: 1.5rem;
    padding: 1.75rem 2rem;
    border-radius: 16px 16px 0 0;
    color: white;
    margin-bottom: 0;
}

.faq-header-green { background: linear-gradient(135deg, #8fa32d, var(--c-green)); }
.faq-header-red   { background: linear-gradient(135deg, #8c0f20, var(--c-red)); }
.faq-header-black { background: linear-gradient(135deg, #222, #444); }

.faq-section-icon-small {
    width: 48px;
    height: 48px;
    flex-shrink: 0;
    opacity: 0.9;
}

.faq-section-header h2 {
    margin: 0 0 0.2rem 0;
    font-size: 1.5rem;
    font-weight: 800;
    color: white;
}

.faq-section-header p {
    margin: 0;
    font-size: 0.9rem;
    opacity: 0.8;
}

/* --- ACCORDION --- */
.faq-accordion {
    border: 1px solid #eee;
    border-top: none;
    border-radius: 0 0 16px 16px;
    overflow: hidden;
    background: white;
    box-shadow: 0 10px 30px rgba(0,0,0,0.06);
}

.faq-item {
    border-bottom: 1px solid #f0f0f0;
}

.faq-item:last-child {
    border-bottom: none;
}

.faq-item-highlight {
    background: #fffef5;
}

.faq-question {
    width: 100%;
    background: none;
    border: none;
    padding: 1.4rem 1.75rem;
    text-align: left;
    cursor: pointer;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 1rem;
    font-family: var(--font-main);
    font-size: 1rem;
    font-weight: 600;
    color: #222;
    transition: background 0.2s ease, color 0.2s ease;
    line-height: 1.4;
}

.faq-question:hover {
    background: #fafaf5;
    color: #000;
}

.faq-question.open {
    color: #000;
    background: #f9fbf0;
}

.faq-icon {
    font-size: 1.5rem;
    font-weight: 300;
    color: var(--c-green);
    flex-shrink: 0;
    transition: transform 0.3s ease;
    line-height: 1;
    width: 28px;
    text-align: center;
}

.faq-question.open .faq-icon {
    transform: rotate(45deg);
}

.faq-answer {
    display: none;
    padding: 0 1.75rem 1.5rem 1.75rem;
    color: #555;
    line-height: 1.8;
    font-size: 0.96rem;
    border-top: 1px solid #f0f0f0;
}

.faq-answer.open {
    display: block;
    animation: fadeAnswer 0.3s ease;
}

@keyframes fadeAnswer {
    from { opacity: 0; transform: translateY(-8px); }
    to   { opacity: 1; transform: translateY(0); }
}

.faq-answer p { margin: 1rem 0; }
.faq-answer p:first-child { margin-top: 1rem; }

.faq-list {
    margin: 0.75rem 0 0.75rem 1.25rem;
    padding: 0;
}

.faq-list li {
    margin-bottom: 0.4rem;
    color: #555;
}

/* --- TWO COLUMN BOXES --- */
.faq-two-col {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1rem;
    margin: 1rem 0;
}

@media (max-width: 640px) {
    .faq-two-col { grid-template-columns: 1fr; }
}

.faq-infobox {
    padding: 1.25rem;
    border-radius: 12px;
}

.faq-infobox h4 {
    margin: 0 0 0.75rem 0;
    font-size: 0.95rem;
    font-weight: 700;
    display: flex;
    align-items: center;
    gap: 0.5rem;
    flex-wrap: wrap;
}

.faq-infobox ul {
    margin: 0;
    padding-left: 1.2rem;
}

.faq-infobox ul li {
    margin-bottom: 0.3rem;
    font-size: 0.92rem;
    color: #444;
}

.faq-infobox p {
    margin: 0;
    font-size: 0.93rem;
    color: #444;
    line-height: 1.6;
}

.faq-infobox-green {
    background: rgba(196,208,79,0.12);
    border-left: 3px solid var(--c-green);
}

.faq-infobox-grey {
    background: rgba(213,213,203,0.25);
    border-left: 3px solid var(--c-grey);
}

.faq-badge {
    font-size: 0.75rem;
    font-weight: 500;
    background: var(--c-green);
    color: white;
    padding: 0.15rem 0.5rem;
    border-radius: 50px;
}

/* --- COST TABLE --- */
.faq-cost-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1.5rem;
    margin: 1rem 0;
}

@media (max-width: 600px) {
    .faq-cost-grid { grid-template-columns: 1fr; }
}

.faq-cost-block {
    background: #fafafa;
    border-radius: 12px;
    padding: 1.25rem;
}

.faq-cost-title {
    font-size: 0.8rem;
    text-transform: uppercase;
    letter-spacing: 1px;
    color: var(--c-green);
    font-weight: 700;
    margin: 0 0 1rem 0;
    padding-bottom: 0.5rem;
    border-bottom: 2px solid var(--c-green);
}

.faq-cost-item {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    padding: 0.6rem 0;
    border-bottom: 1px solid #eee;
    font-size: 0.93rem;
    gap: 0.5rem;
}

.faq-cost-item:last-of-type { border-bottom: none; }

.faq-cost-item span { color: #555; }

.faq-cost-item strong {
    color: #000;
    white-space: nowrap;
    font-size: 1rem;
}

.faq-cost-item strong small {
    font-size: 0.75rem;
    font-weight: 400;
    color: #999;
    margin-left: 0.25rem;
}

.faq-cost-note {
    font-size: 0.82rem;
    color: #999;
    margin-top: 0.75rem !important;
    font-style: italic;
}

/* --- HINT BOX --- */
.faq-hint-box {
    display: flex;
    gap: 1rem;
    background: #fff8e6;
    border-left: 4px solid #f0c040;
    border-radius: 0 10px 10px 0;
    padding: 1.1rem 1.25rem;
    margin-top: 1.25rem;
    font-size: 0.91rem;
    color: #555;
    line-height: 1.65;
}

.faq-hint-icon {
    font-size: 1.2rem;
    flex-shrink: 0;
    color: #c09020;
    margin-top: 1px;
}

/* --- CTA --- */
.faq-cta {
    background: var(--c-black);
    padding: 5rem 2rem;
    text-align: center;
}

.faq-cta-inner {
    max-width: 600px;
    margin: 0 auto;
}

.faq-cta h2 {
    color: white;
    font-size: 2rem;
    font-weight: 800;
    margin-bottom: 0.75rem;
}

.faq-cta p {
    color: #aaa;
    font-size: 1.1rem;
    margin-bottom: 2rem;
}

@media (max-width: 768px) {
    .faq-section-nav { flex-direction: column; align-items: center; }
    .faq-nav-card { max-width: 100%; width: 100%; }
    .faq-question { font-size: 0.95rem; padding: 1.2rem 1.25rem; }
    .faq-answer { padding: 0 1.25rem 1.25rem 1.25rem; }
    .faq-section-header { gap: 1rem; padding: 1.25rem 1.25rem; }
    .faq-section-header h2 { font-size: 1.25rem; }
}
</style>

<!-- ===================== JAVASCRIPT ===================== -->
<script>
function toggleFaq(btn) {
    const answer = btn.nextElementSibling;
    const isOpen = btn.classList.contains('open');

    // Close all in same accordion
    const accordion = btn.closest('.faq-accordion');
    accordion.querySelectorAll('.faq-question.open').forEach(function(q) {
        q.classList.remove('open');
        q.nextElementSibling.classList.remove('open');
    });

    // Open clicked if it was closed
    if (!isOpen) {
        btn.classList.add('open');
        answer.classList.add('open');
    }
}

// Smooth scroll offset for fixed header
document.querySelectorAll('a[href^="#"]').forEach(function(anchor) {
    anchor.addEventListener('click', function(e) {
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
            e.preventDefault();
            const offset = 110;
            const top = target.getBoundingClientRect().top + window.pageYOffset - offset;
            window.scrollTo({ top: top, behavior: 'smooth' });
        }
    });
});
</script>
