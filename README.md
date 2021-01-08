# cw9
## Paweł Rutkowski s18277

Rozwiązania wymaganych konstrukcji LINQ są zawarte w klasie `LinqSamples`.

Uruchomienie programu spowoduje wyświetlenie zawartości samych kolekcji `Emps` i `Depts`, jak
i poszczególnych poleceń.

W ramach tego ćwiczenia rozszerzyłem metody `ToString()` klas `Emps` i `Depts`, aby domyślnie
wyświetlały więcej informacji.

Zmieniłem również nieco formę klasy `LinqSamples` - wszystkie metody są teraz statyczne.
Nie było potrzeby tworzyć i wywoływać je dla konkretnego obiektu.
Stan tego obiektu nigdy nie ulegał by zmianie.