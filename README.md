# Curso Claude para Excel

Repositorio oficial del curso **Claude para Excel** — aprende a usar inteligencia artificial directamente dentro de tu hoja de cálculo, sin código, sin memorizar fórmulas y sin ser experto en Excel.

---

## ¿Qué encontrarás aquí?

Este repositorio contiene los recursos de práctica del curso, incluyendo el archivo Excel base que se usa en todas las clases y los prompts de referencia para cada módulo.

---

## Archivo de práctica

### `Comercial_Norte_SA_CursoClaudeExcel.xlsx`

El archivo central del curso. Simula la hoja de cálculo real de **Comercial Norte S.A.**, una empresa ficticia con datos de ventas, gastos y empleados del año 2024. Todas las demos del curso se realizan sobre este archivo.

Contiene 7 pestañas:

| Pestaña | Color | Descripción | Usada en |
|---------|-------|-------------|----------|
| **Ventas** | 🟢 Verde | 80 transacciones de ventas 2024 con fecha, producto, categoría, vendedor y región | Módulos 2, 3 y 4 |
| **Gastos** | 🟠 Naranja | 48 registros de gastos con categoría, proveedor, monto y estado de pago | Módulo 3 |
| **Empleados** | 🔵 Azul | 15 empleados con cargo, área, salario y años en empresa | Módulos 2 y 3 |
| **Resumen** | 🟣 Morado | Dashboard con KPIs de ventas, gastos y empleados + 3 gráficas | Módulo 3 |
| **Errores_Demo** | 🔴 Rojo | Tabla de productos con errores de fórmula plantados intencionalmente | Módulo 2 — Clase 2.2 |
| **Formulas_Avanzadas** | 🟤 Verde oscuro | 7 fórmulas complejas listas para explicar con Claude | Módulo 2 — Clase 2.3 |
| **Datos_Sucios** | 🟡 Ámbar | Base de proveedores con 6 tipos de problemas de calidad de datos | Módulo 3 — Clase 3.2 |

---

## Errores intencionales en `Errores_Demo`

La pestaña **Errores_Demo** contiene errores plantados a propósito para practicar la detección con Claude en la clase 2.2. No son bugs del archivo:

| Celda | Error | Causa |
|-------|-------|-------|
| `D4` | Muestra **0** sin avisar | La fórmula apunta a `C99`, una fila que no existe |
| `D6` | `#¡VALOR!` | El precio está guardado como texto, no como número |
| `C8` | `#¡DIV/0!` | La fórmula divide entre cero al calcular el promedio |
| `E12` | Resultado incorrecto sin mensaje de error | Error lógico: el bono se calcula sobre el total de todas las ventas en lugar de las ventas del vendedor específico |

---

## Estructura del curso

### YouTube — gratuito

| Módulo | Clases | Contenido |
|--------|--------|-----------|
| 1 — Primeros pasos | 1.1 · 1.2 · 1.3 | Qué es Claude for Excel, instalación y primer uso |
| 2 — Fórmulas con IA | 2.1 · 2.2 | Crear fórmulas y detectar errores con Claude |
| 3 — Análisis de datos | 3.1 · 3.2 · 3.3 | Leer, limpiar y visualizar datos con Claude |
| 4 — Automatización | 4.1 | Skills: flujos guardados de un clic |

### Udemy — avanzado
Incluye los módulos anteriores más contenido exclusivo: modelos financieros, integración Excel + PowerPoint, Skills avanzadas y un proyecto final completo.

---

## Requisitos

- Microsoft Excel con suscripción Microsoft 365
- Add-in **Claude for Excel** instalado desde Microsoft AppSource
- Cuenta de Claude (plan Pro recomendado)

### Cómo instalar Claude for Excel
1. Abre Excel y ve a **Insertar → Complementos → Obtener complementos**
2. Busca **"Claude"** en la tienda de Microsoft AppSource
3. Haz clic en **Agregar** e inicia sesión con tu cuenta de Claude
4. Accede al panel lateral con **Ctrl + Alt + C**


---

## Contribuciones

Este repositorio es de solo lectura para los estudiantes del curso. Si encontraste un error en el archivo de práctica o tienes una sugerencia, abre un **Issue** y lo revisamos.

---

## Licencia

El archivo de práctica y los recursos de este repositorio son de uso exclusivo para estudiantes del curso **Claude para Excel**. No está permitida su redistribución o uso comercial sin autorización.

---

> Curso disponible en YouTube: **[Claude para Excel](#)**  
> Versión avanzada en Udemy: **[Claude para Excel — Avanzado](#)**