# WebAudit Taller — Análisis Web y Usabilidad

Herramienta completa para el taller de análisis web del curso **Diseño de Sitios Web (Licenciatura)**.

## Secciones

| Sección | Contenido |
|---|---|
| **Inicio** | Bienvenida, links rápidos a PageSpeed Insights por sitio |
| **Cronograma** | Flujo de 90 min con instrucciones expandibles por fase |
| **Herramientas** | 6 herramientas gratuitas con links directos |
| **Simulador Lighthouse** | Entrada manual de puntajes → análisis Nielsen + embudo + preguntas |
| **Embudo** | Simulador de métricas de conversión con controles interactivos |
| **Debate y cierre** | 6 preguntas detonadoras + conexión con el proyecto de cierre |

## Cómo usan los estudiantes el Simulador Lighthouse

1. Corren el análisis en `pagespeed.web.dev` sobre el sitio asignado
2. Copian los 4 puntajes numéricos (Rendimiento, Accesibilidad, Buenas prácticas, SEO)
3. Los ingresan en la sección **Simulador Lighthouse** de esta herramienta
4. El simulador genera automáticamente:
   - Semáforo visual de los 4 puntajes
   - Embudo de conversión estimado basado en el rendimiento
   - Hallazgos conectados con las heurísticas de Nielsen (H1–H10) con severidad
   - 5 preguntas de reflexión personalizadas con los valores reales ingresados

## Deploy en Vercel

### Opción A — Drag & drop (más rápida, sin terminal)

1. Ir a [vercel.com](https://vercel.com) → crear cuenta gratuita
2. Clic **Add New → Project**
3. Arrastrar esta carpeta al área de upload
4. Clic **Deploy** → URL lista en ~30 segundos

### Opción B — GitHub + Vercel

1. Crear repositorio en GitHub y subir los 3 archivos
2. En Vercel → **Import Git Repository** → seleccionar el repo
3. Deploy automático en cada push

### Opción C — Vercel CLI

```bash
npm install -g vercel
cd taller-web
vercel
```

## Sin costo

- Vercel plan Hobby: gratuito, HTTPS automático, dominio `.vercel.app`
- Un solo archivo HTML — sin backend, sin base de datos, sin dependencias

## Archivos

```
taller-web/
├── index.html    ← app completa
├── vercel.json   ← configuración Vercel
└── README.md
```
