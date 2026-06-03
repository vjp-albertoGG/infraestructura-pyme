## Configuración de firewall con UFW
- Permitir SSH solo desde IP de la oficina: `ufw allow from 192.168.1.0/24 to any port 22`
- Permitir tráfico web: `ufw allow 80/tcp` y `ufw allow 443/tcp`
- Activar firewall por defecto: `ufw default deny incoming`
- Habilitar UFW: `ufw enable`