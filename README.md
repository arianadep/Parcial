##Parcial
Punto 1
concatenar las secuencias con este código ```cat 'sequence (1).txt'  'sequence (2).txt' 'sequence (3).txt' 'sequence (4).txt' 'sequence (5).txt' 'sequence (6).txt' 'sequence (7).txt' 'sequence (8).txt' >> concatenado_secuencias.txt```
para modificarlo con expresiones regulares ```sed

blast ```makeblastdb -in secuencia.fasta -dbtype nucl -parse_seqid
s -out trans_mistice -title "secuencia"```

punto 2
concatenar ```cat concatenado_secuencias.txt query.fasta >> secuencias.fasta```
hacer alineamiento con muscle 
```muscle -in secuencias.fasta. -out secuencia_muscle.fasta```
con sbatch 
no me sirvió sbatch

punto 3

12. las secuencias de proteínas no tienen intrones porque al pasar de la traducción los intrones no son codificantes y se quitan

para zip el archivo
instalar ```sudo apt install zip```

