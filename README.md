# fullstack-challenge

El objetivo del challenge es hacer un tablero kanban con sólo 3 columnas (buffer, working y done). con las siguientes características:
1. Se debe poder agregar tarjetas. Las tarjetas tendrán nombre y una fecha de entrega.
2. Al lado derecho de los textos de las columnas buffer, working y done, debe aparecer la cantidad de tarjetas de la columna.
3. Al mover la tarjeta a done. Debe aparecer un popup que diga "Felicitaciones por lograrlo!"
4. Si la fecha de entrega es menor a la fecha de hoy, las letras del card se pintarán de rojo.


## Especificaciones técnicas para el proyecto:
- El proyecto base debe ser laravel framework en su versión 6
- El frontend será un SPA dentro de laravel con componentes Vue
- Los estados del frontend serán manejados por vuex
- Antes de ingresar al kanban debe existir un login, de otra forma no se puede acceder al tablero
- 

## Recomendaciones
- Se recomienda el uso del paquete sanctum de laravel para la autenticación del usuario
