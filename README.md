# Tiendita Mary
Versión V0.0.1

Proyecto en Java que simula un sistema de ventas

## Funcionalidades
- Registrar productos
- Registrar clientes
- Registrar ventas
- Calcular stock disponible
- Calcular total de ventas
- Generar inventario de ventas

## Estructura del Proyecto
tiendita/

│── src/

│   └── app/#Presentacion

│   ├── model/ # Entidades

│   ├── service/ # Lógica de negocio

│   └── repository/ # Acceso a datos

│── README.md #Actualizacion de docuemntacion

│──Documents/ #Documentacion

La estructura a usar es la arquitectura en capas, la cual se explica mejor en:
[Estrectura de capas ](Documents/estructuraDeCapas.drawio.png)

## Caso de uso y documentacion 
En este primer caso consideramos la funcion mas importante que es la de registrar un producto
[Estrecturas importantes ](Documents/casoUso.pdf)

## Distribucion de ramas
En cuanto a la estructura de ramas se realizaran de la con la siguiente formato prefijo + número rama + descripción corta
[Estrecturas determinada](Documents/distribucionRamasV1.png)
##  Ramas creadas
- `create-my-firth-branch`: desarrollo de documentacion inicial.
- `develop`: integración y revisión de código.
- `main`: solo recibe código aprobado.
