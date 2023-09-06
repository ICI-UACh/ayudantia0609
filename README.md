# ayudantia0609  
## Complemento del ADN
![](https://static.nationalgeographicla.com/files/styles/image_3200/public/01-dna-nationalgeographic_2490526.webp?w=500&h=350)  

La secuencia de ADN es una molécula que contiene la información genética de los organismos vivos. Está formada por cuatro bases nitrogenadas (A, T, C y G) y tiene una estructura en forma de doble hélice en las que estas hélices forman puentes de hidrógeno con su complemento. Cada base nitrogenada tiene un respectivo complemento, a continuación el detalle:  
```
A -> T
C -> G
T -> A
G -> C
```
Cree un programa en python que calcule el complemento de una hebra de ADN.  

Ejemplo:  
```
ATCGAC
TAGCTG
```
## Equipo pokémon
![](https://www.dexerto.es/cdn-cgi/image/width=750,quality=75,format=auto/https://editors.dexerto.es/wp-content/uploads/sites/3/2022/07/16/mejores-iniciales-pokemon.jpg)  
El mundo Pokémon es un universo ficticio lleno de criaturas llamadas Pokémon. Los entrenadores capturan, entrenan y se enfrentan en emocionantes batallas con sus Pokémon. Cada Pokémon tiene habilidades únicas y pertenece a uno o más tipos (como agua, fuego, eléctrico, etc.)  

Cree un programa en Python que te permita formar tu propio equipo Pokémon. Inicia con un diccionario vacío y, dependiendo de las elecciones del usuario, permita agregar o eliminar Pokémon, así como consultar sus datos.
Aquí tienes un ejemplo del diccionario final que representa tu equipo Pokémon:
```
pokemon_diccionario = {
    "Bulbasaur": {"tipo": "Planta/Veneno", "nivel": 5},
    "Charmander": {"tipo": "Fuego", "nivel": 5},
    "Squirtle": {"tipo": "Agua", "nivel": 5},
    "Pikachu": {"tipo": "Eléctrico", "nivel": 5},
    "Jigglypuff": {"tipo": "Normal/Hada", "nivel": 5},
    "Geodude": {"tipo": "Roca/Tierra", "nivel": 5}
}
```

**Cada clave del diccionario representa el nombre de un Pokémon, y el valor asociado es otro diccionario que contiene información sobre el tipo y el nivel del Pokémon.**

Para lograr esto, implemente las siguientes funciones:
- agregar_pokemon(equipo): Pide el nombre de un pokemon, su tipo y su nivel y lo agrega al equipo. En esta función se debe verificar si el pokemon ya existe en el equipo, si existe, indicar error y no agregarlo. Recibe como parámtero "equipo" que corresponde al diccionario de pokemon.

- eliminar_pokemon(nombre_pokemon, equipo): Elimina el pokemon **nombre_pokemon** del equipo.

- stats_pokemon(nombre_pokemon, equipo): Consulta por los datos del pokemon **nombre_pokemon**.

- existe(pokemon, equipo): Retorna verdadero si el pokemon existe, falso de lo contrario.

- imprimir_pokemon(equipo): Imprime en pantalla los pokemon junto a su tipo y nivel.

  
El programa debe terminar cuando se seleccione la opción para hacerlo o hayan 6 pokémon en el equipo.
