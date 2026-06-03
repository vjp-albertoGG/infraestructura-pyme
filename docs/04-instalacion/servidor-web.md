\# Servidor Web y Balanceador



\## HAProxy

Instalar con `apt install haproxy`. Configurar para escuchar en el puerto 80 y balancear hacia los nodos Apache.



\## Apache

El servidor Apache pasará a escuchar en el puerto 8080 para recibir el tráfico limpio desde HAProxy.

