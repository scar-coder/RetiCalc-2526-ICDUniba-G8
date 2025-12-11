# Assegnazione 2: Socket UDP e DNS in C 
Progettare ed implementare un’applicazione UDP client/server conforme al seguente protocollo: 
1. Il client legge da tastiera il nome dell’host e il numero di porta del server da contattare. 
2. Il client, invia il messaggio iniziale “Hello” al server. 
3. Ricevuti i dati client, il server visualizza sullo std output un messaggio contenente il nome 
e l’indirizzo IP dell’host del client (Esempio: “ricevuti dati dal client nome: xxxxx   
indirizzo:yyyyyy”). 
4. Il client legge una stringa di caratteri dallo standard input e la invia al server. 
5. Il server legge la stringa inviata dal client e la visualizza sullo standard output; dopodiché, 
elimina tutte le vocali e la invia nuovamente al client. 
6. Il server resta in attesa di altri dati. 
7. Il client legge la risposta inviata dal server e visualizza la risposta sullo standard output 
(“Stringa zzzzzz ricevuta dal server nome:xxxxxx inidirizzo:yyyyy”); dopodiché termina il 
processo.

NOTE: 
Ø La consegna deve avvenire secondo le modalità descritte nella guida che troverete su ADA. 
Non chiedete che sia inviata una conferma di ricezione 
Ø La consegna deve includere il sorgente dei 2 progetti Eclipse (uno per il client e uno per il 
server) come cartelle. Utilizzare la seguente nomenclatura per i due progetti: client
UDP_nomegruppo e server-UDP_nomegruppo