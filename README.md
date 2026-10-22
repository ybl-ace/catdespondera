# Infografía Interactiva: Ponderaciones en la Categoría de Desempeño

> Herramienta visual e interactiva diseñada para la comprensión de las ponderaciones de 2 o 3 mediciones dentro del cálculo de la categoría de desempeño.

## Propósito del Recurso

El recurso permite visualizar con claridad cómo se ponderan los resultados educativos a lo largo del tiempo, contrastando dos situaciones reales de medición.

### Escenarios de Medición

**1. Tres (3) Mediciones Disponibles (Escenario habitual)**
* **Año t (reciente):** 50,0%
* **Año t-1 (anterior):** 33,3%
* **Año t-2 (ante anterior):** 16,7%
* *(Suma total: 100,0%)*

**2. Dos (2) Mediciones Disponibles (Escenario con falta de medición histórica)**
* **Año t (reciente):** 66,7% *(dos tercios del puntaje total)*
* **Año t-1 (anterior):** 33,3% *(un tercio del puntaje total)*
* **Año t-2:** Sin medición aplicable.
* *(Suma total: 100,0%)*

### Componentes Anuales Evaluados
En cada año lectivo evaluado coexisten dos dimensiones fundamentales:
* **EDA (Estándares de Aprendizaje / Pruebas SIMCE):** Representa aproximadamente el **67%** de la evaluación de ese año *(círculo superior de mayor tamaño)*.
* **IDPS y otros :** Representa aproximadamente el **33%** de la evaluación de ese año.

---

## Funcionalidades e Interactividad

La infografía fue construida bajo un enfoque minimalista, fluido y centrado en la usabilidad del estudiante y docente:

* **Alternancia de Escenarios:** Botón selector superior que redistribuye instantáneamente la escala, las posiciones y los radios de las esferas con animaciones suaves entre los escenarios de 3 y 2 mediciones.
* **Selección de Pasos / Años por Columna:** Al hacer clic en cualquiera de las columnas temporales *(Año t-2, Año t-1, Año t)*:
  * La columna completa se resalta con un fondo suave.
  * Ambas circunferencias se iluminan en color coral (`#EB4A36`).
  * Se muestran los porcentajes internos de ponderación (67% para EDA y 33% para IDPS).
* **Guías Verticales de Relación:** Líneas discontinuas verticales que conectan de forma intuitiva las esferas con su año cronológico y porcentaje neto en la base.
* **Exploración por Mouseover (Hover Inteligente):**
  * **Conexión Horizontal:** Al posar el cursor sobre una esfera EDA o IDPS, una línea punteada une todos los componentes correspondientes a lo largo del tiempo.
  * **Banner Superior Elevado:** Se activa un banner informativo con la fórmula matemática y el impacto ponderado exacto del componente en el resultado global final *(ej. «En el Año t (reciente, 66,7%) aporta 44,7%
 
## Uso de IA
** Modelado y Generación de componentes interactivos en React y TypeScript.
** Modelado matemático y cálculo trigonométrico de coordenadas y radios vectoriales en SVG.
** Reducción de prototipo a HTML5 para compatibilidad y escalabilidad.
