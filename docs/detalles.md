# Guía de especies y leyendas

## Las criaturas del Reino de las Escamas

El reino, los personajes y las habilidades de estas fichas son ficticios. Se han creado para construir un bestiario coherente y practicar documentación en Markdown.

### DRG-001: Dragón de fuego

**Nombre del ejemplar:** Brasa.

Habita en cuevas volcánicas donde sus escamas rojizas se confunden con la roca caliente. Su aliento produce llamaradas y sus alas le permiten aprovechar las corrientes de aire que ascienden desde los cráteres.

*Leyenda del reino:* Brasa custodia una piedra luminosa que mantiene encendido el fuego de una antigua ciudad.

### DRG-002: Dragón de hielo

**Nombre del ejemplar:** Escarcha.

Vive en las cumbres más altas. Sus escamas claras reflejan la luz y su aliento crea una niebla congelante que oculta las entradas de su refugio.

*Leyenda del reino:* Se dice que Escarcha conserva, dentro de un cristal, la primera nevada del mundo.

### DRG-003: Dragón del bosque

**Nombre del ejemplar:** Verdor.

Protege los bosques antiguos. Sus escamas verdes y sus movimientos silenciosos le permiten ocultarse entre ramas y hojas. Evita los enfrentamientos y guía a quienes respetan su territorio.

*Leyenda del reino:* Cuando Verdor despierta, los senderos olvidados vuelven a cubrirse de flores.

## Cómo ejecutar el programa del bestiario

1. Copia el bloque Python del documento principal en un archivo llamado `bestiario.py`.
2. Abre una terminal en la carpeta donde hayas guardado ese archivo.
3. Con Python instalado, ejecuta:

```bash
python bestiario.py
```

El resultado esperado es:

```text
DRG-001 | Dragón de fuego | Fuego
DRG-002 | Dragón de hielo | Hielo
DRG-003 | Dragón del bosque | Naturaleza
```

La lista `dragones` contiene un diccionario por especie. Cada diccionario guarda las claves `id`, `nombre` y `elemento`. El bucle `for` recorre las fichas y muestra sus datos.

## Dragones en el arte

Para contrastar nuestras criaturas inventadas con una representación artística, puedes consultar el [material educativo del Instituto Smithsoniano sobre Eleven Dragons](https://asia-archive.si.edu/wp-content/uploads/2020/06/O26-F1919.173-Eleven-Dragons-FA.pdf). El recurso describe una pintura de dragones entre nubes, acantilados y olas.

## Organización de los archivos

```text
/
├── markdown.md
├── docs/
│   └── detalles.md
└── assets/
    └── mi-imagen.png
```

El documento principal enlaza esta guía mediante `docs/detalles.md` y muestra la ilustración mediante `assets/mi-imagen.png`. Son rutas relativas desde la raíz del repositorio.

Esta guía está dentro de `docs/`, así que el enlace de vuelta utiliza `../markdown.md`: los dos puntos permiten subir un nivel. La fotografía del instituto utiliza una URL externa de `upload.wikimedia.org` que apunta al archivo de imagen.

## Créditos

- Textos del Reino de las Escamas: ficción creada para esta práctica.
- Ilustración del dragón: generada con IA para el bestiario.
- Fotografía del Instituto Smithsoniano: Davemay3610, 2016, sin modificaciones. [Ficha en Commons](https://commons.wikimedia.org/wiki/File:Smithsonian_Castle,_Washington_DC.jpg), licencia [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
- Referencia artística: material educativo del Instituto Smithsoniano sobre *Eleven Dragons*, enlazado arriba.

[Volver al Bestiario de dragones](../markdown.md).
