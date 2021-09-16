Trabajo extra

1.Introducción

Vamos a Entender el comportamiento y las características de un circuito electrónico visto desde un software de simulación es algo  un poco complicado a primera vista, y más que ver sus resultados, el aprender a interactuar con el mismo se hace una tarea que resulta entretenida. Como una herramienta indispensable para la formación en temas de ingeniería, se ha convertido el uso de software de simulación, 
En temas de circuitos eléctricos el simulador NGSPICE es uno de los programas que incorpora características importantes para tener una interacción sencilla con el usuario.

2.Objetivo

Simular el siguiente circuito mixto compuesto de 4 resistencias, una fuente de voltaje, una fuente de corriente con el software NGSPICE.

3.Marco teórico


4.Explicación del procedimiento

1.1 Como primer paso para el usuario procederá a descargar el software gratuito NGSPICE desde su pagina oficial actualmente este software es multiplataforma es decir se puede usar tanto en Windows como en Ubuntu su instalación es similar en ambos sistemas operativos.

1.2 Para empezar a simular un circuito deberá tener en cuenta ciertos detalles nada complicados como lo son tener descargado un bloc de notas el que mas sea de su agrado el cual le va a servir para que el usuario pueda describir al circuito, como segundo aspecto importante hay que guardar el archivo con la siguiente extensión “ cir “ por ej: circuito.cir esto es importante para que el software NGSPICE pueda ejecutarlo sin problemas.

1.3 Ahora veamos un poco la sintaxis que se utilizara en el bloc de notas para poder describir nuestro circuito para posterior poder ejecutarlo.

1.4 Teniendo en cuenta la sintaxis y la forma correcta de guardar el archivo procedamos a resolver el siguiente circuito mixto que nos pide los siguiente averiguar la tensión en los nodos a,b,c. Y las corrientes que circulan por cada resistencia utilizando el software NGSPICE.

1.5 Describamos el circuito mixto en el bloc de notas conforme a la sintaxis visto anteriormente.

Cualquier carácter descrito después de un (*) el software lo considera como una forma de comentar como se lo hace usualmente en algunos lenguajes de programación. Siempre se debe finalizar con el comando ( .END ).

1.6 Vamos a cargar el archivo del programa con el comando source.
Podemos observar que el archivo se cargó correctamente.

1.7 Si el usuario desea ve lo que cargo al NGSPICE lo vamos hacer con el comando listing.

1.8 Para simular el circuito utilizamos el comando op.

1.9 Para mirar todas las tensiones del circuito utilizamos el comando print all.

1.10 Para mirar las corrientes de cada una de las resistencias usamos el comando show r.

5.Análisis de los resultados

Utilizando el comando ( print all ) que nos da las tensiones en los nodos a,b,c y utilizando el comando ( show r) nos muestra las corrientes que pasan por cada una de las resistencias veamos en las siguientes tablas los datos arojados por el programa.

6.Video

Link del video

7.Conclusion

El software NGSPICE muestra ser un software confiable y gratuito para diferentes sistemas operativos, ha sido muy práctico para la solución, simulación de circuitos, ya que este usa parámetros que se asemejan a la realidad de los elementos. Teniendo en cuenta que el simulador NGSPICE cuenta con un lenguaje propio de código para la descripción de circuitos, se concluye en esta actividad con el conocimiento suficiente el cual permite la correcta descripción del circuito en 
función de los nodos y los elementos que componen el mismo (resistencias, fuentes de voltaje y corriente.

6.BIBLIOGRAFÍA

http://ngspice.sourceforge.net/
http://ngspice.sourceforge.net/ngspice-tutorial.html

