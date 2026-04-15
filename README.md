# Ready4Drive — Rediseño Mobile Latino

Rediseño completo de la aplicación web Ready4Drive, enfocado en el mercado latino de conductores Amazon Flex. Diseño mobile-first, dark mode, español nativo.

## Páginas incluidas

| Archivo | Descripción |
|---|---|
| `index.html` | Landing page pública — hero, features, testimonios, FAQ, CTA |
| `login.html` | Inicio de sesión con número de teléfono |
| `dashboard.html` | Dashboard principal — toggle ON/OFF, ganancias, bloques capturados |
| `settings.html` | Filtros — horario semanal (modal por día) + almacenes (modal con búsqueda) |
| `invitations.html` | Programa de referidos — invitar amigos, tracking de estado |
| `payments.html` | Planes de pago — 3, 7, 14 y 30 días con formulario de tarjeta |
| `profile.html` | Perfil de usuario — info personal, configuración, cerrar sesión |
| `style.css` | Sistema de diseño completo (tokens, componentes, layout) |

## Sistema de diseño

### Colores
```css
--brand-primary: #00C27C;   /* Verde dinero */
--brand-accent:  #FF6B2B;   /* Naranja energía */
--brand-blue:    #0066FF;   /* Azul acción */
--bg-base:       #0D0F14;   /* Fondo oscuro */
--bg-card:       #161A23;   /* Cards */
```

### Tipografía
- **Plus Jakarta Sans** (Google Fonts) — moderna, legible, confiable
- Pesos: 400 (body), 600 (labels), 700 (bold), 800 (títulos/valores)

### Componentes incluidos
- Botones (primary, accent, outline, ghost, sm)
- Cards y listas
- Toggle switch animado
- Tabs (Hoy / Esta semana)
- Modales tipo bottom-sheet con blur
- Day cards con estado activo/inactivo
- Badges de estado (success, warning, danger, info)
- Inputs con foco verde
- Select con icono personalizado
- Bottom navigation bar
- Float WhatsApp button

## Tecnología

- HTML5 + CSS3 vanilla (sin frameworks)
- JavaScript vanilla (sin dependencias)
- Google Fonts (Plus Jakarta Sans)
- 100% estático — compatible con cualquier hosting

## Deploy

Abre directamente en el navegador o sube los archivos a:
- GitHub Pages
- Netlify Drop
- Vercel
- Cualquier servidor estático (S3, Cloudflare Pages, etc.)

## Notas de integración

La app actual usa React compilado (`main.js`). Este rediseño es el **prototipo visual HTML/CSS** listo para:
1. Usar como referencia de diseño exacta para el equipo de desarrollo
2. Implementar componente por componente en React
3. Extraer el `style.css` como base del nuevo sistema de diseño

---

Desarrollado con Ready4Drive — 2026
