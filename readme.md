
#NIVEL 1

##Crear Proyecto en Laravel

1.  Crear el proyecto en Laravel 5.5 (PHP \>= 7.0)

    -   composer create-project --prefer-dist laravel/laravel blog "5.5.\*"

2.  Comprobar que version del framework se ha instalado

    -   php artisan -V


##Detallar los mensajes de error

1.  Ir a la siguiente ruta:

    -   config/app.php

2.  Habilitar el valor de `APP_DEBUG`


##Generar la llave de la aplicación

1.  Renombrar el archivo `env.example` y ponerle `.env`

2.  Ejecutar el siguiente comando:

    -   php artisan key:generate


##Iniciar servidor de Desarrollo

    - php artisan serve


##QUE SON Y COMO SE UTILIZAN LAS RUTAS

-   Las rutas en Laravel estan definidas en el archivo:

    -   routes/web.php

-   Las vistas en Laravel estan definidas en el siguiente directorio:

    -   resources/views
