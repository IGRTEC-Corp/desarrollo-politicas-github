# Políticas de GitHub - Área de Desarrollo

Este repositorio contiene las reglas internas de uso de GitHub para el área de Desarrollo.

Su objetivo es asegurar que todos los colaboradores comprendan y apliquen el flujo correcto de trabajo antes de recibir acceso de escritura a repositorios reales.

## Regla principal

Ningún colaborador debe hacer commits, push o cambios directos sobre las ramas `main` o `master`.

Todo cambio debe realizarse mediante una rama de trabajo y un Pull Request.

## Flujo obligatorio

1. Clonar el repositorio asignado.
2. Crear una rama nueva desde `main` o `master`.
3. Realizar los cambios en la rama creada.
4. Hacer commits con mensajes claros y descriptivos.
5. Subir la rama a GitHub.
6. Crear un Pull Request hacia la rama principal.
7. Explicar claramente los cambios realizados.
8. Esperar revisión y aprobación antes de hacer merge.

## Confirmación obligatoria

Antes de recibir acceso de escritura a repositorios reales, cada colaborador debe confirmar que leyó y entendió esta política.

La confirmación debe hacerse mediante un Pull Request en este repositorio.

Ver instrucciones en:

`PROCESO_CONFIRMACION.md`

## Documentos principales

- `POLITICA_GITHUB.md`: reglas internas de uso de GitHub.
- `PROCESO_CONFIRMACION.md`: pasos para confirmar la política.
- `GUIA_RAPIDA_GIT.md`: comandos básicos para completar la prueba.
- `GUIA_REVISION_CONFIRMACIONES.md`: criterios para revisar y aprobar confirmaciones.
- `CHECKLIST_ONBOARDING.md`: checklist para nuevos colaboradores.
- `CONFIGURACION_REPOSITORIO.md`: configuración recomendada del repositorio.
- `confirmaciones/`: carpeta donde cada colaborador agrega su confirmación.
- `teams/`: publicaciones sugeridas para Microsoft Teams.

## Canal de dudas

Las dudas sobre este proceso deben hacerse en Microsoft Teams, canal:

`02 - GitHub y repositorios`

## Importante

Este repositorio no debe contener código productivo, credenciales, tokens, contraseñas, cadenas de conexión reales, información sensible de clientes ni datos productivos.
