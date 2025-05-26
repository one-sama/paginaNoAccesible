## Prompt de accesibilidad

Para el desarrollo de esta tarea se utilizaron tres IAs.

En primer lugar se creo una pagina con errores de accessibilidad: https://one-sama.github.io/paginaNoAccesible/paginaPrincipal.html

![Captura de pantalla (575)](https://github.com/user-attachments/assets/b9c71190-1036-4d1d-bed0-ca4801dd5e50)

Como se puede ver en la captura hay siete errores, algunos de constrante otros por la colocacion de las etiquetas <h1>, <h2> y <h3>.

###Copilot

Para comenzar empece utilizando la IA Copilot, el prompt utilizado para la tarea fue este:

![Captura de pantalla (563,05)](https://github.com/user-attachments/assets/b1132d4e-6f93-4788-a0cd-2dd4f71be10f)

Este prompt se diferencia del resto en el echo de los archivos que procesa, debido a que con copilot es más facil y sencillo darle contexto con los archivos a modificar, esa es la unica diferencia que hay con los prompts que se veran más adelante, pero el prompt como tal es ese.

![Captura de pantalla (576)](https://github.com/user-attachments/assets/b90c26d5-7645-4b1b-b8b7-4fab2835c219)

Este es el resultado, lo unico resaltable son sus seis alertas, pero a solucionado todos los errores, incluso de css. Hay que aclarar que en un principio hice el proceso mal, modifico el html por un lado y despues le pedi que modificase el css debido a un error mio, cuando modifique el prompt me hizo la misma pagina que ya me habia echo, pero de una sola vez, no se si fue por la memoria u otra cosa ya que esos resultados los elimine. Pero me dio el resultado con ese prompt a pesar de su brevedad.

###Chatgpt

La segunda IA que probe fue Chatgpt, con esta si hubo algunas complicaciones, el prompt fue este:

![Captura de pantalla (579)](https://github.com/user-attachments/assets/b94a8ae5-be53-4da3-ba28-dda540d86acf)

La unica diferencia con el prompt de Copilot fue que le tuve que pasar el html y css de manera manual, esa es la unica diferencia con respecto a Copilot ya que el prompt sigue siendo el mismo.

Probe el prompt con el modelo estandar ###4o, pero no me dio un buen resultado, asi que probe con el modelo o4-mini ya que es el que se recomienda para programar, tambien active el modo para que buscase en internet, debido a que su base de datos en el modo gratuito no esta actualizada y los estandares de accesibilidad podrian haber cambiado en 2 años.

![Captura de pantalla (577)](https://github.com/user-attachments/assets/a0a0753d-bb68-4c01-b738-2357fcb86409)

Este es el resultado al pasarlo por la herramienta Wave, es el mejor resultado que me a dado una IA.

###Gemini

La ultima IA por la que pase el prompt fue Gemini, los problemas que me dio fueron faciles que solucionar.

![Captura de pantalla (580)](https://github.com/user-attachments/assets/ee9a85cc-4e6a-4645-a607-6d7ac46084de)

Como se ve en la captura la unica diferencia es que meti los archivos de manera manual como en Chatgpt, de echo es el mismo, pero la base del prompt sigue siendo la de Copilot.

El unico problema que tuve fue que no capto el prompt a la primera, ya que entendio que el css no habia que arreglarlo sino comentar los errores de este, en este caso si tengo capturas:

![Captura de pantalla (566)](https://github.com/user-attachments/assets/b01961e6-7982-4c97-a466-9ce4f78d27ac)

Esta captura pertenece al css que me dio de primeras.

![Captura de pantalla (567)](https://github.com/user-attachments/assets/4a637000-b231-43da-8e22-a1ed558b1a54)

Y esta es la captura de lo que me entrego en el segundo intento tras recargar la respuesta.

![Captura de pantalla (578)](https://github.com/user-attachments/assets/fb1ead70-4b1f-4e6a-beb0-7e178392add9)

Tras pasarlo por Wave esos son los resultados, a pesar de que soluciono bastantes errores, fue el peor resultado que una IA me dio.

## Conclusion

Las IAs son una buena herramienta, te pueden sacar de apuros si sabes como manejarlas, pero no son perfectas y no todas se especializan para lo que uno puede estar buscando. Son un gran limitante para el desarrollo y estetica de las paginas, si solo copias y pegas el resultado. En mi opinion, a pesar de ser la que peores resultados dio, me parece muy bonita la interfaz que propuso Gemini. Eso y que Chatgpt dominara el mundo

## Para más informacion

https://github.com/one-sama/paginaNoAccesible

Hay esta el repositorio

## Las paginas respectivamente

### Copilot

https://one-sama.github.io/paginaAccesibleCopilot/htmlNuevoCopilot.html

### Chatgpt

https://one-sama.github.io/paginaAccesibleChatgpt/htmlNuevoChatgpt.html

### Gemini

https://one-sama.github.io/paginaAccesibleGemini/htmlNuevoGemini.html
