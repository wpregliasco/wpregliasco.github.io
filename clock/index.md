# Clock
>Para la dama y el caballero.
Con minutero y con segundero....

Esta es una página web programada en html (javascript) llamada `clock.html`.
Puede bajarse/abrirse desde [este link](clock.html).
El propósito es hacer una cuenta regresiva para que vea un conferencista y vea cuánto tiempo le queda. Copié la idea de las charlas TED.

Si se coloca el navegador en pantalla completa queda bastante coqueto. No entendí todavía cómo hacer la pantalla completa en dispositivos android, pero igual funciona razonablemente.

Se puede usar desde los links que hay a continuación o bajarla al propio dispositivo y correrla localmente.

Siéntanse libre de usarlo, modificarlo, maltratarlo o comentarlo.

## Funcionamiento

Se carga la página y aparece un reloj digital, en minutos y segundos, para hacer una cuenta regresiva. 

El reloj aparece detenido. Cuando está detenido, los números son de un amarillo vivo. Puede detenerse la cuenta o continuarla presionando cualquier tecla o con un click de mouse. En un android basta tocar la pantalla. 

El reloj decrece hasta estar en cero, donde se queda titilando. Puede detenerse en cualquier momento. Con un click más vuelve a la cuenta inicial, detenido y listo para recomenzar.

Con los valores por defecto, comienza la cuenta con números claros pero cuando quedan 20 minutos los números toman un tono rojizo, y cuando quedan 5 minutos los números cambian de color cada segundo entre rojo y violeta.

## Valores de tiempo

Hay tres valores de tiempo que se pueden programar, que son:
* `min`: tiempo total de la cuenta, en minutos (default:45)
* `mid`: tiempo de cambio de color, en minutos (default:20)
* `end`: tiempo de parpadeo final, en minutos (default:5)

Estos valores y los colores pueden cambiarse de varias maneras:
1. editando el archivo, 
2. especificándolo en la URL. A modo de ejemplo:
```url
http://clock.html?min=15&mid=5&end=1
```
Puede omitirse cualquiera de los parámetros y elegirá el valor default.  

3. Usando los siguientes links:

| link   | min | mid | end |
|---|---:|---:|---:|
| [1 hora](clock.html?min=60&mid=30&end=10) | 60  | 30 | 10|
| [45 min](clock.html?min=45&mid=20&end=5)  | 45  | 20 | 5 |
| [30 min](clock.html?min=30&mid=15&end=3)  | 30  | 15 | 3 |
| [15 min](clock.html?min=15&mid=06&end=2)  | 15  | 6  | 2 |
| [10 min](clock.html?min=10&mid=5&end=1)   | 10  | 5  | 1 |

## Contacto

Por mejoras hechas o sugeridas, agradecimientos e improperios, escribime a mi [correo electrónico](mailto:willy.pregliasco@gmail.com). Espero que este asunto sirva para conferencistas y organizadores. 

> Flor de relós !
