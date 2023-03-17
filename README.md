# DHCP-DNS-
Sintesi: Appena si effettua il ping al server http la prima tipologia di messaggio è l'arp per trovare il mac address del server dns,dopo che mi ritorna il mac del server dns successivamente viene mandato un pacchetto dns che contiene il nome del dominio
("SIRulez.it") che andrà mandato una seconda volta al server dns, la risposta da parte del server dns è l'indirizzo ip del server http, poi verrà mandato un pacchetto ICMP che contiene l'indirizzo ip del server http che ha ricevuto e il server http risponderà con un pong ovvero che la comunicazione è andata a buon fine.(0% packet loss).

