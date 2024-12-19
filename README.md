# PokeScan :flower_playing_cards:

PokeScan ist eine Applikation, die es Benutzern ermöglicht, eine Pokémon-Karte zu scannen und deren gegenwärtigen Marktpreiswert zu ermitteln.
Diese Ergebnisse können immer wieder eingesehen und genutzt werden, um Karten, die man nicht mehr persönlich benutzen will, in einen angemessenen Gewinn zu verwandeln!


## Features :heavy_dollar_sign:

- **Karten-Scanner:** Halten sie einfach und bequem ihre Karte in ihre integrierte Webcam und drücken Sie ansonsten nur einen Knopf, und der Rest wird erledigt.
- **Echtzeitgetreuer Marktwert:** Es wird nach Scannen der Karte der aktuelle Marktpreis ermittelt und für Sie auf dem Bildschirm ausgegeben.
- **Auf Datenbank sichern:** Die gescannte Karte wird auf einer Datenbank gesichert und kann jederzeit wieder aufgerufen werden, was mehrmaliges Scannen vermeidet.


## Installation :computer:

1. **Repository klonen:** 
   ```bash
   git clone https://github.com/celtechstarter/poke-app.git

2. **In das Projektverzeichnis wechseln:**
	```bash
	cd ./poke-app

3. **Abhängigkeiten installieren:**
	```bash
    cd ./frontend
    npm install // warten bis installiert wurde
    cd ..
    cd ./backend
    npm install


Backend starten:
cd backend
node server.js

Frontend starten:
cd frontend
npm run dev

**4. Ausführung**
    
    ```bash
    node server.js //falls Sie noch nach der Installation im Backend-Ordner sind, ansonsten navigieren sie dahin zurück
    cd ..
    cd ./frontend
    npm start


## Nutzung :rocket:

- **Login** - Loggen sie sich simpel mit Ihrem Google-Account per Knopfdruck ein (Ein Google-Account wird vorausgesetzt).
- **Scannen** - Mit einem Knopfdruck wird Ihre Webcam geöffnet, danach halten Sie ihre Pokémon-Karte in die Webcam und drücken Speichern.
- **Speichern** - Die Karte wird in einer Datenbank abgelegt, so dass sie wieder aufgerufen werden kann, sollten Sie noch einmal die Informationen über diese Karte benötigen.
- **OCR** - Scannen Sie die Karte und lassen Sie sich für die Karte den aktuellen Preiswert ermitteln aus vertrauenswürdigen Quellen.

## Technologie-Stack :camera:

          {/* Technologie-Badges */}
          <Flex gap="2" mt="3" wrap="wrap">
            <Badge color="green">React.js</Badge>
            <Badge color="blue">Node.js</Badge>
            <Badge color="purple">MongoDB</Badge>
            <Badge color="orange">Tesseract.js</Badge>
            <Badge color="yellow">AWS S3</Badge>
            <Badge color="teal">AWS EC2</Badge>
            <Badge color="gray">Express.js</Badge>
            <Badge color="red">ScraperAPI</Badge>
            <Badge color="violet">Axios</Badge>
            <Badge color="pink">Docker</Badge>
            <Badge color="cyan">Radix UI</Badge>
            <Badge color="indigo">Git & GitHub</Badge>
          </Flex>

## Beitrag :dancers:

Beiträge sind willkommen! Bitte folgen Sie diesen Schritten:

1. **Forken** Sie das Repository.
2. Erstellen Sie einen neuen Branch:
   ```bash
   git checkout -b feature/neues-feature

Nehmen Sie Ihre Änderungen vor und committen Sie sie:

	```bash
    git commit -m 'Füge neues Feature hinzu'

Pushen Sie den Branch:

	```bash
    git push origin feature/neues-feature



**7. Lizenz** :registered:


## Lizenz

Dieses Projekt steht unter der [MIT-Lizenz](LICENSE).
![License](https://img.shields.io/badge/license-MIT-blue)

## Kontakt

Bei Fragen oder Feedback wenden Sie sich bitte an: :email:

[marcel.welk87@gmail.com](mailto:marcel.welk87@gmail.com) 

[sawatzkychristian@gmail.com](mailto:sawatzkychristian@gmail.com)

[willellwart@gmail.com](mailto:willellwart@gmail.com).

:wave:
