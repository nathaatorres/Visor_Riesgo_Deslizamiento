# Visor de Riesgo por Deslizamiento — Armenia, Quindío

Visor web geoespacial desarrollado como parte del trabajo de **Gestión del Riesgo** de la Universidad del Quindío.

## ¿Qué permite hacer?

- Consultar cualquier predio por su **cédula catastral** (número predial de 30 dígitos)
- Visualizar si la construcción está en zona de **amenaza alta o media** por deslizamiento
- Ver la distribución espacial de las construcciones en riesgo sobre el mapa

## Datos

| Archivo | Descripción |
|---|---|
| `datos/lookup.json` | Tabla de consulta: cédula catastral → nivel de amenaza |
| `datos/riesgo.geojson` | Geometrías de construcciones en zona de deslizamiento |

Fuente: **SIG Quindío** · Capa de amenaza por deslizamiento

## Instrucciones para publicar en GitHub Pages

1. Crea un repositorio en GitHub (puede ser público)
2. Sube todos los archivos de esta carpeta al repositorio
3. Ve a **Settings → Pages**
4. En "Source" selecciona `main` branch y carpeta `/ (root)`
5. Guarda — en unos minutos el visor estará disponible en `https://tu-usuario.github.io/nombre-repo/`

## Estructura de archivos

```
visor-riesgo/
├── index.html              ← Visor principal
├── logo_uniquindio.png     ← Logo Universidad del Quindío
├── README.md               ← Este archivo
└── datos/
    ├── lookup.json         ← 4.5 MB — tabla de cédulas
    └── riesgo.geojson      ← 2.0 MB — geometrías en riesgo
```

## Universidad del Quindío · 2026
