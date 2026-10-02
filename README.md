# Tabla de simbolos

Ejemplo de la clase de compiladores con lexer en Flex y parser en Bison.

Lo que agregue fue la multiplicacion y la division. Ya se podia sumar y restar, ahora tambien se puede usar * y / con numeros int y float. La multiplicacion y la division se hacen primero que la suma y la resta, por ejemplo 2 + 3 * 4 da 14. Si se divide entre cero el programa muestra un error en vez de caerse.

Para compilar:

make

Para correrlo con el archivo de prueba:

./compiler source.txt

Si se le pone -d antes del archivo tambien muestra el arbol y la tabla de simbolos.

En source.txt deje unas pruebas con multiplicacion y division para ver que funcione.
