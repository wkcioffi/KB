# Indice

- [Repository](#repository)
- [Markdown](#markdown)
- [Struttura](#struttura)
- [Installazione su client](#installazione-su-client)



## Repository

Creare un repository per ogni progetto.

[Github](https://github.com) > *account:* **wkcioffi** > *Repositories* > **New**

Ogni repository potrà corrispondere ad una cartella locale sul client dove è installato vscode

Esempi:

- wkcioffi/**KB**
- wkcioffi/**Proxmox-Single-node-with-OMV-and-PBS**

In ogni repository, creare un file **README.md** che servirà come pagina principale.


## Markdown

[Markdown cheat sheet](https://www.markdownguide.org/basic-syntax/)


## Struttura
Nel caso un progetto comprenda più sottomoduli, creare una sotto cartella separata per ogni modulo e inserire un file *.md* come  pagine descrittiva del modulo.

Esempio con repository **KB** e sotto-moduli **Git** e **VScode**

    > KB
        > vscode
            vscode.md
        > git
            git.md
        README.md

Nei file README.md si possono creare link alla pagine dei sotto-moduli utilizzando la seguente sintassi:

    [Etichetta](sotto-cartella/file.md)

Esempio: 

    [VScode](vscode/vscode.md)
    [Git](git/git.md)

## Installazione su client

Inatallare **Git**

- Client ubuntu:

    sudo apt update && \
    sudo apt install git -y

- Client Windows: Scaricare e installare da **MS store**

Configurare l'identità che verrà utilizzata da **git** sul computer locale:

    git config --global user.email "you@example.com"
    git config --global user.name "your name"

