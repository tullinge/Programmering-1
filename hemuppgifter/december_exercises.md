# Repetitionsövningar december 2019

### Från torsdag 5 december
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

9. Definiera funktionen `divisble_by` som tar två heltal som argument och returnerar en boolean. Den ska returnera `True` om det första talet är delbart med det andra, annars `False`.

10. Definiera funktionen `randomlist` som tar ett heltal som argument och som returnerar en lista med slumptal 0-100 som är lika lång som argumentet anger. Alltså `randomlist(5)` skulle t.ex. kunna returnera `[44, 15, 85, 31, 19]`
