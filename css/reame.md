* CSS: Cascading Style Sheet

.

Para llamar a un archivo que contenerá los estilos de mi pagina html, dentro de la etiqueta head:


<link rel="stylesheet" href="css/styles.css" />

rel: Indica que dicha página html va a contener una página de estilos.

href: Indica dónde está el archivo css, que será importado para aplicar los estilos definidos.

Se creará como ejemplo una página web index.html, en donde se añadirá estilo desde el <body> hacia abajo.

<h1 id="titulo">Hola Mundo!!!</h1>

La etiqueta h1 tiene un id el cual se aplicará un estilo espécifico en la hoja de estilos.

    #titulo{
        color:tomato
    }

Para darle un estilo puntual a un párrafo en html tenemos que asignar una clase:

<p class="texto1">chanchito feliz 1</p>

Un estilo podría se, todos los párrafos que tengan la clase "texto1" tendrán dicho estilo.

    p.texto1 {
        color:rgb(15, 7, 87);
    }

Para darle un estilo puntual a las etiquetas de un <div>:

<div>
    <h2>Soy un h2 dentro de un div</h2>
    <h3>Soy un h3 dentro de un div</h3>
    <p>Soy un parrafo dentro de un div</p>
</div>

Para dar un estilo puntual a los párafos de un <div>:

    div p {
        color: saddlebrown;
    }

Para dar un estilo puntual a las etiquetas h2 y h3 de un <div>:

    div h2, h3 {
        color: rgb(129, 17, 139);
    }

Si agrego un '*' e indico un estilo, todo lo que no esté con un estilo, tendrá lo definido según lo indicado:

    * {
        font-size: 16px;
        color:blue;
    }
En caso que un estilo anterior no haya sido definido su font-size, todos los estilos adoptarán es mismo tamaño, exceptuando los que ya estén prefedinidos.

Los comentarios en css se escriben:

    /* Esto es un comentario y el navegador no tomará este pedazo de texto */

1:05:00

