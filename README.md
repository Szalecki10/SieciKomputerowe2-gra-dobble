# SieciKomputerowe2-gra-dobble
Gra DOBBLE realizowana w ramach przedmiotu sieci komputerowe 2
Program dzieli się na serwer oraz client
serwer jest niezależny i po jego stronie znajduje sie cała logika gry
za pomocą klienta można się połączyć do wybranego lobby do serwera
Przy odpowiedniej (z góry ustalonej) ilości graczy uruchamiana jest gra
Wygrywa gracz który zdobędzie najwiecej punktów (najwięcej razy poprawnie połączy symbole wpisując ich nazwe)
Odzwierciedlenie gry dobble w tej wersji jest zainpirowane kalamburami na stronie scribble.io
Niestety gracz z większym pingiem ma utrudnienie ponieważ serwer nie uwzględnia czasu kiedy wiadomość została nadana a jedynie moment w którym ją odebrał
karty są wczytywane z pliku json
