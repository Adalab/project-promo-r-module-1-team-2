# Proyecto 1. Web grupal

Ahoy! En este repositorio podreis encontrar los ficheros generados en la realización del **proyecto final del Módulo 1 - Promo Radia**. En él desarrollaremos nuestra **primera web colaborativa** creando una página con la información social de todos los miembros del equipo: 

- Alejandra Ameliach Hernández
- Laura González Calvo 
- Mª Elena Arocena López
- Sara Meixoeiro 
- Virginia Álvarez Aragón 

## Objetivos

Durante la realización del proyecto se marcaron los siguientes **objetivos** en el grupo de trabajo: 

- Consolidar el **aprendizaje de las tecnologías: HTML, CSS, diseño responsive, GitHub pages, Sass, grid, gulp**.
- Utilizar **control de versiones** en equipo para aprender las ventajas y conflictos que genera.
- Implementar **Scrum** como marco de referencia para el desarrollo del producto.
- **Mejorar la comunicación** entre los miembros del equipo.
- **Mejorar nuestras habilidades de comunicación en público** al presentar el trabajo y exponer el resultado como parte de los Sprint Reviews y la presentación final de proyecto.

## Especificaciones

El cliente [Adalab](https://adalab.es/) nos solicitó que desarrollásemos una página web con las siguientes **características**:
- Uso de **HTML y Sass.**
- Uso de **mediaqueries** y otras técnicas de **diseño responsive** para la adaptabilidad de la web en distintas pantallas. Tanto la página principal como la de contacto tienen un diseño establecido, al que debiamos ajustaros lo máximo posible:
    - **móvil, por debajo de 768px**
    - **tablet, desde 768px hasta 1200px**
    - **desktop, a partir de 1200px**
- Uso de **git** para el control de versiones del proyecto.
- Publicación del resultado en Internet usando **GitHub Pages**.

Así mismo, la web estará integrada por distintas páginas:
- una página **principal (Home)** con la información principal sobre el equipo.
- una página de **contacto** con un formulario para que puedan ponerse en contacto con nosotras.

Ambas páginas constarán de: 
- una **`header`**: aparecerá el nombre del equipo y un menú de navegación que debe mantenerse fijo en la parte superior de la ventana al hacer scroll. 

![image](https://user-images.githubusercontent.com/113302094/196042787-61d55df6-e8da-4a16-8e1c-d97671705feb.png)

- y un **`footer`**: aparecerá el copyright, otro menú y el logo de Adalab.

![image](https://user-images.githubusercontent.com/113302094/196042401-8f4e517a-d31e-4795-9807-f9665a042df1.png)

## Diseño

Nuestro cliente nos compartió el diseño que quería a través de [Zeplin](https://app.zeplin.io/). Atendiendo a las indicaciónes nuestra página web colaborativa se elaboraría siguendo un esquema en particular.  

### Página principal

En la página principal debe aparecer: 
- una **foto** del equipo
- la **frase (claim)** del equipo
- una sección **"equipo"** con la descripción del mismo con nuestras fortalezas y debilidades
- una sección de **"quiénes somos"** con información resumida de cada miembro del equipo: nombre, foto, breve bio y enlaces sociales (Twitter, LinkedIn, GitHub y correo)

![image](https://user-images.githubusercontent.com/113302094/196042762-3b2894e2-6bfc-4cae-8e6b-8fc71874f70b.png)

![image](https://user-images.githubusercontent.com/113302094/196042716-91767f24-3e50-4c55-acaa-afc6ad97e163.png)

![image](https://user-images.githubusercontent.com/113302094/196042738-53c91825-45d3-4541-b38e-a29391a694f0.png)

### Página de contacto

En la página de **contacto** podréis encontrar un formulario listo apra recoger la siguiente información: nombre completo, email, teléfono y mensaje. Además de el botón **enviar** está enlazado a [Formspree](https://formspree.io/) para poder mandar las respuestas a un servidor.

![image](https://user-images.githubusercontent.com/113302094/196043158-3509e584-c6a5-4a33-8205-c13d533a9180.png)

### Logo, iconos tipografía y paleta
 - El logo de **Adalab**. 
 - Los **iconos sociales** de [Font Awesome](https://fontawesome.com/)
 - Las **tipografías** usadas en el diseño son **Open Sans y Rubik**, disponibles en [Google Fonts](https://fonts.google.com/).
 - Paleta de **colores**.
 ```bash
Verde oscuro: #099d8d
Verde claro: #14d9c4
Blanco: #ffffff
Negro: #000000
Gris oscuro: #54585a
Gris claro: #b8b8b9
Gris de fondo: #f1f1f1
```
## Resultado final 

Puedes echar un vistazo a cómo quedó en Github Pages: https://beta.adalab.es/project-promo-r-module-1-team-2/ 

Esperamos que os guste. 

## Curiosidades de nuestro código

Hemos creado toda la estructura `HTML` de nuestra web en distintos `partials` aplicando los conocmientos aprendidos en la clase de Automatización de tareas:

![image](https://user-images.githubusercontent.com/113302094/196044079-6b72adb6-2bcf-43b4-8bbc-611a615d22a6.png)

Así mismo, hemos utilizado la misma lógica para los estilos, pasando todo nuestro código `CSS` a `Sass`:

![sass](https://user-images.githubusercontent.com/113302094/196044121-3a8d3752-f161-493d-98d6-5df869a79c8a.png)

Creamos un ´partial´para nuestras ´variables´:

![image](https://user-images.githubusercontent.com/113302094/196044164-cfd1461c-2c06-4dfc-b468-ef05fed374c1.png)

Y algunos `partials`dentro de otros:

![about-us-information](https://user-images.githubusercontent.com/113302094/196044221-7305b22b-0b08-4df2-87f1-42945db7577a.png)

![image](https://user-images.githubusercontent.com/113302094/196044471-5f5abbb3-59bf-45ff-9b7f-ff5ceae38a37.png)

También nos gustaría destacar el empleo de **BEM** y de las `mediaqueries`en nuestro proyecto: 


![team-sass](https://user-images.githubusercontent.com/113302094/196044283-48c07947-9db2-4b5d-a345-809d4c32fb0d.png)


## Feedback

Cualquier aportación será bien recibida.

¡Muchas gracias!
