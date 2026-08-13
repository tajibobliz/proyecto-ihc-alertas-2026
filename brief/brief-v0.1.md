# Brief v0.1 — Proyecto propio

> Documento no definitivo. Es una fotografía inicial del reto que
> vamos a investigar, discutir y corregir.

## Problema
¿Qué dificultad queremos comprender?

Cuando Senamhi emite un aviso por vientos fuertes, la información
existe pero no produce acción. La alerta se difunde por el portal
web y redes sociales, en lenguaje técnico y referida a toda una
provincia. La persona no sabe si ese aviso la afecta a ella, cuánto
tiempo tiene, ni qué debe hacer en su casa. El resultado: daños
evitables como calaminas arrancadas y objetos sueltos proyectados.

La dificultad no es meteorológica, es de comunicación de riesgo.

## Usuario
¿Quién vive esa dificultad?

Usuario primario: responsable de un hogar con techo liviano
(calamina) en zona periurbana de Santa Cruz de la Sierra. Usa el
celular principalmente para WhatsApp y redes sociales, no consulta
portales meteorológicos y no tiene formación técnica.

Usuarios secundarios (fuera del alcance v1): viviendas de losa,
departamentos en altura, responsables de obras de construcción.

## Contexto
¿Dónde y cuándo ocurre?

En la vivienda, en las horas previas a un evento de viento fuerte
(temporada de surazos y vientos, con episodios severos registrados
en julio de 2026). El aviso oficial suele emitirse con varias horas
de anticipación. La persona está trabajando o fuera de casa cuando
se emite, y solo puede actuar al llegar. La ventana útil de acción
es corta y no está señalizada en ningún lado.

## Tarea
¿Qué intenta hacer el usuario?

Decidir y ejecutar, en el tiempo que le queda antes del evento, las
acciones de protección que corresponden a su vivienda, sin tener
conocimiento técnico ni saber interpretar km/h o colores de alerta.

## Idea inicial
¿Qué solución imaginamos por ahora?

Una aplicación móvil que recibe el dato de viento de una fuente
meteorológica, lo cruza con la ubicación y el perfil de vivienda del
usuario, y entrega una notificación con:
- si le afecta y desde qué hora
- cuánto tiempo le queda
- una lista corta de acciones concretas y verificables, con apoyo
  visual

Las acciones no se inventan: se derivan de las recomendaciones
oficiales de Senamhi y Defensa Civil, traducidas a lenguaje y
contexto del usuario.

## Alcance
¿Qué parte pequeña abordaremos primero?

- Un solo tipo de evento: viento fuerte
- Un solo perfil de usuario: hogar con techo de calamina
- Un solo flujo: recibir alerta → entender riesgo → ver y marcar
  acciones
- Fuera de v1: reporte de daños, mapa colaborativo, cuentas de
  usuario, otros eventos climáticos