# Tema Matrix

Tema oscuro para Visual Studio Code inspirado en la idea visual de Matrix: negro profundo, verdes fosforicos, lima neon, destellos amarillo-verdosos, acentos anaranjados fosforescentes y rojos muy puntuales para errores y delimitadores estructurales. La extension incluye tambien iconografia propia con formas mas geometricas y digitales para reforzar la estetica del workbench.

![Tema Matrix preview](https://raw.githubusercontent.com/h0w4r/Tema-Matrix-VsCode/master/assets/matrix-preview.png)

## Que incluye

- `Tema Matrix`: color theme oscuro con profundidad visual, mas contraste sintactico y brillo neon controlado.
- `Tema Matrix Icons`: icon theme con siluetas minimalistas, angulares y mas cercanas a una interfaz digital.
- Cobertura ampliada de iconos para IBM i, sistemas, scripting, datos y tooling.
- Cobertura ampliada de iconos para archivos de configuracion, lockfiles, build scripts, frontend frameworks y source files de IBM i.
- Estructura lista para abrirse como extension y empaquetarse con `vsce`.

## Paleta visual

- Fondo base: `#000000`
- Verde principal de interfaz: `#98FF5F`
- Lima / neon activo: `#AEFF00`
- Amarillo-lima de realce: `#D9FF77`
- Texto claro del editor: `#FFFFFA`
- Acento rojo puntual: `#FF7272`

## Concepto visual

- Base armonica analoga: verdes, lima y amarillo-verdoso para que GUI y editor se sientan conectados.
- Acentos calidos controlados: naranjas y ambares fosforicos para enriquecer la interfaz y ciertos tokens sin romper el ADN Matrix.
- Variaciones adicionales integradas en la paleta: `#D16C00`, `#9EED91`, `#EDB391`, `#ED91B3` y `#B3ED91`.
- Contrapunto complementario dividido: rojo muy controlado para errores, brackets y detalles de tension visual.
- Sensacion de fosforo y glow simulada con bordes activos, sombras de widgets, highlights y contraste entre superficies.
- Iconografia mas rectilinea y digital para recordar paneles, nodos y trazos de terminal.

## Uso local

1. Abre esta carpeta en VS Code.
2. Ejecuta `F5` para abrir una ventana `Extension Development Host`.
3. En la nueva ventana, usa `Preferences: Color Theme` y selecciona `Tema Matrix`.
4. Si quieres los iconos, usa `Preferences: File Icon Theme` y selecciona `Tema Matrix Icons`.

## Empaquetado para publicar

1. Instala `vsce` si todavia no lo tienes.
2. Ejecuta `vsce package`.
3. El comando generara un archivo `.vsix` que puedes instalar localmente o publicar en Marketplace.

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
- Los iconos cubren los casos mas visibles de un proyecto tipico y se pueden ampliar sin romper el estilo.
- El icon theme ya cubre familias como COBOL, RPG/RPGLE, CL, DDS, C, C++, C#, Java, XML, YAML, SQL, shell, Docker, Go, Rust, PHP, Ruby, Kotlin, Swift, Astro, Svelte y Vue/React.
- Tambien reconoce mejor archivos reales como `Dockerfile`, `Cargo.toml`, `go.mod`, `requirements.txt`, `package-lock.json`, `pnpm-lock.yaml`, `Makefile`, `Jenkinsfile`, `QCLSRC`, `QRPGLESRC`, `QCBLLESRC` y `QDDSSRC`.
- El glow esta resuelto con recursos nativos de VS Code como bordes, sombras y estados activos; no usa hacks ni CSS externo.
