# challenge1-data-science-latam
## Análisis de Venta de Productos para Tiendas

### Propósito del Proyecto
Este proyecto tiene como objetivo analizar y recomendar la mejor tienda para que el Sr. Juan venda sus productos, basándose en cinco factores clave:
- Ingresos totales por tienda
- Ventas por categoría de productos
- Calificaciones promedio de clientes
- Productos más y menos vendidos
- Coste de envío promedio

El análisis proporciona insights estratégicos para tomar una decisión informada sobre dónde comercializar los productos.

### Estructura del Proyecto
challenge1-data-science-latam/
│
├── AluraStoreLatam.ipynb # Notebook de análisis en Colab
├── InformeFinal.ipynb # Notebook del reporte ejecutivo

## Insights y Hallazgos Clave

### 1. Ingresos por Tienda
![Ingresos por Tienda](img/ingresos_tiendas.png)
- Tienda 2 muestra los mayores ingresos totales
- Tienda 1 y 3 tienen volúmenes similares pero menores

### 2. Satisfacción del Cliente
![Calificaciones](img/calificaciones.png)
- Tienda 3 lidera con 4.048 puntos
- Tienda 2 sigue de cerca con 4.037
- Diferencias significativas con Tiendas 1 y 4

### 3. Productos Destacados
![Productos Vendidos](img/productos_vendidos.png)
- Tienda 4 tiene el producto individual más vendido (Cama box - 60 unidades)
- Tienda 3 muestra mejor distribución entre productos populares y nicho

## Instrucciones de Ejecución

### Requisitos Previos
- Python 3.8+
- Jupyter Notebook
- Bibliotecas: pandas, matplotlib

### Pasos para Ejecutar el Análisis
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/proyecto-venta-tiendas.git
   cd proyecto-venta-tiendas
