Aplicatie de chat   

 Utilizatorii pot transmite mesaje atat sub forma de direct message cat si pe grupuri.
 Mesajele sunt stocate in baza de date si pot fi accesate doar de catre utilizatorii participant la conversatie. 

Aplicatia:
	Ferestre:
	1.Login/Register
	2.Main Page -> ?fereastra setari?
	3.Grup/Conversatie

Baza de date:

-Utilizatori
1.id_util
2.nume
3.prenume
4. ? poza ?
5.nr telefon
6. ? detalii ?
7.email
(send verificare pe mail/alerta conectare)

-Mesaje
1.id_mesaj
2.id_utilizator_sender
3.ora
4.text
5.id_utilizator_receiver accepta NULL
6.id_receiver_grup accepta NULL
(verifica proceduri stocate sau in client??)

-Grupuri
1.id_grup
2.nume_grup

-Grupuri_utilizatori
1.id_grup
2.id_util


