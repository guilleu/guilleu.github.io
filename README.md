# Nexo Store — proyecto base para estudiantes

Esta versión corresponde al sistema que se entrega al comienzo del curso.

## Estado inicial

La estructura general del sistema ya se encuentra creada para que todos los equipos trabajen sobre una misma base. La página de inicio es el módulo habilitado en el Sprint 1. Las demás páginas existen, pero muestran un aviso de funcionalidad en desarrollo y no contienen la solución correspondiente.

## Organización en cuatro sprints

### Sprint 1 — Semanas 1 a 4

**Interfaz web estática y responsive**

Los equipos deberán desarrollar y personalizar:

- nombre e identidad visual del e-commerce;
- página de inicio;
- navbar y footer;
- hero principal;
- productos destacados estáticos;
- estructura semántica;
- estilos propios;
- componentes Bootstrap;
- diseño responsive;
- accesibilidad básica;
- navegación entre páginas.

En este sprint no se debe implementar todavía la lógica del catálogo, el carrito, la autenticación ni Firebase.

### Sprint 2 — Semanas 5 a 8

**Interacción del lado del cliente**

Se habilitarán `catalogo.html`, `producto.html` y `carrito.html`.

Los equipos deberán desarrollar:

- productos representados mediante objetos JavaScript;
- generación dinámica del catálogo;
- categorías, búsqueda, filtros y ordenamiento;
- detalle individual del producto;
- carrusel de imágenes y características;
- valoraciones y comentarios simulados;
- agregado al carrito;
- modificación de cantidades y eliminación;
- cálculo de subtotal y total;
- control de stock;
- persistencia mediante LocalStorage.

### Sprint 3 — Semanas 9 a 12

**Firebase, autenticación y administración inicial**

Se habilitarán el registro, inicio de sesión, `perfil.html`, historial de pedidos y `admin.html`.

Los equipos deberán desarrollar:

- conexión con Firebase;
- productos almacenados en Firestore;
- operaciones CRUD;
- Firebase Authentication;
- cierre y persistencia de sesión;
- protección de páginas privadas;
- diferenciación entre cliente y administrador;
- registro y consulta de pedidos;
- panel administrativo inicial;
- gestión de productos, stock y disponibilidad.

La página de perfil no deberá visualizarse sin iniciar sesión. El panel administrativo solamente deberá estar disponible para usuarios con rol administrador.

### Sprint 4 — Semanas 13 a 15

**Seguridad, calidad y publicación**

Los equipos deberán completar:

- reglas de seguridad de Firestore;
- autorización por roles;
- acceso de cada usuario únicamente a sus propios pedidos;
- validaciones y manejo de errores;
- pruebas funcionales;
- revisión de accesibilidad;
- optimización responsive;
- depuración y documentación;
- publicación en Firebase Hosting;
- presentación final.

## Páginas incluidas

- `index.html`
- `catalogo.html`
- `producto.html`
- `carrito.html`
- `perfil.html`
- `admin.html`

## Consigna inicial del Sprint 1

Los equipos deberán personalizar la página de inicio sin implementar todavía los módulos correspondientes a los siguientes sprints.

Deberán:

- definir la temática y el público objetivo;
- definir nombre e identidad visual;
- modificar colores y tipografías;
- adaptar el hero;
- construir tarjetas estáticas de productos destacados;
- utilizar HTML semántico;
- aplicar Bootstrap;
- asegurar un diseño responsive;
- incorporar textos alternativos;
- mantener la navegación hacia todos los módulos;
- conservar los carteles de funcionalidad en desarrollo.

## Restricciones del Sprint 1

No se deberá implementar todavía:

- catálogo dinámico;
- objetos JavaScript para productos;
- filtros;
- detalle dinámico;
- carrito;
- LocalStorage;
- autenticación;
- Firebase;
- panel administrativo funcional.

Cada módulo será habilitado en el sprint correspondiente.

## Ejecución

Puede abrirse mediante Live Server en Visual Studio Code.
