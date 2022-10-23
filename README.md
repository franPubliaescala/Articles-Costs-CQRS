# Articles_Costs_CQRS
Cálculo de costes de producto con el uso de CQRS.

Se pretende simular una API para consultar el coste de un producto dado.

## Dominio Costes
El coste de un producto será la suma de:
  - Precio de compra del producto
  - Coste de transporte
  - Coste de almecenamiento
![My first board](https://user-images.githubusercontent.com/11891132/197388824-8fa55b1d-52a6-4235-a810-569419f95b37.jpg)

### Subdominos
Para simplificar el ejemplo, el dominio principal solo contará con 3 subdominios.
  - Compras
  - Transporte
  - Almacenamiento

Estos subdominios se gestionarán con microservicios para sus tareas básicas de CRUD
