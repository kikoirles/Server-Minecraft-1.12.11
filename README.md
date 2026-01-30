# Server-Minecraft-1.12.11
Server Minecraft 1.12.11

## 1 Al servidor asignar ip estatica y la siguiente configuración de red

<img width="375" height="296" alt="image" src="https://github.com/user-attachments/assets/6596bd57-c8c0-48dc-8fcc-c3f76ce2da0f" />

java -Xms6G -Xmx6G -jar server.jar nogui (6G de RAM Reajustable)

También hay que cambiar parámetros en el archivo de (server.properties)

server-ip=192.168.2.182

server-port=25565

## 2 Necesitamos Java 17.0.12 o superior

https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html?utm_source=chatgpt.com

<img width="1470" height="265" alt="image" src="https://github.com/user-attachments/assets/4edda658-de1b-4668-8b18-e0366e3afd7a" />

## 3 Configuración del Administrador

El servidor ya deberia funcionar al ejecutar el (Start server.bat),pero a nivel de lan,

<img width="501" height="357" alt="image" src="https://github.com/user-attachments/assets/de719310-35d6-4e83-88e1-d1210cce30fc" />

## 4 Para que salga a extranet necesitamos abrir un túnel 

Utilizaremos en este caso 
 https://playit.gg/

### disclaimer-throwback.gl.joinmc.link 

(es el dominio que nos asigna la aplicación)

 <img width="1016" height="357" alt="image" src="https://github.com/user-attachments/assets/d2a0bb80-76d5-48d4-bbac-31072435abda" />
 <img width="914" height="816" alt="image" src="https://github.com/user-attachments/assets/1736612b-a336-403b-938b-e6ae81504e55" />

 Una vez configurado el túnel Minecraft Java,
 
 Cuando ejecutemos la aplicación descargada podremos ver los túneles que se estan ejecutado, podemos tener varios a la vez 

 <img width="982" height="513" alt="image" src="https://github.com/user-attachments/assets/0260c90d-266e-41a6-b8c2-c0772890194c" />

 ## 5 MUNDOS 

 Si borras las carpetas world, world_nether y world_the_end con el servidor apagado, al volver a iniciarlo:

<img width="134" height="61" alt="image" src="https://github.com/user-attachments/assets/9e500848-e207-403e-9be5-3145dd962258" />

El servidor genera mundos nuevos desde cero.

Overworld, Nether y End se regeneran completos

## 6 La carpeta de pluyings 

<img width="705" height="159" alt="image" src="https://github.com/user-attachments/assets/0be4367d-641c-443e-ae78-64ecfbf4d4da" />

Este servidor tiene los siguientes pluyings se pueden añadir mas

- AngelChest-1.39.4.jar  (cofre si mueres no se pierdan tus cosas)
- AuraSkills-2.3.10.jar  (jobs y skills trbajos)
- Back-1.8.6.jar         (back de un solo uso volver a donde has muerto)
- blocklocker-1.14.1.jar (privacidad de cofres por usuario)
- SetHome-6.2.3.jar      (homes establece 1 home(para tu casa)
- SilkSpawners_v2.jar    (mina toque de seda spawners)
- tpa-1.0.jar            (tpa entre jugadores) (no hay tpahere)




