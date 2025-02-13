El ejercicio del módulo 1 consta de la creación de una clase 'TiendaOnline', que servirá como 'plantilla' para introducir datos, ya predeterminados en esta clase, sobre diferentes instancias, en este caso ecommerces.

Esta clase cuenta con los siguientes parámetros por defecto: 'inventario' y 'ventas_totales'.

Para comenzar, he creado el método 'agregar_stock' que permitirá añadir de forma automatizada un stock al inventario con una cantidad significativa de productos para poder comprobar el correcto funcionamiento de los siguientes métodos.

Para el segundo método, 'agregar_producto' he comenzado creando un código que permita añadir un producto en caso de que el inventario esté vacío. Al añadir un producto al inventrario permitirá actualizar la cantidad en caso de que exista o introducirlo en caso de que no. 

El método 'ver_inventario' permite imprimir uno por uno el contenido del inventario indicando el nombre, cantidad y precio de la prenda.

El método 'buscar_producto' devolverá la información de nombre, precio y cantidad de la prenda que le indiques al llamar a la función.

El método 'actualizar_stock' permite actualizar la cantidad de una prenda indicada como parámetro, sumando la cantidad ya existente con la indicada como parámetro.

El método 'eliminar_producto' permite eliminar la prenda del stock que coincida con la indicada en el parámetro.

El método 'calcular_valor_inventario' permite calcular el valor total del inventario teniendo en cuenta las cantidades y precios de todos los artículos.


He realizado los dos primeros métodos del bonus. Para lo que a la función le he añadido el parámetro clientes, que es un dicciconario vacío. El primer método permite agregar los clientes que no estén registrados con la información de su email y una lista vacía del historial de compras. El segundo permite ver los clientes ya añadidos.