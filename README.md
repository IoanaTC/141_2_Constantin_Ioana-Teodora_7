# 141_2_Constantin_Ioana-Teodora_7
Tema 7. 
Se dau clasele:
-Locuință (string numeClient, int suprafataUtila, float discount)
-Apartament (int etaj) : Locuinta
-Casa (int suprafataCurte) : Locuinta
La clasa Locuinta se va adauga metoda virtuala pura CalculChirie (X,Y) cu X =valoare standard chirie/mp(intreg), Y=1 daca se ia in considerare discountul si 0daca nu se ia in considerare.
Metoda va fi adaugata in clasa Apartament dupa formula X*suprafataUtila*(1-Y*discount/100.0),   respectiv   in   clasa   Casa   dupa   formula   X*(suprafataUtila   +0.2*suprafataCurte) * (1-Y*discount/100.0).
Metodele vor fi testate prin parcurgerea unui vector de pointeri la Locuinta *,incarcat cu obiecte de tip Apartament si Casa.Se defineste clasa AgentieImobiliara continand un vector de pointeri la obiecte detip   Locuinta   alocat   dinamic.   
Se  va   supraincarca   operatorul   >>   pentru   a   citilocuintele agentiei si operatorul << pentru afisarea lor.
 
