# DHCP-DNS-
Sintesi: Appena si effettua il ping al server http la prima tipologia di messaggio è l'arp per trovare il mac address del server dns,dopo che mi ritorna il mac del server dns successivamente viene mandato un pacchetto dns che contiene il nome del dominio
("SIRulez.it") che andrà mandato una seconda volta al server dns, la risposta da parte del server dns è l'indirizzo ip del server http, poi verrà mandato un pacchetto ICMP che contiene l'indirizzo ip del server http che ha ricevuto e il server http risponderà con un pong ovvero che la comunicazione è andata a buon fine.(0% packet loss).
Nel Domain Name System (DNS) le persone accedono alle informazioni online tramite dei nomi di dominio, ogni dispositivo collegato a Internet è dotato di un indirizzo IP univoco, che altre macchine usano per trovarlo. I server DNS eliminano la necessità per gli esseri umani di memorizzare gli indirizzi IP.
Si assegna un indirizzo IP a ciascun dispositivo su Internet, questo indirizzo è necessario per trovare il dispositivo Internet appropriato. Quando un utente desidera caricare una pagina web, deve avvenire una traduzione tra ciò che un utente digita nel proprio browser web (SIRulez.it) e l'indirizzo riconoscibile dalla macchina necessario per individuare la pagina SIRulez.it.


