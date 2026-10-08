# Activity 1 - AR Foundation - ArMobile Project

Proyecto para la asignatura Entornos de Realidad Virtual en CITM (UPC).

Basado en la plantilla AR Mobile de Unity, implementa las siguientes funcionalidades de AR Foundation:

- Image Tracking
- Plane Detection
- Anchors
- Point Cloud

El proyecto está desarrollado específicamente para dispositivos Android.

## Requisitos

| Requisito | Versión |
|---|---|
| Unity | **6000.4.9f1** (Unity 6.4) |
| Android Build Support | Incluido en Unity |
| AR Foundation | **6.4** |
| Google ARCore XR Plug-in | **6.4** |

### Dispositivo

- Teléfono Android compatible con [ARCore](https://developers.google.com/ar/devices).

## Cómo usarlo

1. Instalar la APK en un dispositivo Android compatible.
2. Abrir la aplicación y permitir el acceso a la cámara si se solicita.
3. Escanear las imágenes de referencia adjuntas.
4. Moverse por el espacio para detectar superficies.
5. Hacer clic sobre los planos detectados para añadir los modelos de "pigs".

## Funcionalidades

### Image Tracking

Permite reconocer y seguir imágenes específicas mediante la cámara. Al detectar una de estas imágenes, aparecen elementos virtuales asociados a ella y se mantienen posicionados mientras la cámara se mueve.

### Plane Detection

Permite detectar superficies planas del entorno, como el suelo, mesas o paredes, para colocar elementos virtuales de forma precisa en el espacio real.

### Anchors

Los Anchors son puntos de referencia que permiten mantener la posición y orientación de un objeto virtual de forma estable respecto al entorno real. Gracias a ellos, los modelos pueden permanecer correctamente posicionados dentro del espacio AR.

### Point Cloud

Permite representar mediante puntos las características del entorno detectadas por el dispositivo. Estos puntos proporcionan información espacial que puede utilizarse como referencia para posicionar y alinear objetos virtuales dentro del entorno AR.

Equipo de proyecto:

| Helena Calvo | Maxi Pantoja | Laia Espluga | Ariana Garcia | Ana Guerrero |


