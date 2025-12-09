Link: https://seismic-sim-copy-9fd5eb64.base44.app/

Guía inicial
-

<img width="1078" height="865" alt="784fa4da-0a1d-47c5-a106-fe0ed0506584" src="https://github.com/user-attachments/assets/2beee289-6750-4289-a07a-35926cbbac44" />

<img width="1084" height="603" alt="unnamed" src="https://github.com/user-attachments/assets/e65d7000-5a71-4d32-b775-0678936dce91" />

El Panel de Control Principal
-

Esta es la pantalla "home" donde pasarás la mayor parte del tiempo. Su función es configurar y ejecutar el terremoto virtual.

- Tarjetas de Resumen (Arriba): Te dan un vistazo rápido del estado actual antes y después de la simulación.

- Edificios Analizados: Cuántos edificios están en la sesión.

- Puntos Críticos / Daño Estimado / Costo: Al inicio estarán en 0, pero se actualizarán en cuanto ejecutes la simulación.

Panel Izquierdo (Controles):
-

- Seleccionar Edificio: Un menú desplegable para elegir qué infraestructura vas a someter a prueba (ej. "Prueba"). Muestra un resumen rápido de sus características (Residencial, 5 pisos, Año 2000).

- Parámetros del Sismo: Aquí tú tienes el control. Puedes usar los deslizadores (sliders) para ajustar:

- Magnitud (Richter): La potencia del sismo (ej. 5.5).

- Profundidad (km): Qué tan profundo es el hipocentro.

- Duración (s): Cuánto tiempo dura el movimiento.

- PGA Estimado: Mientras mueves los sliders, este número azul cambia automáticamente. Es la "Aceleración Pico del Suelo"; indica qué tan fuerte se sentirá la sacudida en la base del edificio.

- Botón "Iniciar Simulación": El botón naranja que activa el cálculo matemático y visual.

- Panel Central (Visualización 3D): Un espacio oscuro reservado para mostrar el modelo 3D de tu edificio. Al simular, aquí verás cómo reacciona la estructura.

Mapa y Resultados de Análisis
- 

Esta vista parece estar debajo o conectada al panel principal y se enfoca en la geografía y los detalles técnicos del daño.

- Mapa de Zona Afectada: Un mapa interactivo (tipo Google Maps o Leaflet) que te muestra dónde está tu edificio en relación con el epicentro del sismo.

- Puntos Críticos: Un panel de alerta. Si la simulación detecta que una columna o viga falló, aparecerá listada aquí. En la imagen dice "No hay puntos críticos detectados" porque aún no se ha ejecutado la simulación.

- Análisis de Daños: Un área reservada para gráficos o reportes detallados post-simulación.

<img width="1319" height="474" alt="1d29425b-dbcf-45ad-bbb0-3a7b78492cde" src="https://github.com/user-attachments/assets/1f337dfe-7060-4c2c-a65c-ac87baa1d0d0" />

Escenarios Guardados
-

Esta pantalla funciona como una biblioteca de "Desastres Predefinidos". Es muy útil si no quieres configurar los parámetros manualmente cada vez.

- Tarjetas de Escenarios: Cada tarjeta representa un evento sísmico específico (ej. "Sismo Moderado CDMX" o "Sismo Profundo Oaxaca").

- Datos Fijos: Muestran la Magnitud, Profundidad y Epicentro ya configurados para replicar condiciones históricas o hipotéticas reales.

- Botón "Cargar Escenario": Al hacer clic aquí, la aplicación enviará estos datos exactos al Panel Principal, listos para ser simulados en cualquier edificio.

<img width="1345" height="389" alt="c61bd00e-51df-4c22-a306-966111b8613c" src="https://github.com/user-attachments/assets/bfebf309-749c-479b-a30c-9433a753f8e8" />

Gestión de Edificios
-

Esta sección es tu inventario de infraestructuras. Antes de simular, necesitas registrar qué vas a romper.

- Lista de Edificios: Ves tarjetas con la información de cada propiedad registrada (Nombre, tipo de uso, pisos, material, ubicación).

- Estado del Edificio: Nota la etiqueta azul que dice "Bueno". Esto indica la salud estructural actual antes de cualquier daño.

Botones de Acción:

- Nuevo Edificio: Te permite ingresar una nueva estructura al sistema.

- Editar / Borrar: Para corregir datos o eliminar edificios antiguos.

- Ir a Simulación: Un acceso directo que te lleva de vuelta al Panel Principal con este edificio ya seleccionado.

<img width="1374" height="658" alt="d91cc290-95e0-424b-8ab6-df10bc5ed47d" src="https://github.com/user-attachments/assets/a57bd97d-8246-4d30-b1b7-21438148909e" />

Historial de Simulaciones
-

Esta es tu bitácora o registro de auditoría.

- Lista Cronológica: Muestra todas las pruebas que has hecho, ordenadas por fecha y hora.

- Resultados Clave: De un vistazo puedes ver qué pasó en simulaciones pasadas sin tener que volver a correrlas:

- Magnitud y Profundidad usada.

- Daño Estimado (%): Por ejemplo, la segunda tarjeta muestra un 27.0% de daño, lo que indica un evento serio.

- Estado: "Completada" (verde) o "Pendiente" (gris).

<img width="1363" height="617" alt="cd25e2ce-1dc5-441b-a07d-2d3056ea8e4f" src="https://github.com/user-attachments/assets/9e76c27d-77bf-4c13-854c-837ff2a4e88f" />

Arquitectura
-

Muestra el enfoque técnico y las distintas tecnologías que usa.
