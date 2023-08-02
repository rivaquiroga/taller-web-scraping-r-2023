# Web scraping con R

En este módulo del [Diplomado en Ciencia de Datos UC](https://datascience.uc.cl/) aprenderemos a implementar la técnica de extracción de datos conocida como _web scraping_ usando el paquete {rvest}. Las sesiones serán en modalidad online, los días 5 y 12 de agosto. Este taller es un complemento del [taller de web scraping usando Python](https://github.com/rivaquiroga/taller-web-scraping-python-2023)  realizado en junio. Mostraremos cómo utilizar el paquete {rvest} para extraer texto y tablas, pero nos enfocaremos particularmente en cómo podemos crear nuestras propias funciones para automatizar la extracción de múltiples páginas de un sitio web y cómo limpiar los datos obtenidos. 

## Preparación

**Si no participaste en el taller de web scraping usando Python, es necesario que revises la grabación de la primera parte de la primera clase (10 de junio)**. En ella abordamos los aspectos generales del funcionamiento de un sitio web que es importante conocer para abordar una tarea de web scraping (y que son necesarios para entender lo que haremos en estas dos sesiones). 

Durante la sesión utilizaremos {rvest} y otros paquetes que son parte de lo que se conoce como [Tidyverse](https://www.tidyverse.org/), un conjunto de paquetes diseñados para el trabajo en ciencia de datos. Además, es necesario instalar {janitor}. Todos están disponibles en CRAN, por lo que puedes utilizar la función `install.packages()` para obtenerlos:

```
install.packages("tidyverse")
install.packages("janitor")
```

## Atajos de teclado útiles

Los siguientes atajos de teclado serán útiles al explorar las páginas web que _escrapearemos_.

| Acción | Windows / Linux | Mac |
|---|---|---|
| Abrir el panel de desarrollo | F12<br/>ctrl + shift + i | F12<br/>option + command +i |
| Abrir el panel de desarrollo con la opción de selección activada | ctrl + shift + c | option/ctrl + command + c |


## Actividades

### Sesión 1 (5 de agosto)

:page_facing_up: [Código en vivo]()


