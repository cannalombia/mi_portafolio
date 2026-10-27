# Backlog de mi-portafolio

Este archivo es el **plan** del proyecto. Cada historia de usuario (HU) de aquí
se convierte en un **issue** en GitHub, se pone en el **tablero** de GitHub
Projects y se cierra con un **commit** que diga `closes #número`.

Formato de cada criterio de aceptación:

> `- [ ] Dado <contexto>, cuando <acción>, entonces <resultado esperado>.`

Cuando crees el issue en GitHub, escribe su número en la línea **Issue:**
(por ejemplo `**Issue:** #4`).

---

## HU-01 · Menú de navegación fijo  ✅ (ejemplo resuelto)

**Historia:** Como visitante del portafolio, quiero un menú fijo en la parte superior, para ir a cualquier sección sin hacer scroll.

**Etiquetas:** historia, frontend, prioridad-alta · **Estimación:** S

**Criterios de aceptación:**

- [ ] Dado que abro el portafolio, cuando miro la parte superior, entonces veo un menú con enlaces a "Sobre mí", "Proyectos" y "Contacto".
- [ ] Dado que estoy en la parte de arriba, cuando hago clic en "Proyectos", entonces la página baja hasta la sección de proyectos.
- [ ] Dado que hice scroll hasta el final, cuando miro la parte superior de la pantalla, entonces el menú sigue visible.

**Issue:** #1

---

## HU-02 · Sección de habilidades  ✅ (ejemplo resuelto)

**Historia:** Como reclutador, quiero ver las habilidades técnicas del aprendiz en una lista, para evaluar rápidamente si su perfil encaja con la vacante.

**Etiquetas:** historia, frontend · **Estimación:** S

**Criterios de aceptación:**

- [ ] Dado que abro el portafolio, cuando llego a la sección "Habilidades", entonces veo al menos 6 habilidades técnicas.
- [ ] Dado que estoy en la sección "Habilidades", cuando la leo, entonces las habilidades están agrupadas en "Frontend" y "Herramientas".
- [ ] Dado que estoy en el menú, cuando hago clic en "Habilidades", entonces la página baja hasta esa sección.

**Issue:** #2

---

## HU-03 · Pie de página con redes

**Historia:** Como visitante, quiero un pie de página con el año y los enlaces a las redes del aprendiz, para contactarlo desde cualquier parte de la página.

**Etiquetas:** historia, frontend · **Estimación:** S

**Criterios de aceptación:**

- [ ] Dado que ingreso al portafolio, cuando llego al final de la página, entonces puedo ver el pie de página.
- [ ] Dado que estoy en el pie de página, cuando reviso su contenido, entonces puedo ver el año actual.
- [ ] Dado que estoy en el pie de página, cuando hago clic en un enlace de una red social, entonces se abre la página correspondiente.


**Issue:** #3

---

## HU-04 · Enlace al repositorio en cada proyecto

**Historia:** Como reclutador, quiero que cada tarjeta de proyecto tenga un enlace a su repositorio en GitHub, para revisar el código que escribió el aprendiz.

**Etiquetas:** historia, frontend · **Estimación:** S

**Criterios de aceptación:**
- [ ] Dado que ingreso al portafolio, cuando reviso la sección de proyectos, entonces veo un enlace a GitHub en cada tarjeta.
- [ ] Dado que estoy viendo un proyecto, cuando hago clic en su enlace de GitHub, entonces el repositorio se abre en una pestaña nueva.
- [ ] Dado que estoy en la sección de proyectos, cuando reviso los enlaces, entonces cada uno muestra el texto "Ver repositorio".


**Issue:** #4

---

## HU-05 · Portafolio adaptable al celular

**Historia:** Como visitante que usa el celular, quiero que el portafolio se vea bien en pantallas pequeñas, para leerlo sin hacer zoom ni scroll horizontal.

**Etiquetas:** historia, frontend, prioridad-alta · **Estimación:** M

**Criterios de aceptación:**

- [ ] Dado que ingreso al portafolio desde un celular, cuando se carga la página, entonces puedo leer el contenido sin hacer zoom.
- [ ] Dado que estoy usando una pantalla de menos de 600 px, cuando reviso la sección de proyectos, entonces las tres tarjetas se muestran una debajo de otra.
- [ ] Dado que navego por el portafolio desde el celular, cuando me desplazo por las secciones, entonces no aparece desplazamiento horizontal.

**Issue:** #5

---

## HU-06 · Descargar hoja de vida

**Historia:** Como reclutador, quiero poder descargar la hoja de vida del aprendiz desde su portafolio, para conocer mejor su perfil y formación.

**Etiquetas:** historia, frontend · **Estimación:** S

**Criterios de aceptación:**

- [ ] Dado que ingreso al portafolio, cuando reviso la información del aprendiz, entonces puedo ver un botón para descargar su hoja de vida.
- [ ] Dado que encuentro el botón de descarga, cuando hago clic en él, entonces se descarga la hoja de vida en formato PDF.
- [ ] Dado que termina la descarga, cuando abro el archivo PDF, entonces puedo consultar la información del aprendiz correctamente.

**Issue:** #6
