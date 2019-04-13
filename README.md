# Evolution algorithm 

Evolution algorithm artificial intelligence (Zen garden) http://www2.fiit.stuba.sk/~kapustik/zen.html

## Problem and solution

Zen garden is the surface spilled by thicker sand (small stones). However, it also contains immovable larger objects, such as stones, statues, structures, self-pastures. The monk must adjust the sand in the garden using the rakes to form belts in the image:

![alt tag](http://www2.fiit.stuba.sk/~kapustik/zen-s.png)

Belts can only be horizontally or vertically, never diagonally. It always starts at the edge garden and pulls a straight belt to the other edge or after an obstacle. On the edge outside the garden, he can walk as he wants. However, if it comes to an obstacle stone or sandblasted sand he must turn if he has a place. If both the left and the right have a free route, there is one thing to turn around. If it has only one free direction, it rotates there. If there is nowhere to go, the game is over. The successful game is
the one in which monks can bury the entire garden according to the rules, a maximum
possible number of fields. The output is to cover the garden with the monk's pass.

Use the evolutionary algorithm to solve this problem. The maximum number of genes
must not exceed half the perimeter of the garden plus the number of stones, in our example according to first picture 12 + 10 + 6 = 28. Suitability is determined by the number of coded fields. The output is a matrix showing ways of a monk. At least the program needs to run the garden the first image, but the input can be basically any map.

## Slovak version

Zenová záhradka je plocha vysypaná hrubším pieskom (drobnými kamienkami). 
Obsahuje však aj nepohyblivé väčšie objekty, ako napríklad kamene, sochy, konštrukcie, 
samorasty. Mních má upraviť piesok v záhradke pomocou hrablí tak, že vzniknú pásy na obr:

![alt tag](http://www2.fiit.stuba.sk/~kapustik/zen-s.png)

Pásy môžu ísť len vodorovne alebo zvislo, nikdy nie šikmo. Začína vždy na okraji 
záhradky a ťahá rovný pás až po druhý okraj alebo po prekážku. Na okraji - mimo záhradky 
môže chodiť ako chce. Ak však príde k prekážke - kameňu alebo už pohrabanému piesku - 
musí sa otočiť, ak má kam. Ak má voľné smery vľavo aj vpravo, je jeho vec, kam sa otočí. Ak 
má voľný len jeden smer, otočí sa tam. Ak sa nemá kam otočiť, je koniec hry. Úspešná hra je 
taká, v ktorej mních dokáže za daných pravidiel pohrabať celú záhradu, prípade maximálny 
možný počet políčok. Výstupom je pokrytie danej záhrady prechodmi mnícha. 

Uvedenú úlohu riešte pomocou evolučného algoritmu. Maximálny počet génov 
nesmie presiahnuť polovicu obvodu záhrady plus počet kameňov, v našom príklade podľa 
prvého obrázku 12+10+6=28. Fitnes je určená počtom pohrabaných políčok. Výstupom je 
matica, znázorňujúca cesty mnícha. Je potrebné, aby program zvládal aspoň záhradku podľa 
prvého obrázku, ale vstupom môže byť v princípe ľubovoľná mapa. 
