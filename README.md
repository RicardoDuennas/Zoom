# ZoomImagen
Prototipo de visor con zoom para exploración de imágenes en alta resolución, desarrollado para el curso Automatización del pregrado Creación Digital UdeA (HTML + iframe). Desarrollado con IA.

Herramienta simple en HTML, CSS y JavaScript puro para visualizar detalles mediante zoom interactivo sobre una imagen.

---

## Funcionalidad

- Visualización de imagen en alta resolución  
- Zoom interactivo controlado con el cursor  
- Paneo (desplazamiento) al hacer zoom  
- Enfoque en detalles finos de la imagen  
- Tamaño base: 500x500 (responsive)  
- Integración mediante iframe  

---

## Estructura

- zoom.html: archivo principal del visor  

---

## Uso

### 1. Configurar imagen

Editar dentro de zoom.html:

    <img src="la_scapigliata.jpg">

Se pueden usar rutas locales o URLs.

---

### 2. Integrar con iframe

    <iframe 
      src="zoom.html" 
      width="520" 
      height="580" 
      style="border:none;">
    </iframe>

---

## Controles

- Scroll del mouse: acercar / alejar  
- Click + arrastrar: mover la imagen (paneo)  
- Doble click (opcional): resetear zoom  

---

## Características técnicas

- Sin dependencias externas  
- Compatible con navegadores modernos  
- Código encapsulado para evitar conflictos  
- Uso de transform: scale() para zoom  
- Uso de overflow: hidden para enmarcar la imagen  

---

## Uso pedagógico

Permite analizar detalles de una obra visual ampliando zonas específicas, facilitando el estudio de técnica, textura y composición.

---

## Imagen de referencia

Se utiliza La Scapigliata de Leonardo da Vinci, obra en dominio público, ideal para observar trazos, sfumato y detalles del proceso pictórico.
