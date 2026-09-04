# Expedition Hellmann — Missionsseiten

Zwei eigenstaendige Seiten, je passwortgeschuetzt (clientseitig, Passwort nur als Hash im Code).

    /snowland/index.html      Mission Snowland  — Passwort: Aurora Borealis
    /rising-sun/index.html    Mission Rising Sun — Passwort: Fujiyama

Keine Build-Schritte, keine Abhaengigkeiten ausser Google Fonts.

## Auf GitHub Pages veroeffentlichen

    git init
    git add .
    git commit -m "Expedition Hellmann"
    git branch -M main
    git remote add origin git@github.com:<USER>/<REPO>.git
    git push -u origin main

Dann im Repo unter Settings > Pages als Quelle "Deploy from a branch",
Branch `main`, Ordner `/ (root)` waehlen. Nach ein bis zwei Minuten sind die
Seiten erreichbar unter:

    https://<USER>.github.io/<REPO>/snowland/
    https://<USER>.github.io/<REPO>/rising-sun/

Hinweis: Ein GitHub-Pages-Repo ist oeffentlich einsehbar. Fuer die Passwoerter
ist das unkritisch, sie stehen nicht im Klartext im Quelltext.
