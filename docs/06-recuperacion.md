\# Plan de Recuperación ante Desastres (Disaster Recovery)



En caso de caída total del servidor principal, seguir estos pasos:



1\. \*\*Despliegue rápido:\*\* Levantar un nuevo servidor Ubuntu 22.04 LTS en el proveedor cloud.

2\. \*\*Restauración web:\*\* Volcar la copia de seguridad de `/var/www/pyme\_web` con rsync.

3\. \*\*Restauración BBDD:\*\* Importar el último `.sql` generado por mysqldump.

4\. \*\*DNS:\*\* Cambiar los registros DNS para que apunten a la nueva IP.

