# Programa de facturación

Aplicación de facturación sencilla en un solo archivo (`index.html`). No hace falta instalar nada: ábrelo con doble clic en cualquier navegador (Chrome, Edge, Firefox, Safari).

## Qué hace
- **Facturas** con numeración correlativa por serie y año (`F2026-0001`, `F2026-0002`…).
- Varias líneas por factura, descuento por línea, **IVA 21 / 10 / 4 / 0 %** con desglose por tipo y **retención de IRPF** opcional.
- Estados **pendiente / pagada / anulada**; las pendientes pasan a **vencida** cuando pasa la fecha de vencimiento.
- **Imprimir o guardar en PDF** (botón «Imprimir / PDF» → «Guardar como PDF»).
- Botones para **duplicar** una factura y para **enviarla por email**.
- Fichas de **clientes** y **productos/servicios**, que rellenan los datos de la factura solos.
- **Resumen por trimestre** (base, IVA repercutido, IRPF) para el modelo 303, y exportación a **CSV/Excel**.
- **Copia de seguridad**: descargar y restaurar todos los datos en un archivo `.json`.

## Importante
- Los datos se guardan **solo en el navegador y el dispositivo** donde lo uses. Descarga una copia de seguridad a menudo (en «Mis datos»).
- Por eso, solo se puede eliminar la **última** factura de una serie, para no dejar huecos en la numeración. Las demás se marcan como «Anulada».
- Esta herramienta **no está certificada para VERI\*FACTU** (Reglamento de sistemas de facturación, RD 1007/2023). Cuando esa obligación empiece a aplicarse a tu caso, tendrás que usar un software adaptado o comprobarlo con tu gestor.
