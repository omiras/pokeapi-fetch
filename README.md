# La PokeAPI en acción

Implementa un selector de pokemon que, al escoger el nombre de un pokemon, se realice una llamada a la [PokeAPI](https://pokeapi.co/) y recupere el nombre y la ruta a una imagen del Pokemon.

Además, al hacer clic en el botón **Change to Shiny** se debe cargar la imagen "shiny" del pokemon. Utiliza la [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) para realizar la llamada,

## BONUS

- El selector de pokemons deberia **bloquearse** hasta que no hemos conseguido cargar el pokemon, y **desbloquearse** una vez cargado (mirar atributo __disabled__)
- Existe una bilbioteca para facilitar la comunicación con esta API.
Búscala en la documentación y úsala en vez de hacer las llamadas directamente a la API.