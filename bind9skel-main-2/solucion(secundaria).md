# 1.3 Instalación de zonas secundarias.

1. Tomaremos a máquina darthsidious, e configuraremola para ser servidor secundario, tanto da zona primaria de resolución directa como de resolución inversa. Captura os ficheiros de configuración en ambalas dúas máquinas. 

- Darthvader:

![captura1](imaxes/captura1.png)

- Darthsidious:

![captura2](imaxes/captura2.png)

Fai unha captura onde se vexa o reinicio da máquina darthsidious, no que se vexa no log dos dous equipos e que se fixo a transferencia de zona.

- Reinicio de darthsidious:
![captura3](imaxes/captura3.png)

- Logs:

    -Darthvader:
        ![captura4](imaxes/captura4.png)
    -Darthsidious:
        ![captura5](imaxes/captura5.png)


2. Engade un rexistro tipo A (Chewbacca 192.168.0.28) na zona de resolución directa e tamén na de resolución inversa.  Fai unha captura no momento do reinicio do equipo darthvader, no que se vexa o log dos dous equipos e que se amose que se fixo a transferencia de zona. Adxunta tamén unha captura do ficheiro de zona no servidor secundario.

- Añadimos Chewbacca:

-Zona directa:

![captura6](imaxes/Captura6.png)

-Zona inversa:

![captura7](imaxes/Captura7.png)

- Logs:

-Darthvader:

![captura8](imaxes/Captura8.png)

-Darthsidious:

![captura9](imaxes/Captura9.png)

-Zona inversa en darthsidious:

![captura10](imaxes/Captura10.png)

3. Comproba que o servidor secundario pode resolver ese nome.

![captura11](imaxes/Captura11.png)

![captura12](imaxes/Captura12.png)


4. Fai os cambios necesarios para que as trasferencias se fagan de forma segura empregando chaves.  Repite as capturas e vídeos do punto 2, engadindo o rexistro r2d2 (192.168.0.29)

- Creación da chave:

![captura13](imaxes/Captura13.png)

- Configuración:

-Zona directa:

![captura14](imaxes/Captura14.png)

-Zona inversa:

![captura15](imaxes/Captura15.png)

- logs:

-Darthvader:

![captura16](imaxes/Captura16.png)

-Darthsidious:

![captura17](imaxes/Captura17.png)

- Comprobación de r2d2 en darthsidious:

![captura18](imaxes/Captura18.png)

![captura19](imaxes/Captura19.png)
