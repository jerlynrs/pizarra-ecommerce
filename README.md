# Pizarra: tutor de matemáticas con IA (prototipo de e-commerce)

Prototipo web de la tienda en línea de **Pizarra**, una plataforma de tutoría de matemáticas con inteligencia artificial que guía al estudiante paso a paso en lugar de darle la respuesta.

Proyecto de **Jerlyn Rodríguez (A00113235)** para la clase **ISO923 Implementación de E-commerce**.

> Es un prototipo (mock). No tiene backend: el carrito vive en memoria y los pagos son simulados.

## Qué incluye

| Pantalla | Qué muestra |
| --- | --- |
| Inicio | Propuesta de valor y cómo funciona |
| Planes | Catálogo de productos digitales: planes Gratis, Estudiante, Familia y Colegios (B2B), con precio mensual o anual, y complementos (Modo examen, Paquete Cálculo I, Sesión con tutor humano) |
| Carrito | Agregar y quitar productos, cupón de descuento (`PRIMERCICLO` = 20 %, `PIZARRA10` = 10 %) e ITBIS de 18 % |
| Pago | Checkout con tarjeta, PayPal o transferencia, con validación de campos. Tarjeta de prueba: `4242 4242 4242 4242` |
| Confirmación | Número de pedido y resumen de la compra |
| Mi panel | Dashboard del estudiante con progreso por área, escaneo simulado y ruta sugerida |
| Tutor | Resolución interactiva paso a paso con el botón “Explícalo diferente” |
| Logro | Resumen de reglas aplicadas y “Practicar uno similar” |

Funciona en computadora y celular, y se adapta al modo claro u oscuro del sistema.

## Cómo abrirlo

Haz doble clic en `index.html`. Se abre en el navegador sin instalar nada.

## Modelo de negocio (resumen)

- **Modelo de ingresos:** suscripción freemium (B2C) y licencias para colegios (B2B).
- **Mercado inicial:** estudiantes de secundaria y primeros años universitarios en República Dominicana y Latinoamérica.
- **Diferenciador:** enseña a resolver, no entrega la respuesta.

## Tecnologías

HTML, CSS y JavaScript sin frameworks, en un solo archivo.
