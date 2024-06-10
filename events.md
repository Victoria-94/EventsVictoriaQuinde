1. Obtener la edad promedio de los miembros:
SENTENCIA: SELECT AVG(age) AS edad_promedio FROM members;
CAPTURA 
![cap1](/captura/cap1.png)


2. Obtener la edad mínima de los miembros:
SENTENCIA: SELECT MIN(age) AS edad_minima FROM members;
CAPTURA 
![cap1](/captura/cap2.png)


3. Obtener el número total de registros asistidos:
SENTENCIA: SELECT COUNT(*) AS total_registros FROM members;
CAPTURA 
![cap1](/captura/cap3.png)


4. Obtener el número total de asistentes a todas las conferencias
SENTENCIA: SELECT SUM(total_attendees) AS total_asistentes FROM conference;
CAPTURA 
![cap1](/captura/cap4.png)


5. Obtener el número total de eventos por cada ciudad:
SENTENCIA: SELECT city, COUNT(*) AS eventoCiudad FROM event GROUP BY city;
CAPTURA 
![cap1](/captura/cap5.png)


6. Obtener el número de registros por cada miembro:
SENTENCIA SELECT members_id, COUNT(*) AS total_registros FROM register GROUP BY members_id;
CAPTURA 
![cap1](/captura/cap6.png)



7. Obtener el número de registros por cada conferencia:
SENTENCIA SELECT conference_id, COUNT(*) AS total_registros FROM register GROUP BY conference_id;
CAPTURA 
![cap1](/captura/cap7.png)

