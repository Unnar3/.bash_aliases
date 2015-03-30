# .bash_aliases
Folder that stores aliases Ubuntu

copy following code to .bashrc

if [ -d ~/.bash_aliases ]; then
    for f in ~/.bash_aliases/*.aliases; do . $f; done
fi
