# 🎓 Calculadora de Notas — Ingeniería Civil en Biotecnología USM

Calculadora web para llevar el control de tus notas durante la carrera. Te permite ingresar las evaluaciones de cada ramo (certámenes, controles, tareas, laboratorio y certamen global), calcula automáticamente tu nota final y te dice **cuánto necesitas sacar en lo que falta para aprobar**.

Incluye los 10 semestres de la malla oficial de la carrera, usa la escala de evaluación de la USM (0–100, aprobación con 54,5) y tus notas se guardan solas en tu navegador, sin necesidad de crear cuenta ni instalar nada.

🔗 **Link para usarla: https://joaquin1307.github.io/Calculadora---Notas-ICB-USM

---

## 📖 Cómo usarla

### 1. Navega por semestre

Arriba hay una pestaña por cada semestre (Sem 1 a Sem 10) y una de **📊 Resumen** con el avance general de la carrera. Cada ramo aparece en una tabla con su nota, estado (aprobado/reprobado) y cuánto te falta para pasar.

### 2. Abre un ramo para ingresar notas

Haz clic en el nombre del ramo, en la sección de abajo de la tabla ("Calculadora por evaluaciones"), para desplegar el detalle. Ahí puedes elegir entre dos modos:

- **Nota directa**: si ya tienes la nota final del ramo, simplemente la escribes.
- **Por secciones**: si quieres que la calculadora te haga el cálculo ponderado, activando las partes que correspondan a tu ramo:

| Sección | Para qué sirve |
|---|---|
| 📝 **Certámenes** | Certámenes parciales del semestre |
| 📋 **Controles** | Controles o pruebas cortas |
| 📌 **Tareas** | Tareas evaluadas con nota |
| 🧪 **Laboratorio** | Se divide en prácticos, informes, quizzes, prueba escrita y actividad práctica — activa solo las que tenga tu ramo |
| 🎯 **Certamen Global** | Para ramos donde el examen final pondera junto con el promedio acumulado (ej. 40% global + 60% promedio del ramo) |

Cada sección tiene su propio **peso (%)**, y le puedes agregar o quitar evaluaciones con los botones **+ Agregar** y **×**.

### 3. Descarta tus peores notas (si tu ramo lo permite)

Si tu profesor elimina las notas más bajas de los controles o certámenes (por ejemplo, "se eliminan los 2 peores controles"), usa el selector **"Descartar peores"** dentro de esa sección y elige cuántas. La calculadora las tacha automáticamente y las excluye del cálculo.

### 4. Mira tu promedio mientras vas avanzando

No necesitas completar todo para ver un número: en la tabla aparece un **promedio parcial** (en amarillo, con la etiqueta "parcial") que se va actualizando con cada nota que ingresas, tratando lo que aún no has rendido como si fuera 0 — así ves el peor escenario posible y cómo mejora a medida que subes notas reales.

### 5. Revisa cuánto te falta para aprobar

La columna **"Necesita para pasar"** te muestra la nota mínima que debes obtener en lo que te queda pendiente para que el ramo quede aprobado (54,5 o más). Si dice "Imposible", significa que ya no hay forma de aprobar ese ramo este semestre.

---

## 💾 Sobre el guardado de tus notas

Tus datos se guardan automáticamente en el **almacenamiento local de tu navegador** (`localStorage`), no en un servidor ni en este repositorio. Esto significa:

- ✅ Nadie más puede ver tus notas — son privadas, solo viven en tu navegador.
- ✅ No necesitas registrarte ni iniciar sesión.
- ✅ Si la calculadora se actualiza más adelante (por ejemplo, se agrega una sección nueva), tus notas existentes no se borran.
- ⚠️ Si entras desde otro computador, otro navegador, o en modo incógnito, no vas a ver las notas que guardaste antes — quedaron en el dispositivo donde las ingresaste.
- 🗑️ Puedes borrar todo lo guardado con el botón **"Borrar mis datos"** en la esquina superior derecha, si quieres empezar de cero.

---

## ⚠️ Importante

Esta calculadora es una **herramienta de apoyo no oficial**, hecha por un estudiante para estudiantes. Los nombres de los ramos están tomados de la malla publicada por la USM, pero ante cualquier duda sobre ponderaciones, fechas o reglamento, siempre prevalece lo que indique tu profesor y la información oficial de la universidad. Cualquier comentario de mejora o duda sobre el uso de la pagina escribir a mi correo
jmartinezla@usm.cl

