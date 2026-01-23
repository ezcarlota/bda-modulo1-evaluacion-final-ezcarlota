# bda-modulo1-evaluacion-final-ezcarlota
ejercicio evaluacion final modulo1 CARLOTA ESTEVEZ ZAMORA
# Sistema Básico de Gestión de Tienda en Python

¡Bienvenid@! Este proyecto es mi **primer contacto con Python** y consiste en un programa que permite gestionar compras y clientes en una tienda de manera sencilla.

---

## 🔹 Descripción

Este código simula una tienda básica, permitiendo:
- Agregar productos
- Ver inventario
- Buscar producto
- Actualizar stock
- Eliminar productos
- Calcular valor del inventario
- Realizar una compra
- Procesar un pago
- Registrar clientas/os con nombre y correo electrónico.
- Registrar compras vinculadas a cada cliente.
- Calcular el total de cada compra.
- Actualizar un historial de compras por cliente.
- Mantener un registro del dinero gastado por cada cliente.
- Calcular las ventas totales de la tienda.
- Mostrar información de clientes y compras.

El objetivo principal es **practicar estructuras básicas de Python** como listas, diccionarios, bucles y funciones.

---

## 🛠 Funcionalidades

1. **Agregar cliente/a**
   - Se puede registrar una clienta/o nuevo con su nombre y correo.
   

2. **Registrar compras**
   - Cada cliente/a puede registrar varias compras.
   - El carrito es una lista de productos (nombre y precio).
   - Actualiza automáticamente el historial y el total gastado por cliente.

3. **Calcular total de compra**
   - Suma los precios de los productos del carrito.

4. **Calcular ventas totales**
   - Suma el total gastado de todas las clientas/os de la tienda.

5. **Ver clientes y compras**
   - Permite revisar qué compras ha hecho cada cliente y cuánto ha gastado.

---

## ⚡ Tecnologías

- Python 3.x
- Solo se utilizan **listas, diccionarios y funciones básicas**.
- No requiere librerías externas.

---

## 📝 Ejemplo de uso

```python
# Crear clientes
agregar_cliente("Maria", "maria@xxx")

# Crear un carrito de compra
carrito = [
    {"nombre": "Pantalones", "precio": 30},
    {"nombre": "Abrigo", "precio": 60}
]

# Registrar compra
registrar_compra("Maria", carrito)

# Ver historial de compras
print(clientes[0]["compras"])

# Calcular ventas totales
calcular_ventas_totales()
