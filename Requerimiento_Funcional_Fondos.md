# Requerimiento funcional: Consulta y gestión de Fondos de Inversión (App Móvil)

## Objetivo
Permitir al usuario consultar, visualizar detalles y movimientos, y realizar operaciones básicas (adicionar, retirar) sobre sus productos de fondos de inversión desde la app móvil.

## Alcance
- Visualización de productos de fondos de inversión (FIC, FVP, FIC 360, etc.)
- Acceso a detalle y movimientos de cada fondo
- Acciones rápidas: adicionar y retirar fondos

## Descripción funcional

### 1. Pantalla principal "Mis productos"
- El usuario ve una lista de sus fondos de inversión disponibles.
- Cada producto muestra nombre, número, saldo disponible y un ícono identificador.
- Al pulsar sobre un producto, se accede a la vista de detalle de ese fondo.

### 2. Vista de detalle de fondo(FICs o FVP)
- Se muestra información relevante del fondo seleccionado: nombre, número, saldo total, saldo disponible, rentabilidad, oficina, etc.
- Hay dos pestañas: "Detalles" y "Movimientos".
    - **Detalles:** muestra información estática y de estado del fondo.
    - **Movimientos:** muestra una lista de transacciones recientes (aportes, retiros, rendimientos, etc.), ordenadas del más reciente al más antiguo.
- En la parte inferior, se presentan dos botones: "Adicionar" y "Retirar".
    - **Adicionar:** inicia el flujo para realizar un aporte al fondo.
    - **Retirar:** inicia el flujo para realizar un retiro del fondo.
- El usuario puede regresar a la pantalla principal desde la vista de detalle.

### 3. Navegación y experiencia
- El usuario puede alternar entre las pestañas de detalles y movimientos sin salir de la vista de detalle.
- El botón de regreso siempre lleva a la pantalla principal de productos.
- El flujo es consistente para todos los fondos (FIC, FVP, FIC 360, etc.), cambiando solo los datos específicos de cada producto.

### 4. Restricciones y reglas de negocio
- Solo se muestran los productos activos del usuario.
- Los movimientos deben estar ordenados del más reciente al más antiguo.
- Las acciones de adicionar y retirar deben validar los horarios y reglas de negocio definidos por la entidad.


## Consideraciones de usabilidad
- La navegación debe ser fluida, sin recargas innecesarias.
- Los textos y botones deben ser claros y accesibles.
- El diseño debe ser responsivo y adaptarse a diferentes tamaños de pantalla.

---

## Justificación

Este requerimiento busca que los usuarios tengan una integración entre sus productos de inversión en Fiducoomeva y los productos de Bancoomeva, permitiendo así tanto disponer del dinero invertido como invertir de forma ágil desde la app móvil. El objetivo es promover el uso de la Cuenta Ágil, producto ofrecido por Bancoomeva, y a su vez crear un puente para que los usuarios puedan acceder y utilizar el servicio de llaves bre-be, facilitando la gestión y movilidad de sus recursos financieros desde un solo lugar.
