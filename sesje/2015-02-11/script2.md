# Zadanie 2

Losowy komputer

## Opis:

Wykorzystując kod z zadania 1 zmodyfikuj kod by komputer losował swój wybór wykorzystując moduł `random`.

Pomoże wam dokumentacja modułu random w internecie https://docs.python.org/3/library/random.html lub w interaktywnej konsoli: 
```python
import random
help(random)
```

**Podpowiedź:**
Wykorzystamy w tym zadaniu tzw `krotki` (ang. tuple) które służą do przechowywania sekwencji danych np.:
```python
my_numbers = (1, 20, 3, 10)
my_friends = ('John', 'Alice', 'Kate', 'Lucas')
my_pets = ('skipper', 'Mr. Parrot', 'kitty', 'blacky')
```
O krotkach i innych mechanizmach przechowywania danych opowiemy więcej w przyszłości.

## Explore:

* Spraw by wybór komputera był trochę `głupszy` i zamiast wybierać z pośród 3 możliwości z równym prawdopodobieństwem wybierał jedną opcję z z prawdopodobieństwem 50% a pozostałe dwie z 25%. 

* Spraw by wybór komputera był `głupszy` jak w A. ale tym razem element który będzie losowany z 50% prawdopodobieństwem również był losowy, np:

  - W pierwszym uruchomieniu komputer może wybrać: kamień 50%, papier 25%, nożyczki 25%.
  - W kolejnym uruchomieniu komputer może wybrać: kamień 25%, papier 50%, nożyczki 25%.

**Uwaga:** powyższe przykłady nie mają ustalonej kolejności, wybory komputera powinny być losowe!
