![chancho va](https://github.com/chanchooo-vaaa/chanchooo-vaaa/blob/master/img/chanchova.jpg?raw=true)

>Chancho va es un juego para diseñadores de tipografía aburridxs de la rutina y el trabajo solitario. Aquí los archivos circulan y lxs jugadorxs trabajan colaborativamente.

>El juego comienza cuando cada jugadxr es asignadx un archivo que contiene algunos glifos como pista. Entonces, simultáneamente, todxs deben dibujar algunos signos nuevos en los archivos recibidos, salvar, cerrar y pasar el archivo al siguiente jugadxr al grito de «¡chancho va!». A medida que avancen las rondas, los archivos irán completando su set de caracteres con el trabajo de todxs.

## Los requisitos para jugar son: 
Computadora, conexión a internet buena, acceso y conocimiento de herramientas de dibujo de tipografía y experiencia básica en uso de GitHub (`comit` `push` `pull`).


## Más detalles:

Hay 8-10 jugadores conectados y 8-10 archivos con un sistema tipográfico incompleto.  
A cada jugador se le asigna un primer archivo, por ejemplo, Jugador 1 > 1.UFO.   
El jugador lo abre y a partir de entonces tiene 5 minutos para diseñar y agregar hasta dos nuevos signos siguiendo la coherencia de los signos preexistentes.    
Pasado el tiempo, todos los jugadores salvan los archivos y los devuelven al repositorio.  Así finaliza el primer round.   
Para comenzar el segundo round, cada jugador descarga el archivo siguiente, por ejemplo, Jugador 1 > 2.UFO. Lo abre, suma sus signos, lo salva y vuelve a subirlo al repositorio.   
    
Los rounds se repiten hasta terminar los alfabetos o que hasta que finaliza el tiempo disponible. La dinámica de intercambio se realiza a través de un repositorio compartido en GitHub con archivos editables UFO, soportado en múltiples programas de edición.   


### Advertencia: 
Esto es un juego, no es un espacio de crítica de diseño.

### Cómo jugar

- Se presentan los participantes.   
- Cada participante es asignado un puesto [primero, segundo, tercero, etc.] que mantendrá durante todo el juego.    
- Cada participante realiza un `pull` del repositorio en git y toma de su repositorio local el archivo correspondiente a su puesto [1.UFO, 2.UFO, 3.UFO, etc.] e informa al moderador que está listo para comenzar.
- Cuando los moderadores verifican que todos poseen sus archivos correspondientes da inicio a la primera vuelta al gritar: *“¡Chancho va!”.*
- Cada vuelta durará *5 minutos* (el moderador avisará 1 minuto antes de finalizar) en el que cada participante deberá:    
-- *Agregar* nuevos glifos al archivo con el que está jugando (mínimo 1/ máximo 2).  
-- *Salvar* el archivo UFO.  
-- *Gritar “¡chancho!”* para indicar al moderador que está listo para subir su modificación al repositorio:    
    
1. `COMMIT`: escribir el siguiente _commit:_ "round x - nombre del participante".  
2. `PUSH`: hacer _push_ de los cambios.  
3. `PULL`: actualizo el repositorio según los cambios que los otros participantes hayan _pusheado_  
   
- Si algunos de los participantes completa sus glifos antes de los cinco minutos, grita *chancho va* y puede hacer `push` de sus cambios al repositorio.   
- En caso que algún participante no termine sus glifos, debe eliminar los dibujos inconclusos o `ignorar los cambios` en git.   
- Cuando todos los participantes hayan hecho `commit` `push` de sus archivos finaliza el primer round.   
- El segundo round comienza con cuando todos los particpantes hacen `pull` del repo y el moderador _reparte_ los archivos.    

#### Ejemplo:

![img](https://github.com/CaroGiovagnoli/chancho_va/raw/master/img/grafico.jpg?raw=true)

*Round 1:*
- Jugador 1 - `Archivo 1.UFO`. 
- Jugador 2 - `Archivo 2.UFO`. 
- Jugador 3 - `Archivo 3.UFO`. 


*Round 2:*
- Jugador 1 - `Archivo 3.UFO`. 
- Jugador 2 - `Archivo 1.UFO`. 
- Jugador 3 - `Archivo 2.UFO`. 


Luego de repartidos los archivos para el nuevo round, todo vuelve a empezar.   
`pull` `diseñar` `commit` `push` se repite hasta completar el set de caracteres o hasta que se termine el tiempo.

### Reglas de convivencia

- El link con el acceso al juego es individual e intransferible.
- Cualquier conducta ofensiva provocará que el jugador sea descalificado.
- Chancho va es un juego, no un espacio de crítica de diseño.
- Mantener la coherencia con el dibujo recibido en los nuevos glifos a diseñar.
- No realizar modificaciones en los glifos diseñados por otros participantes.
- Respetar el tiempo de cada ronda para dibujar y subir al repositorio.
- Sumar un mínimo de 1 (uno) y un máximo de 2 (dos) signos al archivo. De no terminar alguno, eliminar el dibujo incompleto.
- No realizar modificaciones en el original de cada archivo.
- No realizar modificaciones en el nombre o ubicación original de los archivos (Abrir > Modificar > Guardar > Cerrar).
- No ocuparse del espaciado en los archivos.
- Respetar el orden para intervenir según el puesto de cada participante (`pull` `commit` `push`). Cuando un participante grita “Chancho” y es autorizado por el moderador, es su momento de carga al repositorio y ningún otro participante puede superponerse.
- Respetar el formato del `commit`: “Round X - Nombre jugador”   


### Avisos legales

- Todo lo que se produzca en el taller no puede ser comercializado ni por los talleristas ni por los asistentes. Antes de iniciar el taller, los asistentes deben dejar sus datos y adherir a la licencia y forma de trabajo propuesta.
- Lo producido durante el taller se rige por la licencia SIL Open Font License (OFL): LINK


===

### HISTORIA PRELIMINAR DEL JUEGO: CHANCHO VA DE CUARENTENA

Durante la primera parte de la cuarentena armamos un grupo para motivarnos a dibujar letras que quizás en otro momentos no hubiésemos encontrado el tiempo.

Aplicamos la lógica de un juego de cartas/naipes popular en Argentina llamado “chancho va” y adaptamos las reglas, en vez de hacer circular cartas/naipes aquí circulaban archivos de Glyphs con el objetivo de dibujar alfabetos de manera colectiva.

Cada jugador recibía un archivo iniciado por otro participante, que contenía un par de signos y ninguna descripción o explicación. Mediante la observación de los elementos identitarios del sistema tipográfico incompleto recibido, se debían agregar nuevos signos manteniendo la coherencia y sin alterar lo ya hecho, para luego pasar el archivo al siguiente jugador. Así nos enfrentamos a desarrollar estilos o situaciones de diseño que individualmente no hubiéramos abordado nunca. 
A partir de esta premisa lúdica de carácter virtual fue que lo consideramos una propuesta interesante para compartir en el marco de TypeWknd.
