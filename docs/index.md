# CHE FACCIAMO QUESTA SETTIMANA?
## 14-21/10/2024
### Il Terminale
Inizia a fare pratica con la riga di comando ``CLI`` sia della ``PowerShell`` di Windows sia del ``Terminale`` di macOS.

### IDE
Installiamo i programmi che ci servono, ovvero un Notepad (un po' più evoluto) e git ...
    - Possiamo usare come Notepad quello che vogliamo, ``Notepad++`` - ``Atom`` - ``Visual Studio Code`` - ``Blocco Note di Windows``
    vi consiglierei di installare **Visual Studio Code** su Windows in modo da poter testare anche il vs. codice senza troppe installazioni;
    trovate **Visual Studio Code** ---> [QUI](https://code.visualstudio.com/)
    - per quanto riguarda **git** possiamo installarlo da [QUI](https://git-scm.com/downloads) sia per Windows che per altri sistemi operativi.
    La strada più semplice per installarlo su Mac è aprire il terminale e scrivere il seguente codice:
    ```bash
    sudo apt-get install git
    ```
### VCS, gitHub e Repository
Crea un Account gratuito su **gitHub**

1. sul sito [github.com](https://github.com) ti registri
2. in locale (che significa sul tuo computer) apri la CLI e crea una cartella di progetto dove vuoi!
3. inizializza la cartella in modo che sia sicronizzata con la cartella di progetto sul tuo account git.
4. seguendo questi semplici comandi crei da zero il tuo nuovo progetto / repository:
    ```
    echo "test" >> README.md
    git init 
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/IL-TUO-NOME-UTENTE/IL-NOME-DEL-TUO-PROGETTO.git
    git push -u origin main
    ```
## *** **29/10/2024**
### Clonare un progetto git

!!! note "Alternativa al punto 4."
    In alternativa all'inizializzazione vista al punto 4. è possibile **clonare** un repo che esiste online:

    - Una volta creato il tuo account crea un nuovo Repository direttamente dalla tua pagina github;
    - ricorda in fase di creazione di creare un file README.md;
    - dal PC, apri il Terminale e crea una cartella Progetti Git, dove vuoi;
    - entra nella cartella che hai creato;
    - clona il repo che hai appena creato online:
    ```git
    git clone https://github.com/IL-TUO-NOME-UTENTE/IL-NOME-DEL-TUO-PROGETTO-PRESENTE-SU-GITHUB.git
    ```

## *** **per 30/10/2024**
- Creare una pagina bio.
!!! tip "Importante!!!"
    Aggiungere una FOTO chiara in bio.

    Con i **MarkDown** le foto si aggiungono così:
    ```
    ![qui va un testo alternativo ma può essere lasciato anche vuoto](qui va il percorso del file immagine)

    esempio:
    
    ![](img/w4/006.png)
    ```




# TUTORIAL, GUIDE e REFERENCE
## Shell Commands
- I 40 Comandi Linux Più Utilizzati Che Devi Assolutamente Conoscere ---> [Link](https://kinsta.com/it/blog/comandi-linux/)

## .MD - MarkDown
- [Guida MarkDown](https://www.markdownguide.org/basic-syntax/)

## Mkdocs
- How to create a BEAUTIFUL documentation-blog website for FREE! | MkDocs Material [Video](https://www.youtube.com/watch?v=DeZjkCtttss).


