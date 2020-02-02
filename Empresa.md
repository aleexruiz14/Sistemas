Ejercicio Empresas
Contamos con dos redes distintas.
La Red A está formada por cuatro ordenadores con IP Fija, un servidor DNS y un router. A los ordenadores se les ha establecido como gateway la dirección IP del Router0 de manera manual.
Red A:
PC0: 192.168.15.3/24
PC1: 192.168.15.4/24
PC2: 192.168.15.5/24
PC3: 192.168.15.6/24
Servidor DNS: 192.168.15.1 dónde está incluida la página web www.empresa.com que nos lleva a una página de inicio en la que podemos elegir entre varios apartados: ropa, móviles y ordenadores.
Router0: 192.168.15.2/24 - 10.0.2.1/8
La Red B está formada por cuatro ordenadores DHCP, un servidor y un router. A los ordenadores se les ha establecido como gateway la dirección IP del Router1 mediante el servidor DHCP.
Red B:
PC4: DHCP
PC5: DHCP
PC6: DHCP
PC7: DHCP
Servidor: 192.168.10.1
Router1: 192.168.10.2/24 - 10.0.2.2/8