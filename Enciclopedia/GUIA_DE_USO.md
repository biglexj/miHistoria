# Guía de Uso - Worldbuilding

## 🎯 Propósito

Esta guía te ayudará a navegar y mantener actualizada la documentación del worldbuilding de "Locuras en el Tiempo".

## 📚 Cómo Navegar

### Estructura General
```
Worldbuilding/
├── 01_Cosmologia/      → Leyes del universo
├── 02_Multiversos/     → Mundos y planetas
├── 03_Personajes/      → Fichas de personajes
├── 04_Tecnologia/      → Objetos y artefactos
├── 05_Organizaciones/  → Facciones y grupos
├── 06_Especies/        → Razas y seres
├── 07_Historia/        → Cronología
└── 08_Glosario/        → Términos
```

### Cada Sección Tiene:
- **README.md**: Índice de la sección
- **Documentos específicos**: Información detallada

## ✍️ Cómo Agregar Contenido

### 1. Nuevo Personaje

1. Decide la categoría (Protagonista/Equipo/Aliado/Antagonista)
2. Crea archivo en `03_Personajes/[Categoría]/[Nombre].md`
3. Usa la plantilla de personajes (ver `plantillas.md`)
4. Actualiza el README de Personajes

### 2. Nuevo Planeta

1. Identifica Multiverso → Universo
2. Crea archivo en `02_Multiversos/Multiverso_XX/Universo_YY/Planeta_[Nombre].md`
3. Usa la plantilla de planetas
4. Actualiza los READMEs correspondientes

### 3. Nueva Tecnología

1. Crea archivo en `04_Tecnologia/[Nombre].md`
2. Usa la plantilla de tecnología
3. Actualiza el README de Tecnología

### 4. Nueva Organización

1. Crea archivo en `05_Organizaciones/[Nombre].md`
2. Usa la plantilla de organizaciones
3. Actualiza el README

## 🔗 Enlaces Entre Documentos

Usa rutas relativas para enlazar documentos:

```markdown
[Ver Biglex](../03_Personajes/Protagonistas/Biglex.md)
[Ver Xacro](../02_Multiversos/Multiverso_03/Universo_11/Planeta_Xacro.md)
```

## 🖼️ Agregar Imágenes

1. Guarda la imagen en `/Assets/Imagenes/[Categoría]/`
2. Referencia desde el documento:

```markdown
![Biglex](/Assets/Imagenes/Personajes/Biglex_v1.png)
```

## 📝 Convenciones

### Nombres de Archivos
- **Personajes**: `Nombre_Apellido.md` (ej: `Jey_Halcime.md`)
- **Planetas**: `Planeta_Nombre.md` (ej: `Planeta_Xacro.md`)
- **Tecnología**: `Nombre_Objeto.md` (ej: `Maquina_del_Tiempo.md`)
- **Organizaciones**: `Nombre.md` (ej: `TyCEC.md`)

### Formato de Documentos
- Usa Markdown (.md)
- Incluye encabezados claros (##, ###)
- Agrega enlaces de navegación al final
- Marca secciones pendientes con *[Pendiente]*

### Actualización
- Actualiza la fecha en el README principal
- Mantén consistencia entre documentos relacionados
- Revisa enlaces rotos periódicamente

## 🔄 Flujo de Trabajo Recomendado

### Al Escribir un Nuevo Capítulo:

1. **Antes de escribir**:
   - Consulta la documentación relevante
   - Verifica consistencia con lo establecido

2. **Durante la escritura**:
   - Toma notas de nuevos elementos introducidos

3. **Después de escribir**:
   - Actualiza/crea documentos para nuevos elementos
   - Actualiza cronología si es necesario
   - Agrega referencias cruzadas

## 📊 Mantenimiento

### Revisión Mensual
- [ ] Verificar enlaces rotos
- [ ] Completar secciones *[Pendiente]*
- [ ] Actualizar índices
- [ ] Revisar consistencia

### Después de Cada Arco
- [ ] Documentar nuevos personajes
- [ ] Actualizar cronología
- [ ] Agregar nuevos planetas/tecnologías
- [ ] Revisar y expandir glosario

## 🎨 Uso de Plantillas

Las plantillas están en el archivo `plantillas.md` en los artifacts:

1. **Cosmología**: Para conceptos físicos/dimensionales
2. **Planeta**: Para mundos y ubicaciones
3. **Personaje**: Para fichas de personajes
4. **Tecnología**: Para objetos y artefactos
5. **Organización**: Para facciones y grupos
6. **Especie**: Para razas y seres

## 💡 Consejos

- **Sé consistente**: Usa los mismos términos en todos los documentos
- **Enlaza todo**: Crea una red de referencias cruzadas
- **Marca lo pendiente**: Usa *[Pendiente]* para información que falta
- **Actualiza regularmente**: No dejes que se acumule el trabajo
- **Usa el glosario**: Define términos únicos de tu universo

## 🆘 Preguntas Frecuentes

**P: ¿Dónde documento un evento histórico?**  
R: En `07_Historia/Eventos_Importantes.md` y actualiza `Linea_Temporal.md`

**P: ¿Cómo organizo múltiples versiones de un personaje?**  
R: Usa secciones dentro del mismo archivo o crea subcarpetas por versión

**P: ¿Qué hago si un planeta cambia de nombre?**  
R: Renombra el archivo y actualiza todos los enlaces que lo referencian

**P: ¿Cómo documento algo que aparece en múltiples categorías?**  
R: Crea el documento en la categoría principal y enlázalo desde las otras

---

[← Volver al índice principal](./README.md)
