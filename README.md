# Tema Matrix

Tema oscuro para Visual Studio Code inspirado en una interfaz tipo Matrix: negros profundos, verdes suaves para el trabajo diario y acentos menta brillantes en puntos clave. La extensión también incluye un conjunto propio de iconos minimalistas para mantener la estética en el explorador.

![Tema Matrix preview](https://github.com/h0w4r/Tema-Matrix-VsCode/raw/HEAD/assets/matrix-preview.svg)

## Qué incluye

- `Tema Matrix`: color theme oscuro con contraste bajo y buena legibilidad.
- `Tema Matrix Icons`: icon theme minimalista para carpetas, archivos genéricos y tipos comunes.
- Estructura lista para abrirse como extensión y empaquetarse con `vsce`.

## Paleta visual

- Fondo base: `#020403`
- Verde principal de interfaz: `#7EC7A1`
- Verde menta de enfoque: `#4FF1B3`
- Texto editor: `#A2CCB4`
- Advertencias: `#CDAF5C`
- Errores: `#D95757`

## Uso local

1. Abre esta carpeta en VS Code.
2. Ejecuta `F5` para abrir una ventana `Extension Development Host`.
3. En la nueva ventana, usa `Preferences: Color Theme` y selecciona `Tema Matrix`.
4. Si quieres los iconos, usa `Preferences: File Icon Theme` y selecciona `Tema Matrix Icons`.

## Empaquetado para publicar

1. Instala `vsce` si todavía no lo tienes.
2. Ejecuta `vsce package`.
3. El comando generará un archivo `.vsix` que puedes instalar localmente o publicar en Marketplace.

## Estructura del proyecto

```text
.
|-- assets/
|-- icon-theme/
|-- icons/
|-- themes/
|-- package.json
`-- README.md
```

## Notas

- La V1 prioriza una sola variante visual bien ajustada.
- Los iconos cubren los casos más visibles de un proyecto típico y se pueden ampliar sin romper el estilo.
