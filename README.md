# 🌸 Floristería Jardín Encantado - Web App

Una aplicación web responsiva diseñada como maqueta visual para la Floristería *Jardín Encantado*, enfocada únicamente en mostrar un producto floral en una interfaz estilizada.  
Este proyecto es estático y *no contiene funcionalidad interactiva*.

---

## 🎯 Objetivo

Desarrollar una *web estática simple y atractiva* que funcione como prototipo visual de una tienda online de flores.  
Pensada para mostrar el diseño y estructura general sin lógica funcional ni programación.

---

## 🛍️ Características principales

### 🌼 Catálogo de Productos

- Se muestra *un único producto predeterminado*.
- La interfaz incluye el nombre del producto, imagen, breve descripción y precio.
- El diseño está inspirado en jardines naturales o estilo bohemio.
- Todo el contenido es *puramente visual*.

### 🧺 Carrito de Compras

- ❌ *No se implementó* carrito de compras ni botones funcionales.
- Cualquier botón o enlace que aparezca es únicamente decorativo.

### 💳 Pago Electrónico

- ❌ *No existe* página de pago ni formulario.
- El flujo de compra no está desarrollado ni simulado.

---

## 🖼️ Interfaz

> El diseño fue adaptado a partir de un *template HTML gratuito, obtenido desde plataformas como **Creative Tim* o *Envato Elements*, y personalizado con temática floral.

---

## 🛠️ Tecnologías utilizadas

- *HTML5 / CSS3* exclusivamente
- Template HTML gratuito personalizado
- *Docker* para ejecución local
- *GitHub Pages* para publicación

---

## 🐳 Docker

### Construcción de la imagen:

``` bash
 docker build -t jardin-encantado .
```

### Desplegar el contenedor:

``` bash
docker run -it --rm -d -p 8080:80 --name web1 web .
```
