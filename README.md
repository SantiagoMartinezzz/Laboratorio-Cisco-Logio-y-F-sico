# Laboratorio-Cisco-Logio-y-F-sico
Investigar Dispositivos en un Armario de Cableado Conectar Dispositivos Finales a Dispositivos de Red Instalar un Router de Respaldo Configuración de un Nombre de Host

- Para el siguiente Laboratorio lo principal es tener un conocimiento básico de lo que es el escenario físico y lógico
- Hay dos formas de ver una red en Packet Tracer. El modo lógico muestra cómo se conectan los dispositivos en la red. El modo físico le muestra dónde se encuentran los dispositivos en la red. Esta actividad se abre y se centra en el modo Físico.

Modo Físico 
- Para responder la primera pregunta debemos entrar al modo físico con shift + p y ver que ciudades están conectadas en este caso Seward y Warrenton
- Tambien podemos observar que el nombre del cable es Alaska United West

Modo Lógico
- Para entrar en este modo usas el shift + l para ver ahora si lo interesante
- Vemos que los dispositivos inalámbricos que no están conectados son el smartphone y Home_Laptop ya que son representados por no tener una linea continua 

Modo Físico
- Volviendo nuevamente ahora entramos en Seward dándole click y podemos ver que en la SewardAlaska encontramos el Branch office igualmente si nos vamos a Warrenton y entramos veremos Data center  y teleworker

Segunda Parte
- En este paso, navegará hasta el armario de Branch Office cableado Seward. También conectará una PC a un conmutador mediante un cable Ethernet.
- Como anteriormente lo había mencionado podemos ir a Seward y entrar en Branch office y de ahí en wiring Closet
- Una vez dentro vamos a conectar PC_1 FastEthernet0  a un puerto vacío FastEthernet en ALS2
- Simplemente vamos a buscar un cable en el apartado de arriba para red el normal Rj45 y lo conectaremos en el switch ALS2 por el puerto FasthEthernet0

Tercera Parte 
- Conectaremos una PC a un switch o Router Cisco mediante un cable de consola.
- para ello En el modo físico, conecte el puerto RS232 PC_1 al puerto de la consola en el Edge_Router.
- Buscaremos el cable de consola para asegurarnos de hacer la conexión exitosa si no lo conoces pasando el mouse por los cables veras los nombres luego lo conectamos en el puerto RS232 y directo a la consola en el Edge_Router

Cuarta Parte
- Instálelo Backup_Router en el Rack y enciéndalo.
- En este paso, instalará y encenderá un nuevo enrutador en el rack. También se conectará a este dispositivo a través de la consola USB con un cable USB.
- El Backup_Router lo encontraremos abajo del wireless_router simplemente lo seleccionamos y lo llevamos al rack para poder entrar y encenderlo
- ahora tenemos que conectar un cable USB al Router usamos el click derecho inspect rear y hacemos zoom para conectarlo en el puerto es uno muy pequeño asi que es facil confundirse y ya de ahí al puerto USB dl laptop

Quinta Parte
- En este paso, configurará el nombre de host en Backup_Router
- Desktop (Escritorio) y haga clic en Terminal. La configuración del Terminal ya está definida con la configuración de puerto necesaria y debe usarse con su configuración predeterminada. Haga clic en OK para iniciar la conexión de terminales. simplemente démosle no en lugar de yes enter y listo
- Entonces iniciaremos con un enable en la terminal podemos utilizar sus respectivas abreviaciones que son en luego un configure terminal tambien con su abreviación config t  y hacemos Hostname Edge_Router_Backup finalizamos con un end

  Pregunta de Reflexion
  - Además de los cables Ethernet y de la consola, ¿qué otras formas de conectar dispositivos
    De forma inalámbrica (Wi-Fi), mediante cables de fibra óptica (para conexiones de larga distancia) y cables coaxiales.
    - Cuál es la diferencia entre el armario de cableado, la mesa y el estante?
      El armario es la habitación que contiene la red; el estante (Rack) es la estructura metálica donde se montan los routers y switches; y la mesa es para colocar dispositivos finales como laptops y PCs de uso directo.
      -En qué se diferencia el modo lógico del modo físico
      El modo lógico muestra la topología de la red, es decir, cómo fluyen los datos y cómo se configuran las direcciones IP de forma virtual. El modo físico muestra la distribución real en el mundo real, incluyendo las ciudades, las distancias de los cables, los edificios y cómo están organizados los equipos en los racks."


  
  
