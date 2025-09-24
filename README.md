Tienda Online en Python

Este proyecto implementa una clase en Python que simula la gestión de una tienda online mediante automatización de procesos.
Desarrollado con Programación Orientada a Objetos (POO) en Visual Studio Code, permite administrar productos e inventario sin necesidad de hacerlo manualmente.

🤖 Automatización aplicada

Gestión automática del inventario: actualización de stock cuando se agregan o eliminan productos.

Control de duplicados: si un producto ya existe, el sistema actualiza la cantidad en lugar de crear registros nuevos.

Validación de stock mínimo: evita que las cantidades bajen por debajo de 0.

Cálculo automático del valor total del inventario: ahorro de tiempo en operaciones manuales.

Reportes básicos por consola: para visualizar datos clave de productos, precios y cantidades.

⚙️ Técnicas utilizadas

Programación Orientada a Objetos (POO).

Listas y diccionarios como estructuras de datos dinámicas.

Condicionales y bucles para la gestión lógica de procesos.

Funciones personalizadas que automatizan tareas repetitivas.

📦 Funcionalidades principales

Agregar productos y actualizar cantidades.

Ver inventario completo.

Buscar productos por nombre.

Actualizar stock (aumentar o disminuir).

Eliminar productos del inventario.

Calcular el valor total del inventario.

▶️ Ejemplo de uso
mi_tienda = TiendaOnline("SuperTienda")

# Agregar productos (automatiza la gestión del inventario)
mi_tienda.agregar_producto("Camiseta", 20.0, 10)
mi_tienda.agregar_producto("Zapatos", 50.0, 5)

# Visualizar inventario
mi_tienda.ver_inventario()

# Calcular valor total automáticamente
mi_tienda.calcular_valor_total()

📊 Ejemplo de salida
Producto Camiseta ha sido agregado al inventario.
Producto Zapatos ha sido agregado al inventario.
Nombre: Camiseta, Precio: $20, Cantidad: 10
Nombre: Zapatos, Precio: $50, Cantidad: 5
Valor total del inventario: €250.0
