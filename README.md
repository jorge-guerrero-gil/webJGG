# Proyecto Web: Leyendas del Atlético de Madrid

Este proyecto ha sido desarrollado para la asignatura de **Fundamentos de la Ingeniería Informática (FII)** en la Universidad Francisco de Vitoria.

## 1. Descripción del Trabajo
El sitio web es una enciclopedia digital dedicada a las figuras más emblemáticas del Atlético de Madrid. El objetivo es combinar la pasión por el club con la aplicación práctica de conceptos de desarrollo web (HTML5 y CSS3) y control de versiones (Git/GitHub).

### Estructura del Proyecto:
- **Inicio:** Introducción al tema colchonero.
- **Sobre mí:** Información personal y CV del autor.
- **Grandes Mitos:** Sección temática dedicada a Luis Aragonés.
- **Contacto:** Formulario de sugerencias para la comunidad.
- **Sección Académica:** Detalle del grado y exploración profunda de la materia FII.

## 2. Problemas durante el Desarrollo
Durante la creación del proyecto, se enfrentaron los siguientes retos técnicos:
- **Gestión de rutas con Git:** Al mover la carpeta del proyecto dentro de OneDrive, el índice de Git se desincronizó, detectando archivos borrados que en realidad seguían existiendo. Se solucionó re-inicializando el repositorio y usando `git add -A`.
- **Nomenclatura de ramas:** Hubo una discrepancia entre la rama local (`master`) y la remota en GitHub (`main`). Se resolvió renombrando la rama local para que coincidiera con el estándar actual.
- **Rutas Relativas:** Configurar correctamente los enlaces `../` para que el CSS y la navegación funcionen tanto desde la raíz como desde la carpeta `publica/`.

## 3. Conclusiones
El desarrollo de este trabajo práctico ha permitido afianzar los conocimientos sobre la jerarquía de archivos en un servidor web y la importancia de un flujo de trabajo ordenado en Git. La separación de contenidos en la carpeta `publica/` y el uso de un CSS común garantiza un mantenimiento más sencillo del sitio en el futuro.

---
**Autor:** Jorge Guerrero Gil
**Grado:** Ingeniería Informática - UFV