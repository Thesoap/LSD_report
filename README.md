# LSD_report

## Requirements, architecture, design and process

This section describes the requirements of the project, the architecture that you have chosen, the design of the actual components and the process you undertook to build them in the end.

### System requirements

Vi satte os ned og gennemgik hvordan Hackernews var opbygget og hvilke funktionaliteter det havde og hvordan vi forventede det var bygget. Derefter kiggede vi på opgavebeskrivelsen for at få idéer til hvad vi skulle have og hvilke ting vi følte ville være fede at få med ind over.
I forhold til opgave beskrivelsen var funktionaliterne vigtige og ikke de virsuele dele af hjemmesiden. Vi valgte derfor at priotere alle de endpoints som skulle laves og den simulition som var givet til os. Dette var det vigtigeste og første vi valgte at lave i vores projekt.
Derefter fokuserede vi på vores database og hvordan den kunne bygges op til at være effektiv. Dette indebar at vi skulle gøre det muligt at få svartider der var lave nok til ikke at få "timed out" på vores requests. Vi ville også gøre vi ikke havde redundant data i vores database.
Til sidst ville vi lave en hjemmeside som stadig kunne vise de forskellige posts som var blevet lagt i ned i databasen på vores forside. Vi ville gerne have vi havde noget virsuelt på vores side som varierede i forhold til den data som var blevet givet til os. 

Vi valgte ikke at priotere det mere virsuele på vores side når man gik længere ind på vores hjemmeside. Vi følte ikke dette requirement var lige så stort som de andre og det ikke havde lige så stort fokus i projektet som de andre requirements. 

This section should contain an elaborate description of the requirements for the project. This includes the scope of the Hackernews clone (what should it be able to do / what should it not be able to do).

### Development process

In this part you should show off by telling us all you know about software development processes and describe which concepts you used to structure your development.

### Software architecture

In this section you illustrate and describe the architecture of your Hackernews clone. That is, you describe how your system is structured and how the different parts interact and communicate with each other.

### Software design

Here you should sketch your thoughts on the software design before you started implementing the system. This includes describing the technical concerns you had about the system before you started development, together with all the technical components you came up with to fix these concerns and meet the requirements.

### Software implementation

This section should describe your actual implementation. Mainly how well you followed the requirements, process and software design you began with. If your system changed during this phase you should summarise the unexpected events/problems and explain how you solved them.

## Maintenance and SLA status

This section describes the process of maintaining the software over time, starting from the hand-over to the shutting down of your system. The section should be written from the viewpoint of the operator, not the developers.

### Hand-over

In this part, you should describe the hand-over of the system you were operating. Specifically you should comment on the quality of the documentation you received and whether you felt well equipped to maintaining the system.

### Service-level agreement

Here you should include the service level agreement you entered together with the group you were operating, including the metric itself and the threshold you agreed upon for that metric. If you had any disagreements about the SLA you should describe them and explain how you found an agreement.

### Maintenance and reliability

This part should contain a description on how you experienced the actual operation. Explain how you actually monitored the system to ensure that the SLA was upheld, and describe any incidents you experienced that broke (or could potentially break) the SLA. Remember to include documentation for each incident! Finally you should conclude how well the developers responded to your issues and conclude on how reliable the system was overall.

## Discussion

### Technical discussion

This part summarises both the first and second part of the report by giving an overview of the good and bad parts of the whole semester project. Be critical and honest.

### Group work reflection & Lessons learned

3.2. Group work reflection & Lessons learned
Give a short reflection on what were the three most important things you learned during the project. The lessons learned are with regards to both, what worked well and what worked not well. These reflections can cover anything from the sections above. That is, development process, architectural and design decisions, implementation, maintenance, etc. If you chose to use roles (project manager, architect, devops etc.) you should use those to reflect on whether they improved the process or not.

Additionally, focus on both, your work as developers as well as operators.
