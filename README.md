COMANDO PARA A INSTALAÇÂO 

      wget https://raw.githubusercontent.com/conexaoscript/renovar/main/install-sudominio.sh && chmod 777 install-sudominio.sh && ./install-sudominio.sh

DEPOIS ADICIONE SEU SUBDOMINIO, SUBSTITUINDO (ServerName) e (ServerAlias)

      cd /etc/apache2/sites-available


      nano renovar.conf


      sudo service apache2 restart
