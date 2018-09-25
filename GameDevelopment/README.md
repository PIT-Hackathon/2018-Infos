# Game Development
Das Thema 'Game Development beim [PIT-Hackathon 2018](https://github.com/PIT-Hackathon/2018-Infos) umfasst die erste Phase der Spieleentwicklung, von der Erstellung eines Konzepts bis zum lauffähigen Prototypen. Dabei werdet ihr diverse Rolle wie Game Designer, Game Developer, Visual Artist, Audio Engineer uvm. einnehmen und zusammen im Team euer Spiel entwickeln. Dabei bieten wir verschiedene Einstiegsmöglichkeiten in das Thema an.

---

## Vorbereitung auf den Hackathon

### Generell
Je nach eueren Fähigkeiten könnt ihr euch, wenn ihr Lust habt (und das sollte ihr), schon auf den Hackathon vorbereiten. Dazu haben wir für jeden interessante Kurse und Videos zusammen gestellt und erweiteren diese Liste ständig bis zu beginn des Hackathons

#### Für Einsteiger
Entwicklung von Spieleprototypen mit der Scriptsprache Lua. Dies ermöglich einen unkomplizierten Einstieg in die Programmierung von Computerspielen. Hierzu werden wir euch eine eine Reihe bekannter Games (Pong, Flappy Bird, etc) im SourceCode an die Hand geben, worauf ihr eure eigenen Prototypen entwicklen könnt und den grundlegenden Aufbau von Computerspielen erfahren könnt.
Mit diesem tollen Kurs könnte ihr euch auf diesen Bereich in den Ferien vorbereiten:
* Harvard's Introduction to Game Development [https://www.edx.org/course/cs50s-introduction-to-game-development]


#### Fortgeschrittene
Entwicklung mit der Unity3d-GameEngine (einer der führenden Entwicklungsumgebungen für kommerzielle Computerspiele). Hier laden wir euch ein mit echter Industrie-Standard-Software euer Ideen umzusetzen. Eingesetzt wird hier die Scriptsprache C#. Diese Sprache findet auch großen Einsatz, bei der Entwicklung von Unternehmmensapplikationen und nicht wenige der am Hackathon beteiligten Unternehmen setzen auf diese Sprache bei der Entwicklung ihrer Software.
Je nach Erfahrungslevel gibt es hier auch sehr interessante Möglichkeiten, sich auf den Hackathon vorzubereiten:
* Coursera Game Design Spezialisation [https://www.coursera.org/learn/game-development]
* Pluralsight Unity [https://www.pluralsight.com/paths/unity-game-development-core-skills]
* Unity Learn [https://unity3d.com/de/learn]
* Coursera Preparation for Unity Expert Gameplay Programmer Exam [https://blogs.unity3d.com/2018/05/28/now-available-worldwide-unity-certified-programmer/]

---
## Vorbereiten des Rechners für die Teilnahme am Hackathon (im Bereich GameDevelopment)

### Notwendige Useraccounts anlegen
* Vor Beginn des Hackathons einen Unity Account anlegen. [Unity3d](https://unity3d.com/de)
* Vor Beginn des Hackathons einen GitHub Account anlegen. [GitHub](https://github.com/)
* Ver Beginn des Hackathons einen Trello Account anlegen. [Trello](https://trello.com)

### Installation von Software
* Unity LTS-Version 2017.4.10f1 installieren: [[Download]](https://download.unity3d.com/download_unity/f2cce2a5991f/UnityDownloadAssistant-2017.4.10f1.exe?_ga=2.140752240.375123843.1535747211-1834572736.1528185000)
* Git installieren: [[Download]](https://git-scm.com/)
* Visual Studio Code installieren: [[Download]](https://code.visualstudio.com/)
* In Visual Studio Code folgende Plugins installieren
  * [C#] von Microsoft
  * [Debugger for Unity] von Unity Technologies
  * [Unity Tools] von Tobiah Zarlez
  
### Zum Testen von Multiplayer auf eigenem Rechner
* VM-Ware Player [[Download]](https://my.vmware.com/de/web/vmware/free#desktop_end_user_computing/vmware_workstation_player/12_0)
* Ubuntu 18.04 Server (wichtig: Docker bei Installation gleich mitinstallieren) [[Download]](https://www.ubuntu.com/download/server)
* Docker-Compose [[Installationsanleitung]](https://docs.docker.com/compose/install/)
* Nakama & CockroachDB als Docker Container starten [[Docker-Quickstart]](https://heroiclabs.com/docs/install-docker-quickstart/)
---

## Themengebiete
Als Themengebiete auf die sich die Mentoren besonders vorbereiten wurden für diesen Hackathon die Bereiche :
#### Spieleentwicklung
Einstieg in die Entwicklung von Computerspielen mit der Unity3d GameEngine.

#### Augmented Reality    
Augmented Reality, das projizieren von computererzeugten Inhalten in die reale Welt könnte sich als ein sehr interessantes Anwendungsgebiet für Spiele und andere Anwendungen. Nicht zuletzt durch Spiele wie PokemonGo etc ist dieses Thema in aller Munde. Wir laden euch ein, euch in diesem Bereich kreative zu betätigen. Vorbereitet haben wir uns dabei auf die Arbeit mit dem Vuforia-Plugin unter Unity  

#### Multiplayer
Der heilige Gral im Bereich der Spieleprogrammierung. Jahrelang war dieser Bereich den Programmierern mit 'schwarzem Gürtel' vorbehalten. Doch auch hier bringt der Trend zu OpenSource immer einfacher zu benutzende Tools hervor, wodurch die Entwicklung von Multiplayer-Spielen zwar nicht 'supereinfach' wird (hier gibt es immer noch genug zu beachten), aber doch wesentlich verständlicher. Wir bieten euch an, euch bei der Implementierung eines Multiplayer-Spiele-Prototyps zu unterstützen. Und zwar unter Verwendung des Open Source Nakama-Multiplayer Server und des entsprechenden Unity-Plugins. Hier findet ihr Resourcen um euch auf den Einstieg in Multiplayer vorzubereiten:
* Nakama Multiplayer [https://heroiclabs.com/docs/gameplay-multiplayer-realtime/]

---

## SourceCode-Repositories
### Lua-Scripting 
* [SourceCode CS50 Game Development](https://github.com/games50)

### Nakama
* [Level 200 - Multiplayer with Autologin](https://github.com/BernhardRubow/example_nakama_003_multiplayer)
* [Level 200 - Simple Multiplayer Game](https://github.com/BernhardRubow/example_nakama_002_multiplayer)
* [Level 200 - Simple Chat Server](https://github.com/BernhardRubow/example_nakama_001_simple_chat)
* [Level 200 - Authorisation](https://github.com/BernhardRubow/022_nakama_v6)

### Vuforia
* [Level 200 - Simple Object on Image Target](https://github.com/BernhardRubow/example_vuforia_001_simple_object)
* [Level 200 - Getting Started](https://github.com/Bakuenjin/VuforiaTest)
* [Level 200 - Camera Focus Controller](https://gist.github.com/BernhardRubow/279221bc57c9c298661a3af8f0baaf40)

### Unity
* [Level 300 - Brettspiel](https://github.com/BernhardRubow/020_boardgame_unity)
* [Level 300 - Regeln nach Command-Pattern](https://github.com/BernhardRubow/019_boardgame_rules_tdd)
* [Level 300 - Zong Mobile Game](https://github.com/BernhardRubow/games-013_zong)
* [Level 100 - Lunar Lander Mentoren](https://github.com/BernhardRubow/example_unity_0004_lunar_lander)
* [Level 100 - Centipede-Prototyp](https://github.com/BernhardRubow/example_unity_0003_centipede)
* [Level 100 - Animationen in Unity](https://github.com/BernhardRubow/example_unity_0001_door_with_animations)
* [Level 100 - Pathfinding with NavMesh](https://github.com/BernhardRubow/example_unity_0002_nav_mesh)
* [Level 100 - Basic techniques in Unity](https://github.com/BernhardRubow/example_unity_0005_tutorials)
* [Tool - ScriptTemplateFile](https://gist.github.com/BernhardRubow/e088a4e43fc36245bca067b1fc48a86e)

---

## Womit entwickeln wir nachher?
Wenn du unsere Vorlagen verwendest, dann benötigst du nur folgende Tools für die Entwicklung. Diese könnt ihr vorab auf eueren Geräten installieren oder wir machen das zu Beginn des Hackathons.

### 1. Git - Source Code Verwaltung 
Wir wollen hier entwickeln, also machen wir es von Anfang an richtig. Da ist eine Versionsverwaltung ein Muss und keine Option. Damit könnt ihr jederzeit Nachvollziehen, wer was geändert hat und im idealen Fall können Änderungen ohne Probleme zusammengefasst werden. Wenn es dann doch mal einen Konflikt gibt, dann wird GIT euch den entsprechenden Bereich markieren und ihr könnte bequem (abhängig vom Editor) entscheiden welche Änderung übernommen werden soll. 
* Download: [https://git-scm.com](https://git-scm.com)
* Anleitung: [tryGit - learn git in 15 minutes](https://try.github.io/levels/1/challenges/1)
* MOOC: [Wie man Git und GitHub nutzt](https://de.udacity.com/course/how-to-use-git-and-github--ud775)

### 2. Code Editor 
Ihr benötigt einen Text Editor um den Source Code schreiben zu können. Am besten einen mit Syntax Highlight, Code Vervollständigung und Validierung. Unser Vorschlag: Visual Studio Code 
* Download: [https://code.visualstudio.com]

### 3. Unity3d
* Download: [https://unity3d.com/de/unity/qa/lts-releases] Unity LTS 2017.4.6f1

### 4. Trello
Um im Team zusammenarbeiten zu können und immer überblick über das Projekt zu haben, setzen wir ein sehr einfaches aber extrem mächtiges Werkzeug ein. Trello ist ein sog. Kanban-Board mit dem man auf unkomplizierte Weise ein Projekt steuern kann. Diese Tool ist kostenlos.

### 5. Lua
Wenn ihr nicht mit Unity arbeiten möchtet, gibt es noch eine sehr viel einfacher gestrickte GameEngine mit der Ihr Spiele entwickeln könnt. Diese setzt auf die Programmiersprache Lua. Hier sind die Mentoren aber nicht ganz so drauf vorbereitet.
* Download: Löve2D 2d GameEngine [https://love2d.org/]


---

## In welchen Rollen werden wir an dem Spiel arbeiten?
Ihr werdet eine oder mehrere der folgenden Rollen bei der Entwicklung einnehmen.

### Game Designer
Der Game Designer einwickelt eine Vision des Spiels. Er beschreibt was der Spieler in dem Spiel unternehmen kann, welche Charaktere er treffen wird und welche Entscheidungen er treffen kann. Alle Optionen und sämtliche Interaktionen werden durch den Game Designer definiert.

### Game Developer
Als Game Developer setzt ihr die Ideen des Game Designer technisch um. Dafür werden diverse Kompontenten wie Physik, Grafik Engine, AI uvm. entwickelt oder integriert.

### Visual Artist
Der Visual Artist erstellt alle visuallen Element, wie 3D Modelle, Texturen, Materialien und Effekte, für das Spiel.

### Post Processing Artist
Der Post Processing Artist kümmert sich um alle Effect, die nicht direkt im Spiel implementiert werden, sondern er nachdem der aktuelle Frame berechnet worden ist (Post Processing) auf das fertige FrameBild berechnet werden, wie z.B. Color Grading, Motion Blur und viele andere Effekte.

### Audio Engineer
Der Audio Engineer ist vergleichbar mit dem Visual Artist, nur das dieser statt Grafiken Geräusche erstellt. Dazu gehören neben Effekten auch die Hintergrund Musik, der Sound Track und vertonte Dialoge.

### Animator
Der Animator erweckt die 3D Modelle des Visual Artist zum Leben.

### Level Designer
Der Level Designer kombiniert die visuellen und akustischen Komponenten und erstellt damit ein Level für das Spiel. 

### Producer
Der Producer steuert und überwacht den Erstellungsprozess des Spiels (auch Finanziell).

### QA Tester
Die QA bestätigt die Qualität des Spiels und zeigt Mängel (Bugs) auf.

---

## Welche GameEngines könnte ich noch verwenden?
Es gibt [diverse Game Engines](https://github.com/showcases/javascript-game-engines) mit der ihr euer Game erstellen könnt. Um euch die Auswahl zu erleichtern haben wir verschiedene Engines ausgewählt und entsprechende Vorlagen vorbereitet.

### PlayCanvas
PlayCanvas ist eine komplett auf JavaScript basiserende GameEngine die durchgehend webbasierend ist, d.h. sogar der Editor wird gleich im Web mit angeboten. Man braucht nichts zu installieren und kann gleiche loslegen (wenn man weiß, wie es geht).

#### Links
[https://playcanvas.com/](https://playcanvas.com/)

### Phaser
Phaser ist eine Open Source 2D Game Engine um HTML 5 Spiele für den Browser als auch dem Desktop zu entwickeln.

##### Links
- [http://phaser.io](http://phaser.io)

### Babylon.js
Babylon.js ist eine Open Source 3D Game Engine. Die Engine wurde komplett in Typescript geschrieben.

##### Links
- [https://www.babylonjs.com](https://www.babylonjs.com)

### Three.js
Wer eine 3D-Anwendung wie ein Spiel ins Internet bringen will, kommt an WebGL kaum vorbei. Doch die Programmierung darin ist umständlich und fehleranfällig. Mit der JavaScript-Bibliothek Three.js gehts viel leichter.
WebGL bietet dem JavaScript-Entwickler eine Unmenge an Möglichkeiten – von der Darstellung einfacher 3D-Modelle bis hin zur direkten Programmierung des Grafikprozessors. 

##### Links
- [https://threejs.org](https://threejs.org)

---

## Vorlagen auf GitHub

Vorlagen auf GitHub:
- JavaScript [https://github.com/PIT-Hackathon/2017-WebGame-Phaser-ES2017](https://github.com/PIT-Hackathon/2017-WebGame-Phaser-ES2017)

Vorlagen auf GitHub:
- JavaScript [https://github.com/PIT-Hackathon/2017-WebGame-Babylon-ES2017](https://github.com/PIT-Hackathon/2017-WebGame-Babylon-ES2017)
- TypeScript [https://github.com/PIT-Hackathon/2017-WebGame-Babylon-TypeScript](https://github.com/PIT-Hackathon/2017-WebGame-Babylon-TypeScript)

Vorlagen auf GitHub:
- JavaScript [https://github.com/PIT-Hackathon/2017-WebGame-Three-ES2017](https://github.com/PIT-Hackathon/2017-WebGame-Three-ES2017)



## Tutorials & Anleitungen

- Phaser
    - [http://phaser.io/](http://phaser.io/)
    - [Examples](http://phaser.io/examples)
- Babylon.js
    - [https://www.babylonjs.com/](https://www.babylonjs.com/)
    - [Tutorials](http://doc.babylonjs.com/tutorials)
- Three.js
    - [https://threejs.org/](https://threejs.org/)
    - [Examples](https://threejs.org/examples/)
- Javascript [ECMAScript 2017] 
    - [Grundlagen_der_Programmierung](https://wiki.selfhtml.org/wiki/JavaScript/Tutorials/Grundlagen_der_Programmierung)
    - [ECMAScript 6 (2015) Tutorial](http://ccoenraets.github.io/es6-tutorial/)
    - [ES2017 async/await to the rescue](https://medium.com/@tmvvr/ecmascript-async-await-to-the-rescue-fc379ff89146)
- Typescript [https://www.typescriptlang.org/](https://www.typescriptlang.org/)
    - [Typescript in 5 minutes](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html)
    - [Playground](https://www.typescriptlang.org/play/index.html)
- HTML5
    - [Tutorial](https://wiki.selfhtml.org/wiki/HTML/Tutorials/HTML5-Grundger%C3%BCst)
- Massiv Open Online Courses (MOOC) zu Gamedesign und Gamedevelopment
    - [edX : 5 teiliger Kurs zu Gamedesign & -development](https://www.edx.org/xseries/video-game-design)
    - [studyToLearn: Kurs zu Konzepten im Gamedesign](https://www.open2study.com/courses/concepts-in-game-development)
    - [coursera: Game Design and Development Specialization](https://www.coursera.org/specializations/game-development)
    - [coursera: Game Design Art and Concepts Specialization](https://www.coursera.org/specializations/game-design)
    - [und natürlich: ExtraCredits](https://www.youtube.com/user/ExtraCreditz)
    - [Unity Certified Programmer Exam Preparation](https://www.coursera.org/specializations/unity-certified-programmer)
- Tools
    - [Jesse Schell: A book of lense (Android App)](https://play.google.com/store/apps/details?id=com.schellgames.deckoflenses&hl=de)
    - [MDA Framework: A Formal Approach to Game Design and Game Research](http://www.cs.northwestern.edu/~hunicke/MDA.pdf)
    - [High Concept Document Template](https://www.dropbox.com/s/cit5rsx8f5d5o6b/HighConceptTemplate.pdf?dl=0)
    - [One Page Game Design Document Template](https://www.dropbox.com/s/xfmzl2d64teinre/OnePageGameDesignDocument.pdf?dl=0)
    - [Game Story Bible Template](https://www.dropbox.com/s/hapw4l0bev115r5/GameStoryBibleTemplate.pdf?dl=0)
- Software
    - [Autodesk 3ds Max (Educational)](http://www.autodesk.com/education/free-software/3ds-max)
    - [Autodesk Maya (Educational)](https://www.autodesk.com/education/free-software/maya)
- Texturen
    - [CG Textures](http://www.cgtextures.com/)
    - [Texture King](http://www.textureking.com)
    - [Stock Textures](http://stocktextures.com/)
- Farbgestaltung
    - [Adobe Color](https://color.adobe.com/de/create/color-wheel/)
    - [Color Lovers](http://www.colourlovers.com/)
- Audio Assets
    - [Übersicht über Seiten mit freier Musik für Spiele](https://v-play.net/game-resources/free-music-for-games)
    - [Übersicht über Seiten mit freien SoundFX für Spiele](https://v-play.net/game-resources/16-sites-featuring-free-game-sounds#_noiseforfun.com/)
    - [ZapSplat Free Effects and Music](https://www.zapsplat.com)
    - [Flashkit](http://www.flashkit.com/soundfx/)
    - [Indie Game Music](http://indiegamemusic.com/)
    - [Jamendo](http://www.jamendo.com/)
    - [Free Sound Effects](http://www.freesoundeffects.com/)
    - [Free Sound Project](https://freesound.org/)
- Models
    - [TurboSquid](http://www.turbosquid.com/Search/?KEYWORD=Free)
    - [Archive 3d](http://www.archive3d.net)
    - [3d Xtras](http://www.3dxtras.com/index.asp)
    - [Artist-3d](http://www.artist-3d.com/)
    - [Exchange 3d](http://www.exchange3d.com/FreeModels/cat_35.html)
    
    


