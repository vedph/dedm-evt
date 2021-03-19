dedm

DEDM - edizione scientifica digitale del Milione
Introduzione

Questo repository contiene tutto il materiale di codifica dell'edizione del Milione di Marco Polo.

Link ai files excel dei realia: https://drive.google.com/drive/folders/1jOpjWO-88kGhZpqb99bru-T5aTNRd1i-?usp=sharing

Per i collaboratori e le collaboratrici:

    non committare sul branch principale (main)
    inviare pull-request per ogni cambiamento
    tenere il proprio repository locale aggiornato.

Come collaborare

Per poter lavorare su questo repository, il vostro account Github deve essere registrato come collaboratore del progetto.

Suggeriamo di creare un branch locale per ogni cambiamento da apportare. Al termine del lavoro, committate localmente e fate un push su un branch remoto. Infine, su https://github.com/vedph/dedm create una "pull-request" selezionando il branch di lavoro.

Più nel dettaglio, suggeriamo di seguire la documentazione proposta da Github su:

    come collaborare ad un progetto: https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/collaborating-on-repositories-with-code-quality-features
    Apportare modifiche: https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/proposing-changes-to-your-work-with-pull-requests
    Gesione dei conflitti: https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/addressing-merge-conflicts
    Revisionare pull-request: https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/reviewing-changes-in-pull-requests
    Incorporare cambiamenti: https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/incorporating-changes-from-a-pull-request

Lista di comandi utili
Creare un branch

Nell'esempio, il branch lavoroX viene creato:

$ git checkout -b lavoroX

Inviare i cambiamenti per una revisione

Al termine del vostro lavoro, quando siete pronti per inviare i vostri cambiamenti, procedete con uno (o più) commit:

$ git commit -a -m "Scrivete qui una descrizione breve del vostro lavoro"

Infine, portate il vostro branch sul repository remoto (github):

$ git push origin lavoroX:lavoroX

Sul sito di github.com/vedph/dedm, creare una pull-request selezionando lavoroX tra i possibili branch. La vostra pull-request verrà analizzata, commentata e possibilmente accettata in tempi ragionevoli.
Scaricare il plugin su oXygen

    Aprire oXygen e seguire il percorso Help > Install new add-ons;
    Inserire nel campo Show add-ons il link https://www.oxygenxml.com/InstData/Addons/default/updateSite.xml;
    Selezionare Git Client dalla lista e cliccare su Next;
    Selezionare I accept all terms of the end user license agreement e terminare l'installazione;
    Riavviare oXygen

Clonare la repository direttamente dal plugin su oXygen

    Per visualizzare le opzioni del plugin, selezionare il percorso Tools > Git Client
    Cliccare su Git Staging che sarà apparso sulla sinistra della schermata di oXygen
    Cliccare sul segno "+" (Clone new repository) e inserire l'URL https://github.com/vedph/dedm.git
    Seleionare il checkout branch e il percorso per il download e selezionare OK

Fare un commit del proprio lavoro

Per aggiornare la repository locale e il branch della propria redazione:

    Cliccare su Git Staging. In alto a destra, selezionare il branch della propria redazione, NON il main o i branch di altre redazioni
    Aprire il percorso del file sul quale si sta lavorando alla voce Working copy e selezionare il file stesso
    Cliccare su Stage Selected
    Nell'ultimo riquadro in basso inserire un breve commento sulle modifiche apportate e cliccare su Commit. Notare le tre piccole icone sopra a questo riquadro: nessuna di esse deve essere selezionata

Per aggiornare il branch della propria redazione nella repository su GitHub:

    Cliccare su Git Staging e poi sulla quarta icona Show Git Branch Manager
    Aprire il Git Branch Manager che sarà apparso a sinistra e selezionare sia nella repository locale che in quella remota il branch della redazione sulla quale si sta lavorando
    Ripetere i quattro punti della sezione precedente però prima di cliccare su Commit selezionare la seconda icona del riquadro di commento Automatically push changes to remote branch

Tenere la repository locale aggiornata

Prima di apportare qualsiasi modifica ai file della repository locale è fondamentale aggiornarla per evitare che si creino conflitti e per avere tutti i file nella loro versione più recente. Per fare ciò, bisogna fare un'operazione di "pull". Sempre da Git Staging, cliccare sulla terza icona, la freccetta che va in basso (Pull (merge)).