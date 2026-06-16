# Proceso de confirmación de política GitHub

Antes de recibir acceso de escritura a repositorios reales, cada colaborador debe confirmar que leyó y entendió la política interna de GitHub.

La confirmación debe hacerse mediante un Pull Request en este repositorio.

## Pasos

1. Leer el archivo `POLITICA_GITHUB.md`.

2. Clonar este repositorio.

3. Crear una rama nueva usando el formato:

```text
confirmacion/nombre-apellido
```

Ejemplo:

```text
confirmacion/juan-perez
```

4. Copiar el archivo:

```text
confirmaciones/plantilla-confirmacion.md
```

5. Crear un nuevo archivo dentro de la carpeta `confirmaciones/`.

El nombre del archivo debe tener este formato:

```text
nombre-apellido.md
```

Ejemplo:

```text
confirmaciones/juan-perez.md
```

6. Completar los datos solicitados.

7. Hacer commit con un mensaje claro.

Ejemplo:

```text
Agregar confirmación de Juan Pérez
```

8. Subir la rama a GitHub.

9. Crear un Pull Request hacia `main`.

10. Completar el checklist del Pull Request.

11. Esperar revisión y aprobación.

## Texto obligatorio de confirmación

El archivo debe incluir el siguiente texto:

```text
Confirmo que leí y entiendo que no debo hacer commits directos a main/master y que todo cambio debe ir por Pull Request.
```

## Criterio de aprobación

La confirmación será aprobada si:

- La rama fue creada correctamente.
- El archivo de confirmación fue agregado en la carpeta correcta.
- El Pull Request tiene una descripción clara.
- No se hicieron cambios innecesarios.
- No se hizo commit directo sobre `main`.
- El colaborador siguió el flujo indicado.
- No se subió información sensible.

## Canal de dudas

Si tienes dudas sobre el proceso, usa el canal de Teams:

`02 - GitHub y repositorios`
