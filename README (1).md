# 🎓 Calculadora de Notas — Ingeniería Civil en Biotecnología USM

Calculadora web para llevar el control de tus notas durante la carrera. Tú armas tus propios semestres con los ramos que realmente estás cursando, ingresas las evaluaciones de cada uno (certámenes, controles, tareas, laboratorio y certamen global) y la calculadora te dice **cuánto necesitas sacar en lo que falta para aprobar**.

Usa la escala de evaluación de la USM (0–100, aprobación con 54,5) y tus notas se guardan solas en tu navegador, sin necesidad de crear cuenta ni instalar nada.

🔗 **Link para usarla:** *(reemplaza esto con tu URL de GitHub Pages, ej. `https://tu-usuario.github.io/nombre-del-repo/`)*

---

## 📖 Cómo usarla

### 1. Arma tus propios semestres

A diferencia de una malla fija, aquí **tú decides** qué semestres tienes y qué ramos va en cada uno:

- Empiezas con un **Semestre 1** vacío.
- Para crear más semestres, haz clic en el botón verde **"+ Nuevo"** que aparece en la barra de pestañas (al lado de "Sem 1", "Sem 2", etc.) — te lleva directo al semestre recién creado.
- También puedes eliminar un semestre completo con el botón rojo **"🗑 Eliminar Semestre"** al fondo de cada uno.

### 2. Agrega ramos a un semestre

Dentro de cada semestre hay una sección **"➕ Agregar ramo a este semestre"** con dos formas de hacerlo:

- **Desde el banco de ramos**: un desplegable con los ramos típicos de la carrera (nombre, sigla y créditos ya cargados). Eliges uno y tocas "+ Agregar del banco".
- **Ramo personalizado**: si no está en el banco (un electivo, un ramo de otra carrera, etc.), escribes el nombre, opcionalmente una sigla, y los créditos, y tocas "+ Agregar".

Para quitar un ramo de un semestre, usa el botón **×** junto a su fila en la tabla. Esto no borra tus notas — si vuelves a agregar el mismo ramo más adelante, las recuperas.

### 3. Abre un ramo para ingresar notas

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

### 4. Descarta tus peores notas (si tu ramo lo permite)

Si tu profesor elimina las notas más bajas de los controles o certámenes (por ejemplo, "se eliminan los 2 peores controles"), usa el selector **"Descartar peores"** dentro de esa sección y elige cuántas. La calculadora las tacha automáticamente y las excluye del cálculo.

### 5. Mira tu promedio mientras vas avanzando

No necesitas completar todo para ver un número: en la tabla aparece un **promedio parcial** (en amarillo, con la etiqueta "parcial") que se va actualizando con cada nota que ingresas, tratando lo que aún no has rendido como si fuera 0 — así ves el peor escenario posible y cómo mejora a medida que subes notas reales.

### 6. Revisa cuánto te falta para aprobar

La columna **"Necesita para pasar"** te muestra la nota mínima que debes obtener en lo que te queda pendiente para que el ramo quede aprobado (54,5 o más). Si dice "Imposible", significa que ya no hay forma de aprobar ese ramo este semestre.

### 7. Resumen general

La pestaña **📊 Resumen** muestra todos tus semestres con su avance y promedio de un vistazo, y desde ahí también puedes agregar un semestre nuevo.

---

## 💾 Sobre el guardado de tus datos

Tus **semestres, ramos y notas** se guardan automáticamente en el **almacenamiento local de tu navegador** (`localStorage`), no en un servidor ni en este repositorio. Esto significa:

- ✅ Nadie más puede ver tu información — es privada, solo vive en tu navegador.
- ✅ No necesitas registrarte ni iniciar sesión.
- ✅ Si la calculadora se actualiza más adelante (por ejemplo, se agrega una sección nueva), tus datos existentes no se borran.
- ⚠️ Si entras desde otro computador, otro navegador, o en modo incógnito, no vas a ver lo que guardaste antes — quedó en el dispositivo donde lo ingresaste.
- 🗑️ Puedes borrar todo lo guardado (semestres, ramos y notas) con el botón **"Borrar mis datos"** en la esquina superior derecha, si quieres empezar de cero.

---

## ⚠️ Importante

Esta calculadora es una **herramienta de apoyo no oficial**, hecha por estudiantes para estudiantes. El banco de ramos está tomado de la malla publicada por la USM como referencia, pero como tú armas tus propios semestres, eres libre de organizarlos como corresponda a tu situación real. Ante cualquier duda sobre ponderaciones, fechas o reglamento, siempre prevalece lo que indique tu profesor y la información oficial de la universidad.
