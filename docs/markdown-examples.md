# Jak stosować notację Markdown
![Markdown logo](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/220px-Markdown-mark.svg.png)

Markdown – język znaczników przeznaczony do formatowania tekstu zaprojektowany przez Johna Grubera i Aarona Swartza. Został stworzony w celu jak najbardziej uproszczenia tworzenia i formatowania tekstu. Markdown został oryginalnie stworzony w Perlu, później dostępny w wielu innych. Jest rozpowszechniany na licencji BSD i jest dostępny jako wtyczka do kilku systemów zarządzania treścią.

### Nagłówki (Setext)
Nagłówki w stylu Setext dla `<h1>` i `<h2>` są tworzone przez „podkreślanie” znakami równości (=) lub dywizami (-).

#### Składnia
```markdown
Nagłówek pierwszego poziomu
===========================

Nagłówek drugiego poziomu
-------------------------
```

#### Wynik
```html
<h1>Nagłówek pierwszego poziomu</h1>
<h2>Nagłówek drugiego poziomu</h2>
````

### Nagłówki (atx) <!---  -->

### Cytaty <!---  -->
Bloki cytatów są oznaczane przez użycie zapożyczonych z e-maili znaków „>”.

####Składnia
> To jest blok cytatu.
>
> To jest drugi akapit w bloku cytatu.
>
####Wynik
```<blockquote>
    <p>To jest blok cytatu.</p>
    <p>To jest drugi akapit w bloku cytatu.</p>
</blockquote>
```


### Emfaza fragmentów tekstu <!---  -->

### Listy punktowane <!---  -->

### Listy numerowane <!---  -->

### Linki "w tekście" <!---  -->

### Linki w stylu referencyjnym <!---  -->

### Grafiki "w tekście" <!---  -->

### Grafiki w stylu referencyjnym <!---  -->

### Kod <!---  -->
