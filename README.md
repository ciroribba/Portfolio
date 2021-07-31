# Portfolio Personal

▢ Este es un ejemplo de portfolio para un desarrollador web

▢ Está desarrollado con codigos de html, css y js. Cuenta con funcionalidades adicionales usando JQuery. 

▢ Presenta un diseño responsive en base al uso de @media query css. Como ejemplo puede ver el siguiente código:

```
/*Start media queries*/
@media screen and (max-width: 768px){
    body{
        background: url("images/sitebg2.jpg") no-repeat center fixed ;
        background-size: cover;
    }
    .landing-text h1{
        font-size: 15rem;;
    }
    .landing-text h6{
        font-size: 1.7rem;
    }
    .nav-list{
        flex-direction: column;
    }
 }
```
▢ Y como punto extra que suma al proyecto son las animaciones, usando @keyframes css. Como por ejemplo:

```
/*Start animations*/
@keyframes pulse{
    0%{
        box-shadow: 0 0 0 0 rgba(109, 0, 25,0.99);
    }
    70%{
        box-shadow: 0 0 0 2rem rgba(109, 0, 25,0);
    }
    100%{
        box-shadow: 0 0 0 0 rgba(109, 0, 25,0);
    }
}
/*End animations*/
```

▢ Puedes usarlo como plantilla, simplemente lo descargas, modificas el contenido necesario y ejecutas haciendo click en el index.html

▢ A continuación te dejo link a un demo del proyecto. [DEMO](https://ciroribba.github.io/portfolio/)

▢ Deberias ver algo como lo siguiente: 

![prtfolio](https://github.com/ciroribba/portfolio/blob/main/demo3.png?raw=true "Portfolio")

❤ Espero lo disfrutes 😄
