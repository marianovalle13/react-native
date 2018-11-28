![](https://cdn.filestackcontent.com/NLhmEQbVQUWSrfIFaXPh)
## Que es ***React Native***?
- **React Native** es un framework desarrollado por Facebook que permite desarrollar apps nativas iOS y Android usando Javascript.
  - Lleva como un “puente” donde su función es la de traducir el código React Native en Objective-C, para el caso de iOS, y Java en Android. 
  - Permite a los programadores web poder desarrollar apps nativas sin tener que aprender nuevos lenguajes de programación muy específicos para cada una de las plataformas.
  -  La sintaxis de React Native es bastante clara y sencilla, además de heredar el mismo diseño que React, aportando flexibilidad y reaprovechamiento en el código. 

## Caracteristicas de ***React Native***
**React Native** posee diferentes caracteristicas que lo definen:
### Virtual DOM
- React mantiene un virtual DOM propio, en lugar de confiar solamente en el DOM del navegador. Esto deja a la biblioteca determinar qué partes del DOM han cambiado comparando contenidos entre la versión nueva y la almacenada en el virtual DOM, y utilizando el resultado para determinar cómo actualizar eficientemente el DOM del navegador.
### Las propiedades
- Las propiedades (props) pueden definirse como los atributos de configuración para dicho componente. Éstas son recibidas desde un nivel superior, normalmente al realizar la instancia del componente y por definición son inmutables.
### El Estado
- El estado de un componente se define como una representación del mismo en un momento concreto, es decir, una instantánea del propio componente. Existen dos tipos de componentes con y sin estado, denominados statefull y stateless.
### Ciclos de vida
- El ciclo de vida es serie de estados por los cuales pasan los componentes statefull a lo largo de su existencia. Se pueden clasificar en tres etapas de montaje o inicialización, actualización y destrucción.
### JSX
- React utiliza una sintaxis parecida a HTML, llamada JSX. No es necesaria para utilizar React, sin embargo, hace el código más legible, y escribirlo es una experiencia similar a HTML.

 ---

## *ALGO DE HISTORIA*: **React Native**
---> React fue creada por Jordan Walke, un ingeniero de software en Facebook, inspirado por los problemas que tenía la compañía con el mantenimiento del código de los anuncios dentro de su plataforma. Enfocado en la experiencia del usuario y la eficiencia para sus programadores, influenciado por XHP (un marco de componentes de HTML para PHP), nace el prototipo ReactJS.
### Antecedentes e inicios **(2010- 2013)**
    2010: Facebook introduce XHP a su stack PHP como código abierto.
    2011: Walke crea un prototipo para ReactJS
    2012: Facebook adquiere Instagram, Pete Hunt desarrolló React para hacerlo de código abierto.
    2013: Facebook lanza React como un código abierto.
        - React y JSX están disponibles en aplicaciones de Python
### Expansión y popularidad **(2014- 2016)**
    2014: Conferencias ReactJS world tour, enfocadas en construir una comunidad. 
         - React Developer Tools es agregado como una extensión para Google Chrome.
    2015: Netflix anuncia que usará React para su desarrollo de interfaz de usuario.
         - Se publica la primera versión de React Native. React Native es público y de libre acceso para iOS, y está disponible en Github. 
         - La primera versión de React Native para Android es publicada.
    2016: React.js Conf 2016 en San Francisco. ReactEurope 2016. Se publica el sistema de Códigos de Error para React.


Biografia:[https://es.wikipedia.org/wiki/React]
 ### ***Sabias que...***
> React al ser una librería de código abierto, puede ser modificado por cualquier persona. 
> Permite que cualquier usuario con conocimientos sea capaz de sugerir cambios o mejoras a la librería. 
> De todas maneras, en un principio todas estas modificaciones no eran fáciles de encontrar puesto que estas se encontraban dispersas por diversas páginas, por lo que *Facebook* decidió crear un repositorio en **GitHub**.
> Gracias a esta idea, se podría facilitar la organización de la comunidad y almacenar las modificaciones hechas tanto por la comunidad como por el grupo de desarrollo de Facebook.

---

## Que necesitas para poder utilizar React Native?
*Sencillo...*



* Instalar **Xcode**: Para poder simular la app iOS (es necesario el software de desarrollo de Apple).
    - https://developer.apple.com/xcode/
* Instalar **node**: Node se encarga de proporcionar una manera fácil para construir programas de red escalables.

        bew install node
        
* Instalar **React Native**: una vez instalado node, ya es posible instalar *React native*

        npm install -g react-native-cli
---
## Una vez instalado todo, podemos iniciar **React Native**

        react-native init nombre_de_la_app

## Estructura de archivos:
- Al haber iniciado nuestra app en react native, con "**nombre_de_la_app**", contiene diferentes ficheros para desarrollar la app:
    * [__test__]: son para testing.
    * **android**: carpeta que contiene archivos nativos.
    * **ios**: carpeta que contiene archivos nativos.
    * **index.android.js**: se haya el codigo fuente en javascript.
    * **index.ios.js**: se haya el codigo fuente en javascript.
        *   --> ***AppRegistry***: para registrar la app en el proyecto. 
        *   --> ***StyleSheet***: para dar estilos a las vistas usando pseudo css.(abstracción similar a css)
        *   --> ***Text***: es la etiqueta para insertar texto.
        *   --> ***View***: para declarar una vista.




***CONOCE UN POCO MAS SOBRE REACT NATIVE!!!***
    > https://clouddistrict.com/blog-dev/que-es-react-native/
    > https://octuweb.com/nuestra-primera-app-nativa-react-native/
    > https://facebook.github.io/react-native/
 
 **¡He aqui unos ejemplos de aplicaciones que han sido desarrolladas con React Native!**   
![](https://www.paradigmadigital.com/wp-content/uploads/2018/06/app-nativas-react-native-1.png)

**ALUMNO**: Mariano Valle
**CURSO**: 7°"C"
