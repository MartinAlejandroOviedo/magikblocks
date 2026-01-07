# Magik Blocks TW (GitHub Pages)

Paquete listo para publicar en GitHub Pages y consumir como librería remota en Pinegrow.

## Estructura
- `magik-blocks-tw.html`: archivo de librería (usa Tailwind ya presente en tu proyecto).
- `blocks/`: secciones separadas (solo referencia, no es necesario importarlas por separado).
- `preview.html`: vista previa rápida (carga Tailwind desde CDN).
- `README.txt`: instrucciones originales.
- `index.html`: portada con enlaces y URLs clave.

## Publicar en GitHub Pages
1) Crea un repo nuevo y copia todo el contenido de `magik-blocks-tw-gh-pages/` en la raíz.  
2) Commit y push.  
3) Activa GitHub Pages con fuente `main` (carpeta `/`).  
4) Comprueba que `https://<usuario>.github.io/<repo>/magik-blocks-tw.html` responde.

## Usar en Pinegrow (remoto)
1) Asegura que tu proyecto ya tiene Tailwind activo.  
2) En Pinegrow: `Manage Libraries & Plugins` → `Add Library` → `Remote file (URL)`.  
3) Pega la URL pública `https://<usuario>.github.io/<repo>/magik-blocks-tw.html`.  
4) Los bloques aparecen en el panel y se arrastran igual que los oficiales.

## Prueba rápida sin GitHub
- Desde esta carpeta: `python -m http.server 8080` y usa `http://localhost:8080/magik-blocks-tw.html` como URL de librería.  
- Para ver el catálogo visual: abre `http://localhost:8080/preview.html` o, ya publicado, `https://<usuario>.github.io/<repo>/preview.html`.
