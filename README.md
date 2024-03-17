# Node-red
Error amb el MariaDb, 
Node_red persistencia de les dades

Guarda la configuracio a : /data/home/nodered/.node-red/

Problema: no es pot fer resize de els layout en dashboar.
Solucio: borrar els cookies de els ultims dies.

      ¿Cómo puedo eliminar las cookies de Microsoft Edge?
      Seleccione Configuración y, a continuación, haga clic en Privacidad y servicios.
      En Borrar datos de navegación, seleccione Elegir qué desea borrar.
      Marque Imágenes y archivos en caché, cookies y otros datos del sitio y, a continuación, seleccione Borrar ahora


Editar el nom del dispositius Zigbee.

      nano /opt/zigbee2mqtt/data/configuration.yaml
Refrescar el access a Alexa.

      http://192.168.1.186:3456
            nom : xbc@tinet.cat
            password: viscaTarraco25
Copia de la base de dades per el Xavi

      mysqldump -uroot -proot --databases IOT > ~/mysqldump.sql

El Telegram no funciona:
      Anar a telegram @botFather.
      escriu: /mybots
      
      Selecciona API-TOKEn y retorna el numero del Token
      Copia el numero
      1234366419:AAFSLxcywWylglb43iND2sJH774z-WI_FfA     


      Here is the token for bot Raspberry_Xavier 
      @Xavier_Banus_bot: 
      Nou Token
      1234366419:AAFSLxcywWylglb43iND2sJH774z-WI_FfA

      Copiarlo a la configuracio de telegram apartat Token:  
      
Instalacio de Mosquitto
      https://www.zigbee2mqtt.io/guide/installation/01_linux.html
