# AndroidStudio Live Templates

Live Templates da utilizzare in Android Studio per lo sviluppo Android: sono utili per migliorare il tuo lavoro in termini di velocità ma anche di qualità del codice. (Vedi [Android Style Guide](https://github.com/tiknil/android-style-guide) by Tiknil)

### Come aggiungerli ad Android Studio ###

Per aggiungere questi Live Templates devi copiare il file `Tiknil.xml` nella cartella dei live templates della tua versione di Android Studio.

Su mac la cartella è al percorso `~/Library/Preferences/<product name><version number>/templates`, se usi un altro sistema operativo [controlla qual'è il path corretto](https://www.jetbrains.com/idea/help/live-templates.html).
Fai attenzione a usare la cartella della versione corretta. Quando si aggiorna Android Studio ricordati di confermare l'importazione delle impostazioni dalle versioni precedenti.

### Live templates ###

#### `def` ####

Questo live template è molto comodo per organizzare il codice di implementazione delle classi Java in modo coerente. Basta cominciare a digitare `def` e il live template proporrà le `//region` per raggruppare il codice in maniera ordinata

![def_androidstudio_live_templates](http://cl.ly/image/1G2M2y1f3y0S/animation.gif)


#### `tag` ####

Questo live template serve a definire la costante di classe `TAG` da poter utilizzare nei metodi `Log.`. Comincia a scrivere `tag` e ti verrà proposto solo di inserire il nome della classe attuale.

#### `mark` ####

Questo live template è molto comodo per organizzare il codice di implementazione delle classi Kotlin in modo coerente. Basta cominciare a digitare `mark` e il live template proporrà le `//region` per raggruppare il codice in maniera ordinata
