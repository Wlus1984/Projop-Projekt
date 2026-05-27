1. Nazwa i krótki opis projektu:

Prototyp
Przeglądarkowa gra typu Tower Defense z 100 falami przeciwników, systemem złota, bossami oraz dwoma typami wież do obrony bazy.

2. Jak uruchomić:
Sposób 1:
- Upewnij się że wszystkie pliki (Prototyp.html, shoot.wav, hit.wav, death.wav) są w tym samym folderze.
- Otwórz Prototyp.html w przeglądarce (nie wymaga połączenia z Internetem).
Sposób 2:
- Wejdź na moje repozytorium https://github.com/nazwa_konta/nazwa_projektu (skopiuj link i wklej w przeglądarce).

3. Funkcje:
Rozgrywka: fale przeciwników (100 fal), system złota za zabicie wrogów, 100 punktów życia gracza, ekran końca gry.
Wieże: Wieża Podstawowa (niebieska, zasięg 120, celowanie predykcyjne), Wieża Salwowa (różowa, zasięg 85, strzela we wszystkich kierunkach).
Przeciwnicy: Weak, Swift, Tank, Elite – różne prędkości, HP i nagrody złota. Bossowie co 25 falę (fale 25, 50, 75, 100).
System życia: zwykły przeciwnik który dotrze do końca ścieżki odbiera 1 życie, boss który dotrze do końca zabija natychmiast (życia = 0).
Interfejs: sklep po prawej stronie, HUD na dole (złoto, fala, pozostali przeciwnicy, życia), pauza (ESC), menu główne, ustawienia głośności.
Dźwięki: strzał, trafienie, śmierć przeciwnika – regulowana głośność w ustawieniach.

4. Struktura:
- Prototyp.html   # Cały kod gry (struktura, style, logika)
- shoot.wav       # Dźwięk strzału
- hit.wav         # Dźwięk trafienia
- death.wav       # Dźwięk śmierci przeciwnika
- README.txt      # Dokumentacja

5. Użycie:
Start: Kliknij „Start" w menu głównym, aby rozpocząć grę od fali 1.
Wieże: Kliknij „Wieża b." lub „Wieża sal." w sklepie (prawy panel), a następnie kliknij na mapie, aby postawić wieżę. ESC lub przycisk „Anuluj" anuluje wybór.
Pauza: ESC podczas gry pauzuje i pokazuje menu z opcją powrotu do menu głównego.
Ustawienia: Dostępne z menu głównego – suwak głośności dźwięków.
Koniec gry: Gdy życia spadną do 0 (boss dotarł do końca lub skończyły się życia), pojawia się ekran z wynikiem i przyciskiem powrotu do menu.

6. Zależności:
Brak zewnętrznych bibliotek. Gra działa w czystym JavaScript/HTML5 Canvas.

7. Licencja:
MIT

8. Link do kodu:
https://github.com/Wlus1984/Projop-Projekt
