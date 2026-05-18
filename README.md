# Joel Contrera

### Primer Parcial - Informática General
### Artes Multimediales - UNA

---

## Declaración de Uso de Inteligencia Artificial

### 1. Herramientas utilizadas
* Gemini (Modelo de lenguaje de Google).

### 2. Etapas en las que se utilizó IA
* **Revisión y corrección de código:** Diagnóstico de errores de carga del CSS, estructura semántica de las etiquetas y validación de sintaxis en el archivo de estilos.
* **Maquetación del menú:** Asistencia en la correcta implementación de la estructura de listas (`<ul>` y `<li>`) vinculadas a la hoja de estilos global.

### 3. Resumen de errores encontrados y mejoras implementadas
* **Error de sintaxis en el menú:** La IA detectó que el menú de `trayectoria.html` y `obras.html` se rompió al no respetar las etiquetas de lista que el CSS global estaba esperando. Se corrigió reincorporando las etiquetas `<ul>` y `<li>` para normalizar el diseño horizontal.
* **Problemas de visualización en el navegador:** Se analizó si el problema radicaba en la sintaxis de las etiquetas `<link>` del `<head>` o en el almacenamiento en caché del navegador, resolviéndose mediante la reestructuración limpia del orden de carga de los estilos.

### 4. Conclusiones personales (Ventajas y desventajas)
* **Ventajas:** Funciona para detectar errores de tipeo como etiquetas mal cerradas o errores en la estructura de los documentos.
* **Desventajas:** Si no lo analizaba de forma critica y observadora la IA realizaba supuestas correcciones,donde el codigo estaba bien,y solo me faltaban añadir o en ocaciones corregir una etiqueta,o renombrar un archivo como el de las imágenes.