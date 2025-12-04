## Allura-Store
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
Calificación de Clientes: La Tienda 3 tiene la calificación promedio más alta, mientras que la Tienda 1 posee la calificación más baja.
Costo de Envío: La Tienda 1 registra el costo promedio de envío más alto, y la Tienda 4 el más bajo.
Categorías Populares: "Muebles" y "Electrónicos" son consistentemente las categorías más vendidas en todas las tiendas.
Recomendación Estratégica Principal
Se recomienda la venta de la Tienda 1. A pesar de tener la facturación más alta, presenta la calificación promedio más baja y el costo promedio de envío más alto. Estos factores indican problemas significativos en la satisfacción del cliente y la eficiencia operativa, lo que podría afectar su rentabilidad y reputación a largo plazo. La venta permitiría redirigir recursos a tiendas con mejor desempeño.

Instalación
Para ejecutar este proyecto, necesitas tener Python 3.x instalado. Se recomienda usar un entorno virtual para manejar las dependencias.

Clonar el repositorio (si aplica):

git clone <URL_DEL_REPOSITORIO>
cd Allura-Store
Crear y activar un entorno virtual:

python -m venv venv
# En Windows:
venv\Scripts\activate
# En macOS/Linux:
source venv/bin/activate
Instalar las dependencias:

pip install -r requirements.txt
(Asegúrate de crear un archivo requirements.txt con las librerías necesarias, por ejemplo, pandas, matplotlib, seaborn).

Dependencias
Las principales librerías utilizadas en este proyecto son:

pandas para manipulación y análisis de datos.
matplotlib para la creación de gráficos estáticos.
seaborn para la visualización de datos estadísticos.
json para manejar la salida de resúmenes.
Estas y otras dependencias se listan en el archivo requirements.txt.

Cómo Ejecutar el Proyecto
Asegúrate de haber completado los pasos de instalación.
Abre el notebook de Jupyter (o Google Colab) analisis_tiendas.ipynb.
Ejecuta todas las celdas del notebook en orden. Esto cargará los datos, realizará los análisis y generará las visualizaciones y el resumen estratégico.
Posibles Problemas y Soluciones
Archivos CSV no encontrados: Asegúrate de que los URLs de los archivos CSV (tienda_1.csv, tienda_2.csv, etc.) sean correctos y accesibles. Si los archivos están en una ubicación local, verifica la ruta.
Errores de instalación de librerías: Si pip install -r requirements.txt falla, intenta instalar las librerías individualmente (ej. pip install pandas). Asegúrate de que tu entorno virtual esté activado.
Problemas de visualización: Si los gráficos no se muestran correctamente, verifica que matplotlib y seaborn estén instalados y que estés ejecutando el código en un entorno que soporte la visualización (como Jupyter Notebook o Google Colab).
Columnas faltantes: Si el código produce errores de "KeyError" por columnas no encontradas, verifica que los nombres de las columnas en tus archivos CSV coincidan con los usados en el script (Producto, Categoría del Producto, Precio, etc.).