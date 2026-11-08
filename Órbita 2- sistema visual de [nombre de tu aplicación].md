# Órbita 2: sistema visual de [libreryPorts]

## Enlaces

| Qué | Enlace |
|---|---|
| Archivo de Figma  | ([versión "Entrega Órbita 2"](https://www.figma.com/design/yNLvEoiTqaHDkJwoDr5JoU/mockup?t=KmFOQNxhmTRWNpJc-0))|
| Prototipo  |([https://www.figma.com/proto/yNLvEoiTqaHDkJwoDr5JoU/mockup?node-id=2080-248&p=f&t=KmFOQNxhmTRWNpJc-0&scaling=min-zoom&content-scaling=fixed&page-id=2076%3A206](https://www.figma.com/proto/yNLvEoiTqaHDkJwoDr5JoU/mockup?node-id=2080-248&p=f&t=KmFOQNxhmTRWNpJc-0&scaling=min-zoom&content-scaling=fixed&page-id=2076%3A206)) |
| Proyecto de Google Stitch (solo si lo has usado) | |

## Dónde está cada cosa en Figma

| Entregable | Página y sección del archivo |
|---|---|
| Inventario de decisiones | |
| Wireframes rediseñados con sus notas |wireframe rediseñado |
| Componentes | |
| Mockups del happy path |mockup |
| Pantalla principal en el segundo ancho | |
| Pantallas en modo oscuro |variables |
| Guía de estilo |variables |

## Lista de comprobación de Figma

- [x] Variables en dos colecciones (primitivos y semánticos), con alias, modos claro y oscuro, ámbito, descripción y sintaxis de código.
- [ ] Estilos de texto, efecto y retícula vinculados a las variables.
- [x] Componentes con Auto layout, variables, propiedades y variantes de estado.
- [x] Mockups construidos enteros con Auto layout y espacios sacados de variables.
- [ ] Pantalla principal en un segundo ancho, con los mismos componentes.
- [x] Modo oscuro aplicado con el selector de modo.
- [x] Prototipo que recorre el happy path completo.
- [ ] Prueba 1 superada: al cambiar `color/primary`, cambian todas las pantallas a la vez.
- [ ] Prueba 2 superada: con todos los mockups en modo oscuro, nada desaparece contra el fondo.

## Resumen de decisiones

### Rediseño de los wireframes
Qué pantallas has cambiado, cuál es el cambio más importante y por qué (con tu persona o un principio de los apuntes).
No me organicé bien en la orbita 1 por lo que no tenía el wireframe completo, así que básicamente lo he creado completamente

### Color
Color principal y secundario, y por qué los elegiste. Pareja de texto y fondo con el contraste más bajo de tu sistema y su valor, en cada modo.
color primario: 87643B 
color secundario: 751520
los elegí porque por el contexto de mi aplicación necesito colores relajantes y elegantes que no generen mucha fatiga visual.
### Tipografía
Familias y pesos que usas, y por qué esas familias para tus personas.
Domine: para textos informativos y descriptivos.

The Nautigal: para titulos y textos destacados.

### Espaciado y retícula
Base de la escala (4 u 8 píxeles), columnas, medianil y margen de la retícula del dispositivo de tu persona principal.
espaciado 20px
espaciado-2 150px
espaciado-3 10px
margen-horizontal 40px
margen horizontal 16px
margen-vertical 40px
margen-vertical-2 34px
radio 15px

### Componentes
Lista de componentes con sus variantes de estado.

### Responsive y modo oscuro
Qué tuviste que ajustar al pasar la pantalla principal al segundo ancho, y qué corregiste en tus variables al pasar los mockups a modo oscuro.

## Uso de IA
Resumen en dos o tres frases de cómo has usado la IA en la órbita (o "no he usado ninguna herramienta de IA"). El detalle está en el [CHANGELOG.md](CHANGELOG.md).
he usado herramientas de IA para generar un user persona y para generar imagenes.

## Lo que ha quedado pendiente
Lo que no has terminado o sabes que no funciona del todo, y por qué. Si está todo terminado, indícalo.

mockup responsive.
modo oscuro bien integrado.
justificación de colores usados.
apartado de componentes y variantes.
prueba 1 y prueba 2

por qué: mala organización del tiempo, complicaciones para realizar el mockup y el wireframe y desconocimiento de conceptos.