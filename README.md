Trabajo extra ( Circuito mixto con ngspice )

1.Introducción

Vamos a Entender el comportamiento y las características de un circuito electrónico visto desde un software de simulación es algo  un poco complicado a primera vista, y más que ver sus resultados, el aprender a interactuar con el mismo se hace una tarea que resulta entretenida. Como una herramienta indispensable para la formación en temas de ingeniería, se ha convertido el uso de software de simulación, 
En temas de circuitos eléctricos el simulador NGSPICE es uno de los programas que incorpora características importantes para tener una interacción sencilla con el usuario.

2.Objetivo

Simular el siguiente circuito mixto compuesto de 4 resistencias, una fuente de voltaje, una fuente de corriente con el software NGSPICE.

3.Marco teórico

4.Explicación del procedimiento

4.1 Como primer paso para el usuario procederá a descargar el software gratuito NGSPICE desde su pagina oficial actualmente este software es multiplataforma es decir se puede usar tanto en Windows como en Ubuntu su instalación es similar en ambos sistemas operativos.
![Screenshot_20210915-211314_Drive](https://user-images.githubusercontent.com/86451564/133538184-ae0873b0-c8bd-492f-862a-f25ace6de24d.jpg)

4.2 Para empezar a simular un circuito deberá tener en cuenta ciertos detalles nada complicados como lo son tener descargado un bloc de notas el que mas sea de su agrado el cual le va a servir para que el usuario pueda describir al circuito, como segundo aspecto importante hay que guardar el archivo con la siguiente extensión “ cir “ por ej: circuito.cir esto es importante para que el software NGSPICE pueda ejecutarlo sin problemas.
![Screenshot_20210915-211453_Drive](https://user-images.githubusercontent.com/86451564/133538356-5e7042ae-1448-4d6f-8ffa-d1c9ac8ef19d.jpg)

4.3 Ahora veamos un poco la sintaxis que se utilizara en el bloc de notas para poder describir nuestro circuito para posterior poder ejecutarlo.
![Screenshot_20210915-211523_Drive](https://user-images.githubusercontent.com/86451564/133538381-90e71e72-4bcc-4862-813a-0a20d23f22bb.jpg)

4.4 Teniendo en cuenta la sintaxis y la forma correcta de guardar el archivo procedamos a resolver el siguiente circuito mixto que nos pide los siguiente averiguar la tensión en los nodos a,b,c. Y las corrientes que circulan por cada resistencia utilizando el software NGSPICE.
![Screenshot_20210915-211707_Drive](https://user-images.githubusercontent.com/86451564/133538494-7513a31c-84ba-4a8a-8692-bb34b2f70bbe.jpg)

4.5 Describamos el circuito mixto en el bloc de notas conforme a la sintaxis visto anteriormente.
![Screenshot_20210915-211813_Drive](https://user-images.githubusercontent.com/86451564/133538594-3379a0b7-d4a8-4215-822b-9f57843d8f4e.jpg)
Cualquier carácter descrito después de un (*) el software lo considera como una forma de comentar como se lo hace usualmente en algunos lenguajes de programación. Siempre se debe finalizar con el comando ( .END ).

4.6 Vamos a cargar el archivo del programa con el comando source.
![Screenshot_20210915-212039_Drive](https://user-images.githubusercontent.com/86451564/133539210-a8b36bc9-050c-49c1-8598-a15e0ce95a3f.jpg)
Podemos observar que el archivo se cargó correctamente.
![Screenshot_20210915-212601_Drive](https://user-images.githubusercontent.com/86451564/133539334-5d6565ab-cc4f-4c2b-8228-c1c1baee4e42.jpg)

4.7 Si el usuario desea ve lo que cargo al NGSPICE lo vamos hacer con el comando (listing).
![Screenshot_20210915-212732_Drive](https://user-images.githubusercontent.com/86451564/133539481-a1eee756-6db3-4d13-ac78-705e2447c9a9.jpg)

4.8 Para simular el circuito utilizamos el comando op.
![Screenshot_20210915-212851_Drive](https://user-images.githubusercontent.com/86451564/133539581-8e6850dc-a071-41de-b465-f6af6cd48561.jpg)

4.9 Para mirar todas las tensiones del circuito utilizamos el comando print all.
![Screenshot_20210915-213013_Drive](https://user-images.githubusercontent.com/86451564/133539706-9fe243e6-d43d-452e-8f86-618efbef7b3d.jpg)

4.10 Para mirar las corrientes de cada una de las resistencias usamos el comando show r.
![Screenshot_20210915-213109_Drive](https://user-images.githubusercontent.com/86451564/133539773-67c4da61-addd-476a-8fd4-1d4ac9c10823.jpg)

5.Análisis de los resultados

Utilizando el comando ( print all ) que nos da las tensiones en los nodos a,b,c  y utilizando el comando ( show r) nos muestra las corrientes que pasan por cada una de las resistencias veamos en las siguientes tablas los datos arojados por el programa.
![Screenshot_20210915-213227_Drive](https://user-images.githubusercontent.com/86451564/133539902-4ffc3895-69f9-4de8-8e4d-a2528e7201ab.jpg)

6.Video

Link del video

https://youtu.be/6ITWw8XEZ0g

7.Conclusion

El software NGSPICE muestra ser un software confiable y gratuito para diferentes sistemas operativos, ha sido muy práctico para la solución, simulación de circuitos, ya que este usa parámetros que se asemejan a la realidad de los elementos. Teniendo en cuenta que el simulador NGSPICE cuenta con un lenguaje propio de código para la descripción de circuitos, se concluye en esta actividad con el conocimiento suficiente el cual permite la correcta descripción del circuito en 
función de los nodos y los elementos que componen el mismo (resistencias, fuentes de voltaje y corriente.

6.BIBLIOGRAFÍA

http://ngspice.sourceforge.net/

http://ngspice.sourceforge.net/ngspice-tutorial.html

