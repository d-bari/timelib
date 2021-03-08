# Tag des Jahres

Windows Binaries
TagDesJahres.exe

GCC
Compiling and Building 
In the root folder of the project run : 

gcc -c -I .\lib\ .\main.c
gcc -c -I .\lib\ .\lib\timelib.c
gcc -o TagDesJahres .\main.o .\timelib.o

repplace "TagDesJahres" against executable file name. 

Run Programm : 
windows ps:
.\TagDesJahres.exe


