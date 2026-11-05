# Programa de facturación para autónomos

Aplicación de facturación en un solo archivo (`index.html`). No hace falta instalar nada: ábrelo con doble clic en cualquier navegador (Chrome, Edge, Firefox, Safari).

## Qué hace
- **Facturas** con numeración correlativa por serie y año (`F2026-0001`…), IVA 21/10/4/0 % con desglose y **retención de IRPF** (15 % general, 7 % nuevo autónomo, 0 % particulares).
- **Facturas rectificativas** (serie `R`) a partir de la factura original, con referencia a ella.
- Estados pendiente / pagada / anulada / vencida, duplicar facturas, enviarlas por email e **imprimir o guardar en PDF**.
- **Gastos**: facturas de proveedores por categoría, con IVA soportado y porcentaje deducible.
- **Impuestos trimestrales** (orientativos): **modelo 303** (IVA repercutido − soportado) y **modelo 130** (20 % del rendimiento acumulado − retenciones − pagos anteriores).
- **Libro de ingresos y de gastos** en CSV (se abre con Excel) para tu gestor.
- Fichas de clientes y productos, y copia de seguridad en `.json`.

## Pasar de Holded
En **Mis datos → Pasar de Holded a este programa**:
1. **Continuar la numeración**: pon el próximo número de factura del año para seguir donde lo dejaste en Holded.
2. **Importar contactos y productos**: en Holded, usa *Exportar* en Contactos o en Productos y sube el archivo. Los CSV funcionan sin conexión; los Excel (.xlsx) necesitan internet la primera vez.

Antes de darte de baja en Holded, **descarga en PDF todas tus facturas emitidas**: tienes que guardarlas al menos 4 años (6 a efectos mercantiles).

## Importante
- Los datos se guardan **solo en el navegador y el dispositivo** donde lo uses. Descarga una copia de seguridad a menudo.
- Solo se puede eliminar la **última** factura de una serie, para no dejar huecos en la numeración. Las demás se anulan o se rectifican.
- Los cálculos de impuestos son **orientativos**. Revísalos con tu gestor.
- **VERI\*FACTU**: esta herramienta **no está adaptada** al Reglamento de sistemas de facturación (RD 1007/2023). Según el calendario actual, a los autónomos se les aplica desde el **1 de julio de 2027**; a partir de entonces tendrás que usar un software adaptado (como Holded) o adaptar este.
