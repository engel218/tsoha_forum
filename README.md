## Discussion forum (web application)
This is uni work, a course project for tsoha (summer 2024).

&nbsp;
This project is a discussion forum with different boards, separated by topic. These boards include message  threads relevant to the topic. Similar to the first example project introduced in https://hy-tsoha.github.io/materiaali/aiheen_valinta/ .

* forum specifics:
  * the main page shows the forum title, a navigation menu and a boards list
  * for each board is listed: topic of board, summary of board contents, total message count, total thread count, information about latest message (thread title, writer, datetime)
  * threads are listed under the board they belong to (newest thread on top)
  * for each thread is listed: thread topic, writer, message count, information about latest message (writer, datetime)
&nbsp;
* user-side functionality:
  * login function
  * registration for users
  * users can create threads (needs title + opening message)
  * users can reply to existing threads 
  * users can edit their own messages and titles for the threads they created
  * users can delete their own messages
&nbsp;
* search function:
  * you can search for messages that contain a requested word
&nbsp;
* forum moderation:
  * moderators can edit or delete messages from threads
  * moderators can delete threads
  * moderators can lock threads (read-only) or limit the access to a thread (or a board)
  * messages show the datetime and writer, if a message has been edited it also shows the last modification datetime and who modified the message (original poster or moderator)


## Keskustelufoorumi-sovellus

Kuten kurssisivulla annettu malli.
&nbsp;
* Sovellus sisältää seuraavat ominaisuudet:
  * kirjautuminen ja tunnuksen luonti käyttäjille
  * etusivulla listaus alueista jossa näkyy aihe, ketjujen määrä, viestien kokonaismäärä ja viimeisimmän viestin tiedot (aihe, kirjoittaja, ajankohta)
  * käyttäjä voi luoda viestiketjun (otsikko + viesti)
  * käyttäjä voi muokata omia viestejään ja ketjujaan (otsikko + aloitusviesti)
  * käyttäjä voi vastata viestiketjussa viesteihin
  * käyttäjä voi poistaa (oman) viestinsä ketjusta
  * sovelluksessa on toiminto viestien etsimiseen (sanan perusteella)
  * ylläpito-ominaisuuksia kuten viestien ja ketjujen poisto/muokkaus, aiheiden ja ketjujen näkyvyys (kuka pääsee lukemaan/kirjoittamaan ketjuun tai aihealueelle)
  * viesteissä näkyy kirjoituspäivä ja ajankohta, sekä kuka on viimeksi muokannut sitä ja milloin (jos viestiä on muokattu alkuperäisestä)
