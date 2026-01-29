# Proyecto: Análisis de la aplicación **Spotify**

> Trabajo sobre clasificación de software y análisis de una aplicación real.

---

## Índice

1. [Descripción general de la aplicación](#descripción-general-de-la-aplicación)
2. [Imágenes, logos y ejemplos de uso](#imágenes-logos-y-ejemplos-de-uso)
3. [Clasificación del software](#clasificación-del-software)
   - [Según utilidad](#según-utilidad)
   - [Según propósito](#según-propósito)
   - [Según interacción con el usuario](#según-interacción-con-el-usuario)
   - [Según plataforma de ejecución](#según-plataforma-de-ejecución)
   - [Según modelo de negocio](#según-modelo-de-negocio)
4. [Propósito general o específico](#propósito-general-o-específico)
5. [Aplicación de escritorio o web y comparación](#aplicación-de-escritorio-o-web-y-comparación)
6. [Requisitos de instalación o de uso en navegador](#requisitos-de-instalación-o-de-uso-en-navegador)
7. [Problemas que resuelve y usos principales](#problemas-que-resuelve-y-usos-principales)

---

## Descripción general de la aplicación

Spotify es una aplicación de **streaming de audio** que permite escuchar música, pódcasts y otros contenidos sonoros a través de Internet.  
Ofrece búsqueda de canciones, creación de listas de reproducción, recomendaciones personalizadas y funciones sociales como compartir música con amigos.

---

## Imágenes, logos y ejemplos de uso

> En un repositorio real, estas imágenes irían en una carpeta como `img/` o `assets/`.

**Logo principal de la aplicación**

![Logo de Spotify]

**Pantalla de inicio / Home**

![Pantalla de inicio de Spotify]

**Ejemplo de lista de reproducción**

![Lista de reproducción en Spotify]

**Ejemplo de pantalla de reproducción**

![Pantalla de reproducción de una canción]

---

## Clasificación del software

### Según utilidad

- **Tipo:** Software de aplicación / entretenimiento y multimedia.  
- **Por qué:** Está orientado al **consumo de contenido multimedia** (música y audio), no a la gestión del sistema ni al desarrollo de otros programas.

### Según propósito

- **Tipo:** Software de aplicación de propósito específico (reproducción y gestión de audio en streaming).  
- **Por qué:** Está diseñado específicamente para **escuchar música y pódcasts**, gestionar listas y descubrir contenido musical, no para tareas generales como ofimática o edición de vídeo.

### Según interacción con el usuario

- **Tipo:** Aplicación interactiva, cliente–servidor, multiusuario.  
- **Por qué:**
  - El usuario interactúa constantemente (buscar, pausar, saltar canciones, crear listas).
  - Depende de un **servidor remoto** donde están las canciones.
  - Muchos usuarios usan el servicio a la vez, cada uno con su cuenta.

### Según plataforma de ejecución

- **Tipo:** Multiplataforma (escritorio, móvil y web).  
- **Por qué:** Spotify dispone de:
  - Aplicación de escritorio (Windows, macOS, algunas distribuciones Linux).
  - Aplicación móvil (Android, iOS).
  - Versión web que funciona en el navegador.

Para el resto del documento, me centraré sobre todo en la **versión de escritorio** y la **versión web**.

### Según modelo de negocio

- **Tipo:** Modelo **freemium** con suscripción.  
- **Por qué:**
  - Tiene una versión gratuita con anuncios y ciertas limitaciones.
  - Ofrece planes de pago (Premium) con más funciones: sin anuncios, descargas offline, mejor calidad de audio, etc.

---

## Propósito general o específico

- **Clasificación:** Aplicación de **propósito específico**.  
- **Función principal:**  
  - Reproducir música y pódcasts en streaming.  
  - Gestionar listas de reproducción y bibliotecas musicales.  
  - Ofrecer recomendaciones personalizadas basadas en los gustos del usuario.

No sirve para tareas generales como edición de documentos, diseño gráfico o programación; su foco está muy claro en el **consumo y gestión de contenido de audio**.

---

## Aplicación de escritorio o web y comparación

Spotify existe en ambos formatos, pero:

- **Aplicación de escritorio:**  
  - Mejor integración con el sistema (atajos de teclado, control multimedia, integración con dispositivos de audio).  
  - Suele ofrecer un rendimiento más estable y menor consumo de recursos del navegador.  
  - Permite tener la música separada del navegador, sin depender de pestañas abiertas.

- **Aplicación web:**  
  - No requiere instalación, basta con un navegador moderno.  
  - Es útil en ordenadores donde no se puede instalar software (por ejemplo, equipos compartidos o de trabajo con restricciones).  
  - Se integra bien con otras pestañas y servicios web.

**¿En qué caso es mejor cada una?**

- **Mejor como aplicación de escritorio:**  
  - Para usuarios que escuchan música muchas horas al día y quieren **estabilidad, atajos y menor distracción**.  
  - Para quienes usan Spotify mientras trabajan con muchas pestañas abiertas y prefieren separar la música del navegador.

- **Mejor como aplicación web (comparada con la de escritorio):**  
  - Para uso ocasional en equipos donde no se puede instalar nada.  
  - Para probar el servicio rápidamente sin descargar la app.

Como comparación, podemos pensar en un reproductor local de escritorio (por ejemplo, uno que reproduce archivos MP3 guardados en el ordenador).  
Ese tipo de aplicación **no necesita Internet**, pero tampoco ofrece catálogo en streaming ni sincronización entre dispositivos. Spotify, al ser principalmente un servicio en la nube, tiene más sentido como **cliente conectado (escritorio o web)** que como simple reproductor local.

---

## Requisitos de instalación o de uso en navegador

### Requisitos de la aplicación de escritorio

*(Los valores son orientativos, pueden variar según versión y sistema operativo.)*

- **Sistema operativo:**
  - Windows 10 o superior / macOS versión reciente / distribución Linux compatible.
- **Hardware mínimo:**
  - **CPU:** Procesador de 64 bits moderno.
  - **RAM:** Al menos 4 GB (recomendable 8 GB si se usan muchas aplicaciones a la vez).
  - **Almacenamiento:** Espacio libre para la instalación y, si se usan descargas offline, varios GB adicionales.
- **Conectividad:**
  - Conexión a Internet estable para reproducir en streaming.
- **Otros:**
  - Tarjeta de sonido y altavoces/auriculares.

### Requisitos para usar la versión web con fluidez

- **Navegador:**
  - Navegador moderno actualizado (Chrome, Edge, Firefox, etc.) con soporte para reproducción de audio en HTML5.
- **Conexión a Internet:**
  - Ancho de banda suficiente para streaming de audio (por ejemplo, conexión de banda ancha doméstica).  
  - Latencia razonable para evitar cortes.
- **Hardware:**
  - Ordenador con recursos suficientes para manejar varias pestañas sin que el audio se entrecorte (RAM y CPU decentes).
- **Configuración:**
  - Permitir la reproducción de audio en el sitio de Spotify.
  - Opcionalmente, iniciar sesión para guardar listas y preferencias.

---

## Problemas que resuelve y usos principales

- **Acceso legal y sencillo a un catálogo enorme de música y pódcasts.**  
- **Evita tener que almacenar archivos de música localmente**, ahorrando espacio en disco.  
- **Sincronización entre dispositivos:** lo que escuchas en el móvil, el PC o la web se mantiene en la misma cuenta.  
- **Descubrimiento de nueva música:** listas personalizadas, recomendaciones, radios basadas en artistas o canciones.  
- **Organización de la música:** creación de listas de reproducción, bibliotecas, favoritos.  
- **Uso social:** compartir canciones y listas con amigos, ver lo que escuchan otros usuarios (según configuración de privacidad).

En resumen, Spotify resuelve el problema de **cómo escuchar casi cualquier canción en cualquier momento y lugar**, sin tener que comprar o gestionar manualmente todos los archivos de audio.

---
