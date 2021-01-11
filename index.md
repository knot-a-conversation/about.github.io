# K(not) a Conversation
### A Neural Knotwork Prototype

## Project Synopsis
**K(not) a Conversation** is an installation exploring the concepts of artificial intelligence, creativity and labour. Inspired by ancient indigenous communication systems of Quipu knots, it instigates a communication and reflection process through the use of knots and AI systems. 

## Concept Note
The installation exists in two ways, physically and virtually. It consists of a sculptural element, using knots and neurons as visual and conceptual references, a website and a web-based detection app to allow interaction with the sculpture. The piece is designed as part of an open process, demonstrating the proof-of-concept with a working prototype.  

Rooted in Nayeli Vega Vargas’ artistic research on knots as symbolic systems that can be used to communicate specific information, the prototype investigates concepts of creativity and labour in relation to artificial intelligence. By mixing modern and ancient communication technologies, a reflection process is engaged. Hereby, the knots function as information carriers that can be read by the AI. This method is inspired by Quipu, a knot-based technology to record information related to the organisation of the empire’s municipalities developed by the Inka people of the Andean region. The AI is trained to detect the given knots, decode the questions embedded by the artists and respond with answers from its own text prediction AI model. These questions revolve around creativity, autonomy, labour, behaviours, kinship and visibility. Just like in the topology of mathematical knots, which are used in this prototype, the machine-driven communication with itself is potentially endless. It leads to unexpected results that question our understanding and concepts of the human, the natural and the artificial. 

PROJECT LINK: bit.ly/knot-a-conversation

## Process Notes
The project is based on a collaborative process between creative technologist Ambika Joshi, material-textile designer Nayeli Vega Vargas and media artist Thomas Heidtmann. As part of the befantastic CoLab Fellowship, it combines their different professions, methodological approaches and technical skills to explore artistic and technological implications of artificial intelligence.

After the intense 14-day fellowship – which resulted in the roughly outlined project idea – a two-week-long realisation phase followed, during which the initial brainstorming was further extended and a prototype was built. After exploring conceptual directions and the visual language (Fig. 1–4), prototyping of the sculpture and website started.

Drawing inspiration from the scientific illustrations of Santiago Ramón y Cajal (1852–1934) and Picasso’s Constellations drawings (1924), a prototype was developed. The knots, which are used for the prototype, were obtained from mathematical algorithms, converted to meshes and integrated into a neuronal structure with the help of the open source 3D software Blender (Fig. 5–6). 

A website was designed to allow access to the project during COVID-19-times. It contains a virtual representation of the sculpture that eventually will be physically installed in the future. The model was then imported in A-Frame, a HTML framework which allows easy access and development of 3D environments for web browsers. Once the website was successfully tested, it got refined and hosted on GitHub pages (Fig. 8). 

The web-based mobile detection system was a more complex part of the project. It had to be thoroughly tested and developed. To detect the knots, we used the Teachable Machine image classification developed by Google. Through this machine learning model each knot was classified and a question was assigned to it. GPT-3 by OpenAI was used to generate responses which the user can access through the mobile detection app. The entire app was built on p5.js, a popular JavaScript library. (Fig. 9)
