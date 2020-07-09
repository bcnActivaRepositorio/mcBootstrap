# CSS FRAMEWORKS

> bulma.io

> eskeleton

> foundation

> tail wind

> layoutit.com

> bootstrapstudio.io

> materialize

###### cdm

Bootstrap buscará el servidor más cercano para descargarse la librería de bootstrap.

SIEMPRE la maquetación de Bootstrap comienza con CONTENEDORES. Puede ser normal o fluid, pero siempre 

[container](https://www.w3schools.com/bootstrap4/bootstrap_containers.asp)

>   .container-sm 

sólo de móviles EN adelante

>   .container-md

de tablets horizontales EN adelante

si no colocamas nada boostrap inicia con sm

TODOS LOS ELEMENTOS DENTRO DE LA CLASS ROW SE TIENEN QUE REPARTIR ENTRE 12!!

Si al colocar los elementos 

     <div class="container">
        <div class="row">
            <h1 class="display-1 bg-dark col-6">Hola Mundo</h1>
            <p class="col-6"></p>
        </div>

    </div>

debemos considerar que la class="row" automaticamente crea 12 espacios
