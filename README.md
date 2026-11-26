# Esperanza Arcila · Informes de campañas Meta Ads

Cliente: **Esperanza Arcila · Arte que transforma** (esperanzaarcila.com, Instagram @esperanza_arcila_arte) · Agencia: We Rock

Pauta: **$600.000**, 18 nov – 18 dic 2026, cuenta publicitaria CP Artify.
| Campaña | Objetivo | Presupuesto |
|---|---|---|
| C1 · WhatsApp | Conversaciones | $360.000 |
| C2 · Tienda | Visitas a esperanzaarcila.com | $180.000 |
| C3 · Remarketing | Visitantes de la tienda (desde 1 dic) | $60.000 |

## Informes
| Corte | Período | Carpeta |
|---|---|---|
| 26 nov 2026 | 18 – 25 nov (primera semana) | `reportes/2026-11-26/` |

## Proceso de cada corte
1. Ads Manager → Anuncios → Columnas "Rendimiento y clics" → copiar a `data/AAAA-MM-DD_anuncios.csv`.
2. Administrador de eventos → conjunto de datos de Esperanza Arcila - Artista → copiar el embudo a `data/AAAA-MM-DD_pixel.csv`.
3. Revisar Instagram (publicaciones al día) y preguntar a Esperanza por ventas fuera de la web.
4. Copiar `reportes/<último>/index.html`, actualizar cifras y exportar el PDF:
   ```bash
   "/c/Program Files/Google/Chrome/Application/chrome.exe" --headless=new --no-pdf-header-footer --virtual-time-budget=8000 --print-to-pdf="reportes/<fecha>/EsperanzaArcila_Informe_<fecha>.pdf" "file:///<ruta>/reportes/<fecha>/index.html"
   ```
