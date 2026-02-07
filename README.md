# SpeedFast5 – Programación Concurrente

## Descripción
Proyecto desarrollado para la actividad **“Sincronizando procesos en sistemas concurrentes” (Semana 5)**.  
Simula un sistema de entregas donde múltiples repartidores trabajan en paralelo accediendo a una zona de carga compartida, utilizando mecanismos de sincronización en Java.

## Funcionamiento
- Los pedidos se almacenan en una zona de carga común.
- Cada repartidor retira un pedido de forma segura.
- El pedido cambia de estado: PENDIENTE → EN_REPARTO → ENTREGADO.
- Cada pedido es atendido por un único repartidor.

## Estructura
SpeedFastSemana5/
└── src/speedfast/
├── EstadoPedido.java
├── Pedido.java
├── ZonaDeCarga.java
├── Repartidor.java
└── Main.java

## Ejecución en IntelliJ IDEA

1. Abrir IntelliJ IDEA y seleccionar **Open**.
2. Cargar la carpeta `SpeedFastSemana5` como proyecto.
3. Verificar que el SDK de Java esté configurado (JDK 8 o superior).
4. Navegar a `src/speedfast/Main.java`.
5. Hacer clic derecho sobre la clase `Main` y seleccionar **Run 'Main'**.
6. Observar la ejecución en la consola, donde se muestra el retiro y entrega de pedidos por los repartidores.

Al finalizar, se despliega el mensaje:
