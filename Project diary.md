# April 19, 2025: Brainstorming first ideas
## Project requirements
- **Goal**: make it smarter and more user-friendly
	- Issues: unclear categorization, privacy
- **Mean**: user-centered design approach
- **Artifact**: design an innovative User Interface
## Idea 1: Derive requirements from interviews and conduct within-person evaluation
### Gathering Insights
- Next step in the human-centered design approach/project: **gather insights**
	- Look for app reviews, scrape, and analyze using some natural language processing methods
	- Interviews
- We prefer interviews over scraping for reviews, because there are no reviews for the gemeinsam.Oldenburg website
- Ideas on how to proceed with interviews
	- Instruct our friends to use the website/tool for 1-2 weeks
	- Later conduct an interview to gather their feedback (e.g., using qualitative content analysis)
	- While they use the tool, we can design the guided interview
	- Aim: 2-3 interviewees
### Evaluation
	- Perhaps, add some sort of questionnaire: We could use it to conduct a within-person comparison of the original tool to our improved tool.

# April 23, 2025: Preparing the first presentation and next steps
## Idea 2: Derive requirements from existing knowledge and conduct (between-person) evaluation
### Gathering insights
- Are the issues mentioned in the slide part of existing knowledge? -> Ask Dennis (perhaps, using an expert interview)
- Scraping app store reviews of other apps and derive user requirements on that basis
- Or, if categories are an issue, scrape complaints on gemeinsam.Oldenburg site, use e.g., a topic model and derive new categories on that basis
### Evaluation
- Based on our requirements, we can design mockups
- These could also be suitable for A/B testing or, perhaps more advanced, conjoined experiments or factorial survey designs
## Our thoughts
- We are leaning towards idea 2, as it easier to realize within the time frame of the course
## Presentation
- Main points of the project
- Present idea 2
## TODOs
- Michael: prepare two slides
- Michael: send mail with availability (Wednesday, 2pm or afterwards, preferably online)
- Marten: research mockup design
- Minu: research scraping options
  
# April 30, 2025: First Meeting with Dennis

## Communication & Feedback
- Dennis requests to be regularly informed about any feedback recieved from Tobias

## 🛠Current Issues with Mängelmelder
- Mängelmelder is managed by an external company.
- Categories are unclear to citizens; users don’t understand what the labels mean.
- Personal data requirements are a barrier — a common issue across Mängelmelder in Germany.
- Currently, the platform can only be used after registering.
- Accessibility issues: language barriers and the login/register process hinder usability.

## Research & Evaluation Planning
- Recommended number of interviewees: 4–6.
- Plan to conduct user interviews with fellow students based on existing knowledge/requirements.
- Possibility of conducting expert interviews discussed.

## Interview & Survey Design
- Need to assess whether users actually perceive categorization as a problem.
- Suggestion: Replace long interviews with a survey including a short interview section.
- Scraping content for insights or dataset generation – feasibility of scraping pictues questioned.
- Evaluation idea: Have users categorize or interpret images of posts.
- Dennis suggests the use of subcategories to improve clarity.
- Consideration of appropriate interview types for this context.

## UI & Prototyping
- Figma might be used for prototyping UI elements.
- Dennis emphasizes the importance of delivering an idea for a UI design as part of the project requirment.
- Drop-down menus for categories are overwhelming.
- Suggested improvement: hierarchical selection with main and subcategories via step-by-step interface.
- Another Idea: integrate ai image recognition into Mängelmelder to enhance usability.

## Tools & Next Steps
- Survey tools considered: Google Forms, LimeSurvey.
- Communication with Dennis will continue via Discord.
- Next meeting: finalize research and design ideas

# May 6, 2025 - Answering Gathering Insights Questions / Problem Analysis Design Thinking

## Context: 
### Where your system is going to be used?
### When your system is going to be used?

- On the street right after spotting issue / later at home
### Why your system is going to be used?
- Issues might propose dangers to public
- users want there direct surroundings to be pretty and safe
- users want public space to be working
## Stakeholders

### By whom your system is going to be used?
- People living in Oldenburg, adults
### Whose needs have to be considered?
### Who will be affected by the usage?
- people using the system
- people maintaining the system
- people taking care of the issues
- people living Oldenburg, no using the system

NOTE: Who actually takes care of removing the issues? How do they use the platform? -> Ask Dennis!!!

## Design Thinking
### User need
User: People spotting issues in Oldenburg
Need: stressful lives, need to have an easy way to communicate issues
Insight: everybody has a smartphone in their pocket

People spotting issues in Oldenburg need an easy way to communicate that issue in a way that is quick and easy.

### How might we?

How might we make Mängelmelder quicker and easier to use?

# May 7, 2025 - Weekly Meeting
- Some more discussion about the stakeholders: Who actually takes care of removing the issues? How do they use the platform? -> Ask Dennis!!!
- Developing a survey to test categories with pictures, discussing Michaels survey draft in LimeSurvey
- decision to kick out first question, and expand on the
## TODOS:
- finish presentation
- Minu: look into scraping reported issues for clustering
- Michael: finish LimeSurvey
- Marten: research methods for clustering (maybe topic modells)

# May 16, 2025 – Sketch Workshop Results

## Workshop Photo
![Workshop Photo](images/Sketch_workshop_photo.jpg)

## Storyboard 1
![Storyboard 1](images/Sketch_workshop_storyboard1.jpg)

## Storyboard 2
![Storyboard 2](images/Sketch_workshop_storyboard2.jpg)

## Storyboard 3
![Storyboard 3](images/Sketch_workshop_storyboard3.jpg)

# May 20, 2025 - Piloting Thinking Aloud 
- conducting first thinking aloud interview
- subject is told to spot an issue in the city and report it via the city issue service
- while using the service the subject should be thinking out loud and notes are taken by the interviewee
- during the interview there were some difficulties, because the service was unreachable
- eventually the subject could find a working link with some intervention
- after the thinking aloud process a NASA-TLX survey was filled out by the subject
- The issue spotted was a leaking salt container
![thinkingaloud](https://github.com/user-attachments/assets/a15328ea-ff1e-4c97-97e6-c7dddab59d0e)

# May 27, 2025 - Piloting Thinking Aloud
- The participant was instructed to identify an issue in the city and report it via the Gemeinsam Oldenburg issue reporting service.
- While using the service, she was asked to think aloud, and i took notes.
- She attempted to log in at first but realized she had no login credentials, so she opted for "Continue without logging in" instead.
- The participant struggled with locating the issue on the map due to the lack of a mouse while being on the go and faced challenges with the address search (uncertainty about street names and issues with house numbering).
- She also found the category selection confusing, nothng that the options were to broad and unclear.
- After the Think-Aloud process, a NASA-TLX survey was filled out by the participant.
- Identified issue: A damaged bike path, where the street pavement was cracked and broken.
![thinkingaloud](images/think_aloud_damaged_street_pavement.jpg)

# June 03, 2025 - Working on the survey
- **Updated idea**: A/B testing with the original Mängelmelder serving as A and our prototype serving as B
- **Dependent variable(s)**
	- **Subjective ease of categorization**: item measuring self-reported ease of categorization -> difficulty, confidence
		- One option is to use measurements of post-decision confidence: E.g., Pleskac and Busemeyer had respondents rate their post-decision confidence after completing a task using a keyboard with keys for 50, 60, 70, 80, 90, and 100 percent confidence
		- NASA-TLX offers measurements concerning...
			- Mental demand
			- Physical demand
			- Temporal demand
			- Performance
			- Effort
			- Frustration
		- Using NASA-TLX
			- Has the advantage of employing a tested scale
			- Has the disadvantage of not directly asking with regard to categorization
			- If we use it, we would have to make the assumption that e.g., high mental demand is because of categorization. It would, however, be exceedingly difficult to show that it is not due to other factors.
		- Using the confidence scale, could be rephrased in terms of ease of categorization. The only disadvantage would be that we are not really using a tested instrument, because we would have to adapt it. The advantage would be that we do not establish a link based on a range of assumptions.
	- **Objective ease of categorization**: Level of agreement with regard to the selected category
	- Technically, both could be measured with regard to every single picture, but it makes more sense to not do this
		- Measuring ease of categorization for each picture would introduce many additional and repetitive items, increasing the risk that respondents do not complete the survey
		- Level of agreement takes indirectly takes into account every picture anyway (and a more specific analysis could be conducted without introducing additional items later on if deemed necessary)
- **Independent variables**
	- Assigned **group** as main predictor
	- Control variables
		- **Familiarity** with Mangelmelder
		- **Socio-demographic predictors**
		- **Order of stimuli**
		- **Completion time**
		- **Web/mobile**
- **Analysis methods**
	- Probably, linear regression for subjective ease of categorization
	- Probably, ANOVA for objective ease of categorization

# June 04, 2025 - Follow-up meeting with Dennis
- Presentation of progress, i.e. thinking aloud results, scraped data set, Figma prototype, survey idea
- Discussion about which algorithms to use for clustering (e.g., BERT topic modeling, K-means clustering, T-SNE)

# June 13, 2025 - Discussion with Mikołaj
- For scraped data: Consider bias when writing complained -> category has already been selected
- Suggestion: apply clustering algorithm and then use card sorting to actually extract the information infrastructure/tree structure of the extracted categories
	- Card sorting: sorting cards into families
	- Have potential users group our categories
	- What should be high-level/low-level -> constructing the tree of categories
	- Recruit 5-7 people to group categories which we have extracted using clustering -> individually (not as a group)
	- Then have them assign example complaints
- Two potential measures for subjective ease of categorization (which we would use when evaluating the prototype, rather than the information architecture)
	- Rating scale mental effort (RSME)
	- UMUX
- Give them a way to express how easy/difficult it was to categorize things (e.g., free text)
- Ensure that people who are involved in card-sorting are not involved in the survey
- Identify causes of confusion during card sorting -> good empirical result
- Not randomly selected pictures, but representative: select different categories, confusing ones
- **Conclusion**: Use survey to evaluate information architecture (rather than prototype itself) and use results from card sorting to gather qualitative data for the next iteration of the design cycle
# June 13, 2025 - June 30, 2025
- working on clustering algortihms
  	- topic model
  	- embedding + k-means clustering
# June 20, 2025
Decision for BERT Topic Model, as it produces the best results
## Top words per topic
![top_words_per_topic](https://github.com/user-attachments/assets/fe9b8732-489f-4e1c-addd-7ad7b2d3a77a)
## Top original (i.e. unprocessed) documents per topic
Topic 0:
  Document 8:
  Bei den Müllcontainern liegt Müll

  Document 9:
  An den Container liegt sehr viel Müll

  Document 17:
  Müllansammlung an den Wertstoffcontainern



Topic 1:
  Document 5:
  Straßenbeleuchtung so enorm zugewachsen das kein Licht mehr zu sehen ist

  Document 22:
  Wenn man die Ofener Str. Richtung Westkreuz fährt und dann Tappenbeckstr. Und Tirpitzstr., da müssen die Hecken geschnitten werden! Die verdecken die Hälfte des Fußwegs.

  Document 29:
  Hoher Absatz in der Fahrbahn



Topic 2:
  Document 434:
  An der Bahnhofsalle hängen noch Wahlplakate der Partei MLPD.
Bitte entfernen

  Document 475:
  Ampelmast vollgeklebt mit Fußball / VfB Sticker

  Document 500:
  Auf dem Stoppschild am Westfalendamm, Einfahrt in den Damm, befindet sich der Schriftzug einer politischen Partei. Ich bitte darum, diesen Schriftzug schnellstmöglich zu entfernen.



Topic 3:
  Document 46:
  Auf dem Langenweg, Ecke Stiekelkamp ist die Ampel defekt. Der Taster funktioniert nicht mehr und viele gehen bei Rot über die Straße.

  Document 52:
  Stark verstecktes Verkehrsschild

  Document 73:
  Bei einem Auszug wurde eine Matraze und ein Matrazenschoner an der Straße entsorgt. Der Verursacher ist bekannt.



Topic 4:
  Document 51:
  Auf dem öffenlich zugänglichen Parplatz stehen mehrere abgemeldete Autos.
Hier scheint gewerbsmäßig mit Autos gehandelt zu werden.

  Document 60:
  Vor dem Haus ist eine gekennzeichnete Parkfläche auf der ein Transporter mit Anhänger parkt. Dadurch wird die Einfahrt zur hälfte blockiert und die Sicht ist eingeschränkt.

  Document 63:
  Zwei PKWs stehen am Anfang der Straße ohne Nummernschilder. Beide Dunkelblau bis schwarz.



Topic 5:
  Document 11:
  Wild angelegter Sperrmüll

  Document 47:
  Drückampel Langenweg/Stiekelkamp nicht funktionsfähig

  Document 57:
  Die Bedarfsampel beim Altenheim geht gar nicht.



Topic 6:
  Document 32:
  Der Fußweg am Triftweg steht bei stärkeren Regenfällen bereichsweise unter Wasser, sodass Kinderwagen und Rollstuhlfahrer auf die Fahrbahn ausweichen müssen,
siehe Fotos im Bereich Triftweg 8, 3 und Einmündung Heidelberger Straße.
Der Fußweg wird nicht ausreichend gepflegt. Die Entwässerung muss überprüft werden.
Der Fußweg muss entweder eben ausgebessert werden oder das Begleitgrün muss abgesenkt werden, damit das Regenwasser versickern kann. Dieser Mangel besteht seit mehreren Jahren und wird zu wenig beachtet.
Der Mangel gefährdet die Verkehrssicherheit.

  Document 38:
  Bitte Randstein entfernen. 
Da der Weg über die Jahre breiter geworden ist, was auch nötig ist, da hier vormittags und nachmittags viele Kinder und Spaziergänger unterwegs sind, befindet sich der ursprüngliche Randstein jetzt mitten auf dem Weg. 
Im Winter ist ein Kind am Randstein mit dem Fahrrad hängengeblieben, ist gestürzt und hat sich zum Glück nur leicht verletzt.

  Document 58:
  In der Bürgerstraße sind bei verschiedenen Hausgrundstücken die Hecken schon weit auf den Bürgersteig gewachsen (z. B. bei Nr 6, Nr 99), so dass der Bürgersteig für Menschen mit Rollatoren oder Rollstuhl, Kinderwagen etc. kaum zu benutzen ist.



Topic 7:
  Document 13:
  Hinter der Bushaltestelle  auf Höhe Trommelweg liegt ein zerfetzer gelber Sack!

Müll erst raus wenn Abholtag ist.

Der scheint schon länger da zu sein...

Bitte entsorgen  stört die Optik und verengt den Fußweg.

  Document 26:
  Hallo, An der Bushaltestelle hat jemand mehrere Mülltüten mit Hausmüll abgestellt. Vielen Dank fürs Kümmern.

  Document 80:
  Bushaltestellenscheibe "Im Krusenbusch" stadteinwärts liegt in Scherben.



Topic 8:
  Document 64:
  Starke Vermüllung am Altkleidercontainer Glascontainer am sprungweg hier sind wieder große Mengen an Müll klamottenkleidung und irgendwelche Gegenstände abgestellt

  Document 82:
  Altpapier erneut nicht abgeholt

  Document 109:
  Es ist dauerhaft Müll in diversen Variationen vorzufinden. Von Glasswolle bis McD Tüten ist alles dabei.



Topic 9:
  Document 10:
  Im Wassergraben zwischen Staulinie und Staugraben liegt eine Restmülltonne.

  Document 18:
  Seit Aufbruch der Straße durch den Netzbetreiber, läuft der Gully nicht mehr ab und die Straße steht bei starken Regenfällen unter Wasser.

  Document 34:
  Entwässerung vom Etzhorner Weg nördlich der Kreuzung mit Triftweg funktioniert nicht.
 Pfützenbildung in der Bankette führt zu Fahrbahnschäden, Straßenbegleitgrün sollte m.E. tiefergelegt werden,
damit das Regenwasser vesickern kann.



Topic 10:
  Document 105:
  Auf dem Wendehammer des Krögerkamps beim Kreyenbrücker Wasserzug liegt seit einer Woche dieser Sperrmüll.

  Document 116:
  Am Fahrradweg entlang des Kreyenbrücker Wasserzugs steht Müll, neben einer Sitzbank, etwa zwanzig Metter südlich vom Eidechsenweg.

  Document 128:
  mal wieder Sperrmüll unter der Autobahnbrücke



Topic 11:
  Document 104:
  Dwaschweg/Johann-Heinrich-Brandes-Str.,rechts in den Gehweg rein, 3 m wieder rechts drei große Einkaufstüten mit Müll. 
Dwaschweg Gehweg zwischen Sprungweg und Einfahr Sportplatz, rechts zur Fahrbahn eine große Einkaufstüte mit Müll.

  Document 265:
  Sehr geehrte Mitarbeiter:innen,
zwei Teppiche, ein alter Reifen und ein Seil am Baum liegen/sind auf dem Waldweg parallel zur Tennishalle und der Wiese.
Bitte entsorgen Sie den Müll.
J.Pein juergen.pein@ewetel.net

  Document 277:
  Aus Ofenerdiek kommend Richtung Wilhelmshavener Herrstraße ist das rote Licht der mittleren Ampel defekt.



Topic 12:
  Document 1:
  Ecke Nadorster Strasse / Lindenhofsgarten ist diverser Abfall illegal abgelegt worden.

  Document 2:
  In dem Gang Bogenstrasse / Goethestrasse Höhe Hausnummer 36 ist erneut illegal Abfall entsorgt worden.

  Document 70:
  Illegale Müllentsorgung von zwei Dunkeln schwarzen Säcken an der Straße



Topic 13:
  Document 61:
  In der Kurve von der Rennplatzstr. - Butjadinger Str. Muss das Gebüsch  geschnitten werden, denn es verdeckt Teilweise die Schilder!
Und da wo die AB Ohmstede von Nadorster Str. her runter kommt, muss der Asphalt  unten die Schlaglöcher  reparieren!

  Document 72:
  Risse im Asphalt auf dem Sprungweg , Nahe der Autobahnbrücke und dem Wendeplatz .
Grosse Gefahr für Radfahrer !!!

  Document 75:
  wo die Blumenstr. in die Peterstr. mündet, da muß der Asphalt erneuert werden!
Als Auto schon nicht schön, wenn man rein fährt und per Rad  beide Seiten her extrem gefährlich zu fahren!



Topic 14:
  Document 78:
  an den Müllcontainer ist ein schwarzes Sofa angelehnt
Bitte entfernen
stört die Optik

  Document 106:
  Gegenüber der Myliusstraße 7 steht seit längerem dieser Bürostuhl.

  Document 262:
  Bereits am 27.03. und am 04.04. hatte ich Speermüll über die E-Mail des Ordnungsamtes gemeldet. Dieser wurde mindestens eine Woche vor dem 27.03. auf Höhe des Seggenwegs 4 auf dem Gehweg abgeladen. Ursprünglich befand sich dabei auch ein Sofa, das am 04.04. aber weg war. Bei dem Verursacher handelt es sich um einen ehemaligen Mieter aus dem Seggenweg 6. Vermieter ist hausverwaltung@bt-immobilien-oldenburg.de
Das angehängte Bild zeigt die aktuelle Situation. Da nun fast drei Wochen nichts passiert ist, habe ich bei der Stadt angerufen und wurde auf diese Möglichkeit der Meldung hingewiesen.



Topic 15:
  Document 45:
  Auf dem Geh- und Radweg ragen mehrere Äste über den Zaun

  Document 117:
  Sperrmüll im Wendekreis liegt hier seit ca einer Woche. 
Weiter hinten liegt am Bach / Radweg auch noch etwas.

  Document 123:
  Strecke wwist in gesamter Länge immer mal Schlaglöcher  auf!
Bitte richten...



Topic 16:
  Document 115:
  Wenn man aus dem Rummerweg stadtauswärts auf die Ofener Straße möchte ist die Sicht auf den Verkehr der aus der Stadt kommt durch das wuchernde Grün sehr eingeschränkt. Bitte das untere Grün an der Ofener Straße dringend beschneiden. Vielen Dank!

  Document 120:
  Die grüne Fußgängerampel am Ende des Quellenwegs (Bloherfelder Str.) ist auf einer Seite defekt.

  Document 169:
  Grün ragt auf Gehweg, Bürger sprechen uns an. Höhe Hausnummer 9



Topic 17:
  Document 33:
  im Seitengraben vom Triftweg am Haus Etzhorner Weg 71 und gegenüber im anderen Seitengraben des  Triftwegs wächst der  invasive japanische Riesenknöterich seit mehreren Jahren immer weiter.
Laut Merkblatt der Landwirtschaftskammer Niedersachsen
ist diese Pflanze so früh wie möglich zu beseitigen, weil sonst eine Bekämpfung wegen der unterirdischen Rhizome sehr aufwendig sein werde.

  Document 100:
  Grünanlagen von Ackerstraße 18 wuchern weit auf den Gehweg.

  Document 141:
  an der Ecke Bloherfelderstr./Eichenstr. Nahe der Litfaßsäule liegt seit Wochen ein defekter Rattanstuhl und er wird langsam von der Vegetation überwuchert.
Schade, dass die Menschen so etwas immer wieder wild entsorgen!



Topic 18:
  Document 3:
  Am Containerstellplatz Ecke Nedderend wurde diverser Hausmüll entsorgt.

  Document 4:
  Gefrier-Kühlschrank abgelegt

  Document 55:
  Am Containerstellplatz Brookweg/Kattowitzer Straße wurde diverser Hausmüll entsorgt, u.a. Teppiche, Spielzeug, Stühle, Katzenbaum (zerlegt), pp.



Topic 19:
  Document 14:
  Unter der Autobahnbrücke liegt Müll!

  Document 21:
  Am Ende der Straße hinter der Brücke über der Bäke wurde Hausmüll entsorgt.

  Document 245:
  Kreyenstr 41 Unter der Autobahnbrücke (Richtung Nadorster Str auf dem rechten Bürgersteig) liegt Müll



Topic 20:
  Document 196:
  wenn man von der Ofener Str. in den Rummelweg rein schaut, da ist das Schild links sehr weit nach vorne verbogen!
Stange schaut doll rostig aus!
Bitte Richten!
Nicht das es umfällt und den Gehweg oder die Str. gefährdet!

  Document 222:
  Das Spielstraßen-Schild wurde beschmiert.

  Document 229:
  Siehe Foto, angekettetes Schrottrad
## Extracted topic hierarchy (not the one we are going to use, but perhaps an interesting point of reference)
![topic_hierarchy](https://github.com/user-attachments/assets/8004594f-d8c3-4732-bf06-3b8f15ad6ea8)

# July 02, 2025 - Meeting 
- roadmap for the next weeks before deadline
- discussing clustering and deciding on categories that will be used in card sorting
- preparing card sorting

- writing instructions: Hallo :) Wir arbeiten in einem Projekt daran, den Mängelmelder der Stadt Oldenburg zu verbessern. Hier können Bürger:innen verschiedene Probleme und Verbesserungsvorschläge für den öffentlichen Raum melden - und dann wird sich darum gekümmert! Für den Mängelmelder haben wir neue Kategorien erstellt, mit dem du ein Card-Sortung durchführen sollst. Dafür sollst du die Kategorien, die wir vorgegeben haben einer Überkategorie zuordnen. Wir haben sieben Überkategorien eingestellt - davon musst du nicht unbedingt jede benutzen. Falls du eine Überkategorie benutzt, finde bitte auch einen passenden Titel für diese. Wenn du fertig bist, klicke auf "Share Results" und sende uns den so erstellten linkt zu. Vielen Dank! Hier gelangst du zum Card Sorting.

# July 03, 2025 - Card Sorting Results
## Result 1
![Card Sorting Result 1](Card Sorting/Image 2025-07-02 at 19.40.52.jpeg)
# July 04, 2025 - Meeting
## Analyzing Card Sorting
First step: Take all top-level categories as given by our card sorting participants, group them into four categories, and label them (i.e. card sorting of card sorting results).
![grafik](https://github.com/user-attachments/assets/5358e015-4470-4a2b-bbac-9e27f144637d)

Second step: Use our derived top-level categories from step 1 and assign all bottom-level categories as done by our card sorting participants to the derived categories according to the top-level category provided by the participant.
![grafik](https://github.com/user-attachments/assets/8276d68e-f969-4991-81a2-66cc877c815c)

