# Cultura de la Paz — Protocolos de Seguridad (CE43)

Aplicación web **autocontenida, sin dependencias externas y funcional sin internet** para uso interno de planteles federales de Educación Media Superior.

Basada en el documento **"Protocolos de Seguridad para los Planteles Federales de Educación Media Superior"** (SEP, Subsecretaría de Educación Media Superior, 2023), con números de emergencia verificados del Estado de Morelos.

## Contenido

- Pantalla de inicio con 10 tipos de contingencia (pasos de Actuación y Seguimiento)
- Botón directo de llamada al 911
- Semáforo / Código de Seguridad (verde, amarillo, rojo)
- Directorio de Emergencias editable (Morelos)
- Directorio de la Red de Seguridad del plantel
- Cédula del Estudiante (Anexo SEP 2023): guardado local + exportación a CSV
- Bitácora de Seguridad con exportación a CSV para reporte semestral
- Paleta guinda/blanco institucional, diseño móvil tipo "modo emergencia"

## Uso

1. Abrir `index.html` en cualquier navegador (idealmente Chrome en Android).
2. En Android: menú ⋮ → **Agregar a pantalla de inicio**.
3. Los datos (cédulas, bitácora, directorios) se guardan **solo en el dispositivo** (localStorage). No se envía información a ningún servidor.

## ⚠️ Aviso de privacidad

Este repositorio contiene solo el código de la aplicación. **Nunca subas** archivos CSV exportados con datos personales de estudiantes ni del personal.

## GitHub Pages

El sitio se publica automáticamente en: `https://enkialvarez.github.io/culturapazce43/`
