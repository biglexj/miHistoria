# Locuras en el Tiempo 2.0

![Portada](./Media/Portada.webp)

Esta es la historia de Biglex, un joven de 20 años que se embarca en una aventura a través del tiempo y el multiverso.

## Sinopsis

Nacido en el Universo 7 de su multiverso y residente del Universo 11, Biglex siempre ha sentido una profunda curiosidad por los viajes en el tiempo. Su vida tranquila da un giro inesperado cuando conoce a Jey Halcime, un enigmático investigador que le ofrece la oportunidad de unirse a una misión para explorar diferentes épocas y dimensiones.

Junto a su enamorada Ely y un equipo de especialistas, Biglex deberá viajar entre multiversos en busca del "Dimantis", un mineral esencial para potenciar la máquina del tiempo. Su viaje los llevará a mundos desconocidos, los enfrentará a peligros inesperados y cambiará sus vidas para siempre.

## Lectura por capítulos

**Escritura reanudada el 21 de octubre de 2026.** Estado actual: 10 arcos completos y 200 capítulos con cuerpo narrativo. [Roadmap de relevo y tareas pendientes](ROADMAP.md).

- [Arco 01 — La misión del Dimantis](Arco%2001/README.md): 20/20 capítulos desarrollados.
- [Arco 02 — El intervalo de prueba](Arco%2002/README.md): 20/20 capítulos desarrollados.
- [Arco 03 — Los nombres que faltan](Arco%2003/README.md): 20/20 capítulos desarrollados.
- [Arco 04 — Las rutas que dejamos](Arco%2004/README.md): 20/20 capítulos desarrollados.
- [Arco 05 — El lugar del que salimos](Arco%2005/README.md): 20/20 capítulos desarrollados.
- [Arco 06 — Las rutas que nos trajeron](Arco%2006/README.md): 20/20 capítulos desarrollados.
- [Arco 07 — La costura](Arco%2007/README.md): 20/20 capítulos desarrollados.
- [Arco 08 — La otra rama](Arco%2008/README.md): 20/20 capítulos desarrollados.
- [Arco 09 — El cálculo](Arco%2009/README.md): 20/20 capítulos desarrollados.
- [Arco 10 — La fecha](Arco%2010/README.md): 20/20 capítulos desarrollados.

Cada capítulo tiene su archivo. Los diseños de arco están en [Ideas/Desarrollo_Arcos_06_08/DISENO_ARCOS_06_08.md](Ideas/Desarrollo_Arcos_06_08/DISENO_ARCOS_06_08.md) e [Ideas/Desarrollo_Arcos_09_10/DISENO_ARCOS_09_10.md](Ideas/Desarrollo_Arcos_09_10/DISENO_ARCOS_09_10.md). Los cierres de arco, que fijan lo que queda establecido al final de cada uno, están en `Ideas/Desarrollo_Arcos_02_05/CIERRE_ARCO_0N.md`, `Ideas/Desarrollo_Arcos_06_08/CIERRE_ARCO_0N.md` e `Ideas/Desarrollo_Arcos_09_10/CIERRE_ARCO_0N.md`. La serie no termina con el Arco 10: el Arco 11 queda abierto y en diseño.

## Organización de la Historia

La narrativa está estructurada en Arcos argumentales, cada uno con una serie de capítulos:

- **Arcos:** Carpetas principales (ej. `Arco 01`, `Arco 02`) que agrupan los eventos importantes de la trama.
- **Capítulos:** Archivos Markdown dentro de cada arco (ej. `Capitulo 01.md`) que contienen el desarrollo de la historia.

## Estructura de Datos

Para mantener la coherencia y el detalle del mundo, el proyecto cuenta con una carpeta de `Enciclopedia` que contiene información técnica y descriptiva organizada jerárquicamente:

### 📚 [Enciclopedia/Worldbuilding](./Enciclopedia)

Documentación completa del universo organizada en 8 categorías:

- **[01_Cosmologia](./Enciclopedia/01_Cosmologia):** Estructura del multiverso (globos circulares), leyes físicas, viajes temporales
- **[02_Multiversos](./Enciclopedia/02_Multiversos):** Jerarquía completa: Multiversos → Universos → Planetas
- **[03_Personajes](./Enciclopedia/03_Personajes):** Fichas detalladas de protagonistas, equipo, aliados y antagonistas
- **[04_Tecnologia](./Enciclopedia/04_Tecnologia):** Dimantis, cápsulas, naves, máquina del tiempo y otros artefactos
- **[05_Organizaciones](./Enciclopedia/05_Organizaciones):** TyCEC, GDU, GDT, Timenet, SiCoTemp y Cyberjol
- **[06_Especies](./Enciclopedia/06_Especies):** Humanos, Niders, Gisakianos, androides y otras razas
- **[07_Historia](./Enciclopedia/07_Historia):** Cronología y eventos importantes
- **[08_Glosario](./Enciclopedia/08_Glosario):** Términos y conceptos del universo

Ver [Guía de Uso](./Enciclopedia/GUIA_DE_USO.md) para aprender a navegar y mantener la documentación, y el [índice de la enciclopedia](./Enciclopedia/README.md) para ver el detalle de cada categoría.

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
│   ├── Arco 03
│   ├── Arco 04
│   ├── Arco 05
│   ├── Arco 06
│   ├── Arco 07
│   ├── Arco 08
│   ├── Arco 09
│   └── Arco 10
├── Enciclopedia (Documentación del Universo)
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
├── Ideas (Material de trabajo)
│   ├── Desarrollo_Arcos_02_05
│   ├── Desarrollo_Arcos_06_08
│   └── Desarrollo_Arcos_09_10
├── V 1.0.0 (Versiones Anteriores)
└── README.md
```

