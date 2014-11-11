<b>Training: AppCompat 21 / Material Design - RecyclerView + Cards</b>

Este proyecto consiste de un Activity que posee un listado. Dentro de cada "row" del listado, tenemos un ícono y un texto, definidos por un layout. Para manejar los datos del listado, se usa como ListAdapter, un ArrayAdapter. Al hacer click en algún elemento, se muestra un toast con el elemento seleccionado.

Se quiere "migrar" el proyecto para soportar widgets de Material Design, puntualmente RecyclerView y Cards.

Para esto:

1) Hacer que el proyecto soporte AppCompat, modificando lo que corresponda en build.gradle y themes: 

        compileSdkVersion 21
        buildToolsVersion "21.0.0"
        
        minSdkVersion 14
        targetSdkVersion 21
        
        compile 'com.android.support:appcompat-v7:21.+'

2) Reemplazar ListView por RecyclerView. 

3) Al hacer click sobre un elemento de la lista, que nos lleve a una CardView con la información más detallada del item (en este caso, pondremos los mismos datos, pero con una imagen por default).

