# Funerarias inscritas en Zaragoza

Página pública con el listado de las empresas funerarias inscritas en el
[Registro Municipal de Empresas Funerarias](https://www.zaragoza.es/ciudad/cementerios/registro-funerarias.htm)
del Ayuntamiento de Zaragoza, por orden alfabético y con teléfonos de contacto.

Pensada para enlazar desde el folleto informativo que se entrega a las familias
en la UCI del Hospital Universitario Royo Villanova.

**URL:** https://uciroyo.github.io/funerarias/

## Por qué existe

El registro municipal es la fuente oficial de qué empresas están habilitadas
para operar en Zaragoza, pero no publica datos de contacto. Esta página une
ambas cosas: las empresas del registro y sus teléfonos.

## Criterios

- Figuran **todas** las empresas inscritas en el registro municipal, sin excepción.
- El orden es **alfabético**. No hay recomendación ni preferencia de ninguna empresa.
- Los teléfonos y direcciones proceden de las webs y canales de atención de cada
  empresa.

## Mantenimiento

Revisar **una o dos veces al año** contra el registro municipal: las altas y bajas
son poco frecuentes pero existen (Alkarama se inscribió en 2025).

Al actualizar, cambiar también la fecha que aparece en la cabecera de `index.html`:

```html
<span><span class="dot"></span>Actualizado el 27 de octubre de 2026</span>
```

Último cotejo con el registro: **octubre de 2026**.

## Estructura

Un único `index.html` autónomo: sin dependencias, sin build. Solo carga las
tipografías desde Google Fonts. Incluye hoja de estilos de impresión, así que
se puede imprimir a dos columnas directamente desde el navegador.
