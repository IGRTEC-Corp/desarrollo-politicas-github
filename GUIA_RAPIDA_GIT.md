# Guía rápida de Git para confirmar la política

Esta guía resume los comandos básicos para completar la confirmación de política GitHub.

Reemplaza los valores de ejemplo por tu nombre y el enlace real del repositorio.

## 1. Clonar el repositorio

```bash
git clone https://github.com/IGRTEC-Corp/desarrollo-politicas-github.git
cd desarrollo-politicas-github
```

## 2. Crear una rama

```bash
git checkout -b confirmacion/nombre-apellido
```

Ejemplo:

```bash
git checkout -b confirmacion/juan-perez
```

## 3. Crear archivo de confirmación

Copiar la plantilla:

```bash
cp confirmaciones/plantilla-confirmacion.md confirmaciones/juan-perez.md
```

En Windows PowerShell también puedes usar:

```powershell
Copy-Item confirmaciones/plantilla-confirmacion.md confirmaciones/juan-perez.md
```

Luego edita el archivo creado y completa los datos solicitados.

## 4. Revisar cambios

```bash
git status
```

## 5. Agregar cambios

```bash
git add confirmaciones/juan-perez.md
```

## 6. Crear commit

```bash
git commit -m "Agregar confirmación de Juan Pérez"
```

## 7. Subir la rama

```bash
git push origin confirmacion/juan-perez
```

## 8. Crear Pull Request

Desde GitHub, abre un Pull Request desde la rama creada hacia `main`.

Completa la plantilla del Pull Request y espera revisión.

## Comandos útiles

Ver rama actual:

```bash
git branch
```

Ver archivos modificados:

```bash
git status
```

Traer últimos cambios de `main`:

```bash
git checkout main
git pull origin main
```

## Importante

No hacer push directo a `main`.

El objetivo de esta prueba es validar que sabes trabajar con ramas, commits, push y Pull Requests.
