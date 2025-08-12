# Proyecto 4 - Análisis de Comportamiento de Compras en Instacart

## Descripción
Análisis exploratorio de datos de la plataforma Instacart para identificar patrones de comportamiento de compra de los clientes.

## Objetivos
- Analizar hábitos de compra por día de la semana
- Identificar productos más populares
- Estudiar patrones de recompra

## Datasets utilizados
- `instacart_orders.csv` - Información de pedidos
- `products.csv` - Catálogo de productos
- `order_products.csv` - Productos por pedido
- `aisles.csv` - Categorías de pasillos
- `departments.csv` - Departamentos de productos

## Herramientas
- Python
- Pandas
- Matplotlib/Seaborn
- Jupyter Notebook

## Principales hallazgos
- Productos Estrella: Las bananas (orgánicas y convencionales) y fresas orgánicas dominan tanto en ventas como en recompras, representando oportunidades clave para optimización de inventario y estrategias de marketing.

- Comportamiento de Compra: Los clientes muestran patrones claros - productos básicos como bananas y leche orgánica son típicamente los primeros en añadirse al carrito, sugiriendo su uso como "productos ancla" para el diseño de la experiencia de usuario.

- Segmentación de Clientes: Identificamos dos grupos distintos - clientes ocasionales (1-5 pedidos) y clientes frecuentes (hasta 100 pedidos), cada uno requiriendo estrategias de retención diferenciadas.

- Calidad de Datos: Detectamos y corregimos duplicados sistemáticos y datos faltantes (1,258 productos sin categorizar), mejorando la confiabilidad del análisis para la toma de decisiones empresariales.

