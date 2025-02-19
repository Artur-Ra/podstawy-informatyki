
# Topologie Sieci

## Sieci Fizyczne
Sieci fizyczne odnoszą się do fizycznego ułożenia kabli, i połączeń. Przykłady:
- **Topologia magistrali** (bus): charakteryzuje się tym, że wszystkie elementy sieci są podłączone do jednej magistrali
- wady: lokalizacja usterek jest trudna, słaby poziom bezpieczeństwa 
- zalety: małę zużycie przewodu, brak dodatkowych urządzeń, niski koszt producji
- gdzie stosowane: w małych sieciach lokalnych np. niewielkie biuro, domy 
- **Topologia gwiazdy** (star): charakteryzuje się tym, że kable sieciowe od wszystkich urządzeń zbiegają sie w jednym punkcie(punkt dostępu)
- wady: ograniczona liczba komputerów, duże zużycie kabli
- zalety: wysoka przepustowość, wydajność
- gdzie stosowane: w średnich i dużych sieciach lokalnych np. lotniskach, 
- **Topologia pierścienia** (ring): charakteryzuje się połączeniem komputerów bez zakłuceń(układzie zamkniętym), co można uprościć do koła
- wady: złożona diagnostyka sieci, pracochłonna rekonfiguracja
- zalety: małe zużycie przewodów
- gdzie stosowane: w średnich sieciach lan

## Sieci logiczne
Sieci logiczne opisują sposób przesyłania danych między urządzeniami, niezależnie od fizycznej struktury. Przykłady: 
- **Punktu-punkt**(Point-to-Point) charakteryzuje się bezpośrednim połączeniem między dwoma węzłami sieci.
- wady: ciężko o dużą ilość połączeń, jedeno zerwane połączenie zarzymuje całą komunikacje
- zalety: bezpieczeństwo, dedykowane połączenie
- gdzie stosowane: przy łączeniu dwóch sieci lan
- **Przekazywanie żetonu** (Token Passing): podobna do topologii pierścienia; charakteryzuje się tym, że tylko stacja posiadająca token ma prawo do wysyłania danych do łącza, pozostałe urządzenia jedynie nasłuchują
- Wady: przerwanie jednego z łączy powoduje przerwe w działaniu całej sieci
- Zalety: duża wydajność przy obciążeniu
- Zastosowanie: całkowicie wyparta przez ethernet
- **Wielodostępowa** (Multiple Access): charakteryzuje się brakiem specyficzności celu, tzn. wiadomość jest przesyłana do wszystkich komputerów w sieci, ale tylko cel jest w stanie ją zinterpretować
- Wady: konieczne jest wprowadzenie tokena
- Zalety: każde użądzenie widzi wszystkie informacje, tylko ich nie interpretuje 
- Zastosowanie: nie znalazłem
