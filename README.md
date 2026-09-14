# Mini campaña de monitoreo acústico

Este proyecto documenta una mini campaña de monitoreo acústico realizada en un parque Santa Inés, donde se grabo simultáneamente en tres puntos distintos para explorar si el paisaje sonoro varía según la ubicación. El objetivo es transformar esas grabaciones en un conjunto de datos organizado, trazable y analizable.

## 1. Pregunta

¿Varía el paisaje sonoro entre distintos puntos del parque?

## 2. Lugar

- **Lugar:** Parque Santa Inés, Valdivia
- **Por qué este lugar:** Se esperaba una alta diversidad sonora por la coexistencia de sonidos naturales y de tránsito vehicular, además de fácil acceso y espacio suficiente para ubicar puntos de monitoreo en distintos sectores.
- **Ambientes acústicos esperados:** Aves y sonidos de naturaleza en general, con mayor presencia de tráfico vehicular en el sector más cercano a la entrada del parque.
- **Fuentes sonoras esperadas:**
  - Biofonía: aves, otros sonidos de fauna.
  - Geofonía: viento y árboles.
  - Antropofonía: tráfico vehicular y personas caminando.

## 3. Diseño de muestreo

- Puntos: Tres puntos de grabación simultánea.
  - Punto A: **Rellenaaaaaaaaaaaaar**
  - Punto B: **Rellenaaaaaaaaaaaaar**
  - Punto C: Sector más al sur de los tres puntos medidos del parque, frente a un humedal en un camino poco transitado.

- Duración por punto: 20 minutos
- Período: Lunes a las 17:30
- Total de audio: 3 puntos × 20 minutos = 60 minutos de audio

> **Nota:** se grabó a propósito en los 3 puntos al mismo tiempo, para controlar la variable "momento del día". Esto permite comparar A/B/C directamente entre sí, pero no permite saber si las diferencias se mantienen en otros momentos del día.

## 4. Configuración de los equipos

| Punto | Modelo |
|---|---|
| A | Tascam DR-07x |
| B | Tascam DR-07 |
| C | Tascam DR-07 |

**Configuración:**

- **Formato de archivo:** WAV, 16 bits
- **Frecuencia de muestreo:** 44.1 kHz
- **Canales:** estéreo (configuración de micrófono XY)
- **Ganancia:** 75
- **Criterio de ganancia:** se buscó un nivel intermedio entre los lugares más silenciosos y los más ruidosos, de modo que una misma ganancia sirviera para los tres puntos.
- **Duración de grabación:** 20 minutos por punto
- **Fecha de grabación:** Lunes 7 de septiembre

## 5. Organización del proyecto
```text
soundscape_project/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── metadata/
│
├── notebooks/
│
├── figures/
│
├── outputs/
│
└── README.md
```