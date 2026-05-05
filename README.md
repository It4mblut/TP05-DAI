Parte 1
Fuimos deduciendo la estructura al ver la presentacion disponible en el campus ("HTTP ¿Qué es?") y al leer la documentacion de la API
(Aclaración: Siempre se usa el método GET)

Pokemon por nombre: URL: https://pokeapi.co/api/v2/pokemon/charmander, Devuelve un JSON con datos del Pokémon (id, name, sprites, types, stats). (Status: 200, es decir, solicitud realizada correctamente)

Pokemon por ID URL: https://pokeapi.co/api/v2/pokemon/6, Devuelve el mismo JSON, pero buscando por ID. (Status: 200, es decir, solicitud realizada correctamente)

Lista limitada: URL: https://pokeapi.co/api/v2/pokemon?limit=15&offset=3, Devuelve una lista de Pokemon limitada en base a los parametros dados. (Status: 200, es decir, solicitud realizada correctamente)

Tipo específico: URL: https://pokeapi.co/api/v2/type/water, Devuelve datos del tipo Water y sus Pokemon. (Status: 200, es decir, solicitud realizada correctamente)

Error intencional: URL: https://pokeapi.co/api/v2/pokemon/pokemonInexistente, Devuelve error porque el recurso no existe (Status: 404, es decir, error).
