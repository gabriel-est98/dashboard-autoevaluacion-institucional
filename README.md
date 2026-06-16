# 📊 Dashboard Ejecutivo de Autoevaluación e Indicadores de Acreditación Universitaria

## 📋 Descripción del Proyecto
Este proyecto consiste en el diseño, desarrollo e implementación de una solución de Business Intelligence (BI) para el departamento de Aseguramiento de la Calidad. El objetivo principal fue centralizar, estructurar y transformar un informe analítico estático de **150 páginas** correspondiente a la autoevaluación institucional, convirtiéndolo en un ecosistema de dashboards interactivos que optimizan la toma de decisiones estratégicas de la alta dirección (Rectorado, Vicerrectores y Comisión de Aseguramiento de la Calidad).

---

## 🎯 El Problema Organizacional
Previo al proceso de acreditación oficial de la universidad, se realiza una autoevaluación exhaustiva para conocer la situación institucional de cara a la evaluación externa. Sin embargo, la presentación de los resultados mediante documentos extensos de 150 páginas o diapositivas estáticas (PPTX) presentaba las siguientes ineficiencias:
* **Baja eficiencia operativa:** Las reuniones de gobernanza con autoridades requerían demasiado tiempo para localizar indicadores específicos entre cientos de páginas.
* **Falta de dinamismo:** Los datos presentados carecían de la capacidad de filtrado instantáneo por dirección, sede o criticidad.
* **Brecha en la toma de decisiones:** La complejidad visual dificultaba la identificación inmediata de elementos fundamentales y resultados previos a la evaluación definitiva.

---

## 💡 La Solución Propuesta
Se diseñó un producto de datos interactivo e intuitivo en Power BI estructurado de forma modular para sintetizar los componentes clave del informe:

1. **Fase de Ingeniería de Datos (ETL):** Extracción, limpieza y transformación de la información del informe original mediante Power Query, garantizando la consistencia y normalización de las métricas.
2. **Diseño de Interfaz y UX Corporativa:** Implementación de un menú de navegación lateral izquierdo intuitivo y módulos limpios basados en contenedores independientes (gráficos de barras, velocímetros y treemaps) para evitar la saturación visual.
3. **Arquitectura de KPIs:** Agrupación y despliegue estratégico de indicadores por direcciones (Ética, Admisión, Aseguramiento de la Calidad, Bienestar Universitario, Investigación), permitiendo a los directivos evaluar el estado de cumplimiento en segundos.

---

## 🛠️ Tecnologías y Habilidades Aplicadas
* **Power BI:** Desarrollo del modelo de negocio visual y tableros interactivos.
* **Power Query / ETL:** Procesamiento, limpieza y estructuración de datos institucionales.
* **Diseño de KPIs:** Conceptualización y alineación de métricas de autoevaluación.
* **Data Visualization:** Aplicación de principios de diseño visual, contraste y jerarquía de información para audiencias ejecutivas.

---

## 📈 Impacto y Resultados
* **Eficiencia Directiva:** Reducción del tiempo de consulta de indicadores de días a segundos durante las juntas ejecutivas con Rectoría.
* **Estrategia Basada en Datos:** Habilitación de un análisis interactivo que permite identificar brechas críticas de manera inmediata, facilitando planes de acción correctivos rápidos antes de la llegada del comité evaluador externo.
* **Escalabilidad:** El diseño modular permite la actualización periódica de datos para futuros periodos de autoevaluación sin reestructurar la interfaz.

---

## 📂 Estructura sugerida para este Repositorio
* `pbix/`: Contiene el archivo ejecutable de Power BI (versión anonimizada para proteger datos confidenciales institucionales).
* `data/`: Muestra o plantilla de datos simulados utilizados para alimentar el modelo.
* `images/`: Capturas de pantalla del dashboard en alta resolución.
