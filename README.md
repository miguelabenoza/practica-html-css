# Práctica HTML-CSS. Creación de un portfolio
## Consideraciones generales

- No se permite el uso de librerías y frameworks externos como Bootstrap, Spectre.css o similares.
- Se tiene que crear una o más hojas de estilo CSS para aplicar el diseño deseado a la web.
- La página web debe visualizarse correctamente en las versiones actuales de Google Chrome, Mozilla Firefox y Microsoft Edge.
- No se puede usar JavaScript.


## Descripción de la práctica
Este proyecto tiene que cumplir los siguientes requisitos:

- Crear un header con barra de navegación, la cual tiene que tener enlaces a cada elemento del portfolio. Todos los links tendrán que tener el estado hover suavizado con una transición. Estos links no son necesarios en la versión móvil.
- Una sección con una descripción de nosotros y con nuestras habilidades como barras de progreso. Estas barras de progreso tienen que estar animadas con animaciones css.
- Banner que deberá tener una imagen de fondo. En pantallas móviles deberá ser otra. (Practicar media queries o Responsive images)
- Formulario de contacto con estos inputs. Todos ellos tienen que tener tanto los tipos correctos como la validación html de cada input.
    - Nombre - (campo requerido)
    - Apellidos - (campo requerido)
    - Teléfono - (campo requerido)
    - Unos radio input para responder a la pregunta "¿cómo me conociste?" - (requerido)
    - Valor de los **radio inputs**:
      - Universidad
      - Keepcoding kick-off
      - Colegio
      - Github
    - Tag de github (Usar regexp “^@[^\s]+” para la validación - @username)
    - Mensaje con más información del usuario (Textarea max 180 characters) - (campo requerido)
    - Acceso a la newsletter (Checkbox)
    - Botón de guardado
    - Botón de reset
- Footer con links a nuestras redes sociales. Importante tener en cuenta que son links a recursos externos.
- Nueva página que tenga un video que se reproduzca al entrar en la web y aparezca con una animación de fadeIn.
- Crear una nueva página con un grid con nuestros proyectos. Ver capturas para el diseño en caso de no quedar claro.
- README con toda la información necesaria para facilitar la forma de evaluar la práctica. https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/


### **Opcional**

- (Opcional) Podemos hacer un menú burger con solo CSS y un input checkbox, para no usar JS.
- (Opcional) Despliegue en Github pages
- (Opcional) Página de 404. Libre diseño
- (Opcional) Página 500. Libre diseño


### Detalles de la implementación
- La estructura de la web tiene que tener en cuenta las etiquetas de contenido semántico.
- Debéis incluir las media queries necesarias para que el diseño sea responsivo. Tiene que SER MOBILE FIRST!! Sino es un NO APTO.
- Las animaciones o interactividad propuesta deben realizarse exclusivamente mediante técnicas CSS sin el uso de librerías externas.
- Los apartados marcados como opcionales no son necesarios para obtener la calificación de APTA, pero se valorarán positivamente.
- Tiene que entregarse en a través de Github. No se valorará, pero un buen uso de commits será algo positivo. Una entrega en un solo commit, no es algo correcto.

