# Git och Github
## Vad är Git och varför ska vi använda oss av detta?
Git är ett litet program som används för att hantera olika versioner av kod. När man jobbar med programmering på ett *iterativt* sätt vill man ha koll på varenda liten ändring. När man är flera personer som arbetar med samma kodbas vill man också ha möjlighet att hantera situationer när flera personer ändrar i samma fil. Git är ett program som hjälper oss med sådant.

Git är gratis och källkoden är öppen. Programmet skapades av Linus Torvalds, samma person som skapade Linux.

## Vad är Github?
Github är en kommersiell tjänst som tillhandahåller ett ställe i molnet där utvecklare kan lägga sin kod och samarbeta med andra. Tjänsten drar nytta av programmet Git, därav namnet. Att skapa ett konto på Github är gratis och något som nästan alla professionella utvecklare har.

En hink med kod på Github kallas för ett **repository** ("repo"). Lär dig det ordet.

Obs: Det är fullt möjligt att använda Git utan att använda Github.

## Kom igång
1. Gå in på [git-scm.com/downloads](https://git-scm.com/downloads) och ladda hem Git
2. Installera Git. Välj Visual Studio Code som "default editor"
3. Öppna ett terminalfönster (Powershell)
   1. Skriv `git config --global user.name "Your Name"`
   2. Skriv `git config --global user.email you@example.com`
4. Gå in på [github.com](https://github.com) och registera ett konto

Woho! Klappa dig själv på axeln. Nu är du redo för... ditt första repository!

## Ditt första repository
1. Gå in på [github.com](https://github.com)
2. Skapa ett nytt repository som heter `hello-world`. Välj `public`.
3. Öppna ett terminalfönster (Powershell) och navigera till en mapp där du har dina projekt.
4. Skriv `git clone https://github.com/<ditt namn här>/hello-world.git`
5. Gå in i mappen genom att skriva `cd hello-world`
6. Öppna Visual Studio Code genom att skriva `code .` Punkten betyder att du ska öppna programmet där du står, dvs i mappen hello-world.
7. Skapa en ny fil som heter `hello-world.py` och fyll det med `print(̈́"Hello, world")`. Spara.
8. Skriv `git status`. Detta kommando visar status. Det är ett helt säkert kommando som inte kan förstöra något.
9. Skriv `git add .` för att fånga upp och lägga till alla ändringar i mappen (i det här fallet bara en ny fil)
10. Skriv `git status` igen för att se skillnaden
11. Skriv nu `git commit -m "My first commit"` för att definitivt bekräfta alla ändringar. En ny commit / stämpel skapas.
12. Skriv `git push` för att knuffa upp koden till Github
13. Gå in på `github.com/<ditt namn>/hello-world` och kolla att koden ligger där

Woho! Klappa dig själv på axeln. Du har tagit ett viktigt steg mot att bli en kompetent utvecklare.

## Två olika fall

### A: Skapa ett nytt projekt
För nya projekt kan du följa mallen ovan, dvs skapa ett repository på Github och använd sedan `git clone` för att få en kopia på din dator som du kan arbeta utifrån.

### B: Du har redan kod på din dator som du vill skapa ett repository för
1. Gå in på [github.com](https://github.com) och skapa ett repository med samma namn som ditt projekt/mapp på datorn. Välj `public`.
2. Navigera till mappen i Powershell lokalt på din dator
3. Skriv `git init`
4. Skriv `git remote add origin https://github.com/<ditt användarnamn>/<ditt repo-namn>.git`
5. Skriv `git add .`
6. Skriv `git commit -m "Initial commit"`
7. Skriv `git push -u origin master`

## Löpande arbete med Git
Kommer..
