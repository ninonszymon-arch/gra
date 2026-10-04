Kicia & Rufi Runner V10 — BEST REBUILD

Najważniejsza zmiana:
Nie odtwarzam już wszystkich 16 wygenerowanych póz po kolei.
To właśnie powodowało efekt „odwijania / odpychania”.
Każda postać ma teraz krótki, spójny cykl łap:
0 → 1 → 2 → 3 → 2 → 1
przy stałych 7 FPS.

Skok:
- niski i krótki, w stylu Chrome Dino
- jedna poza przy wznoszeniu
- jedna poza przy opadaniu
- bez przewijania klatek biegu w powietrzu
- wysokość teoretyczna ok. 94px
- czas w powietrzu ok. 0.58s
- mobilne przeszkody dolne są mniejsze, żeby ten niski skok faktycznie je czyścił
- krótka tolerancja przy starcie skoku, żeby tap nie kończył się natychmiastową śmiercią

Telefon:
- jeden system pointer events zamiast mieszania touch + pointer
- tap = skok od razu
- przyciski nadal są wyłączone z obsługi skoku
- pion i poziom mają osobne dopasowanie wysokości planszy

Pozostało bez zmian:
- stare mapy
- urodzinowe tło dla „Ona + Rufi”
- górne i dolne przeszkody
- osadzenie dolnych przeszkód w ziemi
- wszystkie sprite sheety

Walidacja JavaScript: OK
