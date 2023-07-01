# piac

## Készítsd el és olvasd be a piac.txt fájlt és tárold az elemeit megfelelő classokban!
- Eleinte elég, ha nem hozol létre enumot, csak Stringben tárolod a sós/édes értéket! 
- Amint már működik a beolvasás és példányosítás, módosíthatod enumra a Stringet!

- Hány db hatósági áras termék van?
- Mekkora a sós és édes termékek aránya?
- Mi a legdrágább/legolcsóbb?


  

piac.txt

tojás;1 db;100;TRUE;sós

cukor; 1 kg;250;TRUE;édes

vaj;100 g;1000;FALSE;sós

Milka csoki;1 tábla;666;FALSE;édes

rizs;1 kg;800;FALSE;sós

pityóka;1 kg;400;TRUE;sós


## Ha az eddigiekkel készen vagy, módosítsuk kicsit a piac.txt fájlt, adjunk hozzá plusz attribútumokat az egyes ételekhez!

- A sorok formátuma (melyik rész mit jelent):
név; egység; ár (Ft-ban); hatósági áras-e; kategória (sós/édes); beszerzési helyek vesszővel elválasztva, nem tudjuk előre hány db lesz (őket vmi Collectionben kell majd tárolnod)



piac.txt

tojás;1 db;100;TRUE;sós;Nagyi farmja,Papi boltja

cukor; 1 kg;250;TRUE;édes;kurvára nem kapható sehol

vaj;100 g;1000;FALSE;sós;CBA,TESCO,Príma,Madaras Teszkó

Milka csoki;1 tábla;666;FALSE;édes;csokibánya

rizs;1 kg;800;FALSE;sós;Japán,Kína,TESCO

pityóka;1 kg;400;TRUE;sós;Pityuka pityókás pultja

- Melyik termék kapható a legtöbb helyen?
- Van olyan hely, ahol több termék is elérhető?
