# Dashboard de Facturación - Power BI | DVA Ingeniería

## Descripción
Dashboard interactivo de facturación semanal desarrollado en Power BI 
para DVA Ingeniería, conectado a SharePoint Online para actualización 
automática de datos desde cualquier dispositivo.

## ⚠️ Aviso importante
Los datos mostrados en este dashboard son completamente simulados 
y no corresponden a información real de ninguna empresa. 
Fueron generados con fines demostrativos para proteger la 
confidencialidad de la información empresarial.
Para solicitar el archivo .pbix contáctame en:
📩 linkedin.com/in/gustavo-adolfo-davila-donoso-b713302b8

## Arquitectura
- **Power BI Desktop** — desarrollo del dashboard
- **SharePoint Online** — almacenamiento del Excel en la nube de Microsoft
- **Excel** — fuente de datos actualizable semanalmente
- **Power BI Service** — publicación y acceso remoto desde cualquier dispositivo

## Páginas del Dashboard

### Página 1 - Indicadores Principales
- KPIs: Facturación Mes Anterior, Mes Actual y Semana Actual
- Gauge de Cumplimiento de Meta Mensual
- Top Clientes por facturación total
- Tendencia de facturación semanal en el tiempo con líneas de meta
- Filtros por Año, Semana, Mes y Cliente
- Botón Reset para limpiar filtros

### Página 2 - Análisis Detallado
- Top Clientes con facturación semana a semana del año actual
- KPIs detallados: % vs Año Anterior, % vs Mes Anterior
- Facturación por Año, Mes y Semana
- Botón Reset para limpiar filtros

### Página de Preguntas Frecuentes
- Herramienta Q&A de Power BI integrada
- Responde preguntas habituales del usuario sobre los datos

## Funcionalidades destacadas
- Actualización automática conectando Excel en SharePoint
- Acceso desde cualquier dispositivo via nube de Microsoft
- **Marcadores (Bookmarks)** para navegación entre pestañas via barra lateral
- **Botón Reset** por pestaña implementado con marcadores para limpiar filtros
- **Q&A integrado** para consultas en lenguaje natural
- Filtros interactivos por Año, Semana, Mes y Cliente
- Meta mensual configurable (establecida en $200 millones para demo)

## Medidas DAX implementadas
- Facturación Mes Actual
- Facturación Mes Anterior
- Facturación Semana Actual
- Facturación Por Año
- Facturación Por Mes
- % Cumplimiento Meta Mensual
- % Variación vs Año Anterior
- % Variación vs Mes Anterior
- Facturación Por Semana
- Top Clientes por Facturación

## Stack
- Power BI Desktop
- Power Query (ETL)
- DAX
- SharePoint Online
- Excel (fuente de datos)
- Marcadores (Bookmarks)
- Q&A Power BI


  ## Capturas del Dashboard

### Página 1 - Indicadores Principales
![Página 1](P1%20DASHBOARD%20FACTURACION.png)

### Página 2 - Análisis Detallado
![Página 2](P2%20DAHSBOARD%20FACTURACION.png)
