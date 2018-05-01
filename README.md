# Práctica de Desarrollo con Metodologías Ágiles

### Enunciado
Una empresa hotelera desea revolucionar el alquiler de habitaciones de hotel mediante la oferta de habitaciones por horas. Para ello, desea realizar una aplicación web para la gestión de la disponibilidad y de las reservas online de las habitaciones. Para alcanzar este objetivo, ha encomendado a los profesores de Metodologías de Desarrollo Web verificar el avance del proyecto e interactuar con los equipos de desarrollo de la ETSISI.

### Integrantes
* Joaquín Zamora - Product Owner
* Juan Jiménez - Scrum Master
* Jesús Zea - Team Member
* Rafael Falconí - Team Member
* Antonio Chain - Team Member
* Santiago Pérez - Team Member


#### [Máster en Ingeniería Web por la U.P.M.](http://miw.etsisi.upm.es)


Para arracancar la aplicacion debes ejecurar losgientes pasos

1 Asgurate que as inicaido mysql o XAMPP
2 Crea la base de datos o ejecuta los caomandos de doctrinte para crear la base desde las clases entity del proyecto
  Comprobar si la base de datos esta sincronizada con el mapeo  
  php bin/console doctrine:schema:validate
  php bin/console doctrine:schema:update --dump-sql --force
3 Ejecuta el comando composer update o composer install
4 Revisa los archivos ebn el proyect /web/js/busqueda.js,  /web/js/reserva.js  su rutas internas esten el puerto correcto.
5 Ejecuta el comando >php bin/console server:run para arrancar la app
6 En el navagador puedes probar los siegueinte links que pertenecen a la primer string.
    Información del producto entregado:
    •	URL de página inicial de reservación para clientes 
        o	http://localhost:8001/
    •	URL para confirmación de la reserva por parte del hotel
        o	http://localhost:8001/confirm?
    	Para confirmar la reserva el PIN del hotel es 1234
    •	URL para acceder al reporte de reservas confirmadas por parte la empresa Buking
        o	http://localhost:8001/admin/reservations
