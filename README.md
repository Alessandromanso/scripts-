# scripts-backup-BD (ALESSANDRO MIGUEL MANSO)

#!/bin/bash

export PGPASSWORD = "1234"


pg_dump -U postgre -h localhost -O -q -b -F c bercario > bercario_$DATA.backup


pg_restore -U postgre -h (localhost) -d bercario > bercario.backup


_______________________________________________________________________________________________________________________________________



Obs: lembrando: backup data para selecionar arquivo palavras entre parenteses devem ser substituido pelo respectivo local

definição de rodar hora Data='date +%Y %m %d_%H %M' echo $TEXTO= echo$VOLOR= echo $DATA=AGENDAR ROTINA NO LINUX=GEDIT/ETC/CRONTAB

________________________________________________________________________________________________________________________________________



obs: lembrando:
backup data para selecionar arquivo
palavras entre parenteses devem ser substituido pelo respectivo local


definição 

de rodar hora 
Data='date +%Y %m %d_%H %M'
echo $TEXTO=
echo$VOLOR=
echo $DATA=


AGENDAR ROTINA NO LINUX= GEDIT/ETC/CRONTAB
