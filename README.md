# Automatización de reportes operativos

Este proyecto automatiza la generación de informes logísticos semanales utilizando Python. A partir de datos operativos estructurados, los reportes son generados en formatos PDF y/o Excel y enviados automáticamente por email.

El objetivo es reducir el tiempo dedicado a tareas manuales repetitivas y aumentar la consistencia y velocidad en la entrega de información clave.

## Objetivo

Optimizar el proceso de elaboración de reportes para equipos operativos y de supervisión logística.  
Reducir el esfuerzo manual en la preparación, exportación y distribución de informes recurrentes.

## Qué hace el sistema

- Lee datos desde archivo CSV, base de datos o fuente estructurada.
- Genera informes semanales con tablas de resumen y visualizaciones.
- Exporta automáticamente en formato PDF o Excel.
- Envía los archivos por email desde un servidor configurado.

## Tecnologías utilizadas

- Python
- pandas
- openpyxl (para Excel)
- ReportLab o fpdf2 (para PDF)
- yagmail o smtplib (para envío de correos)
- Git y GitHub

## Estructura del repositorio

automacion-reportes-operativos/


## Resultados esperados

- Reducción del 60 % en el tiempo destinado a tareas manuales de reporte semanal.
- Informes entregados puntualmente y sin errores de formato.
- Escalabilidad para integrar nuevos datos o KPIs en el futuro.

## Próximos pasos

- Incluir autenticación para envío seguro de emails.
- Publicar versión parametrizable vía interfaz (opcional).
- Conectar con dashboard de análisis para resumen visual.

---

**Este proyecto está basado en casos reales de automatización operativa en el entorno logístico de Encobox.**
