# DNS
## Creación de un DNS en VirtualBox
Crear un servidor DNS con las siguientes zonas:

sitioa.com
www web con información de java.
ftp servidor ftp.
sitiob.net
www web con información de C#
sitioc.net.
www web con información de Oracle.
Crear una máquina virtual con un entorno gráfico. Esta accede a los sitios web.
El servidor DNS será RAID 0.
Los Servidores web ftp será RAID 5.
## Ejercicio 1:
### Servidor DNS
RAID 0
![](https://github.com/mafercar/DNS-y-Apache-en-linux/blob/master/particiones.PNG)
Configuración router DNS /etc/network/interfaces
![](https://github.com/mafercar/DNS-y-Apache-en-linux/blob/master/dns1.PNG)
Zonas - Archivos named.conf.local
![](https://github.com/mafercar/DNS-y-Apache-en-linux/blob/master/dns2.PNG)
Sitioa.com
![](https://github.com/mafercar/DNS-y-Apache-en-linux/blob/master/dns3.PNG)
Sitiob.net
![](https://github.com/mafercar/DNS-y-Apache-en-linux/blob/master/dns4.PNG)
Sitioc.net
![](https://github.com/mafercar/DNS-y-Apache-en-linux/blob/master/dns5.PNG)
Resolución inversa
![](https://github.com/mafercar/DNS-y-Apache-en-linux/blob/master/dns6.PNG)
Archivo named.conf.options
![](https://github.com/mafercar/DNS-y-Apache-en-linux/blob/master/dns7.PNG)
### Servidor Web
RAID 5
![](https://github.com/mafercar/DNS-y-Apache-en-linux/blob/master/web1.PNG)
Configuración router web /etc/network/interfaces
![](https://github.com/mafercar/DNS-y-Apache-en-linux/blob/master/web2.PNG)
Comprobación sitioa.com HTML, .conf 
![](https://github.com/mafercar/DNS-y-Apache-en-linux/blob/master/web3.PNG)
![](https://github.com/mafercar/DNS-y-Apache-en-linux/blob/master/web4.PNG)
![](https://github.com/mafercar/DNS-y-Apache-en-linux/blob/master/web5.PNG)
Comprobación sitiob.net HTML, .conf
![](https://github.com/mafercar/DNS-y-Apache-en-linux/blob/master/web6.PNG)
![](https://github.com/mafercar/DNS-y-Apache-en-linux/blob/master/web7.PNG)
![](https://github.com/mafercar/DNS-y-Apache-en-linux/blob/master/web8.PNG)
Comprobación sitioc.net HTML, .conf, comprobación
![](https://github.com/mafercar/DNS-y-Apache-en-linux/blob/master/web9.PNG)
![](https://github.com/mafercar/DNS-y-Apache-en-linux/blob/master/web10.PNG)
![](https://github.com/mafercar/DNS-y-Apache-en-linux/blob/master/web11.PNG)
```sadasdas```
