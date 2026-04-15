# 📄 RPA: Extracción Automatizada de Facturas PDF a Excel (Regex)

## Descripción del Proyecto
Este bot soluciona la carga administrativa de procesar facturas recibidas en formato PDF. Utilizando técnicas de **Regex (Expresiones Regulares)**, el robot identifica y extrae datos específicos de cada documento, consolidándolos automáticamente en un reporte estructurado de Excel.

## Impacto del Proyecto (Resultados Reales)
* **Ahorro de Tiempo:** Reducción del ciclo de procesamiento de **2 horas a menos de 1 minuto**.
* **Precisión:** Eliminación total de errores de digitación manual.
* **Escalabilidad:** El bot puede procesar cientos de facturas en una sola ejecución sin intervención humana.

## Tecnologías y Herramientas
* **UiPath Studio:** Desarrollo del flujo de trabajo (Workflow).
* **PDF Automation:** Uso de actividades de lectura de texto en PDF.
* **Regex (Regular Expressions):** Extracción precisa de número de factura, fecha y valores totales.
* **DataTables:** Manejo y estructuración de la información extraída.
* **Excel Automation:** Generación y actualización del reporte final.

## Flujo de Trabajo
1.  **Lectura de Directorio:** El robot escanea una carpeta local en busca de archivos PDF.
2.  **Extracción de Datos:** Aplica patrones Regex para capturar:
    * Número de Factura.
    * Fecha de Emisión.
    * Valor Total.
3.  **Consolidación:** Almacena los datos en una tabla de memoria.
4.  **Exportación:** Escribe los resultados en un archivo Excel maestro.

---<img width="1152" height="648" alt="download" src="https://github.com/user-attachments/assets/f03175eb-24b4-4450-8280-5dcab81077e5" />

### 📺 Demostración del Bot
![Demostración del Robot](nombre-de-tu-gif-aqui.gif)
