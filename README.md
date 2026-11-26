# Valentino Dorrego

Analista funcional y desarrollador de software. Convierto procesos de negocio en requerimientos verificables y en software que los cumple.

## Qué hago

- **Análisis funcional** — relevamiento con usuarios, modelado de procesos AS-IS / TO-BE en BPMN, análisis de brechas y definición de alcance.
- **Ingeniería de requerimientos** — especificaciones (SRS), historias de usuario con criterios de aceptación en Gherkin, reglas de negocio y matrices de trazabilidad.
- **Desarrollo** — aplicaciones web full-stack y automatización de procesos e infraestructura de reportes: integración de datos, flujos en Power Automate y modelos para Power BI.

turnos-consultorio y solicitudes-it documentan esa cadena completa en su carpeta `/docs`: cada requisito tiene un ID, una o más historias que lo cubren, los tests que lo verifican y el código que lo implementa.

## Proyectos

| Proyecto | Problema | Qué demuestra | Stack |
|---|---|---|---|
| [**pricevision**](https://github.com/tinodorrego/pricevision) | Encontrar dónde se vende un producto que se ve en una foto, a qué precio y en qué talles, sin revisar cada tienda por separado. | SRS con criterios de aceptación → arquitectura → código: comparación de imágenes con CLIP en la propia computadora, resultados de tres tiendas online con precio, talles y enlace, 108 tests y una evaluación del ranking que también documenta lo que no funcionó. [Ver documentación](https://github.com/tinodorrego/pricevision/tree/main/docs) | Python, FastAPI, DuckDB, OpenCLIP, JavaScript, pytest |
| [**turnos-consultorio**](https://github.com/tinodorrego/turnos-consultorio) | Un consultorio de salud que daba turnos por WhatsApp y cuaderno: el paciente no veía la disponibilidad y no había forma simple de cancelar. | Relevamiento → SRS → diseño UX/UI → código: reserva con interfaz de almanaque de farmacia, sin dobles reservas aunque dos personas confirmen a la vez, comprobante con cancelación, panel con ocupación y ausentismo, y un plan de validación con usuarios. [Ver documentación](https://github.com/tinodorrego/turnos-consultorio/tree/main/docs) | Next.js, TypeScript, Tailwind, PostgreSQL, Drizzle, Vitest |
| [**solicitudes-it**](https://github.com/tinodorrego/solicitudes-it) | Las solicitudes internas a IT llegaban por mail y chat, sin prioridad, plazo ni seguimiento. | Relevamiento → SRS → historias con Gherkin → código: ciclo de vida con permisos por rol, seguimiento, SLA calculado por reglas documentadas, dashboard de indicadores y 49 tests que citan el ID de cada requisito. [Ver documentación](https://github.com/tinodorrego/solicitudes-it/tree/main/docs) | Next.js, TypeScript, Tailwind, PostgreSQL, Drizzle, Vitest |

## Stack

- **Frontend:** React, Next.js, TypeScript, Tailwind CSS
- **Backend y datos:** Node.js, Python, FastAPI, PostgreSQL, DuckDB, SQL
- **Automatización y reportes:** Power Automate, Power BI, integración de datos
- **Análisis y modelado:** BPMN, UML, diagramas entidad-relación, Mermaid, Gherkin
- **Herramientas:** Git, GitHub Actions, Vitest, pytest, Playwright

## Formación

proximo ingeniero de UADE

## Contacto

- LinkedIn: [linkedin.com/in/valentino-dorrego](https://www.linkedin.com/in/valentino-dorrego)
- Email: [valentinodorrego@gmail.com](mailto:valentinodorrego@gmail.com)
