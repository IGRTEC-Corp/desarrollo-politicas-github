# Guía de revisión de confirmaciones

Este documento es para owners, líderes técnicos o responsables de revisar los Pull Requests de confirmación.

## Objetivo de la revisión

Validar que el colaborador entiende y puede ejecutar el flujo básico de trabajo con GitHub antes de recibir acceso de escritura a repositorios reales.

## Qué revisar en el Pull Request

Aprobar únicamente si cumple con lo siguiente:

- El colaborador creó una rama propia.
- La rama usa el formato `confirmacion/nombre-apellido`.
- Agregó un archivo propio dentro de `confirmaciones/`.
- No modificó archivos de otros colaboradores.
- No modificó archivos innecesarios.
- El archivo de confirmación incluye nombre, usuario GitHub y fecha.
- El archivo incluye el texto obligatorio de confirmación.
- El mensaje de commit es claro.
- La descripción del Pull Request es entendible.
- El checklist del Pull Request fue completado.
- No subió credenciales, tokens, contraseñas ni información sensible.

## Cuándo pedir cambios

Solicitar cambios si ocurre alguno de estos casos:

- El archivo fue creado fuera de la carpeta `confirmaciones/`.
- El archivo no tiene el nombre correcto.
- Modificó documentos principales sin autorización.
- El Pull Request no tiene descripción.
- El mensaje de commit no es claro.
- No incluyó el texto obligatorio de confirmación.
- El colaborador no parece entender qué hizo.

## Cuándo no aprobar

No aprobar si:

- Intentó hacer cambios directos sobre `main`.
- Subió archivos temporales, binarios o innecesarios.
- Subió información sensible.
- Modificó confirmaciones de otros colaboradores.
- El cambio no corresponde al proceso de confirmación.

## Comentario sugerido para aprobar

```text
Confirmación revisada y aprobada.

El colaborador completó correctamente el flujo de rama, commit, push y Pull Request, y confirmó que entiende la política interna de uso de GitHub.
```

## Comentario sugerido para pedir cambios

```text
Gracias por enviar la confirmación.

Antes de aprobar, por favor corrige lo siguiente:

- [indicar ajuste requerido]

Luego vuelve a solicitar revisión.
```
