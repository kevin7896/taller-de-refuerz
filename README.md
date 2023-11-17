# taller-de-refuerz

1.¿Explicar brevemente el concepto de ReactJS y sus principales características.?
 R/ react se utiliza para crear todo tipo de apliciones la cual la hace un leguanje de desarrollo flexible 

 
las carateristicas 
 

las composicion de react es un acto de cambiar partes o elmentos para crear o formar todo al mismo tiempo ya que utilizamos las mismas funciones como las de javaScript los componentes funcionales como la funcion padre ya que se puede crear componetes hijos que permite al usuario proporsicionar dale mas elementos al base de datos de la aplicacion 

el class component 

react se trabaja bajo logica funcional con las cuales los componentes tomas mas fuerza ya permiten renderizar o retornar cualquier elemento 
ya que permite crear mas elememtos al crear extencion class hijo 

reactd-router-dom

al ReactDOM.render le pasamos un elemento de React
Dicho elemento se conforma de un componente el cual se le pasan ciertas propiedades como los componentes contiene otras carateristicas como el ciclo de vida y el state

los  composición nos indica que la salida de un componente puede estar compuesta de uno o mas componentes, los cuales pueden ser el mismo componente o diferentes.

La composición es realmente como se trabaja en React ya que como por lo regular solo llamamos a React DOM una única vez, montando el componente principal las cuales esta compuesto de sub componentes que cumplen con cierta funcionalidad en especifico como las extracion y division de componenetes 

2.¿Definir qué es un componente en ReactJS y mencionar los tipos de componentes que existen.?

R/ Los componentes permiten separar la interfaz de usuario en piezas independientes reutilizables y pensar en cada pieza de forma aislada

tipos de componentes 


Statefull Components
render
Stateless Components 
api
props
Smart Component
3.¿Qué es el Virtual DOM y cuál es su función en ReactJS? 

R/ el virtual DOM es una representacion que se almacena en la memoria del navegador y tambien se sincroniza con el dom real y esto pasa atravez de la bibloteca react dom 

4.¿Qué es JSX en ReactJS y porqué es importante? 

R/  es un componente que nos coneta con htlm,css,ect en un mismo archivo sin necidad de trabajar en un solo archivo 

5. ¿Qué es un Hook en ReactJS y cuál es su propósito?
   R/ el hook una funsion que nos permite usar react sin clase y tambien nos permite engachar otros archivos pero tambien esta probisto que los hook no funciona dentro las clase .

   6. Mencionar al menos tres tipos de Hooks en ReactJS y explicar brevemente para qué se utilizan.
      R/ useEffect : useEffect es como un ayudante externo que nos permiten sincronizar con otras propiedades y tambien es darle un efecto con tan solo darle un click y nos renderiza la pagina ect
      useContext : es conponente que nos permiten leer o sucribir un contexto entre otros, tambien es como un tipo de atajos que nos permite compartir datos a diferentes componentes.
      useReducer : useReducer es conponente que resive dos tipos de argumentos un reductor y un valor inicial, El reductor es una función que recibe el estado actual y una acción  y devuelve el nuevo estado , valor inicial es el estado inicial de la aplicación es como un array con dos elmentos el estado actual y una función dispatch el dispatch recibe una acción y tambien podemos utilizar el reductor para actualizar el estado

      7. ¿Cuáles son las reglas de uso para los Hooks en ReactJS?
         R/ Los hooks solo se pueden usar en componentes funcionales o custom hooks 
Los hooks solo se pueden llamar en el nivel superior de un componente. No se pueden llamar dentro de bucles, condicionales o funciones anidadas
 es son las dos reglas que yo recuerdo
8. Explicar qué es React Router DOM versión 6, para qué se utiliza y cuáles son sus principales componentes y Hooks.
 R/  React Router DOM es una librería que permite agregar enrutamiento a una aplicación web de React, Algunas ventajas de usar React Router DOM son :
    es que nos permite navegar mas fluido entre otra cosas.
   nos permite a nosotro como usuarios  cambiar la URL y al mismo tiempo actualizar la vista sin necesidad de una recarga completa de la página

    se puede ustilizar para definir las rutas tambien  permite agrupar varias rutas en un solo componente y proporciona una sintaxis más clara y concisa para definir las rutas de la aplicación.
     
   las principales son :  useParams y  useNavegate

   9. Explicar cómo se realiza la navegación entre diferentes páginas utilizando React Router DOM.
      R/ la navegacion utiliza atravez de una peticion que hace usuraios
      10. ¿Cómo se definen rutas en React Router DOM?
          R/ lo definimos atravez una carpeta jsx
          11. Describir cómo crear un proyecto ReactJS con Vite
              R/ primero lo hacemos atravez un de  npm create vite@latest <nombre-de-mi-proyecto> Una vez creado, dirígete al directorio creado y ejecuta el comando de instalacións despues ejecutamos el comando  cd <nombre-de-mi-proyecto> y despues npm install
              12. Describir cómo desplegar un JSON server en cualquier Hosting free o servicio en la nube gratuito de su elección
                  R/ los hacemos atravez de una api que nos permiteran almacenar dato echos por usario

                  13. Describir cómo desplegar una aplicación en cualquier Hosting de su elección.
                      R/ primero ponemos un codigo en visual despues nos vamos a una pagina que nos conectara a una red ect

