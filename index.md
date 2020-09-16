![chancho va](https://github.com/chanchooo-vaaa/info/blob/master/img/WhatsApp%20Image%202020-09-11%20at%2015.07.11.jpg?raw=true)

>Chancho va es un juego para diseñadores de tipografía aburridxs de la rutina y el trabajo solitario. Aquí los archivos circulan y lxs jugadorxs trabajan colaborativamente.

>El juego comienza cuando cada jugadxr es asignadx un archivo que contiene algunos glifos como pista. Entonces, simultáneamente, todxs deben dibujar algunos signos nuevos en los archivos recibidos, salvar, cerrar y pasar el archivo al siguiente jugadxr al grito de «¡chancho va!». A medida que avancen las rondas, los archivos irán completando su set de caracteres con el trabajo de todxs.

## Los requisitos para jugar son: 
- Computadora con software de dibujo de tipografía
- Nivel intermedio de dibujo de tipografía.
- Experiencia en el uso básico de GitHub (`pull` `comit` `push`).


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
- Cada participante realiza `pull` del repositorio en Git y toma de su repositorio local el archivo indicado por el moderador [1.UFO, 2.UFO, 3.UFO, etc.] e informa que está listo para comenzar.
- Cuando el moderador verifica que todos poseen sus archivos correspondientes da inicio al primer round al gritar: *“¡Chancho va!”.*
- Cada round durará *5 minutos* (el moderador avisará 1 minuto antes de finalizar) en el que cada participante deberá:    
-- *Agregar* nuevos glifos al archivo con el que está jugando (mínimo 1/ máximo 2).  
-- *Salvar* el archivo UFO.  
-- *Gritar “¡chancho!”* para indicar al moderador que está listo para subir su modificación al repositorio:    
    
1. `COMMIT`: escribir el siguiente _commit:_ "round x - Nombre del participante".  
2. `PUSH`: hacer _push_ de los cambios.  
3. `PULL`: hacer _pull_ para actualizar su repositorio con los cambios que los otros participantes hayan realizado.  
   
- Si algún participante completa sus glifos antes de los cinco minutos, grita *chancho va* y puede hacer `push` de sus cambios al repositorio.   
- En caso que algún participante no termine sus glifos, debe eliminar los dibujos inconclusos o `ignorar los cambios` en Git.   
- Cuando todos los participantes hayan hecho `commit` `push` de sus archivos finaliza el primer round.   
- El segundo round comienza con cuando todos los particpantes hacen `pull` del repositorio y el moderador _asigna_ los nuevos archivos.    

#### Ejemplo:


*Round 1:*
- Jugador 1 - `Archivo 1.ufo`. 
- Jugador 2 - `Archivo 2.ufo`. 
- Jugador 3 - `Archivo 3.ufo`. 


*Round 2:*
- Jugador 1 - `Archivo 3.ufo`. 
- Jugador 2 - `Archivo 1.ufo`. 
- Jugador 3 - `Archivo 2.ufo`. 


Luego de asignados los archivos para el nuevo round, todo vuelve a empezar.   
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

### Historia preliminar del juego: «Chancho va de cuarentena»

Durante la primera parte de la cuarentena armamos un grupo para motivarnos a dibujar letras que quizás en otro momentos no hubiésemos encontrado el tiempo.

Aplicamos la lógica de un juego de cartas/naipes popular en Argentina llamado “chancho va” y adaptamos las reglas, en vez de hacer circular cartas/naipes aquí circulaban archivos de Glyphs con el objetivo de dibujar alfabetos de manera colectiva.

Cada jugador recibía un archivo iniciado por otro participante, que contenía un par de signos y ninguna descripción o explicación. Mediante la observación de los elementos identitarios del sistema tipográfico incompleto recibido, se debían agregar nuevos signos manteniendo la coherencia y sin alterar lo ya hecho, para luego pasar el archivo al siguiente jugador. Así nos enfrentamos a desarrollar estilos o situaciones de diseño que individualmente no hubiéramos abordado nunca. 
A partir de esta premisa lúdica de carácter virtual fue que lo consideramos una propuesta interesante para compartir en el marco de TypeWknd.


===


<<<<<<< HEAD
### PORTUGÊS
## O jogo «Chancho va» 
=======

# PORTUGUÊS

## O JOGO/WS “CHANCHO VA” 
>>>>>>> cb9609faef2435db20a59ede58f9a44e7edc66f3

>*Chancho va* é um jogo para typeface designers entediados da rotina e de trabalhar sozinhos. Aqui, os arquivos vão circular e o jogadorxs devem trabalhar de forma colaborativa.

>O jogo começa quando a cada jogadxr é assignadx um arquivo que contém algumas letras como pista. Então, em simultâneo, todxs devem desenhar novas letras nos arquivos recebidos, salvar, fechar e passar o arquivo ao seguinte jogadxr e gritar «¡chancho va!». 
Na medida que avança as rodadas, os arquivos vão completando o seu set de caracteres com o trabalho de todxs.

<<<<<<< HEAD
## Os requisitos para jogar são: 

- Computador com software de desenho tipográfico.
- Nível intermediário de desenho tipográfico.
- Experiência no uso de GitHub (`pull` `comit` `push`).

## Mais detalhes: 
=======
### Os requisitos para jogar são: 
Computador conectado à internet, acesso e conhecimento das ferramentas de desenho de tipografia e experiência no uso de GitHub (`comit` `push` `pull`). 

### Isto seria mais ou menos assim: 
>>>>>>> cb9609faef2435db20a59ede58f9a44e7edc66f3
São 10 jogadores online e 10 arquivos com um sistema tipográfico incompleto.
A cada jogador se lhe assigna um arquivo, por exemplo, Jogador 1 > Chancho1.ufo. O jogador abre e a partir de então tem 5 minutos para desenhar e agregar até dois novos glifos seguindo a coerência dos letras preexistentes. 
Passado o tempo, todos os jogadores salvam os arquivos e atualizam a pasta.  Assim termina o primeiro round.
Para começar o segundo round, cada jogador baixa o arquivo seguinte, por exemplo, Jogador 1 > Chancho2.ufo. Abre, adiciona seus glifos, salva e volta a fazer o upload da pasta.

Os rounds se repetem até acabar os alfabetos ou que termine o tempo.

A dinâmica do intercâmbio se realiza através de uma pasta compartilhada em GitHub com arquivos editáveis (UFOs) e compatíveis com vários programas de edição.


### Advertência

Alerta: Isto é um jogo, não é um espaço para críticas de desenho.


### Como jogar

- Se apresentam todos os participantes.
- A cada participante lhe é designado um posto [1, 2, 3… 20 ] que permanecerá durante todo o jogo. 
Cada participante deve realizar uma ação de PULL e tomar da sua pasta local o arquivo correspondente a seu posto [Ufo1, Ufo2, Ufo3… Ufo20] e informar ao moderador que já está pronto para começar.
- Quando os moderadores verificarem que todos já possuem seus arquivos correspondentes se dá início à primeira rodada com grito de: “¡Chancho va!”.
- Cada volta dura no máximo 5 minutos, e cada participante deverá: 
-- *Agregar* novos glifos ao arquivo com o qual está jogando (mínimo 1/ máximo 2).
-- *Exportar* um arquivo UFO que reemplazará ao original ao guardar no mesmo lugar (pasta local do repositório) e com o mesmo nome.
-- *Grita “¡chancho!”* para indicar ao moderador que está pronto para carregar sua modificação no repositório
- Logo de receber a autorização do moderador, o participante deverá realizar o upload da pasta seguindo a sequência:

1. `COMMIT`: escrever o seguinte _commit:_ "round x - nome do jogador".  
2. `PUSH`: Fazer _push_ das alterações.  
3. `PULL`: atualizo a pasta do repositório com as alterações que outros jogadores tenham _pusheado_  


- No caso que algum participante não chegue a terminar uma vez transcorridos os 5 minutos, poderão realizar o upload –prévia autorização do moderador– segundo a ordem do seus postos.
- No caso que algum participante fique com 1 ou 2 glifos sem terminar, deverá eliminar o desenho incompleto para não confundir ao seguinte participante debe ou `ignorar alterações no GitHub`.

- Quando todos os participantes tenham feito o upload de seus arquivos finaliza o primeiro round.

- O segundo round começa quando todos os participante fazem `PULL` do repositório e o moderador distribui os arquivos. 



*Round 1:*
- Jugador 1 - `Arquivo 1.ufo`. 
- Jugador 2 - `Arquivo 2.ufo`. 
- Jugador 3 - `Arquivo 3.ufo`. 


*Round 2:*
- Jogador 1 - `Arquivo 3.ufo`. 
- Jogador 2 - `Arquivo 1.ufo`. 
- Jogador 3 - `Arquivo 2.ufo`. 

Depois de designados os arquivos para o novo round, tudo volta do zero. 
`pull` `desenhar` `commit` `push` se repete até completar todo o alfabeto ou terminar o tempo.


### Regras de convivência

- O link com acesso ao jogo é individual e intransferível.
- Qualquer conduta ofensiva provocará que o jogador seja desqualificado.
- Chancho va é um jogo, não é um espaço para críticas de desenho.
- Manter a consistência com o desenho recebido nos novos glifos a desenhar.
- Não realizar modificações nos glifos desenhados por outros participantes.
- Respeitar o tempo de cada ROUND para desenhar e fazer o upload da pasta.
- Adiciona no mínimo 1 (uma) e no máximo de 2 (duas) letras ao arquivo. Se não terminar alguma, eliminar o desenho incompleto.
- Não realizar modificações no original de cada arquivo.
- Não realizar modificações no nome ou lugar de origem dos arquivos (Abrir > Modificar > Salvar > Fechar).
- Não preocuparse com o espaçamento dos arquivos.
<<<<<<< HEAD
- Respeitar a ordem para intervenir segundo o posto de cada participante (PULL - COMMIT - PUSH). Quando um participante grita “Chancho” e  é autorizado pelo moderador, é seu momento de carga ao repositório e nenhum outro participante pode sobreponerse.
- Respeitar o formato do commit 
=======
- Respeitar a ordem para intervenir segundo o posto de cada participante (`PULL``COMMIT``PUSH`). Quando um participante grita “Chancho” e  é autorizado pelo moderador, é seu momento de carga ao repositório e nenhum outro participante pode sobreponerse.

- Respeitar o formato do `commit` 
>>>>>>> cb9609faef2435db20a59ede58f9a44e7edc66f3
“Round X - Nome do jogador”
- Os programas com os quais se podem jogar são Robofont, FontForge, Glyphs e Fontlab 6.


### Avisos legales

- Tudo que se desenhe no Jogo não pode ser comercializado nem pelos realizadores nem pelos participantes. Antes de iniciar o jogo, os participantes devem deixar seus dados e aderir a licença e forma de trabalho proposta.
- Tudo que for produzido durante o jogo se rige pela licença SIL Open Font License (OFL): LINK

===

### História preliminar do jogo: “Chancho va de quarentena"

Durante a primeira parte da Quarentena, armamos um grupo que nos motive a desenhar letras, que talvez em outro momentos não tínhamos encontrado o tempo.

Aplicamos a lógica de um juego de cartas/naipes popular na Argentina chamado “chancho va” e adaptamos as regras, em vez de fazer circular cartas/naipes aqui circulavam arquivos de Glyphs com o objetivo de desenhar alfabetos de maneira coletiva.

Cada jogador recebeu um arquivo feito por outro, que tinha algumas letras e nenhuma descrição ou explicação. Ao observar os elementos do sistema tipográfico incompleto recebido, se adicionava novas letras mantendo a coerência e sem alterar o que já estava feito, para logo passar o arquivo ao próximo jogador. Assim nos enfrentamos com estilos ou situações de desenho que individualmente nunca não teríamos abordado. 
A partir dessa premissa lúdica e virtual foi que consideramos interessante compartilhar essa proposta dentro do TypeWknd.





