#Lab 4

##Zad 1
Wyświetl listę plików z aktualnego katalogu, zamieniając wszystkie małe litery na duże.

```
ls | tr [:lower:] [:upper:] | tr 'ąćęłńóżź' 'ĄĆĘŁŃÓŻŹ'
```


##Zad 2
Wyświetl listę praw dostępu do plików w aktualnym katalogu, ich rozmiar i nazwę.

```sh
??
```


##Zad 3 
Wyświetl listę plików w aktualnym katalogu, posortowaną według rozmiaru pliku.

```sh
ls -s
```

##Zad 4
Wyświetl zawartość pliku /etc/passwd posortowaną według numerów UID w kolejności od największego do najmniejszego.

```sh
cat /etc/passwd | sort -r
```

