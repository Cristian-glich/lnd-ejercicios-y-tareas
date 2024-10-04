# Direccionamiento IP

El direccionamiento IP es un componente esencial en las redes de computadoras, permitiendo la identificación de dispositivos y la correcta entrega de datos. Las direcciones IP se dividen en clases y tienen rangos específicos según su uso.

## Clases de Direcciones IP

A continuación, se muestra una tabla con las clases de direcciones IP, sus rangos, máscaras de subred, rangos privados y el número de hosts disponibles por cada clase:

| Clase | Rango de Direcciones     | Máscara de Subred | Rango Privado         | Número de Hosts |
|-------|--------------------------|-------------------|-----------------------|-----------------|
| A     | 0.0.0.0 - 127.255.255.255| 255.0.0.0         | 10.0.0.0 - 10.255.255.255 | 16,777,214     |
| B     | 128.0.0.0 - 191.255.255.255 | 255.255.0.0     | 172.16.0.0 - 172.31.255.255 | 65,534        |
| C     | 192.0.0.0 - 223.255.255.255 | 255.255.255.0   | 192.168.0.0 - 192.168.255.255 | 254          |
| D     | 224.0.0.0 - 239.255.255.255 | No aplica       | No aplica             | Multicast (No asignado) |
| E     | 240.0.0.0 - 255.255.255.255 | No aplica       | No aplica             | Reservado (No asignado) |

## Descripción de las Clases

- **Clase A**: Usada principalmente para grandes redes, como empresas multinacionales. Soporta un gran número de dispositivos.
- **Clase B**: Orientada a redes medianas, como instituciones educativas o grandes empresas.
- **Clase C**: Utilizada para redes pequeñas, como oficinas o redes domésticas.
- **Clase D**: Reservada para multicast.
- **Clase E**: Reservada para usos futuros o experimentales.

Para más información sobre redes y direccionamiento IP, consulta la documentación y recursos adicionales disponibles en el material de estudio.
