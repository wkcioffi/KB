# Indice

- [Installazione](#installazione)
- [Contesti](#contesti)
- [Collegamento a Github](#collegamento-a-github)

## Installazione

Installare **VScode**:

    sudo apt update && \
    sudo apt install code -y

## Collegamento a Github

- Se non è già stato fatto, procedere con l'installazione di **git** tramite la [procedura dedicata](/git/git.md) e configurare l'identità corretta.

- Creare una cartella operativa (es: ```/home/user/vscode```) in cui clonare le cartelle dei singoli repository.

- Avviare **VScode** > Accounts (in basso a sx) > Collegare account Github.

Selezionare la cartella dove salvare tutti i repository clonati da Github. Volendo, nella stessa cartella, si possono creare manualmente nuove sottocartelle di nuovi progetti che si potranno *lanciare* come nuovi repository su Github.

## Contesti

Il contesto di default di VScode è quello del client locale.

Installando l'estensione **Remote - SSH** e possibile collegarsi tramite VScode a host remoti (es. un server docker) ed utilizzare VScode come se l'istanza fosse stata direttamente su quell'host.

I contesti (locale o remoti) sono separati e si possono installare set di **estensioni** distinti ed indipendenti.

**Esempio:** posso avviare l'istanza locale di VScode (default) ed installare l'estensione **Python** e successivamente avviare, in una nuova finestra, una seconda istanza remota di VScode senza trovarvi l'estensione installata installata precedentemente sull'istanza locale. In breve, ogni contesto è come se fosse un'installazione a sè di VScode.

## Estensioni

Le estensioni si possono installare sul contesto locale (istanza di VScode avviata localmente) oppure su un contesto remoto (istanza di VScode avviata su una macchina remota).

### Remote SSH

Questa estensione permette di collegarsi ad host remoti, avviando istanze di VScode dedicate e gestirne i file con **Explorer** come se fossero in locale.

Extensions > "*Remote - SSH (Microsoft)*" Install

### Docker

Per la gestione dei **container** e dei **compose**, sono disponibili queste estensioni:

- *Docker (Microsoft)*
- *Docker DX (Docker)*

### Python

- *Python (Microsoft)*