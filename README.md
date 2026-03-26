🛵 Proyecto Urban Scooter

**Urban Scooter** es una aplicación móvil diseñada para simplificar el alquiler de scooters eléctricos durante varios días, ofreciendo un flujo completo de gestión de pedidos para repartidores y usuarios. La app permite aceptar, gestionar y completar pedidos de manera eficiente, garantizando notificaciones oportunas, control de atrasos y acceso a información detallada de cada pedido.  


🚀 Funcionalidades Principales

- **Inicio de sesión seguro**  
  - Primer acceso con validación de usuario y contraseña.  
  - Opción de “Olvidé la contraseña” con notificación de contacto.  
  - Capacidad de cerrar sesión y volver a la pantalla de login.  

- **Gestión de pedidos**  
  - Lista de pedidos no reclamados en la pestaña "Todos los pedidos".  
  - Pedidos aceptados por el repartidor en "Mis pedidos".  
  - Actualización de listas mediante gestos de deslizamiento o filtros por estación de metro.  

- **Tarjetas de pedido inteligentes**  
  - Versión corta: dirección, fecha de entrega y estación de metro.  
  - Versión completa: incluye nombre, apellido, teléfono, color del scooter y comentarios del cliente.  
  - Alternancia entre versiones con animaciones fluidas.  

- **Aceptar y completar pedidos**  
  - Confirmaciones mediante notificaciones emergentes.  
  - Control de pedidos ya aceptados o cancelados.  
  - Pedidos completados se ordenan según tiempo de entrega.  

- **Notificaciones push**  
  - Alertas cuando quedan 2 horas para completar un pedido.  
  - Acceso directo a la pestaña “Mis pedidos” desde la notificación.  

- **Control de pedidos atrasados**  
  - Pedidos pendientes resaltados en rojo y priorizados en la lista hasta ser completados.  

- **Manejo de falta de conexión**  
  - Mensajes emergentes de “Sin acceso a Internet” con cierre manual.  


🏆 Resultados y Logros

- Cobertura completa de UI, móvil y API.
- Identificación de múltiples bugs críticos.
- Aplicación rigurosa de técnicas de diseño de pruebas.
- Escenarios complejos cubiertos: pedidos atrasados, cancelaciones, conectividad offline.
- Documentación profesional de casos de prueba y validaciones de campos.



 🛠 Tecnologías y Herramientas de Testing

- **Lenguajes:** JavaScript, SQL, JSON  
- **Herramientas:** Postman, emuladores móviles, pruebas manuales UI  
- **Bases de Datos:** SQL relacional  
- **Metodologías:** Clases de equivalencia, valores límite, tablas de decisión, pruebas positivas/negativas, testing exploratorio y automatizado  



⚠️ Áreas de Mejora

- Profundizar en conceptos de caché y su impacto en testing.
- Diferenciar correctamente entre PUT y PATCH y conocer códigos HTTP comunes.
- Refuerzo en valores límite y rangos medios.
- Ampliar conocimiento sobre bases de datos NoSQL.
- Evaluar automatización estratégica, especialmente en la capa de API.



📊 Cobertura de Pruebas

| Sección          | Fortalezas                                                  | Bugs Críticos |
|-----------------|-------------------------------------------------------------|---------------|
| UI & Formulario  | Validación completa de campos, valores límite y clases de equivalencia | 0             |
| Mobile App       | Notificaciones, conectividad offline y diseño visual        | 4             |
| API              | Endpoints Courier y Orders con pruebas positivas y negativas | 13            |
| SQL & DB         | Consultas funcionales y joins correctos                     | 0             |



 📈 Experiencia del Usuario

La aplicación está diseñada para que los repartidores gestionen sus rutas y pedidos de manera rápida y visual. Las tarjetas de pedido muestran la información más relevante al instante, y las notificaciones garantizan que los plazos se cumplan. La interfaz vertical es intuitiva, con actualización de listas mediante deslizamiento y filtros por estaciones de metro, priorizando los pedidos atrasados para que se completen a tiempo.

✨ Conclusión

Este proyecto refleja un avance significativo en habilidades de testing profesional. La atención al detalle, cobertura exhaustiva y documentación clara muestran un enfoque avanzado y profesional en testing de software.
