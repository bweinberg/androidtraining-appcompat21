<b>Training: Material Design - RecyclerView + Cards</b>

Este proyecto consiste de un Activity que posee un listado. Dentro de cada "row" del listado, tenemos un texto, definidos por un layout. Para manejar los datos del listado, se usa como ListAdapter, un ArrayAdapter.
 
Se quiere "migrar" el proyecto para soportar widgets de Material Design, puntualmente RecyclerView y Cards.

Para esto:

1) Hacer que el proyecto soporte ambos, modificando lo que corresponda en build.gradle: 

BUILD.GRADLE:

    dependencies {
            ...
            compile 'com.android.support:cardview-v7:21.0.+'
            compile 'com.android.support:recyclerview-v7:21.0.+'
    }
        

2) Reemplazar ListView por RecyclerView y hacer que cada "row" del RecyclerView sea un CardView.

