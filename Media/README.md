# Media - Recursos Multimedia

Bienvenido a la carpeta **Media** de "Locuras en el Tiempo". Aquí se almacenan todos los recursos visuales, audiovisuales y de referencia del proyecto.

## 📁 Estructura

### 🖼️ [Imagenes](./Imagenes)
Recursos visuales organizados por categoría:

- **[Personajes](./Imagenes/Personajes)**: Retratos, diseños de personajes, referencias
- **[Planetas](./Imagenes/Planetas)**: Paisajes, vistas, mapas de planetas
- **[Tecnologia](./Imagenes/Tecnologia)**: Naves, dispositivos, artefactos
- **[Conceptos](./Imagenes/Conceptos)**: Arte conceptual general
- **[Mapas](./Imagenes/Mapas)**: Mapas del multiverso, universos, sistemas

### 🎬 [Videos](./Videos)
Contenido audiovisual:

- **[Trailers](./Videos/Trailers)**: Avances y teasers
- **[Animaciones](./Videos/Animaciones)**: Animaciones de conceptos
- **[Visualizaciones](./Videos/Visualizaciones)**: Viajes temporales, portales, efectos

### 📋 [Storyboards](./Storyboards)
Planificación visual por arco:

- **[Arco_01](./Storyboards/Arco_01)**: Storyboards del primer arco
- **[Arco_02](./Storyboards/Arco_02)**: Storyboards del segundo arco
- **[Arco_03](./Storyboards/Arco_03)**: Storyboards del tercer arco

### 🎵 [Audio](./Audio)
Recursos de audio:

- **[Musica](./Audio/Musica)**: Bandas sonoras, temas
- **[Efectos](./Audio/Efectos)**: Efectos de sonido
- **[Voces](./Audio/Voces)**: Grabaciones de voz, audiolibros

### 📄 [Documentos](./Documentos)
Material de referencia:

- **[Referencias](./Documentos/Referencias)**: Imágenes de referencia, mood boards
- **[Investigacion](./Documentos/Investigacion)**: Investigación científica, artículos

## 📝 Convenciones de Nomenclatura

### Imágenes
```
[Categoría]_[Nombre]_[Versión].[ext]

Ejemplos:
- Personaje_Biglex_v1.png
- Planeta_Xacro_Lumiria_v2.jpg
- Tecnologia_Dimantis_v1.png
- Concepto_ViajeMultiversal_v3.jpg
- Mapa_Multiverso03_v1.svg
```

### Videos
```
[Tipo]_[Nombre]_[Fecha].[ext]

Ejemplos:
- Trailer_Arco01_20260119.mp4
- Animacion_AgujeroBlanco_v1.mp4
- Visualizacion_ViajesTiempo_v2.mov
```

### Storyboards
```
Arco[XX]_Cap[YY]_Escena[ZZ]_[Descripción].[ext]

Ejemplos:
- Arco01_Cap02_Escena05_EncuentroJey.pdf
- Arco01_Cap06_Escena12_InfiltracionCelestia.png
```

### Audio
```
[Tipo]_[Nombre]_[Versión].[ext]

Ejemplos:
- Musica_TemaPrincipal_v1.mp3
- Efecto_ViajeMultiversal_v2.wav
- Voz_Biglex_Capitulo01_v1.mp3
```

### Documentos
```
[Tipo]_[Tema]_[Fecha].[ext]

Ejemplos:
- Referencia_ArquitecturaFuturista_20260119.pdf
- Investigacion_AgujerosNegros_v1.pdf
```

## 🎨 Formatos Recomendados

### Imágenes
| Tipo    | Formato | Uso                                 |
| ------- | ------- | ----------------------------------- |
| **PNG** | `.png`  | Transparencias, logos, UI           |
| **JPG** | `.jpg`  | Fotografías, arte sin transparencia |
| **SVG** | `.svg`  | Gráficos vectoriales, mapas         |
| **PSD** | `.psd`  | Archivos editables de Photoshop     |
| **AI**  | `.ai`   | Archivos editables de Illustrator   |

### Videos
| Tipo     | Formato | Uso                       |
| -------- | ------- | ------------------------- |
| **MP4**  | `.mp4`  | Universal, web            |
| **MOV**  | `.mov`  | Alta calidad, edición     |
| **GIF**  | `.gif`  | Animaciones cortas        |
| **WEBM** | `.webm` | Web, compresión eficiente |

### Audio
| Tipo     | Formato | Uso                       |
| -------- | ------- | ------------------------- |
| **MP3**  | `.mp3`  | Universal, comprimido     |
| **WAV**  | `.wav`  | Alta calidad, sin pérdida |
| **OGG**  | `.ogg`  | Web, código abierto       |
| **FLAC** | `.flac` | Sin pérdida, archivado    |

### Documentos
| Tipo     | Formato | Uso                  |
| -------- | ------- | -------------------- |
| **PDF**  | `.pdf`  | Documentos finales   |
| **DOCX** | `.docx` | Documentos editables |
| **TXT**  | `.txt`  | Notas simples        |

## 🔗 Uso en Documentación

Para referenciar archivos de Media desde Worldbuilding:

```markdown
![Biglex](/Media/Imagenes/Personajes/Personaje_Biglex_v1.png)

[Ver trailer del Arco 01](/Media/Videos/Trailers/Trailer_Arco01_20260119.mp4)

[Escuchar tema principal](/Media/Audio/Musica/Musica_TemaPrincipal_v1.mp3)
```

## 📊 Organización por Proyecto

Si trabajas en múltiples versiones:

```
Media/
├── Imagenes/
│   ├── V1.0/
│   ├── V2.0/
│   └── Final/
```

## 💡 Consejos

### Para Imágenes
- **Resolución mínima**: 1920x1080 para arte principal
- **Usa capas**: Guarda archivos editables (.psd, .ai)
- **Versiona**: Mantén versiones anteriores
- **Optimiza**: Comprime para web cuando sea necesario

### Para Videos
- **Codec**: H.264 para compatibilidad
- **Resolución**: 1080p mínimo, 4K para calidad
- **Framerate**: 24fps para cinemático, 30fps para web
- **Backup**: Guarda archivos de proyecto (.prproj, .aep)

### Para Audio
- **Sample Rate**: 44.1kHz o 48kHz
- **Bit Depth**: 16-bit mínimo, 24-bit para calidad
- **Normaliza**: Ajusta niveles de volumen
- **Backup**: Guarda archivos de proyecto (.aup, .flp)

## 🗂️ Gestión de Archivos

### Versionado
- Usa `_v1`, `_v2`, `_v3` para versiones
- Mantén al menos 2 versiones anteriores
- Documenta cambios importantes

### Backup
- Haz backup regular de Media
- Usa control de versiones para archivos importantes
- Considera almacenamiento en la nube

### Limpieza
- Archiva versiones antiguas periódicamente
- Elimina archivos no utilizados
- Mantén solo versiones finales en producción

## 📐 Dimensiones Recomendadas

### Personajes
- **Retrato**: 1000x1400px
- **Cuerpo completo**: 1200x2000px
- **Referencia**: 2000x2000px

### Planetas
- **Paisaje**: 3840x2160px (4K)
- **Vista orbital**: 2000x2000px
- **Detalle**: Variable según necesidad

### Tecnología
- **Diseño conceptual**: 2000x1500px
- **Plano técnico**: 3000x2000px
- **Icono**: 512x512px

### Mapas
- **Multiverso**: 4000x3000px
- **Planeta**: 3000x3000px
- **Ciudad**: 2500x2000px

## 🎯 Checklist de Calidad

Antes de agregar un archivo a Media:

- [ ] Nombre sigue las convenciones
- [ ] Formato apropiado para el uso
- [ ] Calidad suficiente (resolución, bitrate)
- [ ] Archivo optimizado (tamaño razonable)
- [ ] Versión documentada si aplica
- [ ] Ubicado en la carpeta correcta

## 🔍 Búsqueda Rápida

### Por Personaje
`Media/Imagenes/Personajes/Personaje_[Nombre]_*`

### Por Arco
`Media/Storyboards/Arco_[XX]/*`

### Por Tipo
`Media/Videos/[Tipo]/*`

---

**Última actualización**: 2026-01-19

[← Volver al proyecto](../README.md)
