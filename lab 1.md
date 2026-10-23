# Cwiczenie 1   
owoc(jablko).  
owoc(gruszka).  
owoc(sliwka).  
kolor(jablko,czerwony).  
kolor(gruszka,zielony).  
kolor(sliwka,fioletowy).   

1.Cw1.1 PODSTAWOWE. Napisz zapytanie zwracające kolor gruszki w zmiennej Kolor.  
kolor(gruszka, Opis)./ kolor(gruszka,X).  
L1.Cw1.2 PODSTAWOWE. Znajdź produkt o kolorze czerwonym, nie wpisując jego nazwy.  
kolor(X,czerwony).
L1.Cw1.3 DODATKOWE. Sprawdź owoc(banan)., a następnie dopisz fakt owoc(banan). przy innych faktach  
owoc/1. Porównaj wyniki.
njapierw będzie pokazywać false a nastęþnie true
L1.Cw1.4 DODATKOWE. Uruchom kolor(_,niebieski). Czy wynik mówi cokolwiek pewnego o wszystkich  
owocach w rzeczywistości?
Piszę true wiec mówi że w tym zbiorze owoców nie ma żadnego o kolorze niebieskim 
L1.Cw1.5 DODATKOWE. Porównaj kolor(gruszka,x). i kolor(gruszka,X). Wyjaśnij różnicę między x i X.  
x nie działa a X działa


# Ćwiczenie 2. Unifikacja i struktury  
## PROGRAM BAZOWY — ĆWICZENIE 2   
posiada(anna,ksiazka(hobbit,tolkien)).  
posiada(marek,ksiazka(diuna,herbert)).  
posiada(anna,ksiazka(solaris,lem)).  

Uwaga: punkty 2.3–2.5 to zapytania unifikacyjne z =. Nie wymagają faktów o czujnikach ani o parach.  

L1.Cw2.1 PODSTAWOWE. Wypisz tytuły książek Anny, ignorując ich autorów.   
posiada(anna,ksiazka(Tytul,_)).
L1.Cw2.2 PODSTAWOWE. Znajdź autora książki diuna bez podawania właściciela.   
posiada(_,ksiazka(diuna,Autor)).
L1.Cw2.3 DODATKOWE. Uzgodnij odczyt(dzwonek,K,glosny) = odczyt(dzwonek,sluch,P). Podaj K i P.  

L1.Cw2.4 DODATKOWE. Sprawdź, czy odczyt(lampa,wzrok,jasny) można zunifikować z odczyt(_,sluch,_).
Wyjaśnij wynik.  

L1.Cw2.5 DODATKOWE. Uruchom osobno para(X,X) = para(ania,marek). oraz para(X,X) =
para(ania,ania). Kiedy unifikacja jest możliwa?  





















