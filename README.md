# Instrukcje szczegółowe:
Stwórz narzędzie, które dla dwóch podanych słów, z których pierwsze posiada artykuł
na Wikipedii, policzy odległość w sensie logicznym pomiędzy słowami wg następującej zasady:
- Odległość między słowami wynosi 1, jeśli drugie słowo występuje co najmniej raz na
stronie artykułu słowa pierwszego
- Odległość między słowami wynosi 2, jeśli drugie słowo występuje w jednym z artykułów
do których odnośniki znajdują się na stronie słowa pierwszego
- Jeśli słowo drugie występuje na stronie artykułu, do której odnośnik prowadzi przez więcej
niż jedną stronę artykułu pośredniego, to odległość między słowami jest zwiększana o 1 za
każdy jeden odnośnik prowadzący od artykułu słowa pierwszego do artykułu
zawierającego słowo drugie
