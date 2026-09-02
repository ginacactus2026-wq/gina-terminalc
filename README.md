# CONTPAQi® Bancos - Control de Pólizas, Tesorería y Dashboard

Herramienta en un solo archivo HTML para generar pólizas bancarias automáticamente desde
extractos de cuenta en Excel, con bandeja de revisión, captura manual, dashboard con
gráficas y control antiduplicados.

## ⚠️ Importante sobre los datos

Este sitio guarda toda la información (pólizas, bancos, objetos de negocio) **en el
navegador de cada persona que lo usa** (localStorage), no en este repositorio ni en
ningún servidor. Esto significa:

- Cada persona que abre la liga ve **su propia información**, no la de los demás.
- Los datos **no se sincronizan** entre distintos equipos o navegadores.
- Si limpias el caché del navegador, se pierde la información de ese equipo.

**Para pasar información entre equipos:**
1. Dentro de la app, da clic en **💾 Generar y Descargar HTML** — descarga una copia
   con todas tus pólizas ya incluidas.
2. Abre ese archivo descargado en el otro equipo — cargará automáticamente esos datos.

O bien, vuelve a cargar el mismo Excel del banco en cada equipo (el sistema evita
duplicados automáticamente).

## Uso

Abre `index.html` (o la liga de GitHub Pages) en cualquier navegador. No requiere
instalación ni servidor.
