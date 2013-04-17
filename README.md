# GitBashPrompt

Prompt pour afficher les noms des branches sur les dépôts GIT.
Plus d'infos sur <http://blog.rom1v.com/2012/04/prompt-bash-pour-git/>.

## Usage

Clonez ce dépôt quelque part :

    git clone URL

Puis éditez le fichier `~/.bashrc` pour remplacer:

    PS1='${debian_chroot:+($debian_chroot)}\u@\h:\w\$ '

par *(adaptez le chemin)*:

    . /full/path/to/your/gitbashprompt

Puis ouvrez un nouveau terminal.
