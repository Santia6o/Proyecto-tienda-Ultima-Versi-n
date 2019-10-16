#Documentación:

####Proyecto Tienda:

####INTRODUCTION
Project Store, Software Engineering II
Below is the "Store" project that aims to Simulate the internal operation of a store, and alarm the seller at that time the products of the store are equal to or less than the quantity 10 (Unit) and also be able to prevent a shortage of any necessary product for sale.

###Code Proyect

     class movimiento.producto:
     def __init__(self, cantidad.producto, alarma, precio, proveedor1, proveedor2, proveedor3):
     self.cantidad.producto = cantidad.producto
     self.alarma = alarma
     self.precio = precio
     self.proveedor1. = proveedor1
     self.proveedor2. = proveedor2
     self.proveedor3. = proveedor3

     class productos:
     def __init__(self, cantidad.producto, alarma, precio, proveedor1, proveedor2, proveedor3):
     self.productos = productos:
     self.alarma = alarma
     self.precio = precio
     self.proveedor1. = proveedor1
     self.proveedor2. = proveedor2
     self.proveedor3. = proveedor3

     class cantidad:
     def __init__(self, cantidad.producto, alarma, precio, proveedor1, proveedor2, proveedor3):
     self.cantidad = cantidad:
     self.alarma = alarma
     self.precio = precio
     self.proveedor1. = proveedor1
     self.proveedor2. = proveedor2
     self.proveedor3. = proveedor3


##CLASS CHARTS

| Clase 1 | Clase2 | Clase 3 |
|---------|--------|---------|
|Movimiento.producto|Products|Quantity|
|Product movement: refers to products that are bought and sold in the store (entry / exit)|Products: shows the products offered and / or supplied by each supplier.|shows the quantity requested from the supplier for each product that will be supplied to the store.|


##Class diagram
| TIENDA                |PROVEEDORES| CANTIDAD |
|-----------------------|-----------|----------|
 •Productos: float,|     •ALPINA|       •15
 •Lacteos|              •FRESCAMPO|    •16 
• Bon Yurt|             •JHONSON       •24
• Kumis|                 |             •55
• Mantequilla|           |             •28 
• Yogurt Alpina|         |             •14
• QuesoMozarela Alpina|  |             •85
• Quesos|                |             •77
• Frijoles|              |             •33
• Arroz|                 |             •65
• Pasta marcaFrescampo|  |             •14
• Huevos|                |             •22 
• Pan|                   |             •36 
• Aceite|                |             •88
• Pescado|               |             •66
• Champoo|               |             •36 
• Limpiador de vidrios|  |             •51
• Detergente liquido|    |             •25
• Jabon Protex|          |             •55
•Cepillo de dientes|     |             •56
• Cepillo para el inodoro| |           •48
• Clorox|                |             •14


##Solution or steps of the program
####Class 1:
 Movement.product, in this class the movements of the products of the store are validated, taking into account the purchase and sale of the same.

####Class 2 
 Products: The seller asks the supplier for the products necessary to supply the store, the supplier
Indicates an estimated delivery date and the price to be paid for each product

####Clase 3 :
Quantity: The seller asks the supplier for the quantity of products needed to supply the store,
It is taken into account that the program is intended to alarm the seller when one or more products
are in short supply less than or equal to 10 (Units).

-------------------------------------------------
Autor: Bryan Santiago Useche Galeano
Cedula: #1012456618
Corporacion iberoamericana de estudios CIES
Materia: Ingenieria del Sofware II
Profesor: David Ariza