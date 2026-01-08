Fondamenti di Network pt.3

In questo esercizio ho lavorato su una rete locale (LAN) per capire come un client riesce a collegarsi a un server web usando un nome di dominio interno invece dell’indirizzo IP.
Il DHCP serve per assegnare automaticamente al client l’indirizzo IP e le altre informazioni di rete, così non è necessario configurarle a mano.
Il DNS interno viene usato per tradurre il nome del dominio nell’indirizzo IP del server.
Il server HTTP, che ha un IP statico, risponde alle richieste del client mostrando la pagina web.
Quando dal browser viene inserito il nome del dominio, prima avviene la risoluzione DNS e poi la richiesta HTTP al server.
Se si prova ad accedere a un sito esterno, come ad esempio Google, la connessione non funziona perché la rete non è collegata a Internet.
Questo esercizio mi ha aiutato a capire meglio come DHCP, DNS e HTTP lavorano insieme all’interno di una rete locale.
