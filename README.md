# 🛒 Proyecto Symfony: **ShopLite** - Mini E-commerce

## 📍 Fase 1: Análisis, Requerimientos y Planeación

---

### 🧠 Objetivo General

Desarrollar una aplicación web de tipo **e-commerce** utilizando Symfony, que permita gestionar productos, categorías y un carrito de compras. Este proyecto tiene como fin aplicar los principios del **patrón MVC** y explorar las capacidades reales del framework.

---

### 🎯 Objetivos Específicos

- ✅ Aplicar el patrón **MVC** de Symfony en un proyecto real.
- ✅ Crear operaciones **CRUD** para productos y categorías.
- ✅ Implementar un **carrito de compras** usando sesiones.
- ✅ Simular un flujo de compra sin pasarela de pago.
- ✅ Explorar **relaciones entre entidades** con Doctrine.
- ✅ Usar **formularios** y validaciones de Symfony.

---

### 📋 Requerimientos del Sistema

#### ✅ Funcionales:

- Ver catálogo de productos.
- CRUD de productos y categorías por parte del administrador.
- Agregar y quitar productos del carrito.
- Ver y modificar el carrito.
- Simular una compra con resumen de pedido.

#### ⚙️ No funcionales:

- Accesible desde cualquier navegador moderno.
- Interfaz simple, funcional y responsive.
- Código bien estructurado, legible y comentado.

---

### 👥 Historias de Usuario

#### 🛍️ Cliente

- *Como cliente*, quiero ver una lista de productos para elegir qué comprar.
- *Como cliente*, quiero agregar productos a mi carrito para planear mi compra.
- *Como cliente*, quiero revisar y modificar el contenido de mi carrito.
- *Como cliente*, quiero simular una compra y ver un resumen del pedido.

#### 🧑‍💼 Administrador

- *Como administrador*, quiero crear nuevos productos para mantener el catálogo actualizado.
- *Como administrador*, quiero editar productos para corregir errores o actualizar precios.
- *Como administrador*, quiero eliminar productos que ya no estén disponibles.
- *Como administrador*, quiero organizar productos en categorías para facilitar la navegación.

---

### 🧱 Arquitectura del Proyecto (MVC)

- **Modelo (Model):** Entidades como `Product`, `Category`, `Cart`, `Order`.
- **Vista (View):** Plantillas Twig limpias y minimalistas.
- **Controlador (Controller):** Lógica de negocio y manejo de rutas.

---

### 🛠️ Tecnologías Utilizadas

**Symfony 5.4** (LTS), PHP 8.2, Apache2, MariaDB, Doctrine ORM, Twig, Symfony Forms & Validator, sesiones PHP, y Composer.

---

### 🧾 Fase actual: Planeación

En esta primera fase se definieron los **objetivos**, **requerimientos**, **historias de usuario** y la estructura base del proyecto.  
En la próxima etapa, comenzaremos con la creación del proyecto Symfony y el diseño de nuestras primeras entidades como `Product` y `Category`.

---

### 🚀 ¡Esto recién empieza!

En la siguiente entrada vamos a levantar el proyecto Symfony desde cero y modelar nuestras entidades con Doctrine.  

Si estás aprendiendo Symfony y te interesa construir un e-commerce paso a paso con buenas prácticas,  
**¡seguí leyendo y desarrollando junto conmigo este proyecto llamado ShopLite!**
