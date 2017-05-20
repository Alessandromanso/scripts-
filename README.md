# scripts-

!/bin/bash


pg_dump -U (usuario) -h localhost -O -q -b -F c (banco) > (arquivo).backup

pg_restore -U (usuario) -h (localhost) -d (banco)b(arquivo).backup

lembrando:
backup data para selecionar arquivo
palavras entre parenteses devem ser substituido pelo respectivo local
