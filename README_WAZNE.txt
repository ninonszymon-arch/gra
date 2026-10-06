Kicia & Rufi Runner V12 — NEW FRAMES + NATURAL JUMP

POSTACIE:
- wszystkie sześć postaci korzysta z najnowszych, od nowa wygenerowanych sprite sheetów
- stare sprite sheety zostały usunięte
- każda klatka została oczyszczona i wyrównana do wspólnej linii łap
- animacja biegu: prawdziwe klatki przy stałych 7 FPS
- skok używa osobnej sekwencji klatek przez cały łuk skoku

MECHANIKA SKOKU:
- NIE kopiuje Chrome Dino
- brak sztucznej niewidzialności / przebaczania kolizji
- tap daje natychmiastowy, krótki łuk
- JUMP_MOBILE = -710
- GRAVITY_MOBILE = 2100
- wysokość fizycznego skoku ≈ 120px
- czas w powietrzu ≈ 0.68s
- przeszkoda w tym czasie przejeżdża ≈ 120–153px
- największa dolna przeszkoda na telefonie ma ≈ 101px szerokości
- więc skok ma ją faktycznie przeskoczyć, nie przechodzić przez hitbox

TELEFON:
- pointerdown = natychmiastowy skok
- puszczenie palca nie ucina skoku
- większe odstępy między przeszkodami
- górne przeszkody pojawiają się dopiero później
- pion i poziom nadal działają

JavaScript: OK
