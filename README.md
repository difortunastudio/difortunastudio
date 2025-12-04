# Difortuna Studio — Web

## Estructura del proyecto

```
difortuna-web/
├── index.html          ← Home
├── servicios.html      ← Página de servicios completa
├── difor.html          ← Página de DIFOR (línea de moda)
├── contacto.html       ← Formulario de contacto
├── css/
│   └── styles.css      ← Estilos globales
└── images/             ← Carpeta para tus imágenes
```

## Cómo usarlo

1. **Abre la carpeta en VSCode**
2. **Usa Live Server** para ver los cambios en tiempo real
3. **Reemplaza las imágenes** de Unsplash por las tuyas propias

## Imágenes a reemplazar

### Home (index.html)
- Hero: Imagen del estudio o trabajo
- Proyectos: 3 fotos de proyectos reales
- DIFOR teaser: Imagen de prenda
- Estudio: Foto del espacio de trabajo

### Servicios (servicios.html)
- Asesoría: Foto de sesión de colorimetría o styling
- Confección: Foto del taller / costura
- Colecciones: Foto de muestrario

### DIFOR (difor.html)
- 6 fotos de prendas (ratio 3:4 vertical)
- 1 foto para sección historia (ratio 4:5 vertical)

### Contacto (contacto.html)
- Opcional: mapa embed de Google Maps

## Formularios

Los formularios usan Formspree. Para activarlos:

1. Crea cuenta en https://formspree.io
2. Crea un formulario nuevo
3. Reemplaza `TU_FORM_ID` en los action de los formularios:
   - `contacto.html` → formulario principal
   - `difor.html` → formulario de encargos

## Fuentes

El sitio usa Google Fonts:
- **Playfair Display** → títulos (Studio)
- **Cormorant Garamond** → títulos (DIFOR)
- **Inter** → textos

## Colores principales

```css
--white-warm: #F5F5F2;
--black: #1A1A1A;
--gray: #666666;
--gray-light: #999999;
--accent: #8B7355;  /* Taupe/marrón */
--warm-bg: #F0EDE8;
```

## Para publicar

Opciones recomendadas:
- **Netlify** (gratis, arrastra la carpeta)
- **Vercel** (gratis)
- **GitHub Pages** (gratis)

## Contacto

Email: hola@difortunastudio.com
Dirección: Joan d'Austria 95-97, 2º 3ª, 08018 Barcelona
