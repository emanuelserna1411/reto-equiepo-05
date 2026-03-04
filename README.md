1. Contexto del Problema: "El Caos en la Tienda de Mascotas"
   
Actualmente, el sistema de ventas de nuestra tienda está "atado". Una sola función se encarga de todo el proceso, lo que genera Baja Cohesión:
tenemos lógica de matemáticas mezclada con acceso a archivos y visualización de datos.

Si el dueño del negocio pide un cambio en los precios, o el equipo técnico decide cambiar la base de datos, tenemos que editar la misma clase una y otra vez, 
violando el principio SRP (Responsabilidad Única).

Siguiendo los estándares de High Cohesion, el equipo debe separar esta clase en partes independientes para que cada una solucione un problema concreto.
Instrucciones:
Crear una clase que solo haga cálculos (Lógica de negocio).
Crear una clase que solo guarde datos (Persistencia).
Crear una clase que solo gestione la comunicación/recibo (Notificación).
