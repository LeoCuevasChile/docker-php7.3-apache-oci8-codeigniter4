# docker-php7.3-apache-oci8-codeigniter4
Imágen Docker con php7.3, Apache, oci8, oracle instant_client 12, composer y  codeigniter4


## Cómo usar

1. Crea la imágen con el comando:
```docker build -t "php73-apache-oci8-codeigniter4:0.1" . ```

2. Levanta el contenedor con el comando:
```docker run -d -v /tudirectorio:/var/www/html/ -p 9000:80 php73-apache-oci8-codeigniter4:0.1```

con la instrucción ```-v /tudirectorio:/var/www/html/``` creas el volumen en tu local en el directorio "/tudirectorio", puedes usar la ruta que desees. Aquí, podrás modificar tu codeigniter4.


¡Ya puedes conectar codeigniter 4 a tu base de datos ORACLE con oci-8!


