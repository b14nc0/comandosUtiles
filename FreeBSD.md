# Instalar apliaciones 

pkg install 

# FW
## Comprobar listado de bloqueados

ipfw table all list

# Cambiar tarjeta virtual de estado BACKUP o MAESTRO

ifconfig vmx0 vhid 33 state BACKUP

ifconfig vmx0 vhid 33 state MAESTRO
