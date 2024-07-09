# TALLER-INDIVIDUAL-
![image](https://github.com/Marylin-Rosero/TALLER-INDIVIDUAL-MR/assets/169502533/a4114e8c-5ef3-420a-984f-ed8e1ea8a1ca)
![image](https://github.com/Marylin-Rosero/TALLER-INDIVIDUAL-MR/assets/169502533/509a1a3b-c301-4b99-ae2f-6d04349374ed)
![image](https://github.com/Marylin-Rosero/TALLER-INDIVIDUAL-MR/assets/169502533/5623b1d2-da63-4a81-ac5f-d4efd7a3cb74)
arte del código:

*Paquete e importaciones: Importa las clases necesarias de Java Swing y SQL.

Clase Interfaz Gráfica:

Atributos: conn para la conexión a la base de datos, frame para la ventana principal, comboBox para seleccionar el año de carrera, table para mostrar los datos en una tabla, y tableModel para manejar los datos de la tabla.

Constructor InterfazGrafica():

Establezca la conexión a la base de datos llamando al método connectDB().
Crea la interfaz gráfica llamando al método createGUI().
Método connectDB():

Establezca la conexión con PostgreSQL utilizando los parámetros de URL, usuario y contraseña especificados.
Método createGUI():

Crea y configura la ventana (JFrame) con un título y tamaño predefinido.
Crea un cuadro combinado (JComboBox) para seleccionar el año de carrera.
Crea una tabla (JTable) para mostrar los datos de los pilotos y carreras.
Centra el contenido de las celdas de la tabla.
Método populateComboBox():

Ejecuta una consulta SQL para obtener los años disponibles desde la base de datos y los agrega al combo box.
Método updateTable():

Actualiza la tabla de pilotos según el año seleccionado en el cuadro combinado.
Ejecuta una consulta SQL compleja que obtiene el nombre del piloto, victorias, puntos totales y posición en las carreras para el año seleccionado.
Organiza los datos obtenidos en vectores y actualiza el modelo de la tabla con estos datos.
Centra el contenido de las celdas de la tabla.
Método main():

Inicia las aplicaciones Swing en el hilo de despacho de eventos ( Event Dispatch Thread).
En resumen, este código crea una interfaz gráfica que permite seleccionar un año de carrera de Fórmula 1 y muestra información detallada sobre los pilotos, incluyendo sus victorias, puntos totales y posición en las carreras de ese año, todo gestionado desde una base de datos PostgreSQL.
