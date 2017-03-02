# GMZ2.1

## Gas Mess Zentrale für bis zu 2 analoge Sensoren in 4-20mA Technologie

Dieser, scheinbar leere, Branch enthält nur die Dateien die im Vergleich zum Master Branch des Repos anders sind.

Um aus diesen Daten eine lauffähige Version zu generieren sollten folgende Schritte ausgeführt werden.

```bash
# sicherstellen das vom master Branch aus opperiert wird
git checkout master

# eine neuen, temporären, branch aus dem master erstellen
git checkout -b merge master

# die Defines aus dem Branch importieren der als Vorlage dienen soll
git checkout Defines.h C5H12-0-100UEG-linear

# nachdem das Hex File gebuildet und dokumentiert wurde kann der temp. branch
# wieder gelöscht werden
git branch -d merge
```

Nun kann kompelliert werden.

Zum Abschluss wird das Hex File in die Versionskontrolle aufgenommen.

```
```
