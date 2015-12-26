# GtkSourceView-Arduino
Syntax highligthing and auto-completion for Arduino in gedit or gnome-builder.
## English:
The file is coming soon.
### Install:

## Français :

Le fichier arrive bientôt, le temps de configurer GIT.

Le fichier permet d'avoir la reconnaissance automatique des fichiers Arduino *.ino* et *.pde* dans *Gedit* et *Gnome-builder* grâce à *GtkSourceView*. J'ai ajouté les mots clés issus du document de référence : https://www.arduino.cc/en/Reference/HomePage pour améliorer la coloration  syntaxique, et l'auto-complétion.
Mais je n'ai pas ajouté les mots clés des différentes librairies pour éviter de trop emcombrer l'auto-complétion... à voir à l'usage.

Le fichier fait référence au fichier .lang de *C* et *C++* mais il existe de petites différences de la syntaxe expliquées ici : https://www.arduino.cc/en/Reference/Comparison

### Installation :
Se placer dans le dossier gtksourceview de l'utilisateur courant:
```bash
cd ~/somewhere
```
Si on veut en faire profitertous les utilisateurs :
```bash
cd /usr/share/gtksourceview-3.0/language-specs/
```
Pour gtk2 ce sera plutôt : `/usr/share/gtksourceview-2.0/language-specs/`

Y télécharger le fichier *arduino.lang*
```bash
wget arduino.lang
```
Puis on redémarre Gedit ou Gnome-Builder pour que soit pris en compte.



