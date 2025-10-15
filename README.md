# 🧩 Comparador de Lotes de Promociones

Este es un **simple pero poderoso proyecto web** diseñado para comparar múltiples archivos **JSON** que contienen listas de promociones.  
La herramienta identifica **promociones nuevas, eliminadas y modificadas**, generando un **reporte cronológico detallado** de todos los cambios detectados.

---

## ✨ Características Principales

### Carga de Múltiples Archivos  
Permite seleccionar **dos o más archivos JSON** para su comparación.

### Orden Cronológico  
Organiza automáticamente los archivos basándose en la fecha **`calledAt`** para asegurar un análisis secuencial correcto.

### Detección de Cambios  
- **Promociones Creadas:** Identifica las promociones que aparecen en un lote pero no en el anterior.  
- **Promociones Eliminadas:** Detecta las promociones que estaban en un lote pero desaparecieron en el siguiente.  
- **Promociones Modificadas:** Muestra los campos específicos que han cambiado entre versiones de una misma promoción.

### Reporte Interactivo  
- **Resumen General:** Presenta tarjetas con el total de promociones creadas, modificadas y eliminadas.  
- **Filtro Dinámico:** Incluye una barra de búsqueda para filtrar los resultados por ID, nombre o tipo de cambio.  
- **Interfaz Clara:** Utiliza colores y un diseño limpio para diferenciar fácilmente los tipos de cambios.  
- **Fácil de Usar:** Interfaz de un solo clic para generar y limpiar el reporte.

---

## 🚀 Cómo Utilizar

1. Abre el archivo **`comparador_promociones.html`** en tu navegador web.  
2. Haz clic en el botón **"Seleccionar archivos"** y elige los archivos JSON que deseas comparar (mínimo dos).  
3. Presiona el botón **"Generar Reporte"**.  
4. ¡Listo! Revisa el **reporte cronológico** con todos los cambios detectados.  
5. Utiliza la **barra de búsqueda** para filtrar los resultados si es necesario.  
6. Para empezar de nuevo, haz clic en **"Limpiar Reporte"**.

---

## 🛠️ Tecnologías Utilizadas

- **HTML5:** Para la estructura básica de la página.  
- **Tailwind CSS:** Para un diseño moderno y responsivo sin necesidad de archivos CSS externos.  
- **JavaScript (Vanilla):** Para toda la lógica de lectura de archivos, comparación y generación dinámica del reporte.

---

Este proyecto fue creado para **simplificar el seguimiento de cambios en catálogos de promociones** de forma rápida y visual.
