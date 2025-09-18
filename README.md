# Proyecto Web 2.0 – Mockup comercial (React + Vite + Tailwind)

Este proyecto contiene la presentación mockup interactiva lista para publicar.

## Requisitos
- Node.js 18+
- NPM

## Instalación
```bash
npm install
```

## Ejecutar en local
```bash
npm run dev
```
Abre el link que aparece (por defecto http://localhost:5173).

## Construir y publicar
```bash
npm run build
```
La carpeta `dist/` contiene el sitio estático listo.

### Publicar en Vercel
1. Sube este folder a un repo en GitHub.
2. Ve a https://vercel.com, importa el repo y despliega con los defaults.
3. Framework: **Vite**. Command: `npm run build`. Output dir: `dist`.
4. Obtendrás un dominio público (ej. `https://proyectoweb-mockup.vercel.app`).

### Publicar en Netlify
1. Conecta tu repo en https://app.netlify.com/.
2. Build command: `npm run build` – Publish directory: `dist`.

### Cambiar datos de contacto / WhatsApp
- Edita en `src/App.jsx` el footer y el QR (busca `wa.me/525522336797`).

### Exportar a PDF
- Abre el sitio y usa Imprimir → Destino: Guardar como PDF, orientación horizontal.
