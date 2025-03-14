# Urban.Lunch - Pruebas de QA para Aplicación Móvil

## Descripción del Proyecto

Este proyecto de pruebas se llevó a cabo como parte del Sprint 5 del programa de formación en QA Engineer de TripleTen para evaluar la primera versión de la aplicación móvil **Urban.Lunch** en Android. La aplicación permite a los usuarios pedir comidas de diferentes restaurantes de la ciudad y recogerlas en puntos de entrega específicos. 



https://github.com/user-attachments/assets/5a1cac4e-c684-440d-b46c-52414dffa978



El objetivo de las pruebas fue garantizar el correcto funcionamiento de las principales características de la aplicación y detectar posibles errores antes de su lanzamiento.

## Funcionalidades Probadas

### 1. Selección del Punto de Recogida
- Verificación de la visualización de los puntos de recogida en el mapa.
- Validación de la selección y cancelación de un punto de recogida.
- Comprobación de la selección de un nuevo punto cuando otro ya está seleccionado.

### 2. Elección de Platillos
#### a) Lista de Platillos
- Comprobación de la correcta visualización de los platillos.
- Validación de la funcionalidad de los botones "+" y "-".
- Verificación de la navegación a la pantalla de detalles del platillo.
- Comprobación del progreso del pedido en el pie de página.

#### b) Detalles del Platillo
- Revisión de la presentación de la foto, descripción y composición.
- Validación del funcionamiento del botón "+".
- Verificación de la activación del botón "Siguiente".

### 3. Confirmación del Pedido
- Comprobación de la correcta visualización de la información del pedido.
- Validación del importe total y del tiempo estimado de entrega.
- Verificación de la funcionalidad del botón "Pedir".

### 4. Seguimiento de Pedido
- Validación de la correcta visualización del mapa, rutas y tiempos de entrega.
- Comprobación del temporizador de entrega.
- Verificación de la transición automática a la pantalla "El pedido ha sido enviado".

### 5. Manejo de Errores
- Verificación de la aparición de mensajes de error cuando:
  - No se permite el acceso a la geolocalización.
  - Se intenta hacer un pedido sin agregar platillos.

## Herramientas Utilizadas
- **Android Studio**: Emulador para pruebas.
- **Dispositivo Android**: Pruebas en un entorno real.
- **Jira**: Reporte y seguimiento de bugs.
- **Google Docs**: Documentación y reporte de pruebas.

## Resultados de Pruebas
- Se realizaron pruebas de funcionalidad y usabilidad.
- Se documentaron errores encontrados en **Jira**.
- Se generó un informe de pruebas con los resultados obtenidos.

Puedes consultar el informe de pruebas dando clic [aquí](https://docs.google.com/spreadsheets/d/1xZ1CvxFbwF-2wVRwoU40sA4NxzYimqdz/edit?usp=sharing&ouid=100155335199930450797&rtpof=true&sd=true).

## Conclusión
Este proyecto de pruebas ayudó a identificar errores y oportunidades de mejora en la primera versión de **Urban.Lunch** para Android. Los reportes de bugs y el informe de pruebas permitirán al equipo de desarrollo mejorar la calidad y experiencia del usuario en futuras versiones.

📌 **Autor:** Jorge Luis Pasten Peña
📅 **Sprint:** 5
🚀 **Estado:** Finalizado
