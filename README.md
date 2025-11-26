# Allura-Store

Análisis Comparativo de Tiendas y Recomendación Estratégica
Descripción del Proyecto
Este proyecto tiene como objetivo analizar el rendimiento de cuatro tiendas de comercio electrónico (Tienda 1, Tienda 2, Tienda 3, Tienda 4) basándose en métricas clave de negocio. El análisis está diseñado para ayudar en la toma de decisiones estratégicas, específicamente para identificar si alguna tienda debería ser considerada para venta o reestructuración debido a un bajo rendimiento o ineficiencias operativas.

Origen de los Datos
Los datos provienen de cuatro archivos CSV, cada uno representando las ventas y operaciones de una tienda diferente. Estos archivos contienen información sobre productos, categorías, precios, costos de envío, fechas de compra, vendedores, lugar de compra, calificaciones y métodos de pago.

Análisis Realizados
Se llevaron a cabo los siguientes análisis para cada tienda:

Facturación Total: Cálculo del ingreso total generado por cada tienda.
Categorías de Productos: Identificación de las categorías de productos más y menos populares, así como el Top 3 de categorías más vendidas por tienda.
Calificación Promedio de Clientes: Evaluación de la satisfacción del cliente a través de la calificación promedio recibida por cada tienda.
Productos Más y Menos Vendidos: Identificación del Top 5 de productos con mayor y menor volumen de ventas por tienda.
Costo Promedio de Envío: Cálculo del costo promedio asociado al envío de productos desde cada tienda.
Hallazgos Clave
Facturación: La Tienda 1 presenta la facturación total más alta, seguida de la Tienda 2, Tienda 3 y Tienda 4.
Calificación de Clientes: La Tienda 3 tiene la calificación promedio más alta, mientras que la Tienda 1 registra la calificación más baja.
Costos de Envío: La Tienda 1 incurre en el costo promedio de envío más alto, siendo la Tienda 4 la que tiene el costo más bajo.
Categorías Populares: 'Muebles', 'Electrónicos' y 'Juguetes' son consistentemente las categorías más populares en la mayoría de las tiendas.
Recomendación Estratégica
Basándose en un análisis comparativo de todos los puntos clave, se recomienda la venta de la Tienda 1.

Justificación de la Recomendación:
Aunque la Tienda 1 tiene la facturación más alta, la combinación de la calificación promedio más baja de los clientes y el costo promedio de envío más alto la identifica como la tienda con el mayor riesgo y el menor potencial de mejora a largo plazo sin una inversión sustancial y reestructuración. Una baja satisfacción del cliente y altos costos operativos erosionan la rentabilidad y pueden dañar la reputación general de la marca. En contraste, otras tiendas, como la Tienda 4, aunque con menor facturación, muestran una mayor eficiencia operativa y una mejor satisfacción del cliente, lo que las hace más atractivas para una futura inversión o crecimiento.

Cómo Utilizar este Notebook
Cargar Datos: Ejecuta las celdas de importación de datos para cargar los archivos CSV en DataFrames de pandas.
Ejecutar Análisis: Recorre las secciones del notebook, ejecutando las celdas para visualizar los diferentes análisis (facturación, categorías, calificaciones, etc.).
Revisar Conclusión: La sección final "Análisis y Recomendación Estratégica" consolida todos los hallazgos y presenta la recomendación final.
Requisitos
Este notebook utiliza las librerías pandas, matplotlib y seaborn.