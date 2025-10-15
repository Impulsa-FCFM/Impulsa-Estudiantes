# Impulsa-Estudiantes

Impulsa-Estudiantes es el repositorio público de la organización estudiantil **Impulsa**, orientado a los alumnos que cursan los Seminarios de Diseño e Innovación Tecnológica (EL4030, EL5030 y EL6030). Aquí encontrarás la documentación oficial, plantillas, registro de ideas y proyectos desarrollados bajo la metodología relámpago. Su propósito es servir como espacio colaborativo para aprender, innovar y crear soluciones tecnológicas con impacto real.

## Cómo está organizado

La estructura del repositorio agrupa documentación transversal para estudiantes, proyectos por curso y un registro de ideas. Además, incluye la carpeta `docs`, desde la cual se publica el portal web mediante GitHub Pages.


## Cómo usar este espacio

Cada equipo debe crear su carpeta dentro del curso correspondiente e incluir un `README.md` con propósito, alcance, integrantes y plan de hitos. La documentación viva se mantiene en `docs/` y el código o prototipo en `src/`.  
Las ideas iniciales se registran en `ideas/registro_YYYY.md` indicando autor, problema, propuesta y estado. Cuando una idea evoluciona a proyecto, se mueve a la carpeta del curso correspondiente.

## Flujo de trabajo y ramas

El trabajo se organiza con una rama principal `main` y ramas breves por tarea o mejora, siguiendo prefijos que indiquen el curso, por ejemplo `EL4030/feature-monitor-energia`.  
Cada cambio debe registrarse mediante un **Pull Request**, explicando qué se hizo y por qué. Las tareas se gestionan con **Issues** usando etiquetas claras como `tipo:feature`, `curso:EL5030` o `prio:alta`.

## Metodología relámpago

La **metodología relámpago** guía a los equipos desde la identificación del problema hasta un PMV funcional, en ciclos cortos de validación.  
En `documentacion/metodologia_relampago.md` se describen las etapas, los entregables mínimos por sprint y los criterios de salida. Cada proyecto debe reflejar en su `README.md` el sprint en curso y su próximo hito.

## Convenciones y buenas prácticas

Usa Markdown con encabezados claros, tablas simples y nombres de archivo descriptivos (por ejemplo, `informe_`, `bitacora_`, `reporte_`). No subas archivos pesados ni datos personales; si un proyecto requiere datos, documenta la fuente y utiliza ejemplos mínimos o scripts de descarga.  
Las decisiones relevantes se documentan en la carpeta `docs/` del proyecto, en archivos tipo `adr-0001-eleccion-stack.md`.

## Plantillas disponibles

En `documentacion/plantillas/` encontrarás formatos para informes, bitácoras y reportes de avance. Solo debes copiar la plantilla al proyecto, completarla y mantener los cambios versionados con commits pequeños y descriptivos.  

---

🔗 Para más información sobre el funcionamiento interno del equipo y coordinación general, revisa el repositorio privado **ImpulsaHub** (acceso exclusivo para tutores y coordinadores).
