# scripts-

#!/bin/bash


pg_dump -U (usuario) -h localhost -O -q -b -F c (banco) > (arquivo)_$DATA.backup

pg_restore -U (usuario) -h (localhost) -d (banco) > (arquivo).backup


lembrando:
backup data para selecionar arquivo
palavras entre parenteses devem ser substituido pelo respectivo local


definição de rodar hora 
Data='date +%Y %m %d_%H %M'
echo $TEXTO=
echo$VOLOR=
echo $DATA=


AGENDAR ROTINA NO LINUX= GEDIT/ETC/CRONTAB
