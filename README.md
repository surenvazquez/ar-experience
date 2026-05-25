# AR · Patrimonio Cultural

Experiencia de **Realidad Aumentada web** para el Máster en Humanidades Digitales — Módulo Interacción Persona-Ordenador.

## Demo

🌐 **[Abrir experiencia](https://surenvazquez.github.io/ar-experience/)**

Abre el enlace en **Chrome** (Android o iOS), acepta el permiso de cámara y apunta al marcador Hiro.

## Marcador

Muestra esta imagen en pantalla o imprímela:

![Marcador Hiro](https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/hiro.png)

## Estructura del proyecto

```
index.html   →  Página de inicio para estudiantes (instrucciones + marcador)
ar.html      →  Experiencia AR (cámara + objeto 3D sobre el marcador)
```

## Tecnología

| Librería | Función |
|----------|---------|
| [A-Frame](https://aframe.io) | Renderizado 3D en WebGL |
| [AR.js](https://ar-js-org.github.io/AR.js-Docs/) | Visión por computador y tracking de marcador |
| GitHub Pages | Hosting con HTTPS (necesario para acceso a cámara) |

## Cómo funciona

1. La cámara del móvil captura fotogramas en tiempo real
2. AR.js analiza cada fotograma buscando el patrón del marcador Hiro
3. Cuando lo detecta, calcula su posición y orientación en el espacio 3D (pose estimation)
4. A-Frame renderiza el objeto 3D en esas coordenadas exactas sobre el vídeo

## Próximos pasos

- [ ] Marcador personalizado con imagen de patrimonio cultural (NFT tracking)
- [ ] Contenido multimedia: imágenes, vídeo y audio sobre el marcador
- [ ] Múltiples marcadores con experiencias diferenciadas
- [ ] Guía didáctica para que los estudiantes creen sus propias experiencias

## Autora

Desarrollado por **Suren Vázquez** · Humanidades Digitales, Citilab