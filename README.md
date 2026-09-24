# Construcción histórica de las infancias

Página web colaborativa del curso **Infancias: Historias y Perspectivas** (código 514517) de la **Universidad Nacional Abierta y a Distancia (UNAD)**, Escuela de Ciencias de la Educación.

El sitio documenta el análisis del grupo sobre las transformaciones históricas, sociales y culturales que han moldeado la manera de comprender a los niños, las niñas y las infancias. Se construye de forma progresiva: en cada reto del curso se incorporan nuevas evidencias y reflexiones.

🔗 **Sitio publicado:** `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`

---

## Contenido

La página se organiza en cuatro pestañas, una por reto:

| Pestaña | Título | Estado |
|---|---|---|
| I | Construcción histórica de las infancias | ✅ Disponible |
| II | Infancias en perspectiva | 🚧 Reto 3 (pendiente) |
| III | Comprendiendo las realidades y desafíos de las infancias | 🚧 Reto 4 (pendiente) |
| IV | Voces para la transformación de las infancias | 🚧 Reto 5 (pendiente) |

### Reto 2: línea de tiempo interactiva

Recorre tres periodos históricos. Cada uno incluye contexto social, contexto cultural, concepciones de niño, niña y niñez, autores y aportes, hitos relevantes y una reflexión crítica:

- **Edad Antigua** (siglo VIII a.C. – 476 d.C.)
- **Edad Media** (476 – 1453 d.C.)
- **Edad Moderna** (siglos XV – XVIII)

La pestaña termina con una conclusión y las referencias bibliográficas en formato APA.

### Integrantes

La sección de equipo muestra una tarjeta por integrante, con foto, nombre, descripción y el rol asignado en el curso:

- Dinamizador del proceso
- Relator
- Utilero
- Veedor de la autenticidad
- Evaluador

---

## Estructura del repositorio

```
.
├── index.html   # Página completa (HTML, CSS y JavaScript en un solo archivo)
└── README.md    # Este archivo
```

No requiere instalación, compilación ni dependencias. La única conexión externa es la carga de las tipografías **Cormorant Garamond** y **Karla** desde Google Fonts.

## Uso local

1. Descarga o clona el repositorio.
2. Abre `index.html` con doble clic en cualquier navegador moderno.

```bash
git clone https://github.com/TU-USUARIO/NOMBRE-DEL-REPOSITORIO.git
cd NOMBRE-DEL-REPOSITORIO
```

---

## Modo de edición

La página incluye un editor integrado, accesible desde la barra inferior:

- **✎ Editar página:** activa la edición directa de cualquier texto, incluidos nombres, roles, descripciones y referencias. En la lista de referencias, `Enter` añade una nueva.
- **Foto de integrante:** en modo edición, el botón ✎ sobre cada avatar permite subir una imagen (se recorta y comprime automáticamente).
- **💾 Guardar borrador:** guarda los cambios en el navegador (`localStorage`).
- **⬇ Descargar página final:** genera un HTML limpio, sin modo edición, con todos los cambios incluidos.
- **Salir sin guardar:** cierra el modo edición.

> ⚠️ **Importante:** el borrador se guarda solo en el navegador de quien edita, no en el repositorio. Para que los cambios se vean en el sitio publicado, hay que **descargar la página final** y reemplazar el `index.html` del repositorio.

## Publicar en GitHub Pages

1. **Renombra el archivo.** Cambia `Construcción_histórica_de_las_infancias.html` por **`index.html`** (en minúsculas, sin tildes ni espacios). GitHub Pages busca ese nombre para mostrar la página principal.
2. **Crea un repositorio** en GitHub (por ejemplo, `infancias-historia`) y déjalo como **Public**.
3. **Sube los archivos** `index.html` y `README.md`, desde el botón *Add file → Upload files* o con Git:
   ```bash
   git init
   git add index.html README.md
   git commit -m "Publicación inicial del sitio"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/NOMBRE-DEL-REPOSITORIO.git
   git push -u origin main
   ```
4. Ve a **Settings → Pages**.
5. En *Build and deployment*, elige **Source: Deploy from a branch**, selecciona la rama **main** y la carpeta **/ (root)**, y pulsa **Save**.
6. Espera uno o dos minutos. El sitio quedará disponible en:
   `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`

### Actualizar el sitio

Cada vez que tengas una versión nueva (por ejemplo, al completar el Reto 3), descarga la página final desde el editor, renómbrala a `index.html` y súbela al repositorio reemplazando la anterior. GitHub Pages se actualiza solo.

---

## Tecnologías

- HTML5, CSS3 y JavaScript vanilla
- Google Fonts (Cormorant Garamond y Karla)
- GitHub Pages para el alojamiento

## Referencias principales

- Ariès, P. (1987). *El niño y la vida familiar en el Antiguo Régimen*. Taurus.
- Benchimol, K., et al. (2023). *Infancias en plural*. Universidad Nacional General de Sarmiento.
- Chica, F., & Rasero, L. (2012). Construcción social de la infancia y el reconocimiento de sus competencias. *Itinerario Educativo*, 26(60), 75–96.
- Locke, J. (1990). *Pensamientos sobre la educación*. Akal. (Obra original de 1693).
- Pedraza Ramírez, C. E., et al. (2022). *Representaciones sobre la educación infantil: Infancias en contingencia*. Sello Editorial UNAD.
- Rousseau, J. J. (1990). *Emilio, o de la educación*. Alianza Editorial. (Obra original de 1762).

La lista completa con enlaces está en la pestaña I del sitio.

## Autores

Grupo colaborativo del curso *Infancias: Historias y Perspectivas*, UNAD.

<!-- Reemplaza con los nombres reales del grupo -->
- Nombre del integrante 1 – Dinamizador del proceso
- Nombre del integrante 2 – Relator
- Nombre del integrante 3 – Utilero
- Nombre del integrante 4 – Veedor de la autenticidad
- Nombre del integrante 5 – Evaluador

## Nota académica

Este sitio es un producto académico elaborado con fines educativos en el marco del curso 514517 de la UNAD.
