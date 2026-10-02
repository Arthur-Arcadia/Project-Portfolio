# Zirui Zhou(Arthur) — Interaction Design Portfolio

Master of Interaction Design student at The University of Queensland.

I am interested in **Human-Computer Interaction (HCI), Interaction Design, UX Research, and Interactive Systems**. My projects explore how people interact with digital, physical, and spatial systems through research, prototyping, and iterative design.

## About Me

I am an Interaction Design student with an interest in designing interactive experiences that connect **people, technology, and context**.

My work typically combines:

* User research and qualitative methods
* Interaction design and prototyping
* Human-Computer Interaction
* Social and collaborative interaction
* Physical computing
* Web-based interactive experiences
* Unity and XR
* User testing and design iteration

I am particularly interested in how interaction design can respond to **social behaviour, real-world contexts, and the relationship between people and interactive systems**.

---

# Selected Projects

## 01 — Pally — Discord Bot for Better Social Gameplay

**Type:** Team-based interaction design project  
**Role:** UX research and interaction design  
**Tools:** Discord, Figma, GitHub  
**Status:** Interactive prototype

### Overview

Pally is a Discord bot prototype for multiplayer gaming groups. It provides a control panel with three tools: Random Pick, Trait Picker, and Excuse Generator. When the bot is added to a server, it posts the panel; users can also bring it up with `/tools`.

### Problem

Players may hesitate to express their preferences during social gaming because they do not want to disappoint teammates, disrupt the group atmosphere, or appear antisocial. The project initially explored game addiction, but the team later refined its focus to **social compliance and social power dynamics** in multiplayer groups.

Pally explores playful interactions around group selection, sharing impressions, and finding ways to leave or pause a session. It is not a clinical intervention or a tool for diagnosing problematic gaming.

### Design Opportunity

Explore how lightweight Discord interactions can support social gaming groups when members feel uncomfortable expressing preferences directly.

### Design Process

The team reviewed relevant research, conducted two rounds of player interviews, and used affinity mapping to identify recurring issues around group decisions, post-game expression, and leaving a session. These findings informed the feature concepts and prototype flows.

The team also prepared simulated gaming scenarios to compare group interactions with and without Pally. The planned evaluation uses Groupware Heuristics and follow-up interviews to examine collaboration and social dynamics.

### Key Interaction Concepts

- **Random Pick:** After a user clicks the button, the bot posts a prompt visible to the server, runs a short rolling animation, and selects a name from the current voice-channel member list. The selected member’s name and description are then displayed.
- **Trait Picker:** The bot randomly selects a member in the voice channel and introduces the activity. Voice-channel members receive private messages with word options to submit. After submissions, a prompt appears and the bot posts an AI-written summary for everyone to see.
- **Excuse Generator:** The bot privately presents categories for the user to choose from. It then generates a copyable excuse; the user can select “Try another” to replace it with a new one.

### My Contribution
- Analyzed the target audience, stakeholder relationships, and existing solutions for the Project pitch.  
- Communicate actively with the teaching team, and help the team narrowed the scope of the project.  
- COntributed to the team's exploration of social pressures in multiplayer aming and possible design responses.  

### Key Learning

The project shifted from treating prolonged play as an individual self-control problem to examining how group relationships and social influence shape players’ choices. Pally explores playful ways to support group interaction; the planned evaluation will examine how these interactions affect the experience.

### Project Links

- [Project repository](https://github.com/Arthur-Arcadia/Pally)

---

## 02 — SqueezeCare: Support for People Living Alone When They Are Unwell

**Type:** UX Research / Interaction Design / Physical–Digital Concept Design  
**Role:** User Research / Interaction Design / Concept Development  
**Tools:** Figma / Google Forms / Interview Transcription / Sketching  
**Status:** Research and concept proposal; no working interactive prototype

![Illustrative SqueezeCare concept from the team’s final report](media/concept-sketch.png)

## Overview

SqueezeCare proposes a soft handheld companion for international young people who feel unwell while living alone in an unfamiliar environment. A deliberate squeeze would request support, while a response from another person would return through gentle tactile feedback. An optional voice interaction would help the user summarise and translate their own symptom description.

The project developed through three rounds of research and reframing. Its final direction focuses on emotional reassurance, low-effort human connection, and communication assistance. The outcome is a documented design proposal and exhibition material, supported by interviews, questionnaires, and an exploratory study using existing physical objects.

## Design Question

How might we help international young people living alone feel supported when they feel unwell in an unfamiliar environment?

Interviews revealed that difficulty seeking help extends beyond finding a service. Participants also described language uncertainty, isolation, reluctance to inconvenience others, and the effort involved in explaining their condition.

## Research and Iteration

| Stage | Main activities | Design development |
| --- | --- | --- |
| Iteration 1 | Brainstorming, background reading, two preliminary interviews | Explored night-time medical access, safety, and privacy. Early frameworks were too broad and insufficiently connected to evidence. |
| Iteration 2 | Team interviews with 18 participants, open coding and affinity mapping, a 37-response survey | Examined unfamiliar healthcare systems, communication barriers, support gaps, and technology/privacy preferences. |
| Iteration 3 | A 19-response support-needs survey, exploratory object comparison, literature review, further ideation | Reframed the concept around reassurance, lightweight contact, and symptom communication. |

In the exploratory interaction study, five of seven usable sessions favoured a squeezable object as the first choice, and all seven included one in their top three. This informed the proposed material and interaction, without establishing the effectiveness of the finished concept.

## Proposed Experience

- A light squeeze would initiate a support signal to a user-selected recipient.
- A supporter could squeeze back, with the response represented through vibration and potentially light.
- Squeeze rhythm, intensity, and duration would shape the proposed tactile response.
- A longer squeeze would activate guided voice input for a translated symptom summary on the user’s phone.

These interactions remain design proposals. Pressure sensing, connected devices, haptic output, and translation were not implemented as a functioning system.

## My Contribution

I conducted three interviews within the team’s larger study and helped develop both questionnaires. My contributions included research aims, question sequencing, answer options, participant choice, and the focus on language barriers and symptom expression.

I independently designed and led the object-preference study, using video and think-aloud prompts to understand why participants selected particular forms and interactions. I also developed the early conceptual models and areas of investigation, recorded and analysed team/tutor discussions, reviewed literature, and synthesised solution-exploration findings.

For the exhibition, I prepared the Iteration 2 research panels. The final SqueezeCare product poster is a team output; my personal portfolio attributes its creation to another team member.

## Outcome and Learning

The project produced a research-informed concept, proposed requirements, interaction flows, and exhibition materials. It did not produce a working connected device or establish clinical or wellbeing outcomes.

My main learning was how to connect a conceptual model to both evidence and a concrete next research activity. Earlier versions either introduced solutions too soon or repeated the problem without advancing it. Iteration 3 provided a clearer relationship between observed needs, interaction qualities, and unresolved questions.

## Case Study Links
[Case Study](https://github.com/Arthur-Arcadia/Squeezecare/blob/main/CASE-STUDY.md)
[Github](https://github.com/Arthur-Arcadia/Squeezecare/tree/main)

---

## 03 - The Witch’s Puppet — A Cooperative Physical Computing Game

**Type:** Physical Computing / Haptic Interaction / Cooperative Carnival Game  
**Role:** Physical Interaction Design / Hardware Prototyping / Embedded Programming  
**Tools:** ESP32, Arduino Uno, ESP-NOW, Ultrasonic Sensors, Hall Sensors, Vibration Motors, Servo Motors, 3D Printing  
**Status:** Working prototype exhibited and tested with participants

### Overview

The Witch’s Puppet is a two-player carnival game exploring cooperation through haptic communication and information asymmetry.

One player acts as the witch, who can see the game field but remains confined to a cage. The other acts as the puppet, whose sight and hearing are restricted but who can move around the field.

Using a six-button controller, the witch sends vibration signals to the puppet’s wearable system. The players must establish a shared understanding of these signals to navigate the space, avoid traps, and collect three keys to unlock the cage.

When the puppet triggers a trap, a motor-driven mechanism punishes the witch. This makes the person giving instructions bear the consequences of their guidance.

### Design Goal

Explore how players develop communication and cooperation when they have different abilities to perceive and act within the same environment.

The experience focuses on:

- establishing a shared communication system through vibration;
- coordinating movement with limited sensory information;
- adapting to another player’s interpretation of signals;
- sharing responsibility for navigation and mistakes;
- creating an engaging cooperative carnival experience.

### Interaction Flow

1. The players discuss their strategy and test the vibration mappings.
2. The witch presses controller buttons to send wireless signals.
3. Vibration motors on the puppet’s wearable system communicate movement instructions.
4. The puppet follows the signals to navigate the field and collect keys.
5. Ultrasonic traps detect nearby movement and activate the witch’s punishment mechanism.
6. The puppet places each key into its corresponding slot.
7. Hall sensors detect the correctly placed keys.
8. Once all three keys are in place, a servo releases the cage lock.

The puppet can carry only one key at a time. The game has no time limit, allowing players to develop their communication through practice.

### Key Interaction Concepts

- **Information asymmetry:** The witch can observe the field but cannot navigate it, while the puppet can move but lacks direct visual and auditory information.
- **Haptic communication:** Players translate button presses and body-based vibration signals into a shared movement vocabulary.
- **Cooperative navigation:** Successful movement depends on both players adapting to one another.
- **Shared consequences:** Triggering a trap affects the player providing guidance.
- **Physical state feedback:** LEDs, motors, key slots, and the cage lock communicate events and progress.

### Technical Implementation

The final team prototype combined several connected subsystems:

- **Wireless control and wearable feedback:** A six-button controller sends ESP-NOW messages to six wearable ESP32 modules, each connected to a vibration motor.
- **Proximity traps:** Four ESP32-based traps use ultrasonic sensors to detect nearby objects and transmit trigger events.
- **Punishment mechanism:** A receiving ESP32 activates a motor-driven mechanism when a trap is triggered.
- **Key detection and cage release:** An Arduino Uno and three Hall sensors detect magnets in the keys. Correct placement of all three keys activates the cage-lock servo.
- **Physical fabrication:** 3D-printed enclosures protect and position the trap electronics.

ESP-NOW enables direct communication between ESP32 modules without requiring a shared Wi-Fi network.

### My Contribution

I was responsible for the trap and punishment subsystem.

My work included:

- defining how traps should detect the puppet and trigger consequences for the witch;
- exploring an initial Time-of-Flight sensing approach based on deformation of a stepping surface;
- replacing that approach with ultrasonic proximity detection after testing physical constraints;
- developing ESP32 sender and receiver logic using ESP-NOW;
- integrating sensor readings, LED indicators, and motor activation;
- designing and iterating 3D-printed enclosures to secure the electronics and wiring;
- testing detection responsiveness and communication between the traps and punishment mechanism.

### Evaluation and Iteration

The trap design changed substantially during prototyping. The initial stepping-surface concept was difficult to conceal while providing sufficient space and protection for the electronics. Ultrasonic proximity sensing allowed traps to be positioned beside the player’s path.

The enclosure was also revised after the first version allowed components to move inside it. A second version used measured compartments to hold the breadboard, ESP32, and cables more securely.

The complete game was tested during an exhibition with participants of different ages. Observations focused on communication, cooperation, and task completion.

Most groups completed the game within ten minutes. Longer sessions were associated with unclear signal mappings, reduced vibration perception through thick clothing, misunderstandings of the objectives, or misinterpreted instructions.

### Key Learning

The project showed how players can develop a shared communication system through repeated physical interaction. It also highlighted how sensing methods, enclosure geometry, clothing, and actuator behaviour directly shape the experience.

For my subsystem, prototyping helped connect the intended gameplay behaviour with practical requirements for detection, wireless communication, and physical construction.

### Project Demo

[Watch the project demonstration](https://www.youtube.com/watch?v=2GjQerEt0JA)

---

## 04 — Cultural Heritage Interactive Website

**Type:** Web Interaction / Digital Heritage / Information Design
**Role:** Interaction Design / UX / Front-end Development
**Tools:** HTML / CSS / JavaScript / REST APIs / Fetch / FormData / Live Server  
**Status:** Front-end prototype with external API integrations  

### Overview

An interactive website that presents Chinese cultural heritage through artifact collections, geographic exploration, storytelling, and community participation. The project brings together content about the Sanxingdui archaeological site, the Terracotta Army, and the Mogao Grottoes.  

The experience includes a virtual museum, an image-based exploration map, a detailed Mogao Grottoes page, and an API-backed cultural discussion forum.

### Design Goal

Make cultural content easier to explore through complementary entry points: objects, places, and stories. The design also provides a space for visitors to contribute to cultural discussion.  

### Design Process

- Used documented personas to identify needs around artifact exploration, cultural learning, and sharing findings.
- Organised the site into a visitor homepage, virtual museum, exploration map, cultural showcase, and community area.
- Developed and revised page layouts and interactive components through implementation testing.
- Documented accessibility findings and revised typography, colour choices, and responsive layouts.

## Core Experiences

| Experience | Implemented interaction |
| --- | --- |
| Virtual museum | Switch between three cultural collections and open enlarged artifact images. |
| Exploration map | Select one of three markers on a China map to read a short site introduction. |
| Cultural storytelling | Read a detailed Mogao Grottoes page, including the Nine-Colored Deer story and Cave 17. |
| Community forum | Submit a post, retrieve existing posts, and manually refresh discussions through an external API. |
| Community participation | Submit contact details, a message, and an optional photo through a community join form. |

## Technical Implementation

Built with HTML, CSS, and vanilla JavaScript. CSS is separated into shared foundations, reusable components, and page-specific styles. JavaScript manages category switching, image enlargement, map popups, and form interactions.

The forum and community form use course-provided REST endpoints through Fetch and FormData. They provide submission feedback and handle request failures. The repository contains the front end; the API service is hosted separately.

## My Contribution

- Defined the information structure and page navigation from persona-based needs.
- Designed the visual hierarchy and interaction flows for cultural browsing and community participation.
- Implemented the front-end pages and their interactive components.
- Integrated external APIs for forum posts and community submissions.
- Documented accessibility issues and iterated the interface during development.

AI-assisted content, translation, and code support are acknowledged in the project's accompanying documentation. Generated material was adapted and reviewed as part of the implementation process.

## Accessibility and Prototype Scope

The implementation includes responsive styles, image descriptions, labelled form fields, and navigation aids. An accessibility audit is documented, but a completed post-revision audit is not provided. Further work is needed on keyboard interaction and consistent accessibility across pages.

The detailed cultural showcase currently covers Mogao Grottoes. Links from the other cultural cards and map markers also lead to that page. The community join form does not implement account authentication; event and artisan-product cards are illustrative content. The site does not provide a complete bilingual experience.

## Key Learning

The project developed my ability to connect cultural information with web interaction design, implement API-backed participation, and use accessibility findings to guide interface revisions. It also highlighted the need to align navigation labels and content coverage with the capabilities of a working prototype.

## Project Link

- [Source code](https://github.com/Arthur-Arcadia/Cultural-Heritage-Website-Showcase)  
- [Website Demo](https://arthur-arcadia.github.io/Cultural-Heritage-Website-Showcase/)  

# 05 — XR 3D Modelling Tool

**Type:** XR / Spatial Interaction / 3D Interaction  
**Role:** Interaction Design / Unity Development / Prototyping / User Testing  
**Tools:** Unity / C# / Meta XR / OpenXR / Meta Quest  
**Status:** Evaluated VR prototype  
**Year:** 2026

## Overview

A VR workshop for creating and manipulating primitive shapes through controller-based spatial interaction. Users can create shapes, move and rotate them, adjust their scale with two hands, delete them, and switch gravity on or off.

The prototype combines a medieval-style workspace with three tutorial areas and an open workshop containing modelling challenges. It explores how direct manipulation and guided practice can support learning in an immersive 3D environment.

![Primitive shapes in the VR workshop, captured from the walkthrough](media/workshop.png)

## Design Goal

Explore an alternative to screen-based 3D manipulation by letting users work with objects in surrounding space. The design focuses on helping users understand the relationship between controller actions, transformation modes, and object behaviour.

During iteration, the focus shifted from immersion alone towards clearer guidance and more understandable interactions. The project investigates these goals through a working prototype; it does not establish superiority over desktop modelling software.

## Core Interactions

| Interaction | Prototype behaviour |
| --- | --- |
| Shape creation | Generate primitive shapes from the workbench. The testing plan describes revised creation that places a cloned shape directly into the user's hand. |
| Direct manipulation | Grab, move, and rotate shapes with VR controllers. |
| Two-handed scaling | Adjust object size and switch between uniform and non-uniform scaling modes. |
| Deletion | Remove shapes through the trash-can interaction introduced in the first tutorial. |
| Gravity control | Switch gravity on or off to explore falling or suspended arrangements. |
| Guided practice | Progress through creation/deletion, scaling, and gravity tutorials before exploring workshop challenges. |

Combining shapes in the workshop means arranging individual objects into a construction. Dedicated grouping, ungrouping, or mesh-editing tools are not established by the supplied demonstration and evaluation materials.

## Design Process

The final report describes three prototype iterations. Earlier testing challenged the assumption that users would understand the interactions with little guidance. The final iteration introduced dedicated tutorial areas and explanatory boards before open-ended workshop practice.

The evaluation combined task timings with post-test ratings and written feedback. The report also reflects on removing think-aloud from later sessions because speaking interrupted actions and affected time measurements.

## Evaluation and Findings

The final evaluation involved **four students and one tutor**. All five rated the overall experience **4/5**.

| Experience | Mean rating out of 5 |
| --- | ---: |
| Shape creation and deletion tutorial | 4.8 |
| Scaling tutorial | 4.4 |
| Gravity control tutorial | 4.2 |
| Overall experience | 4.0 |

Participants valued the manipulation features and several found the tutorials helpful. However, feedback exposed unclear controller-button mappings, excessive tutorial text, difficulty controlling scaling, and bugs affecting state feedback. The report records that one participant skipped the gravity tutorial and needed verbal clarification during scaling.

These findings support further refinement of the learning experience. The small sample and assisted interactions do not demonstrate that every participant independently completed every task or that cognitive load was measurably reduced.

## My Contribution

- Developed the interaction concept and spatial manipulation workflow.
- Implemented and iterated the Unity prototype and controller interactions.
- Designed the tutorial sequence and workshop practice activities.
- Planned and evaluated task-based testing using timings and questionnaires.
- Synthesised feedback into priorities for visual guidance, controller labels, and clearer state feedback.

## Next Design Priorities

Replace lengthy instructions with shorter steps and progressive prompts; make controller buttons and gravity/scaling states easier to identify; resolve documented state bugs; and introduce challenges with increasing difficulty. Duplicating an already adjusted object was also suggested by the tutor. These are proposed improvements, rather than verified additions to the demonstrated prototype.

## Key Learning

Spatial manipulation still requires explicit guidance. The project showed why designers need to test the connection between users' expectations and controller behaviour, rather than assume that a physical-looking interaction will explain itself.

## Project Link

[Github](https://github.com/Arthur-Arcadia/XR-3D-Modeling-Tool)

---

# Skills & Methods

## UX / HCI

* User Interviews
* Qualitative Research
* Affinity Mapping
* Thematic Analysis
* User Personas
* User Journey Mapping
* Problem Framing
* Design Opportunities
* User Testing
* Interaction Design
* Prototyping
* Usability Evaluation

## Interaction Design

* Social Computing
* Collaborative Interaction
* Tangible Interaction
* Spatial Interaction
* Human-Computer Interaction
* Interactive Systems
* Physical Computing
* XR Interaction
* Information Design

## Tools & Technologies

### Design

* Figma
* [Adobe Creative Cloud, if applicable]

### Development

* HTML
* CSS
* JavaScript
* C#
* Unity

### Interactive / Physical Computing

* Arduino
* ESP32
* Sensors
* Servo Motors
* ESP-NOW
* [Other technologies]

### XR

* Unity
* Meta XR
* OpenXR

---

# Design Approach

Across my projects, I am interested in the relationship between **people, technology, and context**.

My design process generally follows:

**Understand → Define → Explore → Prototype → Test → Iterate**

I try to use research and testing to understand not only whether an interaction works, but also **why people behave in particular ways and how the surrounding social or physical context influences interaction**.

---

# Contact

**Email:** arthur.zhouzr@gmail.com  
**LinkedIn:** [LinkedIn Profile](http://www.linkedin.com/in/zirui-zhou-3b5752399)

---

# Project Status

| Project                           | Area                                      | Status                   |
| --------------------------------- | ----------------------------------------- | ------------------------ |
| Pally                             | Social Computing / HCI                    | Prototype / User Testing |
| SqueezeCare                       | UX Research / Healthcare Interaction      | Research / Prototype     |
| Interactive Physical Installation | Physical Computing / Tangible Interaction | Prototype                |
| Cultural Heritage                 | Web Interaction / Information Design      | Completed                |
| XR Modelling                      | XR / Spatial Interaction                  | Prototype                |

