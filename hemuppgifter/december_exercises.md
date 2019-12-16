# Repetitionsövningar december 2019

### Torsdag 5 december

1. Gör ett program som skriver ut ett tal i taget från 0, 1, 2 och så vidare, **med en sekunds mellanrum**:

Output:
```
0
1
2
3
4
5
6
7
... osv
```

2. Definiera funktionen `questionify` som tar en sträng som argument och som returnerar samma sträng men med ett frågetecken efter. Så `questionify("Jag heter Einar")` returnerar `"Jag heter Einar?"`. Printa ut resultatet så ni ser att det stämmer.

3. Definiera funktionen `divisible_by_five` som tar ett argument och returnerar `True` om argumentet är delbart med fem och `False` annars

4. Definiera funktionen `angry` som tar en sträng som argument och returnerar samma sträng fast bara stora bokstäver **och** tre utropstecken efteråt.
`angry("kan du vara snäll och räcka mig mjölken?")` returnerar `"KAN DU VARA SNÄLL OCH RÄCKA MIG MJÖLKEN?!!!"`

5. Definiera funktionen `copy_list` som tar en lista som argument och som returnerar en kopia av listan

6. Gör ett program som i uppgift ett, men det tickar bara upp till och med 3 och sen börjar det om igen från 0. En sekunds mellanrum.

Output:
```
0
1
2
3
0
1
2
3
0
1
2
... osv
```
7. Skriv ett program som skapar en tom lista. Fyll sedan listan med ditt eget namn 50 gånger. Printa ut listan så du ser att det stämmer

8. Definiera funktionen `contains` som tar två argument. En lista och en sträng. Funktionen ska returnera `True` om strängen finns i listan.
```
cities = ["Stockholm", "New York", "Tokyo", "Berlin"]

contains(cities, "Tokyo") # Returnerar True
contains(cities, "Madrid") # Returnerar False
```

### Måndag 9 december

9. Definiera funktionen `divisble_by` som tar två heltal som argument och returnerar en boolean. Den ska returnera `True` om det första talet är delbart med det andra, annars `False`.

10. Definiera funktionen `randomlist` som tar ett heltal som argument och som returnerar en lista med slumptal 0-100 som är lika lång som argumentet anger. Alltså `randomlist(5)` skulle t.ex. kunna returnera `[44, 15, 85, 31, 19]`

### Torsdag 12 december

11.  Ta reda på hur man använder metoderna `split` och `join` på strängar i Python. Använd internet för att söka reda på svaret och labba själv tills du känner att du har koll.

12. Använd funktionen `divisible_by` från fråga 9 för att skriva ut alla tal mellan 1 och 1000 som är delbara med 7 men inte delbara med 2.

13. Ta reda på hur man slice-ar listor i python. Använd internet för att söka reda på svaret och labba själv tills du känner att du har koll.

14. Definiera funktionen `has_equal_ends` som tar en lista som argument och returnerar `True` ifall första och sista elementet är lika, annars `False`.

15. Definiera funktionen `is_palindrom` som tar en sträng som argument och returnerar `True` om strängen är ett palindrom, dvs. om det är samma sak baklänges (t.ex. "anna"). Annars returnera `False`

16. Skriv ett program `lotto.py` som är ett lottospel. Programmet ska ge en lottorad till användaren på 7 tal. Använd `randomlist` från fråga 10. Slumpa sedan ett tal mellan 1-100 och berätta för användaren om den vann.

17. Utöka programmet `lotto.py` för att hantera pengar. Låt varje lott kosta 5 kr och vinst ge 30 kr. Efter varje spel ska det skrivas ut hur mycket pengar spelaren har.

18. Ta reda på hur man skriver ut dagens datum, veckodag och tid med Python. Använd internet.

19. Skriv ett program `clock.py` som skriver ut vad klockan är och uppdateras varje sekund.

20. Ta reda på vad funktionerna `ord` och `chr` gör för något. Använd internet för att söka reda på svaret och labba själv tills du känner att du har koll.

### Måndag 16 december

21. Skapa filen `encryption.py`. Använd det du lärt dig i fråga 20 om `ord` och `char` för att definiera en superenkel krypteringsfunktion `silly_encrypt`. Den ska ta en sträng och shifta alla bokstäver 1 steg framåt. A->B, B->C, C->D och så vidare. Ex. `silly_encrypt("abc")` ska returnera `bcd`

22. Skapa filen `journal.py`. Definiera funktionen `save_journal_entry` som tar ett dagboksinlägg som argument och sparar det till filen `my_journal.txt`. Varje gång du kör funktionen ska det läggas till sist i filen (istället för att filen skrivs över). Du behöver googla runt för att ta reda på hur man gör.

23. Utöka `silly_encrypt` så att den även tar ett argument `shift`, som anger hur många bokstäver som ska skiftas. T.ex `silly_encrypt("abc", 2)` ska returnera `cde`. Definiera även `silly_decrypt` som gör motsatsen, dvs tar ett krypterat meddelande och avkrypterar det.

24. Utöka `save_journal_entry` så att den även lägger till dagens datum och tid varje gång den körs.

25. I `journal.py`, definiera funktionen `add_journal_entry`. Den ska ställa några dagboksfrågor till användaren. Resultatet ska krypteras med hjälp av `silly_encrypt` (behöver importeras) och sparas med hjälp av `save_journal_entry`

26. I `journal.py` definiera funktionerna `load_journal_entries` och `print_journal`. `load_journal_entries` ska bara ladda in texten från `my_journal.txt` och returnera denna. `print_journal` ska anropa `load_journal_entries`, dekryptera innehållet och skriva ut det på skärmen.

27. I `journal.py`, definiera funktionen `show_menu` som låter användaren välja mellan att skriva nytt dagboksinlägg, visa dagboken eller avsluta programmet. Längst ner i filen, kalla på funktionen `show_menu` så att det blir ett körbart program.

28. Ta reda på vad som menas med `if __name__ == "__main__"` i Python. Använd internet för att söka reda på svaret och labba själv tills du känner att du har koll. Anpassa programmet `journal.py`

29. Flytta `journal.py` och `encryption.py` till en egen mapp och ett eget repo på Github.

30. Lägg till en fil `README.md` i `journal`-repot. Skriv lite kort vad det är för ett program. Använd markdown: https://markdown-guide.readthedocs.io/en/latest/basics.html

31. Påminn dig om hur man använder dictionaries. Använd internet och labba själv tills du känner att du har koll.