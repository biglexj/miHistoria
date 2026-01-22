# Locuras en el Tiempo 2.0

![Portada](./Media/Portada.webp)

Esta es la historia de Biglex, un joven de 20 años que se embarca en una aventura a través del tiempo y el multiverso.

## Sinopsis

Nacido en el futurista Universo 7 pero residente del Universo 11, Biglex siempre ha sentido una profunda curiosidad por los viajes en el tiempo. Su vida tranquila da un giro inesperado cuando conoce a Jey Halcime, un enigmático investigador que le ofrece la oportunidad de unirse a una misión para explorar diferentes épocas y dimensiones.

Junto a su enamorada Ely y un equipo de especialistas, Biglex deberá viajar entre multiversos en busca del "Dimantis", un mineral esencial para potenciar la máquina del tiempo. Su viaje los llevará a mundos desconocidos, los enfrentará a peligros inesperados y cambiará sus vidas para siempre.

## Organización de la Historia

La narrativa está estructurada en Arcos argumentales, cada uno con una serie de capítulos:

- **Arcos:** Carpetas principales (ej. `Arco 01`, `Arco 02`) que agrupan los eventos importantes de la trama.
- **Capítulos:** Archivos Markdown dentro de cada arco (ej. `Capitulo 01.md`) que contienen el desarrollo de la historia.

## Estructura de Datos

Para mantener la coherencia y el detalle del mundo, el proyecto cuenta con una carpeta de `Worldbuilding` que contiene información técnica y descriptiva organizada jerárquicamente:

### 📚 [Worldbuilding](./Worldbuilding)

Documentación completa del universo organizada en 8 categorías:

- **[01_Cosmologia](./Worldbuilding/01_Cosmologia):** Estructura del multiverso (globos circulares), leyes físicas, viajes temporales
- **[02_Multiversos](./Worldbuilding/02_Multiversos):** Jerarquía completa: Multiversos → Universos → Planetas
- **[03_Personajes](./Worldbuilding/03_Personajes):** Fichas detalladas de protagonistas, equipo, aliados y antagonistas
- **[04_Tecnologia](./Worldbuilding/04_Tecnologia):** Dimantis, cápsulas, naves, máquina del tiempo y otros artefactos
- **[05_Organizaciones](./Worldbuilding/05_Organizaciones):** TyCEC, GDU, Timenet, Cyberjol
- **[06_Especies](./Worldbuilding/06_Especies):** Humanos, Niders, Gisakianos, androides y otras razas
- **[07_Historia](./Worldbuilding/07_Historia):** Cronología y eventos importantes
- **[08_Glosario](./Worldbuilding/08_Glosario):** Términos y conceptos del universo

Ver [Guía de Uso](./Worldbuilding/GUIA_DE_USO.md) para aprender a navegar y mantener la documentación.

### 🎨 [Media](./Media)

Recursos multimedia organizados en 5 categorías:

- **[Imagenes](./Media/Imagenes)**: Personajes, planetas, tecnología, conceptos, mapas
- **[Videos](./Media/Videos)**: Trailers, animaciones, visualizaciones
- **[Storyboards](./Media/Storyboards)**: Planificación visual por arco
- **[Audio](./Media/Audio)**: Música, efectos de sonido, voces
- **[Documentos](./Media/Documentos)**: Referencias e investigación

Ver [README de Media](./Media/README.md) para convenciones de nomenclatura y formatos recomendados.


## Jerarquía del Proyecto

```text
AHistoria (Root)
├── Arcos (Carpetas)
│   ├── Arco 01
│   │   ├── Capitulo 01.md
│   │   ├── Capitulo 02.md
│   │   └── ...
│   ├── Arco 02
│   └── Arco 03
├── Worldbuilding (Documentación del Universo)
│   ├── 01_Cosmologia
│   ├── 02_Multiversos
│   ├── 03_Personajes
│   ├── 04_Tecnologia
│   ├── 05_Organizaciones
│   ├── 06_Especies
│   ├── 07_Historia
│   └── 08_Glosario
├── Media (Recursos Multimedia)
│   ├── Imagenes
│   │   ├── Personajes
│   │   ├── Planetas
│   │   ├── Tecnologia
│   │   ├── Conceptos
│   │   └── Mapas
│   ├── Videos
│   │   ├── Trailers
│   │   ├── Animaciones
│   │   └── Visualizaciones
│   ├── Storyboards
│   │   ├── Arco_01
│   │   ├── Arco_02
│   │   └── Arco_03
│   ├── Audio
│   │   ├── Musica
│   │   ├── Efectos
│   │   └── Voces
│   └── Documentos
│       ├── Referencias
│       └── Investigacion
├── V 1.0.0 (Versiones Anteriores)
└── README.md
```

