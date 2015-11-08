# timebank
Draft for a CMS for courses and a time bank

Who wants to share this project with me?

Banca del tempo

1) Organizzazione --> Iscritti

2) Iscritti --> Volontari, 

3) Volontario --> Propone Corso

4) Organizzazione --> Approva / Non approva il corso e lo mette in bacheca, stabilisce il limite di tempo entro cui iscriversi
	4.1) Se il corso è approvato al volontario viene dato un wallet e una direcotory dove aggiungere i materiali per il corso e un blog per tenere gli aggiornamenti per i corsisti

5) Se il corso si tiene allora il Volontario guadagna crediti per partecipare a un altro corso

	5.1) Come si guadagnano i crediti? Ad esempio: 
		a) per ogni ora di corso si guadagno credito per 30 minuti di corso.
		b) se il volontario a fine corso ottiene un buon punteggio nella valutazione dei corsisti ottiene 

6) Se il volontario partecipa a un corso può spendere i crediti del suo wallet e/o integrare in denaro.

Tabelle necessarie:
ACL: Utenti, Ruoli, Privilegi

Organizzazione: gestione utenti, gestione corsi

Users Area: Corsi seguiti, Corsi tenuti, Wallet crediti

Bacheca corsi-->Gestione classi studenti.

Corsi: Descrizione, materiali, Status (in via di approvazione, approvato, in corso, concluso)
Privilegi-> Proponente: La descrizione e i materiali 
	-> Organizzazione: Status

7) Eventualmente integrare sistema di e-learning (diventa complicato)

Flussi:
User:

	1.0) iscriviti
	2.0)Agisci 
	
		2.a)Partecipa a un corso 
			2.a.1) iscriviti al corso
			2.a.2) Paga
			2.a.3) Scarica i materiali
			2.a.4) Partecipa ai forum on line
		
		2.b)Proponi un corso
			2.b.1) upload CV
			2.b.2) Descrivi: contenuto, corsi
				2.b.2.1) C'è un esame?
			2.b.3) Upload materiali
		
		
