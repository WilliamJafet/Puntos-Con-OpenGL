# Puntos Secuenciales Con OpenGL

La práctica consiste en realizar lo siguiente:
Cuadricula. Pantalla completa, cada cuadro deberá medir 30 unidades por lado, como se muestra en el ejemplo. Deberá realizar la cuadricula UTILIZANDO SOLAMENTE PUNTOS, NO LINEAS, NO POLIGONOS, NO FIGURAS. El color de fondo y color de los puntos es libre.

![image](https://user-images.githubusercontent.com/72232712/145735819-3aa837f6-7b34-4c0d-b0fb-82759b41c39d.png)

Para ello primero se explica el código fuente del programa realizado.
En principio se realiza la importación de librerías necesarias para realizar la práctica.

![image](https://user-images.githubusercontent.com/72232712/145735830-7ffcd78b-9e7d-46f3-9bd8-004a329c00e2.png)

El siguiente bloque de código es la declaración de variables necesarias para realizar distintas acciones.

![image](https://user-images.githubusercontent.com/72232712/145735837-95e56da3-f14c-4d8d-a9cc-ee804a08fc28.png)

La función principal es importante debido a que es en esta parte donde empieza a ejecutarse el programa. En este bloque se realizan diversas configuraciones de la ventana para que se muestre al usuario.

![image](https://user-images.githubusercontent.com/72232712/145735840-02e78ed4-aced-4444-9af1-4ddc3b4a53c7.png)

La función init es parte de la librería OpenGL y se utiliza para inicializar los componentes del Canvas, este es un componente en el que se va a realizar el pintado del objeto.

![image](https://user-images.githubusercontent.com/72232712/145735852-d9347d73-b895-402c-b2a4-e8035bf1856a.png)

En la función reshape no se realiza ninguna acción por ahora.

![image](https://user-images.githubusercontent.com/72232712/145735858-6b66ab04-4dad-45a5-b7b1-84516a466749.png)

La función display es una de las funciones más importantes porque es aquí donde se programan las instrucciones para que el programa pinte lo que le estamos indicando.
En este caso primero asignamos un tamaño en pixeles, después con el método gl.glBegin(GL.GL_POINTS); indicamos que vamos a pintar puntos. Establecemos un color. En el centro de los for anidados le indicamos al programa que se pinten los puntos.

![image](https://user-images.githubusercontent.com/72232712/145735870-f5a101e7-605d-4b08-bc65-2949859abf09.png)

La última función por el momento no se realiza ninguna acción.

![image](https://user-images.githubusercontent.com/72232712/145735881-8450bdd5-4d1f-4a95-85d4-88493feca85f.png)

Ahora que se ha explicado el código fuente, la siguiente parte es mostrar el resultado.
Como resultado hemos obtenido lo que se muestra en la siguiente figura.

![image](https://user-images.githubusercontent.com/72232712/145735889-81ce6426-54c1-413f-9e33-88382ef454de.png)
