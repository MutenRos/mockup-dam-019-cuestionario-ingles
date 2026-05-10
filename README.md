# 019 -- Cuestionario online de ingles

> Proyecto 019 del bloque DAM 1.o - 3.a evaluacion. Esta es **nuestra version**: la del enunciado de Jocarsa **completada y ampliada**.

## Descripcion

Plataforma de cuestionarios de ingles con correccion automatica y puntuacion.

**Stack tecnologico:** HTML Â· CSS Â· JavaScript Â· JSON

**Punto de entrada:** `001-leer csv.php` (PHP)

## Como ejecutar

```ash
php -S localhost:8000
# luego abre http://localhost:8000/001-leer csv.php
```

## Estructura

- [FILE] `001-leer csv.php`
- [FILE] `002-crear el formulario.php`
- [FILE] `003-ahora las preguntas.php`
- [FILE] `004-preguntas iniciales.php`
- [FILE] `005-estilo.php`
- [FILE] `006-guardar y evaluar.php`
- [FILE] `admin.php`
- [FILE] `README.md`
- [FILE] `test_nivel.sqlite`

## Mejoras respecto a la version original

Banco de preguntas externalizado, niveles A1-C1 y feedback por pregunta.

Cambios transversales aplicados a todas las versiones nuestras:

- Limpieza de archivos temporales y artefactos pesados (node_modules, binarios, .blend recompilables).
- README profesional documentando ejecucion y estructura.
- Publicacion como repositorio independiente y mockup en GitHub Pages para captura de evidencias.

## Enlaces

| Recurso | URL |
|---------|-----|
| Repositorio (codigo) | <https://github.com/MutenRos/dam-019-cuestionario-ingles> |
| Repositorio mockup | <https://github.com/MutenRos/mockup-dam-019-cuestionario-ingles> |
| GitHub Pages (demo) | <https://mutenros.github.io/mockup-dam-019-cuestionario-ingles/> |

## Variantes del proyecto

Este proyecto se entrega en tres carpetas:

| # | Carpeta | Que es |
|---|---------|--------|
| 1 | `1-jocarsa-intacta/` | Version del profesor sin tocar (referencia). |
| 2 | `2-nuestra-version/` | **Esta carpeta**: nuestra version completada y mejorada. |
| 3 | `3-mockup-pages/` | Mockup estatico publicado en GitHub Pages para capturas/grabacion. |

---

_Ultima actualizacion: 2026-05-07_
