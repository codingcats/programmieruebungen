# programmieruebungen

## Namen ausgeben lassen

Schreibe ein Programm, welches nach dem Namen und der Lieblingsfarbe der Benutzerin fragt. Anschließend sollen diese ausgegeben werden:

```bash
$ ruby names.rb
> Vorname: Jan
> Lieblingsfarbe: Gruen
> Hallo, ich heiße Jan und meine Lieblingsfarbe ist Gruen.
```

Verwendete Konzepte:

* Text auf der Konsole ausgeben
* Von der Kommandozeile Eingaben lesen

## Gerade Zahlen ausgeben

Schreibe ein Programm, welches eine natuerliche Zahl abfragt und dann alle geraden Zahlen von 0 bis zur eingegeben Zahl
ausgibt.

```bash
$ ruby even_numbers.rb
> Deine Zahl: 100
> 0
> 2
> 4
> 6
> ...
```

Verwendete Konzepte:

- Text auf der Konsole ausgeben
- Von der Kommandozeile Eingaben lesen
- For Schleife

## Variablen tauschen

Schreibe ein Programm, welches zwei Zahlen einliest und sie in die Variablen `a` und `b` speichert.
Nun tausche die Werte von `a` und `b` und gib sie danach aus.


```bash
$ ruby swap.rb
> Zahl fuer a: 5
> Zahl fuer b: 4
> Wert von a: 4
> Wert von b: 5
```

Verwendete Konzepte:

- Dreieckstausch von Werten

## FizzBuzz

Schreibe ein Programm, dass die Zahlen von 0 bis 100 ausgibt. Fuer jede Zahl, die durch 3 teilbar ist, gebe statt der Zahl `fizz` aus.
Fuer jede Zahl, die durch 5 teilbar ist, gebe statt der Zahl `buzz` aus. Wenn eine Zahl durch 3 und 5 teilbar ist, gebe `FizzBuzz` aus.

```bash
$ ruby fizzbuzz.rb
> 0
> 1
> 2
> Fizz
> 4
> Buzz
> Fizz
> 7
> ...
> 14
> FizzBuzz
> 16
> ...
```

Verwendete Konzepte:

- For loop
- If-Abfrage
- Text auf der Konsole ausgeben

## Phonebook

Schreibe ein Programm, dass ein Telefonbuch aus einer Datei liest (numbers.json) und anzeigt.

```bash
$ ruby phonebook.rb
> All entries:
> Edit Mueller - 524532432
>
> Else Maier - 769521
>
> Michael Schmidt - 48531
>
> Erik Schmidt - 54391

```

Verwendete Konzepte:

- Aus Datei lesen
- JSON parsen
- Auf dem Bildschirm ausgeben


### Zusatzaufgabe 1

Erweitere das Programm oben so, dass man nach einem Eintrag suchen kann (nach Name):

```bash
$ ruby phonebook.rb Mueller
> Edit Mueller - 524532432
```

Wenn kein passender Eintrag gefunden wurde, soll folgende Ausgabe erscheinen:

```bash
$ ruby phonebook.rb Simon
> Kein Eintrag zu `Simon` gefunden
```

### Zusatzaufgabe 2

Erweitere das Programm so, dass man auch nach der Telefonnummer suchen kann:

```bash
$ ruby phonebook.rb 769521
> Else Maier
```

Wenn kein passender Eintrag gefunden wurde, soll folgende Ausgabe erscheinen:

```bash
$ ruby phonebook.rb 12345
> Kein Eintrag zu `12345` gefunden
```

Gravatar
