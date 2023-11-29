# Semana 10 en Homerti de Fernando Gonzalez Serrano (FINAL)

- Día 1 (Lunes):
08:30am - 17:00pm.
Comida -> 30min

    Subida a producción del CMS Gestor de Traducciones al Ubuntu Server de Homerti, configurando el .env en producción y ajustando parámetros en el CMS, además de corregir el código de Intranet Vacalia para que apunte al CMS ya en producción (en vez de usar gestortraducciones.local virtualhost, pasamos a usar translator.homerti.com).

- Día 2 (Martes):
08:30am - 17:00pm.
Comida -> 30min

    Desarrollo del proyecto web Aura de Mallorca: implementación sistema de promociones con código antes de pagar (recompensa a las 5 reservas del usuario generando una promoción única para el usuario de un solo uso del 50% de descuento), y arreglo en db, backend y frontend.

- Día 3 (Miércoles):
08:30am - 17:00pm.
Comida -> 30min

    Seteando el .env en producción del CMS Translator (y migración de carpeta cms a translator en el proyecto propio local, no en prod), arreglando conflictos de merge con git con la librería GuzzleHttp, visto de hacer que desde el CMS las pages guarden el domain y cada que se cambie un literal, hacer una llamada al domain al /updates.php que estará ese mismo archivo en todos los proyectos con una api key unica para el gestor que cada proyecto la sabrá de antemano seteada manualmente en updates.php
    Desarrollo del proyecto web Aura de Mallorca:
    Reservas canceladas se pueden duplicar cambiando fechas y editar esa reserva como si fuera otra nueva con todos los datos y pago ya hecho, se puede ver el promo code del usuario de un solo uso en editar perfil, se checkea que no exista el dni tampoco en booking personal data y en registro bien se por qr o por normal, se inhabilita la cuenta si hay 2 o mas reservas canceladas de ese usuario, se puso traducciones en toda la web (faltaba en admin y user bookings, además de arreglos en algunos puntos de la web), arreglo del nav en modo móvil ya que no salía los links a user bookings y admin (solo salían en versión web).

- Día 4 (Jueves):
08:30am - 17:00pm.
Comida -> 30min

    Testeando Aura de Mallorca proyecto web.

- Día 5 (Viernes):
08:30am - 17:00pm.
Comida -> 30min

    Testeando Aura de Mallorca proyecto web.

**FIN**
.
