# ALPACEL — Agenda Sanitaria (Anomalías & Seguimiento)

Un mini-sistema **offline** (HTML + JS) para registrar anomalías sanitarias/operativas y dar seguimiento en sucursales ALPACEL (Farmacias Similares).

## ✅ Qué incluye
- Registro de anomalías (farmacia, área, prioridad, estatus, responsable, fechas, evidencia)
- Seguimiento por notas con fecha (historial)
- Semáforo por farmacia (verde/amarillo/rojo)
- Checklist sugerido (carga plantillas al campo de acción correctiva)
- Exportar / Importar **JSON**
- Exportar **CSV**
- Generar e imprimir **Acta** (para firma / PDF)

## 🚀 Cómo usar en GitHub Pages
1. Crea un repositorio (o usa uno existente).
2. Sube el archivo `index.html` a la raíz del repo.
3. En GitHub: **Settings → Pages → Build and deployment → Deploy from branch**
   - Branch: `main`
   - Folder: `/ (root)`
4. Guarda y abre el link de Pages.

## 🔒 Datos
Los datos se guardan en el navegador (localStorage). Para moverlos a otra PC:
- Usa **Exportar JSON** y luego **Importar JSON** en el otro equipo.

Hecho para trabajo real: evidencia, control y cierre.
