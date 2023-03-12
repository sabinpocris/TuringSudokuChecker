
# Tema 1 - Pocris Sabin - 322CB


## Linii

Desen: [Link](https://imgur.com/VKp1xoC)

Am ales sa implementez cate o stare pentru fiecare combinatie de input pentru o regiune
corecta, porning de la ql pana la ql1234(s-au citit toate variantele posibile pentru un
input corect). De exemplu, daca ma aflu in starea ql123 si citesc valoarea 1, pot considera
ca sudokul nu este corect, pentru ca eu deja am citit valorile 1,2,3 iar 1 se regaseste acolo.

Din starea ql1234 voi intra in starea ql din nou si se ve repeta algoritmul pana
voi da de un caracter blank, ceea ce inseamna ca am terminat inputul.

De aici, ma intorc la inceputul benzii si incep verificarea pe coloane.


## Coloane

Desen: [Link](https://imgur.com/uqZbaeT)

Am incercat sa aplic acelasi algoritm ca si mai sus, doar ca am ajuns la concluzia
ca numarul starilor creste destul de repede si am decis sa merg pe varianta copieri
coloanele pe rand, la sfarsitul benzii, urmand sa fac verificarea pe fiecare copie
dupa algoritmul de la subpunctul 1.


## Regiuni

Desen: [Link](https://imgur.com/huWjlMD)

Am ales sa fac un hibrid intre cele 2 subpuncte: voi folosi algorimutul de la numarul 1,
doar ca efectuez un salt la urmatoarea zona care trebuie verificata, putand sa ma folosesc
de positia zonei fata de reperele: ':' si '*'.

Algoritmul incepe ca la subpunctul 1, verifica prim pare a regiunii si apoi sare la 
a 2-a parte a regiunii, urmand sa treaca in starea reprezentand a 2-a regiune and so on.

Ca la subpunctul 1, cand intalneste un input deja inregristrat ca si citit in stare,
masina se opreste.
