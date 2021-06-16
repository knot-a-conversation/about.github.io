---
title: Version 2
permalink: /projects/v2-vorspiel-transmediale-ctm
image: 
  path: /assets/v2-vorspiel-transmediale.jpg
  thumbnail: /assets/v2-vorspiel-transmediale-thumbnail.jpg
  caption: "Version 2 at Vorspiel / transmediale & CTM"
read_time: false
date: 2021-02-25
vimeoId: 516739403
driveId: 1eaz-6p8M53AWMdMxgGI_hsKJnZ3PGDrO/preview

actions:
  - label: "Digital Prototype"
    url: "https://knotaconversation.art/sculpture/"

---

# Vorspiel / transmediale & CTM
Real conversations and a physical prototype.

## About
For [Vorspiel / transmediale & CTM](https://vorspiel.berlin/) the artists present the second version of the project. It completes the [original concept](https://befantastic.in/2020/11/16/knot-a-conversation/) developed during the CoLab Fellowship by introducing an enhanced digital version and by showcasing a first physical sculpture prototype. 

The event is part of Lacuna Lab's event series [Scattered Partners](https://lacunalab.org/events/transmediale-vorspiel-2021-or-scattered-partners).

*Access to OpenAI’s GPT-3 kindly supported by [Dara](https://www.dara.network/), a global community for change-makers & cultural professionals. Special thanks to [Hasan S.](https://curiouswala.com/) and [Anushka Trivedi](https://instagram.com/ophelia.game) for additional help with the GPT-3 implementation, and to [Nuño de la Serna](https://action-io.com/) for editing the video.*

*Nayeli Vega Vargas is supported by Elsa Neumann Scholarship of the State of Berlin.*

*Thomas Heidtmann wird gefördert durch die Senatsverwaltung für Kultur und Europa des Landes Berlin.*

{% include vimeoPlayer.html id=page.vimeoId %}

<br />
## Entanglements between datasets of today and datasets of the past
### How does it work?

Starting with the simpler machine learning models of classifying images, the smartphone app recognizes the knots in the sculpture. Each knot reveals a question the artists have embedded. These questions are provocations for the viewer about the relationship between creativity and Artificial Intelligence systems. The questions prompt a text-based machine learning model called [GPT-3](https://github.com/openai/gpt-3). It is a widely recognised Machine Learning model, that uses human text prompts to generatively produce text. While the responses aren’t always coherent, they are able to maintain some relatability to the artists’ input and are grammatically correct. These responses are reproduced on the smartphone app along with a computer-generated voice. The project’s second iteration adds a layer of human-like embodiment to the conversations with AI (Fig. 01).

PROTOTYPE LINK: [https://knotaconversation.art/sculpture/](https://knotaconversation.art/sculpture/)

*To use the digital prototype a desktop pc or laptop and a separate smartphone are required. Real-time interaction with the digital sculpture and GPT-3 is possible from 25 February 2021, 7 pm CET to 28 February 2021, 11.59 pm CET.*

#### Instruction Video
{% include googleDrivePlayer.html id=page.driveId %}

### Datasets
 
At the base of every AI and Machine Learning system are datasets. A mild mirroring of the quipu knots that were also datasets with dedicated *khipu kamayuq*, the oral record keepers of the knots. 

The project maintains a database of all the machine-generated responses. This database gives an insight into the patterns and “thoughts” of the machine.

DATABASE LINK: [https://knotaconversation.art/answers/](https://knotaconversation.art/answers/)

### Physical prototype process

For the second iteration of the project, a physical prototype was constructed. It resembles a neural structure crossed by closed knots which can be identified by the AI by the number of crossings. To materialize these neural structures and knots a 3D printer was used. In advance, the Open Source 3D rendering software Blender helped to prepare the files from the digital prototype. After this, manual assembly and video documentation of the final prototype followed (Fig. 02–05).

In that way, not only the appearance but also the production process of the sculpture represent symbolically the discussed topics at hand.


### Supporting Images
![](/assets/v2-flowchart.jpg)
**Fig. 01:** Flow chart of the app workflow.

![](/assets/v2-physical-prototype-pieces.jpg)
**Fig. 02:** Sliced 3d printed pieces before and after assembly.

![](/assets/v2-physical-prototype-pieces-manual-labour.jpg)
**Fig. 03:** Manual labour for details and coating.

![](/assets/v2-physical-prototype-finished.jpg)
**Fig. 04:** The finished physical prototype. 

![](/assets/v2-docu-process.jpg)
**Fig. 05:** Documentation of the physical prototype.


### Additional tech stack for v2 
See the the tech stack for v1 here: [https://knotaconversation.art/projects/v1-colab](https://knotaconversation.art/projects/v1-colab)

#### Server and database management
- [Expressjs](https://expressjs.com/) - A web framework to manage server side requests
- [Firebase](https://firebase.google.com/docs/database) - A cloud hosted "Database-as-a-Service"

#### GitHub repository
 [https://github.com/knot-a-conversation](https://github.com/knot-a-conversation)
 
## Partner

![](/assets/logos/v2-logos.png)
