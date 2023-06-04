# compilar_tad_c_windows
como compilar TAD C no Windows

Terminal : PowerShell

cd (endereço do diretorio  onde estam os arquivos a serem Compilados)
ls (listagem de arquivos)

gcc - c ( aquivo .c que deve ser execulado) arquivo.c  >> turma.o >> se torna um arquivo execultavel 
o arquivo .c  possui em sua referencia o arquivo .h não sendo necessário a execulção do arquivo .h

gcc main.c arquivo.o -o main
./main
