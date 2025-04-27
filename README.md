# torneo-esports-uml
Diseño de una aplicación de gestión de torneos

DISEÑO DE UNA APLICACIÓN DE GESTIÓN Y CONSULTA DE TORNEOS DE ESPORTS
Aplicación de Torneos de eSports
Para la realización de esta actividad me he inspirado en el la página de torneos de Riot Games https://lolesports.com/es-ES/tournament/113470835034591734/overview.
Con la aplicación se podrá administrar y consultar la organización de un torneo de manera eficiente
# Actores y Casos de Uso
# ¿Quién va a utilizar la aplicación (actores)?
-	Sistema (alojamiento)
-	Usuario (consulta)
-	Administrador (gestión)
# ¿Qué acciones realizarán los actores (casos de uso)?
Sistema:
-	Interfaz de la aplicación
Administrador:
-	Registrar equipo
    o	Añadir jugadores
-	Buscar equipo
    o	Seleccionar equipo
	Editar equipo
-	Buscar jugador
    o	Seleccionar jugador
	Editar jugador
-	Crear torneo
    o	Tipo de torneo
    o	Añadir equipos
    o	Añadir fecha de inicio
    o	Generar partidos
    o	Añadir premios
-	Buscar torneo
    o	Editar torneo - - - - - <<exclude>>- - - - - - > Eliminar torneo
    o	Mostrar clasificación
    o	Seleccionar partido
	Estadísticas de partido
    o	Seleccionar equipo
	Estadísticas equipo
    o	Seleccionar jugador
	Estadísticas jugador
    o	Generar estadísticas
    o	Ver premios
Usuario:
-	Iniciar sesión
    o	Verificar Usuario
	Recuperar Contraseña
    o	Nuevo Usuario
-	Cerrar sesión
-	Buscar equipo
    o	Seleccionar equipo
-	Buscar torneo
    o	Mostrar clasificación
    o	Seleccionar partido
	Estadísticas de partido
    o	Seleccionar equipo
	Estadísticas equipo
    o	Seleccionar jugador
	Estadísticas jugador
    o	Estadísticas torneo
    o	Ver premios
# Identificación de clases y relaciones
Administrador y Usuario tienen una relación de dependencia con Sistema ya que si el Sistema cambia las otras entidades también cambian porque se ven directamente afectadas.
Usuario, por su parte, tiene una relación de asociación con Administrador, aunque Administrador tienes capacidades adicionales a las del Usuario, para que este pueda disponer de toda la información.
# Justificación del diseño
Según mi visión estamos desarrollando una aplicación para la gestión y consulta de torneos en la cual tiene que haber un administrador que se encargue de la gestión de todos los aspectos (organización, información, actualizaciones, etc), registro y actualización de equipos y jugadores, organización de los eventos y mantenimiento de estos, para ofrecer una información accesible a todos los usuarios de la aplicación que utilizarán la misma a modo informativo para poder seguir los progresos de sus equipos y jugadores favoritos en los diferentes torneos, por eso, el Administrador tiene capacidades superiores a los usuarios. 
# Conclusiones
UML parece un sistema estupendo para la organización de la estructura de la aplicación ya que tener la posibilidad de visualizar el concepto del uso de la aplicación, previo al desarrollo, permite identificar carencias, interacciones y funcionalidades que de otra manera habría podrían significar enormes pérdidas de tiempo y confusiones entre cliente y desarrollador. Ahora solo queda que alguien nos enseñe como hacer esto de la manera correcta o ver más vídeos en Youtube. 



