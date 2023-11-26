# W świecie składni Markdowna 😱

To moja praktyczna ściągawka, która zawsze podpowie, jak używać składni Markdowna.  
Dwie spacje i enter dadzą nowy wiersz, ale bez nowego akapitu - tekst jest niżej, ale bliżej.

Shift + Clr + P - wyszukiwanie automatycznych funkcji

## Spis treści

- [W świecie składni Markdowna 😱](#w-świecie-składni-markdowna-)
  - [Spis treści](#spis-treści)
  - [Jak tworzyć nagłówki?](#jak-tworzyć-nagłówki)
  - [Wyróżnienia w tekście](#wyróżnienia-w-tekście)
    - [Pogrubienia - bold](#pogrubienia---bold)
    - [Kursywa](#kursywa)
    - [Cytaty](#cytaty)
    - [Równania, wzory matematyczne i kody](#równania-wzory-matematyczne-i-kody)
    - [Horizontal rule](#horizontal-rule)
    - [Przekreślanie tekstu](#przekreślanie-tekstu)
  - [Jak tworzyć wypunktowania lub listy numeryczne?](#jak-tworzyć-wypunktowania-lub-listy-numeryczne)
  - [Odsyłacze - jak umieszczać linki w tekście?](#odsyłacze---jak-umieszczać-linki-w-tekście)
  - [Jak wstawiać obrazy do tekstu?](#jak-wstawiać-obrazy-do-tekstu)
  - [Jak stworzyć tabelę w tekście?](#jak-stworzyć-tabelę-w-tekście)
  - [Inne przydatne informacje](#inne-przydatne-informacje)


## Jak tworzyć nagłówki?

Nagłówki pozwalają uporządkować tekst. Sprawiają, że jest on bardziej przystępny dla czytelnika. W Markdownie wprowadzamy je przy pomocy #. # - H1, ## - H2, ### - H3, itd.  

## Wyróżnienia w tekście

W zależności od potrzeb, możemy wyróżniać różne fragmenty swojego tekstu. Jest na to kilka sposobów. 

### Pogrubienia - bold

Copywriterzy SEO muszą pogrubiać odpowiedzi, których czytelnik szuka w ich tekście. Dzięki wizualnemu wyróżnieniu odbiorca szybciej trafia na interesującą go informację, jest usatysfakcjonowany i ma dobre skojarzenia ze stroną, autorem czy marką. Umiejętnie stosowane pogrubienie docenią także roboty Google'a.

Pogrubienie z angielskiego zwane jest boldem. W Markdownie wprowadzamy je zamykając pogrubiany fragment w **. Dwie *gwiazdki" stawiamy na początku i na końcu pogrubianego słowa, zdania, akapitu itd.

**Ten fragment jest pogrubiony, bo niesie istotną informację.**

### Kursywa

Kursywa nie ma większego znaczenia w świecie copywritingu SEO. Nie jest ona tak ważna dla robotów Google'a, jak wcześniej wspomniane pogrubienie. Czasem autorzy używają jej jednak do zaznaczenia nazwy własnej, cytatu lub w dowolnie wybranym przez siebie celu. 

Kursywę w Markdownie wprowadzamy podobnie, co pogrubienia, tyle że używamy jednej "gwiazdki", zamiast dwóch *.

*Kursywą zaznaczałam tytuły zagranicznych czasopism, z których korzystałam, pisząc pracę magisterską.*

### Cytaty

Cytaty pozwalają budować wiarygodność artykułu. Przywoływanie wypowiedzi ekspertów zwiększa zaufanie czytelnika do informacji, które znajduje w treści. 

Cytaty w Markdownie wprowadzamy znakiem większości >.

Oto cytat z *Fausta* J. W. Goethego:

> Jam częścią tej siły, która wiecznie zła pragnąc, wiecznie dobro czyni.

### Równania, wzory matematyczne i kody

Jeśli piszemy tekst dla maturzysty, w którym wyjaśniamy, że ujemna delta to dla niego nic dobrego, możemy zechcieć wyróznić w tekście równiania lub różne wzory. W Markdownie zrobimy to przy pomocy znaku `, którym zamkniemy ten fragment tekstu.

`X+Y=Z`

Tak samo wprowadzimy kod: 

`started_in = os.getcwd()
    download_content(terminology_url, terminology_languages)
    os.chdir(started_in)`

Możemy również tworzyć bloki kodu:

```
  started_in = os.getcwd()
    download_content(terminology_url, terminology_languages)
    os.chdir(started_in)
```

### Horizontal rule

Możesz zauważyć, że w tym tekście H1 i każde H2 oddziela pozioma kreska. W Markdownie wyróżnisz w ten sposób fragment tekstu stosując ---, ale pamiętaj, że bez spacji pomiędzy --- a tekstem, stworzysz po prostu kolejny nagłówek.

---

Sprawdź ściągawkę ze składni Markdowna!

---

### Przekreślanie tekstu

Fragmenty tekstu można także przekreślać. W ten sposób pokazujemy, że na przykład pewna część jest do wywalenia albo zmiany. 

W markdownie teksty przekreślamy zamykając je w znakach ~~ (dwa na początku, dwa na końcu).

~~Oto przekreślony, niepoprawny tekst.~~

## Jak tworzyć wypunktowania lub listy numeryczne?

To bardzo ważne części każdego tekstu, w którym aż prosi się, żeby coś wypunktować. Jeśli przedstawiamy "5 sposobów na...", wyjaśniamy, jak zrobić coś w trzech krokach albo wypisujemy wszystkie rzeczy, które muszą znaleźć się w bagażu podręcznym, koniecznie skorzystajmy z wypunktowań. One również porządkują tekst i ułatwiają jego odbiór czytelnikowi. 

W Markdownie listę numeryczną wprowadzamy po prostu używając cyfr:

*Niech w bagażu podręcznym znajdzie się:*
1. Dobra książka,
2. Butelka wody, 
3. Przekąska, 
4. Lek przeciwbólowy.

Wypunktowania wprowadzimy znakiem - 

* Poduszka na kark,
* Dokumenty,
* Słuchawki.

W Mardownie można także stworzyć zgrabną **listę do zrobienia**:

- [X] To już zrobiłam.
- [ ] A to muszę jeszcze zrobić.


## Odsyłacze - jak umieszczać linki w tekście?

Linkowanie ma kluczowe znaczenie w teksach pisanych pod SEO. Trzeba linkować do własnych treści lub do wiarygodnych źródeł "z zewnątrz" - na przykład rządowych portali. 

W Markdownie linki wprowadzamy za pomocą takiej składni: w nawiasie kwadratowym zamykamy anchor, czyli słowo czy zwrot, w którym chcemy umieścić link (może to być np. "Zobacz tutaj!"), a potem w nawiasie okrągłym umieszczamy właściwy link. Nawiasów nie przedzielamy spacją. 

[Ściągawka składni Markdowna](https://www.markdownguide.org/cheat-sheet/)

## Jak wstawiać obrazy do tekstu?

Trzeba pamiętać, że zdjęcie lub obraz, które chcemy umieścić w tekście, powinno być zapisane w tym samym folderze, co tekst, który piszemy w Markdownie. 

A umieścimy je przy pomocą następującej składni ! [tytuł obrazu] (nazwa pliku ze zdjęciem) - tylko nie używając spacji pomiędzy poszczególnymi elementami.

![mostek](mostek.jpg)

## Jak stworzyć tabelę w tekście?

Jeśli ogórek nie śpiewa..,

| Heading text | Definition text |
| ------------ | --------------- |
| Item A       | Definicion of A |
| Item B       | Definition of B |

...to najwidoczniej nie może.

## Inne przydatne informacje

- W Markdownie pliki zapisywać w rozszerzeniu nazwa.md. 
- Zapisywać je w tym samym folderze, co gitowe repozytorium.

Jeśli chcę zrobić z tego, co napisałam w Markdownie stronę internetową w gicie, muszę w nazwie tego pliku mieć "index".
