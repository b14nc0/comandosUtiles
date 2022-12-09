## Instalar apliaciones 

pkg install 

## FW
### Comprobar listado de bloqueados

ipfw table all list

## Servicios
### Parada y arranque

service servicio start

service servicio stop

### Habilitar servicios 

sysrc servicio="YES"

## Cambiar tarjeta virtual de estado BACKUP o MAESTRO

ifconfig vmx0 vhid 33 state BACKUP

ifconfig vmx0 vhid 33 state MAESTRO


