# Aufgabe Makroarchitektur Teil 2

## A: Inbetriebnahme der Microservice-Variante von erplite

- Schritt 1: Verzeichnis erstellen, darin im Termimal "git init" und anschließend "git pull https://gitlab.com/itkolleg-imst/fse/erplite-microservices.git" ausführen.
- Schritt 2: In das Verzeichnis "dockerfiles\erpliteinfrastructurecomplex" wechseln und dort den Befehl 'docker compose up' ausführen.
- Schritt 3: Warten bis alle Dockerimages gepullt und installiert wurden. Die daraus resultierenden Dockercontainer werden automatisch gestartet.<br>Das sieht dann ungefähr so aus:<br><img src="screenshots\dockercomposecmd.PNG"/>
- Schritt 4: Nachdem alle Dockercontainer installiert und ausgeführt wurden, kann man anschließend die fünf Microservices (auffindbar über den Services-Tab oder auch mit dem Shortcut ALT+8) ausführen.<br>Sollte ungefähr so aussehen (funktioniert bei mir aus gründen noch nicht, die fehlermeldungen sind nicht hilfreich und ich habe gerade wirklich keine lust auf diese fehlersuche)<br><img src="screenshots/services_wont_start.png">
