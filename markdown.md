# Bestiario de dragones

## Un viaje entre escamas, fuego y leyendas

Los **dragones** protagonizan historias llenas de misterio y aventuras. En este *bestiario fantástico* exploraremos tres especies inventadas, sus territorios y sus habilidades. Cada criatura tendrá un identificador, como `DRG-001`, para organizar su ficha y construir nuestro propio mundo de fantasía.

![Dragón de escamas rojizas con las alas desplegadas sobre una montaña al amanecer](assets/mi-imagen.png)

*Ilustración de fantasía generada con IA para esta práctica y guardada como imagen local en el repositorio.*

## El mundo del bestiario

Imagina una región donde los volcanes, las montañas heladas y los bosques antiguos esconden criaturas extraordinarias. Los exploradores llaman a estas tierras **El Reino de las Escamas**. Este escenario y sus especies son una creación para la práctica.

Cada dragón posee un elemento dominante que influye en su aspecto y su comportamiento. Para conocer las fichas completas, consulta la [guía de especies y leyendas](docs/detalles.md).

## Rasgos de nuestros dragones

- Escamas resistentes que protegen su cuerpo.
- Alas capaces de recorrer grandes distancias.
- Un aliento mágico relacionado con su elemento.
- Una memoria que conserva antiguos relatos del reino.
- Un territorio que cada especie protege a su manera.

## Cómo registrar un avistamiento

1. Observar al dragón desde una distancia segura dentro de la historia.
2. Anotar el color de sus escamas y la forma de sus alas.
3. Identificar el territorio y las señales de su elemento.
4. Comparar la descripción con la tabla del bestiario.
5. Añadir una ficha con su nombre, identificador y habilidades.

## Especies del Reino de las Escamas

Las siguientes categorías pertenecen a nuestro mundo inventado.

| Especie | Elemento | Hábitat | Habilidad principal |
| --- | --- | --- | --- |
| Dragón de fuego | Fuego | Volcanes y cuevas cálidas | Expulsar llamaradas |
| Dragón de hielo | Hielo | Cumbres nevadas | Crear una niebla congelante |
| Dragón del bosque | Naturaleza | Bosques antiguos | Ocultarse entre la vegetación |

## Un bestiario programado en Python

Este programa recorre las fichas de las tres especies y muestra sus identificadores y elementos.

```python
dragones = [
    {"id": "DRG-001", "nombre": "Dragón de fuego", "elemento": "Fuego"},
    {"id": "DRG-002", "nombre": "Dragón de hielo", "elemento": "Hielo"},
    {"id": "DRG-003", "nombre": "Dragón del bosque", "elemento": "Naturaleza"},
]

for dragon in dragones:
    print(f"{dragon['id']} | {dragon['nombre']} | {dragon['elemento']}")
```

## De la fantasía al arte: el Instituto Smithsoniano

Los dragones también se representan en obras de arte. El **Instituto Smithsoniano** ofrece un [recurso educativo sobre la pintura Eleven Dragons](https://asia-archive.si.edu/wp-content/uploads/2020/06/O26-F1919.173-Eleven-Dragons-FA.pdf), que muestra estas criaturas entre nubes, acantilados y olas. Es un punto de partida para comparar esas representaciones con las especies que hemos imaginado.

La siguiente fotografía muestra el edificio del Instituto Smithsoniano, conocido como *Castle*. La imagen se carga directamente desde Wikimedia Commons.

![Edificio del Instituto Smithsoniano, conocido como Castle, en Washington D. C.](https://upload.wikimedia.org/wikipedia/commons/d/da/Smithsonian_Castle%2C_Washington_DC.jpg)

Fotografía de **Davemay3610**, del 3 de septiembre de 2016. Fuente: [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Smithsonian_Castle,_Washington_DC.jpg). Licencia: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Sin modificaciones.

## La siguiente aventura

El bestiario puede crecer con nuevas especies, mapas y relatos. Su propósito es dar forma a un universo de dragones mediante descripciones, imágenes y un pequeño registro programado que cualquier explorador pueda consultar.
