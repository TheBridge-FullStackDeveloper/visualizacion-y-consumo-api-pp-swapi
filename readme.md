![logotipo de The Bridge](https://user-images.githubusercontent.com/27650532/77754601-e8365180-702b-11ea-8bed-5bc14a43f869.png "logotipo de The Bridge")

# :crossed_swords: SWAPI #

## Introducción ##

SWAPI es una API del mundo de La Guerra de las Galaxias, que ofrece una colección de recursos que se mueve entre personajes, planetas, vehículos y más.

Extraeremos datos de dicha API y los utilizaremos para dar forma a varias gráficas hechas con [Chartist]

![sw4]

## Requisitos ##
- Precurso web
- Programación avanzada
- Manejo de APIs
- [Chartist]

![sw1]

## Iteraciones ##

Tendrías que haber conseguido realizar la [plantilla HTML5 con linters] y tener tu base a utilizar durante la semana. Si no has terminado, te animo a que uses la [plantilla HTML5 con linters de TheBridge] y así poder seguir el ritmo diario.

Debes saber también que, cuando trabajamos con API Rest, como es el caso que tenemos entre manos, se ha de jugar mucho con la asincronía, pues los recursos que necesitamos pueden estar en 3 rutas distintas, y que para obtener la información de una ruta tengamos que llamar a las otras dos antes.

Existen varios recursos disponibles en la página de [SWAPI]:
- Root
- Films
- People:
- Planets
- Species
- Starships
- Vehicles

![sw2]

0. Agrega la bibliotecas [Chartist]

### Films ###

1. Usa una gráfica de líneas para relacionar cada película con su año de estreno.

### People ###

2. Usa una gráfica de barras para relacionar cada personaje con el número de películas en las que aparece.

### Planets ###

3. Crea una gráfica en la que se representen, en orden ascendente, los planetas según su diámetro.

### Species ###

4. Representa en un gráfico circular, el número de personajes que hay por cada especie.

### Starships ###

5. Agrupa las naves espaciales, según la calificación de hiperimpulsión, representada por la propiedad "hiperdrive_rating". Hazlo en una gráfica con forma de donut.

![sw3]

[SWAPI]: https://swapi.dev "SWAPI"
[Chartist]: https://gionkunz.github.io/chartist-js "Chartist"

[sw1]: sw1.gif "Star Wars image 1"
[sw2]: sw2.gif "Star Wars image 2"
[sw3]: sw3.gif "Star Wars image 3"
[sw4]: sw4.gif "Star Wars image 4"
