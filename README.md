# Inside Radiator Springs 

Interactieve storywebsite voor een individueel AR project, gebaseerd op de wereld van Disney/Pixar Cars.

##  Live Prototype
Bekijk de website hier:  
https://acidkirby.github.io/insideradiatorsprings/

---

##  Over het project

Inside Radiator Springs is een interactieve web experience waarin de gebruiker een digitale roadtrip maakt door iconische locaties uit de film Cars.

In plaats van een traditionele website is gekozen voor een verhalende en visuele aanpak. De gebruiker wordt stap voor stap meegenomen langs verschillende stops, met als eindpunt een augmented reality (AR) ervaring.

---

##  Doel

Het doel van dit project is om te laten zien hoe storytelling, visueel design en webtechnologie gecombineerd kunnen worden tot een immersieve digitale ervaring.

De gebruiker:
- navigeert intuïtief door de website
- ervaart een filmische sfeer
- ontdekt locaties via scroll-interactie
- beleeft een AR-moment aan het einde van de route

---

##  Belangrijkste features

- Video hero (YouTube embed met autoplay & loop)
- Scroll-based roadtrip met meerdere story stops
-  Animaties bij scroll (Intersection Observer)
- Responsive design (mobile-first optimalisaties)
- 3D model viewer (model-viewer)
- AR-functionaliteit (WebXR / Scene Viewer / Quick Look)
-  Geluid toggle + achtergrondmuziek
-  Cinematic UI (Cars-inspired kleuren en styling)

---

##  Concept

De website is opgebouwd als een lineaire route (roadtrip), waarbij de gebruiker door de pagina scrolt alsof hij door de wereld van Cars rijdt.

De structuur:
1. Hero (intro + video)
2. Introductie van de route
3. Roadtrip met locaties (Radiator Springs → Willy’s Butte)
4. Detailmoment
5. AR experience (eindpunt)
6. Afsluiting

De AR-functionaliteit fungeert als het hoogtepunt van de ervaring.

---

##  Gebruikte technologieën

- HTML5
- CSS3 (custom styling, responsive design)
- JavaScript (DOM, events, scroll interactions)
- YouTube Iframe API
- `<model-viewer>` 
- WebXR / AR ondersteuning (Android & iOS)

---

##  Projectstructuur


/images
/models
/audio
index.html
style.css


---

##  AR ondersteuning

AR werkt alleen op ondersteunde mobiele apparaten:

- Android → Scene Viewer
- iOS → Quick Look (.usdz bestand nodig)
- Desktop → alleen 3D preview

---

##  Installatie / gebruik

1. Clone de repository:

git clone https://github.com/jouwusername/InsideRadiatorSprings.git


2. Open `index.html` in je browser  
of gebruik Live Server

---

##  Opmerking

Dit project is een fan-concept voor educatieve doeleinden.  
Niet officieel verbonden aan Disney of Pixar.

---

##  Auteur

Naam: Arion Martha - Acidkirby 
Opleiding: Hbo-Ict - 2nd year-Software engineer
Project: AR Individueel project

---

## 📸 Credits

- Disney / Pixar (Cars)
- Sketchfab (3D model)
