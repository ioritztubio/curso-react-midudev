# Prueba técnica para Juniors de React en Live Coding

APIs:

    - Facts Random: https://catfact.ninja/fact
    - Imagen random: https://cataas.com/cat/says/hello

Recupera un hecho aleatorio de gatos y muestra una imagen de un gato con la primera palabra del hecho.

---

# Cómo crear un proyecto React desde Vanilla con Vite?

~~~
1.  npm create vite@latest
     project-name: nombreProy
     select framework: Vanilla
         variant: JS
~~~

Instalamos pluging de react:

~~~
2.  cd nombreProy
    npm intsall @vitejs/plugin-react -E
~~~

Una vez completada la instalación, iremos al package.json y podremos observar que no hay nada realacionado con React.
Para conseguir que aparezca necesitamos instalar las siguientes dependencias:

1. react: esta dependencia es la librería de React, la que contiene todo el tema de los hooks, etc.
2. react-dom: esta dependencia es la que tiene todo el tema de los bindings con el navegador.

Entonces, debemos ejecutar la siguiente línea para instalar las dependencias:

~~~
npm install react react-dom -E
~~~

Para finalizar debemos hacer la configuración de Vite. (vite.config.js)