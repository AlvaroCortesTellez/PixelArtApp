# 🎨 PiscisArt – Editor de Pixel Art en Navegador

**PiscisArt** es un editor simple de **pixel art basado en HTML5 Canvas y JavaScript**, diseñado para funcionar directamente en el navegador sin necesidad de instalación.

Este proyecto fue creado con fines **educativos y de prototipado rápido**, especialmente para estudiantes que están aprendiendo:

* desarrollo web
* gráficos con Canvas
* arte para videojuegos
* lógica básica de herramientas de edición

El editor permite crear gráficos pixelados y exportarlos como imágenes o recursos reutilizables.

---

# 🚀 Características

La primera versión incluye:

✔ Creación de lienzo con resolución personalizada
✔ Dibujo pixel a pixel
✔ Cuadrícula visual para facilitar el diseño
✔ Herramienta **lápiz**
✔ Herramienta **relleno tipo Paint (Flood Fill)**
✔ Selector de color
✔ Gestión básica de **frames de animación**
✔ Exportación de **SpriteSheet**
✔ Exportación de **Atlas JSON**

Todo funciona **100% en el navegador** usando:

* HTML5
* CSS
* JavaScript
* Canvas API

---

# 🖥️ Cómo ejecutar el proyecto

1. Clona el repositorio:

```bash
git clone https://github.com/usuario/piscisart.git
```

2. Entra al directorio del proyecto:

```bash
cd piscisart
```

3. Abre el archivo:

```
index.html
```

en tu navegador.

No se requiere servidor ni dependencias.

---

# 🧰 Cómo usar el editor

## 1. Crear un lienzo

Define el tamaño del sprite:

```
ancho
alto
```

y presiona **Crear**.

Ejemplo típico para videojuegos:

```
32 x 32
16 x 16
64 x 64
```

---

## 2. Dibujar

Selecciona una herramienta:

**Lápiz**

Permite pintar píxeles individuales.

**Relleno**

Funciona como el "balde de pintura" de Paint.

---

## 3. Elegir color

Usa el selector de color del panel izquierdo.

---

## 4. Crear animaciones

El editor permite trabajar con **frames**.

Presiona:

```
Añadir Frame
```

para crear un nuevo cuadro de animación.

Cada frame puede contener un sprite diferente.

---

# 📦 Exportación de recursos

## Exportar PNG

Genera una imagen del sprite actual.

```
pixel.png
```

---

## Exportar SpriteSheet

Combina todos los frames en una sola imagen horizontal.

Ejemplo:

```
[frame0][frame1][frame2][frame3]
```

Archivo generado:

```
spritesheet.png
```

---

## Exportar Atlas JSON

Se genera un archivo JSON que describe la posición de cada sprite en el spritesheet.

Ejemplo:

```json
{
  "frames":[
    {"name":"frame_0","x":0,"y":0,"w":32,"h":32},
    {"name":"frame_1","x":32,"y":0,"w":32,"h":32}
  ]
}
```

Esto permite usar fácilmente los sprites en motores de videojuegos.

---

# 🎮 Uso en desarrollo de videojuegos

Los sprites generados pueden utilizarse en motores como:

* Unity
* Godot
* Construct
* Phaser

Flujo típico:

```
1 Crear sprite
2 Crear frames
3 Exportar spritesheet
4 Importar en el motor
5 Crear animación
```

---

# 🧑‍🏫 Uso educativo

Este proyecto está pensado para:

* enseñanza de **HTML5 Canvas**
* lógica de herramientas gráficas
* introducción al **arte para videojuegos**
* comprensión de **spritesheets y animaciones**

---

# 🛠️ Tecnologías usadas

* HTML5
* CSS
* JavaScript
* Canvas API

No se utilizan frameworks ni dependencias externas.

---

# 📁 Estructura del proyecto

```
piscisart
│
├── index.html
└── README.md
```

---

# 🔮 Futuras mejoras

Posibles mejoras del editor:

* sistema de capas
* onion skin para animación
* timeline de animación
* editor de tiles
* exportación de mapas
* soporte de paletas retro
* exportación directa para motores de videojuegos

---

# 👨‍💻 Autor

Proyecto desarrollado por:

**Álvaro Cortés Téllez**

Con fines educativos y de experimentación en desarrollo de herramientas web.

---

# 📜 Licencia

Este proyecto puede distribuirse libremente con fines educativos.
