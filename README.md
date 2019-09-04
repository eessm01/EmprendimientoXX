# entrepreneursXX
Análisis de casos de uso, funcionalidad y páginas demo para el proyecto: Escuela de Javascript - E-commerce

### Propósito general del proyecto
Para este proyecto tu y tu equipo deben desarrollar un E-commerce.

Este tipo de sistemas permiten que los compradores puedan hacer sus compras a través de sitios web o aplicaciones moviles. El objetivo es que el cliente pueda ingresar al sitio web del ecommerce, ver el catalogo de productos y sus precios, ver la descripción detallada de los productos, agregar productos al carrito de compras y hacer la compra de su producto.

### Alcance del proyecto

1. Pantallas mínimas que deben ser implementadas
2. Pantalla de Sign in / Sign up / Logout
3. Pantalla de listado de productos
4. Pantalla de detalle del producto
5. Carrito de compras
6. Pantalla de Checkout
   
### Flujo esperado

1. El cliente ingresa al sitio web y busca el producto que le interesa.

2. El cliente puede navegar por el listado de productos ofertados.
   links de ejemplo:
  
3. El cliente selecciona el producto de su interés y lo agrega al carrito de compras.

4. El cliente revisa su carrito de compras, allí puede hacer modificaciones como por ejemplo cambiar la cantidad de productos que va a comprar.

5. Cuando esté listo el cliente puede hacer checkout de la compra y se le presentaran opciones para el pago.

6. Se debe registrar información relacionada con la dirección y datos de facturación y de entrega.

7. Si el cliente aún no se ha registrado debe registrarse antes de hacer checkout.

### El usuario administrador puede

1. Agregar, modificar o eliminar los productos del listado de productos.

2. Validar compras y revisar facturas de clientes con el número de documento.

3. Agregar, eliminar o modificar datos y detalles de los productos.

4. Generar reportes de inventario del negocio.

### Requerimientos técnicos adicionales
1. El sistema debe funcionar en la nube
2. El cliente debe poder ver los productos, seleccionar y agregar al carrito de compras sin que sea necesario hacer login en el sitio.


# Propuestas de páginas y soluciones.

https://www.kichink.com/
https://estadonatural.com.mx/ 
https://www.ceresbiomarkets.mx
https://www.xamania.com/

Listado de productos:
  - nombre del producto
  - imagen principal
  - costo
  - Dueño
  - indica si el producto es nuevo
  - Boton de ver detalles

En cada detalle del producto o "card":
   - muestra más imagenes
   - nombre del producto
   - costo
   - cantidad
   - descripcion del producto
   - botón de añadir al carrito
   - ver otros productos de la misma persona o marca

En carrito de compras:
   - Total de productos de productos
   - boton de pagar orden
   - subtotal de compra
   - listado de productos en el que para cada uno viene:
      - nombre del producto
      - costo
      - cantidad
      - imagen principal
 
Checkout:
Debe ser usuario logueado
  - subtotal
  - opción de buscar más productos
  - boton de efectuar pago
  - listado de productos en el que cada uno debe tener:
      - nombre
      - imagen principal
      - nombre del producto
      - cantidad
      - acción de borrar producto
      - importe
      

Ejemplos de pantallas:
   ![](https://gobiznext.com/wp-content/uploads/2017/08/home-int-wp.jpg)
   ![](https://gobiznext.com/wp-content/uploads/2017/08/maxresdefault-int-wp.jpg)
   ![](https://www.immidesodorante.com/wp-content/uploads/2018/07/immi-desodorante-en-kichink3.png)
   

