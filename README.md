# IAA-DALIproject
Progetto DALI relaizzato per il corso Intelligent Autonomous Agents nell'anno accademico 2021/2022 al DISIM UnivAQ.

Il progetto è stato sviluppato in sistemi operativi linux ubuntu e MacOS utilizzando la versione 4.7.1 di sicstus.
Nella repository è già presente la cartella src, ed essa è quella riferita dal file startmas.sh. In quest’ultimo file va aggiornato il percorso della variabile SICSTUS_HOME in base a dove è stato installato sicstus ed in base alla versione installata. Infine la riga 18 del file startmas.sh, ossia:

# rm -f work/* remove everything if you want to clear agent history

deve rimanere con il # all’inizio, ossia commentata. Questo perché sono state modificate le direttive riguardo alcuni eventi interni degli agenti. Togliere il # all’inizio di questa riga potrebbe influire sul corretto funzionamento degli agenti.
