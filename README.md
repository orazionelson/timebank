# timebank
## sharing time in the sharing economy

1) Organizzazione --> Iscritti

2) Iscritti --> Docenti 

3) Docente --> Propone Corso

4) Organizzazione --> Approva / Non approva il corso e lo mette in bacheca, stabilisce il limite di tempo entro cui iscriversi
	4.1) Se il corso è approvato al Docente viene dato un wallet e una direcotory dove aggiungere i materiali per il corso e un blog per tenere gli aggiornamenti per i corsisti

5) Se il corso si tiene allora il Docente guadagna crediti per partecipare a un altro corso

	5.1) Come si guadagnano i crediti? Ad esempio: 
		a) per ogni ora di corso si guadagno credito per 30 minuti di corso.
		b) se il Docente a fine corso ottiene un buon punteggio nella valutazione dei corsisti ottiene 

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

Users & User Stories		
	1) Visitor: can just Read, Register, Apply for the ML
	2) Registered User: can Apply for Courses, can Contact the oganization
	3) Student (A registered user the applied to a course): can Read and Use course board
	4) Teacher (A registered user that offers a course): Can Edit the course board and a blog
	5) Tutor (A member of the organization that organize the course): Full CRUD on his courses, 
	6) Administrator

User:

	1.0) Register
	2.0) Do 
		2.a)Partecipa a un corso 
			2.a.1) iscriviti al corso
			2.a.2) Paga
			2.a.3) Scarica i materiali
			2.a.4) Partecipa ai forum on line
		
		2.b)Proponi un corso
			2.b.1) upload CV
			2.b.2) Descrivi: contenuto, corsi
				2.b.2.1) Durata totale in ore
				2.b.2.2) Durata singole lezioni			
				2.b.2.3) C'è un esame?
			2.b.3) Bibliografia / Linkografia	
			2.b.4) Upload materiali: PDF, ppt, img


		
