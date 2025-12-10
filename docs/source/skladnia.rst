Składnia elementów dokumentu
===========================

1. Nagłówki (poziomy)
---------------------

Nagłówek poziomu 1: tekst podkreślony znakiem "="  
Nagłówek poziomu 2: "-"  
Nagłówek poziomu 3: "^"  
Nagłówek poziomu 4: "~"

2. Akapit tekstowy
------------------
To jest zwykły akapit — po prostu linie tekstu oddzielone pustą linią.

.. note::
   To jest akapit informacyjny (Note).

.. tip::
   To jest Tip — dodatkowa wskazówka.

3. Fragment kodu
----------------
Liniowy: ``print("hello")``

Blokowy::

    def foo():
        return "bar"

4. Odnośniki
------------
- Lokalny (wewnętrzny): :doc:`/skladnia`
- Zewnętrzny: `Read the Docs <https://docs.readthedocs.com/>`_

5. Listy
--------
- Wypunktowana:
  * pierwszy
  * drugi
- Numerowana:
  1. krok jeden
  2. krok dwa

6. Obraz
--------
.. figure:: ../images/przyklad.png
   :alt: przykładowy obraz
   :figcaption: Przykładowy podpis pod obrazem.

7. Tabela
---------
+-----------+-----------+
| Kolumna A | Kolumna B |
+===========+===========+
| a1        | b1        |
+-----------+-----------+
| a2        | b2        |
+-----------+-----------+
