Programa que recibe texto por el bluetooth integrado del ESP32 y lo escribe en un LCD 16x2 (con módulo I2C)

Esta versión soluciona algunas de las limitaciones de la versión básica:

* Cada texto nuevo enviado borra el texto anterior
* Si la longitud del texto es mayor a 16 caracteres (1 fila) muestra el resto del texto en la 2a fila
* Si la longitud del texto es mayor a 32 caracteres (2 filas) no muestra más caracteres
