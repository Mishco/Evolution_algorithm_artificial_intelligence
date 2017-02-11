# UI evolution algorithm

Machine learning - evolution algorithm (Zen garden) http://www2.fiit.stuba.sk/~kapustik/zen.html

Zenová záhradka je plocha vysypaná hrubším pieskom (drobnými kamienkami). 
Obsahuje však aj nepohyblivé väčšie objekty, ako napríklad kamene, sochy, konštrukcie, 
samorasty. Mních má upraviť piesok v záhradke pomocou hrablí tak, že vzniknú pásy. 

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
