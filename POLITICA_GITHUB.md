# Política interna de uso de GitHub

## Objetivo

Mantener el orden, trazabilidad y seguridad en los repositorios del área de Desarrollo, evitando cambios directos en ramas principales y asegurando que todo cambio sea revisado antes de integrarse.

## Regla principal

Ningún colaborador debe hacer commits directos, push directo o modificaciones directas sobre las ramas `main` o `master`.

Todo cambio debe realizarse mediante una rama de trabajo y un Pull Request.

## Flujo obligatorio de trabajo

1. Crear una rama desde `main` o `master`.
2. Realizar los cambios en esa rama.
3. Hacer commits con mensajes claros.
4. Subir la rama a GitHub.
5. Crear un Pull Request hacia la rama principal.
6. Explicar qué se modificó y por qué.
7. Esperar revisión.
8. Corregir observaciones si aplica.
9. Esperar aprobación antes de hacer merge.

## Formato recomendado para ramas

Usar nombres claros y descriptivos:

```text
feature/nombre-cambio
fix/nombre-correccion
docs/nombre-documentacion
test/nombre-prueba
confirmacion/nombre-apellido
```

Ejemplos:

```text
feature/login-usuarios
fix/error-consulta-clientes
docs/actualizar-readme
confirmacion/juan-perez
```

## Reglas para commits

Los commits deben tener mensajes claros y descriptivos.

Ejemplos correctos:

```text
Agregar confirmación de Juan Pérez
Actualizar guía de Pull Requests
Corregir instrucciones de clonación
```

Ejemplos incorrectos:

```text
cambios
update
prueba
final
varios
```

## Reglas para Pull Requests

Todo Pull Request debe incluir:

- Descripción breve del cambio.
- Motivo del cambio.
- Archivos modificados.
- Evidencia de prueba, cuando aplique.
- Comentarios importantes para el revisor, si existen.

## No está permitido

- Hacer push directo a `main` o `master`.
- Hacer merge sin revisión.
- Subir credenciales, tokens o contraseñas.
- Subir cadenas de conexión reales.
- Subir archivos temporales o generados innecesariamente.
- Subir archivos `.zip`, `.rar`, `.exe`, `bin/`, `obj/`, `.vs/` o similares.
- Modificar archivos fuera del alcance de la tarea asignada sin autorización.
- Subir información sensible de clientes, usuarios o ambientes productivos.

## Archivos sensibles

Nunca se deben subir archivos que contengan:

- Contraseñas.
- Tokens.
- API keys.
- Llaves privadas.
- Certificados privados.
- Cadenas de conexión reales.
- Información sensible de clientes.
- Datos productivos.

## Excepciones

Solo los owners o responsables técnicos autorizados pueden hacer cambios directos a ramas principales en casos excepcionales, como correcciones urgentes o tareas administrativas.

Toda excepción debe ser justificada y comunicada al responsable del área.

## Incumplimiento

Si un colaborador incumple esta política, su acceso podrá ser limitado temporalmente hasta reforzar el proceso correcto de trabajo.

El objetivo de esta política no es sancionar, sino proteger los repositorios, mantener trazabilidad y evitar cambios no revisados.
