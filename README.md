# Hemodinamia

Cronograma interactivo 2026 para Monitoreo Hemodinámico (curso de Cuidados Intensivos).

## Cómo verlo en línea (GitHub Pages)
1. Crea un repo público en tu cuenta: `VAnCorr/Hemodinamia`.
2. Sube los archivos (ver pasos abajo).
3. En GitHub, ve a **Settings → Pages**, elige "Deploy from a branch", rama `main`, carpeta `/ (root)` y guarda.
4. La URL quedará: https://vancorr.github.io/Hemodinamia/cronograma.html
   - Si renombraras `cronograma.html` a `index.html`, la URL sería https://vancorr.github.io/Hemodinamia/

## Subir los archivos (PowerShell)
Desde la carpeta del proyecto:

```powershell
cd "c:\Users\LENOVO\OneDrive\Desktop\Hemodinamia"
git init
git add cronograma.html README.md
git commit -m "Add cronograma"
git branch -M main
git remote add origin https://github.com/VAnCorr/Hemodinamia.git
git push -u origin main
```

Luego activa GitHub Pages (paso 3) y espera 1-2 minutos.

## Sobre el cronograma
- Tema claro/oscuro, buscador y acordeón con objetivos.
- Los títulos largos se expanden al abrir la tarjeta.
- Datos están embebidos en el JS del HTML (sin backend).
