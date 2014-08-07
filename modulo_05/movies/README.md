 Ejercicios del curso Python y Pruebas
=========================================================

M�dulo 05: Pruebas en Entornos Espec�ficos

Modificaci�n del ejemplo que hicimos en el m�dulo 3 y que se conecta a un servicio web para traer informaci�n de una pel�cula, siempre que dicha pel�cula no est� guardada en una cach�. Los cambios son:

1) A�adir una cach� que funciona con MongoDB adem�s de la cach� con SQLite3.

2) Nuevas pruebas que verifican el uso de la cach� con la librer�a MongoMock. Estas pruebas se pueden ejecutar sin un servidor de MongoDB.

3) Nuevas pruebas que interceptan la llamada a la API Rest para devolver un valor concreto. Adem�s, se usa MonkeyPatch para verificar que el c�digo de producci�n muestra la pel�cula correcta.





