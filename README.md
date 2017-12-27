Diese Homepage baut auf [https://github.com/Phlow/feeling-responsive](https://github.com/Phlow/feeling-responsive) auf.

## Die Homepage lokal anschauen
Während du die Homepage umbaust, möchtest du anschauen, wie sie letzlich aussieht. Dazu dienen folgende Schritte:
- Öffne ein Terminal mit der Tastenkombination `Strg` + `Alt` + `T`.
- Gehe in den CantaPeregrinaHomepage Ordner, indem du den Befehl `cd CantaPeregrinaHomepage` in das Terminal tippst und dann Enter drückst. `cd` bedeutet "change directory".
- Führe das Skript, das aus den für Menschen lesbaren Dateien auf dem Browser (z.B. Firefox) anschaubare Dateien macht, aus, indem du den Befehl `bundle exec jekyll serve` in das Terminal tippst. Das Skript läuft nun im Hintergrund.
- Das Skript gibt dir eine lokale Adresse an, unter der du im Browser die Homepage betrachten kannst. Das ist im Normalfall `http://127.0.0.1:4000/`. Unter dieser Adresse kannst du im Browser die aktuelle Version der Homepage mit deinen lokalen neuen Änderungen betrachten. Achtung: Wenn du auf einen Link in der Homepage klickst, z.B. in der Navigationsleiste, wirst du auf die Seite, die tatsächlich online ist (d.h. die alte Version) geleitet. Du musst daher, nachdem du den Link geklickt hast, einen Teil der Adresse, nämlich `http://www.canta-peregrina.de/` durch `http://127.0.0.1:4000/` ersetzen, dann siehst du deine lokale Änderung.
- Wenn du eine Datei veränderst und speicherst, führt sich das Skript automatisch erneut aus und zeigt deine Änderung im Browser an, wenn du die Seite neu lädst. Betrifft deine Änderung allerdings Konfiguration oder Navigation, funktioniert das unter Umständen nicht. Dann beendest du das Skript mit der Tastenkombination `Strg` + `C` und startest es mit `bundle exec jekyll serve` neu.
