# GtkSourceView-Arduino
Syntax highlighting and auto-completion for Arduino in gedit or gnome-builder.
## English:
The file [arduino.lang](#arduino.lang) allow Gedit or Gnome-Builder to automaticaly recognize the Arduino's files *.ino* and *.pde*. I added few keywords from the reference documentation: https://www.arduino.cc/en/Reference/HomePage in order to improve syntax highlighting and auto-completion. I didn't add the specific librairies for now, I don't know if it's very usefull.

### Install:
Duplicate the repository in local to get the *arduino.lang* file:
```bash
git clone https://github.com/kaochen/GtkSourceView-Arduino/
cd GtkSourceView-Arduino/
```
copy the file to the gtksourceview directory of the current user:
```bash
cp arduino.lang ~/.local/share/gtksourceview-3.0/language-specs/arduino.lang
```
If you want make the file visible for all users:
```bash
cp arduino.lang  /usr/share/gtksourceview-3.0/language-specs/arduino.lang
```
With gtk2 it's more like that : `/usr/share/gtksourceview-2.0/language-specs/arduino.lang`

Then restart Gedit or Gnome-builder to see the change.

## Français :

Le fichier [arduino.lang](#arduino.lang) permet d'avoir la reconnaissance automatique des fichiers Arduino *.ino* et *.pde* dans *Gedit* et *Gnome-builder* grâce à *GtkSourceView*. J'ai ajouté les mots clés issus du document de référence : https://www.arduino.cc/en/Reference/HomePage pour améliorer la coloration  syntaxique, et l'auto-complétion.
Mais je n'ai pas ajouté les mots clés des différentes librairies pour éviter de trop emcombrer l'auto-complétion... à voir à l'usage.

Le fichier fait référence au fichier .lang de *C* et *C++* mais il existe de petites différences de la syntaxe expliquées ici : https://www.arduino.cc/en/Reference/Comparison

### Installation :
Dupliquer le répertoire en local pour récupérer le fichier *arduino.lang* :
```bash
git clone https://github.com/kaochen/GtkSourceView-Arduino/
cd GtkSourceView-Arduino/
```
Placer le fichier dans le dossier dans le dossier gtksourceview de l'utilisateur courant :
```bash
cp arduino.lang ~/.local/share/gtksourceview-3.0/language-specs/arduino.lang
```
Si on veut en faire profiter tous les utilisateurs :
```bash
cp arduino.lang /usr/share/gtksourceview-3.0/language-specs/arduino.lang
```
Pour gtk2 ce sera plutôt : `/usr/share/gtksourceview-2.0/language-specs/arduino.lang`

Puis on redémarre Gedit ou Gnome-Builder pour que soit pris en compte.



