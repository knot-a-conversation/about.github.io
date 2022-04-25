---
title: Version 1
permalink: /projects/v1-colab
image: 
  path: /assets/hero/v1-colab-hero.jpg
  thumbnail: /assets/thumbnails/v1-colab-thumbnail.jpg
  caption: "Version 1 at CoLab"
read_time: false
date: 2020-10-30
driveId: 1_1PjcS-FtXqFEl88CHzJMv4wgD5IX4aj/preview

actions:
  - label: "Digital Prototype"
    url: "https://ambikajo.github.io/knot-a-conversation/"

---

# CoLab Fellowship
The idea for K(not) a Conversation is born.

<div class="embed-responsive embed-responsive-16by9">
<iframe width="560" height="315" src="https://www.youtube.com/embed/mScIl9BM_HM?start=401" class="align-center" alt="" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

[BeFantastic’s CoLab Fellowship](https://befantastic.in/) was offered online in October and November 2020 to 23 international Fellows from Germany, UK and South Asia. The fellowship brought together creators from diverse arts and design disciplines to meet, learn and make Artificial Intelligence & Machine Learning based interactive artworks together.

During the fellowship the idea for K(not) a Converation came to life as a digital prototype.

## Concept Note
The installation exists in two ways, physically and virtually. It consists of a sculptural element, using knots and neurons as visual and conceptual references, a [website](https://ambikajo.github.io/knot-a-conversation/) and a web-based detection app to allow interaction with the sculpture. The piece is designed as part of an open process, demonstrating the proof-of-concept with a working virtual prototype. 

{% include googleDrivePlayer.html id=page.driveId %}
<br />

Rooted in Nayeli Vega Vargas’ artistic research on knots as symbolic systems that can be used to communicate specific information[^1], the prototype investigates concepts of creativity and labour in relation to artificial intelligence. By mixing modern and ancient communication technologies, a reflection process is engaged. Hereby, the knots function as information carriers that can be read by the AI. This method is inspired by Quipu, a knot-based technology to record information related to the organisation of the empire’s municipalities developed by the Inka people of the Andean region. The AI is trained to detect the given knots, decode the questions embedded by the artists and respond with answers from its own text prediction AI model. These questions revolve around creativity, autonomy, labour, behaviours, kinship and visibility. Just like in the topology of mathematical knots, which are used in this prototype, the machine-driven communication with itself is potentially endless. It leads to unexpected results that question our understanding and concepts of the human, the natural and the artificial.

PROJECT LINK: [bit.ly/knot-a-conversation](https://bit.ly/knot-a-conversation)

## Process Notes
The project is based on a collaborative process between creative technologist Ambika Joshi[^2], material-textile designer Nayeli Vega Vargas[^3] and media artist Thomas Heidtmann[^4]. As part of the befantastic CoLab Fellowship[^5], it combines their different professions, methodological approaches and technical skills to explore artistic and technological implications of artificial intelligence.

After the intense 14-day fellowship – which resulted in the roughly outlined project idea – a two-week-long realisation phase followed, during which the initial brainstorming[^6] was further extended and a prototype was built. After exploring conceptual directions and the visual language (Fig. 1–4), prototyping of the sculpture and website started.

Drawing inspiration from the scientific illustrations of Santiago Ramón y Cajal (1852–1934) and Picasso’s Constellations drawings (1924), a prototype was developed. The knots, which are used for the prototype, were obtained from mathematical algorithms, converted to meshes and integrated into a neuronal structure with the help of the open source 3D software Blender (Fig. 5–6). 

A website was designed to allow access to the project during COVID-19-times. It contains a virtual representation of the sculpture that eventually will be physically installed in the future. The model was then imported in A-Frame, a HTML framework which allows easy access and development of 3D environments for web browsers. Once the website was successfully tested, it got refined and hosted on GitHub pages (Fig. 7–8). 

The web-based mobile detection system was a more complex part of the project. It had to be thoroughly tested and developed. To detect the knots, we used the Teachable Machine image classification developed by Google. Through this machine learning model each knot was classified and a question was assigned to it. GPT-3 by OpenAI was used to generate responses which the user can access through the mobile detection app. The entire app was built on p5.js, a popular JavaScript library. (Fig. 9)

## Supporting Images
![](/assets/images/01_KAC_concept_quipur.jpg)
**Fig. 01: Left:** taken from the Ethnological Museum of Berlin. **Right:** Facsimile of a drawing by Felipe Guaman Poma from his 'El Primer Nueva Coronica y Buen Gobierno'. It is the only extant 'Codex' from Peru that shows drawings of 16thC Peruvian life.- The 'Keeper of the Quipu' or 'Quipucamayoc'. 
Country of Origin: Peru Culture: Inca. 

![](/assets/images/02_KAC_concept_knot_structure.jpg)
**Fig. 02:** Moodboard inspiration. Left top: drawing from Santiago Ramón y Cajal (Cajal's Neuronal Forest: Science and Art). **Left bottom:** Khipu with Summary Cords, Inka, 1450–1534 CE, Dumbarton Oaks collection. **Center top:** Time Ball (mnemonic device) Canada, created before 1920, National Museum of the American Indian, Smithsonian Institution. **Center middle:** The hands of Rusten Hogness, Donna’s partner, learning Ma’ii Ats’áá’ Yílwoí, in English “Coyotes Running Opposite Ways.” Coyote is the trickster who constantly scatters the dust of disorder into the orderly star patterns made by the Fire God, setting up the non-innocent world-making performances of disorder and order that shape the lives of terran critters (Haraway, 2016). **Center bottom:** The Constellations drawings are a series of sketches by Pablo Picasso drawn on sixteen pages of a notebook in 1924. **Right top:** drawing from Santiago Ramón y Cajal (Cajal's Neuronal Forest: Science and Art). **Right bottom:** The Neural Network Zoo, The Asimov Institute.

![](/assets/images/03_KAC_concept_drawing.jpg)
**Fig. 03:** Concept drawing, first ideas for the creation of the prototype.

![](/assets/images/04_KAC_concept_miroboard.JPG)
**Fig. 04:** Collection of the group’s ideas, questions, visual references and inspirations on Miro whiteboard. 

![](/assets/images/05_KAC_discussing_knots.jpeg)
**Fig. 05:** An initial meeting of the team discussing and understanding the possibilities of using 3D knots.

![](/assets/images/06_KAC_3dmodel_WIP.png)
**Fig. 06:** Working on 3d model – with inspiration from human neurons, neural network schematics and mathematical knots, a sculpture was developed in the 3D software Blender. 

![](/assets/images/07_KAC_machine-training.jpg)
**Fig. 07:** Machine training – using Google’s Teachable Machine to classify the various knots in the sculpture. These will be used for the detection model on the mobile app.

![](/assets/images/08_KAC_website.jpg)
**Fig. 08:** Website development – hosting the virtual sculpture as a web app. This uses 3D frameworks “A-Frame” and “threejs”. 

![](/assets/images/09_KAC_detection_app.jpg)
**Fig. 09:** Detection app
Using the image classification model from Teachable Machine the mobile web app is able to recognise the various knots in the sculpture. Each knot represents a question devised by the team and the machine gendered answers based on GPT-3 Machine learning model

## Bibliography, references and tech stack     

- [The Nooscope Manifested](https://nooscope.ai/)
- [Lisa Nakamura – Indigenous Circuits](https://lnakamur.files.wordpress.com/2011/01/indigenous-circuits-nakamura-aq.pdf)
- [Neural Networks Architecture](https://www.asimovinstitute.org/neural-network-zoo/)                    
- [Making Kin with the Machines](https://jods.mitpress.mit.edu/pub/lewis-arista-pechawis-kite/release/1)
- [Neuronal Forest](https://www.humanbrainproject.eu/en/follow-hbp/news/cajal-s-neuronal-forest-new-book-by-javier-defelipe/)
- [Towards a poetics of artificial superintelligence](https://medium.com/after-us/towards-a-poetics-of-artificial-superintelligence-ebff11d2d249)

### Tech stack 
#### Website
- [aframe.io](https://aframe.io) – a web framework for VR experiences
- [Blender](https://blender.org) – open source 3D modelling software 

#### Mobile web-based detection app
- [Teachable machine](https://teachablemachine.withgoogle.com/) – a GUI based machine learning tool for image classification
- [p5.js](https://p5js.org/) is a JavaScript library for creative coding, with a focus on making coding accessible and inclusive for artists, designers, educators, beginners, and anyone else
- [GPT-3](https://github.com/openai/gpt-3) – Generative Pre-trained Transformer 3 is an autoregressive language model that uses deep learning to produce human-like text. It is the third-generation language prediction model in the GPT-n series created by OpenAI

#### GitHub repository
 [https://github.com/knot-a-conversation/prototype-I_colab](https://github.com/knot-a-conversation/prototype-I_colab)


## Partner

![](/assets/logos/v1-logos.png) 

[^1]:[https://yokoiki.com/2020/10/18/codes-in-knots-2/](https://yokoiki.com/2020/10/18/codes-in-knots-2/)
[^2]:[https://computationalmama.xyz](https://computationalmama.xyz)
[^3]:[https://yokoiki.com](https://yokoiki.com)
[^4]:[http://thomasheidtmann.de/](http://thomasheidtmann.de/)
[^5]:[https://befantastic.in/colab/](https://befantastic.in/colab/)
[^6]:[https://miro.com/app/board/o9J_khNZQwE=/](https://miro.com/app/board/o9J_khNZQwE=/)

