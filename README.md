# VetQR — Modelos UML

Repositorio académico de análisis y diseño orientado a objetos del sistema **VetQR**.

## Semana 15: diagramas de comunicación, secuencia y actividad

**Caso:** Un participante responde un cuestionario veterinario. El sistema valida que las respuestas obligatorias estén completas. Cuando lo están, registra las respuestas y muestra confirmación. Cuando faltan, informa los pendientes y termina sin guardar.

- **Comunicación:** participantes `pantalla`, `gestor` y `repositorio`; mensajes numerados 1, 1.1 y 1.2.
- **Secuencia:** los mismos participantes y mensajes en orden cronológico para la ruta exitosa.
- **Actividad:** rutas `[completas]` e `[incompletas]`.

## Organización

- `Modelos_XMI/`: archivos XMI de Semana 15, vista lógica y despliegue.
- `Diagramas/`: código PlantUML de los tres diagramas y una imagen de despliegue.
- `Documentacion/`: indicaciones de uso e importación.

## Enterprise Architect 15

Los archivos XMI son modelos de intercambio: **no son un repositorio nativo `.feap`** y su importación o presentación gráfica no se ha validado en Enterprise Architect 15. Para entregar `.feap`, se debe crear el proyecto en Enterprise Architect, importar los modelos que sean compatibles, revisar o dibujar los diagramas y guardar.
