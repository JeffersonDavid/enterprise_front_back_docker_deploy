# Utiliza la imagen oficial de MySQL 8
FROM mysql:8.0

# Establece las variables de entorno para la base de datos
ENV MYSQL_DATABASE=enterprise_backend

# Establece una contraseña para el usuario root
ENV MYSQL_ROOT_PASSWORD=root_password

# Copia el archivo de configuración personalizado
COPY ./bbdd/my.cnf /etc/mysql/conf.d/

# Expone el puerto en el que MySQL estará escuchando (por defecto es 3306)
EXPOSE 3306
